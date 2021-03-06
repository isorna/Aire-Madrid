# Lectura de datos

La lectura de datos se realiza desde [Firebase](https://airemadrid.firebaseio.com/) y esta la estructura, en caso de querer usar estos datos en tu aplicación.

## Estructura por estaciones

Puedes verificar que la lectura de datos esta alineada con los datos del Ayuntamiento ejecutando una funcion.

```javascript
controlEstaciones ();
```

Esta función devuelve por consola todos los detalles.

No te olvides de habilitar el modoDebug antes, ya que al estar deshabilitado los mensajes por consola estan en mute.

```javascript
debugMode = true;
```

**Estaciones y keys**

Empieza | Termina | Estación
------------ | ------------- | -------------
0 | 22 | Media de la Red
23 | 33 | Plaza España
34 | 48 | Escuelas Aguirre
49 | 56 | Av. Ramón y Cajal
57 | 63 | Arturo Soria
64 | 69 | Villaverde Alto
68 | 80 | Farolillo
70 | 105 | Casa de Campo
106 | 110 | Barajas
111 | 117 | Pza Carmen
118 | 125 | Moratalaz
126 | 137 | Cuatro Caminos
138 | 144 | Barrio del Pilar
145 | 151 | Vallecas
152 | 157 | Méndez Álvaro
158 | 163 | Castellana
164 | 168 | Retiro
169 | 173 | Pza. Castilla
174 | 183 | Ensanche de Vallecas
184 | 194 | Urb. Embajada
195 | 205 | Pza. Fdez. Ladreda
206 | 213 | Sanchinarro
214 | 218 | El Prado
219 | 231 | Parque Juan Carlos I
232 | 239 | Tres Olivos

## Estructura en detalles

*Media de la red no es una estación. Es la media de datos*

Estación | Valor | Enlace
------------ | ------------- | -------------
Media de la Red | Dióxido de Azufre (S02) | [https://airemadrid.firebaseio.com/last/0](https://airemadrid.firebaseio.com/last/0)
Media de la Red | Monóxido de Carbono (CO) | [https://airemadrid.firebaseio.com/last/1](https://airemadrid.firebaseio.com/last/1)
Media de la Red | Monóxido de Nitrógeno (NO) | [https://airemadrid.firebaseio.com/last/2](https://airemadrid.firebaseio.com/last/2)
Media de la Red | Dióxido de Nitrógeno (NO2) | [https://airemadrid.firebaseio.com/last/3](https://airemadrid.firebaseio.com/last/3)
Media de la Red | Partículas en suspensión (-2.5) | [https://airemadrid.firebaseio.com/last/4](https://airemadrid.firebaseio.com/last/4)
Media de la Red | Partículas en suspensión (-10) | [https://airemadrid.firebaseio.com/last/5](https://airemadrid.firebaseio.com/last/5)
Media de la Red | Óxidos de Nitrógeno totales (NOx) | [https://airemadrid.firebaseio.com/last/6](https://airemadrid.firebaseio.com/last/6)
Media de la Red | Ozono (O3) | [https://airemadrid.firebaseio.com/last/0](https://airemadrid.firebaseio.com/last/7)
Media de la Red | Tolueno (C6H5CH3) | [https://airemadrid.firebaseio.com/last/0](https://airemadrid.firebaseio.com/last/8)
Media de la Red | Benceno (C6H6) | [https://airemadrid.firebaseio.com/last/0](https://airemadrid.firebaseio.com/last/9)
Media de la Red | Etilbenceno (C6H5CH2CH3) | [https://airemadrid.firebaseio.com/last/0](https://airemadrid.firebaseio.com/last/10)
Media de la Red | Hidrocarburos Totales (HC) | [https://airemadrid.firebaseio.com/last/0](https://airemadrid.firebaseio.com/last/11)
Media de la Red | Metano (CH4) | [https://airemadrid.firebaseio.com/last/0](https://airemadrid.firebaseio.com/last/12)
Media de la Red | Hidrocarburos No Metánicos (NMH) | [https://airemadrid.firebaseio.com/last/0](https://airemadrid.firebaseio.com/last/13)
Media de la Red | Radiación Ultravioleta (UV) | [https://airemadrid.firebaseio.com/last/0](https://airemadrid.firebaseio.com/last/14)
Media de la Red | Velocidad del Viento (VV) | [https://airemadrid.firebaseio.com/last/0](https://airemadrid.firebaseio.com/last/15)
Media de la Red | Dirección del Viento (DD) | [https://airemadrid.firebaseio.com/last/0](https://airemadrid.firebaseio.com/last/16)
Media de la Red | Temperatura Media (TMP) | [https://airemadrid.firebaseio.com/last/0](https://airemadrid.firebaseio.com/last/17)
Media de la Red | Temperatura Mínima (TMI) | [https://airemadrid.firebaseio.com/last/0](https://airemadrid.firebaseio.com/last/18)
Media de la Red | Humedad Relativa (HR) | [https://airemadrid.firebaseio.com/last/0](https://airemadrid.firebaseio.com/last/19)
Media de la Red | Presión Barométrica (PRB) | [https://airemadrid.firebaseio.com/last/0](https://airemadrid.firebaseio.com/last/20)
Media de la Red | *Valor Desconocido* | [https://airemadrid.firebaseio.com/last/0](https://airemadrid.firebaseio.com/last/21)
Media de la Red | *Valor Desconocido* | [https://airemadrid.firebaseio.com/last/0](https://airemadrid.firebaseio.com/last/22)
Plaza España | Dióxido de Azufre (S02) | [https://airemadrid.firebaseio.com/last/23](https://airemadrid.firebaseio.com/last/23)
Plaza España | Monóxido de Carbono (CO) | [https://airemadrid.firebaseio.com/last/24](https://airemadrid.firebaseio.com/last/24)
Plaza España | Monóxido de Nitrógeno (NO) | [https://airemadrid.firebaseio.com/last/25](https://airemadrid.firebaseio.com/last/25)
Plaza España | Dióxido de Nitrógeno (NO2) | [https://airemadrid.firebaseio.com/last/26](https://airemadrid.firebaseio.com/last/26)
Plaza España | Óxidos de Nitrógeno totales (NOx) | [https://airemadrid.firebaseio.com/last/27](https://airemadrid.firebaseio.com/last/27)
Plaza España | Velocidad del Viento (VV) | [https://airemadrid.firebaseio.com/last/29](https://airemadrid.firebaseio.com/last/28)
Plaza España | Dirección del Viento (DD) | [https://airemadrid.firebaseio.com/last/29](https://airemadrid.firebaseio.com/last/29)
Plaza España | Temperatura Media (TMP) | [https://airemadrid.firebaseio.com/last/30](https://airemadrid.firebaseio.com/last/30)
Plaza España | Temperatura Mínima (TMI) | [https://airemadrid.firebaseio.com/last/31](https://airemadrid.firebaseio.com/last/31)
Plaza España | Humedad Relativa (HR) | [https://airemadrid.firebaseio.com/last/32](https://airemadrid.firebaseio.com/last/32)
Plaza España | *Valor Desconocido* | [https://airemadrid.firebaseio.com/last/33](https://airemadrid.firebaseio.com/last/33)
Escuelas Aguirre | Dióxido de Azufre (S02) | [https://airemadrid.firebaseio.com/last/34](https://airemadrid.firebaseio.com/last/34)
Escuelas Aguirre | Monóxido de Carbono (CO) | [https://airemadrid.firebaseio.com/last/35](https://airemadrid.firebaseio.com/last/35)
Escuelas Aguirre | Monóxido de Nitrógeno (NO) | [https://airemadrid.firebaseio.com/last/36](https://airemadrid.firebaseio.com/last/36)
Escuelas Aguirre | Dióxido de Nitrógeno (NO2) | [https://airemadrid.firebaseio.com/last/37](https://airemadrid.firebaseio.com/last/37)
Escuelas Aguirre | Partículas en suspensión (-2.5) | [https://airemadrid.firebaseio.com/last/38](https://airemadrid.firebaseio.com/last/38)
Escuelas Aguirre | Partículas en suspensión (-10) | [https://airemadrid.firebaseio.com/last/39](https://airemadrid.firebaseio.com/last/39)
Escuelas Aguirre | Óxidos de Nitrógeno totales (NOx) | [https://airemadrid.firebaseio.com/last/40](https://airemadrid.firebaseio.com/last/40)
Escuelas Aguirre | Ozono (O3) | [https://airemadrid.firebaseio.com/last/41](https://airemadrid.firebaseio.com/last/41)
Escuelas Aguirre | Tolueno (C6H5CH3) | [https://airemadrid.firebaseio.com/last/42](https://airemadrid.firebaseio.com/last/42)
Escuelas Aguirre | Benceno (C6H6) | [https://airemadrid.firebaseio.com/last/43](https://airemadrid.firebaseio.com/last/43)
Escuelas Aguirre | Etilbenceno (C6H5CH2CH3) | [https://airemadrid.firebaseio.com/last/44](https://airemadrid.firebaseio.com/last/44)
Escuelas Aguirre | Hidrocarburos Totales (HC) | [https://airemadrid.firebaseio.com/last/45](https://airemadrid.firebaseio.com/last/45)
Escuelas Aguirre | Metano (CH4) | [https://airemadrid.firebaseio.com/last/46](https://airemadrid.firebaseio.com/last/46)
Escuelas Aguirre | Hidrocarburos No Metánicos (NMH) | [https://airemadrid.firebaseio.com/last/47](https://airemadrid.firebaseio.com/last/47)
Escuelas Aguirre | Temperatura Mínima (TMI) | [https://airemadrid.firebaseio.com/last/48](https://airemadrid.firebaseio.com/last/48)
Ramón y Cajal | Monóxido de Nitrógeno (NO) | [https://airemadrid.firebaseio.com/last/49](https://airemadrid.firebaseio.com/last/49)
Ramón y Cajal | Dióxido de Nitrógeno (NO2) | [https://airemadrid.firebaseio.com/last/50](https://airemadrid.firebaseio.com/last/50)
Ramón y Cajal | Óxidos de Nitrógeno totales (NOx) | [https://airemadrid.firebaseio.com/last/51](https://airemadrid.firebaseio.com/last/51)
Ramón y Cajal | Tolueno (C6H5CH3) | [https://airemadrid.firebaseio.com/last/52](https://airemadrid.firebaseio.com/last/52)
Ramón y Cajal | Benceno (C6H6) | [https://airemadrid.firebaseio.com/last/53](https://airemadrid.firebaseio.com/last/53)
Ramón y Cajal | Etilbenceno (C6H5CH2CH3) | [https://airemadrid.firebaseio.com/last/54](https://airemadrid.firebaseio.com/last/54)
Ramón y Cajal | Temperatura Mínima (TMI) | [https://airemadrid.firebaseio.com/last/55](https://airemadrid.firebaseio.com/last/55)
Ramón y Cajal | *Valor Desconocido* | [https://airemadrid.firebaseio.com/last/56](https://airemadrid.firebaseio.com/last/56)
Arturo Soria | Monóxido de Carbono (CO) | [https://airemadrid.firebaseio.com/last/57](https://airemadrid.firebaseio.com/last/57)
Arturo Soria | Monóxido de Nitrógeno (NO) | [https://airemadrid.firebaseio.com/last/58](https://airemadrid.firebaseio.com/last/58)
Arturo Soria | Dióxido de Nitrógeno (NO2) | [https://airemadrid.firebaseio.com/last/59](https://airemadrid.firebaseio.com/last/59)
Arturo Soria | Óxidos de Nitrógeno totales (NOx) | [https://airemadrid.firebaseio.com/last/60](https://airemadrid.firebaseio.com/last/60)
Arturo Soria | Ozono (O3) | [https://airemadrid.firebaseio.com/last/61](https://airemadrid.firebaseio.com/last/61)
Arturo Soria | Temperatura Mínima (TMI) | [https://airemadrid.firebaseio.com/last/62](https://airemadrid.firebaseio.com/last/62)
Arturo Soria | *Valor Desconocido* | [https://airemadrid.firebaseio.com/last/63](https://airemadrid.firebaseio.com/last/63)
Villaverde Alto | Dióxido de Azufre (S02) | [https://airemadrid.firebaseio.com/last/64](https://airemadrid.firebaseio.com/last/64)
Villaverde Alto | Monóxido de Nitrógeno (NO) | [https://airemadrid.firebaseio.com/last/65](https://airemadrid.firebaseio.com/last/65)
Villaverde Alto | Dióxido de Nitrógeno (NO2) | [https://airemadrid.firebaseio.com/last/66](https://airemadrid.firebaseio.com/last/66)
Villaverde Alto | Óxidos de Nitrógeno totales (NOx) | [https://airemadrid.firebaseio.com/last/67](https://airemadrid.firebaseio.com/last/67)
Villaverde Alto | Ozono (O3) | [https://airemadrid.firebaseio.com/last/68](https://airemadrid.firebaseio.com/last/68)
Villaverde Alto | Temperatura Mínima (TMI) | [https://airemadrid.firebaseio.com/last/69](https://airemadrid.firebaseio.com/last/69)
Farolillo | Dióxido de Azufre (S02) | [https://airemadrid.firebaseio.com/last/70](https://airemadrid.firebaseio.com/last/70)
Farolillo | Monóxido de Carbono (CO) | [https://airemadrid.firebaseio.com/last/71](https://airemadrid.firebaseio.com/last/71)
Farolillo | Monóxido de Nitrógeno (NO) | [https://airemadrid.firebaseio.com/last/72](https://airemadrid.firebaseio.com/last/72)
Farolillo | Dióxido de Nitrógeno (NO2) | [https://airemadrid.firebaseio.com/last/73](https://airemadrid.firebaseio.com/last/73)
Farolillo | Partículas en suspensión (-10) | [https://airemadrid.firebaseio.com/last/74](https://airemadrid.firebaseio.com/last/74)
Farolillo | Óxidos de Nitrógeno totales (NOx) | [https://airemadrid.firebaseio.com/last/75](https://airemadrid.firebaseio.com/last/75)
Farolillo | Ozono (O3) | [https://airemadrid.firebaseio.com/last/76](https://airemadrid.firebaseio.com/last/76)
Farolillo | Tolueno (C6H5CH3) | [https://airemadrid.firebaseio.com/last/77](https://airemadrid.firebaseio.com/last/77)
Farolillo | Benceno (C6H6) | [https://airemadrid.firebaseio.com/last/78](https://airemadrid.firebaseio.com/last/78)
Farolillo | Etilbenceno (C6H5CH2CH3) | [https://airemadrid.firebaseio.com/last/79](https://airemadrid.firebaseio.com/last/79)
Farolillo | Temperatura Media (TMP) | [https://airemadrid.firebaseio.com/last/80](https://airemadrid.firebaseio.com/last/80)
Farolillo | Temperatura Mínima (TMI) | [https://airemadrid.firebaseio.com/last/81](https://airemadrid.firebaseio.com/last/81)
Farolillo | *Valor Desconocido* | [https://airemadrid.firebaseio.com/last/82](https://airemadrid.firebaseio.com/last/82)
Casa de Campo | Dióxido de Azufre (S02) | [https://airemadrid.firebaseio.com/last/83](https://airemadrid.firebaseio.com/last/83)
Casa de Campo | Monóxido de Carbono (CO) | [https://airemadrid.firebaseio.com/last/84](https://airemadrid.firebaseio.com/last/84)
Casa de Campo | Monóxido de Nitrógeno (NO) | [https://airemadrid.firebaseio.com/last/85](https://airemadrid.firebaseio.com/last/85)
Casa de Campo | Dióxido de Nitrógeno (NO2) | [https://airemadrid.firebaseio.com/last/86](https://airemadrid.firebaseio.com/last/86)
Casa de Campo | Partículas en suspensión (-2.5) | [https://airemadrid.firebaseio.com/last/87](https://airemadrid.firebaseio.com/last/87)
Casa de Campo | Partículas en suspensión (-10) | [https://airemadrid.firebaseio.com/last/88](https://airemadrid.firebaseio.com/last/88)
Casa de Campo | Óxidos de Nitrógeno totales (NOx) | [https://airemadrid.firebaseio.com/last/89](https://airemadrid.firebaseio.com/last/89)
Casa de Campo | Ozono (O3) | [https://airemadrid.firebaseio.com/last/90](https://airemadrid.firebaseio.com/last/90)
Casa de Campo | Tolueno (C6H5CH3) | [https://airemadrid.firebaseio.com/last/91](https://airemadrid.firebaseio.com/last/91)
Casa de Campo | Benceno (C6H6) | [https://airemadrid.firebaseio.com/last/92](https://airemadrid.firebaseio.com/last/92)
Casa de Campo | Etilbenceno (C6H5CH2CH3) | [https://airemadrid.firebaseio.com/last/93](https://airemadrid.firebaseio.com/last/93)
Casa de Campo | Hidrocarburos Totales (HC) | [https://airemadrid.firebaseio.com/last/94](https://airemadrid.firebaseio.com/last/94)
Casa de Campo | Metano (CH4) | [https://airemadrid.firebaseio.com/last/95](https://airemadrid.firebaseio.com/last/95)
Casa de Campo | Hidrocarburos No Metánicos (NMH) | [https://airemadrid.firebaseio.com/last/96](https://airemadrid.firebaseio.com/last/96)
Casa de Campo | Radiación Ultravioleta (UV) | [https://airemadrid.firebaseio.com/last/97](https://airemadrid.firebaseio.com/last/97)
Casa de Campo | Velocidad del Viento (VV) | [https://airemadrid.firebaseio.com/last/98](https://airemadrid.firebaseio.com/last/98)
Casa de Campo | Dirección del Viento (DD) | [https://airemadrid.firebaseio.com/last/99](https://airemadrid.firebaseio.com/last/99)
Casa de Campo | Temperatura Media (TMP) | [https://airemadrid.firebaseio.com/last/100](https://airemadrid.firebaseio.com/last/100)
Casa de Campo | Temperatura Mínima (TMI) | [https://airemadrid.firebaseio.com/last/101](https://airemadrid.firebaseio.com/last/101)
Casa de Campo | Humedad Relativa (HR) | [https://airemadrid.firebaseio.com/last/102](https://airemadrid.firebaseio.com/last/102)
Casa de Campo | Presión Barométrica (PRB) | [https://airemadrid.firebaseio.com/last/103](https://airemadrid.firebaseio.com/last/103)
Casa de Campo | *Valor Desconocido* | [https://airemadrid.firebaseio.com/last/104](https://airemadrid.firebaseio.com/last/104)
Casa de Campo | *Valor Desconocido* | [https://airemadrid.firebaseio.com/last/105](https://airemadrid.firebaseio.com/last/105)
Barajas | Monóxido de Nitrógeno (NO) | [https://airemadrid.firebaseio.com/last/106](https://airemadrid.firebaseio.com/last/106)
Barajas | Dióxido de Nitrógeno (NO2) | [https://airemadrid.firebaseio.com/last/107](https://airemadrid.firebaseio.com/last/107)
Barajas | Óxidos de Nitrógeno totales (NOx) | [https://airemadrid.firebaseio.com/last/108](https://airemadrid.firebaseio.com/last/108)
Barajas | Ozono (O3) | [https://airemadrid.firebaseio.com/last/109](https://airemadrid.firebaseio.com/last/109)
Barajas | Temperatura Mínima (TMI) | [https://airemadrid.firebaseio.com/last/110](https://airemadrid.firebaseio.com/last/110)
Plaza del Carmen | Dióxido de Azufre (S02) | [https://airemadrid.firebaseio.com/last/111](https://airemadrid.firebaseio.com/last/111)
Plaza del Carmen | Monóxido de Carbono (CO) | [https://airemadrid.firebaseio.com/last/112](https://airemadrid.firebaseio.com/last/112)
Plaza del Carmen | Monóxido de Nitrógeno (NO) | [https://airemadrid.firebaseio.com/last/113](https://airemadrid.firebaseio.com/last/113)
Plaza del Carmen | Dióxido de Nitrógeno (NO2) | [https://airemadrid.firebaseio.com/last/114](https://airemadrid.firebaseio.com/last/114)
Plaza del Carmen | Óxidos de Nitrógeno totales (NOx) | [https://airemadrid.firebaseio.com/last/115](https://airemadrid.firebaseio.com/last/115)
Plaza del Carmen | Ozono (O3) | [https://airemadrid.firebaseio.com/last/116](https://airemadrid.firebaseio.com/last/116)
Plaza del Carmen | Temperatura Mínima (TMI) | [https://airemadrid.firebaseio.com/last/117](https://airemadrid.firebaseio.com/last/117)
Moratalaz | Dióxido de Azufre (S02) | [https://airemadrid.firebaseio.com/last/118](https://airemadrid.firebaseio.com/last/118)
Moratalaz | Monóxido de Carbono (CO) | [https://airemadrid.firebaseio.com/last/119](https://airemadrid.firebaseio.com/last/119)
Moratalaz | Monóxido de Nitrógeno (NO) | [https://airemadrid.firebaseio.com/last/120](https://airemadrid.firebaseio.com/last/120)
Moratalaz | Dióxido de Nitrógeno (NO2) | [https://airemadrid.firebaseio.com/last/121](https://airemadrid.firebaseio.com/last/121)
Moratalaz | Partículas en suspensión (-10) | [https://airemadrid.firebaseio.com/last/122](https://airemadrid.firebaseio.com/last/122)
Moratalaz | Óxidos de Nitrógeno totales (NOx) | [https://airemadrid.firebaseio.com/last/123](https://airemadrid.firebaseio.com/last/123)
Moratalaz | Temperatura Mínima (TMI) | [https://airemadrid.firebaseio.com/last/124](https://airemadrid.firebaseio.com/last/124)
Moratalaz | *Valor Desconocido* | [https://airemadrid.firebaseio.com/last/125](https://airemadrid.firebaseio.com/last/125)
Cuatro Caminos | Dióxido de Azufre (S02) | [https://airemadrid.firebaseio.com/last/126](https://airemadrid.firebaseio.com/last/126)
Cuatro Caminos | Monóxido de Nitrógeno (NO) | [https://airemadrid.firebaseio.com/last/127](https://airemadrid.firebaseio.com/last/127)
Cuatro Caminos | Dióxido de Nitrógeno (NO2) | [https://airemadrid.firebaseio.com/last/128](https://airemadrid.firebaseio.com/last/128)
Cuatro Caminos | Partículas en suspensión (-2.5) | [https://airemadrid.firebaseio.com/last/129](https://airemadrid.firebaseio.com/last/129)
Cuatro Caminos | Partículas en suspensión (-10) | [https://airemadrid.firebaseio.com/last/130](https://airemadrid.firebaseio.com/last/130)
Cuatro Caminos | Óxidos de Nitrógeno totales (NOx) | [https://airemadrid.firebaseio.com/last/131](https://airemadrid.firebaseio.com/last/131)
Cuatro Caminos | Tolueno (C6H5CH3) | [https://airemadrid.firebaseio.com/last/132](https://airemadrid.firebaseio.com/last/132)
Cuatro Caminos | Benceno (C6H6) | [https://airemadrid.firebaseio.com/last/133](https://airemadrid.firebaseio.com/last/133)
Cuatro Caminos | Etilbenceno (C6H5CH2CH3) | [https://airemadrid.firebaseio.com/last/134](https://airemadrid.firebaseio.com/last/134)
Cuatro Caminos | Temperatura Media (TMP) | [https://airemadrid.firebaseio.com/last/135](https://airemadrid.firebaseio.com/last/135)
Cuatro Caminos | Temperatura Mínima (TMI) | [https://airemadrid.firebaseio.com/last/136](https://airemadrid.firebaseio.com/last/136)
Cuatro Caminos | *Valor Desconocido* | [https://airemadrid.firebaseio.com/last/137](https://airemadrid.firebaseio.com/last/137)
Barrio del Pilar | Monóxido de Carbono (CO) | [https://airemadrid.firebaseio.com/last/138](https://airemadrid.firebaseio.com/last/138)
Barrio del Pilar | Monóxido de Nitrógeno (NO) | [https://airemadrid.firebaseio.com/last/139](https://airemadrid.firebaseio.com/last/139)
Barrio del Pilar | Dióxido de Nitrógeno (NO2) | [https://airemadrid.firebaseio.com/last/140](https://airemadrid.firebaseio.com/last/140)
Barrio del Pilar | Óxidos de Nitrógeno totales (NOx) | [https://airemadrid.firebaseio.com/last/141](https://airemadrid.firebaseio.com/last/141)
Barrio del Pilar | Ozono (O3) | [https://airemadrid.firebaseio.com/last/142](https://airemadrid.firebaseio.com/last/142)
Barrio del Pilar | Temperatura Mínima (TMI) | [https://airemadrid.firebaseio.com/last/143](https://airemadrid.firebaseio.com/last/143)
Barrio del Pilar | *Valor Desconocido* | [https://airemadrid.firebaseio.com/last/144](https://airemadrid.firebaseio.com/last/144)
Vallecas | Dióxido de Azufre (S02) | [https://airemadrid.firebaseio.com/last/145](https://airemadrid.firebaseio.com/last/145)
Vallecas | Monóxido de Nitrógeno (NO) | [https://airemadrid.firebaseio.com/last/146](https://airemadrid.firebaseio.com/last/146)
Vallecas | Dióxido de Nitrógeno (NO2) | [https://airemadrid.firebaseio.com/last/147](https://airemadrid.firebaseio.com/last/147)
Vallecas | Partículas en suspensión (-10) | [https://airemadrid.firebaseio.com/last/148](https://airemadrid.firebaseio.com/last/148)
Vallecas | Óxidos de Nitrógeno totales (NOx) | [https://airemadrid.firebaseio.com/last/149](https://airemadrid.firebaseio.com/last/149)
Vallecas | Temperatura Mínima (TMI) | [https://airemadrid.firebaseio.com/last/150](https://airemadrid.firebaseio.com/last/150)
Vallecas | *Valor Desconocido* | [https://airemadrid.firebaseio.com/last/151](https://airemadrid.firebaseio.com/last/151)
Méndez Álvaro | Monóxido de Nitrógeno (NO) | [https://airemadrid.firebaseio.com/last/152](https://airemadrid.firebaseio.com/last/152)
Méndez Álvaro | Dióxido de Nitrógeno (NO2) | [https://airemadrid.firebaseio.com/last/153](https://airemadrid.firebaseio.com/last/153)
Méndez Álvaro | Partículas en suspensión (-2.5) | [https://airemadrid.firebaseio.com/last/154](https://airemadrid.firebaseio.com/last/154)
Méndez Álvaro | Partículas en suspensión (-10) | [https://airemadrid.firebaseio.com/last/155](https://airemadrid.firebaseio.com/last/155)
Méndez Álvaro | Óxidos de Nitrógeno totales (NOx) | [https://airemadrid.firebaseio.com/last/156](https://airemadrid.firebaseio.com/last/156)
Méndez Álvaro | Temperatura Mínima (TMI) | [https://airemadrid.firebaseio.com/last/157](https://airemadrid.firebaseio.com/last/157)
Castellana | Monóxido de Nitrógeno (NO) | [https://airemadrid.firebaseio.com/last/158](https://airemadrid.firebaseio.com/last/158)
Castellana | Dióxido de Nitrógeno (NO2) | [https://airemadrid.firebaseio.com/last/159](https://airemadrid.firebaseio.com/last/159)
Castellana | Partículas en suspensión (-2.5) | [https://airemadrid.firebaseio.com/last/160](https://airemadrid.firebaseio.com/last/160)
Castellana | Partículas en suspensión (-10) | [https://airemadrid.firebaseio.com/last/161](https://airemadrid.firebaseio.com/last/161)
Castellana | Óxidos de Nitrógeno totales (NOx) | [https://airemadrid.firebaseio.com/last/162](https://airemadrid.firebaseio.com/last/162)
Castellana | Temperatura Mínima (TMI) | [https://airemadrid.firebaseio.com/last/163](https://airemadrid.firebaseio.com/last/163)
Retiro | Monóxido de Nitrógeno (NO) | [https://airemadrid.firebaseio.com/last/164](https://airemadrid.firebaseio.com/last/164)
Retiro | Dióxido de Nitrógeno (NO2) | [https://airemadrid.firebaseio.com/last/165](https://airemadrid.firebaseio.com/last/165)
Retiro | Óxidos de Nitrógeno totales (NOx) | [https://airemadrid.firebaseio.com/last/166](https://airemadrid.firebaseio.com/last/166)
Retiro | Ozono (O3) | [https://airemadrid.firebaseio.com/last/167](https://airemadrid.firebaseio.com/last/167)
Retiro | Temperatura Mínima (TMI) | [https://airemadrid.firebaseio.com/last/168](https://airemadrid.firebaseio.com/last/168)
Plaza Castilla | Monóxido de Nitrógeno (NO) | [https://airemadrid.firebaseio.com/last/169](https://airemadrid.firebaseio.com/last/169)
Plaza Castilla | Dióxido de Nitrógeno (NO2) | [https://airemadrid.firebaseio.com/last/170](https://airemadrid.firebaseio.com/last/170)
Plaza Castilla | Partículas en suspensión (-2.5) | (Eliminado 26/07/2015)*
Plaza Castilla | Partículas en suspensión (-10) | (Eliminado 26/07/2015)*
Plaza Castilla | Óxidos de Nitrógeno totales (NOx) | [https://airemadrid.firebaseio.com/last/171](https://airemadrid.firebaseio.com/last/171)
Plaza Castilla | Temperatura Media (TMP) | [https://airemadrid.firebaseio.com/last/172](https://airemadrid.firebaseio.com/last/172)
Plaza Castilla | Temperatura Mínima (TMI) | [https://airemadrid.firebaseio.com/last/173](https://airemadrid.firebaseio.com/last/173)
Ensanche de Vallecas | Monóxido de Nitrógeno (NO) | [https://airemadrid.firebaseio.com/last/174](https://airemadrid.firebaseio.com/last/174)
Ensanche de Vallecas | Dióxido de Nitrógeno (NO2) | [https://airemadrid.firebaseio.com/last/175](https://airemadrid.firebaseio.com/last/175)
Ensanche de Vallecas | Óxidos de Nitrógeno totales (NOx) | [https://airemadrid.firebaseio.com/last/176](https://airemadrid.firebaseio.com/last/176)
Ensanche de Vallecas | Ozono (O3) | [https://airemadrid.firebaseio.com/last/177](https://airemadrid.firebaseio.com/last/177)
Ensanche de Vallecas | Radiación Ultravioleta (UV) | [https://airemadrid.firebaseio.com/last/178](https://airemadrid.firebaseio.com/last/178)
Ensanche de Vallecas | Velocidad del Viento (VV) | [https://airemadrid.firebaseio.com/last/179](https://airemadrid.firebaseio.com/last/179)
Ensanche de Vallecas | Dirección del Viento (DD) | [https://airemadrid.firebaseio.com/last/180](https://airemadrid.firebaseio.com/last/180)
Ensanche de Vallecas | Temperatura Media (TMP) | [https://airemadrid.firebaseio.com/last/181](https://airemadrid.firebaseio.com/last/181)
Ensanche de Vallecas | Temperatura Mínima (TMI) | [https://airemadrid.firebaseio.com/last/182](https://airemadrid.firebaseio.com/last/182)
Ensanche de Vallecas | *Valor Desconocido* | [https://airemadrid.firebaseio.com/last/183](https://airemadrid.firebaseio.com/last/183)
Urbanización Embajada | Monóxido de Nitrógeno (NO) | [https://airemadrid.firebaseio.com/last/184](https://airemadrid.firebaseio.com/last/184)
Urbanización Embajada | Dióxido de Nitrógeno (NO2) | [https://airemadrid.firebaseio.com/last/185](https://airemadrid.firebaseio.com/last/185)
Urbanización Embajada | Partículas en suspensión (-10) | [https://airemadrid.firebaseio.com/last/186](https://airemadrid.firebaseio.com/last/186)
Urbanización Embajada | Óxidos de Nitrógeno totales (NOx) | [https://airemadrid.firebaseio.com/last/187](https://airemadrid.firebaseio.com/last/187)
Urbanización Embajada | Tolueno (C6H5CH3) | [https://airemadrid.firebaseio.com/last/188](https://airemadrid.firebaseio.com/last/188)
Urbanización Embajada | Benceno (C6H6) | [https://airemadrid.firebaseio.com/last/189](https://airemadrid.firebaseio.com/last/189)
Urbanización Embajada | Etilbenceno (C6H5CH2CH3) | [https://airemadrid.firebaseio.com/last/190](https://airemadrid.firebaseio.com/last/190)
Urbanización Embajada | Hidrocarburos Totales (HC) | [https://airemadrid.firebaseio.com/last/191](https://airemadrid.firebaseio.com/last/191)
Urbanización Embajada | Metano (CH4) | [https://airemadrid.firebaseio.com/last/192](https://airemadrid.firebaseio.com/last/192)
Urbanización Embajada | Hidrocarburos No Metánicos (NMH) | [https://airemadrid.firebaseio.com/last/193](https://airemadrid.firebaseio.com/last/193)
Urbanización Embajada | Temperatura Mínima (TMI) | [https://airemadrid.firebaseio.com/last/194](https://airemadrid.firebaseio.com/last/194)
Pza. Fdez. Ladreda | Monóxido de Carbono (CO) | [https://airemadrid.firebaseio.com/last/195](https://airemadrid.firebaseio.com/last/195)
Pza. Fdez. Ladreda | Monóxido de Nitrógeno (NO) | [https://airemadrid.firebaseio.com/last/196](https://airemadrid.firebaseio.com/last/196)
Pza. Fdez. Ladreda | Dióxido de Nitrógeno (NO2) | [https://airemadrid.firebaseio.com/last/197](https://airemadrid.firebaseio.com/last/197)
Pza. Fdez. Ladreda | Óxidos de Nitrógeno totales (NOx) | [https://airemadrid.firebaseio.com/last/198](https://airemadrid.firebaseio.com/last/298)
Pza. Fdez. Ladreda | Ozono (O3) | [https://airemadrid.firebaseio.com/last/199](https://airemadrid.firebaseio.com/last/299)
Pza. Fdez. Ladreda | Velocidad del Viento (VV) | [https://airemadrid.firebaseio.com/last/200](https://airemadrid.firebaseio.com/last/200)
Pza. Fdez. Ladreda | Dirección del Viento (DD) | [https://airemadrid.firebaseio.com/last/201](https://airemadrid.firebaseio.com/last/201)
Pza. Fdez. Ladreda | Temperatura Media (TMP) | [https://airemadrid.firebaseio.com/last/202](https://airemadrid.firebaseio.com/last/202)
Pza. Fdez. Ladreda | Temperatura Mínima (TMI) | [https://airemadrid.firebaseio.com/last/203](https://airemadrid.firebaseio.com/last/203)
Pza. Fdez. Ladreda | Humedad Relativa (HR) | [https://airemadrid.firebaseio.com/last/204](https://airemadrid.firebaseio.com/last/204)
Pza. Fdez. Ladreda | *Valor Desconocido* | [https://airemadrid.firebaseio.com/last/205](https://airemadrid.firebaseio.com/last/205)
Sanchinarro | Dióxido de Azufre (S02) | [https://airemadrid.firebaseio.com/last/206](https://airemadrid.firebaseio.com/last/206)
Sanchinarro | Monóxido de Carbono (CO) | [https://airemadrid.firebaseio.com/last/207](https://airemadrid.firebaseio.com/last/207)
Sanchinarro | Monóxido de Nitrógeno (NO) | [https://airemadrid.firebaseio.com/last/208](https://airemadrid.firebaseio.com/last/208)
Sanchinarro | Dióxido de Nitrógeno (NO2) | [https://airemadrid.firebaseio.com/last/209](https://airemadrid.firebaseio.com/last/209)
Sanchinarro | Partículas en suspensión (-10) | [https://airemadrid.firebaseio.com/last/210](https://airemadrid.firebaseio.com/last/210)
Sanchinarro | Óxidos de Nitrógeno totales (NOx) | [https://airemadrid.firebaseio.com/last/211](https://airemadrid.firebaseio.com/last/211)
Sanchinarro | Temperatura Media (TMP) | [https://airemadrid.firebaseio.com/last/212](https://airemadrid.firebaseio.com/last/212)
Sanchinarro | Temperatura Mínima (TMI) | [https://airemadrid.firebaseio.com/last/213](https://airemadrid.firebaseio.com/last/213)
El Pardo | Monóxido de Nitrógeno (NO) | [https://airemadrid.firebaseio.com/last/214](https://airemadrid.firebaseio.com/last/214)
El Pardo | Dióxido de Nitrógeno (NO2) | [https://airemadrid.firebaseio.com/last/215](https://airemadrid.firebaseio.com/last/215)
El Pardo | Óxidos de Nitrógeno totales (NOx) | [https://airemadrid.firebaseio.com/last/216](https://airemadrid.firebaseio.com/last/216)
El Pardo | Ozono (O3) | [https://airemadrid.firebaseio.com/last/217](https://airemadrid.firebaseio.com/last/217)
El Pardo | Temperatura Mínima (TMI) | [https://airemadrid.firebaseio.com/last/218](https://airemadrid.firebaseio.com/last/218)
Parque Juan Carlos I | Monóxido de Nitrógeno (NO) | [https://airemadrid.firebaseio.com/last/219](https://airemadrid.firebaseio.com/last/219)
Parque Juan Carlos I | Dióxido de Nitrógeno (NO2) | [https://airemadrid.firebaseio.com/last/220](https://airemadrid.firebaseio.com/last/220)
Parque Juan Carlos I | Óxidos de Nitrógeno totales (NOx) | [https://airemadrid.firebaseio.com/last/221](https://airemadrid.firebaseio.com/last/221)
Parque Juan Carlos I | Ozono (O3) | [https://airemadrid.firebaseio.com/last/222](https://airemadrid.firebaseio.com/last/222)
Parque Juan Carlos I | Radiación Ultravioleta (UV) | [https://airemadrid.firebaseio.com/last/223](https://airemadrid.firebaseio.com/last/223)
Parque Juan Carlos I | Velocidad del Viento (VV) | [https://airemadrid.firebaseio.com/last/224](https://airemadrid.firebaseio.com/last/224)
Parque Juan Carlos I | Dirección del Viento (DD) | [https://airemadrid.firebaseio.com/last/225](https://airemadrid.firebaseio.com/last/225)
Parque Juan Carlos I | Temperatura Media (TMP) | [https://airemadrid.firebaseio.com/last/226](https://airemadrid.firebaseio.com/last/226)
Parque Juan Carlos I | Temperatura Mínima (TMI) | [https://airemadrid.firebaseio.com/last/227](https://airemadrid.firebaseio.com/last/227)
Parque Juan Carlos I | Humedad Relativa (HR) | [https://airemadrid.firebaseio.com/last/228](https://airemadrid.firebaseio.com/last/228)
Parque Juan Carlos I | Presión Barométrica (PRB) | [https://airemadrid.firebaseio.com/last/229](https://airemadrid.firebaseio.com/last/229)
Parque Juan Carlos I | *Valor Desconocido* | [https://airemadrid.firebaseio.com/last/230](https://airemadrid.firebaseio.com/last/230)
Parque Juan Carlos I | *Valor Desconocido* | [https://airemadrid.firebaseio.com/last/231](https://airemadrid.firebaseio.com/last/231)
Tres Olivos | Monóxido de Nitrógeno (NO) | [https://airemadrid.firebaseio.com/last/232](https://airemadrid.firebaseio.com/last/232)
Tres Olivos | Dióxido de Nitrógeno (NO2) | [https://airemadrid.firebaseio.com/last/233](https://airemadrid.firebaseio.com/last/233)
Tres Olivos | Partículas en suspensión (-10) | [https://airemadrid.firebaseio.com/last/234](https://airemadrid.firebaseio.com/last/234)
Tres Olivos | Óxidos de Nitrógeno totales (NOx) | [https://airemadrid.firebaseio.com/last/235](https://airemadrid.firebaseio.com/last/235)
Tres Olivos | Ozono (O3) | [https://airemadrid.firebaseio.com/last/236](https://airemadrid.firebaseio.com/last/236)
Tres Olivos | Temperatura Mínima (TMI) | [https://airemadrid.firebaseio.com/last/237](https://airemadrid.firebaseio.com/last/237)
Tres Olivos | Presión Barométrica (PRB) | [https://airemadrid.firebaseio.com/last/238](https://airemadrid.firebaseio.com/last/238)
Tres Olivos | *Valor Desconocido* | (Eliminado 26/07/2015)*

## Historial de cambios

*El ayuntamiento realiza cambios constantes en los datos que se emiten en las estaciones en ocasiones elimina datos y en otras añade. Este es un registro de cambios*

Día 26/07/2015 -> Se eliminan los siquientes datos

Estación | Valor | Log
------------ | ------------- | -------------
Plaza Castilla | Partículas en suspensión (-2.5) | (Eliminado 26/07/2015)*
Plaza Castilla | Partículas en suspensión (-10) | (Eliminado 26/07/2015)*
Tres Olivos | *Valor Desconocido* | (Eliminado 26/07/2015)*