pkgname=appmonitord
pkgver=1.0.0
pkgrel=1
pkgdesc='Monitors one or more directories, waiting for AppImages to be added or deleted, creating or removing menu entries accordingly.'
arch=('any')
source=('appmonitord')
sha256sums=('SKIP')
url='https://github.com/eloquentos/appmonitord'
license=('BSD')
depends=('inotify-tools' 'xdg-utils')

package() {
  mkdir -p $pkgdir/usr/bin
  cp appmonitord $pkgdir/usr/bin
}
