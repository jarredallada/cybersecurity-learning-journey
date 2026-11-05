<p align="center">
  <img src="https://www.kali.org/images/kali-dragon-icon.svg" width="120" alt="Kali Linux Logo"/>
</p><p align="center">
  <strong>Installing Kali NetHunter on Android Devices</strong>
</p><p align="center">
  A step-by-step reference for setting up Kali NetHunter on rooted and non-rooted Android devices.
</p>

---

<h2>📋 Requirements</h2>

<h3>📱 Rooted Devices</h3>

<table>
  <tr>
    <th>Requirements</th>
    <th>Description</th>
  </tr>
  <tr>
    <td>Android Device</td>
    <td>An Android smartphone with root access.</td>
  </tr>
  <tr>
    <td>Internet Connection</td>
    <td>Wi-Fi or mobile data connection for downloading required files and packages.</td>
  </tr>
  <tr>
    <td>Storage</td>
    <td>At least 3–5 GB of available storage is recommended. More may be required depending on the installation type.</td>
  </tr>
  <tr>
    <td>Magisk</td>
    <td>Latest compatible version of Magisk for managing root access.</td>
  </tr>
  <tr>
    <td>Kali NetHunter Files</td>
    <td>Compatible NetHunter installation ZIP package for your device architecture.</td>
  </tr>
</table>

Available Kali NetHunter packages:

- "kali-nethunter-20YY.X-generic-arm64-kalifs-full.zip"
- "kali-nethunter-20YY.X-generic-arm64-kalifs-minimal.zip"

<sub>Note: Replace 20YY.X with the actual release version. Make sure the package matches your device architecture and installation requirements.</sub>

---

📱 Non-Rooted Devices

<table>
  <tr>
    <th>Requirements</th>
    <th>Description</th>
  </tr>
  <tr>
    <td>Android Device</td>
    <td>An Android smartphone without root access.</td>
  </tr>
  <tr>
    <td>Internet Connection</td>
    <td>Wi-Fi or mobile data connection for downloading and installing the required applications and packages.</td>
  </tr>
  <tr>
    <td>Storage</td>
    <td>At least 3–5 GB of available storage is recommended. Additional space may be needed for tools and packages.</td>
  </tr>
  <tr>
    <td>Termux</td>
    <td>A terminal emulator that provides a Linux-like command-line environment on Android. Used to download, install, and launch Kali NetHunter Rootless.</td>
  </tr>
  <tr>
    <td>Kali NetHunter Store</td>
    <td>The official application store for Kali NetHunter, providing access to NetHunter applications and utilities.</td>
  </tr>
  <tr>
    <td>NetHunter KeX Client</td>
    <td>An application that allows users to access the Kali Linux graphical desktop environment on Android.</td>
  </tr>
</table>

Required downloads:

- "Termux" (https://github.com/termux/termux-app/releases)
- "Kali NetHunter Store" (https://store.nethunter.com/)
- "NetHunter KeX Client" (https://store.nethunter.com/)

---

<h2>⚙️ Installation Methods</h2>There are two available installation approaches depending on your Android device.

1. Rooted Installation

For Android devices with root access.

- Uses Magisk for root management.
- Supports additional hardware and security features, depending on the device and kernel.
- Allows access to more advanced NetHunter capabilities.

2. Rootless Installation

For Android devices without root access.

- Does not require unlocking root privileges.
- Uses Termux and a PRoot-based Kali Linux environment.
- Supports many Linux command-line tools and applications.
- Has limitations with certain hardware-dependent penetration testing features.

---

<h2>⚠️ Important Notes</h2>- Not all Kali NetHunter features are supported on every Android device.
- Rootless installation does not provide the same hardware access as rooted NetHunter.
- Wi-Fi monitor mode and packet injection generally require compatible hardware, drivers, and kernel support.
- Always download installation files from official Kali NetHunter sources.
- Keep your Android device and applications updated.

---

<h2>📚 Official Documentation</h2>Resource| Link
Kali NetHunter Documentation| "Official Documentation" (https://www.kali.org/docs/nethunter/)
NetHunter Rootless Installation| "Installation Guide" (https://www.kali.org/docs/nethunter/nethunter-rootless/)
NetHunter Store| "Official Store" (https://store.nethunter.com/)
Termux| "GitHub Repository" (https://github.com/termux/termux-app)

---

<p align="center">
  <i>"Learning cybersecurity one installation, command, and experiment at a time."</i>
</p><p align="center">
  <sub>This documentation is part of my personal cybersecurity learning journey.</sub>
</p>
