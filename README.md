# EFI RYZEN 7 5700G - B550M PLUS


**Verões testadas do macOS**: Ventura e Sonoma (beta 1)

**Verão do OpenCore**: 0.9.4

## Especificações

| **Componente** | **Modelo**                       |
| ------------- | --------------------------------------------------------------- |
| Placa Mãe     | Asus TUF Gaming B550M PLUS                                      |
| CPU           | AMD Ryzen 7 5700G                                               |
| GPU           | RX 580 8G Jieshuo ([Vbios da MSI RX 470 8 GB BIOS][vbios-gpu])  |
| RAM           | 16GB @ 3200 MHz                                                 |
| Armazenamento | SSD WD Green 2.5, 480gb (só para o Mac)                         |
| Armazenamento | NVMe SSD XPG Gammix, 240gb (Win10)                              |
| Ethernet      | Realtek PCIe 2.5Gbe family controller                           |

### Observações
- Efi elaborada com base nos vídeos e lives do brabo [Gabriel Luchina][universo-hackintosh]
- Ainda refinando a EFI, mas deu boot sem problemas no Ventura e consgeui rodar várias programas como XCode o simulador do iPhone, também testei alguns jogos como Aslphalt só para ver se funcionva e foi.

### Ainda falta fazer
- Mapear USBs
- Ajustar kexts de áudio.
- Testar outras vbios para RX, a atual até funciona bem, porém as fans só ligam acima de 70 graus mais ou menos. Pra todos os efeitos sem a GPU o sistema boot normal com a APU do processador.


[vbios-gpu]: https://www.techpowerup.com/vgabios/189348/msi-rx470-8192-161121
[universo-hackintosh]: https://www.youtube.com/channel/UCZl_huXnf8T4e0dHv5zdFlw
