# Tips

## Important - Raspberry Pi 3b+

It is important to increase the swap size since it is very demanding.
Use zram and swap config to at least 1G.
If you wish to use swap file, it is fine but use it on a nice ssd not thumbdrive (it may cause problems)

```bash
sudo apt install zram-tools -y
sudo vi /etc/default/zramswap
# Change the line PERCENT=50 to PERCENT=150
```
