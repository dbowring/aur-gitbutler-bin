# Maintainer: Daniel Bowring <aur@daniel.bowring.email>
pkgname=gitbutler-bin
pkgver=0.14.34
pkgrel=1
_pkgvernum=2109
pkgdesc="Version control client, backed by Git, powered by Tauri/Rust/Svelte "
arch=('x86_64')
url="https://gitbutler.com/"
depends=('libayatana-appindicator' 'webkit2gtk-4.1' 'gtk3')
license=('FSL-1.0-MIT')
source=("https://releases.gitbutler.com/releases/release/${pkgver}-${_pkgvernum}/linux/$CARCH/GitButler_${pkgver}_amd64.deb")
sha256sums=('6c52ac75befa2b1ab868898d383cff6f577ae09b7d1adaa0d32649a00f38b1f1')

package() {
	bsdtar -xf "$srcdir/data.tar.gz" -C "$pkgdir"
}
