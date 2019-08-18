# Maintainer: Jan Boelsche <jan@lagomorph.de>
pkgname='large-console-font'
pkgver=1.0
pkgrel=1
pkgdesc='Set a large font for the Linux console'
packager='Jan Boelsche'
arch=('any')
license=('GPL')
groups=()
depends=(
  'terminus-font'
)
makedepends=()
checkdepends=()
optdepends=()
source=(
  'vconsole.conf'
)

sha256sums=('e09f63d5c1c9bd69122a12a2f8939b1b4283d075ebf73cbc792bd6c5f02d6df5')

package() {
	install -Dm 644 -t "${pkgdir}/etc" vconsole.conf
}
