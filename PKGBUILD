# Contributor: Maxim Karasev <begs@disroot.org>
pkgname=ttf-ios-emoji
pkgver=14.5
pkgrel=1
pkgdesc='Apple Color Emoji is a color typeface used by iOS and macOS to display emoji'
arch=('any')
license=('unknown')
provides=(emoji-font)
depends=()

conflicts=(
    'ttf-apple-emoji'
)

package() {
    install -Dm644 AppleColorEmoji.ttf "$pkgdir"/usr/share/fonts/TTF/AppleColorEmoji.ttf
}
