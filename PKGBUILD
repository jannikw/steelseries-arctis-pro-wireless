# Maintainer: jannikw

pkgname=pulseaudio-arctis-pro-wireless
pkgver=0.3
pkgrel=1
pkgdesc="Set SteelSeries Arctis Pro Wireless Stereo as the default output when connected"
arch=("any")
url="https://github.com/jannikw/steelseries-arctis-pro-wireless"
license=('GPL')
depends=("pulseaudio")
source=("steelseries-arctis-pro-wireless.service"
       	"steelseries-arctis-pro-wireless")
md5sums=('46610661b78e23811171f8a0e3c6745f'
         'b0567f2aa01744531c27a9f4497fefb3')

package() {
	install -Dm644 steelseries-arctis-pro-wireless.service "$pkgdir"/usr/lib/systemd/system/steelseries-arctis-pro-wireless.service
	install -Dm755 steelseries-arctis-pro-wireless "$pkgdir"/usr/local/bin/steelseries-arctis-pro-wireless
}

