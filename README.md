# User Guide: How to Use the Application

Welcome to the user guide for our file sharing application. This tool allows you to seamlessly send and receive files and folders across local and remote networks. Below you will find step-by-step instructions on how to set up, send, and receive files, along with important security notes.

---

## 🔒 Security Settings & Encryption

Located in the **bottom-left corner**, you will find an encryption checkbox (enabled by default).

* **Encrypted Connection (Recommended):** If enabled, the application creates a secure, encrypted connection (if supported by your device). Once connected, a quick security verification check takes place between the sender and the receiver to ensure the connection has not been intercepted by a malicious third party.
* **Unencrypted Connection:** If disabled, data travels in plain text. **Only disable encryption if your device does not support it AND you are on a trusted home network. Never disable encryption over public or external networks!**

---

## 📤 How to Send Files or Folders

1. **Select Content:** Use the central **Drag & Drop area** or the selection button to choose files and/or folders.
   * *Note on Folders:* Sent folders are automatically zipped to preserve their directory hierarchy. The receiver will get a `.zip` file that must be extracted.
2. **Choose the Recipient:**
   * **Option A (Manual IP):** In the top bar, enter the IP address of the recipient device to connect.
   * **Option B (Auto-Discovery):** In the bottom bar, select from the list of active devices on the local network currently requesting to receive files.
3. **No Limits:** There are **no limits** on file sizes or the number of files you can send. Depending on the size, it may take some time—thank you for your patience!

---

## 📥 How to Receive Files

1. Click the **Receive** button at the top of the interface.
2. The application will display two IP addresses:
   * **LAN IP:** Share this IP if both devices are connected to the **same local network**.
   * **WAN IP:** Share this IP if the devices are on **different networks** (over the internet).

### 🌐 Port Forwarding Requirement for WAN (Remote Transfers)
To receive files from outside your local network (WAN), you must configure **Port Forwarding** on your router:
* **Port:** `37773`
* **Protocol:** `TCP`
* **Target:** Forward to the receiving device's local IP address.
* *Without port forwarding, firewalls and NAT will block incoming connections from outside your network. A quick Google search for your router model will show you how simple this is to set up.*

3. **Saving Files:** Received files are saved to your chosen folder or, by default, to your device’s **Downloads** folder.

---

## ☕ Support the Developer

If you find this application helpful and would like to support its ongoing development, click the **Donate** button in the **top-right corner**. Even a small contribution makes a huge difference!

---

## ⚖️ License & Terms of Use

* **Personal Use:** This application is free for personal use.
* **Prohibition of Tampering:** Modifying, reverse engineering, or tampering with the application is strictly prohibited by law and goes against the fair-use spirit of providing this tool for free. Please respect the license agreement found in the project's repository.
* **Commercial Use & Inquiries:** If you are a company or intend to use this software for commercial purposes, please contact the developer first.

---

## 📧 Contact & Feedback

For questions, feedback, or commercial licensing queries, feel free to reach out via email:
📩 **valbald02@gmail.com**

*Thank you for using the application!*
