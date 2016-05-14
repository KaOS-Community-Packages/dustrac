pkgname=dustrac
pkgver=1.11.0
_pkgver=1.11.0-3
pkgrel=1
pkgdesc="A tile-based 2D racing game and track editor"
arch=("x86_64")
url="https://sourceforge.net/projects/dustrac/"
category=Game
screenshot=http://i.imgur.com/w0kKsSz.png
license=('GPL3')
depends=('qt5-base' 'libvorbis' 'openal' )
source=("https://github.com/juzzlin/DustRacing2D/releases/download/1.11.0/${pkgname}_${_pkgver}_amd64.ubuntu.15.04.deb")
md5sums=('c0c03a06a6a1418c9fc1b098caac50e1')
package() {
  tar -xJf data.tar.xz -C $pkgdir
  rm -r $pkgdir/usr/share/doc
}
