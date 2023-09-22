# PARES_DIFERENCIALES_CYC1000
Fotografías y datos sobre los pares diferenciales escogidos para la creación de la placa ATLAS.

Integrado fpga -> 10CL025YU256C8G
Placa -> CYC1000

Colocamos la matriz de pineado en el emplazamiento del chip CYCLONE 10 LP y Procedemos a medir la ruta desde la matriz BGA a los pines de la placa CYC1000.

### CYC1000 en formato din A4 manteniendo las proporciones.
![CYC1000 en formato din A4](https://github.com/AtlasFPGA/PARES_DIFERENCIALES_CYC1000/blob/main/FOTOS/FOTO_ALTA_RESOLUCION_CYC1000_PINEADO.png)

### CYC1000 identificando los pares diferenciales y medición de longitud sabiendo que 265mm en el papel corresponden a 62mm reales.
![Identificación pares diferenciales CYC1000](https://github.com/AtlasFPGA/PARES_DIFERENCIALES_CYC1000/blob/main/FOTOS/P1040085.JPG)


## Pares diferenciales identificados por el nombre de su pin y la medida en milimetros sobre la hoja DIN A4.



| N2 | N1 | P2 | P1 | J2 | J1 | L15 | L16 |
| ----- | ---- |----- | ---- | ----- | ---- |----- | ---- |
| 10 | 10 | 24 | 10 | 7 | 8 | 7 | 7 |
| 70 | 60 | 53 | 10 | 13 | 22 | 39 | 48 |
| 21 | 23 | 8 | 4 | 18 | 19 | 8 | 7  |
| 2 | 5 | 2 | 8 | 12 | 10 | 0 | 3 |
| 3 | 0 | 4 | 5 | 2 | 0 | 0 | 0 |
| 3 | 0 | 2 | 6 | 0 | 0 | 0 | 0 |
| 0 | 0 | 0 | 2 | 0 | 0 | 0 | 0 |
| total | total | total | total | total | total | total | total |
| 109 | 98 | 93 | 45 | 59 | 58 | 54 | 65|
| Escala | Escala | Escala | Escala | Escala | Escala | Escala | Escala |
| 25,50 | 22,92_mm | 21,75_mm| 10,52_mm | 13,80_mm | 13,56_mm | 12,63_mm | 15,20_mm |

La escala esta en milímetros sobre la placa real CYC1000.

Correspondencia de las señales nomenclatura 10CL025YU256C8G y las salidas de vídeo de la placa ATLAS:

| TMDS | DVI | VGA64 | SCART128 | 10CL025YU256C8G |
| ----- | ---- |----- | ---- | ----- |
| TMDS[0] | CLK- | HS | CSYNC| L16 |
| TMDS[1] | CLK+ | VS | G[0] | L15 |
| TMDS[2] | 0- | BLUE[0] | B[0] | P1 |
| TMDS[3] | 0+ | BLUE[1] | [1] | P2 |
| TMDS[4] | 1- | GREEN[0] | G[1] | J1 |
| TMDS[5] | 1+ | GREEN[1] | G[2] | J2 |
| TMDS[6] | 2- | RED[0] | R[0] | N1 |
| TMDS[7] | 2+ | RED[1] | R[1] | N2 |
