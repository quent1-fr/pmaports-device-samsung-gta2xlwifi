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
5b17322a9574e1aa33c27ab03bfffadcbd7857383f04b3536faaaa47399dbd575700b2805502f5f866ce8f80a367c4438ce5393ab59e41f982e986fe2fc1c549  deviceinfo
"
