# Route Not Received in the Mobile App

### Getting Started

When the planner shares a route from the TourSolver back office, the route appears in the mobile app of the driver. If the route does not appear, the cause is usually the link between the deliverer and the mobile user, the agencies, or the app that needs to be refreshed.

* **Before you begin**:
  * The driver can log in to the app. See [Cannot Log In to the Mobile App](cannot-log-in-to-the-mobile-app.md).
  * The planner has shared the route with **Export** > **Share with the mobile app**. See [Share a Tour with the Mobile App](https://nomadia-docs.gitbook.io/products/operationsandroutemanagement/operationsandroutemanagement-shareatourwiththemobileapp).

### Feature Explanations with Benefits

* **Mobile app user**: The user who receives the routes of a deliverer. Each deliverer must be linked to a mobile user.
* **Share confirmation**: After the planner clicks **Send**, TourSolver shows how many deliveries are shared and how many emails are sent to the mobile users. It confirms that the route was sent.
* **Refresh**: Reloads the routes in the app, without waiting for the automatic synchronization.

### Common Tasks with Detailed Steps

* **Refresh the routes in the app (driver)**
  1. In the app, tap the **three dots** at the top of the screen.
  2. Tap **Refresh**.
  3. Check the date: the route appears on the day for which it was shared.

* **Check the share confirmation (planner)**
  1. In the back office, share the route again with **Export** > **Share with the mobile app**.
  2. After you click **Send**, read the confirmation: the number of deliveries shared and the number of emails sent.
  3. If no email is sent, the deliverer is not linked to a mobile user. Link it as described below.

* **Link the deliverer to a mobile user (planner)**

  If a deliverer is not linked to a mobile user, TourSolver does not share the route and shows, for example, "You cannot share your routes because some (11/11/2026 Truck10, 11/11/2026 Truck13) are not mapped with any mobile user."

![](<../.gitbook/assets/AppLaunch-RouteNotReceived_NotMapped.jpg>)

  1. In the back office, go to **My deliverers**.
  2. Click the **Edit** icon of the deliverer, and then click the **Vehicle** tab.
  3. In **Mobile app user**, select the user of the driver, and then click **Save**.

![](<../.gitbook/assets/AppLaunch-CannotLogIn_MobileAppUser.jpg>)

  4. Share the route again.

* **Check the agencies (planner)**
  1. In **Configuration** > **Roles & Profiles** > **Manage users**, check the **Agencies** of the mobile user.
  2. Check that the deliverer belongs to one of these agencies, on the **General** tab of the deliverer in **My deliverers**.
  3. If needed, add the agency of the deliverer to the user on the **Agencies** tab, and then click **Save**.

![](<../.gitbook/assets/AppLaunch-CannotLogIn_UsersAgencies.jpg>)

### Troubleshooting

* **"You cannot share your routes because some … are not mapped with any mobile user"**: Link each deliverer of the routes to a mobile user, and then share again.
* **The confirmation shows 0 emails sent**: Check the **Mobile app user** of the deliverers and the email address of the mobile users.
* **The route was shared but does not appear**: Refresh the app with the **three dots** > **Refresh**, check the date of the route, and check that the user and the deliverer belong to the same agency.

### Productivity Tips

* 💡 **Link once, share every day**: Link each deliverer to its mobile user once. The next shared routes then reach the driver automatically.
* 💡 **Check the counters**: Always read the share confirmation. The number of emails sent tells you how many drivers received the route.
