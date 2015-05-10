# Maintainer: Daniel Hillenbrand <codeworkx [at] bbqlinux [dot] org>

pkgname=bbqlinux-desktop-plasma
pkgver=1.0.1
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
'bluedevil'
'breeze'
'drkonqi'
'kde-gtk-config'
'kdeplasma-addons'
'kinfocenter'
'kio-extras'
'kmenuedit'
'kscreen'
'ksshaskpass'
'ksysguard'
'kwin'
'kwrited'
'milou'
'oxygen'
'oxygen-cursors'
'plasma-desktop'
'plasma-mediacenter'
'plasma-nm'
'plasma-workspace'
'plasma-workspace-wallpapers'
'powerdevil'
'systemsettings'

# Terminal
'konsole'

# File Manager
'kdebase-dolphin'
'kdesdk-dolphin-plugins'

# For Qt4 applications to have a consistent appearance
'breeze-kde4'

)

package() {
    cd "$srcdir"
}
