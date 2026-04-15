# meta-ads-dashboard

> an automated workflow to extract daily account balances from meta ads, delivering reports directly to whatsApp.

## Features

* **Automated Daily Extraction:** connects to the facebook graph API to pull up-to-date daily spend and account balance data.
* **WhatsApp Integration:** delivers the daily report directly to your phone or a specific whatsApp group via Waha.
* **Self-Hosted Infrastructure:** runs completely on a self-hosted Ubuntu VPS environment, keeping data processing under your control.
* **Low-Code Maintenance:** built entirely within n8n, allowing for easy visual adjustments to the workflow.

* ## Tech Stack

* **Automation Platform:** [n8n](https://n8n.io/)
* **Data Source:** Facebook Graph API (Meta Ads)
* **Messaging API:** [Waha](https://waha.devlike.pro/) (WhatsApp HTTP API)
* **Hosting / OS:** Ubuntu VPS

## Prerequisites

* an **Ubuntu VPS** with **n8n** and **Waha** installed and running.
* a meta developer account with an app configured to generate a graph API `ACCESS_TOKEN`.
* your meta ad account ID 
* an active whatsApp session connected via Waha.
