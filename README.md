OWL-Predator v1.0
==============


for HTC Marvel/MarvelC / HTC Liberty / HTC ChaCha / HTC Legend
==============================================================

Changelog:
===========
- Update ADSP driver
- Update KGSL from Kernel 3.x
- Backport ashmem from Kernel 3.0
- Backport lowmemorykiller from Kernel 3.4
- Backport UHID driver from Kernel 3.8
- Fix Bluetooth tethering
- Fix YouTube [LQ/HQ]

marvel_defconfig
===========
- Add support CIFS/NFS
- Add zRam
- Add LZO


Features:
==========

* Governors:
- Superbad
- Skywalker
- Intellidemand
- Lagfree
- Lulzactive
- Lazy
- Brazilionwax
- Smartass
- SmartassV2
- SmartassH3 [Default]
- Minmax
- Smoothass
- Savagedzen
- InteractiveX
- Conservative
- OndemandX
- Ondemand
- Userspace
- Powersave
- LionHeart
- Performance


* Schedulers:
- Noop
- Deadline
- CFQ
- BFQ
- VR
- SIO [Default]

* Other Features:
- Ext2/3/4 support
- Swap support
- zRam that uses snappy
- Google snappy compression/decompression
- Zcache
- Frontswap
- FScache
- Cachefiles
- Cleancache

==============
                                                by OWL Project [Based on CRYPTOMILK Kernel]
