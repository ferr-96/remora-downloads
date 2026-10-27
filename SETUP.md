# Set up Remora Host

1. On your Apple silicon Mac running macOS 14 or later, open the Remora installer from the release. Finish any active call first. Follow macOS Installer and enter your administrator password in the system prompt yourself.
2. Open **Applications → Remora Host**. It runs in the menu bar. The installer includes the Host, Login Service and Remora Microphone; no separate Login Service download is needed.
3. Open **Setup…** from the Remora Host menu. Follow each permission button to System Settings and enable the permissions that Setup requests, including Screen Recording and Accessibility. Approve audio capture when using sound. If macOS offers **Quit & Reopen**, accept it. macOS wording varies by version.
4. On a new Mac, use the **Sign in to Remora** window to initialize the account with an email, a password of at least eight characters, and the password again. This verifier is stored on this Mac. Use the same email and password in the iPhone/iPad app. Complete any device-approval prompt on the Mac.
5. For internet access, apply your assigned relay enrollment code in **Settings → Relay → Relay code → Apply**. Obtain enrollment through the setup channel that supplied your access. App Review receives its scoped code privately in the review notes. Never post a relay code in a public issue or screenshot. Confirm that Relay shows connected before testing from another network.
6. Restart the Mac when convenient to activate a newly installed microphone driver. Save your work first. If FileVault is enabled, arrange a local unlock after the restart.
7. Connect from the phone/tablet and verify that the Mac appears, a harmless click and text entry work, and your selected sound/microphone options behave as expected. Test optional call features only with accounts and people you have permission to use.

## Optional: connect after normal logout

Use the Mac's own keyboard and mouse to set this up; Remora does not accept its own remote input for enabling this feature.

1. Sign in to Remora Host and approve your client device.
2. Open **Settings → Account** and enable **Allow connecting after logout**. Enter the Remora password, then approve the separate macOS administrator prompt yourself.
3. Use **Open permissions…** and enable Screen Recording and Accessibility for **Remora Login Agent**. The Login Agent is included with Remora Host.
4. Check that the feature reports enabled. Test a normal logout and remote sign-in while you have a local recovery method available. Test your own network and Mac before depending on unattended access.

This feature does not bypass FileVault startup protection. With FileVault enabled, a restart can require someone to unlock the Mac locally before remote software is available. Signing out of Remora Host is different from logging out of macOS: signing out of Remora Host turns its remote access off.

## Updates

Use the release's matching Host package. Keep the Mac's existing permission and account settings unless the app explicitly asks you to finish setup. Re-check the feature status after installation. Do not assume an installer completing proves the remote connection works.
