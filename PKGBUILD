pkgname=encoder
pkgver=1.4
pkgrel=1
pkgdesc="Encode DVD to MKV using x264"
url=""
arch=('i686' 'x86_64')
license=('custom')
depends=('lsdvd' 'ogmtools' 'mkvtoolnix-cli' 'mplayer' 'mencoder' 'x264')
source=(encoder)
md5sums=('290c2c43b985de5be27d9684b7afd608')
package() {
  install -d ${pkgdir}/usr/bin/ || return 1
  install -m 755 encoder ${pkgdir}/usr/bin/encoder || return 1
}

