# Creating an invite

Send a customer an invite to appraise their own vehicle. The customer receives a link by email and completes the inspection on their own device using the ClearInspect Client app.

{% hint style="info" %}
If you do not see **Invite** in the sidebar, customer self-inspection is not enabled for your retailer - your setup is inspection-only, and this page does not apply.
{% endhint %}

## Before you start

* Have the customer's first name, last name and email address to hand.
* Have the vehicle's registration number (VRM) or VIN.

![](../../.gitbook/assets/WD05-1.png)

## Send an invite

1. Click **Invite** in the sidebar.
2. If you manage more than one retailer, select it from the **Select Dealer** dropdown.
3. Enter the customer's **First name** and **Email** (required). **Last name** and **Phone** are optional.
4. Select the **email language** for the invite (defaults to your profile language).
5. Under **Enter Vehicle Details**, enter the **registration number** (or **VIN**, as prompted for your market).
6. Click **Fetch vehicle data**.

   The vehicle details appear for you to check before sending. For JLR vehicles, extra data appears under **JLR API Integration**, and more is retrieved automatically during the inspection itself.

   ![](../../.gitbook/assets/WD05-2.png)

7. If the lookup returns nothing, click **Enter manually** - the **Make** and **Model** fields then appear for you to fill in.
8. If asked, record the **vehicle condition** and **odometer reading**.
9. Click **Send Invite**.

A confirmation appears. The customer receives an email within a minute or two. Invites are usually valid for 48 hours, but the exact validity depends on your retailer setup - the email shows the expiry time.


{% hint style="info" %}
If a vehicle lookup returns no data, check that you have entered the correct registration or VIN. You can still send the invite by entering vehicle details manually.
{% endhint %}

## What the customer receives

The customer email contains:

* A unique link to begin their self-appraisal (one-time use).
* The expiry time.
* Step-by-step instructions and contact details for the inviting retailer.
* A link to download the ClearInspect Client app.

## Vehicle data returned by lookup

The fields returned differ for JLR and non-JLR vehicles.

| Field | JLR vehicles | Other vehicles |
|---|---|---|
| Make | Yes | Yes |
| Model | Yes | Yes |
| Model year | Yes | Yes |
| Number of seats | Yes | Yes |
| First registration date | Yes | Yes |
| Chassis number | Yes | Yes |
| Engine number | Yes | - |
| Engine size | Yes | - |
| Fuel type | Yes | Yes |
| Exterior colour | Yes | Yes |
| Interior colour | Yes | - |
| Optional extras | Yes | - |
| Service history | Yes | - |
| Service recalls | Yes | - |
| Bodystyle | Yes | Yes |
