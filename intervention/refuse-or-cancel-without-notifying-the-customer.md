# Refuse or Cancel a Visit Without Notifying the Customer

### Getting Started

A driver can refuse a visit that they cannot perform, or cancel a visit that they already accepted. This page explains how to do it without sending the "Upcoming arrival" notification to the customer, and what to check when a mission cannot be edited in the app.

* **Before you begin**:
  * The driver can open the visit in the app. See [Cancel](cancel.md).
  * The administrator can sign in to the TourSolver back office with access to **Configuration**.

### Feature Explanations with Benefits

* **Decline deliveries**: Allows the driver to refuse a visit before accepting it. The customer does not receive the "Upcoming arrival" notification for a refused visit.
* **Cancel accepted deliveries**: Allows the driver to cancel a visit after accepting it. The "Upcoming arrival" notification may already have been sent.
* **Enable the acceptance step**: The step where the driver accepts the visit. It is required when the "Upcoming arrival" notification to the customer is enabled.
* **Mission edit configuration**: Defines which missions a user can edit in the app.

### Common Tasks with Detailed Steps

* **Allow the drivers to refuse a visit (administrator)**
  1. In the TourSolver back office, go to **Configuration** > **Fulfillment and client experience** > **Configure the mobile app**.
  2. Click **DELIVERIES**.
  3. Turn on **Decline deliveries**.
  4. If needed, turn on **Cancel accepted deliveries**.

![](<../.gitbook/assets/Intervention-Refuse_DeliveriesSettings.jpg>)

  ⚠️ **Warning**: **Enable the acceptance step** cannot be turned off while the "Outgoing email/SMS of upcoming arrival to the customer" is turned on. To turn it off, first uncheck this notification in **Configure outgoing messages** > **Upcoming arrival**.

* **Refuse a visit without notifying the customer (driver)**
  1. Open the visit from the **Dashboard**.
  2. **Refuse** the visit before you accept it.

  💡 **Tip**: Refuse the visit instead of accepting it and then cancelling it. When you accept a visit, the customer can receive the "Upcoming arrival" notification.

* **Cancel an accepted visit (driver)**
  1. Open the visit, and then tap the cancel button.
  2. Confirm the cancellation. See [Cancel](cancel.md).

### Troubleshooting

* **The driver cannot refuse a visit**: Check that **Decline deliveries** is turned on in **Configure the mobile app** > **DELIVERIES**.
* **The customer received the "Upcoming arrival" notification**: The driver accepted the visit before cancelling it. Ask the driver to refuse the visits instead.
* **The mission cannot be edited in the app**:
  * Check the edit rights of the user in the order givers settings of the back office.
  * Check that the mission type is compatible with the mission edit configuration of the user. If none of the mission edit configurations is compatible with the mission type, TourSolver shows "None of your mission edit configurations are compatible with the selected mission types.", and the missions of this type are not editable.

### Productivity Tips

* 💡 **Refuse early**: Refuse the visits that you cannot perform as soon as you see them, so that the planner can assign them to another driver.
* 💡 **Ask your administrator**: The refuse and cancel options are set in the back office. If you do not see them in the app, contact your administrator.
