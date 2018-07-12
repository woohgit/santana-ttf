# $Id$
# Maintainer: Adam Papai (wooh) <wooh@wooh.hu>

pkgname=santana-ttf
pkgver=1
_relver=2009.04.03
pkgrel=1
pkgdesc="Santana font family created by Manfred Klein"
url="https://www.dafont.com/santana.font"
arch=(any)
license=(custom)
source=("santana.zip::https://dl.dafont.com/dl/?f=santana")
sha256sums=('5a42adc486144e471a85d900b2930731114be19a8a1205fae2f3dc4e682f84a2')

package() {
  install -d "$pkgdir/usr/share/fonts/${pkgname%-fonts}"
  install -t "$pkgdir/usr/share/fonts/${pkgname%-fonts}" -m644 *.ttf
}

# vim:set ts=2 sw=2 et:
