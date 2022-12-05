# Reference: <https://postmarketos.org/devicepkg>
pkgname=device-samsung-gta2xlwifi
pkgdesc="Samsung Galaxy Tab A 10.5 2018"
pkgver=0.1
pkgrel=0
url="https://postmarketos.org"
license="MIT"
arch="aarch64"
options="!check !archcheck"
depends="
	linux-samsung-gta2xlwifi
	mkbootimg
	postmarketos-base
"
makedepends="devicepkg-dev"
source="deviceinfo"

build() {
	devicepkg_build $startdir $pkgname
}

package() {
	devicepkg_package $startdir $pkgname
}

sha512sums="
3ebf17d364ab221844ad80916a24ee017bbd7aeac8e1c01bf52a290fff986fc6d6892ce6a5807c7e5e0a9c07da3b868c0f706d77a11ecd64fb7598d875dfd148  deviceinfo
"
