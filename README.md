<h1>Huawei Matebook D15 AMD</h1>
<img src="https://www.notebookcheck.net/fileadmin/Notebooks/Huawei/MateBook_D_15-53010TUY/Huawei_MateBook_D_15_7.jpg">
<img src="https://www.notebookcheck.net/fileadmin/Notebooks/Huawei/MateBook_D_15-53010TUY/Huawei_MateBook_D_15_4.jpg">
<img src="https://www.notebookcheck.net/fileadmin/Notebooks/Huawei/MateBook_D_15-53010TUY/Huawei_MateBook_D_15_5.jpg">
<img src="https://www.notebookcheck.net/fileadmin/_processed_/0/3/csm_Huawei_MateBook_D_15_Wartung_49913b894d.jpg">

- Photos courtesy of: 
<a href="https://www.notebookcheck.net/Huawei-MateBook-D-15-Laptop-Review-Still-a-good-notebook-with-AMD.456383.0.html">NotebookCheck</a> 
<h2>Specs: </h2>

- CPU: AMD Ryzen 5 3500U
- Memory: Soldered 8GB 2400Mhz Sk Hynix
- SSD: Any M.2 NVME should work
  - Samsung 980 500GB
- GPU: AMD Radeon RX Vega 8
  - Set to 1GB of VRAM
 
- Display: 15" Integrated, IPS, 1920x1080
- WLAN: Intel AX210 Wi-Fi 6
- Portage:
  - USB-C 3.2 Gen 1
  - USB-A 3.2 Gen 1
  - 2x USB-A 2.0
  - HDMI 1.4b
  - Headphone / mic combo

<p></p>

# This is just the standalone EFI file i used to install MacOS Ventura. 


Please change the SMBios. The used SMBios was **MacbookPro16,3**.
Heres how to do it: https://www.youtube.com/watch?v=8MsueH5EouQ 
\
\
After downloading don't copy the README.md file to your USB drive. 
If you have any trouble booting/installing add "-v" to the front of your boot-args, so you can figure out what's wrong.

When in bootloader press (space) and select dmg.
Also, make sure you create an "EFI" file and put the "BOOT" and "OC" files in it.
