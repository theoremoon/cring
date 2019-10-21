pkgname=python-cring-git
pkgver=0.1.0
pkgrel=1
pkgdesc="ring based clipboard manager"
arch=('any')
license=('Apache')
depends=('python' 'python-gobject' 'python-pynput')
source=("git+git://github.com/theoremoon/cring.git")

package() {
    cp "$srcdir/cring" "$pkgdir/cring"
}
