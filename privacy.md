# Louder privacy policy

_Last updated: 7 October 2026 (version 1.0.1)_

Louder is an alarm clock app. It collects nothing about you.

- **No data collection.** Louder has no accounts, analytics, ads or tracking.
- **No internet access.** The app does not request the Android internet permission, so it cannot send anything anywhere.
- **What stays on your phone.** Your alarms (time, repeat days, label and sound) are stored only on your device, in the app's private storage. Uninstalling Louder deletes them.
- **No backups.** Louder opts out of Android cloud backup, so your alarms are not copied to any server.

## Permissions and why Louder needs them

| Permission | Why |
|---|---|
| Alarms & reminders (`USE_EXACT_ALARM`, `SCHEDULE_EXACT_ALARM` on Android 12) | To ring at exactly the time you set. |
| Notifications | To show the ringing alarm. |
| Full-screen alerts (`USE_FULL_SCREEN_INTENT`) | To show the alarm screen over the lock screen. |
| Foreground service (media playback) | To keep playing the alarm sound until you stop it. |
| Run at startup (`RECEIVE_BOOT_COMPLETED`) | To set your alarms again after the phone restarts. |
| Vibration and wake lock | To vibrate and keep the phone awake while the alarm rings. |
| Do Not Disturb access (optional, Android 14 and below) | If Do Not Disturb is set to block alarms, Louder switches it to "alarms only" while an alarm rings and puts your setting back afterwards. |

While an alarm rings, Louder raises the **alarm** volume to maximum and sets it back to your
previous level when the alarm ends. It does not change any other volume.

## Contact

Questions: open an issue at https://github.com/ciphercon/louder-legal/issues
