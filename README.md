# hackintosh-z490-vision-g

My OpenCore EFI folder for my hackintosh on a Z490 Vision G motherboard.

Currently running on macOS Big Sur 11.2 and OpenCore 0.6.6

Full Specs:

- Gigabyte Z490 Vision G Motherboard
- Intel i9-10900K
- G.SKILL Ripjaws V Series 32GB DDR4 3200 CL16 RAM
- Sabrent 1TB Rocket NVMe 4.0 M.2
- Fenvi FV-T919
- AMD RX 570 w/4GB VRAM

My EFI folder is heavily based off of [SchmockLord](https://github.com/SchmockLord/Hackintosh-Intel-i9-10900k-Gigabyte-Z490-Vision-D) and [samuel21119's](https://github.com/samuel21119/Intel-i9-10900-Gigabyte-Z490-Vision-G-Hackintosh) configs.

Notes:

- I would not recommend the Fenvi FV-T919 wireless card. It does support airdrop in the technical sense but the signal strength is very poor and it has only worked when putting the other device directly next to the antenna (and even then only sometimes). I even tried getting an external antenna but to no avail.

- I initially tried the [Samsung 970 EVO Plus](https://smile.amazon.com/gp/product/B07MFZY2F2) but it caused significant system lag which is apparently common with samsung SSDs on macOS.