# Troubleshooting and FAQ

## I cannot sign in

* Sign in with the email address your administrator registered for you, then enter the one-time passcode (OTP) sent to that email. The code is numeric and must be the right length.
* No OTP? Check your spam folder, wait a moment, then use **Resend** after the cooldown. Confirm your email address is correct.
* If you see an access error, contact your retailer admin to confirm your account has been provisioned in ClearInspect, or contact the ClearInspect support team if the issue persists.

## The customer did not receive the invite email

* Check that you entered the correct email address when creating the invite.
* Ask the customer to check their spam or junk folder.
* Check the invite's **Inspection Status** in the invite table. If the customer cannot find the email, create a new invite with the correct address.

## The invite has expired

Invite links are valid for 48 hours by default. If the customer has not completed their appraisal and the link has expired:

1. Go to **Invite** in the sidebar.
2. Send a new invite with the same details.

The customer will receive a fresh link.

## The vehicle lookup returned no data

* Check that you entered the registration number or VIN correctly.
* Some vehicles, particularly older models or grey imports, may not be in the lookup database. Enter the vehicle details manually and continue.

## The JLR vehicle data is missing or incomplete

The **JLR API Integration** data is retrieved automatically during the inspection using the VIN. It does not appear for:

* Non-JLR vehicles.
* Inspections where the VIN was not confirmed during the flow.
* Any lookup where the VIN does not return a result.

If the data is missing for a JLR vehicle, contact your ClearInspect support team.
