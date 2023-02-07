
# Frappe Chat Demo

## Software Requirements
1.Python 3.10+ (v14)

2.Node.js 16

3.Redis 6 (caching and realtime updates)

4.MariaDB 10.6.6+/Postgres v12 to v14         (Database backend)

5.yarn 1.12+(js dependency manager)

6.pip 20+(py dependency manager)

7.wkhtmltopdf (version 0.12.5 with patched qt) (for pdf generation)

8.cron                                          (bench's scheduled jobs: automated certificate renewal, scheduled backups)

9.NGINX    


## Hardware Requirements

4GB RAM

40GB Hard Disk

## Installation

1. Add a New site
 
   ```
   bench new-site your-site.local
   ```

2. Get the app from the repository.

   
   ```
   bench get-app erpnext
   ```
   ```
   bench get-app chat
   ```

3. Install the app on your site.
   
   ```
   bench --site your-site.local install-app erpnext
   ```
   ```
   bench --site your-site.local install-app chat
   ```
4. Start in Local
   ```
   bench start
   ```
   