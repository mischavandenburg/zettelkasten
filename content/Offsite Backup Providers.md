---
publish: true
---
# Offsite Backup Providers

After some research I have made my choice for the provider I'll use for my off-site backups.

## iDrive e2

Reasons why I went for iDrive e2:

- Compatible with Restic and Synology
- Cheap
- 2FA
- S3 object storage

5 TB
$247.50/year $123.75 first year

10 TB
$495.00/year $247.50 first year

20 TB
$990.00/year $495.00 first year


https://www.idrive.com/s3-storage-e2/

## Hetzner Storage Box

Looks good, but the data is attached to one server only as far as I can gather. Higher risk of data loss.

But it's cheap and unrestricted.

https://www.hetzner.com/storage/storage-box/

## pcloud

Looks great too, but it seems you need to use their web interface for everything.

They have an rclone backend, from what I gather, but it seems a bit finicky.

I am not really interested in their share links functionality etc.

Seems more like a google drive.

https://www.reddit.com/r/pcloud/comments/1fu2ny2/is_rclone_supported_on_pcloud_what_about_restic/

https://www.pcloud.com/eu

## Azure blob storage

This was much more expensive than I thought. For 2TB it is already $41 a month, and that doesn't even include data traffic or write operations!

## A useful comparison list

https://comparisontabl.es/cloud-storage/