# Radarr 

- One thing that happens for some torrent indexers is that it might be set as others/misc, so radar does not allow it.
- The workaround is to allow - in the apps setting of prowlarr for radarr - the `7010` and `others` in category - see this [github issue](https://github.com/Jackett/Jackett/issues/8961#:~:text=wait%2C%20or%20add-,7010,-to%20the%20categories).