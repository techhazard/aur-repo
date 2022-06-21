# Maintainer: Vince van Oosten <techhazard@codeforyouand.me>
pkgname=aur-repo
pkgver=1.0.0
pkgrel=1
epoch=
pkgdesc=""
arch=('any')
url="https://github.com/techhazard/${pkgname}"
license=('GPL3')
groups=()
depends=(systemd bash gnupg findutils coreutils)
makedepends=(git)
checkdepends=()
optdepends=()
provides=()
conflicts=()
replaces=()
backup=()
options=()
install=PKGBUILD.install
changelog=
source=("${pkgname}.tgz::${url}/archive/refs/tags/${pkgver}.tar.gz")
validpgpkeys=()
sha256sums=('024e9b928d4bc75620cb9bd20cccd49b69390ae6bd09ba327254e2e172e6fb71')


prepare() {
	true
}

build() {
	true
}

check() {
	true
}

package() {
	src="${pkgname}-${pkgver}"
	install -D -m 755 -t $pkgdir/usr/bin/                "${src}"/bin/*
	install -D -m 644 -t $pkgdir/usr/lib/systemd/system/ "${src}"/systemd/system/*
}
