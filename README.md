# Mertensia32

![alt text](https://github.com/fsctnh/Mertensia32/blob/260b1adb204e24101faeb97b6308a401522a7cd8/MainLogo.png)

## Uma placa compacta de desenvolvimento Wireless e Bluetooth STM32WB55CEU6

### Contém:
* Conectividade USB-C
* Microcontrolador STM32 Programável
* Conector SWD TagConnect para ST-Link e Programador
* Slot de antena RF para compatibilidade Bluetooth
* Conector UART
* Design Compacto

Essa placa foi uma tentativa minha de realizar um design compacto e minha primeira vez mexendo em múltiplas camadas, mesmo que relativamente pouco.
Agradecimento especial ao canal Phil's Lab (Philip Salmony) pelos tutoriais de KiCad.

Possíveis atualizações futuras incluem:
* Expor os pinos para inserção de componentes TH (Semelhante ao Arduino Pro Micro)
* Melhorar posicionamento de vias

**_Isso é uma placa bem amadora. Manufature por sua própria conta e risco._**

# Imagens
## Esquemática:
![alt text](https://github.com/fsctnh/Mertensia32/blob/dd81cdb73c4c8b27ddba23150ceea8005d9483a2/schematicMertensia.png)

## Render 3D:
#### Vista de Cima:
![alt text](https://github.com/fsctnh/Mertensia32/blob/dd81cdb73c4c8b27ddba23150ceea8005d9483a2/3dviewtop.png)
#### Vista de Baixo:
![alt text](https://github.com/fsctnh/Mertensia32/blob/dd81cdb73c4c8b27ddba23150ceea8005d9483a2/3dbiewbot.png)

## Configuração do Chip:
___(Feito com STM32CubeMX)___


![alt text](https://github.com/fsctnh/Mertensia32/blob/98eea7696beb9d2136c9893db0a6ed6fd118847f/Chip_Config.png)

# Arquivos Adicionais:
A pasta de manufatura contém alguns arquivos além dos gerbers necessários pra manufatura:
* ***BOM (Bill of Materials)***: Arquivo CSV contendo todos os componentes usados, em quais modelos e quais quantidades, alguns possuem datasheets e outros valores linkados;
* ***Arquivos .pos***: Lista de coordenadas para cada peça, tanto SMD quanto TH. É usado pela máquina Pick and Place no processo de manufatura.
