# Maintainer: Muflone <muflone@vbsimple.net>
pkgname=tn5250j-jtopen
pkgver=7.9
pkgrel=1
pkgdesc="Support for export of spool files and data files in tn5250j"
arch=(any)
url="http://jt400.sourceforge.net/"
license=('GPL')
depends=(tn5250j jtopen)

package() {
  # Install files for the package
  install -d "$pkgdir/usr/share/java/tn5250j"
  ln -s /usr/lib/jtopen/jt400.jar "$pkgdir/usr/share/java/tn5250j/jt400.jar"
}

