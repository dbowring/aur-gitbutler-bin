# Maintainer: Daniel Bowring <aur@daniel.bowring.email>
pkgname=gitbutler-bin
pkgver=0.12.21
pkgrel=1
_pkgvernum=1199
pkgdesc="Version control client, backed by Git, powered by Tauri/Rust/Svelte "
arch=('x86_64')
url="https://gitbutler.com/"
depends=('libayatana-appindicator' 'webkit2gtk' 'gtk3')
license=('FSL-1.0-MIT')
source=("https://releases.gitbutler.com/releases/release/${pkgver}-${_pkgvernum}/linux/$CARCH/git-butler_${pkgver}_amd64.deb")
sha256sums=('eb7ea4aee80add0dca733a1c5fad538581e2aaef76fad3d88cab9039eacc3fb7')

package() {
	bsdtar -xf "$srcdir/data.tar.gz" -C "$pkgdir"
}

