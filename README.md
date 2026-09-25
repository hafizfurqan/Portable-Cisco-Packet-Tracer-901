# Cisco Packet Tracer 9.0.1 (Portable)

This repository provides a portable version of **Cisco Packet Tracer 9.0.1** with custom updated device icons.

### Visual Preview of App
`CiscoPT.png`

Please note that the software is **not patched** or modified. Instead, the login/auth screen has been bypassed by routing it through the application's built-in proxy settings. 

---

## 📥 How to Download and Run

Because this project contains over 6,500 files, the full portable structure is bundled into a single compressed archive.

1. Look at the right-hand sidebar of this page and click on **Releases**.
2. Download the `.7z` (or `.zip`) archive.
3. Extract the contents to any folder on your computer.
4. Run the main executable to start the application.

---

## 🔄 How to Revert / Remove the Proxy (Restore Normal Login)

If you want to disable the built-in proxy bypass and log in normally with your Cisco Networking Academy account, follow these steps:

1. Open Cisco Packet Tracer.
2. Navigate to the top menu and select **Options** > **Preferences**.
3. Click on the **Miscellaneous** tab.
4. Locate the **Proxy Settings** section.
5. Change the **Proxy Type** from `Socks 5` to **`Auto`**.
6. Click **Apply Proxy**
7. **Restart** the application.

Upon restarting, the software will prompt you with the standard Cisco login screen again.

### Revert Back to Guest mode

If you want to revert it back to guest mode, delete newly created Data Folder and it will revert back to offline mode.

### Visual Reference
For a step-by-step visual layout of these options, please refer to the image located at the root of this repository:
👉 **`CPT-Revert.png`**
