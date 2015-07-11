pkgname=encoder
pkgver=1.2
pkgrel=2
pkgdesc="Encode DVD to MKV using x264"
url=""
arch=('i686' 'x86_64')
license=('custom')
depends=('lsdvd' 'ogmtools' 'mkvtoolnix-cli' 'mplayer' 'mencoder' 'x264')
source=(encoder)
md5sums=('300aa9f65f9c080508e1aabb753ea3a4')
package() {
  install -d ${pkgdir}/usr/bin/ || return 1
  install -m 755 encoder ${pkgdir}/usr/bin/encoder || return 1
}

