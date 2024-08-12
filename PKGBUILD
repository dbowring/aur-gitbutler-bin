# Maintainer: Daniel Bowring <aur@daniel.bowring.email>
pkgname=gitbutler-bin
pkgver=0.12.19
pkgrel=1
_pkgvernum=1165
pkgdesc="Version control client, backed by Git, powered by Tauri/Rust/Svelte "
arch=('x86_64')
url="https://gitbutler.com/"
depends=('libayatana-appindicator' 'webkit2gtk' 'gtk3')
license=('FSL-1.0-MIT')
source=("https://releases.gitbutler.com/releases/release/${pkgver}-${_pkgvernum}/linux/$CARCH/git-butler_${pkgver}_amd64.deb")
sha256sums=('bc1b7a1ce40a3832a5cb07a352055f9874822576b6aad79f15d08f0e090bac8a')

package() {
	bsdtar -xf "$srcdir/data.tar.gz" -C "$pkgdir"
}

