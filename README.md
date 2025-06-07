## 🛸 GUÍA DE PSEUDOCÓDIGO: DE NOOB A EXPERTO (Edición Star Wars)

---

### 🔰 NIVEL 1: **Joven Padawan (Noob)**

#### Objetivo: Entender lo básico del pseudocódigo.

**Conceptos que aprenderás:**

* Variables
* Entrada / salida
* Operaciones simples

**Ejemplo 1 – Sumar midiclorianos:**

```plaintext
INICIO
  ESCRIBIR "Introduce la cantidad de midiclorianos de Anakin:"
  LEER midiclorianos
  SI midiclorianos > 20000 ENTONCES
    ESCRIBIR "Es el Elegido"
  SINO
    ESCRIBIR "Un Jedi más"
  FIN SI
FIN
```

---

### 🧪 NIVEL 2: **Aprendiz Jedi**

#### Objetivo: Aprender estructuras de control.

**Conceptos:**

* Condicionales (`SI`, `SINO`)
* Bucles (`MIENTRAS`, `PARA`)
* Contadores y acumuladores

**Ejemplo 2 – Entrenar Padawans:**

```plaintext
INICIO
  PARA i ← 1 HASTA 5 HACER
    ESCRIBIR "Entrenando Padawan #" + i
  FIN PARA
  ESCRIBIR "Todos los Padawans han sido entrenados."
FIN
```

---

### ⚔️ NIVEL 3: **Caballero Jedi**

#### Objetivo: Resolver problemas reales simples.

**Conceptos:**

* Funciones
* Listas (vectores)
* Lógica booleana

**Ejemplo 3 – Escanear naves enemigas:**

```plaintext
FUNCION ContarTIEs(listaNaves)
  contador ← 0
  PARA cada nave EN listaNaves HACER
    SI nave = "TIE Fighter" ENTONCES
      contador ← contador + 1
    FIN SI
  FIN PARA
  RETORNAR contador
FIN FUNCION

INICIO
  naves ← ["X-Wing", "TIE Fighter", "TIE Fighter", "A-Wing"]
  resultado ← ContarTIEs(naves)
  ESCRIBIR "Se han detectado " + resultado + " cazas TIE."
FIN
```

---

### 🧠 NIVEL 4: **Maestro Jedi**

#### Objetivo: Crear algoritmos modulares y eficientes.

**Conceptos:**

* Modularidad con funciones
* Paso de parámetros
* Estructuras anidadas

**Ejemplo 4 – Evaluar misiones Jedi:**

```plaintext
FUNCION EsPeligrosa(mision)
  SI mision.dificultad > 7 Y mision.planeta = "Mustafar" ENTONCES
    RETORNAR VERDADERO
  SINO
    RETORNAR FALSO
  FIN SI
FIN FUNCION

INICIO
  mision ← CREAR_MISION("Espiar Sith", 9, "Mustafar")
  SI EsPeligrosa(mision) ENTONCES
    ESCRIBIR "¡Solo un Maestro Jedi puede aceptar esta misión!"
  SINO
    ESCRIBIR "Misión asignada a un Caballero Jedi."
  FIN SI
FIN
```

---

### 🌌 NIVEL 5: **Gran Maestro Jedi (Experto)**

#### Objetivo: Resolver problemas complejos con estructuras avanzadas.

**Conceptos:**

* Matrices
* Algoritmos de búsqueda y ordenación
* Pensamiento algorítmico avanzado

**Ejemplo 5 – Mapear la Galaxia:**

```plaintext
INICIO
  galaxia[5][5] ← MATRIZ DE PLANETAS
  PARA i ← 1 HASTA 5 HACER
    PARA j ← 1 HASTA 5 HACER
      SI galaxia[i][j] = "Base Sith" ENTONCES
        ESCRIBIR "¡Alerta! Base Sith encontrada en coordenadas [" + i + "," + j + "]"
      FIN SI
    FIN PARA
  FIN PARA
FIN
```

---

## 🚀 Recomendaciones para tu entrenamiento Jedi

| Hábito          | Herramienta / Recurso                                                    |
| --------------- | ------------------------------------------------------------------------ |
| Practicar       | [PSeInt](http://pseint.sourceforge.net/) o lápiz y papel                 |
| Resolver retos  | [Codewars](https://www.codewars.com/) (elige pseudocódigo mental)        |
| Enseñar a otros | Crea tus propias misiones como maestro Jedi                              |
| Leer más        | Algoritmos + estructuras de datos explicados en español (libros, vídeos) |

---

## 🏁 Final Boss: El Desafío de la Estrella de la Muerte

**Haz un pseudocódigo que:**

* Reciba un escuadrón de naves rebeldes
* Simule un ataque con probabilidad de éxito
* Genere un informe final

¿Quieres que te lo prepare como ejercicio? 😄

---
