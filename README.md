# bpi-r2-debian

https://forum.banana-pi.org/t/bpi-r2-new-image-debian-10-buster-image-with-kernel-4-19-62/9601
にあるgoogle driveへのリンクで飛んだ先に、bpi-r2-bullseye_incomplete.img.gzがある。

* これを32GBのmicroSDに書き込み、Banana Pi R2を起動したあと、bookwormまで更新した。
* wan portが静的に設定(192.168.0.18/24)されていたので、DHCPで動的に設定するように変更した。

このmicroSDからイメージを取り出したものをreleaseにおいてある。このイメージを使うときは32GB以上のmicroSDを用意すること。

https://forum.banana-pi.org/t/bpi-r2-new-image-debian-10-buster-image-with-kernel-4-19-62/9601There is a link to Google Drive where bpi-r2-bullseye_incomplete.img.gz is located.

* After writing this to a 32GB microSD and booting the Banana Pi R2, I updated it to Bookworm.
* The wan port was statically set to 192.168.0.18/24, so I changed it to be dynamically set via DHCP.

The image extracted from this microSD is available in the release. When using this image, please prepare a microSD card of 32GB or larger.
