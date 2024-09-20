[discord-badge]: https://discord.com/api/guilds/897156326776520736/widget.png?style=shield
[discord-link]: https://discord.gg/RgZGCqKxAb

<div align="center">

# WP Admin IP Blocklist (Wordfence Export)

[![Discord Server][discord-badge]][discord-link]  

</div>  


This repository contains a collection of IP addresses exported from the Wordfence Dashboard firewall. These IPs have been flagged for attempting unauthorized access to WordPress admin areas, primarily targeting `wp-admin` login attempts. The purpose of this blocklist is to help WordPress administrators easily re-import the list into their Wordfence security plugin to enhance protection.

## **How to Use**

### **Import into Wordfence**

These IPs were directly exported from Wordfence and are intended to be imported back for blocking. To import the IP blocklist into your Wordfence installation:

1. Go to **Wordfence > Firewall > Blocking** in your WordPress dashboard.
2. Locate the **"Import/Export"** options.
3. Use the **Import** function to upload the blocklist file from this repository.
4. Once imported, Wordfence will automatically block these IPs from accessing your site.

## **Updating the Blocklist**

This blocklist will be updated periodically as new IPs are flagged by Wordfence. To stay protected, regularly check back or watch the repository for updates.

## **Contributing**

If you have additional IPs to contribute (from your Wordfence installation or another source), feel free to submit a pull request or open an issue.

### **Contribution Steps:**

1. Fork this repository.
2. Add the new IPs to the `ips-blocklist.txt` file.
3. Submit a pull request with details about the IPs you've contributed.

## **Disclaimer**

While this IP blocklist can help improve your site’s security, it should be used in conjunction with other security best practices, such as using strong passwords, enabling two-factor authentication, and keeping your WordPress installation up to date.
