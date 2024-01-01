# Maintainer: Refined7075 <yxgw5rdy2@mozmail.com>
pkgname=aouracord-bin
pkgver=3.1.1
pkgrel=1
pkgdesc="BetterDiscord alternative, based off of Dorion."
arch=('x86_64')
url="https://github.com/JSpeightADev/Aoura-Cord"
license=('GPL3')
depends=('libayatana-appindicator' 'webkit2gtk' 'gtk3')
provides=('aouracord')
conflicts=('aouracord')
source=("https://github.com/JSpeightADev/Aoura-Cord/releases/download/v${pkgver}/aouracord_${pkgver}_amd64.deb")
sha256sums=('e29cb66b447ba6a733e5aded5bb768ab4678f3eeb32c254da79117699ba05967')

package() {
    bsdtar -xf "$srcdir/data.tar.gz" -C "$pkgdir"
}