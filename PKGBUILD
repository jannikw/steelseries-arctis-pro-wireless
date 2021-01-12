# Maintainer: jannikw

pkgname=pulseaudio-arctis-pro-wireless
pkgver=0.2
pkgrel=1
pkgdesc="Set SteelSeries Arctis Pro Wireless Stereo as the default output when connected"
arch=("any")
url="https://github.com/jannikw/steelseries-arctis-pro-wireless"
license=('GPL')
depends=("pulseaudio")
source=("steelseries-arctis-pro-wireless.service"
       	"steelseries-arctis-pro-wireless")
md5sums=('6d55e535a3e7eed574e36de6da9c0ca6'
         '7a5072a6af43b8be5495b6452c291d23')

package() {
	install -Dm644 steelseries-arctis-pro-wireless.service "$pkgdir"/usr/lib/systemd/system/steelseries-arctis-pro-wireless.service
	install -Dm755 steelseries-arctis-pro-wireless "$pkgdir"/usr/local/bin/steelseries-arctis-pro-wireless
}

