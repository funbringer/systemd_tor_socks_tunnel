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
sha256sums=('206bba8df826854c8c1c5a4850d900120b4dc83f5c1477279961c68671de47ed')

package() {
	install -m 755 -d $pkgdir/etc/systemd/system/
	install -m 644 tor-socks-tunnel.service $pkgdir/etc/systemd/system/
}
