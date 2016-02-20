# Maintainer: Julian Sanin <sanin89julian@gmail.com>

pkgname=pacbobo
pkgver=1.0.0
pkgrel=2
pkgdesc="Custom pacman package manager for Arch Linux ARM"
arch=("any")
url="https://github.com/unibz-bobo/pacbobo"
license=("MIT")
depends=("pacman")
source=("LICENSE" "$pkgname")
md5sums=('c2452e9972a32a82dc876de06b775145'
         'f78d20bb73c702f02d5169203f1bd769')

package() {
  install -o root -g root -Dm755 "$pkgname" "$pkgdir/usr/bin/pacbobo"
  install -o root -g root -Dm644 LICENSE "$pkgdir/usr/share/licenses/$pkgname/LICENSE"
}
