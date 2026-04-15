# meta-ads-dashboard

> an automated workflow to extract daily account balances from meta ads, delivering reports directly to whatsapp.

## features

* **automated daily extraction:** connects to the facebook graph api to pull up-to-date daily spend and account balance data.
* **whatsapp integration:** delivers the daily report directly to your phone or a specific whatsapp group via waha.
* **self-hosted infrastructure:** runs completely on a self-hosted ubuntu vps environment, keeping data processing under your control.
* **low-code maintenance:** built entirely within n8n, allowing for easy visual adjustments to the workflow.

## tech stack

* **automation platform:** [n8n](https://n8n.io/)
* **data source:** facebook graph api (meta ads)
* **messaging api:** [waha](https://waha.devlike.pro/) (whatsapp http api)
* **hosting / os:** ubuntu vps

## prerequisites

* an **ubuntu vps** with **n8n** and **waha** installed and running.
* a meta developer account with an app configured to generate a graph api `access_token`.
* your meta ad account id 
* an active whatsapp session connected via waha.
