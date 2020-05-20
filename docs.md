#  Assets

untuk simple aset seperti diamond.png letakan di images/

and define asset in `pubspec.yml`

untuk icon:
buka appicon.co
lalu drag and drop icon.png milikmu
pilih
- android
- iphone

click generate maka akan di buatkan icon untuk android dan iphon

## Android Icon
untuk config icon android
replace directory `android/app/src/main/res/mipmap-*` dengan hasil generate icon untuk android


## Ios Icon
replace directory `ios/Runner/Assets.xcassets` dengan hasil generate icon ios

inside page of pubscpec.yml don't forget to click `Packages get`