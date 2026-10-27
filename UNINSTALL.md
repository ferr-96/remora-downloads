# Remove Remora Host

Use the matching **Uninstall-Remora** package from the release. Moving the Host app to Trash alone leaves its background service and microphone driver behind.

1. Finish calls and save your work. Revoke approved phones/laptops in **Remora Host → Devices…**, or remove this Mac from those clients.
2. Quit Remora Host from its menu bar menu. Run the uninstaller and approve macOS Installer yourself. It refuses to continue while the Host is running.
3. The uninstaller removes the Host, its login item, Login Service and launch-service files, Remora Microphone, matching authorization right and installer receipts. Removing the microphone briefly restarts the Mac's sound service. Installer's **Window → Installer Log** lists the paths it removed.

The uninstaller deliberately retains this user's Remora settings and sign-in, so reinstalling may restore them. It also leaves the separate Remora for Mac client app installed. Do not describe this as deleting every account or every user's data.

For removal of your retained Host data as well, after revoking devices and uninstalling, remove these Remora-specific items from your own account:

- `~/Library/Application Support/Remora`
- `~/Library/Preferences/com.miroteg.remora.host.plist`
- The Remora Host items beginning `com.miroteg.remora.host` in **Keychain Access**.

Inspect each item before deleting it; do not remove unrelated Keychain entries. Remove any remaining Remora Host entry from **System Settings → General → Login Items**. For a shared Mac, each user's retained data is separate. Contact support if you need help identifying an item.
