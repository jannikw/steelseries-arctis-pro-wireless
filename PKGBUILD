# Maintainer: jannikw

pkgname=pulseaudio-arctis-pro-wireless
pkgver=0.1
pkgrel=1
pkgdesc="Set SteelSeries Arctis Pro Wireless Stereo as the default output when connected"
arch=("any")
url=""
license=('GPL')
depends=("pulseaudio")
source=("85-steelseries-arctis-pro-wireless.rules"
       	"steelseries-arctis-pro-wireless")
md5sums=("c7add45f3071a6ca26d1644ef8f0c57c"
	"b67538d94338021e320712e7022e9cee")

package() {
	install -Dm644 85-steelseries-arctis-pro-wireless.rules "$pkgdir"/usr/lib/udev/rules.d/85-steelseries-arctis-pro-wireless.rules
	install -Dm755 steelseries-arctis-pro-wireless "$pkgdir"/usr/local/bin/steelseries-arctis-pro-wireless
}

