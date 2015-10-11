# Maintainer: Daniel Hillenbrand <codeworkx [at] bbqlinux [dot] org>

pkgname=bbqlinux-desktop-plasma
pkgver=1.0.6
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
'breeze-icons'
'drkonqi'
'kde-gtk-config'
'kdeplasma-addons'
'kgamma5'
'khelpcenter'
'kinfocenter'
'kmenuedit'
'kscreen'
'ksshaskpass'
'ksysguard'
'kwallet-pam'
'kwayland-integration'
'kwin'
'kwrited'
'milou'
'oxygen'
'oxygen-cursors'
'plasma-desktop'
'plasma-mediacenter'
'plasma-nm'
'plasma-pa'
'plasma-workspace'
'plasma-workspace-wallpapers'
'powerdevil'
'sddm-kcm'
'systemsettings'
'user-manager'

# Terminal
'konsole'

# File Manager
'kdebase-dolphin'
'kdesdk-dolphin-plugins'

# For Qt4 applications to have a consistent appearance
'breeze-kde4'

)

package() {
    cd "$pkgdir"
    mkdir -p etc

    cp -R "$srcdir/etc/skel" etc/skel
}
