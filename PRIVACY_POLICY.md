## Remind Me!: Privacy Policy

Welcome to the Remind Me! app for Android!

As an avid Android user myself, I take privacy very seriously.
I know how irritating it is when apps collect your data without your knowledge.

I hereby state, to the best of my knowledge and belief, that I have not programmed this app to collect any personally identifiable information. All data (app preferences (like theme, etc.) and alarms) created by the you (the user) is stored on your device only, and can be simply erased by clearing the app's data or uninstalling it.

### Explanation of permissions requested in the app
<br/>

| Permission | Why it is required |
| :---: | --- |
| `android.permission.USE_EXACT_ALARM` | This is required to schedule an exact alarm, and was introduced in Android 12. You, as a user, or the system, can revoke this permission at any time from Settings. Revoking this permission will, lead to crash and the app may be no loger be functional as expected. |
| `android.permission.RECEIVE_BOOT_COMPLETED` | When your device restarts, all alarms set in the system are lost. This permission enables the app to receive a message from the system once the system has rebooted and you have unlocked your device the first time. When this message is received, the app creates a service to set all the active alarms in the system.|
| 'android.permission.POST_NOTIFICATIONS' | This is required to notify the user regarding the reminder configured . The permission can be revoked by the user by going to App Settings, by doing so, the app won't be able to notify about the alarm/reminder which is the main usage of the app.
 <hr style="border:1px solid gray">

If you find any security vulnerability that has been inadvertently caused by me, or have any question regarding how the app protectes your privacy, please send me an email or post a discussion on GitHub, and I will surely try to fix it/help you.

Yours sincerely,  
Sudeep Reddy Borlapu  
Hyderabad, India.
sudeep.borlapu@gmail.com
