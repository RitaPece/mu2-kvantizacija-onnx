# Kvantizacija neuronskih mreža korišćenjem ONNX formata

**Autor:** Rita Pece, EE195/2021  
**Predmet:** Mašinsko učenje 2  
**Fakultet:** Fakultet tehničkih nauka, Novi Sad  

## O projektu

Projekat implementira kvantizaciju neuronske mreže korišćenjem ONNX formata.  
Cilj je smanjiti memorijsku potrošnju i ubrzati izvršavanje modela uz minimalan gubitak tačnosti.

Urađene su dve vrste kvantizacije:
- **8-bit (INT8)** – statička kvantizacija
- **16-bit (FP16)** – konverzija tipa podataka

## Struktura projekta

- `MU2.ipynb` – Jupyter Notebook sa kompletnim kodom

## Instalacija

### Preduslovi
- Python 3.12
- Jupyter Notebook

### Koraci

1. Klonirati repozitorijum:
```bash
git clone https://github.com/RitaPece/mu2-kvantizacija-onnx.git
cd mu2-kvantizacija-onnx
