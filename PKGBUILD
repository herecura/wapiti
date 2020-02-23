# Maintainer: BlackEagle < ike DOT devolder AT gmail DOT com >
pkgname=wapiti
pkgver=3.0.3
pkgrel=1
pkgdesc="vulnerability scanner for web applications."
url='http://wapiti.sourceforge.net/'
license=('GPL')
depends=('python-requests' 'python-beautifulsoup4' 'python-pysocks'
         'python-mako' 'python-tld' 'python-yaswfp')
makedepends=('python-setuptools')
arch=('any')
source=("https://downloads.sourceforge.net/project/$pkgname/$pkgname/$pkgname-$pkgver/${pkgname}3-$pkgver.tar.gz")
sha256sums=('059f778453ebf05b38e9c6c837d3b3eb9b8921c8fdc6d4029df89f2b0e84f5b7')

package() {
	cd "${pkgname}3-$pkgver"
	python3 setup.py install --root="$pkgdir/" --optimize=1
}

