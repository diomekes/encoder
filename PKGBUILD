pkgname=encoder
pkgver=1.4.1
pkgrel=1
pkgdesc="Encode DVD to MKV using x264"
url=""
arch=('i686' 'x86_64')
license=('custom')
depends=('lsdvd' 'ogmtools' 'mkvtoolnix-cli' 'mplayer' 'mencoder' 'x264')
source=(encoder)
md5sums=('bb530e8845c785bfc05526ea724669a7')
package() {
  install -d ${pkgdir}/usr/bin/ || return 1
  install -m 755 encoder ${pkgdir}/usr/bin/encoder || return 1
}
