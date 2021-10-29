pkgname=ttf-ios-emoji
pkgver=14
pkgrel=5
pkgdesc='Apple Color Emoji is a color typeface used by iOS and macOS to display emoji'
arch=('any')
license=('unknown')
provides=(emoji-font)
depends=()
conflicts=(
'noto-fonts-emoji' 
'ttf-symbola'
'ttf-joypixels'
'ttf-twemoji-color'
'ttf-apple-emoji'
)

package() {
    install -dm 755 "${pkgdir}/usr/share/fonts/TTF"
        install -m 644 AppleColorEmoji.ttf "${pkgdir}/usr/share/fonts/TTF/"
}
