# Maintainer:  <clu@nimbus>

pkgname=python2-montage-wrapper
_pkgname=montage-wrapper
pkgver=0.9.8
pkgrel=1 
pkgdesc="A pure Python module that provides a Python API to the Montage Astronomical Image Mosaic Engine."
url="http://www.astropy.org/montage-wrapper"
arch=('any')
license=('unknown')
depends=(python2 python2-numpy python2-astropy montage)
makedepends=()
conflicts=()
replaces=()
backup=()
source=(https://github.com/astropy/$_pkgname/archive/v${pkgver}.tar.gz
        .AURINFO)
md5sums=('01ad10b3bfe3ea28c352b62378e8f1dc'
         'SKIP')

package() {
  cd ${srcdir}/${_pkgname}-${pkgver}
  python2 setup.py install --root=${pkgdir} --optimize=1
}
