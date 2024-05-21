# stm32_driver
I tried to build a driver based on a youtube GOOD tutorial [here](https://youtu.be/z1Px6emHIeg), well explained, usint [STM32CubeIDE](https://www.st.com/en/development-tools/stm32cubemx.html) (v 6.11) for configuration, and loading the *.ioc file with [STM32CubeIDE](https://www.st.com/en/development-tools/stm32cubeide.html) (v 1.15.1). 

Problems, in some way, the generated code by STM32CubeMX fails some times, so building a NEW project from STM32CubeIDE, and there configuring the stm32, should be the best way to avoid those ANOYING errors at compiling time.

Parts needed:
1. STM32F103C8T6 board, better known as "[bluepill](https://vi.aliexpress.com/item/1005006706304043.html?spm=a2g0o.productlist.main.3.6b3e75b1YhHckj&algo_pvid=152be49a-ac90-4a81-a81b-6492c003d38c&algo_exp_id=152be49a-ac90-4a81-a81b-6492c003d38c-1&pdp_npi=4%40dis%21PEN%219.99%219.99%21%21%212.59%212.59%21%402101e9a217163092138587879ed1b0%2112000038059988882%21sea%21PE%212112184344%21&curPageLogUid=X9zf5SNnOcLI&utparam-url=scene%3Asearch%7Cquery_from%3A)"
2. An [oled ssd1306](https://www.ebay.com/itm/401599003676?itmmeta=01HYDZWZ9MNV6N8Z71KRQWFCV2&hash=item5d812a7c1c:g:FQcAAOSwM~Rbm3T0&itmprp=enc%3AAQAJAAAA0KPQT7EUPA6sz%2Bdvw2zeLI%2BbybUd2RqpUGOKeVR1hXHO%2B1LKNkTbF4j%2FHOlx3cLqKA9HNo40XybAe0ciGM7rOcgp5KXRpusV0zU%2Brkn2aVYj6x6tlOzUx6oFQvn4LUgvR4kaI2bVd6v8OkafJ8ryG0UIQGQWccet3U40ow%2BWQRyNFUvXtpWZeDBv4WSOHityR3sZ4wJB%2F4%2F%2BuDoBkZ4Q4%2F7A%2B0tGnYVvE69OMpkH6McFIc0IJzLTQE7wbISNz0UjdsSVqxZ6CJFmePgQvZBroqY%3D%7Ctkp%3ABk9SR_r087_zYw) or compatible screen, this was 0.96" size
3. [Female to Female cables](https://naylampmechatronics.com/cables/52-cable-jumper-dupont-hembra-a-hembra-20cm-20und.html) (x8 units to be exact)

## Wiring:

![imagen](https://github.com/davemaster/stm32_driver/assets/1075807/20ebf018-11c0-4b3a-b549-a54e216c0c57)
![imagen](https://github.com/davemaster/stm32_driver/assets/1075807/9ea3d9cd-1bb4-41d9-83e6-d1cd50607c7d)

## Code:
You can download this stm32 library, from this [link](https://github.com/afiskon/stm32-ssd1306) 
