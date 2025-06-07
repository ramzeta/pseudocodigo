## 🌟 EJEMPLOS CLÁSICOS DE PSEUDOCÓDIGO EN PLANTUML

### 🔰 1. **Es el Elegido** (if simple)

```plantuml
@startuml
start
:Leer midiclorianos;
if (¿midiclorianos > 20000?) then (sí)
  :Escribir "Es el Elegido";
else (no)
  :Escribir "Un Jedi más";
endif
stop
@enduml
```

---

### 🧪 2. **Entrenar Padawans** (bucle `PARA`)

```plantuml
@startuml
start
repeat
  :Entrenando Padawan #i;
repeat while (i <= 5)
:Escribir "Todos los Padawans han sido entrenados.";
stop
@enduml
```

---

### ⚔️ 3. **Contar cazas TIE** (lista + contador)

```plantuml
@startuml
start
:contador ← 0;
:listaNaves ← ["X-Wing", "TIE Fighter", "TIE Fighter", "A-Wing"];
:Recorrer cada nave en listaNaves;
if (¿nave == "TIE Fighter"?) then (sí)
  :contador ← contador + 1;
endif
:Escribir cantidad de TIEs;
stop
@enduml
```

---

### 🧠 4. **Evaluar misión peligrosa**

```plantuml
@startuml
start
:Leer datos de la misión;
if (¿dificultad > 7 Y planeta == "Mustafar"?) then (sí)
  :Escribir "¡Solo un Maestro Jedi puede aceptar esta misión!";
else (no)
  :Escribir "Misión asignada a un Caballero Jedi.";
endif
stop
@enduml
```

---

### 🌌 5. **Escanear la Galaxia (matriz 5x5)**

```plantuml
@startuml
start
:i ← 1;
repeat
  :j ← 1;
  repeat
    if (¿galaxia[i][j] == "Base Sith"?) then (sí)
      :Escribir alerta con coordenadas [i,j];
    endif
  :j ← j + 1;
  repeat while (j <= 5)
:i ← i + 1;
repeat while (i <= 5)
stop
@enduml
```

---

### ✅ Cómo usar estos diagramas

Puedes:

* Pegarlos en [https://plantuml.com/es/activity-diagram-beta](https://plantuml.com/es/activity-diagram-beta)
* O usar [https://plantuml-online-editor.kkeisuke.dev/](https://plantuml-online-editor.kkeisuke.dev/)
* O integrarlos en VSCode con la extensión "PlantUML"

---
