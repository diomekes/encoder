pkgname=encoder
pkgver=1.1
pkgrel=4
pkgdesc="Encode DVD to MKV using x264"
url=""
arch=('i686' 'x86_64')
license=('custom')
depends=('lsdvd' 'ogmtools' 'mkvtoolnix-cli' 'mplayer' 'mencoder' 'x264')
source=(encoder)
md5sums=('a9abd740e49fd6436a1846dc5ae9f003')
package() {
  install -d ${pkgdir}/usr/bin/ || return 1
  install -m 755 encoder ${pkgdir}/usr/bin/encoder || return 1
}

