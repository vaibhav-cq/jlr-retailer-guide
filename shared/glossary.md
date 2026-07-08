# Glossary

This glossary explains the terms used across the ClearInspect Retailer app and Web Dashboard documentation.

**ClearInspect**
The name of the JLR vehicle inspection platform. It includes the Retailer app, the web dashboard, and the Client app.

**Retailer app**
The ClearInspect mobile app used by JLR retailer staff to carry out in-person vehicle inspections.

**Web dashboard**
The browser-based tool for retailer staff at [https://jlr-uat.web.app](https://jlr-uat.web.app). Used to invite customers, track inspections, and view, edit and share reports.

**Client app**
The ClearInspect app used by JLR customers to self-appraise their own vehicle. It is invite-only.

**Invite**
A secure link sent by a retailer to a customer, giving them access to begin their self-appraisal. Invites expire after 48 hours by default.

**ForgeRock SSO**
The JLR single sign-on system. This is planned as the long-term sign-in method for the web dashboard and the Retailer app but is not yet available. For now, the web dashboard uses email, password and an email OTP, and the Retailer app uses a User ID and password.

**OTP (one-time passcode)**
A short numeric code sent to your email to confirm your identity when signing in to the web dashboard.

**Terms & Conditions**
The terms you accept in a pop-up the first time you sign in to the Retailer app or the web dashboard.

**Guided flow**
The step-by-step image capture process in the Retailer app. The app shows you which part of the vehicle to photograph next.

**Overlay**
The on-screen outline that shows how to frame each photo. It turns green when the framing is correct.

**Real-time checks**
Live checks that confirm the correct part is in frame and the image is clear before it is captured.

**Auto-capture**
When the overlay is green, the app takes the photo automatically (used for exterior images).

**Manual override (Manual toggle)**
A toggle, top right of the capture screen, that switches off real-time validation so you can take a photo with the shutter button.

**Shutter button**
The on-screen button used to take a photo manually (used for interior images, tyres and other manual captures).

**Instrument cluster**
The dashboard display behind the steering wheel. ClearInspect reads the odometer, fuel or charge level and warning lights from a photo of it.

**Checklist**
The set of questions completed during an inspection. Some answers are pre-filled from detected values.

**Damage / damage review (Damage Confirmation)**
The stage where you review the damage the app has detected, and add, edit or confirm it. The overview legend marks each section as Clean, Damages or Unrecognized; the tyre view uses Clean, Mismatch/Damages and Not available.

**Repair method**
How a damage will be fixed: Repair, Repaint, Smart Repair, Polish or Replace.

**Smart Repair**
A repair method for minor scratches and small dents on eligible panels.

**Repair estimate**
The estimated cost of repairs, based on confirmed damage and the chosen repair methods. Shown in the report if enabled for your retailer.

**Assessment table**
The panel-by-panel breakdown of confirmed damage and repair methods in the inspection report. It is separate from the repair estimate table. On repeat inspections of the same licence plate, the Comparison section appears in its place.

**Comparison**
A report section shown when a vehicle with the same licence plate is inspected again. It compares the current inspection against the previous one, with filters for New damages, Existing Damage, Repaired, Clear and Unrecognized.

**Change log**
An audit trail recorded for each report, shown below the checklist section, listing edits with the editor name and timestamp. It is read-only; retention follows your organisation's policy.

**Tyre tread**
The depth of the grooves on a tyre. Enter the inner, middle and outer readings for each tyre on the Enter Tyre Tread screen.

**Tyre spec / mismatch**
The manufacturer's recommended tyre specification. A mismatch means a tyre does not meet that spec, or the tyres on the vehicle do not match each other.

**Alloy**
The wheel itself, as opposed to the tyre. Alloy damage is recorded in the tyre section.

**VIN**
Vehicle Identification Number, the unique 17-character identifier for a vehicle. Used for JLR Topix lookups.

**VRM**
Vehicle Registration Mark. The number plate number used to look up vehicle data.

**Topix**
The JLR internal system that provides vehicle data by VIN, including service history, recalls and optional extras. Data is retrieved automatically during the inspection.

**Sign-off**
Confirming and completing an inspection at the end of the process.

**Inspection Summary**
The metric card on the web dashboard home screen showing the total and counts of retailer-conducted inspections by status: Complete, In Progress and Incomplete.

**Draw Mode / Zoom Mode**
A toggle in damage review. Zoom Mode zooms in on the image; Draw Mode lets you draw around a damage to mark it.

**Damage Area**
The Small or Large size choice made when adding a damage manually.

**Offline Mode**
A toggle on the Vehicle details screen. Turn it on before starting an inspection with no internet connection.

**Faults List**
A toggle on the damage review overview that lists the recorded faults.

**Bodystyle**
The body shape of the vehicle, for example hatchback, saloon or SUV.

**Interior configuration**
The interior layout, such as left or right hand drive and the number of seat rows. It affects which interior photos are requested.
