**# PureGym-Apple-Wallet
Create a Wallet Pass on iPhone
**

1. WalletWallet: https://www.walletwallet.dev
2. Wallet Shortcut: https://www.icloud.com/shortcuts/8c6c3c72e21b4379abdf44127b9a86c0
3. Start Shortcut: https://www.icloud.com/shortcuts/dde2a221d74e4205a3da90595d94522f

Step 1 – Install the shortcuts

First, install both Apple Shortcuts:

1. Open the Wallet Shortcut.
2. Tap Add Shortcut.
3. Open the Start Shortcut.
4. Tap Add Shortcut.

You should now have both shortcuts in your Shortcuts app.

Step 2 – Get your WalletWallet API key

1. Visit https://www.walletwallet.dev
2. Create a free account.
3. Open your dashboard.
4. Find your API key.
5. Copy your API key somewhere safe.

IMPORTANT: Treat your API key like a password. Never share it or upload it to GitHub.

Step 3 – Configure the Wallet Shortcut

1. Open the Apple Shortcuts app.
2. Find your Wallet Shortcut (Generate PureGym).
3. Tap to edit it.
4. Find the WalletWallet API Key field.
5. Paste your API key.
6. Enter your PureGym email address.
7. Enter your PureGym PIN.

Make sure your details are entered correctly.

Step 4 – Generate your Wallet pass

1. Open your Start Shortcut.
2. Run it.
3. It should ask for your API key.
4. It should open a WalletWallet webpage.
5. Select Add to Wallet.
6. Tap Add to add the pass to Apple Wallet.

Your pass may initially appear with a false QR code. This is normal at this stage.

Step 5 – Get your Pass Number

Now you need to connect your Wallet pass to the Generate PureGym shortcut.

1. Open the WalletWallet page again.
2. Go to the URL tab.
3. Find the URL field.
4. Copy everything after /p/ in the URL.

For example, if the URL looks like:

https://example.com/p/ABC123456

You only need:

ABC123456

5. Open Shortcuts.
6. Find Generate PureGym.
7. Tap to edit it.
8. Find the Pass Number field.
9. Replace its existing value with the code you just copied.

Step 6 – Set up automatic updates

Now let’s make sure your QR code refreshes automatically.

1. Open the Generate Shortcut editor.
2. Go to Automation.
3. Tap the on button.
4. Select Time of Day.
6. Set it to repeat Daily.
8. Set the automation to run automatically, if prompted.

Recommended: Choose a time that isn’t midnight. I recommend avoiding 12:00 AM because it can sometimes cause delays.

Step 7 – Test everything

Almost finished!

1. Open your Generate PureGym shortcut.
2. Press the play button to run it manually.
3. Wait for it to finish.
4. Open Apple Wallet.
5. Check that your PureGym pass has updated.

Your shortcut should now automatically refresh your pass at the time you selected.

🎉 You’re done!

You should now have your PureGym membership QR code available directly in Apple Wallet.

No need to open the PureGym app every time you visit the gym.

Your scheduled automation will run the shortcut to refresh the pass.

⸻


* Check the shortcut actions before entering your login details.
* This is an unofficial community project and is not affiliated with or endorsed by PureGym.
* WalletWallet pricing and API limits may change. Check its website for current terms.

Troubleshooting

Problem	What to try
Pass has no QR code	Run Generate PureGym manually.
Pass doesn’t update	Check your API key and Pass Number.
Shortcut fails	Check your PureGym email and PIN.
Automation doesn’t run	Check your daily automation settings.
Wallet pass is missing	Run Start again and add the pass to Wallet.

Enjoy your PureGym membership in Apple Wallet! 💪
