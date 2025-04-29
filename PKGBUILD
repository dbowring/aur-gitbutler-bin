# Maintainer: Daniel Bowring <aur@daniel.bowring.email>
pkgname=gitbutler-bin
pkgver=0.14.19
pkgrel=1
_pkgvernum=1894
pkgdesc="Version control client, backed by Git, powered by Tauri/Rust/Svelte "
arch=('x86_64')
url="https://gitbutler.com/"
depends=('libayatana-appindicator' 'webkit2gtk-4.1' 'gtk3')
license=('FSL-1.0-MIT')
source=("https://releases.gitbutler.com/releases/release/${pkgver}-${_pkgvernum}/linux/$CARCH/GitButler_${pkgver}_amd64.deb")
sha256sums=('b94c13f9f8334257379eb70ec17b6a45506ad345ac4a47e963fab46c1d3707d4')

package() {
	bsdtar -xf "$srcdir/data.tar.gz" -C "$pkgdir"
}
