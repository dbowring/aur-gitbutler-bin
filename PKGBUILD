# Maintainer: Daniel Bowring <aur@daniel.bowring.email>
pkgname=gitbutler-bin
pkgver=0.12.17
pkgrel=1
_pkgvernum=1154
pkgdesc="Version control client, backed by Git, powered by Tauri/Rust/Svelte "
arch=('x86_64')
url="https://gitbutler.com/"
depends=('libayatana-appindicator' 'webkit2gtk' 'gtk3')
license=('FSL-1.0-MIT')
source=("https://releases.gitbutler.com/releases/release/${pkgver}-${_pkgvernum}/linux/$CARCH/git-butler_${pkgver}_amd64.deb")
sha256sums=('3b2b7f5e1fd11a52bb06b28168fc71fda5ca0678fb8fb475c2110140dbbf2878')

package() {
	bsdtar -xf "$srcdir/data.tar.gz" -C "$pkgdir"
}

