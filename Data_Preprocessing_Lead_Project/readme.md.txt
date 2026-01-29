# Përpunimi i të Dhënave për Sisteme Rekomandimi

## 📌 Përshkrimi i Projektit
Ky projekt fokusohet në **përpunimin e të dhënave (data preprocessing)** si hap themelor për ndërtimin e një **sistemi rekomandimi**.  
Përdoret dataset-i **MovieLens 100k**, i cili përpunohet nga forma e tij origjinale në të dhëna të pastra dhe të strukturuara, gati për analiza ose modele machine learning.

Qëllimi i projektit është të demonstrojë:
- Ngarkimin e të dhënave
- Pastrimin e të dhënave
- Transformimin e tyre
- Strukturimin për përdorim në sisteme rekomandimi

---

## 📂 Struktura e Projektit

data/
│ ├── raw/ # Të dhënat origjinale (MovieLens)
│ └── processed/ # Të dhënat e përpunuara (output)
│
├── notebooks/
│ └── exploration.ipynb # Analizë dhe eksplorim i të dhënave (opsionale)
│
└── src/
└── preprocessing.py # Script-i kryesor për përpunimin e të dhënave