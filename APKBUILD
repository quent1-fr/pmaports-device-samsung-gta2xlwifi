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
0ecb70f3f73fa4b013e9d6c26c6dda43c27eefa25850ed482f282e6767745a450cf5374705fe82e785a24cc396576fceb51d251a4f1d387dbe09e1e7d86ac097  deviceinfo
"
