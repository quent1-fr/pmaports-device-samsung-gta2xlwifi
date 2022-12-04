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
1afaa61297e345bf6b2c48f841684e9b361d1a13712a344f1dcbd3a12b90e67265237098328cf54eaea01404ba5b718d9777d5e6c59f5ef0a556770350e8f0f5  deviceinfo
"
