# SISTEMA EXPERTO DEL CAMPER PERFECTO 

## Que es un sistema experto?

Un sistema experto es un programa de inteligencia artificial diseñado para imitar la forma en que un experto humano toma decisiones en un área específica.

Es decir, funciona como si fuera un “experto digital” en un tema: medicina, finanzas, diagnóstico técnico, educación, etc.

---
## Que es un buen, un mal y un camper regular?
### 🟢 camper Perfecto

Un **camper perfecto** es aquel cuyo *rendimiento académico global* es sobresaliente.
En el sistema experto, esto significa que su score final es igual o mayor a 80.

Características del camper perfecto:

* Domina las competencias del programa.
* Tiene notas altas en Inglés, SER, Software, Empleabilidad y Lógica.
* Su aprendizaje es consistente y demuestra un desempeño integral.
* Es el perfil ideal para continuar procesos avanzados o proyectos exigentes.

### 🟡 Camper Regular

El **camper regular** representa un nivel medio de desempeño.
En el sistema experto, esto es cuando **su score está entre 70 y 79.9**.

Características del camper regular:

* Tiene competencias aceptables, aunque con áreas por mejorar.
* No está en un nivel bajo, pero tampoco sobresale de forma general.
* Puede avanzar en el programa, pero se recomienda refuerzo académico.
* Sus resultados muestran entendimiento, pero con inconsistencias.

###  🔴 Camper Deficiente (o No perfecto)

Es un estudiante cuyo rendimiento global es insuficiente.
En el sistema experto, esto sucede cuando **su score es menor a 70**.

 Características del camper deficiente:

* Presenta debilidades importantes en varias áreas.
* Sus notas indican falta de dominio en competencias básicas.
* Necesita apoyo adicional, tutorías o repetir contenidos.
* El desempeño es bajo para las exigencias del programa.



## 1. Atributos del Sistema Experto

| Abreviación | Nombre del Atributo | Valores |
|------------|----------------------|---------|
| N1 | Nota de Inglés | 0–100 |
| N2 | Nota de SER | 0–100 |
| N3 | Nota de Software | 0–100 |
| N4 | Nota de Empleabilidad | 0–100 |
| N5 | Nota de Prueba Lógica | 0–100 |
| S6 | Score Final | 0–100 |

---

## 2. Porcentajes usados

| Atributo | Peso % |
|---------|--------|
| Inglés | 20% |
| SER | 20% |
| Software | 30% |
| Empleabilidad | 10% |
| Prueba lógica | 20% |

---

## 3. Fórmula del Score Final

- Score = A1*0.20 + A2*0.20 + A3*0.30 + A4*0.10 + A5*0.20

---

## 4. Clases del Sistema 

| Clase | Significado | Criterio |
|-------|-------------|-----------|
| 1 | Camper Perfecto | Score ≥ 80 |
| 2 | Camper Regular | 70 ≤ Score < 80 |
| 0 | Deficiente / No perfecto | Score < 70 |

---

## 5. Ejemplo

| Nº | N1 | N2 | N3 | N4 | N5 | S6 | Clase |
|----|----|----|----|----|----|--------|--------|
| 01 | 70 | 75 | 80 | 70 | 85 | 78.5 | 2 |
| 02 | 85 | 80 | 90 | 75 | 88 | 86.1 | 1 |
| 03 | 60 | 65 | 70 | 80 | 60 | 65.5 | 0 |
| 04 | 95 | 90 | 88 | 85 | 92 | 90.7 | 1 |
| 05 | 80 | 78 | 75 | 72 | 70 | 75.1 | 2 |
| 06 | 88 | 85 | 92 | 90 | 94 | 91.5 | 1 |
| 07 | 50 | 55 | 60 | 65 | 58 | 56.9 | 0 |
| 08 | 78 | 80 | 85 | 70 | 82 | 80.1 | 1 |
| 09 | 82 | 79 | 70 | 88 | 75 | 76.0 | 2 |
| 10 | 90 | 92 | 95 | 90 | 93 | 92.2 | 1 |
| 11 | 72 | 75 | 78 | 70 | 74 | 73.8 | 2 |
| 12 | 88 | 82 | 85 | 80 | 86 | 84.6 | 1 |
| 13 | 65 | 70 | 75 | 68 | 72 | 69.5 | 0 |
| 14 | 91 | 88 | 90 | 85 | 89 | 89.9 | 1 |

---




