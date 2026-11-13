# Cannot Log In to the Mobile App

### Getting Started

If a driver cannot log in to the TourSolver mobile app, the cause is usually the user ID, the password, or the settings of the user in the TourSolver back office. This page helps the driver and the back office administrator find and fix the cause.

* **Before you begin**:
  * The driver has installed the TourSolver app from the **iOS App Store** or the **Google Play Store**. See [Login](login.md).
  * The administrator can sign in to the TourSolver back office with access to **Configuration**.

### Feature Explanations with Benefits

* **Mobile access**: The setting of the user that allows the connection to the mobile app. When it is enabled, the user can connect with the login and the password registered in the back office.
* **Password (mobile app)**: The password that the driver types in the app. The administrator sets it in the back office.
* **Mobile app user**: The link between a deliverer and the user who drives it. The routes of the deliverer are sent to this user.
* **Agencies**: The user and the deliverer must belong to the same agency, so that the user can see the routes of the deliverer.

### Common Tasks with Detailed Steps

* **Check the user ID and the password (driver)**
  1. In the **User ID field**, type the login of your TourSolver account exactly as it was given to you, usually an email address.
  2. In the **Password field**, type your password, and then tap the **eye icon** to check it.
  3. Check the capital letters, and make sure that there is no space before or after the user ID or the password.
  4. Tap **Login**.

  ⚠️ **Warning**: If the message "**Incorrect username or password**" appears, contact your TourSolver back office administrator. Only the administrator can change your password.

* **Check the mobile access of the user (administrator)**
  1. In the TourSolver back office, go to **Configuration** > **Roles & Profiles** > **Manage users**.
  2. Click the **Edit** icon of the user.
  3. On the **Access** tab, check that the user is **Enabled**, and that **Mobile access** is enabled: "The user can connect to the mobile app".
  4. Check or reset the **Password (mobile app)**, and then click **Save**. Give the new password to the driver.
  5. Check **Last connection on** to see when the user last connected.

![](<../.gitbook/assets/AppLaunch-CannotLogIn_MobileAccess.jpg>)

* **Link the user to the deliverer (administrator)**
  1. In the TourSolver back office, go to **My deliverers**.
  2. Click the **Edit** icon of the deliverer, and then click the **Vehicle** tab.
  3. In **Mobile app user**, select the user of the driver. If it shows **Unknown user**, the routes of this deliverer are not sent to any driver.
  4. Click **Save**.

![](<../.gitbook/assets/AppLaunch-CannotLogIn_MobileAppUser.jpg>)

* **Check the agencies (administrator)**
  1. In **Configuration** > **Roles & Profiles** > **Manage users**, check the **Agencies** column of the user.
  2. Check that the deliverer belongs to one of these agencies, on the **General** tab of the deliverer in **My deliverers**.
  3. If the agencies do not match, change the agencies of the user on the **Agencies** tab, and then click **Save**.

![](<../.gitbook/assets/AppLaunch-CannotLogIn_UsersAgencies.jpg>)

### Troubleshooting

* **"Incorrect username or password"**: Check the capital letters and the spaces, and then ask the administrator to check the **Password (mobile app)**.
* **The user can log in but sees no route**: Check that the user is the **Mobile app user** of the deliverer, and that they belong to the same agency. See also [Share a Tour with the Mobile App](https://nomadia-docs.gitbook.io/products/operationsandroutemanagement/operationsandroutemanagement-shareatourwiththemobileapp).
* **The app does not open or closes at login**: Update the TourSolver app from the **App Store** or **Google Play**, and check that the device meets the system requirements: **Android 8 to 14**, or **iOS 15.5 or later**.

### Productivity Tips

* 💡 **Same login as the back office**: The user ID of the app is the login of the user in the back office. Copy it from **Manage users** to avoid typos.
* 💡 **Keep the app up to date**: Turn on the automatic updates of the TourSolver app on the device, so that the driver always has the latest version.
