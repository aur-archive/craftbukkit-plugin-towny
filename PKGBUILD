pkgname=craftbukkit-plugin-towny
pkgver=0.89.2.23
pkgrel=1
pkgdesc="Towny Advanced is a versatile, player-controlled land management plugin for use with Bukkit/Tekkit/Spigot/Libigot."
arch=(any)
url="http://palmergames.com/towny/"
license=("NC-NDv3")
depends=("craftbukkit>=1.8")
source=("http://palmergames.com/file-repo/Towny%20Advanced/Development/$pkgver/Towny.jar")
md5sums=('460336a4b5573e839716673cb0156ffe')

package() {
  find . -name '*.jar' -exec install -Dm644 {} "$pkgdir/srv/craftbukkit/plugins/"{} \;
}

# vim:set ts=2 sw=2 et:
