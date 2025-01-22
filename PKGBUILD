# Maintainer: Daniel Bowring <aur@daniel.bowring.email>
pkgname=gitbutler-bin
pkgver=0.14.6
pkgrel=1
_pkgvernum=1650
pkgdesc="Version control client, backed by Git, powered by Tauri/Rust/Svelte "
arch=('x86_64')
url="https://gitbutler.com/"
depends=('libayatana-appindicator' 'webkit2gtk-4.1' 'gtk3')
license=('FSL-1.0-MIT')
source=("https://releases.gitbutler.com/releases/release/${pkgver}-${_pkgvernum}/linux/$CARCH/GitButler_${pkgver}_amd64.deb")
sha256sums=('4079c7884348c19e0cd514b7cfce503de934dc7d1c67fc508bda13f0aa3e27c9')

package() {
	bsdtar -xf "$srcdir/data.tar.gz" -C "$pkgdir"
}
