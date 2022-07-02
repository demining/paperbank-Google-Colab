-------------------------
### Run paperbank-Google-Colab

https://colab.research.google.com/drive/1OShIMVcFZ_khsUIBOIV1lzrqAGo1gfm_?usp=sharing

-------------------------

check other branches for future enhancements

- MAIN branch will be the new master
- VANITY branch should have vanitygen integration
- this branch will be named HELLO_WORLD in the future, right now check the MAIN branch


## Installing 

### prerequisites

I don't know about the other OSes but

on linux it's all pretty easy

- install ruby

- install libmagickcore-dev and libmagickwand-dev (the first cna be libmagick-dev in some cases)

- gem install escper

- gem install rqrcode_png

- edit miniprint.rb

configure your printer and your receiving address:

    PRINTER = "/dev/usb/lp1"
    DATA = "1Jxvq9...pPVup"


### running


    ruby miniprint.rb


this should work on Debian out of the box!


----

|  | Donation Address |
| --- | --- |
| ♥ __BTC__ | 1Lw2kh9WzCActXSGHxyypGLkqQZfxDpw8v |
| ♥ __ETH__ | 0xaBd66CF90898517573f19184b3297d651f7b90bf |
