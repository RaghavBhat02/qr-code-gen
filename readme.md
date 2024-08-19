# QR Code Gen

## The Why

This app is built for the purpose of generating nice QR codes. I was trying to generate QR codes for the Music Meditation Club at the University of Michigan, and realized that pretty much any QR code generation website makes you pay to do nice things like curved squares, tracking, centered logos, etc. So I decided I'd just create my own. Problem is that most QR Code generation libraries that I looked at don't support all of the features I'd like them to (primarily looked at ones in Go and Java). Plus the go to Java library is now in maintanence-only mode. Thus I decided to create it from scratch, and more deeply understand Java while doing so.

## Roadmap

### v0.1

[ ] Generate basic QR Code Version 1 with M error-correction level, no fancy features
[ ] Curved Squares
[ ] Logo in middle
[ ] Link tracking

### v1

[ ] Add Versions 2+
[ ] Add the remaining error correction levels
