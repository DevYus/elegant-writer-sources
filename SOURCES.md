# Source code of the libraries shipped with Elegant Writer

This repository holds a copy of the source archives that correspond to the MSYS2 binary packages bundled in the
Windows build of Elegant Writer (the GTK runtime used for PDF export, and the GCC runtime libraries). The
binary packages are pinned by version and sha256 in `backend/packaging/gtk-runtime-lock.json` of the application.

The archives are attached to the release `v0.9.9-sources` of this repository
(https://github.com/DevYus/elegant-writer-sources/releases/tag/v0.9.9-sources); this file lists them. Each one is a copy of the file of the
same name published at https://repo.msys2.org/mingw/sources/: it holds the upstream tarball, the MSYS2 build recipe (`PKGBUILD`) and
the patches, i.e. what is needed to rebuild the package.

To request anything else, open an issue in this repository.

## Archives

| Source archive | Version | Binary packages (Elegant Writer lock) | Licence | Size (bytes) | SHA-256 | SHA-256 of the signature | Original address |
|---|---|---|---|---:|---|---|---|
| `mingw-w64-brotli-1.2.1-1.src.tar.zst` | 1.2.1-1 | `mingw-w64-ucrt-x86_64-brotli` | MIT | 645162 | `3dfc69b88a111ef4809928e81d4cb650ea9c7ba5da4ebd1bf28d6effdeeb6bd6` | `d0cd64eb605587c5350aa3b3e374107611f6fb7bf8a81e62fe16b63342eab3d6` | https://repo.msys2.org/mingw/sources/mingw-w64-brotli-1.2.1-1.src.tar.zst |
| `mingw-w64-bzip2-1.0.8-4.src.tar.zst` | 1.0.8-4 | `mingw-w64-ucrt-x86_64-bzip2` | custom | 818825 | `fd9360917314d1cbccb3cb15ed8450d1e56b8a9f733b606504aba52c52159e54` | `c122fdd19f4f35dc886557f71dcd21c9f147d663344680035cdd88dc17814ab7` | https://repo.msys2.org/mingw/sources/mingw-w64-bzip2-1.0.8-4.src.tar.zst |
| `mingw-w64-expat-2.10.0-1.src.tar.zst` | 2.10.0-1 | `mingw-w64-ucrt-x86_64-expat` | MIT | 545999 | `8473f4c38da677e7f0f2eabf9fb60404ea2ef80c5e465258a2724ceff4c1d331` | `3417393d228b52ce56b43ea66c048e564c2f7de0d5e7340f10ad6f9a044bb586` | https://repo.msys2.org/mingw/sources/mingw-w64-expat-2.10.0-1.src.tar.zst |
| `mingw-w64-fontconfig-2.18.3-1.src.tar.zst` | 2.18.3-1 | `mingw-w64-ucrt-x86_64-fontconfig` | custom | 659688 | `7df65dbf84397f4f71c6aa0bd39fac93f839d6b87f04a935773b69828740230d` | `a608d6a852956be7e1b9c1950326113cb6fe4402f393d8b8fc3ccc0dd9bc7ab8` | https://repo.msys2.org/mingw/sources/mingw-w64-fontconfig-2.18.3-1.src.tar.zst |
| `mingw-w64-freetype-2.15.0-1.src.tar.zst` | 2.15.0-1 | `mingw-w64-ucrt-x86_64-freetype` | GPL-2.0-or-later OR FTL | 2720468 | `2f09c60b72bd249642d055aa5a34edf2577392e592415f3f4730dd37990b47ad` | `4ecd6179f3bf1ff12c85776ed409cee3eaeee2ee08b0174ec8edec750908200a` | https://repo.msys2.org/mingw/sources/mingw-w64-freetype-2.15.0-1.src.tar.zst |
| `mingw-w64-fribidi-1.0.18-1.src.tar.zst` | 1.0.18-1 | `mingw-w64-ucrt-x86_64-fribidi` | LGPL-2.1-or-later | 1224214 | `7cd0b6290516a7d61b1508d79c18d2661170a0e3189582ded99bd9879cc159b2` | `574a4e510317afccf4f0cb165e719088cedec7240c6edbb67ae56bf03ea1f363` | https://repo.msys2.org/mingw/sources/mingw-w64-fribidi-1.0.18-1.src.tar.zst |
| `mingw-w64-gcc-16.2.0-6.src.tar.zst` | 16.2.0-6 | `mingw-w64-ucrt-x86_64-libgcc`, `mingw-w64-ucrt-x86_64-libstdc++` | GPL-3.0-or-later WITH GCC-exception-3.1 AND GFDL-1.3-or-later | 107229138 | `a901d8afb78438abcff9ed020cd9aa9431db76de1992171c2454c3c07ad289e8` | `4e6dcbe01d9b6072c7416a9e7d6d306f245a05e828e49d30a774d31de23badbf` | https://repo.msys2.org/mingw/sources/mingw-w64-gcc-16.2.0-6.src.tar.zst |
| `mingw-w64-gettext-1.0-1.src.tar.zst` | 1.0-1 | `mingw-w64-ucrt-x86_64-gettext-runtime` | GPL-3.0-or-later AND LGPL-2.1-or-later | 10267655 | `cca0d0c8f60353faccc5ad40405240014e4a7ccc8b1c6ca9f4626aef3097d26e` | `daaa76ab77b852c1d62de5ab2338b026a5281e6d208a5f83e963f19c504baf95` | https://repo.msys2.org/mingw/sources/mingw-w64-gettext-1.0-1.src.tar.zst |
| `mingw-w64-glib2-2.90.1-1.src.tar.zst` | 2.90.1-1 | `mingw-w64-ucrt-x86_64-glib2` | LGPL-2.1-or-later | 5875958 | `ac3bc00e4079e6b51dd0a1fb9ccc420fff033b4e9095e4487dbf6cf01312cee6` | `8a4a15f9134d813d9e525a0ecf67a587cf5a414138b5019e6a37b1a8a7d59e4d` | https://repo.msys2.org/mingw/sources/mingw-w64-glib2-2.90.1-1.src.tar.zst |
| `mingw-w64-graphite2-1.3.15-1.src.tar.zst` | 1.3.15-1 | `mingw-w64-ucrt-x86_64-graphite2` | LGPL-2.1-or-later | 13317053 | `eb76ce274c68ea6bad0883144c21e44a803ec94fed9dc0f6584feb0a8415a1d6` | `e90d1ad525400918fbe5956243071f70d1ecda382778f9b9a3fed1669cff9a86` | https://repo.msys2.org/mingw/sources/mingw-w64-graphite2-1.3.15-1.src.tar.zst |
| `mingw-w64-harfbuzz-15.1.0-1.src.tar.zst` | 15.1.0-1 | `mingw-w64-ucrt-x86_64-harfbuzz` | MIT | 20519808 | `fcfb6610eecb6945d7b6c05fca828846a15881083e23da0557e0a2960cd013c1` | `dfbbef73f09e0c73762111208dc2d95dece746966bed5d70a6c4d2815246c099` | https://repo.msys2.org/mingw/sources/mingw-w64-harfbuzz-15.1.0-1.src.tar.zst |
| `mingw-w64-libdatrie-0.2.14-1.src.tar.zst` | 0.2.14-1 | `mingw-w64-ucrt-x86_64-libdatrie` | LGPL | 327473 | `da58ca439051a8cfb1d7f15cdd82af104e1ea1eeefdb090e608d2305a747df7d` | `8ef120af8e79a47174acfd6fba43ac5f7d3348b59437e6cfa092942d3f639ee8` | https://repo.msys2.org/mingw/sources/mingw-w64-libdatrie-0.2.14-1.src.tar.zst |
| `mingw-w64-libffi-3.8.0-1.src.tar.zst` | 3.8.0-1 | `mingw-w64-ucrt-x86_64-libffi` | MIT | 1582238 | `641ea78ce0333839eab5262656f03fdcfd8496d7388bd7b27e4f0638aeed9adf` | `0d301f47149d81169bd5e45b69151fd40bcb882d2bed129c9cbe3bf3f52d912a` | https://repo.msys2.org/mingw/sources/mingw-w64-libffi-3.8.0-1.src.tar.zst |
| `mingw-w64-libiconv-1.19.1-1.src.tar.zst` | 1.19.1-1 | `mingw-w64-ucrt-x86_64-libiconv` | LGPL-2.1-or-later | 5104269 | `ed46bb1b524ad9bd9d843091bf7b18ab23e5cd21fef6de743c8c943bdc11dabe` | `094a812672283d4ae7dcf8a5256ec3510d7410233749510f17d4f336b70111c7` | https://repo.msys2.org/mingw/sources/mingw-w64-libiconv-1.19.1-1.src.tar.zst |
| `mingw-w64-libpng-1.6.59-2.src.tar.zst` | 1.6.59-2 | `mingw-w64-ucrt-x86_64-libpng` | custom | 1611367 | `7f7c029d119427fe7b36be8a79228f831062bedadee1f49c9e0919fe6d7a459a` | `785b0a5516d5bbc4a382dfb9b860793785169beafa490a2c354278a9648436f2` | https://repo.msys2.org/mingw/sources/mingw-w64-libpng-1.6.59-2.src.tar.zst |
| `mingw-w64-libthai-0.1.30-1.src.tar.zst` | 0.1.30-1 | `mingw-w64-ucrt-x86_64-libthai` | LGPL-2.1-or-later | 438909 | `e4f8d840fca132eb47aed311fc2c36dc59604b9ecd0aa310161b9d1e2cee4d03` | `ae21ce08282f1c585b1a152e1f85a93b19f69af44c35df585d1e83a72c8017b7` | https://repo.msys2.org/mingw/sources/mingw-w64-libthai-0.1.30-1.src.tar.zst |
| `mingw-w64-pango-1.58.2-1.src.tar.zst` | 1.58.2-1 | `mingw-w64-ucrt-x86_64-pango` | LGPL-2.1 | 1920389 | `df981b2c47d9344f3a4869645a8f2392916dac3e470634778453410ec813e390` | `0d7f367c6fe30eac99c87e6788cc8b3b79ae68dacd7d28778f4fa707f96b57a7` | https://repo.msys2.org/mingw/sources/mingw-w64-pango-1.58.2-1.src.tar.zst |
| `mingw-w64-pcre2-10.49-2.src.tar.zst` | 10.49-2 | `mingw-w64-ucrt-x86_64-pcre2` | BSD-3-Clause | 2184385 | `a0834cd8808867aaa3d0065eefcb12a2be09735a6c398c3da9301187e8517ead` | `ee730a948c17e70123f4d0647b4ae599ab391df8dee096efe28e67d6f6c8dd69` | https://repo.msys2.org/mingw/sources/mingw-w64-pcre2-10.49-2.src.tar.zst |
| `mingw-w64-winpthreads-14.0.0.r598.ge3d18511f-1.src.tar.zst` | 14.0.0.r598.ge3d18511f-1 | `mingw-w64-ucrt-x86_64-libwinpthread` | MIT AND BSD-3-Clause | 59897216 | `1da3dad4f6916d0c23e8fe76c38ed79946fb32078f94047c0475229b8112a1db` | `5b201422206762eea7cc9a39e667160c0093b69cb74d5a858b870de0fbea4365` | https://repo.msys2.org/mingw/sources/mingw-w64-winpthreads-14.0.0.r598.ge3d18511f-1.src.tar.zst |
| `mingw-w64-zlib-ng-2.3.3-2.src.tar.zst` | 2.3.3-2 | `mingw-w64-ucrt-x86_64-zlib-ng-compat` | Zlib | 2432615 | `ef7a4579ba62860903cf0e7e151745bac3b0bdead0a1244befa4dbf1d5cfc3c4` | `64500eacd07fa1d5a31c80f83dd53955a27d41b085b2aa1c21f1f9d4b940ff40` | https://repo.msys2.org/mingw/sources/mingw-w64-zlib-ng-2.3.3-2.src.tar.zst |

20 archives, 239322829 bytes in total.

## Checking a copy

Download the archives, their `.sig` files and `SHA256SUMS` from the release into one folder, then:

```
sha256sum -c SHA256SUMS
```

MSYS2 signs each source archive (detached PGP signature, the `.sig` file next to it). The signing key
is the MSYS2 development key, fingerprint `5F944B027F7FE2091985AA2EFA11531AA0AA7F57`, published in the MSYS2 keyring
(https://github.com/msys2/MSYS2-keyring, file `msys2.gpg`). With that key imported:

```
gpg --verify mingw-w64-gcc-<version>.src.tar.zst.sig mingw-w64-gcc-<version>.src.tar.zst
```

The sha256 values above were computed when the archives were copied; MSYS2 itself publishes signatures, not
checksums, for its source archives.
