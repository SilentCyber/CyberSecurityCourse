Vulnerability Report

Product Type: Application
Product: WordPress
Version Affected: 4.2.3
Version Fix: 4.2.4
Vulnerability: SQL Injection

	The SQL Injection vulnerability allows a remote attacker to execute an SQL command through a comment that is mishandled after retrieval from the trash. The vulnerability is in the wp_untrash_post_comments in the wp-includes/post.php. The software did not validate user-supplied input. Rapid7.com gives this vulnerability a score of 8 out of 10. WordPress released a latest version, which is version 4.2.4 that fixes the SQL Injection. Go to https://wordpress.org/download/ to get the latest version.

Product Type: Application
Product: WordPress
Version Affected: 2.0 – 2.0.11
Version Fixed: 2.1
Vulnerability: CSRF

	This CSRF vulnerability is in the retrospam component in wp-admin/options-discussion.php. This allows remotes attackers to capture authentication of administrators for requests that move comments to the moderation list. Rapid7.com scores this vulnerability at a 7. Rapid7 suggests a solution by updating WordPress to version 2.1. Latest update to fix this is at https://wordpress.org/download/.

Product Type: Application
Product: WordPress
Version Affect:4.5.2
Version fixed: 4.5.3
Vulnerability: XSS

	The XSS vulnerability is in the column_title function in wp-admin/includes/class-wp-media0list-table.php. This vulnerability lets a person inject arbitrary web script or HTML through a crafted attachment name. Cvedailts.com give this vulnerability a score of 4.3. It is recommended to go to WordPress website and download the latest version 4.5.3 to fix this issue. Here is the link to get it https://wordpress.org/download/.

Product Type: Application
Product: WordPress
Version Affected: 4.7
Version Fix: 4.7.1
Vulnerability: User Enumeration

	This vulnerability doesn’t properly restrict listings of posts authors. This will allow a remote attacker to obtain sensitive information through a wp-json/wp/v2/users request without any form of authentication. This is considered a zero-day vulnerability. You can easily pick up this vulnerability using the Nessus vulnerability scanner. Go to https://wordpress.org/download/ to download the latest version of WordPress.

Product Type: Application
Product: WordPress
Version Affected: 4.2.2
Version Fix:4.2.3
Vulnerability: Privilege Escalation

	This vulnerability doesn’t verify the edit_posts capability. A remote attacker can authenticate as users to bypass intended access restrictions and create drafts leveraging the subscriber role. This can be demonstrated by a post-quickdraft-save action to wp-admin/post.php. To get the latest patch go to https://wordpress.org/download/.
