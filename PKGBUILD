# Maintainer: BlackEagle < ike DOT devolder AT gmail DOT com >
pkgname=wapiti
pkgver=3.0.1
pkgrel=2
pkgdesc="vulnerability scanner for web applications."
url='http://wapiti.sourceforge.net/'
license=('GPL')
depends=('python-requests' 'python-beautifulsoup4' 'python-pysocks'
         'python-mako' 'python-tld' 'python-yaswfp')
makedepends=('python-setuptools')
arch=('any')
source=("https://downloads.sourceforge.net/project/$pkgname/$pkgname/$pkgname-$pkgver/${pkgname}3-$pkgver.tar.gz")
sha256sums=('bbb8c8f572afe77319734489a6ca0b211df4b87ad294db79b8bf0bda1c5aff29')

package() {
	cd "${pkgname}3-$pkgver"
	python3 setup.py install --root="$pkgdir/" --optimize=1
}

