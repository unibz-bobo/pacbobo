# Maintainer: Julian Sanin <sanin89julian@gmail.com>

pkgname=pacbobo
pkgver=1.0.0
pkgrel=1
pkgdesc="Custom pacman package manager for Arch Linux ARM"
arch=("any")
url="https://github.com/unibz-bobo/pacbobo"
license=("MIT")
depends=("pacman")
source=("LICENSE" "$pkgname")
md5sums=("292e0d6c7f6827b97f4defdd9e99a7a3"
         "3b9b6d9badaa892ccb980c25c8cb150c")

package() {
  install -o root -g root -Dm755 "$pkgname" "$pkgdir/usr/bin/pacbobo"
  install -o root -g root -Dm644 LICENSE "$pkgdir/usr/share/licenses/$pkgname/LICENSE"
}
