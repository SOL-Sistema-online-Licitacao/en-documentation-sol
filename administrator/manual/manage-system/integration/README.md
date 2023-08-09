# Integration

In the "Integration" tab, accessible through the main menu at the top of the page, you can see a list of all the Integrations in the System, edit their information and force the integration.&#x20;

SOL verifies the information of the system that was integrated and updates the information on Membership, Agreement and Cost Items in the database.

{% hint style="info" %}
Integration frequency:&#x20;

To schedule the task of updating the database in the integration, a cron expression is used to create the recurrence.&#x20;

[https://crontab.cronhub.io/](https://crontab.cronhub.io/)
{% endhint %}

<figure><img src="../../../../.gitbook/assets/inte.png" alt=""><figcaption></figcaption></figure>

## How to edit an integration?&#x20;

To edit an integration, just click on the edit available next to the integration name in the list on the "Integrations" tab.&#x20;

<figure><img src="../../../../.gitbook/assets/inte-upd.png" alt=""><figcaption></figcaption></figure>

Then make the necessary changes using valid endpoints and tokens, then click "Save". The changes will be saved and the integration will update.

## How to force integration?&#x20;

To force an integration, you must first edit the integration using the required endpoints and tokens and then click on force integration, thus the status will change to "In progress".
