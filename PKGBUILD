# Maintainer: Vu Dinh <vuniverse143@gmail.com> 
# Contributor: 

pkgname=ttf-monda
pkgver=1.0
pkgrel=1

pkgdesc="Sharp looking ttf sans serif font"
url="https://github.com/veltall/ttf-monda"
license=('MIT')

depends=()
arch=('any')
source=("https://github.com/veltall/ttf-monda/archive/v$pkgver.tar.gz")

md5sums=('3f9fbbf496f2d7568507482f7240c6a2')

package() {
  cd ttf-monda-$pkgver/fonts
  install -d "$pkgdir"/usr/share/fonts/TTF
  install -m644 *.ttf "$pkgdir"/usr/share/fonts/TTF
}

