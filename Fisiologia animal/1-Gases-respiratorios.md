
# Propiedades
## En fase gaseosa
### Ley general de gases 

> Ley gral de los gases
> PV = nRT

#### Composicion de gases en aire seco

| Gas        | Proporcion |
| ---------- | ---------- |
| Oxigeno    | 20.95 %    |
| Nitrongeno | 78.08 %    |
| Argón      | 0.93 %     |
| CO2        | 0.04 %     |
### Ley de dalton
Presiones parciales

>$Px = Fx * Pt$
>Px: presion del gas x
>Fx: fraccion del gas x
### Influencia de la humedad
A 37°c la P del vapor de H20 es 46,9 mmHg => la Px del O2:
Restar la Px del H2O: $760 - 46,9 = 713,1mmHg$
Calcular la Px del O2 con ese resto como si fuera aire seco
$Px O2 = 713,1 *0,2095 = 149,39 mmHg$

## En Fase acuosa
### Ley de henry
  $Cx = A * Px$
  Donde: 
  - Cx: concentracion del gas x
  - A: coef de absorcion (mMol/L) 
  - Px: presion parcial del gas x
El coeficiente A es una medida de la solubilidad del gas
Coef A para distintos gases a 0°C en H2O destilada

| Gas | Coef A (mMol / L) |
| --- | ----------------- |
| CO2 | 77.2              |
| O2  | 2.2               |
| N2  | 1.1               |

# Transporte de gases
## Difusión
- Movimiento siguiendo el gradiente de presiones parciales, no necesariamente de concentración (en especial de interfaz gaseosa a líquida).
- Las moléculas de gas combinadas a otras dejan de ejercer presión parcial.
#### Ley de Fick
Derivación simplificada por **Krogh**
$$
J = K * (P1 - P2) / X
$$
J: tasa de difusión por área
K: coef de difusión de krogh
P1, P2: presión en dos puntos
X: distancia (grosor de la membrana respiratoria)

K define la permeabilidad del tejido, en fn de viscosidad, composición, temp 

## Convección
 Flujo determinista de una sustancia, líquida o gaseosa, de un sitio a otro

 ```mermaid
graph LR
1[Esfuerzo muscular] --> 2[Ventilacion respiratoria]
1 --> 3[Bombeo de sangre]
4[Ambiental] --> Aire
4 --> Agua
```

