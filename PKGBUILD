# Maintainer: BlackEagle < ike DOT devolder AT gmail DOT com >
pkgname=wapiti
pkgver=3.0.0
pkgrel=1
pkgdesc="Wapiti is a vulnerability scanner for web applications."
url='http://wapiti.sourceforge.net/'
license=('GPL')
depends=('python-requests' 'python-beautifulsoup4')
makedepends=('python-setuptools')
arch=('any')
source=("http://downloads.sourceforge.net/$pkgname/$pkgname-$pkgver.tar.gz")
sha256sums=('4708fa1d8159b0a5e606bdb26e1454e8df1d8bf6e11d9ad63c84e12e8edc8daa')

package() {
	cd "$pkgname-$pkgver"
	python3 setup.py install --root="$pkgdir/" --optimize=1
}

