# Maintainer: Dave Reisner <dreisner@archlinux.org>

pkgname=pambase
pkgver=20120602
pkgrel=1
pkgdesc="Base PAM configuration for services"
arch=('any')
url="http://www.archlinux.org"
license=('GPL')
source=('system-auth'
        'system-local-login'
        'system-login'
        'system-remote-login'
        'system-services'
        'other')
backup=('etc/pam.d/system-auth'
        'etc/pam.d/system-local-login'
        'etc/pam.d/system-login'
        'etc/pam.d/system-remote-login'
        'etc/pam.d/system-services'
        'etc/pam.d/other')
md5sums=('5f169a4ffe7ed69f58e106cdd2d760df'
         '477237985820117a0e6e1b13a86eb599'
         '887c4fa3f878fc8651cc5e6f027fe5a5'
         '477237985820117a0e6e1b13a86eb599'
         '30fe7d41e054ee43fab7855bf88a07e5'
         '4d353b4351f9983abc218466bc8ffb1f')

package() {
  install -dm755 "$pkgdir/etc/pam.d"
  install -t "$pkgdir/etc/pam.d" -m644 \
      system-auth \
      system-local-login \
      system-login \
      system-remote-login \
      system-services \
      other
}

# vim:set ts=2 sw=2 et:
