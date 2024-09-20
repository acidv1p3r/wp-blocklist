WP Admin IP Blocklist (Wordfence Export)
This repository contains a collection of IP addresses exported from the Wordfence Dashboard firewall. These IPs have been flagged for attempting unauthorized access to WordPress admin areas, primarily through wp-admin login attempts. The purpose of this blocklist is to help WordPress administrators easily re-import the list into their Wordfence security plugin.

How to Use
Import into Wordfence
These IPs were directly exported from the Wordfence firewall and are intended to be imported back into Wordfence for blocking. To import the IP blocklist into your Wordfence installation:

Go to Wordfence > Firewall > Blocking in your WordPress dashboard.
Locate the "Import/Export" options.
Use the import function to upload the blocklist file from this repository.
Once imported, Wordfence will automatically block these IPs from accessing your site.
Updating the Blocklist
This blocklist will be updated periodically as new IPs are flagged by Wordfence. To stay protected, regularly check back or watch the repository for updates.

Contributing
If you have additional IPs to contribute (from your Wordfence installation or another source), feel free to submit a pull request or open an issue.

Contribution Steps:
Fork this repository.
Add the new IPs to the ips-blocklist.txt or ips-blocklist.json file.
Submit a pull request with details about the IPs you've contributed.
Disclaimer
Please note that while this IP blocklist can improve your site’s security, it should be used in conjunction with other security best practices, such as using strong passwords, enabling two-factor authentication, and keeping your WordPress installation up to date.
