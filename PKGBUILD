
# Author: Lucain
#
 pkgname=zukitwo-colors
 pkgver=2012.11.01
 pkgrel=1
 pkgdesc="Zukitwo Gtk2.0/Gtk3.0/Metacity with Shiki-Colors color scheme."
 url="http://www.deviantart.com/download/310434222/zukitwo_colors__2012_11_01__by_karashata-d54toku.zip"
 license=('LGPL')
 arch=('any')
 depends=('gtk-engine-murrine')
 optdepends=('gnome-shell-extension-user-theme: User Theme extension for GNOME Shell'
             'gnome-tweak-tool: A tool to customize advanced GNOME 3 options.')
source=("http://www.deviantart.com/download/310434222/zukitwo_colors_by_karashata-d54toku.zip")
DLAGENTS=('http::/usr/bin/wget -c -t 3 --waitretry=3 -H -U Mozilla -O %o %u')
sha256sums=('895b0722be22ef44825bd804e6cbfa7a4704986b60af69472484c2461b2e3e57')


package() {
 mkdir -p ${pkgdir}/usr/share/themes/
 cp -R ${srcdir}/Zukitwo** ${pkgdir}/usr/share/themes/
 chmod -R 755 ${pkgdir}/usr/share/themes/
}
