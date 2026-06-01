# Resolução de Exercícios – Materiais Elétricos

## Introdução

Para a resolução destas questões de Materiais Elétricos, foram utilizados os fundamentos de estruturas de bandas, mecanismos de polarização e capacitância estudados na disciplina.

---

# 17. Condutividade em Materiais Não Estequiométricos (Wüstita)

## Significado Físico

A wüstita (Fe₁₋ₓO) possui vacâncias de ferro. Para manter a neutralidade elétrica, íons Fe³⁺ são criados, atuando como lacunas ("buracos") que permitem a condução do tipo p.

## Fórmulas Utilizadas

σ = p · |e| · μh

p = Portadores / Vcélula

Vcélula = a³

## Dados

* x = 0,060
* a = 0,437 nm = 4,37 × 10⁻¹⁰ m
* μh = 1,0 × 10⁻⁵ m²/(V·s)
* |e| = 1,6 × 10⁻¹⁹ C

Na estrutura tipo NaCl existem 4 unidades de fórmula por célula unitária. Como cada vacância gera dois portadores Fe³⁺, existem 8x portadores por célula.

## Resolução

### Concentração de lacunas

p = 8x / a³

p = 8(0,060) / (4,37 × 10⁻¹⁰)³

p ≈ 5,75 × 10²⁷ m⁻³

### Condutividade

σ = (5,75 × 10²⁷)(1,6 × 10⁻¹⁹)(1,0 × 10⁻⁵)

σ ≈ 92,0 S/m

## Resultado

**σ ≈ 9,20 × 10¹ S/m**

---

# 18. Alteração de Espaçamento entre Placas

## Fórmula

C = ε₀ εr A / l

Como C e A permanecem constantes:

εr₁ / l₁ = εr₂ / l₂

## Dados

* εr₁ = 2,5
* l₁ = 1 mm
* εr₂ = 4,0

## Cálculo

l₂ = (εr₂ / εr₁) · l₁

l₂ = (4,0 / 2,5) · 1 mm

l₂ = 1,6 mm

## Resultado

**l₂ = 1,6 mm**

---

# 19. Seleção de Candidatos (Tabela 8.4)

## Fórmula

εr = (C · l) / (ε₀ · A)

## Dados

* C = 38 pF
* l = 3 mm
* A = 100 mm × 25 mm = 2500 mm²

## Resultado

εr,min ≈ 5,15

### Materiais candidatos

* Titanato de Bário (εr ≈ 1000–2000)
* Mica (εr ≈ 5,4–8,7)
* Estatita (εr ≈ 5,5–7,5)
* Vidro cal-sodada (εr ≈ 6,9)
* Porcelana (εr ≈ 6,0)

Materiais como Baquelite e Nylon não atendem ao requisito.

---

# 20. Cálculo de Campo Elétrico

## Dados

* A = 2500 mm²
* l = 2 mm
* εr = 4,0

### (a) Capacitância

C = 4,427 × 10⁻¹¹ F

C = 44,27 pF

### (b) Campo Elétrico

V = Q / C

V ≈ 18,07 V

E = V / l

E ≈ 9,03 × 10³ V/m

## Resultado

**E = 9,03 × 10³ V/m**

---

# 21. Mecanismo de Armazenamento

A inserção de um dielétrico provoca a polarização do material. O campo elétrico aplicado induz o alinhamento de dipolos, gerando um campo interno oposto que reduz a diferença de potencial para uma mesma carga.

Como consequência, a capacitância aumenta e o capacitor consegue armazenar mais carga para a mesma tensão aplicada.

---

# 22. Momento de Dipolo no NaCl

## Fórmula

p = Q · d

## Resultado

**p = 2,26 × 10⁻³⁰ C·m**

---

# 23. Constante Dielétrica e Deslocamento

### (a) Constante dielétrica

εr = P/(ε₀E) + 1

εr ≈ 3,26

### (b) Vetor deslocamento elétrico

D = ε₀E + P

D = 1,44 × 10⁻⁶ C/m²

---

# 24. Comparação entre Dielétrico e Vácuo

## Resultados

* Vdielétrico = 17,29 V
* Vvácuo = 86,45 V
* Ca = 2,02 pF
* Cb = 0,405 pF
* D = 2,19 × 10⁻⁷ C/m²
* P = 1,75 × 10⁻⁷ C/m²

---

# 25. Tipos de Polarização

## Mecanismos

### Polarização eletrônica

Deslocamento da nuvem eletrônica em relação ao núcleo.

### Polarização iônica

Deslocamento relativo entre cátions e ânions.

### Polarização por orientação

Alinhamento de dipolos permanentes com o campo aplicado.

## Classificação

| Material | Tipo de Polarização             |
| -------- | ------------------------------- |
| BaTiO₃   | Eletrônica, Iônica e Orientação |
| Neônio   | Eletrônica                      |
| Diamante | Eletrônica                      |
| KCl      | Eletrônica e Iônica             |
| NH₃      | Eletrônica e Orientação         |

---

# 26. Momento Dipolar no Titanato de Bário (BaTiO₃)

## Resultado

p ≈ 1,06 × 10⁻²⁹ C·m

### Polarização Máxima

P ≈ 0,166 C/m²

---

# 27. Dependência com a Frequência

Em frequências elevadas (10¹⁵ Hz), apenas a polarização eletrônica contribui para a constante dielétrica.

εr = 2,3

Em 1 MHz:

εtotal = 6,9

Contribuição iônica:

εiônica = 6,9 − 2,3 = 4,6

Fração:

4,6 / 6,9 ≈ 67%

## Resultado

A polarização iônica corresponde a aproximadamente **67%** da constante dielétrica total.

---

# 28. Temperatura de Curie

Acima da temperatura de Curie (Tc), a energia térmica supera as forças de alinhamento dos dipolos.

O BaTiO₃ passa da estrutura tetragonal para a estrutura cúbica, tornando coincidentes os centros de carga positiva e negativa.

Dessa forma, desaparece o momento dipolar permanente e o material perde o comportamento ferroelétrico.
