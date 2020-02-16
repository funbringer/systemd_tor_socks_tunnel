## Systemd unit for Tor tunnel device

Usage:

```bash
# Install everything
$ makepkg -si
$ sudo systemctl enable tor-socks-tunnel --now

# Add some routes
$ sudo ip route add $(tor-resolve example.org) via 10.0.15.2
```
