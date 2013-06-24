# submitter: Gen2ly <toddrpartridge@gmail.com>

pkgname=xuserrun
pkgver=72a0fd9
pkgrel=1
pkgdesc="Run a command as the currently-active X.org server user"
arch=(any)
github_user=jdsumsion
url="https://github.com/$github_user/xuserrun"
license=('GPL')
makedepends=('systemd')
conflicts=('xuserrun-git')
install=${pkgname}.install
changelog=
source=(https://github.com/$github_user/$pkgname/tarball/$pkgver)
md5sums=('1409e7ebd212431980d08b2bac5906f7')
sha1sums=('de23fce48aaab35b2aebf61177cfcf0516a45301')

package() {
  cd "$srcdir/$github_user-$pkgname-$pkgver"
  install -Dm755 "$srcdir/$github_user-$pkgname-$pkgver"/$pkgname \
  $pkgdir/usr/bin/$pkgname
}

# vim:set ts=2 sw=2 et:
