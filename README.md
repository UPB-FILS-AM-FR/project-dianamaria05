
# Flappy Bird 2

## 🐦 Descriere

Acest proiect este o versiune personalizată a celebrului joc **Flappy Bird**, dezvoltată în **Java** folosind biblioteca **JavaFX**. Jocul permite controlul unei păsări care trebuie să evite obstacole în mișcare pentru a acumula puncte. Versiunea actuală aduce funcționalități extinse și o interfață grafică intuitivă.

## 🛠️ Tehnologii utilizate

- **Java 21**
- **JavaFX** – pentru partea de interfață grafică și animații
- **IntelliJ IDEA** – mediu de dezvoltare
- **Scene Builder** – pentru editarea interfeței

## 🚀 Funcționalități

- Meniu principal cu opțiuni:
  - **Start Game**
  - **How to Play**
  - **Exit**
- Controlul păsării cu tasta **SPACE**
- Scor în timp real și sistem de coliziuni
- Elemente vizuale animate (fundaluri, obstacole)
- Sunete pentru evenimente (coliziune, punctaj)
- Ecran de final cu scor final și opțiuni de reluare sau ieșire

## 🎮 Gameplay

- Păsarea zboară în sus la apăsarea tastei **SPACE** și coboară gravitațional.
- Scopul este de a trece prin spațiile dintre țevi fără a le atinge.
- La fiecare obstacol trecut se acumulează un punct.
- Jocul se termină dacă pasărea atinge o țeavă sau solul.

## 🖼️ Capturi de ecran

*(Adaugă imagini relevante cu meniul principal, gameplay-ul și ecranul de final aici)*

## 📁 Structura proiectului

```
FlappyBird2/
│
├── src/
│   ├── Main.java
│   ├── Controller/
│   ├── Model/
│   └── View/
│
├── resources/
│   ├── images/
│   └── sounds/
│
├── README.md
└── .gitignore
```

## ✅ Task-uri implementate

- [x] Meniu principal complet funcțional
- [x] Implementarea logicii de zbor și coliziuni
- [x] Sistem de scor
- [x] Sunete pentru acțiuni
- [x] Ecran final cu opțiuni

## 🔄 Posibile îmbunătățiri viitoare

- Adăugarea unui sistem de high-score
- Niveluri de dificultate progresivă
- Salvarea scorurilor într-o bază de date
- Optimizarea coliziunilor și a animațiilor

## 📦 Lansare

Aplicația poate fi rulată din IDE sau compilată într-un `.jar` folosind configurările din IntelliJ.
