pkgname=encoder
pkgver=1.2
pkgrel=4
pkgdesc="Encode DVD to MKV using x264"
url=""
arch=('i686' 'x86_64')
license=('custom')
depends=('lsdvd' 'ogmtools' 'mkvtoolnix-cli' 'mplayer' 'mencoder' 'x264')
source=(encoder)
md5sums=('1bc8d2eb86d348b93ae077631b23f80a')
package() {
  install -d ${pkgdir}/usr/bin/ || return 1
  install -m 755 encoder ${pkgdir}/usr/bin/encoder || return 1
}

