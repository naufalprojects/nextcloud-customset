# nextcloud-customset
Custom settings of Nextcloud Docker

Base are still from original (Nextcloud:latest and PSQL:latest)

# Warning
1. You must adjust your PHP_MEMORY_LIMIT based from your server (mine is 2G)*
2. (Optional) You can adjust your PHP_UPLOAD_LIMIT based for your need (mine is 10G)

*) My suggestion :
1. If your system just only have 2GB (or less), adjust to 256M (or 512M).
2. If your system is 4GB, you can use my default config.
3. If your system is more than 8GB, you can increase the memory limit.
