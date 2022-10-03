# Paastis – Enhance your PaaS experience!

## ☁️ WTF is PaaS ?!

Platform as a service (PaaS) is a cloud computing model where a third-party provider delivers hardware and software tools to users over the internet.
Usually, these tools are needed for application development. 
A PaaS provider hosts the hardware and software on its own infrastructure. 
As a result, PaaS frees developers from having to install in-house hardware and software to develop or run a new application.

## 🚀 Some leading PaaS providers

- [Heroku](https://heroku.com): the first one
- [Render](https://render.com): the new world challenger
- [Scalingo](https://scalingo.com): the Eureopean Heroku
- [Clever Cloud](https://clever-cloud): Europe-based PaaS company
- [Platform.sh](https://platform.sh/): yet another cool French PaaS

Without forgetting Google, Microsoft, Azure & cie.

## 🍺 WTF is Paastis ?!

[Paastis.dev](paastis.dev) is a digital platform that helps teams to manage their PaaS applications.

## ❤️ The promises of Paastis

- convenient
- economical
- ecological

## 🏛 Architecture

- `paastis-engine`: HTTP proxy + registry of running apps (in-memory or Redis-based) + idle apps scheduler (CRON) + system API server (native Node.js HTTP server)
- `paastis-website`: official documentation website (Docusaurus 2.0)
- `paastis-console` (private): SaaS webapp for managed cloud-hosting
