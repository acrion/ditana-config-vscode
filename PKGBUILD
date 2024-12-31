# Maintainer: Stefan Zipproth <s.zipproth@ditana.org>

pkgname=ditana-config-vscode
pkgver=1.03
pkgrel=1
pkgdesc="Ditana vscode configuration"
arch=(any)
url="https://code.visualstudio.com/"
license=('MIT')
conflicts=()
depends=(code code-marketplace)
makedepends=()
source=("file://${PWD}/settings.json")
sha256sums=('SKIP')

package() {
    mkdir -p "$pkgdir/etc/skel/.config/Code"
    install -D -m644 $srcdir/settings.json "$pkgdir/etc/skel/.config/Code - OSS/User/settings.json"
}
