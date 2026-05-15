# Restorative yoga for a Yamaha Clavinova CVP-87A

I'm kidnapping this fork for myself - sorry McVenco! ahahah! Since I tried to pull some new info I'd like to share, but I don't want to change the soul of the original repository, I decided to make this my own.
Long story short, after more than 5 years trying to revive a Clavinova CVP-87A, I finally did it. I wish I had documented better, but I am no blogger, sorry. I could promise you I will make some videos or tutorials teaching how I got there, but, really, I would be lying. You can read a little more on [my personal repository](https://www.electrolab.com.br/yamaha-cvp-87a-repair-the-full-saga/). Disclaimer: it´s really a personal knwoledge base where I write things for me and I really don't care much with beautifulness or grammar. It's more like a reminder of how I did achieved something. 

If you want to reach me, try email me to bGFiQGVsZWN0cm9sYWIuY29tLmJy (hint: base64) and I will answer you as soon as I can.

## Documentation

The docs helps, of course, but I added a new approach for those who wants to fix your old Clavinova at home. 

* [Service manual for Yamaha Clavinova CVP-85A CVP-87A](./documentation/manuals/yamaha_clavinova_cvp-85a_cvp-87a_service_manual.pdf)
* [Owner's manual for Yamaha Clavinova CVP-87A CVP-85A CVP-83S](./documentation/manuals/yamaha_clavinova_cvp-87a_cvp-85a_cvp-83s_owners_manual.pdf)
* [Ghidra from NSA](https://github.com/NationalSecurityAgency/ghidra)
* [TMS27C240](./documentation/datasheets/TMS27C240.PDF)
* [D27C8000D](./documentation/datasheets/AT27C800.PDF)
* [MCU H8/510 Datasheet](./documentation/datasheets/H8510%20Datasheet.pdf)
* [MCU H8/500 Programming guide](./documentation/datasheets/h8500%20Programming%20Manual.pdf)
  

## Equipment

In the sacred practice of restoration, we embrace the gentle companions of our journey, the tools that guide us on our path:

* [Yihua 862BD+ SMD hot air rework station with soldering iron](http://yihua-soldering.com/product-1-3-1-hot-air-rework-station-en/147662/)
* [Digital Multimeter]()
* [Precision screw driver set]()
* [Hu-friedy Curette Gracy 15/16](https://hufriedygroup.eu/en/products/periodontal/gracey-curettes/standard/sg1516r9e2-curette-gracey-1516-hdl-9-rigid-mesial)
* [Flux/solder paste](https://termopasty.pl/en/produkty/solder-paste/)
* [DriodCam as digital microscope](https://www.dev47apps.com/)
* [EPROM reader](https://pt.aliexpress.com/item/1005001970106758.html?spm=a2g0o.productlist.main.1.7af476b88V2B8P&algo_pvid=c12ebe61-5236-4413-9946-363bd460184b&algo_exp_id=c12ebe61-5236-4413-9946-363bd460184b-0&pdp_ext_f=%7B%22order%22%3A%22217%22%2C%22eval%22%3A%221%22%2C%22fromPage%22%3A%22search%22%7D&pdp_npi=6%40dis%21BRL%21140.53%21110.44%21%21%2126.57%2120.88%21%402103212317786696540167049e3a40%2112000018270006071%21sea%21BR%210%21ABX%211%210%21n_tag%3A-29910%3Bd%3Abff8c564%3Bm03_new_user%3A-29895%3BpisId%3A5000000204375211&curPageLogUid=dk4aVC3wjt3Y&utparam-url=scene%3Asearch%7Cquery_from%3A%7Cx_object_id%3A1005001970106758%7C_p_origin_prod%3A)

## Parts

* [SMD capacitors KIT](https://pt.aliexpress.com/item/1005009881452009.html?spm=a2g0o.productlist.main.2.44ae90Mc90McQ8&algo_pvid=d0df0d57-34b1-49dd-8230-208bdec48094&algo_exp_id=d0df0d57-34b1-49dd-8230-208bdec48094-1&pdp_ext_f=%7B%22order%22%3A%2245%22%2C%22eval%22%3A%221%22%2C%22fromPage%22%3A%22search%22%7D&pdp_npi=6%40dis%21BRL%21149.44%2169.72%21%21%21191.88%2189.52%21%40210319b717786697106208341ef6d6%2112000050463365107%21sea%21BR%210%21ABX%211%210%21n_tag%3A-29910%3Bd%3Abff8c564%3Bm03_new_user%3A-29895%3BpisId%3A5000000204375111&curPageLogUid=hvt3JW0NJVAh&utparam-url=scene%3Asearch%7Cquery_from%3A%7Cx_object_id%3A1005009881452009%7C_p_origin_prod%3A&tblci=GiC1XQY5gnhrit6B0Jp-JP78lLD2yt7AiSGFqtXUpWByhyDA9m4ox--0k9fQr-FuMIenSw)
* [SOP44 to DIP44](https://pt.aliexpress.com/item/1005010306838291.html?spm=a2g0o.productlist.main.1.4524P3dNP3dN1e&algo_pvid=0555f9db-25d0-4529-9455-1530957998f6&algo_exp_id=0555f9db-25d0-4529-9455-1530957998f6-0&pdp_ext_f=%7B%22order%22%3A%223%22%2C%22eval%22%3A%221%22%2C%22fromPage%22%3A%22search%22%7D&pdp_npi=6%40dis%21BRL%2124.39%2124.39%21%21%214.61%214.61%21%402101f70717786697928646999e893e%2112000051904003556%21sea%21BR%210%21ABX%211%210%21n_tag%3A-29910%3Bd%3Abff8c564%3Bm03_new_user%3A-29895&curPageLogUid=nDqWpD73oPKG&utparam-url=scene%3Asearch%7Cquery_from%3A%7Cx_object_id%3A1005010306838291%7C_p_origin_prod%3A&tblci=GiC1XQY5gnhrit6B0Jp-JP78lLD2yt7AiSGFqtXUpWByhyDA9m4ox--0k9fQr-FuMIenSw)
* [AM29F400BB](https://pt.aliexpress.com/item/4001315506149.html?spm=a2g0o.productlist.main.1.34a1ab0fnFeDLn&algo_pvid=a450c244-83ac-40ec-8846-3caf8711e66a&algo_exp_id=a450c244-83ac-40ec-8846-3caf8711e66a-0&pdp_ext_f=%7B%22order%22%3A%22143%22%2C%22eval%22%3A%221%22%2C%22fromPage%22%3A%22search%22%7D&pdp_npi=6%40dis%21BRL%2111.79%216.99%21%21%212.23%211.32%21%402103123917786698504938064e6af5%2112000016729921389%21sea%21BR%210%21ABX%211%210%21n_tag%3A-29910%3Bd%3Abff8c564%3Bm03_new_user%3A-29895%3BpisId%3A5000000204375142&curPageLogUid=sPLbG3FA5b5c&utparam-url=scene%3Asearch%7Cquery_from%3A%7Cx_object_id%3A4001315506149%7C_p_origin_prod%3A&tblci=GiC1XQY5gnhrit6B0Jp-JP78lLD2yt7AiSGFqtXUpWByhyDA9m4ox--0k9fQr-FuMIenSw)
 
## Gratitude

I want to express my heartfelt thanks to following souls for their unwavering support and guidance. Your kindness has made a significant impact on this journey

* [Drew Forchione](https://drewforchione.wordpress.com/about-me/) for his [blog](https://drewforchione.wordpress.com/portfolio/yamaha-cvp-87a-repair/)- [PDF mirror](./documentation/diagrams/yamaha_clavinova_cvp-87a_repair_guide_by_drewforchione.pdf)
* [McVenco](https://github.com/McVenco) who made this repository;
* Eduardo Alberto, from Canada;
* [Adrian Black](https://www.youtube.com/@adriansdigitalbasement) for showing me that PSRAM back in the 90's suck and fail all the time
* My wife for her patience, of course!
