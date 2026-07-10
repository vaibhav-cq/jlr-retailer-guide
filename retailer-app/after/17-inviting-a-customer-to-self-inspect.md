# Inviting a customer to self-inspect

You can invite a customer to appraise their own vehicle using the ClearInspect Client app.

{% hint style="info" %}
If you do not see **Invite** in the sidebar of the web dashboard, customer self-inspection is not enabled for your retailer - your setup is inspection-only, and this page does not apply.
{% endhint %}

{% hint style="info" %}
Customer invites are sent from the web dashboard, not from the Retailer app. For the full walkthrough, see [Creating an invite](../../web-dashboard/inviting-customers/05-creating-an-invite.md) and [Tracking invites](../../web-dashboard/inviting-customers/06-tracking-invites.md) on the web dashboard.
{% endhint %}

## Send an invite

1. Go to https://jlr-uat.web.app on a desktop browser and sign in.
2. Open **Invite (Customer Inspection)** in the sidebar.
3. If you manage more than one retailer, choose it from the **Select Dealer** dropdown.
4. Enter the customer's **first name** and **email** (required). Last name and phone are optional.
5. Choose the email language (defaults to yours).
6. Enter the vehicle registration number (or VIN, as prompted for your market) and click **Fetch vehicle data**.
7. If the lookup returns nothing, click **Enter manually** and fill in the **Make** and **Model**.
8. Click **Send Invite**.

The invite goes to the client by email and links to the ClearInspect Client app. Invites are usually valid for 48 hours, but the exact validity depends on your retailer setup - the email shows the expiry time.

![](../../.gitbook/assets/WD05-1.png)

## Track your invites

Open the **Metrics** tab on the Invite page. For each invite the table shows:

* The customer **name** and **invite date**.
* The vehicle **registration**, **VIN** and **make & model**.
* The **inspection status** - Pending, In progress or Completed.

Completed inspections can be marked as reviewed. Open a row's **Details** to view the inspection.

![](../../.gitbook/assets/WD06-1.png)
