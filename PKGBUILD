# Maintainer: David Runge <dvzrv@archlinux.org>
# Contributor: Dave Reisner <dreisner@archlinux.org>

pkgname=pambase
pkgver=20211210
pkgrel=1
pkgdesc="Base PAM configuration for services"
arch=(any)
url="https://www.archlinux.org"
license=(GPL)
backup=(
  etc/pam.d/system-auth
  etc/pam.d/system-local-login
  etc/pam.d/system-login
  etc/pam.d/system-remote-login
  etc/pam.d/system-services
  etc/pam.d/other
)
source=(
  system-auth
  system-local-login
  system-login
  system-remote-login
  system-services
  other
)
sha512sums=('881f2d76cd5f621b46cc710e9f63269b801b6e03fd3cacf0b31bd1ec2b846c1e610891e2f7a52bfc67917336f411005927a9a6a01f6173143c4ef89a034dc604'
            '83cc3d84ef5afded9afd4d347132901b9adcbd8b21be45b80d010370a2082e8388a713eb78d052944bc47b07fd7383edf18e2674d9d0545215cc45e14a2e14b1'
            '39fc1b3e9d16c5049453d9756ae2088e4a927e42c5dad35a1d07b372c7801bb67606e69eb1dbf19c85843277f207812aca3da0addab09032a4de9ef933e7b0c5'
            '83cc3d84ef5afded9afd4d347132901b9adcbd8b21be45b80d010370a2082e8388a713eb78d052944bc47b07fd7383edf18e2674d9d0545215cc45e14a2e14b1'
            '5c2947f8644803783d19cc97ddc19fdaa234dac41a939edd32c9452e78bb2a4751bceeb4737d0791fb122ca932b8b941aab869b6dec3146bf90e94517d31724a'
            'df554f70f017dd3f6023a3c62b95d19123eaf41c08deaac0c4bc343fcce6eeefcf468910f7cb9ba58ee2846abb88091d18d718eb0228e38f6ce26ebced94c407')
b2sums=('2120f15bca3092ce6ed672a3244c1f2d9f13601db3fda83442029d1ceca3a5622b9ce8e215d821ac1e68d30f20556d3ad463fed9f3670778e4b87f4813d7df1b'
        '900a5250f5a9e464c1c3ab8fc112475c99f4d76b597abf362041b661707dcc458cd385fd2cfeecf1ba9e3e831176ca8d183cffc9a913fb79e8ddcaa68223a7e6'
        'b7cce82e2c10d527a05281527bc3bb505357239cb99418c715dfdfea28822fd46615190f420e96d9a497c18b8b54f125fcdc878d388d1f03ee287e940597b37d'
        '900a5250f5a9e464c1c3ab8fc112475c99f4d76b597abf362041b661707dcc458cd385fd2cfeecf1ba9e3e831176ca8d183cffc9a913fb79e8ddcaa68223a7e6'
        'e11e8959c961036a384016096f0fce0696d8a3ecc63d0d12d8016cc7c27a7afc80f8580ab639c97360aed0d49af3159462d85260b4404b9d65963f440eb77243'
        '3de32ccd196fecaf0a3cce8e61867f93f85fff651044519d8521a28d9f8d6ddaf51f3e30eac4979884c505f9f52d01f458e5bccc5d5adc4f1d7d372068dd02da')

package() {
  install -vDm 644 "${source[@]}" -t "$pkgdir/etc/pam.d/"
}

# vim:set ts=2 sw=2 et:
