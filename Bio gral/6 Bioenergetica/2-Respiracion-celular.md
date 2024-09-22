
# Respiración celular
## ATP
Es la "moneda energética" porque se usa para transferir energia de diferentes reacciones, y de un lugar a otro. Nucleotido con base adenina y 3P.
El producto final de la respiracion celular será el ATP en un ciclo de varias vias metabolicas.
Se usa para:
- **Trabajo mecánico**: fosforilando proteinas motoras
- **Trabajo de transporte**: fosforilando proteinas de membrana para transporte en contra de un gradiente de concentración
- **Trabajo químico**: fosforilando reactivos clave

## Vías metabólicas
```mermaid
graph LR
1[Glucólisis] --> 2[Oxidación piruvato] -->3[Ciclo de krebs] --> 4[CTE]
```
\* CTE : cadena transportadora de electrones
![respiracion_celular_que_es_etapas_y_tipos_4393_orig](attachments/respiracion_celular_que_es_etapas_y_tipos_4393_orig.jpg)

### Glucólisis
Ocurre en el citoplasma, cada paso esta catalizado por enzimas
El ATP producido en esta etapa es por ==fosforilación a nivel de sustrato== porque el P proviene de otra molécula orgánica.
#### Fases
![Glucolisis](attachments/Glucolisis.png)
#### Resultado neto
```mermaid
graph LR
0[Glucosa 6C] --> 1[ 2 Piruvato 3C + 2 H2O]
2[4 ATP - 2 ATP]  --> 3[2 ATP]
4[2 NAD<sup>+</sup> + 4e<sup>-</sup> + 4H<sup>+</sup> ] --> 5[2 NADH + 2H<sup>+</sup>]
```

### Oxidación del piruvato

> Piruvato + coenzima A + NAD+ --> CO2 + AcetylCoA + NADH
![acetilcoa](attachments/acetilcoa.jpeg)

### Cliclo de krebs

![ciclo_Krebs](attachments/ciclo_Krebs.gif)
Por cada glucosa -> 2 piruvato --> 2 AcetilCoA --> 4 CO<sub>2</sub> + 6 NADH + 2 FADH<sub>2</sub> 
> [!Poder reductor]
> El NAD<sup>+</sup> y FAD<sup>+</sup> (nad y fad oxidados) son nucleotidos que sirven para transportar electrones de alta energía como NADH y FADH (nad y fad reducido) que se usarán en la CTE

### Cadena transportadora de electrones (CTE)
La cadena transportadora permite que los electrones de alta energía sean cedidos al O2 para formar agua en una reacción exergónica controlada. De lo contrario la formación de agua es explosiva liberando energia de forma de descontrolada.
El O2 que es el mas electronegativo es el <font color="#00b0f0">aceptor final de electrones</font> de la cadena, que se reduce formando H2O. 
La energía liberada por pasaje de electrones por las proteinas transmembrana se usa para bomber H+ al espacio intermembrana formando un grandiente electroquimico por la alta concentracion de H+
==Fosforilación oxidativa== los [H+]  del espacio intermebrana pasan por la ATP-sintasa para generar ATP en un proceso de quimiosmosis. 

> RESULTADO: 32 ATP de 1 glucosa

![ CTE-khanacademy](CTE.png%20)
### Vías alternativas
#### Con O2 disponible
Además de la glucólisis se pueden hidrolizar lípidos y proteínas para obtener piruvato, pero hay una fase de inversión energética mayor para en la descomposición de las macromoléculas
#### Sin O2
Se produce la glucólisis pero no ingresa al ciclo de krebs porque no hay NAD+, ni a la CTE por la ausencia de oxígeno
##### Fermentación láctica
Ej ejercicio físico intenso, el musculo se queda sin O2
![ferm-lactica](attachments/ferm-lactica.png)
##### Fermentación alcoholica
Ej levaduras
![ferm-alcoholica](attachments/ferm-alcoholica.png)

