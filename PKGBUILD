# Maintainer: Daniel Hillenbrand <codeworkx [at] bbqlinux [dot] org>

pkgname=bbqlinux-desktop-plasma
pkgver=1.0.7
pkgrel=1
pkgdesc="BBQLinux Plasma Desktop"
arch=('any')
url="https://github.com/bbqlinux/bbqlinux-desktop-plasma"
license=('GPL')
groups=('bbqlinux')
provides=('bbqlinux-desktop-environment')
depends=(

# Display Manager
'lightdm'
'lightdm-bbqlinux-greeter'

# Plasma
'plasma-meta'

# Terminal
'konsole'

# File Manager
'dolphin'
'dolphin-plugins'

# For Qt4 applications to have a consistent appearance
'breeze-kde4'

)

package() {
    cd "$pkgdir"
    mkdir -p etc

    cp -R "$srcdir/etc/skel" etc/skel
}
