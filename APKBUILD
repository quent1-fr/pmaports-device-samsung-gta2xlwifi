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
1a10eb811fb4d217b5fc5900aaa8fcf1abce5f4df2a1656b7fe31314314dce9ad3e24618394c82a41ebcfea5428f594a485c0a7b5289d9cd3a2aeda157d41ecc  deviceinfo
"
