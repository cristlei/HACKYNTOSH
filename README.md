# HACKYNTOSH
EFI para PC Gigabyte B560M Aorus Elite.
Placa mae intel Tiger Point B560M, intel Comet Lake-S
O Processador eo HexaCore intel i5-10400, 4000 Mhz (41 x 100) G0,G1 intel.
A placa Grafica integrada e intel (R) UHD Graphics 630 (1GB).
PC placa ethernet: Realtek Gaming 2.5GbE Famyli Controller (LucyRTL8125Ethernet.kext)
PC Audio: Realtek ALC897 @intel Audio Controle (AppleALC.kext).
SSD NVME: XPG GAMMIX S41 PCI-E 3.0 X4  ( NVMeFix.Kext ) .
USB intel Tiger Point PCH-USB 3.2 Geb 2x1
Bios: F8 ( American Megatrends International,LLC

E preciso modificar os seriais no arquivo config.plist, que se encontra dentro da pasta.
EFI/OC abra com ProperTree , crie o serial com GenSMBIOS.
Opcao 3 , depois nome do MAC.
Exemplo: iMac20,1 para i3,i5 ate 8 Cores
E iMac20,2 para i9 10 Cores em diante.

Type:         iMac00,0
Serial:       AAAAAAAAAAA
Board Serial: AAAAAAAAAAAAA
SmUUID:       AAAAAAAAA-AAAAAA-AAAAAA-AAAAAA
Apple ROM:   AAAAAAAAAAAAAAA

