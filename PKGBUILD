# Maintainer: BlackEagle < ike DOT devolder AT gmail DOT com >
pkgname=wapiti
pkgver=3.0.2
pkgrel=1
pkgdesc="vulnerability scanner for web applications."
url='http://wapiti.sourceforge.net/'
license=('GPL')
depends=('python-requests' 'python-beautifulsoup4' 'python-pysocks'
         'python-mako' 'python-tld' 'python-yaswfp')
makedepends=('python-setuptools')
arch=('any')
source=("https://downloads.sourceforge.net/project/$pkgname/$pkgname/$pkgname-$pkgver/${pkgname}3-$pkgver.tar.gz")
sha256sums=('df86cab9f66c7794cab54fede16029056a764f5da565b2695524f9bd2bc9a384')

package() {
	cd "${pkgname}3-$pkgver"
	python3 setup.py install --root="$pkgdir/" --optimize=1
}

