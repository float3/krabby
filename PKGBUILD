# Maintainer: Yann Jorelle <yannjorelle@protonmail.com>
#
# This PKGBUILD was generated by `cargo aur`: https://crates.io/crates/cargo-aur

pkgname=krabby-bin
pkgver=0.1.5
pkgrel=1
pkgdesc="Print pokemon sprites in your terminal"
url="https://github.com/yannjor/krabby"
license=("GPL-3.0")
arch=("x86_64")
provides=("krabby")
conflicts=("krabby")
source=("https://github.com/yannjor/krabby/releases/download/v$pkgver/krabby-$pkgver-x86_64.tar.gz")
sha256sums=("3460848976a46ad7eedcb8125a2b1aa9f9743c94bc17201e2d91fbcd6c061595")

package() {
    install -Dm755 krabby -t "$pkgdir/usr/bin"
    install -Dm644 LICENSE "$pkgdir/usr/share/licenses/$pkgname/LICENSE"
}
