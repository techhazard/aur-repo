# Maintainer: Vince van Oosten <techhazard@codeforyouand.me>
pkgname=aur-repo
pkgver=0.1.3
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
#source=("${pkgname}.tgz::${url}/archive/refs/tags/${pkgver}.tar.gz")
source=()
validpgpkeys=()
#sha256sums=('34db10cf6e465068c206fe2d8c3d24561c25e771cd4000c2d7baca365b496546')


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
	#src="${pkgname}-${pkgver}"
	src="${pkgname}"
	install -D -m 755 -t $pkgdir/usr/bin/                "${src}"/bin/*
	install -D -m 644 -t $pkgdir/usr/lib/systemd/system/ "${src}"/systemd/system/*
}
