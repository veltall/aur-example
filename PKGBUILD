# Maintainer: Vu Dinh <vuniverse143@gmail.com> 

pkgname=ttf-fonts
pkgver=2.0
pkgrel=1

pkgdesc="Sharp looking ttf sans serif font"
url="https://github.com/veltall/ttf-fonts"
license=('OFL')

depends=()
arch=('any')
source=("https://github.com/veltall/$pkgname/archive/v$pkgver.tar.gz")

md5sums=('c9980796e289df190c49d7dc81cbd911')

package() {
  cd $pkgname-$pkgver/fonts
  install -d "$pkgdir"/usr/share/fonts/TTF
  install -m644 *.ttf "$pkgdir"/usr/share/fonts/TTF
}

