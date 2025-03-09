# macOS Sequoia on Lenovo ThinkPad L540 



<summary><strong>My Hardware</strong></summary>
<br>

| Category  | Component                            |
| --------- | ------------------------------------ |
| CPU       | Intel Core i5-4210M                 |
| GPU       | Intel HD Graphics 4600               |
| SSD       | Goodram SSD 240GB               |
| Memory    | 12GB DDR3 1333Mhz                     |
| WiFi & BT | Intel Wireless-N 7260                |

# Screenshots

![lock](https://github.com/user-attachments/assets/a5675f28-6cdc-4c02-a554-13e5416cc04a)
![home](https://github.com/user-attachments/assets/9e550539-c3ba-4afc-b8bc-14dc1cb1e19b)
![about](https://github.com/user-attachments/assets/113a40ca-35a2-4dce-a35b-6edaf8a17fc6)

# Status

- Bugs and long time loading desktop
  
<summary><strong>What's not working</strong></summary>
</br>

- Wi-Fi
- Audio Jack
- VGA
- Sleep
- Realtek Card Reader


# How to fix Intel HD Graphics 4600

- "amfi_get_out_of_my_way=1" - Add in config.plist boot-args
- Open terminal
- sudo spctl --master-disable
- Restart, go to recovery (press space in boot menu), choose utility, open terminal
- csrutil disable
- csrutil authenticated-root disable
- Restart
- Run OCLP (OpenCore Legacy Patcher)
- Press Post-install Root Patch
- Done



```Copyright (c) kitxchi 2024-2025```
