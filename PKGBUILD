# Maintainer: Daniel Bowring <aur@daniel.bowring.email>
pkgname=gitbutler-bin
pkgver=0.12.20
pkgrel=1
_pkgvernum=1172
pkgdesc="Version control client, backed by Git, powered by Tauri/Rust/Svelte "
arch=('x86_64')
url="https://gitbutler.com/"
depends=('libayatana-appindicator' 'webkit2gtk' 'gtk3')
license=('FSL-1.0-MIT')
source=("https://releases.gitbutler.com/releases/release/${pkgver}-${_pkgvernum}/linux/$CARCH/git-butler_${pkgver}_amd64.deb")
sha256sums=('722a07c2d236464029d83d329888d0dec5c411cd2a84ebe209a79f6070ba83e9')

package() {
	bsdtar -xf "$srcdir/data.tar.gz" -C "$pkgdir"
}

