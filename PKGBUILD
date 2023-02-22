# Maintainer: Your Name <youremail@domain.com>
pkgname=asahi-identifier
pkgver=1.0.0
pkgrel=1
pkgdesc="Asahi Linux os-release and lsb-release files"
arch=('aarch64')
license=('MIT')
source=("os-release"
        "lsb-release"
	"kcm-about-distrorc")

package() {
	mkdir -p "$pkgdir/etc/xdg"
	cp os-release lsb-release "$pkgdir/etc"
	cp kcm-about-distrorc "$pkgdir/etc/xdg"
}
sha256sums=('e95d28071b1ae1d466f4bbc3272d7ab53e2f7394d2b0ca89b4a69c831841747b'
            'efd04e8611a5f82717cafe53115ddfa2103acbd99d8ce588b0f979f3ff44a360'
            'fbc15230eac758af4fee9cc3b35c9be7c8484c65cd00023bb7746e011e7582d3')
