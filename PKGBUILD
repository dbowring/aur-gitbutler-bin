# Maintainer: Daniel Bowring <aur@daniel.bowring.email>
pkgname=gitbutler-bin
pkgver=0.14.16
pkgrel=1
_pkgvernum=1836
pkgdesc="Version control client, backed by Git, powered by Tauri/Rust/Svelte "
arch=('x86_64')
url="https://gitbutler.com/"
depends=('libayatana-appindicator' 'webkit2gtk-4.1' 'gtk3')
license=('FSL-1.0-MIT')
source=("https://releases.gitbutler.com/releases/release/${pkgver}-${_pkgvernum}/linux/$CARCH/GitButler_${pkgver}_amd64.deb")
sha256sums=('73e3513238488861c2cc95b90a93a31398c4ab8d05f42ea19237c940c68dc1a5')

package() {
	bsdtar -xf "$srcdir/data.tar.gz" -C "$pkgdir"
}
