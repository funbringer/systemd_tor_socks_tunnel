# Maintainer: Dmitry Ivanov <ivadmi5@gmail.com>

pkgname=systemd-tor-socks-tunnel
pkgver=1.0
pkgrel=1
pkgdesc="systemd unit for tor socks tunnel device"
arch=('any')
url="https://github.com/funbringer/systemd_tor_socks_tunnel"
license=('MIT')
depends=('tor' 'badvpn' 'systemd')
source=('tor-socks-tunnel.service')
sha256sums=('b077e09e8171f52b76ec19f0a2bbab9d9bc183a2989af1ef1ca443aa6b66f599')

package() {
	install -m 755 -d $pkgdir/etc/systemd/system/
	install -m 644 tor-socks-tunnel.service $pkgdir/etc/systemd/system/
}
