# Maintainer: Tom Vincent <http://tlvince.com/contact/>
pkgname=irssi-script-queryresume
_name=queryresume.pl
pkgver=2003021201
pkgrel=2
pkgdesc="Restores the last lines of a query on re-creation"
arch=(any)
url="http://scripts.irssi.org/"
source="http://scripts.irssi.org/scripts/$_name"
license=('GPL')
depends=('irssi')
md5sums=('ace05acd4d61eed410b30ff5b02c4677')

package() {
  install -Dm644 "$srcdir/$_name" "$pkgdir/usr/share/irssi/scripts/$_name"
}
