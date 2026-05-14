# QCA-Exito-de-Protestas-Estudiantiles-

Se trabajó con 20 casos ficticios y variables binarias:

- 0 = ausencia de la condición
- 1 = presencia de la condición

---

# Variables

## Condiciones

- **A:** apoyo en redes sociales
- **B:** liderazgo organizado
- **C:** cobertura mediática

## Resultado

- **Resultados:** éxito de la protesta estudiantil

---

# Tabla de verdad

| A | B | C | Resultado |
|---|---|---|---|
| 0 | 0 | 0 | 0 |
| 0 | 0 | 1 | 0 |
| 0 | 1 | 0 | 0 |
| 0 | 1 | 1 | 1 |
| 1 | 0 | 0 | 0 |
| 1 | 0 | 1 | 0 |
| 1 | 1 | 0 | 1 |
| 1 | 1 | 1 | 1 |

---

# Resultados

## Condiciones necesarias

El análisis mostró que la condición **B (liderazgo organizado)** aparece en todos los casos exitosos.

Esto significa que el liderazgo organizado parece ser una condición necesaria para que una protesta estudiantil tenga éxito dentro de este ejercicio.

Las otras condiciones también ayudan, pero no aparecen en todos los casos exitosos.

---

# Minimización booleana

La fórmula obtenida fue:

```math
A*B + B*C \leftrightarrow Resultados
```

Esto significa que el éxito puede ocurrir cuando existe:

- apoyo en redes sociales + liderazgo organizado
o
- cobertura mediática + liderazgo organizado

---

# Interpretación

Los resultados sugieren que las protestas estudiantiles tienen más probabilidades de éxito cuando existe una buena organización interna.

Las redes sociales y la cobertura mediática ayudan al movimiento, pero por sí solas no parecen suficientes.

El ejercicio también permite entender cómo el QCA analiza combinaciones de factores y no solo variables individuales.

---

# Herramientas utilizadas

- R
- Paquete `QCA`
- Paquete `SetMethods`

