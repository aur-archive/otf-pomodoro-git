pkgname=otf-pomodoro-git
pkgver=1.0
pkgrel=2
pkgdesc="Font with symbols to talk about the Pomodoro Technique"
arch=('any')
url="https://github.com/gabrielelana/pomicons"
license=('CC BY-NC-ND 3.0')
depends=('fontconfig' 'xorg-font-utils')
install=$pkgname.install
source=(https://github.com/gabrielelana/pomicons/raw/master/fonts/Pomicons.otf)
md5sums=('SKIP')

package() {
  cd "${srcdir}"

  install -d "${pkgdir}/usr/share/fonts/OTF"
  install -m644 *.otf "${pkgdir}/usr/share/fonts/OTF/"
}
