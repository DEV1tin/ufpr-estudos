# Referência Auxiliar — BeamsDiagrams (Prof. Marco André Argenta)

Espelho e catálogo em Markdown extraído de [argenta-ma.github.io/BeamsDiagrams](https://argenta-ma.github.io/BeamsDiagrams/) *(Licença CC BY-NC-SA 4.0 — Prof. Dr. Marco André Argenta, UFPR)*.

- **Total de vigas catalogadas:** `59` vigas em `6` categorias.
- **Site offline local:** salvo em `./00. Site Offline/index.html`.
- **Uso nos exercícios:** consulte as equações analíticas (flechas, momentos fletores, cortantes e reações de apoio) e os blocos em Python prontos para validação numérica.

---

## Índice Rápido por Categoria

### BIAPOIADAS

| Código | Descrição | Blocos no Formulário |
| :---: | :--- | :---: |
| [**BA1-w**](#ba1-w) | Viga biapoiada com carga uniformemente distribuída em todo o vão | — |
| [**BA2-td**](#ba2-td) | Viga biapoiada com carga triangular distribuída em todo o vão com máximo na direita | — |
| [**BA3-te**](#ba3-te) | Viga biapoiada com carga triangular distribuída em todo o vão com máximo na esquerda | — |
| [**BA4-tm**](#ba4-tm) | Viga biapoiada com carga triangular distribuída em todo o vão com máximo meio do vão | — |
| [**BA5-pe**](#ba5-pe) | Viga biapoiada com carga uniforme distribuída na parte esquerda do vão | — |
| [**BA6-pv**](#ba6-pv) | Viga biapoiada com carga uniforme distribuída em parte do vão | — |
| [**BA7-ev**](#ba7-ev) | Viga biapoiada com carga uniforme distribuída nos extremos do vão | — |
| [**BA8-fa**](#ba8-fa) | Viga biapoiada com carga concentrada no vão | — |
| [**BA9-ff**](#ba9-ff) | Viga biapoiada com duas cargas concentradas no vão assimétricas | — |
| [**BA10-m**](#ba10-m) | Viga biapoiada com momento concentrado no vão | — |
| [**BA11-mo**](#ba11-mo) | Viga biapoiada com momentos concentrados no vão assímetricos | — |

### EM BALANÇO

| Código | Descrição | Blocos no Formulário |
| :---: | :--- | :---: |
| [**BL1-w**](#bl1-w) | Viga em balanço com carga uniformemente distribuída em todo o vão | — |
| [**BL2-td**](#bl2-td) | Viga em balanço com carga triangular distribuída em todo o vão com máximo na direita | — |
| [**BL3-te**](#bl3-te) | Viga em balanço com carga triangular distribuída em todo o vão com máximo na esquerda | — |
| [**BL4-pe**](#bl4-pe) | Viga em balanço com carga uniforme distribuída na parte esquerda do vão | — |
| [**BL5-pv**](#bl5-pv) | Viga em balanço com carga uniforme distribuída em parte do vão | — |
| [**BL6-ev**](#bl6-ev) | Viga em balanço com carga uniforme distribuída nos extremos do vão | — |
| [**BL7-fa**](#bl7-fa) | Viga em balanço com carga concentrada no vão | — |
| [**BL8-m**](#bl8-m) | Viga em balanço com momento concentrado no vão | — |

### BIENGASTADAS

| Código | Descrição | Blocos no Formulário |
| :---: | :--- | :---: |
| [**BE1-w**](#be1-w) | Viga biengastada com carga uniformemente distribuída em todo o vão | **[BM]** |
| [**BE2-td**](#be2-td) | Viga biengastada com carga triangular distribuída em todo o vão com máximo na direita | — |
| [**BE3-te**](#be3-te) | Viga biengastada com carga triangular distribuída em todo o vão com máximo na esquerda | — |
| [**BE4-tm**](#be4-tm) | Viga biengastada com carga triangular distribuída em todo o vão com máximo meio do vão | — |
| [**BE5-pe**](#be5-pe) | Viga biengastada com carga uniforme distribuída na parte esquerda do vão | — |
| [**BE6-pv**](#be6-pv) | Viga biengastada com carga uniforme distribuída em parte do vão | — |
| [**BE7-ev**](#be7-ev) | Viga biengastada com carga uniforme distribuída nos extremos do vão | — |
| [**BE8-fa**](#be8-fa) | Viga biengastada com carga concentrada no vão | — |
| [**BE9-ff**](#be9-ff) | Viga biengastada com duas cargas concentradas no vão assimétricas | — |
| [**BE10-m**](#be10-m) | Viga biengastada com momento concentrado no vão | — |
| [**BE11-mo**](#be11-mo) | Viga biengastada com momentos concentrados no vão assímetricos | — |

### APOIO-ENGASTE

| Código | Descrição | Blocos no Formulário |
| :---: | :--- | :---: |
| [**AE1-w**](#ae1-w) | Viga apoio-engaste com carga uniformemente distribuída em todo o vão | **[I]**, **[AN]**, **[BK]** |
| [**AE2-td**](#ae2-td) | Viga apoio-engaste com carga triangular distribuída em todo o vão com máximo na direita | — |
| [**AE3-te**](#ae3-te) | Viga apoio-engaste com carga triangular distribuída em todo o vão com máximo na esquerda | — |
| [**AE4-tm**](#ae4-tm) | Viga apoio-engaste com carga triangular distribuída em todo o vão com máximo meio do vão | — |
| [**AE5-pe**](#ae5-pe) | Viga apoio-engaste com carga uniforme distribuída na parte esquerda do vão | **[K]** |
| [**AE6-pv**](#ae6-pv) | Viga apoio-engaste com carga uniforme distribuída em parte do vão | — |
| [**AE7-ev**](#ae7-ev) | Viga apoio-engaste com carga uniforme distribuída nos extremos do vão | — |
| [**AE8-fa**](#ae8-fa) | Viga apoio-engaste com carga concentrada no vão | **[J]**, **[AO]**, **[BL]** |
| [**AE9-ff**](#ae9-ff) | Viga apoio-engaste com duas cargas concentradas no vão assimétricas | — |
| [**AE10-m**](#ae10-m) | Viga apoio-engaste com momento concentrado no vão | **[L]**, **[AP]** |
| [**AE11-mo**](#ae11-mo) | Viga apoio-engaste com momentos concentrados no vão assímetricos | **[BJ]** |

### VÃO-BALANÇO

| Código | Descrição | Blocos no Formulário |
| :---: | :--- | :---: |
| [**VB1-w**](#vb1-w) | Viga vão-balanço com carga uniformemente distribuída em toda a viga | **[AQ]**, **[BN]** |
| [**VB2-wv**](#vb2-wv) | Viga vão-balanço com carga uniformemente distribuída no vão da viga | — |
| [**VB3-wb**](#vb3-wb) | Viga vão-balanço com carga uniformemente distribuída no balanço da viga | — |
| [**VB4-pv**](#vb4-pv) | Viga vão-balanço com carga uniforme distribuída em parte do vão | — |
| [**VB5-fv**](#vb5-fv) | Viga vão-balanço com carga concentrada no vão | — |
| [**VB6-fb**](#vb6-fb) | Viga vão-balanço com carga concentrada no balanço | — |
| [**VB7-m**](#vb7-m) | Viga vão-balanço com momento concentrado no vão | — |
| [**VB8-ma**](#vb8-ma) | Viga vão-balanço com momento concentrado no apoio | — |

### DUPLO-VÃO

| Código | Descrição | Blocos no Formulário |
| :---: | :--- | :---: |
| [**DV1-w**](#dv1-w) | Viga duplo-vão com carga uniformemente distribuída em toda a viga | **[O]** |
| [**DV2-we**](#dv2-we) | Viga duplo-vão com carga uniformemente distribuída no vão da esquerda | **[M]** |
| [**DV3-wd**](#dv3-wd) | Viga duplo-vão com carga uniformemente distribuída no vão da direita | **[N]** |
| [**DV4-wv**](#dv4-wv) | Viga duplo-vão com carga uniformemente distribuída em parte do vão esquerdo da viga | — |
| [**DV5-wd**](#dv5-wd) | Viga duplo-vão com carga uniformemente distribuída em parte do vão direito da viga | — |
| [**DV6-fe**](#dv6-fe) | Viga duplo-vão com carga concentrada no vão da esquerda | — |
| [**DV7-fe**](#dv7-fe) | Viga duplo-vão com carga concentrada no vão da direita | — |
| [**DV8-me**](#dv8-me) | Viga duplo-vão com momento concentrado no vão da esquerda | — |
| [**DV9-me**](#dv9-me) | Viga duplo-vão com momento concentrado no vão da direita | — |
| [**DV10-mm**](#dv10-mm) | Viga duplo-vão com momento concentrado em ambos os vãos | — |

---

## BIAPOIADAS

### BA1-w
- **Descrição:** Viga biapoiada com carga uniformemente distribuída em todo o vão
- **Página offline:** `00. Site Offline/BA1-w.html`
- **Legenda:**
  - $E$ - módulo de elasticidade do material da viga;
  - $I$ - inércia da seção transversal da viga (em torno no eixo que sai da tela);
  - $L$ - comprimento total da viga;
  - $w$ - carga distribuída uniforme;
  - $x$ - posição em uma parte qualquer de um tramo da viga;

#### Flechas
$$\delta_A = \dfrac{w x \left(- L^{3} + 2 L x^{2} - x^{3}\right)}{24 E I}$$

#### Momentos fletores
$$M_A = \dfrac{w x \left(L - x\right)}{2}$$

#### Esforços cortantes
$$V_A = \dfrac{w \left(L - 2 x\right)}{2}$$

#### Reações de apoio
$$R_1 = \dfrac{L w}{2}$$

$$R_2 = \dfrac{L w}{2}$$

#### Equações em Python
```python
# Flechas
deltaA = w*x*(-L**3 + 2*L*x**2 - x**3)/(24*E*I)
# Momentos fletores
MA = w*x*(L - x)/2
# Esforços cortantes
VA = w*(L - 2*x)/2
# Reações de apoio
R1 = L*w/2
R2 = L*w/2
```

---

### BA2-td
- **Descrição:** Viga biapoiada com carga triangular distribuída em todo o vão com máximo na direita
- **Página offline:** `00. Site Offline/BA2-td.html`
- **Legenda:**
  - $E$ - módulo de elasticidade do material da viga;
  - $I$ - inércia da seção transversal da viga (em torno no eixo que sai da tela);
  - $L$ - comprimento total da viga;
  - $w$ - carga distribuída uniforme;
  - $x$ - posição em uma parte qualquer de um tramo da viga;

#### Flechas
$$\delta_A = \dfrac{w x \left(- 7 L^{4} + 10 L^{2} x^{2} - 3 x^{4}\right)}{360 E I L}$$

#### Momentos fletores
$$M_A = \dfrac{w x \left(L^{2} - x^{2}\right)}{6 L}$$

#### Esforços cortantes
$$V_A = \dfrac{w \left(L^{2} - 3 x^{2}\right)}{6 L}$$

#### Reações de apoio
$$R_1 = \dfrac{L w}{6}$$

$$R_2 = \dfrac{L w}{3}$$

#### Equações em Python
```python
# Flechas
deltaA = w*x*(-7*L**4 + 10*L**2*x**2 - 3*x**4)/(360*E*I*L)
# Momentos fletores
MA = w*x*(L**2 - x**2)/(6*L)
# Esforços cortantes
VA = w*(L**2 - 3*x**2)/(6*L)
# Reações de apoio
R1 = L*w/6
R2 = L*w/3
```

---

### BA3-te
- **Descrição:** Viga biapoiada com carga triangular distribuída em todo o vão com máximo na esquerda
- **Página offline:** `00. Site Offline/BA3-te.html`
- **Legenda:**
  - $E$ - módulo de elasticidade do material da viga;
  - $I$ - inércia da seção transversal da viga (em torno no eixo que sai da tela);
  - $L$ - comprimento total da viga;
  - $w$ - carga distribuída uniforme;
  - $x$ - posição em uma parte qualquer de um tramo da viga;

#### Flechas
$$\delta_A = \dfrac{w x \left(- 8 L^{4} + 20 L^{2} x^{2} - 15 L x^{3} + 3 x^{4}\right)}{360 E I L}$$

#### Momentos fletores
$$M_A = \dfrac{w x \left(2 L^{2} - 3 L x + x^{2}\right)}{6 L}$$

#### Esforços cortantes
$$V_A = \dfrac{L w}{3} - w x + \dfrac{w x^{2}}{2 L}$$

#### Reações de apoio
$$R_1 = \dfrac{L w}{3}$$

$$R_2 = \dfrac{L w}{6}$$

#### Equações em Python
```python
# Flechas
deltaA = w*x*(-8*L**4 + 20*L**2*x**2 - 15*L*x**3 + 3*x**4)/(360*E*I*L)
# Momentos fletores
MA = w*x*(2*L**2 - 3*L*x + x**2)/(6*L)
# Esforços cortantes
VA = L*w/3 - w*x + w*x**2/(2*L)
# Reações de apoio
R1 = L*w/3
R2 = L*w/6
```

---

### BA4-tm
- **Descrição:** Viga biapoiada com carga triangular distribuída em todo o vão com máximo meio do vão
- **Página offline:** `00. Site Offline/BA4-tm.html`
- **Legenda:**
  - $E$ - módulo de elasticidade do material da viga;
  - $I$ - inércia da seção transversal da viga (em torno no eixo que sai da tela);
  - $L$ - comprimento total da viga;
  - $w$ - carga distribuída uniforme;
  - $x$ - posição em uma parte qualquer de um tramo da viga;

#### Flechas
$$\delta_A = \dfrac{w x \left(- 25 L^{4} + 40 L^{2} x^{2} - 16 x^{4}\right)}{960 E I L}$$

$$\delta_B = \dfrac{w \left(L \left(- L^{4} - 15 L^{3} x - 40 L^{2} x^{2} + 120 L x^{3} - 80 x^{4}\right) + 16 x^{5}\right)}{960 E I L}$$

#### Momentos fletores
$$M_A = \dfrac{L w x}{4} - \dfrac{w x^{3}}{3 L}$$

$$M_B = \dfrac{w \left(L \left(- L^{2} + 9 L x - 12 x^{2}\right) + 4 x^{3}\right)}{12 L}$$

#### Esforços cortantes
$$V_A = \dfrac{L w}{4} - \dfrac{w x^{2}}{L}$$

$$V_B = \dfrac{w \left(L \left(3 L - 8 x\right) + 4 x^{2}\right)}{4 L}$$

#### Reações de apoio
$$R_1 = \dfrac{L w}{4}$$

$$R_2 = \dfrac{L w}{4}$$

#### Equações em Python
```python
# Flechas
deltaA = w*x*(-25*L**4 + 40*L**2*x**2 - 16*x**4)/(960*E*I*L)
deltaB = w*(L*(-L**4 - 15*L**3*x - 40*L**2*x**2 + 120*L*x**3 - 80*x**4) + 16*x**5)/(960*E*I*L)
# Momentos fletores
MA = L*w*x/4 - w*x**3/(3*L)
MB = w*(L*(-L**2 + 9*L*x - 12*x**2) + 4*x**3)/(12*L)
# Esforços cortantes
VA = L*w/4 - w*x**2/L
VB = w*(L*(3*L - 8*x) + 4*x**2)/(4*L)
# Reações de apoio
R1 = L*w/4
R2 = L*w/4
```

---

### BA5-pe
- **Descrição:** Viga biapoiada com carga uniforme distribuída na parte esquerda do vão
- **Página offline:** `00. Site Offline/BA5-pe.html`
- **Legenda:**
  - $E$ - módulo de elasticidade do material da viga;
  - $I$ - inércia da seção transversal da viga (em torno no eixo que sai da tela);
  - $L$ - comprimento total da viga;
  - $a$ - comprimento do tramo A;
  - $w$ - carga distribuída uniforme;
  - $x$ - posição em uma parte qualquer de um tramo da viga;

#### Flechas
$$\delta_A = \dfrac{w x \left(- 4 L^{2} a^{2} + 4 L a^{3} + 4 L a x^{2} - L x^{3} - a^{4} - 2 a^{2} x^{2}\right)}{24 E I L}$$

$$\delta_B = \dfrac{a^{2} w \left(L \left(- 4 L x + a^{2} + 6 x^{2}\right) - x \left(a^{2} + 2 x^{2}\right)\right)}{24 E I L}$$

#### Momentos fletores
$$M_A = \dfrac{w x \left(2 L a - L x - a^{2}\right)}{2 L}$$

$$M_B = \dfrac{a^{2} w \left(L - x\right)}{2 L}$$

#### Esforços cortantes
$$V_A = a w - w x - \dfrac{a^{2} w}{2 L}$$

$$V_B = - \dfrac{a^{2} w}{2 L}$$

#### Reações de apoio
$$R_1 = \dfrac{a w \left(2 L - a\right)}{2 L}$$

$$R_2 = \dfrac{a^{2} w}{2 L}$$

#### Equações em Python
```python
# Flechas
deltaA = w*x*(-4*L**2*a**2 + 4*L*a**3 + 4*L*a*x**2 - L*x**3 - a**4 - 2*a**2*x**2)/(24*E*I*L)
deltaB = a**2*w*(L*(-4*L*x + a**2 + 6*x**2) - x*(a**2 + 2*x**2))/(24*E*I*L)
# Momentos fletores
MA = w*x*(2*L*a - L*x - a**2)/(2*L)
MB = a**2*w*(L - x)/(2*L)
# Esforços cortantes
VA = a*w - w*x - a**2*w/(2*L)
VB = -a**2*w/(2*L)
# Reações de apoio
R1 = a*w*(2*L - a)/(2*L)
R2 = a**2*w/(2*L)
```

---

### BA6-pv
- **Descrição:** Viga biapoiada com carga uniforme distribuída em parte do vão
- **Página offline:** `00. Site Offline/BA6-pv.html`
- **Legenda:**
  - $E$ - módulo de elasticidade do material da viga;
  - $I$ - inércia da seção transversal da viga (em torno no eixo que sai da tela);
  - $L$ - comprimento total da viga;
  - $a$ - comprimento do tramo A;
  - $b$ - comprimento do tramo B;
  - $w$ - carga distribuída uniforme;
  - $x$ - posição em uma parte qualquer de um tramo da viga;

#### Flechas
$$\delta_A = \dfrac{b w x \left(- 8 L^{2} a - 4 L^{2} b + 12 L a^{2} + 12 L a b + 4 L b^{2} + 4 L x^{2} - 4 a^{3} - 6 a^{2} b - 4 a b^{2} - 4 a x^{2} - b^{3} - 2 b x^{2}\right)}{24 E I L}$$

$$\delta_B = \dfrac{w \left(L \left(- 8 L a b x - 4 L b^{2} x - a^{4} + 4 a^{3} x + 12 a^{2} b x - 6 a^{2} x^{2} + 12 a b^{2} x + 4 a x^{3} + 4 b^{3} x + 4 b x^{3} - x^{4}\right) - b x \left(4 a^{3} + 6 a^{2} b + 4 a b^{2} + 4 a x^{2} + b^{3} + 2 b x^{2}\right)\right)}{24 E I L}$$

$$\delta_C = \dfrac{b w \left(L \left(- 8 L a x - 4 L b x + 4 a^{3} + 6 a^{2} b + 4 a b^{2} + 12 a x^{2} + b^{3} + 6 b x^{2}\right) - x \left(4 a^{3} + 6 a^{2} b + 4 a b^{2} + 4 a x^{2} + b^{3} + 2 b x^{2}\right)\right)}{24 E I L}$$

#### Momentos fletores
$$M_A = \dfrac{b w x \left(2 L - 2 a - b\right)}{2 L}$$

$$M_B = \dfrac{w \left(L \left(- a^{2} + 2 a x + 2 b x - x^{2}\right) - 2 a b x - b^{2} x\right)}{2 L}$$

$$M_C = \dfrac{b w \left(L \left(2 a + b\right) - 2 a x - b x\right)}{2 L}$$

#### Esforços cortantes
$$V_A = \dfrac{b w \left(2 L - 2 a - b\right)}{2 L}$$

$$V_B = \dfrac{w \left(2 L \left(a + b - x\right) - 2 a b - b^{2}\right)}{2 L}$$

$$V_C = - \dfrac{b w \left(2 a + b\right)}{2 L}$$

#### Reações de apoio
$$R_1 = \dfrac{b w \left(2 L - 2 a - b\right)}{2 L}$$

$$R_2 = \dfrac{b w \left(2 a + b\right)}{2 L}$$

#### Equações em Python
```python
# Flechas
deltaA = b*w*x*(-8*L**2*a - 4*L**2*b + 12*L*a**2 + 12*L*a*b + 4*L*b**2 + 4*L*x**2 - 4*a**3 - 6*a**2*b - 4*a*b**2 - 4*a*x**2 - b**3 - 2*b*x**2)/(24*E*I*L)
deltaB = w*(L*(-8*L*a*b*x - 4*L*b**2*x - a**4 + 4*a**3*x + 12*a**2*b*x - 6*a**2*x**2 + 12*a*b**2*x + 4*a*x**3 + 4*b**3*x + 4*b*x**3 - x**4) - b*x*(4*a**3 + 6*a**2*b + 4*a*b**2 + 4*a*x**2 + b**3 + 2*b*x**2))/(24*E*I*L)
deltaC = b*w*(L*(-8*L*a*x - 4*L*b*x + 4*a**3 + 6*a**2*b + 4*a*b**2 + 12*a*x**2 + b**3 + 6*b*x**2) - x*(4*a**3 + 6*a**2*b + 4*a*b**2 + 4*a*x**2 + b**3 + 2*b*x**2))/(24*E*I*L)
# Momentos fletores
MA = b*w*x*(2*L - 2*a - b)/(2*L)
MB = w*(L*(-a**2 + 2*a*x + 2*b*x - x**2) - 2*a*b*x - b**2*x)/(2*L)
MC = b*w*(L*(2*a + b) - 2*a*x - b*x)/(2*L)
# Esforços cortantes
VA = b*w*(2*L - 2*a - b)/(2*L)
VB = w*(2*L*(a + b - x) - 2*a*b - b**2)/(2*L)
VC = -b*w*(2*a + b)/(2*L)
# Reações de apoio
R1 = b*w*(2*L - 2*a - b)/(2*L)
R2 = b*w*(2*a + b)/(2*L)
```

---

### BA7-ev
- **Descrição:** Viga biapoiada com carga uniforme distribuída nos extremos do vão
- **Página offline:** `00. Site Offline/BA7-ev.html`
- **Legenda:**
  - $E$ - módulo de elasticidade do material da viga;
  - $I$ - inércia da seção transversal da viga (em torno no eixo que sai da tela);
  - $L$ - comprimento total da viga;
  - $a$ - comprimento do tramo A;
  - $b$ - comprimento do tramo B;
  - $w$ - carga distribuída uniforme;
  - $x$ - posição em uma parte qualquer de um tramo da viga;

#### Flechas
$$\delta_A = \dfrac{w x \left(- 4 L^{2} a^{2} - 2 L^{2} b^{2} + 4 L a^{3} + 4 L a x^{2} - L x^{3} - a^{4} - 2 a^{2} x^{2} + b^{4} + 2 b^{2} x^{2}\right)}{24 E I L}$$

$$\delta_B = \dfrac{w \left(L \left(- 4 L a^{2} x - 2 L b^{2} x + a^{4} + 6 a^{2} x^{2}\right) + x \left(- a^{4} - 2 a^{2} x^{2} + b^{4} + 2 b^{2} x^{2}\right)\right)}{24 E I L}$$

$$\delta_C = \dfrac{w \left(L \left(- L^{4} + 4 L^{3} b + 4 L^{3} x - 6 L^{2} b^{2} - 12 L^{2} b x - 6 L^{2} x^{2} - 4 L a^{2} x + 4 L b^{3} + 10 L b^{2} x + 12 L b x^{2} + 4 L x^{3} + a^{4} + 6 a^{2} x^{2} - b^{4} - 4 b^{3} x - 6 b^{2} x^{2} - 4 b x^{3} - x^{4}\right) + x \left(- a^{4} - 2 a^{2} x^{2} + b^{4} + 2 b^{2} x^{2}\right)\right)}{24 E I L}$$

#### Momentos fletores
$$M_A = \dfrac{w x \left(2 L a - L x - a^{2} + b^{2}\right)}{2 L}$$

$$M_B = \dfrac{w \left(L a^{2} - a^{2} x + b^{2} x\right)}{2 L}$$

$$M_C = \dfrac{w \left(L \left(- L^{2} + 2 L b + 2 L x + a^{2} - b^{2} - 2 b x - x^{2}\right) - a^{2} x + b^{2} x\right)}{2 L}$$

#### Esforços cortantes
$$V_A = \dfrac{w \left(2 L a - 2 L x - a^{2} + b^{2}\right)}{2 L}$$

$$V_B = \dfrac{w \left(- a^{2} + b^{2}\right)}{2 L}$$

$$V_C = \dfrac{w \left(2 L \left(L - b - x\right) - a^{2} + b^{2}\right)}{2 L}$$

#### Reações de apoio
$$R_1 = \dfrac{w \left(2 L a - a^{2} + b^{2}\right)}{2 L}$$

$$R_2 = \dfrac{w \left(2 L b + a^{2} - b^{2}\right)}{2 L}$$

#### Equações em Python
```python
# Flechas
deltaA = w*x*(-4*L**2*a**2 - 2*L**2*b**2 + 4*L*a**3 + 4*L*a*x**2 - L*x**3 - a**4 - 2*a**2*x**2 + b**4 + 2*b**2*x**2)/(24*E*I*L)
deltaB = w*(L*(-4*L*a**2*x - 2*L*b**2*x + a**4 + 6*a**2*x**2) + x*(-a**4 - 2*a**2*x**2 + b**4 + 2*b**2*x**2))/(24*E*I*L)
deltaC = w*(L*(-L**4 + 4*L**3*b + 4*L**3*x - 6*L**2*b**2 - 12*L**2*b*x - 6*L**2*x**2 - 4*L*a**2*x + 4*L*b**3 + 10*L*b**2*x + 12*L*b*x**2 + 4*L*x**3 + a**4 + 6*a**2*x**2 - b**4 - 4*b**3*x - 6*b**2*x**2 - 4*b*x**3 - x**4) + x*(-a**4 - 2*a**2*x**2 + b**4 + 2*b**2*x**2))/(24*E*I*L)
# Momentos fletores
MA = w*x*(2*L*a - L*x - a**2 + b**2)/(2*L)
MB = w*(L*a**2 - a**2*x + b**2*x)/(2*L)
MC = w*(L*(-L**2 + 2*L*b + 2*L*x + a**2 - b**2 - 2*b*x - x**2) - a**2*x + b**2*x)/(2*L)
# Esforços cortantes
VA = w*(2*L*a - 2*L*x - a**2 + b**2)/(2*L)
VB = w*(-a**2 + b**2)/(2*L)
VC = w*(2*L*(L - b - x) - a**2 + b**2)/(2*L)
# Reações de apoio
R1 = w*(2*L*a - a**2 + b**2)/(2*L)
R2 = w*(2*L*b + a**2 - b**2)/(2*L)
```

---

### BA8-fa
- **Descrição:** Viga biapoiada com carga concentrada no vão
- **Página offline:** `00. Site Offline/BA8-fa.html`
- **Legenda:**
  - $E$ - módulo de elasticidade do material da viga;
  - $F$ - carga concentrada;
  - $I$ - inércia da seção transversal da viga (em torno no eixo que sai da tela);
  - $L$ - comprimento total da viga;
  - $a$ - comprimento do tramo A;
  - $x$ - posição em uma parte qualquer de um tramo da viga;

#### Flechas
$$\delta_A = \dfrac{F x \left(- 2 L^{2} a + 3 L a^{2} + L x^{2} - a^{3} - a x^{2}\right)}{6 E I L}$$

$$\delta_B = \dfrac{F a \left(L \left(- 2 L x + a^{2} + 3 x^{2}\right) - x \left(a^{2} + x^{2}\right)\right)}{6 E I L}$$

#### Momentos fletores
$$M_A = \dfrac{F x \left(L - a\right)}{L}$$

$$M_B = \dfrac{F a \left(L - x\right)}{L}$$

#### Esforços cortantes
$$V_A = \dfrac{F \left(L - a\right)}{L}$$

$$V_B = - \dfrac{F a}{L}$$

#### Reações de apoio
$$R_1 = \dfrac{F \left(L - a\right)}{L}$$

$$R_2 = \dfrac{F a}{L}$$

#### Equações em Python
```python
# Flechas
deltaA = F*x*(-2*L**2*a + 3*L*a**2 + L*x**2 - a**3 - a*x**2)/(6*E*I*L)
deltaB = F*a*(L*(-2*L*x + a**2 + 3*x**2) - x*(a**2 + x**2))/(6*E*I*L)
# Momentos fletores
MA = F*x*(L - a)/L
MB = F*a*(L - x)/L
# Esforços cortantes
VA = F*(L - a)/L
VB = -F*a/L
# Reações de apoio
R1 = F*(L - a)/L
R2 = F*a/L
```

---

### BA9-ff
- **Descrição:** Viga biapoiada com duas cargas concentradas no vão assimétricas
- **Página offline:** `00. Site Offline/BA9-ff.html`
- **Legenda:**
  - $E$ - módulo de elasticidade do material da viga;
  - $F$ - carga concentrada;
  - $I$ - inércia da seção transversal da viga (em torno no eixo que sai da tela);
  - $L$ - comprimento total da viga;
  - $a$ - comprimento do tramo A;
  - $b$ - comprimento do tramo B;
  - $x$ - posição em uma parte qualquer de um tramo da viga;

#### Flechas
$$\delta_A = \dfrac{F x \left(- 2 L^{2} a - L^{2} b + 3 L a^{2} + L x^{2} - a^{3} - a x^{2} + b^{3} + b x^{2}\right)}{6 E I L}$$

$$\delta_B = \dfrac{F \left(L \left(- 2 L a x - L b x + a^{3} + 3 a x^{2}\right) + x \left(- a^{3} - a x^{2} + b^{3} + b x^{2}\right)\right)}{6 E I L}$$

$$\delta_C = \dfrac{F \left(L \left(L^{3} - 3 L^{2} b - 3 L^{2} x - 2 L a x + 3 L b^{2} + 5 L b x + 3 L x^{2} + a^{3} + 3 a x^{2} - b^{3} - 3 b^{2} x - 3 b x^{2} - x^{3}\right) + x \left(- a^{3} - a x^{2} + b^{3} + b x^{2}\right)\right)}{6 E I L}$$

#### Momentos fletores
$$M_A = \dfrac{F x \left(L - a + b\right)}{L}$$

$$M_B = \dfrac{F \left(L a - a x + b x\right)}{L}$$

$$M_C = \dfrac{F \left(L \left(L + a - b - x\right) - a x + b x\right)}{L}$$

#### Esforços cortantes
$$V_A = \dfrac{F \left(L - a + b\right)}{L}$$

$$V_B = \dfrac{F \left(- a + b\right)}{L}$$

$$V_C = \dfrac{F \left(- L - a + b\right)}{L}$$

#### Reações de apoio
$$R_1 = \dfrac{F \left(L - a + b\right)}{L}$$

$$R_2 = \dfrac{F \left(L + a - b\right)}{L}$$

#### Equações em Python
```python
# Flechas
deltaA = F*x*(-2*L**2*a - L**2*b + 3*L*a**2 + L*x**2 - a**3 - a*x**2 + b**3 + b*x**2)/(6*E*I*L)
deltaB = F*(L*(-2*L*a*x - L*b*x + a**3 + 3*a*x**2) + x*(-a**3 - a*x**2 + b**3 + b*x**2))/(6*E*I*L)
deltaC = F*(L*(L**3 - 3*L**2*b - 3*L**2*x - 2*L*a*x + 3*L*b**2 + 5*L*b*x + 3*L*x**2 + a**3 + 3*a*x**2 - b**3 - 3*b**2*x - 3*b*x**2 - x**3) + x*(-a**3 - a*x**2 + b**3 + b*x**2))/(6*E*I*L)
# Momentos fletores
MA = F*x*(L - a + b)/L
MB = F*(L*a - a*x + b*x)/L
MC = F*(L*(L + a - b - x) - a*x + b*x)/L
# Esforços cortantes
VA = F*(L - a + b)/L
VB = F*(-a + b)/L
VC = F*(-L - a + b)/L
# Reações de apoio
R1 = F*(L - a + b)/L
R2 = F*(L + a - b)/L
```

---

### BA10-m
- **Descrição:** Viga biapoiada com momento concentrado no vão
- **Página offline:** `00. Site Offline/BA10-m.html`
- **Legenda:**
  - $E$ - módulo de elasticidade do material da viga;
  - $I$ - inércia da seção transversal da viga (em torno no eixo que sai da tela);
  - $L$ - comprimento total da viga;
  - $M$ - momento concentrado;
  - $a$ - comprimento do tramo A;
  - $x$ - posição em uma parte qualquer de um tramo da viga;

#### Flechas
$$\delta_A = \dfrac{M x \left(- 2 L^{2} + 6 L a - 3 a^{2} - x^{2}\right)}{6 E I L}$$

$$\delta_B = \dfrac{M \left(L \left(- 2 L x + 3 a^{2} + 3 x^{2}\right) - x \left(3 a^{2} + x^{2}\right)\right)}{6 E I L}$$

#### Momentos fletores
$$M_A = - \dfrac{M x}{L}$$

$$M_B = \dfrac{M \left(L - x\right)}{L}$$

#### Esforços cortantes
$$V_A = - \dfrac{M}{L}$$

$$V_B = - \dfrac{M}{L}$$

#### Reações de apoio
$$R_1 = - \dfrac{M}{L}$$

$$R_2 = \dfrac{M}{L}$$

#### Equações em Python
```python
# Flechas
deltaA = M*x*(-2*L**2 + 6*L*a - 3*a**2 - x**2)/(6*E*I*L)
deltaB = M*(L*(-2*L*x + 3*a**2 + 3*x**2) - x*(3*a**2 + x**2))/(6*E*I*L)
# Momentos fletores
MA = -M*x/L
MB = M*(L - x)/L
# Esforços cortantes
VA = -M/L
VB = -M/L
# Reações de apoio
R1 = -M/L
R2 = M/L
```

---

### BA11-mo
- **Descrição:** Viga biapoiada com momentos concentrados no vão assímetricos
- **Página offline:** `00. Site Offline/BA11-mo.html`
- **Legenda:**
  - $E$ - módulo de elasticidade do material da viga;
  - $I$ - inércia da seção transversal da viga (em torno no eixo que sai da tela);
  - $L$ - comprimento total da viga;
  - $M$ - momento concentrado;
  - $a$ - comprimento do tramo A;
  - $b$ - comprimento do tramo B;
  - $x$ - posição em uma parte qualquer de um tramo da viga;

#### Flechas
$$\delta_A = \dfrac{M x \left(- L^{2} + 6 L a - 3 a^{2} - 3 b^{2} - 2 x^{2}\right)}{6 E I L}$$

$$\delta_B = \dfrac{M \left(L \left(- L x + 3 a^{2} + 3 x^{2}\right) - x \left(3 a^{2} + 3 b^{2} + 2 x^{2}\right)\right)}{6 E I L}$$

$$\delta_C = \dfrac{M \left(L \left(3 L^{2} - 6 L b - 7 L x + 3 a^{2} + 3 b^{2} + 6 b x + 6 x^{2}\right) - x \left(3 a^{2} + 3 b^{2} + 2 x^{2}\right)\right)}{6 E I L}$$

#### Momentos fletores
$$M_A = - \dfrac{2 M x}{L}$$

$$M_B = \dfrac{M \left(L - 2 x\right)}{L}$$

$$M_C = \dfrac{2 M \left(L - x\right)}{L}$$

#### Esforços cortantes
$$V_A = - \dfrac{2 M}{L}$$

$$V_B = - \dfrac{2 M}{L}$$

$$V_C = - \dfrac{2 M}{L}$$

#### Reações de apoio
$$R_1 = - \dfrac{2 M}{L}$$

$$R_2 = \dfrac{2 M}{L}$$

#### Equações em Python
```python
# Flechas
deltaA = M*x*(-L**2 + 6*L*a - 3*a**2 - 3*b**2 - 2*x**2)/(6*E*I*L)
deltaB = M*(L*(-L*x + 3*a**2 + 3*x**2) - x*(3*a**2 + 3*b**2 + 2*x**2))/(6*E*I*L)
deltaC = M*(L*(3*L**2 - 6*L*b - 7*L*x + 3*a**2 + 3*b**2 + 6*b*x + 6*x**2) - x*(3*a**2 + 3*b**2 + 2*x**2))/(6*E*I*L)
# Momentos fletores
MA = -2*M*x/L
MB = M*(L - 2*x)/L
MC = 2*M*(L - x)/L
# Esforços cortantes
VA = -2*M/L
VB = -2*M/L
VC = -2*M/L
# Reações de apoio
R1 = -2*M/L
R2 = 2*M/L
```

---

## EM BALANÇO

### BL1-w
- **Descrição:** Viga em balanço com carga uniformemente distribuída em todo o vão
- **Página offline:** `00. Site Offline/BL1-w.html`
- **Legenda:**
  - $E$ - módulo de elasticidade do material da viga;
  - $I$ - inércia da seção transversal da viga (em torno no eixo que sai da tela);
  - $L$ - comprimento total da viga;
  - $w$ - carga distribuída uniforme;
  - $x$ - posição em uma parte qualquer de um tramo da viga;

#### Flechas
$$\delta_A = \dfrac{w x^{2} \left(- 6 L^{2} + 4 L x - x^{2}\right)}{24 E I}$$

#### Momentos fletores
$$M_A = \dfrac{w \left(- L^{2} + 2 L x - x^{2}\right)}{2}$$

#### Esforços cortantes
$$V_A = w \left(L - x\right)$$

#### Reações de apoio
$$R_1 = L w$$

$$M_1 = \dfrac{L^{2} w}{2}$$

#### Equações em Python
```python
# Flechas
deltaA = w*x**2*(-6*L**2 + 4*L*x - x**2)/(24*E*I)
# Momentos fletores
MA = w*(-L**2 + 2*L*x - x**2)/2
# Esforços cortantes
VA = w*(L - x)
# Reações de apoio
R1 = L*w
M1 = L**2*w/2
```

---

### BL2-td
- **Descrição:** Viga em balanço com carga triangular distribuída em todo o vão com máximo na direita
- **Página offline:** `00. Site Offline/BL2-td.html`
- **Legenda:**
  - $E$ - módulo de elasticidade do material da viga;
  - $I$ - inércia da seção transversal da viga (em torno no eixo que sai da tela);
  - $L$ - comprimento total da viga;
  - $w$ - carga distribuída uniforme;
  - $x$ - posição em uma parte qualquer de um tramo da viga;

#### Flechas
$$\delta_A = \dfrac{w x^{2} \left(- 20 L^{3} + 10 L^{2} x - x^{3}\right)}{120 E I L}$$

#### Momentos fletores
$$M_A = \dfrac{w \left(- 2 L^{3} + 3 L^{2} x - x^{3}\right)}{6 L}$$

#### Esforços cortantes
$$V_A = \dfrac{w \left(L^{2} - x^{2}\right)}{2 L}$$

#### Reações de apoio
$$R_1 = \dfrac{L w}{2}$$

$$M_1 = \dfrac{L^{2} w}{3}$$

#### Equações em Python
```python
# Flechas
deltaA = w*x**2*(-20*L**3 + 10*L**2*x - x**3)/(120*E*I*L)
# Momentos fletores
MA = w*(-2*L**3 + 3*L**2*x - x**3)/(6*L)
# Esforços cortantes
VA = w*(L**2 - x**2)/(2*L)
# Reações de apoio
R1 = L*w/2
M1 = L**2*w/3
```

---

### BL3-te
- **Descrição:** Viga em balanço com carga triangular distribuída em todo o vão com máximo na esquerda
- **Página offline:** `00. Site Offline/BL3-te.html`
- **Legenda:**
  - $E$ - módulo de elasticidade do material da viga;
  - $I$ - inércia da seção transversal da viga (em torno no eixo que sai da tela);
  - $L$ - comprimento total da viga;
  - $w$ - carga distribuída uniforme;
  - $x$ - posição em uma parte qualquer de um tramo da viga;

#### Flechas
$$\delta_A = \dfrac{w x^{2} \left(- 10 L^{3} + 10 L^{2} x - 5 L x^{2} + x^{3}\right)}{120 E I L}$$

#### Momentos fletores
$$M_A = \dfrac{w \left(- L^{3} + 3 L^{2} x - 3 L x^{2} + x^{3}\right)}{6 L}$$

#### Esforços cortantes
$$V_A = \dfrac{w \left(L^{2} - 2 L x + x^{2}\right)}{2 L}$$

#### Reações de apoio
$$R_1 = \dfrac{L w}{2}$$

$$M_1 = \dfrac{L^{2} w}{6}$$

#### Equações em Python
```python
# Flechas
deltaA = w*x**2*(-10*L**3 + 10*L**2*x - 5*L*x**2 + x**3)/(120*E*I*L)
# Momentos fletores
MA = w*(-L**3 + 3*L**2*x - 3*L*x**2 + x**3)/(6*L)
# Esforços cortantes
VA = w*(L**2 - 2*L*x + x**2)/(2*L)
# Reações de apoio
R1 = L*w/2
M1 = L**2*w/6
```

---

### BL4-pe
- **Descrição:** Viga em balanço com carga uniforme distribuída na parte esquerda do vão
- **Página offline:** `00. Site Offline/BL4-pe.html`
- **Legenda:**
  - $E$ - módulo de elasticidade do material da viga;
  - $I$ - inércia da seção transversal da viga (em torno no eixo que sai da tela);
  - $a$ - comprimento do tramo A;
  - $w$ - carga distribuída uniforme;
  - $x$ - posição em uma parte qualquer de um tramo da viga;
  - $L$ - comprimento total da viga;

#### Flechas
$$\delta_A = \dfrac{w x^{2} \left(- 6 a^{2} + 4 a x - x^{2}\right)}{24 E I}$$

$$\delta_B = \dfrac{a^{3} w \left(a - 4 x\right)}{24 E I}$$

#### Momentos fletores
$$M_A = \dfrac{w \left(- a^{2} + 2 a x - x^{2}\right)}{2}$$

$$M_B = 0$$

#### Esforços cortantes
$$V_A = w \left(a - x\right)$$

$$V_B = 0$$

#### Reações de apoio
$$R_1 = a w$$

$$M_1 = \dfrac{a^{2} w}{2}$$

#### Equações em Python
```python
# Flechas
deltaA = w*x**2*(-6*a**2 + 4*a*x - x**2)/(24*E*I)
deltaB = a**3*w*(a - 4*x)/(24*E*I)
# Momentos fletores
MA = w*(-a**2 + 2*a*x - x**2)/2
MB = 0
# Esforços cortantes
VA = w*(a - x)
VB = 0
# Reações de apoio
R1 = a*w
M1 = a**2*w/2
```

---

### BL5-pv
- **Descrição:** Viga em balanço com carga uniforme distribuída em parte do vão
- **Página offline:** `00. Site Offline/BL5-pv.html`
- **Legenda:**
  - $E$ - módulo de elasticidade do material da viga;
  - $I$ - inércia da seção transversal da viga (em torno no eixo que sai da tela);
  - $a$ - comprimento do tramo A;
  - $b$ - comprimento do tramo B;
  - $w$ - carga distribuída uniforme;
  - $x$ - posição em uma parte qualquer de um tramo da viga;
  - $L$ - comprimento total da viga;

#### Flechas
$$\delta_A = \dfrac{b w x^{2} \left(- 6 a - 3 b + 2 x\right)}{12 E I}$$

$$\delta_B = \dfrac{w \left(- a^{4} + 4 a^{3} x - 6 a^{2} x^{2} - 12 a b x^{2} + 4 a x^{3} - 6 b^{2} x^{2} + 4 b x^{3} - x^{4}\right)}{24 E I}$$

$$\delta_C = \dfrac{b w \left(4 a^{3} + 6 a^{2} b - 12 a^{2} x + 4 a b^{2} - 12 a b x + b^{3} - 4 b^{2} x\right)}{24 E I}$$

#### Momentos fletores
$$M_A = \dfrac{b w \left(- 2 a - b + 2 x\right)}{2}$$

$$M_B = \dfrac{w \left(- a^{2} - 2 a b + 2 a x - b^{2} + 2 b x - x^{2}\right)}{2}$$

$$M_C = 0$$

#### Esforços cortantes
$$V_A = b w$$

$$V_B = w \left(a + b - x\right)$$

$$V_C = 0$$

#### Reações de apoio
$$R_1 = b w$$

$$M_1 = \dfrac{b w \left(2 a + b\right)}{2}$$

#### Equações em Python
```python
# Flechas
deltaA = b*w*x**2*(-6*a - 3*b + 2*x)/(12*E*I)
deltaB = w*(-a**4 + 4*a**3*x - 6*a**2*x**2 - 12*a*b*x**2 + 4*a*x**3 - 6*b**2*x**2 + 4*b*x**3 - x**4)/(24*E*I)
deltaC = b*w*(4*a**3 + 6*a**2*b - 12*a**2*x + 4*a*b**2 - 12*a*b*x + b**3 - 4*b**2*x)/(24*E*I)
# Momentos fletores
MA = b*w*(-2*a - b + 2*x)/2
MB = w*(-a**2 - 2*a*b + 2*a*x - b**2 + 2*b*x - x**2)/2
MC = 0
# Esforços cortantes
VA = b*w
VB = w*(a + b - x)
VC = 0
# Reações de apoio
R1 = b*w
M1 = b*w*(2*a + b)/2
```

---

### BL6-ev
- **Descrição:** Viga em balanço com carga uniforme distribuída nos extremos do vão
- **Página offline:** `00. Site Offline/BL6-ev.html`
- **Legenda:**
  - $E$ - módulo de elasticidade do material da viga;
  - $I$ - inércia da seção transversal da viga (em torno no eixo que sai da tela);
  - $L$ - comprimento total da viga;
  - $a$ - comprimento do tramo A;
  - $b$ - comprimento do tramo B;
  - $w$ - carga distribuída uniforme;
  - $x$ - posição em uma parte qualquer de um tramo da viga;

#### Flechas
$$\delta_A = \dfrac{w x^{2} \left(- 12 L b - 6 a^{2} + 4 a x + 6 b^{2} + 4 b x - x^{2}\right)}{24 E I}$$

$$\delta_B = \dfrac{w \left(- 12 L b x^{2} + a^{4} - 4 a^{3} x + 6 b^{2} x^{2} + 4 b x^{3}\right)}{24 E I}$$

$$\delta_C = \dfrac{w \left(- L^{4} + 4 L^{3} b + 4 L^{3} x - 6 L^{2} b^{2} - 12 L^{2} b x - 6 L^{2} x^{2} + 4 L b^{3} + 12 L b^{2} x + 4 L x^{3} + a^{4} - 4 a^{3} x - b^{4} - 4 b^{3} x - x^{4}\right)}{24 E I}$$

#### Momentos fletores
$$M_A = \dfrac{w \left(- 2 L b - a^{2} + 2 a x + b^{2} + 2 b x - x^{2}\right)}{2}$$

$$M_B = \dfrac{b w \left(- 2 L + b + 2 x\right)}{2}$$

$$M_C = \dfrac{w \left(- L^{2} + 2 L x - x^{2}\right)}{2}$$

#### Esforços cortantes
$$V_A = w \left(a + b - x\right)$$

$$V_B = b w$$

$$V_C = w \left(L - x\right)$$

#### Reações de apoio
$$R_1 = w \left(a + b\right)$$

$$M_1 = \dfrac{w \left(2 L b + a^{2} - b^{2}\right)}{2}$$

#### Equações em Python
```python
# Flechas
deltaA = w*x**2*(-12*L*b - 6*a**2 + 4*a*x + 6*b**2 + 4*b*x - x**2)/(24*E*I)
deltaB = w*(-12*L*b*x**2 + a**4 - 4*a**3*x + 6*b**2*x**2 + 4*b*x**3)/(24*E*I)
deltaC = w*(-L**4 + 4*L**3*b + 4*L**3*x - 6*L**2*b**2 - 12*L**2*b*x - 6*L**2*x**2 + 4*L*b**3 + 12*L*b**2*x + 4*L*x**3 + a**4 - 4*a**3*x - b**4 - 4*b**3*x - x**4)/(24*E*I)
# Momentos fletores
MA = w*(-2*L*b - a**2 + 2*a*x + b**2 + 2*b*x - x**2)/2
MB = b*w*(-2*L + b + 2*x)/2
MC = w*(-L**2 + 2*L*x - x**2)/2
# Esforços cortantes
VA = w*(a + b - x)
VB = b*w
VC = w*(L - x)
# Reações de apoio
R1 = w*(a + b)
M1 = w*(2*L*b + a**2 - b**2)/2
```

---

### BL7-fa
- **Descrição:** Viga em balanço com carga concentrada no vão
- **Página offline:** `00. Site Offline/BL7-fa.html`
- **Legenda:**
  - $E$ - módulo de elasticidade do material da viga;
  - $F$ - carga concentrada;
  - $I$ - inércia da seção transversal da viga (em torno no eixo que sai da tela);
  - $a$ - comprimento do tramo A;
  - $x$ - posição em uma parte qualquer de um tramo da viga;
  - $L$ - comprimento total da viga;

#### Flechas
$$\delta_A = \dfrac{F x^{2} \left(- 3 a + x\right)}{6 E I}$$

$$\delta_B = \dfrac{F a^{2} \left(a - 3 x\right)}{6 E I}$$

#### Momentos fletores
$$M_A = F \left(- a + x\right)$$

$$M_B = 0$$

#### Esforços cortantes
$$V_A = F$$

$$V_B = 0$$

#### Reações de apoio
$$R_1 = F$$

$$M_1 = F a$$

#### Equações em Python
```python
# Flechas
deltaA = F*x**2*(-3*a + x)/(6*E*I)
deltaB = F*a**2*(a - 3*x)/(6*E*I)
# Momentos fletores
MA = F*(-a + x)
MB = 0
# Esforços cortantes
VA = F
VB = 0
# Reações de apoio
R1 = F
M1 = F*a
```

---

### BL8-m
- **Descrição:** Viga em balanço com momento concentrado no vão
- **Página offline:** `00. Site Offline/BL8-m.html`
- **Legenda:**
  - $E$ - módulo de elasticidade do material da viga;
  - $I$ - inércia da seção transversal da viga (em torno no eixo que sai da tela);
  - $M$ - momento concentrado;
  - $a$ - comprimento do tramo A;
  - $x$ - posição em uma parte qualquer de um tramo da viga;
  - $L$ - comprimento total da viga;

#### Flechas
$$\delta_A = - \dfrac{M x^{2}}{2 E I}$$

$$\delta_B = \dfrac{M a \left(a - 2 x\right)}{2 E I}$$

#### Momentos fletores
$$M_A = - M$$

$$M_B = 0$$

#### Esforços cortantes
$$V_A = 0$$

$$V_B = 0$$

#### Reações de apoio
$$R_1 = 0$$

$$M_1 = M$$

#### Equações em Python
```python
# Flechas
deltaA = -M*x**2/(2*E*I)
deltaB = M*a*(a - 2*x)/(2*E*I)
# Momentos fletores
MA = -M
MB = 0
# Esforços cortantes
VA = 0
VB = 0
# Reações de apoio
R1 = 0
M1 = M
```

---

## BIENGASTADAS

### BE1-w
- **Descrição:** Viga biengastada com carga uniformemente distribuída em todo o vão
- **Equivalente nos formulários da prova:** **[BM]**
- **Página offline:** `00. Site Offline/BE1-w.html`
- **Legenda:**
  - $E$ - módulo de elasticidade do material da viga;
  - $I$ - inércia da seção transversal da viga (em torno no eixo que sai da tela);
  - $L$ - comprimento total da viga;
  - $w$ - carga distribuída uniforme;
  - $x$ - posição em uma parte qualquer de um tramo da viga;

#### Flechas
$$\delta_A = \dfrac{w x^{2} \left(- L^{2} + 2 L x - x^{2}\right)}{24 E I}$$

#### Momentos fletores
$$M_A = \dfrac{w \left(- L^{2} + 6 L x - 6 x^{2}\right)}{12}$$

#### Esforços cortantes
$$V_A = \dfrac{w \left(L - 2 x\right)}{2}$$

#### Reações de apoio
$$R_1 = \dfrac{L w}{2}$$

$$M_1 = \dfrac{L^{2} w}{12}$$

$$R_2 = \dfrac{L w}{2}$$

$$M_2 = - \dfrac{L^{2} w}{12}$$

#### Equações em Python
```python
# Flechas
deltaA = w*x**2*(-L**2 + 2*L*x - x**2)/(24*E*I)
# Momentos fletores
MA = w*(-L**2 + 6*L*x - 6*x**2)/12
# Esforços cortantes
VA = w*(L - 2*x)/2
# Reações de apoio
R1 = L*w/2
M1 = L**2*w/12
R2 = L*w/2
M2 = -L**2*w/12
```

---

### BE2-td
- **Descrição:** Viga biengastada com carga triangular distribuída em todo o vão com máximo na direita
- **Página offline:** `00. Site Offline/BE2-td.html`
- **Legenda:**
  - $E$ - módulo de elasticidade do material da viga;
  - $I$ - inércia da seção transversal da viga (em torno no eixo que sai da tela);
  - $L$ - comprimento total da viga;
  - $w$ - carga distribuída uniforme;
  - $x$ - posição em uma parte qualquer de um tramo da viga;

#### Flechas
$$\delta_A = \dfrac{w x^{2} \left(- 2 L^{3} + 3 L^{2} x - x^{3}\right)}{120 E I L}$$

#### Momentos fletores
$$M_A = \dfrac{w \left(- 2 L^{3} + 9 L^{2} x - 10 x^{3}\right)}{60 L}$$

#### Esforços cortantes
$$V_A = \dfrac{w \left(3 L^{2} - 10 x^{2}\right)}{20 L}$$

#### Reações de apoio
$$R_1 = \dfrac{3 L w}{20}$$

$$M_1 = \dfrac{L^{2} w}{30}$$

$$R_2 = \dfrac{7 L w}{20}$$

$$M_2 = - \dfrac{L^{2} w}{20}$$

#### Equações em Python
```python
# Flechas
deltaA = w*x**2*(-2*L**3 + 3*L**2*x - x**3)/(120*E*I*L)
# Momentos fletores
MA = w*(-2*L**3 + 9*L**2*x - 10*x**3)/(60*L)
# Esforços cortantes
VA = w*(3*L**2 - 10*x**2)/(20*L)
# Reações de apoio
R1 = 3*L*w/20
M1 = L**2*w/30
R2 = 7*L*w/20
M2 = -L**2*w/20
```

---

### BE3-te
- **Descrição:** Viga biengastada com carga triangular distribuída em todo o vão com máximo na esquerda
- **Página offline:** `00. Site Offline/BE3-te.html`
- **Legenda:**
  - $E$ - módulo de elasticidade do material da viga;
  - $I$ - inércia da seção transversal da viga (em torno no eixo que sai da tela);
  - $L$ - comprimento total da viga;
  - $w$ - carga distribuída uniforme;
  - $x$ - posição em uma parte qualquer de um tramo da viga;

#### Flechas
$$\delta_A = \dfrac{w x^{2} \left(- 3 L^{3} + 7 L^{2} x - 5 L x^{2} + x^{3}\right)}{120 E I L}$$

#### Momentos fletores
$$M_A = \dfrac{w \left(- 3 L^{3} + 21 L^{2} x - 30 L x^{2} + 10 x^{3}\right)}{60 L}$$

#### Esforços cortantes
$$V_A = \dfrac{7 L w}{20} - w x + \dfrac{w x^{2}}{2 L}$$

#### Reações de apoio
$$R_1 = \dfrac{7 L w}{20}$$

$$M_1 = \dfrac{L^{2} w}{20}$$

$$R_2 = \dfrac{3 L w}{20}$$

$$M_2 = - \dfrac{L^{2} w}{30}$$

#### Equações em Python
```python
# Flechas
deltaA = w*x**2*(-3*L**3 + 7*L**2*x - 5*L*x**2 + x**3)/(120*E*I*L)
# Momentos fletores
MA = w*(-3*L**3 + 21*L**2*x - 30*L*x**2 + 10*x**3)/(60*L)
# Esforços cortantes
VA = 7*L*w/20 - w*x + w*x**2/(2*L)
# Reações de apoio
R1 = 7*L*w/20
M1 = L**2*w/20
R2 = 3*L*w/20
M2 = -L**2*w/30
```

---

### BE4-tm
- **Descrição:** Viga biengastada com carga triangular distribuída em todo o vão com máximo meio do vão
- **Página offline:** `00. Site Offline/BE4-tm.html`
- **Legenda:**
  - $E$ - módulo de elasticidade do material da viga;
  - $I$ - inércia da seção transversal da viga (em torno no eixo que sai da tela);
  - $L$ - comprimento total da viga;
  - $w$ - carga distribuída uniforme;
  - $x$ - posição em uma parte qualquer de um tramo da viga;

#### Flechas
$$\delta_A = \dfrac{w x^{2} \left(- 25 L^{3} + 40 L^{2} x - 16 x^{3}\right)}{960 E I L}$$

$$\delta_B = \dfrac{w \left(L \left(- L^{4} + 10 L^{3} x - 65 L^{2} x^{2} + 120 L x^{3} - 80 x^{4}\right) + 16 x^{5}\right)}{960 E I L}$$

#### Momentos fletores
$$M_A = \dfrac{w \left(- 5 L^{3} + 24 L^{2} x - 32 x^{3}\right)}{96 L}$$

$$M_B = \dfrac{w \left(L \left(- 13 L^{2} + 72 L x - 96 x^{2}\right) + 32 x^{3}\right)}{96 L}$$

#### Esforços cortantes
$$V_A = \dfrac{L w}{4} - \dfrac{w x^{2}}{L}$$

$$V_B = \dfrac{w \left(L \left(3 L - 8 x\right) + 4 x^{2}\right)}{4 L}$$

#### Reações de apoio
$$R_1 = \dfrac{L w}{4}$$

$$M_1 = \dfrac{5 L^{2} w}{96}$$

$$R_2 = \dfrac{L w}{4}$$

$$M_2 = - \dfrac{5 L^{2} w}{96}$$

#### Equações em Python
```python
# Flechas
deltaA = w*x**2*(-25*L**3 + 40*L**2*x - 16*x**3)/(960*E*I*L)
deltaB = w*(L*(-L**4 + 10*L**3*x - 65*L**2*x**2 + 120*L*x**3 - 80*x**4) + 16*x**5)/(960*E*I*L)
# Momentos fletores
MA = w*(-5*L**3 + 24*L**2*x - 32*x**3)/(96*L)
MB = w*(L*(-13*L**2 + 72*L*x - 96*x**2) + 32*x**3)/(96*L)
# Esforços cortantes
VA = L*w/4 - w*x**2/L
VB = w*(L*(3*L - 8*x) + 4*x**2)/(4*L)
# Reações de apoio
R1 = L*w/4
M1 = 5*L**2*w/96
R2 = L*w/4
M2 = -5*L**2*w/96
```

---

### BE5-pe
- **Descrição:** Viga biengastada com carga uniforme distribuída na parte esquerda do vão
- **Página offline:** `00. Site Offline/BE5-pe.html`
- **Legenda:**
  - $E$ - módulo de elasticidade do material da viga;
  - $I$ - inércia da seção transversal da viga (em torno no eixo que sai da tela);
  - $L$ - comprimento total da viga;
  - $a$ - comprimento do tramo A;
  - $w$ - carga distribuída uniforme;
  - $x$ - posição em uma parte qualquer de um tramo da viga;

#### Flechas
$$\delta_A = \dfrac{w x^{2} \left(- 6 L^{3} a^{2} + 4 L^{3} a x - L^{3} x^{2} + 8 L^{2} a^{3} - 3 L a^{4} - 4 L a^{3} x + 2 a^{4} x\right)}{24 E I L^{3}}$$

$$\delta_B = \dfrac{a^{3} w \left(L^{3} \left(a - 4 x\right) + 8 L^{2} x^{2} - L x^{2} \left(3 a + 4 x\right) + 2 a x^{3}\right)}{24 E I L^{3}}$$

#### Momentos fletores
$$M_A = - \dfrac{a^{2} w}{2} + a w x - \dfrac{w x^{2}}{2} + \dfrac{2 a^{3} w}{3 L} - \dfrac{a^{4} w}{4 L^{2}} - \dfrac{a^{3} w x}{L^{2}} + \dfrac{a^{4} w x}{2 L^{3}}$$

$$M_B = \dfrac{a^{3} w \left(8 L^{2} - 3 L \left(a + 4 x\right) + 6 a x\right)}{12 L^{3}}$$

#### Esforços cortantes
$$V_A = a w - w x - \dfrac{a^{3} w}{L^{2}} + \dfrac{a^{4} w}{2 L^{3}}$$

$$V_B = \dfrac{a^{3} w \left(- 2 L + a\right)}{2 L^{3}}$$

#### Reações de apoio
$$R_1 = a w - \dfrac{a^{3} w}{L^{2}} + \dfrac{a^{4} w}{2 L^{3}}$$

$$M_1 = \dfrac{a^{2} w \left(6 L^{2} - 8 L a + 3 a^{2}\right)}{12 L^{2}}$$

$$R_2 = \dfrac{a^{3} w \left(2 L - a\right)}{2 L^{3}}$$

$$M_2 = \dfrac{a^{3} w \left(- 4 L + 3 a\right)}{12 L^{2}}$$

#### Equações em Python
```python
# Flechas
deltaA = w*x**2*(-6*L**3*a**2 + 4*L**3*a*x - L**3*x**2 + 8*L**2*a**3 - 3*L*a**4 - 4*L*a**3*x + 2*a**4*x)/(24*E*I*L**3)
deltaB = a**3*w*(L**3*(a - 4*x) + 8*L**2*x**2 - L*x**2*(3*a + 4*x) + 2*a*x**3)/(24*E*I*L**3)
# Momentos fletores
MA = -a**2*w/2 + a*w*x - w*x**2/2 + 2*a**3*w/(3*L) - a**4*w/(4*L**2) - a**3*w*x/L**2 + a**4*w*x/(2*L**3)
MB = a**3*w*(8*L**2 - 3*L*(a + 4*x) + 6*a*x)/(12*L**3)
# Esforços cortantes
VA = a*w - w*x - a**3*w/L**2 + a**4*w/(2*L**3)
VB = a**3*w*(-2*L + a)/(2*L**3)
# Reações de apoio
R1 = a*w - a**3*w/L**2 + a**4*w/(2*L**3)
M1 = a**2*w*(6*L**2 - 8*L*a + 3*a**2)/(12*L**2)
R2 = a**3*w*(2*L - a)/(2*L**3)
M2 = a**3*w*(-4*L + 3*a)/(12*L**2)
```

---

### BE6-pv
- **Descrição:** Viga biengastada com carga uniforme distribuída em parte do vão
- **Página offline:** `00. Site Offline/BE6-pv.html`
- **Legenda:**
  - $E$ - módulo de elasticidade do material da viga;
  - $I$ - inércia da seção transversal da viga (em torno no eixo que sai da tela);
  - $L$ - comprimento total da viga;
  - $a$ - comprimento do tramo A;
  - $b$ - comprimento do tramo B;
  - $w$ - carga distribuída uniforme;
  - $x$ - posição em uma parte qualquer de um tramo da viga;

#### Flechas
$$\delta_A = \dfrac{b w x^{2} \left(- 12 L^{3} a - 6 L^{3} b + 4 L^{3} x + 24 L^{2} a^{2} + 24 L^{2} a b + 8 L^{2} b^{2} - 12 L a^{3} - 18 L a^{2} b - 12 L a^{2} x - 12 L a b^{2} - 12 L a b x - 3 L b^{3} - 4 L b^{2} x + 8 a^{3} x + 12 a^{2} b x + 8 a b^{2} x + 2 b^{3} x\right)}{24 E I L^{3}}$$

$$\delta_B = \dfrac{w \left(L^{3} \left(- a^{4} + 4 a^{3} x - 6 a^{2} x^{2} - 12 a b x^{2} + 4 a x^{3} - 6 b^{2} x^{2} + 4 b x^{3} - x^{4}\right) + 8 L^{2} b x^{2} \left(3 a^{2} + 3 a b + b^{2}\right) - L b x^{2} \left(12 a^{3} + 18 a^{2} b + 12 a^{2} x + 12 a b^{2} + 12 a b x + 3 b^{3} + 4 b^{2} x\right) + 2 b x^{3} \left(4 a^{3} + 6 a^{2} b + 4 a b^{2} + b^{3}\right)\right)}{24 E I L^{3}}$$

$$\delta_C = \dfrac{b w \left(L^{3} \left(4 a^{3} + 6 a^{2} b - 12 a^{2} x + 4 a b^{2} - 12 a b x + b^{3} - 4 b^{2} x\right) + 8 L^{2} x^{2} \left(3 a^{2} + 3 a b + b^{2}\right) - L x^{2} \left(12 a^{3} + 18 a^{2} b + 12 a^{2} x + 12 a b^{2} + 12 a b x + 3 b^{3} + 4 b^{2} x\right) + 2 x^{3} \left(4 a^{3} + 6 a^{2} b + 4 a b^{2} + b^{3}\right)\right)}{24 E I L^{3}}$$

#### Momentos fletores
$$M_A = \dfrac{b w \left(- 12 L^{3} a - 6 L^{3} b + 12 L^{3} x + 24 L^{2} a^{2} + 24 L^{2} a b + 8 L^{2} b^{2} - 12 L a^{3} - 18 L a^{2} b - 36 L a^{2} x - 12 L a b^{2} - 36 L a b x - 3 L b^{3} - 12 L b^{2} x + 24 a^{3} x + 36 a^{2} b x + 24 a b^{2} x + 6 b^{3} x\right)}{12 L^{3}}$$

$$M_B = \dfrac{w \left(6 L^{3} \left(- a^{2} - 2 a b + 2 a x - b^{2} + 2 b x - x^{2}\right) + 8 L^{2} b \left(3 a^{2} + 3 a b + b^{2}\right) - 3 L b \left(4 a^{3} + 6 a^{2} b + 12 a^{2} x + 4 a b^{2} + 12 a b x + b^{3} + 4 b^{2} x\right) + 6 b x \left(4 a^{3} + 6 a^{2} b + 4 a b^{2} + b^{3}\right)\right)}{12 L^{3}}$$

$$M_C = \dfrac{b w \left(8 L^{2} \left(3 a^{2} + 3 a b + b^{2}\right) - 3 L \left(4 a^{3} + 6 a^{2} b + 12 a^{2} x + 4 a b^{2} + 12 a b x + b^{3} + 4 b^{2} x\right) + 6 x \left(4 a^{3} + 6 a^{2} b + 4 a b^{2} + b^{3}\right)\right)}{12 L^{3}}$$

#### Esforços cortantes
$$V_A = \dfrac{b w \left(2 L^{3} - 6 L a^{2} - 6 L a b - 2 L b^{2} + 4 a^{3} + 6 a^{2} b + 4 a b^{2} + b^{3}\right)}{2 L^{3}}$$

$$V_B = \dfrac{w \left(2 L^{3} \left(a + b - x\right) - 2 L b \left(3 a^{2} + 3 a b + b^{2}\right) + b \left(4 a^{3} + 6 a^{2} b + 4 a b^{2} + b^{3}\right)\right)}{2 L^{3}}$$

$$V_C = \dfrac{b w \left(- 2 L \left(3 a^{2} + 3 a b + b^{2}\right) + 4 a^{3} + 6 a^{2} b + 4 a b^{2} + b^{3}\right)}{2 L^{3}}$$

#### Reações de apoio
$$R_1 = \dfrac{b w \left(2 L^{3} - 6 L a^{2} - 6 L a b - 2 L b^{2} + 4 a^{3} + 6 a^{2} b + 4 a b^{2} + b^{3}\right)}{2 L^{3}}$$

$$M_1 = \dfrac{b w \left(12 L^{2} a + 6 L^{2} b - 24 L a^{2} - 24 L a b - 8 L b^{2} + 12 a^{3} + 18 a^{2} b + 12 a b^{2} + 3 b^{3}\right)}{12 L^{2}}$$

$$R_2 = \dfrac{b w \left(6 L a^{2} + 6 L a b + 2 L b^{2} - 4 a^{3} - 6 a^{2} b - 4 a b^{2} - b^{3}\right)}{2 L^{3}}$$

$$M_2 = \dfrac{b w \left(- 12 L a^{2} - 12 L a b - 4 L b^{2} + 12 a^{3} + 18 a^{2} b + 12 a b^{2} + 3 b^{3}\right)}{12 L^{2}}$$

#### Equações em Python
```python
# Flechas
deltaA = b*w*x**2*(-12*L**3*a - 6*L**3*b + 4*L**3*x + 24*L**2*a**2 + 24*L**2*a*b + 8*L**2*b**2 - 12*L*a**3 - 18*L*a**2*b - 12*L*a**2*x - 12*L*a*b**2 - 12*L*a*b*x - 3*L*b**3 - 4*L*b**2*x + 8*a**3*x + 12*a**2*b*x + 8*a*b**2*x + 2*b**3*x)/(24*E*I*L**3)
deltaB = w*(L**3*(-a**4 + 4*a**3*x - 6*a**2*x**2 - 12*a*b*x**2 + 4*a*x**3 - 6*b**2*x**2 + 4*b*x**3 - x**4) + 8*L**2*b*x**2*(3*a**2 + 3*a*b + b**2) - L*b*x**2*(12*a**3 + 18*a**2*b + 12*a**2*x + 12*a*b**2 + 12*a*b*x + 3*b**3 + 4*b**2*x) + 2*b*x**3*(4*a**3 + 6*a**2*b + 4*a*b**2 + b**3))/(24*E*I*L**3)
deltaC = b*w*(L**3*(4*a**3 + 6*a**2*b - 12*a**2*x + 4*a*b**2 - 12*a*b*x + b**3 - 4*b**2*x) + 8*L**2*x**2*(3*a**2 + 3*a*b + b**2) - L*x**2*(12*a**3 + 18*a**2*b + 12*a**2*x + 12*a*b**2 + 12*a*b*x + 3*b**3 + 4*b**2*x) + 2*x**3*(4*a**3 + 6*a**2*b + 4*a*b**2 + b**3))/(24*E*I*L**3)
# Momentos fletores
MA = b*w*(-12*L**3*a - 6*L**3*b + 12*L**3*x + 24*L**2*a**2 + 24*L**2*a*b + 8*L**2*b**2 - 12*L*a**3 - 18*L*a**2*b - 36*L*a**2*x - 12*L*a*b**2 - 36*L*a*b*x - 3*L*b**3 - 12*L*b**2*x + 24*a**3*x + 36*a**2*b*x + 24*a*b**2*x + 6*b**3*x)/(12*L**3)
MB = w*(6*L**3*(-a**2 - 2*a*b + 2*a*x - b**2 + 2*b*x - x**2) + 8*L**2*b*(3*a**2 + 3*a*b + b**2) - 3*L*b*(4*a**3 + 6*a**2*b + 12*a**2*x + 4*a*b**2 + 12*a*b*x + b**3 + 4*b**2*x) + 6*b*x*(4*a**3 + 6*a**2*b + 4*a*b**2 + b**3))/(12*L**3)
MC = b*w*(8*L**2*(3*a**2 + 3*a*b + b**2) - 3*L*(4*a**3 + 6*a**2*b + 12*a**2*x + 4*a*b**2 + 12*a*b*x + b**3 + 4*b**2*x) + 6*x*(4*a**3 + 6*a**2*b + 4*a*b**2 + b**3))/(12*L**3)
# Esforços cortantes
VA = b*w*(2*L**3 - 6*L*a**2 - 6*L*a*b - 2*L*b**2 + 4*a**3 + 6*a**2*b + 4*a*b**2 + b**3)/(2*L**3)
VB = w*(2*L**3*(a + b - x) - 2*L*b*(3*a**2 + 3*a*b + b**2) + b*(4*a**3 + 6*a**2*b + 4*a*b**2 + b**3))/(2*L**3)
VC = b*w*(-2*L*(3*a**2 + 3*a*b + b**2) + 4*a**3 + 6*a**2*b + 4*a*b**2 + b**3)/(2*L**3)
# Reações de apoio
R1 = b*w*(2*L**3 - 6*L*a**2 - 6*L*a*b - 2*L*b**2 + 4*a**3 + 6*a**2*b + 4*a*b**2 + b**3)/(2*L**3)
M1 = b*w*(12*L**2*a + 6*L**2*b - 24*L*a**2 - 24*L*a*b - 8*L*b**2 + 12*a**3 + 18*a**2*b + 12*a*b**2 + 3*b**3)/(12*L**2)
R2 = b*w*(6*L*a**2 + 6*L*a*b + 2*L*b**2 - 4*a**3 - 6*a**2*b - 4*a*b**2 - b**3)/(2*L**3)
M2 = b*w*(-12*L*a**2 - 12*L*a*b - 4*L*b**2 + 12*a**3 + 18*a**2*b + 12*a*b**2 + 3*b**3)/(12*L**2)
```

---

### BE7-ev
- **Descrição:** Viga biengastada com carga uniforme distribuída nos extremos do vão
- **Página offline:** `00. Site Offline/BE7-ev.html`
- **Legenda:**
  - $E$ - módulo de elasticidade do material da viga;
  - $I$ - inércia da seção transversal da viga (em torno no eixo que sai da tela);
  - $L$ - comprimento total da viga;
  - $a$ - comprimento do tramo A;
  - $b$ - comprimento do tramo B;
  - $w$ - carga distribuída uniforme;
  - $x$ - posição em uma parte qualquer de um tramo da viga;

#### Flechas
$$\delta_A = \dfrac{w x^{2} \left(- 6 L^{3} a^{2} + 4 L^{3} a x - L^{3} x^{2} + 8 L^{2} a^{3} - 4 L^{2} b^{3} - 3 L a^{4} - 4 L a^{3} x + 3 L b^{4} + 4 L b^{3} x + 2 a^{4} x - 2 b^{4} x\right)}{24 E I L^{3}}$$

$$\delta_B = \dfrac{w \left(L^{3} a^{3} \left(a - 4 x\right) + 4 L^{2} x^{2} \left(2 a^{3} - b^{3}\right) + L x^{2} \left(- 3 a^{4} - 4 a^{3} x + 3 b^{4} + 4 b^{3} x\right) + 2 x^{3} \left(a^{4} - b^{4}\right)\right)}{24 E I L^{3}}$$

$$\delta_C = \dfrac{w \left(L^{3} \left(- L^{4} + 4 L^{3} b + 4 L^{3} x - 6 L^{2} b^{2} - 12 L^{2} b x - 6 L^{2} x^{2} + 4 L b^{3} + 12 L b^{2} x + 12 L b x^{2} + 4 L x^{3} + a^{4} - 4 a^{3} x - b^{4} - 4 b^{3} x - 6 b^{2} x^{2} - 4 b x^{3} - x^{4}\right) + 4 L^{2} x^{2} \left(2 a^{3} - b^{3}\right) + L x^{2} \left(- 3 a^{4} - 4 a^{3} x + 3 b^{4} + 4 b^{3} x\right) + 2 x^{3} \left(a^{4} - b^{4}\right)\right)}{24 E I L^{3}}$$

#### Momentos fletores
$$M_A = \dfrac{w \left(- 6 L^{3} a^{2} + 12 L^{3} a x - 6 L^{3} x^{2} + 8 L^{2} a^{3} - 4 L^{2} b^{3} - 3 L a^{4} - 12 L a^{3} x + 3 L b^{4} + 12 L b^{3} x + 6 a^{4} x - 6 b^{4} x\right)}{12 L^{3}}$$

$$M_B = \dfrac{w \left(4 L^{2} \left(2 a^{3} - b^{3}\right) + 3 L \left(- a^{4} - 4 a^{3} x + b^{4} + 4 b^{3} x\right) + 6 x \left(a^{4} - b^{4}\right)\right)}{12 L^{3}}$$

$$M_C = \dfrac{w \left(6 L^{3} \left(- L^{2} + 2 L b + 2 L x - b^{2} - 2 b x - x^{2}\right) + 4 L^{2} \left(2 a^{3} - b^{3}\right) + 3 L \left(- a^{4} - 4 a^{3} x + b^{4} + 4 b^{3} x\right) + 6 x \left(a^{4} - b^{4}\right)\right)}{12 L^{3}}$$

#### Esforços cortantes
$$V_A = \dfrac{w \left(2 L^{3} a - 2 L^{3} x - 2 L a^{3} + 2 L b^{3} + a^{4} - b^{4}\right)}{2 L^{3}}$$

$$V_B = \dfrac{w \left(2 L \left(- a^{3} + b^{3}\right) + a^{4} - b^{4}\right)}{2 L^{3}}$$

$$V_C = \dfrac{w \left(2 L^{3} \left(L - b - x\right) + 2 L \left(- a^{3} + b^{3}\right) + a^{4} - b^{4}\right)}{2 L^{3}}$$

#### Reações de apoio
$$R_1 = \dfrac{w \left(2 L^{3} a - 2 L a^{3} + 2 L b^{3} + a^{4} - b^{4}\right)}{2 L^{3}}$$

$$M_1 = \dfrac{w \left(6 L^{2} a^{2} - 8 L a^{3} + 4 L b^{3} + 3 a^{4} - 3 b^{4}\right)}{12 L^{2}}$$

$$R_2 = \dfrac{w \left(2 L^{3} b + 2 L a^{3} - 2 L b^{3} - a^{4} + b^{4}\right)}{2 L^{3}}$$

$$M_2 = \dfrac{w \left(- 6 L^{2} b^{2} - 4 L a^{3} + 8 L b^{3} + 3 a^{4} - 3 b^{4}\right)}{12 L^{2}}$$

#### Equações em Python
```python
# Flechas
deltaA = w*x**2*(-6*L**3*a**2 + 4*L**3*a*x - L**3*x**2 + 8*L**2*a**3 - 4*L**2*b**3 - 3*L*a**4 - 4*L*a**3*x + 3*L*b**4 + 4*L*b**3*x + 2*a**4*x - 2*b**4*x)/(24*E*I*L**3)
deltaB = w*(L**3*a**3*(a - 4*x) + 4*L**2*x**2*(2*a**3 - b**3) + L*x**2*(-3*a**4 - 4*a**3*x + 3*b**4 + 4*b**3*x) + 2*x**3*(a**4 - b**4))/(24*E*I*L**3)
deltaC = w*(L**3*(-L**4 + 4*L**3*b + 4*L**3*x - 6*L**2*b**2 - 12*L**2*b*x - 6*L**2*x**2 + 4*L*b**3 + 12*L*b**2*x + 12*L*b*x**2 + 4*L*x**3 + a**4 - 4*a**3*x - b**4 - 4*b**3*x - 6*b**2*x**2 - 4*b*x**3 - x**4) + 4*L**2*x**2*(2*a**3 - b**3) + L*x**2*(-3*a**4 - 4*a**3*x + 3*b**4 + 4*b**3*x) + 2*x**3*(a**4 - b**4))/(24*E*I*L**3)
# Momentos fletores
MA = w*(-6*L**3*a**2 + 12*L**3*a*x - 6*L**3*x**2 + 8*L**2*a**3 - 4*L**2*b**3 - 3*L*a**4 - 12*L*a**3*x + 3*L*b**4 + 12*L*b**3*x + 6*a**4*x - 6*b**4*x)/(12*L**3)
MB = w*(4*L**2*(2*a**3 - b**3) + 3*L*(-a**4 - 4*a**3*x + b**4 + 4*b**3*x) + 6*x*(a**4 - b**4))/(12*L**3)
MC = w*(6*L**3*(-L**2 + 2*L*b + 2*L*x - b**2 - 2*b*x - x**2) + 4*L**2*(2*a**3 - b**3) + 3*L*(-a**4 - 4*a**3*x + b**4 + 4*b**3*x) + 6*x*(a**4 - b**4))/(12*L**3)
# Esforços cortantes
VA = w*(2*L**3*a - 2*L**3*x - 2*L*a**3 + 2*L*b**3 + a**4 - b**4)/(2*L**3)
VB = w*(2*L*(-a**3 + b**3) + a**4 - b**4)/(2*L**3)
VC = w*(2*L**3*(L - b - x) + 2*L*(-a**3 + b**3) + a**4 - b**4)/(2*L**3)
# Reações de apoio
R1 = w*(2*L**3*a - 2*L*a**3 + 2*L*b**3 + a**4 - b**4)/(2*L**3)
M1 = w*(6*L**2*a**2 - 8*L*a**3 + 4*L*b**3 + 3*a**4 - 3*b**4)/(12*L**2)
R2 = w*(2*L**3*b + 2*L*a**3 - 2*L*b**3 - a**4 + b**4)/(2*L**3)
M2 = w*(-6*L**2*b**2 - 4*L*a**3 + 8*L*b**3 + 3*a**4 - 3*b**4)/(12*L**2)
```

---

### BE8-fa
- **Descrição:** Viga biengastada com carga concentrada no vão
- **Página offline:** `00. Site Offline/BE8-fa.html`
- **Legenda:**
  - $E$ - módulo de elasticidade do material da viga;
  - $F$ - carga concentrada;
  - $I$ - inércia da seção transversal da viga (em torno no eixo que sai da tela);
  - $L$ - comprimento total da viga;
  - $a$ - comprimento do tramo A;
  - $x$ - posição em uma parte qualquer de um tramo da viga;

#### Flechas
$$\delta_A = \dfrac{F x^{2} \left(- 3 L^{3} a + L^{3} x + 6 L^{2} a^{2} - 3 L a^{3} - 3 L a^{2} x + 2 a^{3} x\right)}{6 E I L^{3}}$$

$$\delta_B = \dfrac{F a^{2} \left(L^{3} \left(a - 3 x\right) + 6 L^{2} x^{2} - 3 L x^{2} \left(a + x\right) + 2 a x^{3}\right)}{6 E I L^{3}}$$

#### Momentos fletores
$$M_A = \dfrac{F \left(- L^{3} a + L^{3} x + 2 L^{2} a^{2} - L a^{3} - 3 L a^{2} x + 2 a^{3} x\right)}{L^{3}}$$

$$M_B = \dfrac{F a^{2} \left(2 L^{2} - L \left(a + 3 x\right) + 2 a x\right)}{L^{3}}$$

#### Esforços cortantes
$$V_A = \dfrac{F \left(L^{3} - 3 L a^{2} + 2 a^{3}\right)}{L^{3}}$$

$$V_B = \dfrac{F a^{2} \left(- 3 L + 2 a\right)}{L^{3}}$$

#### Reações de apoio
$$R_1 = \dfrac{F \left(L^{3} - 3 L a^{2} + 2 a^{3}\right)}{L^{3}}$$

$$M_1 = \dfrac{F a \left(L^{2} - 2 L a + a^{2}\right)}{L^{2}}$$

$$R_2 = \dfrac{F a^{2} \left(3 L - 2 a\right)}{L^{3}}$$

$$M_2 = \dfrac{F a^{2} \left(- L + a\right)}{L^{2}}$$

#### Equações em Python
```python
# Flechas
deltaA = F*x**2*(-3*L**3*a + L**3*x + 6*L**2*a**2 - 3*L*a**3 - 3*L*a**2*x + 2*a**3*x)/(6*E*I*L**3)
deltaB = F*a**2*(L**3*(a - 3*x) + 6*L**2*x**2 - 3*L*x**2*(a + x) + 2*a*x**3)/(6*E*I*L**3)
# Momentos fletores
MA = F*(-L**3*a + L**3*x + 2*L**2*a**2 - L*a**3 - 3*L*a**2*x + 2*a**3*x)/L**3
MB = F*a**2*(2*L**2 - L*(a + 3*x) + 2*a*x)/L**3
# Esforços cortantes
VA = F*(L**3 - 3*L*a**2 + 2*a**3)/L**3
VB = F*a**2*(-3*L + 2*a)/L**3
# Reações de apoio
R1 = F*(L**3 - 3*L*a**2 + 2*a**3)/L**3
M1 = F*a*(L**2 - 2*L*a + a**2)/L**2
R2 = F*a**2*(3*L - 2*a)/L**3
M2 = F*a**2*(-L + a)/L**2
```

---

### BE9-ff
- **Descrição:** Viga biengastada com duas cargas concentradas no vão assimétricas
- **Página offline:** `00. Site Offline/BE9-ff.html`
- **Legenda:**
  - $E$ - módulo de elasticidade do material da viga;
  - $F$ - carga concentrada;
  - $I$ - inércia da seção transversal da viga (em torno no eixo que sai da tela);
  - $L$ - comprimento total da viga;
  - $a$ - comprimento do tramo A;
  - $b$ - comprimento do tramo B;
  - $x$ - posição em uma parte qualquer de um tramo da viga;

#### Flechas
$$\delta_A = \dfrac{F x^{2} \left(- 3 L^{3} a + L^{3} x + 6 L^{2} a^{2} - 3 L^{2} b^{2} - 3 L a^{3} - 3 L a^{2} x + 3 L b^{3} + 3 L b^{2} x + 2 a^{3} x - 2 b^{3} x\right)}{6 E I L^{3}}$$

$$\delta_B = \dfrac{F \left(L^{3} a^{2} \left(a - 3 x\right) + 3 L^{2} x^{2} \left(2 a^{2} - b^{2}\right) + 3 L x^{2} \left(- a^{3} - a^{2} x + b^{3} + b^{2} x\right) + 2 x^{3} \left(a^{3} - b^{3}\right)\right)}{6 E I L^{3}}$$

$$\delta_C = \dfrac{F \left(L^{3} \left(L^{3} - 3 L^{2} b - 3 L^{2} x + 3 L b^{2} + 6 L b x + 3 L x^{2} + a^{3} - 3 a^{2} x - b^{3} - 3 b^{2} x - 3 b x^{2} - x^{3}\right) + 3 L^{2} x^{2} \left(2 a^{2} - b^{2}\right) + 3 L x^{2} \left(- a^{3} - a^{2} x + b^{3} + b^{2} x\right) + 2 x^{3} \left(a^{3} - b^{3}\right)\right)}{6 E I L^{3}}$$

#### Momentos fletores
$$M_A = \dfrac{F \left(- L^{3} a + L^{3} x + 2 L^{2} a^{2} - L^{2} b^{2} - L a^{3} - 3 L a^{2} x + L b^{3} + 3 L b^{2} x + 2 a^{3} x - 2 b^{3} x\right)}{L^{3}}$$

$$M_B = \dfrac{F \left(L^{2} \left(2 a^{2} - b^{2}\right) + L \left(- a^{3} - 3 a^{2} x + b^{3} + 3 b^{2} x\right) + 2 x \left(a^{3} - b^{3}\right)\right)}{L^{3}}$$

$$M_C = \dfrac{F \left(L^{3} \left(L - b - x\right) + L^{2} \left(2 a^{2} - b^{2}\right) + L \left(- a^{3} - 3 a^{2} x + b^{3} + 3 b^{2} x\right) + 2 x \left(a^{3} - b^{3}\right)\right)}{L^{3}}$$

#### Esforços cortantes
$$V_A = \dfrac{F \left(L^{3} - 3 L a^{2} + 3 L b^{2} + 2 a^{3} - 2 b^{3}\right)}{L^{3}}$$

$$V_B = \dfrac{F \left(3 L \left(- a^{2} + b^{2}\right) + 2 a^{3} - 2 b^{3}\right)}{L^{3}}$$

$$V_C = \dfrac{F \left(- L^{3} + 3 L \left(- a^{2} + b^{2}\right) + 2 a^{3} - 2 b^{3}\right)}{L^{3}}$$

#### Reações de apoio
$$R_1 = \dfrac{F \left(L^{3} - 3 L a^{2} + 3 L b^{2} + 2 a^{3} - 2 b^{3}\right)}{L^{3}}$$

$$M_1 = \dfrac{F \left(L^{2} a - 2 L a^{2} + L b^{2} + a^{3} - b^{3}\right)}{L^{2}}$$

$$R_2 = \dfrac{F \left(L^{3} + 3 L a^{2} - 3 L b^{2} - 2 a^{3} + 2 b^{3}\right)}{L^{3}}$$

$$M_2 = \dfrac{F \left(- L^{2} b - L a^{2} + 2 L b^{2} + a^{3} - b^{3}\right)}{L^{2}}$$

#### Equações em Python
```python
# Flechas
deltaA = F*x**2*(-3*L**3*a + L**3*x + 6*L**2*a**2 - 3*L**2*b**2 - 3*L*a**3 - 3*L*a**2*x + 3*L*b**3 + 3*L*b**2*x + 2*a**3*x - 2*b**3*x)/(6*E*I*L**3)
deltaB = F*(L**3*a**2*(a - 3*x) + 3*L**2*x**2*(2*a**2 - b**2) + 3*L*x**2*(-a**3 - a**2*x + b**3 + b**2*x) + 2*x**3*(a**3 - b**3))/(6*E*I*L**3)
deltaC = F*(L**3*(L**3 - 3*L**2*b - 3*L**2*x + 3*L*b**2 + 6*L*b*x + 3*L*x**2 + a**3 - 3*a**2*x - b**3 - 3*b**2*x - 3*b*x**2 - x**3) + 3*L**2*x**2*(2*a**2 - b**2) + 3*L*x**2*(-a**3 - a**2*x + b**3 + b**2*x) + 2*x**3*(a**3 - b**3))/(6*E*I*L**3)
# Momentos fletores
MA = F*(-L**3*a + L**3*x + 2*L**2*a**2 - L**2*b**2 - L*a**3 - 3*L*a**2*x + L*b**3 + 3*L*b**2*x + 2*a**3*x - 2*b**3*x)/L**3
MB = F*(L**2*(2*a**2 - b**2) + L*(-a**3 - 3*a**2*x + b**3 + 3*b**2*x) + 2*x*(a**3 - b**3))/L**3
MC = F*(L**3*(L - b - x) + L**2*(2*a**2 - b**2) + L*(-a**3 - 3*a**2*x + b**3 + 3*b**2*x) + 2*x*(a**3 - b**3))/L**3
# Esforços cortantes
VA = F*(L**3 - 3*L*a**2 + 3*L*b**2 + 2*a**3 - 2*b**3)/L**3
VB = F*(3*L*(-a**2 + b**2) + 2*a**3 - 2*b**3)/L**3
VC = F*(-L**3 + 3*L*(-a**2 + b**2) + 2*a**3 - 2*b**3)/L**3
# Reações de apoio
R1 = F*(L**3 - 3*L*a**2 + 3*L*b**2 + 2*a**3 - 2*b**3)/L**3
M1 = F*(L**2*a - 2*L*a**2 + L*b**2 + a**3 - b**3)/L**2
R2 = F*(L**3 + 3*L*a**2 - 3*L*b**2 - 2*a**3 + 2*b**3)/L**3
M2 = F*(-L**2*b - L*a**2 + 2*L*b**2 + a**3 - b**3)/L**2
```

---

### BE10-m
- **Descrição:** Viga biengastada com momento concentrado no vão
- **Página offline:** `00. Site Offline/BE10-m.html`
- **Legenda:**
  - $E$ - módulo de elasticidade do material da viga;
  - $I$ - inércia da seção transversal da viga (em torno no eixo que sai da tela);
  - $L$ - comprimento total da viga;
  - $M$ - momento concentrado;
  - $a$ - comprimento do tramo A;
  - $x$ - posição em uma parte qualquer de um tramo da viga;

#### Flechas
$$\delta_A = \dfrac{M x^{2} \left(- L^{3} + 4 L^{2} a - 3 L a^{2} - 2 L a x + 2 a^{2} x\right)}{2 E I L^{3}}$$

$$\delta_B = \dfrac{M a \left(L^{3} \left(a - 2 x\right) + 4 L^{2} x^{2} - L x^{2} \left(3 a + 2 x\right) + 2 a x^{3}\right)}{2 E I L^{3}}$$

#### Momentos fletores
$$M_A = \dfrac{M \left(- L^{3} + 4 L^{2} a - 3 L a^{2} - 6 L a x + 6 a^{2} x\right)}{L^{3}}$$

$$M_B = \dfrac{M a \left(4 L^{2} - 3 L \left(a + 2 x\right) + 6 a x\right)}{L^{3}}$$

#### Esforços cortantes
$$V_A = \dfrac{6 M a \left(- L + a\right)}{L^{3}}$$

$$V_B = \dfrac{6 M a \left(- L + a\right)}{L^{3}}$$

#### Reações de apoio
$$R_1 = \dfrac{6 M a \left(- L + a\right)}{L^{3}}$$

$$M_1 = \dfrac{M \left(L^{2} - 4 L a + 3 a^{2}\right)}{L^{2}}$$

$$R_2 = \dfrac{6 M a \left(L - a\right)}{L^{3}}$$

$$M_2 = \dfrac{M a \left(- 2 L + 3 a\right)}{L^{2}}$$

#### Equações em Python
```python
# Flechas
deltaA = M*x**2*(-L**3 + 4*L**2*a - 3*L*a**2 - 2*L*a*x + 2*a**2*x)/(2*E*I*L**3)
deltaB = M*a*(L**3*(a - 2*x) + 4*L**2*x**2 - L*x**2*(3*a + 2*x) + 2*a*x**3)/(2*E*I*L**3)
# Momentos fletores
MA = M*(-L**3 + 4*L**2*a - 3*L*a**2 - 6*L*a*x + 6*a**2*x)/L**3
MB = M*a*(4*L**2 - 3*L*(a + 2*x) + 6*a*x)/L**3
# Esforços cortantes
VA = 6*M*a*(-L + a)/L**3
VB = 6*M*a*(-L + a)/L**3
# Reações de apoio
R1 = 6*M*a*(-L + a)/L**3
M1 = M*(L**2 - 4*L*a + 3*a**2)/L**2
R2 = 6*M*a*(L - a)/L**3
M2 = M*a*(-2*L + 3*a)/L**2
```

---

### BE11-mo
- **Descrição:** Viga biengastada com momentos concentrados no vão assímetricos
- **Página offline:** `00. Site Offline/BE11-mo.html`
- **Legenda:**
  - $E$ - módulo de elasticidade do material da viga;
  - $I$ - inércia da seção transversal da viga (em torno no eixo que sai da tela);
  - $L$ - comprimento total da viga;
  - $M$ - momento concentrado;
  - $a$ - comprimento do tramo A;
  - $b$ - comprimento do tramo B;
  - $x$ - posição em uma parte qualquer de um tramo da viga;

#### Flechas
$$\delta_A = \dfrac{M x^{2} \left(- L^{3} + 4 L^{2} a + 2 L^{2} b - 3 L a^{2} - 2 L a x - 3 L b^{2} - 2 L b x + 2 a^{2} x + 2 b^{2} x\right)}{2 E I L^{3}}$$

$$\delta_B = \dfrac{M \left(L^{3} a \left(a - 2 x\right) + 2 L^{2} x^{2} \left(2 a + b\right) - L x^{2} \left(3 a^{2} + 2 a x + 3 b^{2} + 2 b x\right) + 2 x^{3} \left(a^{2} + b^{2}\right)\right)}{2 E I L^{3}}$$

$$\delta_C = \dfrac{M \left(L^{3} \left(L^{2} - 2 L b - 2 L x + a^{2} - 2 a x + b^{2} + 2 b x + x^{2}\right) + 2 L^{2} x^{2} \left(2 a + b\right) - L x^{2} \left(3 a^{2} + 2 a x + 3 b^{2} + 2 b x\right) + 2 x^{3} \left(a^{2} + b^{2}\right)\right)}{2 E I L^{3}}$$

#### Momentos fletores
$$M_A = \dfrac{M \left(- L^{3} + 4 L^{2} a + 2 L^{2} b - 3 L a^{2} - 6 L a x - 3 L b^{2} - 6 L b x + 6 a^{2} x + 6 b^{2} x\right)}{L^{3}}$$

$$M_B = \dfrac{M \left(2 L^{2} \left(2 a + b\right) - 3 L \left(a^{2} + 2 a x + b^{2} + 2 b x\right) + 6 x \left(a^{2} + b^{2}\right)\right)}{L^{3}}$$

$$M_C = \dfrac{M \left(L^{3} + 2 L^{2} \left(2 a + b\right) - 3 L \left(a^{2} + 2 a x + b^{2} + 2 b x\right) + 6 x \left(a^{2} + b^{2}\right)\right)}{L^{3}}$$

#### Esforços cortantes
$$V_A = \dfrac{6 M \left(- L a - L b + a^{2} + b^{2}\right)}{L^{3}}$$

$$V_B = \dfrac{6 M \left(- L \left(a + b\right) + a^{2} + b^{2}\right)}{L^{3}}$$

$$V_C = \dfrac{6 M \left(- L \left(a + b\right) + a^{2} + b^{2}\right)}{L^{3}}$$

#### Reações de apoio
$$R_1 = \dfrac{6 M \left(- L a - L b + a^{2} + b^{2}\right)}{L^{3}}$$

$$M_1 = \dfrac{M \left(L^{2} - 4 L a - 2 L b + 3 a^{2} + 3 b^{2}\right)}{L^{2}}$$

$$R_2 = \dfrac{6 M \left(L a + L b - a^{2} - b^{2}\right)}{L^{3}}$$

$$M_2 = \dfrac{M \left(L^{2} - 2 L a - 4 L b + 3 a^{2} + 3 b^{2}\right)}{L^{2}}$$

#### Equações em Python
```python
# Flechas
deltaA = M*x**2*(-L**3 + 4*L**2*a + 2*L**2*b - 3*L*a**2 - 2*L*a*x - 3*L*b**2 - 2*L*b*x + 2*a**2*x + 2*b**2*x)/(2*E*I*L**3)
deltaB = M*(L**3*a*(a - 2*x) + 2*L**2*x**2*(2*a + b) - L*x**2*(3*a**2 + 2*a*x + 3*b**2 + 2*b*x) + 2*x**3*(a**2 + b**2))/(2*E*I*L**3)
deltaC = M*(L**3*(L**2 - 2*L*b - 2*L*x + a**2 - 2*a*x + b**2 + 2*b*x + x**2) + 2*L**2*x**2*(2*a + b) - L*x**2*(3*a**2 + 2*a*x + 3*b**2 + 2*b*x) + 2*x**3*(a**2 + b**2))/(2*E*I*L**3)
# Momentos fletores
MA = M*(-L**3 + 4*L**2*a + 2*L**2*b - 3*L*a**2 - 6*L*a*x - 3*L*b**2 - 6*L*b*x + 6*a**2*x + 6*b**2*x)/L**3
MB = M*(2*L**2*(2*a + b) - 3*L*(a**2 + 2*a*x + b**2 + 2*b*x) + 6*x*(a**2 + b**2))/L**3
MC = M*(L**3 + 2*L**2*(2*a + b) - 3*L*(a**2 + 2*a*x + b**2 + 2*b*x) + 6*x*(a**2 + b**2))/L**3
# Esforços cortantes
VA = 6*M*(-L*a - L*b + a**2 + b**2)/L**3
VB = 6*M*(-L*(a + b) + a**2 + b**2)/L**3
VC = 6*M*(-L*(a + b) + a**2 + b**2)/L**3
# Reações de apoio
R1 = 6*M*(-L*a - L*b + a**2 + b**2)/L**3
M1 = M*(L**2 - 4*L*a - 2*L*b + 3*a**2 + 3*b**2)/L**2
R2 = 6*M*(L*a + L*b - a**2 - b**2)/L**3
M2 = M*(L**2 - 2*L*a - 4*L*b + 3*a**2 + 3*b**2)/L**2
```

---

## APOIO-ENGASTE

### AE1-w
- **Descrição:** Viga apoio-engaste com carga uniformemente distribuída em todo o vão
- **Equivalente nos formulários da prova:** **[I]**, **[AN]**, **[BK]**
- **Página offline:** `00. Site Offline/AE1-w.html`
- **Legenda:**
  - $E$ - módulo de elasticidade do material da viga;
  - $I$ - inércia da seção transversal da viga (em torno no eixo que sai da tela);
  - $L$ - comprimento total da viga;
  - $w$ - carga distribuída uniforme;
  - $x$ - posição em uma parte qualquer de um tramo da viga;

#### Flechas
$$\delta_A = \dfrac{w x \left(- L^{3} + 3 L x^{2} - 2 x^{3}\right)}{48 E I}$$

#### Momentos fletores
$$M_A = \dfrac{w x \left(3 L - 4 x\right)}{8}$$

#### Esforços cortantes
$$V_A = \dfrac{w \left(3 L - 8 x\right)}{8}$$

#### Reações de apoio
$$R_1 = \dfrac{3 L w}{8}$$

$$R_2 = \dfrac{5 L w}{8}$$

$$M_2 = - \dfrac{L^{2} w}{8}$$

#### Equações em Python
```python
# Flechas
deltaA = w*x*(-L**3 + 3*L*x**2 - 2*x**3)/(48*E*I)
# Momentos fletores
MA = w*x*(3*L - 4*x)/8
# Esforços cortantes
VA = w*(3*L - 8*x)/8
# Reações de apoio
R1 = 3*L*w/8
R2 = 5*L*w/8
M2 = -L**2*w/8
```

---

### AE2-td
- **Descrição:** Viga apoio-engaste com carga triangular distribuída em todo o vão com máximo na direita
- **Página offline:** `00. Site Offline/AE2-td.html`
- **Legenda:**
  - $E$ - módulo de elasticidade do material da viga;
  - $I$ - inércia da seção transversal da viga (em torno no eixo que sai da tela);
  - $L$ - comprimento total da viga;
  - $w$ - carga distribuída uniforme;
  - $x$ - posição em uma parte qualquer de um tramo da viga;

#### Flechas
$$\delta_A = \dfrac{w x \left(- L^{4} + 2 L^{2} x^{2} - x^{4}\right)}{120 E I L}$$

#### Momentos fletores
$$M_A = \dfrac{L w x}{10} - \dfrac{w x^{3}}{6 L}$$

#### Esforços cortantes
$$V_A = \dfrac{w \left(L^{2} - 5 x^{2}\right)}{10 L}$$

#### Reações de apoio
$$R_1 = \dfrac{L w}{10}$$

$$R_2 = \dfrac{2 L w}{5}$$

$$M_2 = - \dfrac{L^{2} w}{15}$$

#### Equações em Python
```python
# Flechas
deltaA = w*x*(-L**4 + 2*L**2*x**2 - x**4)/(120*E*I*L)
# Momentos fletores
MA = L*w*x/10 - w*x**3/(6*L)
# Esforços cortantes
VA = w*(L**2 - 5*x**2)/(10*L)
# Reações de apoio
R1 = L*w/10
R2 = 2*L*w/5
M2 = -L**2*w/15
```

---

### AE3-te
- **Descrição:** Viga apoio-engaste com carga triangular distribuída em todo o vão com máximo na esquerda
- **Página offline:** `00. Site Offline/AE3-te.html`
- **Legenda:**
  - $E$ - módulo de elasticidade do material da viga;
  - $I$ - inércia da seção transversal da viga (em torno no eixo que sai da tela);
  - $L$ - comprimento total da viga;
  - $w$ - carga distribuída uniforme;
  - $x$ - posição em uma parte qualquer de um tramo da viga;

#### Flechas
$$\delta_A = \dfrac{w x \left(- 3 L^{4} + 11 L^{2} x^{2} - 10 L x^{3} + 2 x^{4}\right)}{240 E I L}$$

#### Momentos fletores
$$M_A = \dfrac{w x \left(33 L^{2} - 60 L x + 20 x^{2}\right)}{120 L}$$

#### Esforços cortantes
$$V_A = \dfrac{11 L w}{40} - w x + \dfrac{w x^{2}}{2 L}$$

#### Reações de apoio
$$R_1 = \dfrac{11 L w}{40}$$

$$R_2 = \dfrac{9 L w}{40}$$

$$M_2 = - \dfrac{7 L^{2} w}{120}$$

#### Equações em Python
```python
# Flechas
deltaA = w*x*(-3*L**4 + 11*L**2*x**2 - 10*L*x**3 + 2*x**4)/(240*E*I*L)
# Momentos fletores
MA = w*x*(33*L**2 - 60*L*x + 20*x**2)/(120*L)
# Esforços cortantes
VA = 11*L*w/40 - w*x + w*x**2/(2*L)
# Reações de apoio
R1 = 11*L*w/40
R2 = 9*L*w/40
M2 = -7*L**2*w/120
```

---

### AE4-tm
- **Descrição:** Viga apoio-engaste com carga triangular distribuída em todo o vão com máximo meio do vão
- **Página offline:** `00. Site Offline/AE4-tm.html`
- **Legenda:**
  - $E$ - módulo de elasticidade do material da viga;
  - $I$ - inércia da seção transversal da viga (em torno no eixo que sai da tela);
  - $L$ - comprimento total da viga;
  - $w$ - carga distribuída uniforme;
  - $x$ - posição em uma parte qualquer de um tramo da viga;

#### Flechas
$$\delta_A = \dfrac{w x \left(- 25 L^{4} + 55 L^{2} x^{2} - 32 x^{4}\right)}{1920 E I L}$$

$$\delta_B = \dfrac{w \left(L \left(- 2 L^{4} - 5 L^{3} x - 80 L^{2} x^{2} + 215 L x^{3} - 160 x^{4}\right) + 32 x^{5}\right)}{1920 E I L}$$

#### Momentos fletores
$$M_A = \dfrac{w x \left(33 L^{2} - 64 x^{2}\right)}{192 L}$$

$$M_B = \dfrac{w \left(L \left(- 16 L^{2} + 129 L x - 192 x^{2}\right) + 64 x^{3}\right)}{192 L}$$

#### Esforços cortantes
$$V_A = \dfrac{11 L w}{64} - \dfrac{w x^{2}}{L}$$

$$V_B = \dfrac{w \left(L \left(43 L - 128 x\right) + 64 x^{2}\right)}{64 L}$$

#### Reações de apoio
$$R_1 = \dfrac{11 L w}{64}$$

$$R_2 = \dfrac{21 L w}{64}$$

$$M_2 = - \dfrac{5 L^{2} w}{64}$$

#### Equações em Python
```python
# Flechas
deltaA = w*x*(-25*L**4 + 55*L**2*x**2 - 32*x**4)/(1920*E*I*L)
deltaB = w*(L*(-2*L**4 - 5*L**3*x - 80*L**2*x**2 + 215*L*x**3 - 160*x**4) + 32*x**5)/(1920*E*I*L)
# Momentos fletores
MA = w*x*(33*L**2 - 64*x**2)/(192*L)
MB = w*(L*(-16*L**2 + 129*L*x - 192*x**2) + 64*x**3)/(192*L)
# Esforços cortantes
VA = 11*L*w/64 - w*x**2/L
VB = w*(L*(43*L - 128*x) + 64*x**2)/(64*L)
# Reações de apoio
R1 = 11*L*w/64
R2 = 21*L*w/64
M2 = -5*L**2*w/64
```

---

### AE5-pe
- **Descrição:** Viga apoio-engaste com carga uniforme distribuída na parte esquerda do vão
- **Equivalente nos formulários da prova:** **[K]**
- **Página offline:** `00. Site Offline/AE5-pe.html`
- **Legenda:**
  - $E$ - módulo de elasticidade do material da viga;
  - $I$ - inércia da seção transversal da viga (em torno no eixo que sai da tela);
  - $L$ - comprimento total da viga;
  - $a$ - comprimento do tramo A;
  - $w$ - carga distribuída uniforme;
  - $x$ - posição em uma parte qualquer de um tramo da viga;

#### Flechas
$$\delta_A = \dfrac{w x \left(- 6 L^{4} a^{2} + 8 L^{3} a^{3} + 8 L^{3} a x^{2} - 2 L^{3} x^{3} - 3 L^{2} a^{4} - 6 L^{2} a^{2} x^{2} + a^{4} x^{2}\right)}{48 E I L^{3}}$$

$$\delta_B = \dfrac{a^{2} w \left(2 L^{3} \left(- 3 L x + a^{2} + 6 x^{2}\right) - 3 L^{2} x \left(a^{2} + 2 x^{2}\right) + a^{2} x^{3}\right)}{48 E I L^{3}}$$

#### Momentos fletores
$$M_A = \dfrac{w x \left(8 L^{3} a - 4 L^{3} x - 6 L^{2} a^{2} + a^{4}\right)}{8 L^{3}}$$

$$M_B = \dfrac{a^{2} w \left(4 L^{3} - 6 L^{2} x + a^{2} x\right)}{8 L^{3}}$$

#### Esforços cortantes
$$V_A = a w - w x - \dfrac{3 a^{2} w}{4 L} + \dfrac{a^{4} w}{8 L^{3}}$$

$$V_B = \dfrac{a^{2} w \left(- 6 L^{2} + a^{2}\right)}{8 L^{3}}$$

#### Reações de apoio
$$R_1 = \dfrac{a w \left(8 L^{3} - 6 L^{2} a + a^{3}\right)}{8 L^{3}}$$

$$R_2 = \dfrac{a^{2} w \left(6 L^{2} - a^{2}\right)}{8 L^{3}}$$

$$M_2 = - \dfrac{a^{2} w}{4} + \dfrac{a^{4} w}{8 L^{2}}$$

#### Equações em Python
```python
# Flechas
deltaA = w*x*(-6*L**4*a**2 + 8*L**3*a**3 + 8*L**3*a*x**2 - 2*L**3*x**3 - 3*L**2*a**4 - 6*L**2*a**2*x**2 + a**4*x**2)/(48*E*I*L**3)
deltaB = a**2*w*(2*L**3*(-3*L*x + a**2 + 6*x**2) - 3*L**2*x*(a**2 + 2*x**2) + a**2*x**3)/(48*E*I*L**3)
# Momentos fletores
MA = w*x*(8*L**3*a - 4*L**3*x - 6*L**2*a**2 + a**4)/(8*L**3)
MB = a**2*w*(4*L**3 - 6*L**2*x + a**2*x)/(8*L**3)
# Esforços cortantes
VA = a*w - w*x - 3*a**2*w/(4*L) + a**4*w/(8*L**3)
VB = a**2*w*(-6*L**2 + a**2)/(8*L**3)
# Reações de apoio
R1 = a*w*(8*L**3 - 6*L**2*a + a**3)/(8*L**3)
R2 = a**2*w*(6*L**2 - a**2)/(8*L**3)
M2 = -a**2*w/4 + a**4*w/(8*L**2)
```

---

### AE6-pv
- **Descrição:** Viga apoio-engaste com carga uniforme distribuída em parte do vão
- **Página offline:** `00. Site Offline/AE6-pv.html`
- **Legenda:**
  - $E$ - módulo de elasticidade do material da viga;
  - $I$ - inércia da seção transversal da viga (em torno no eixo que sai da tela);
  - $L$ - comprimento total da viga;
  - $a$ - comprimento do tramo A;
  - $b$ - comprimento do tramo B;
  - $w$ - carga distribuída uniforme;
  - $x$ - posição em uma parte qualquer de um tramo da viga;

#### Flechas
$$\delta_A = \dfrac{b w x \left(- 12 L^{4} a - 6 L^{4} b + 24 L^{3} a^{2} + 24 L^{3} a b + 8 L^{3} b^{2} + 8 L^{3} x^{2} - 12 L^{2} a^{3} - 18 L^{2} a^{2} b - 12 L^{2} a b^{2} - 12 L^{2} a x^{2} - 3 L^{2} b^{3} - 6 L^{2} b x^{2} + 4 a^{3} x^{2} + 6 a^{2} b x^{2} + 4 a b^{2} x^{2} + b^{3} x^{2}\right)}{48 E I L^{3}}$$

$$\delta_B = \dfrac{w \left(2 L^{3} \left(- 6 L a b x - 3 L b^{2} x - a^{4} + 4 a^{3} x + 12 a^{2} b x - 6 a^{2} x^{2} + 12 a b^{2} x + 4 a x^{3} + 4 b^{3} x + 4 b x^{3} - x^{4}\right) - 3 L^{2} b x \left(4 a^{3} + 6 a^{2} b + 4 a b^{2} + 4 a x^{2} + b^{3} + 2 b x^{2}\right) + b x^{3} \left(4 a^{3} + 6 a^{2} b + 4 a b^{2} + b^{3}\right)\right)}{48 E I L^{3}}$$

$$\delta_C = \dfrac{b w \left(2 L^{3} \left(- 6 L a x - 3 L b x + 4 a^{3} + 6 a^{2} b + 4 a b^{2} + 12 a x^{2} + b^{3} + 6 b x^{2}\right) - 3 L^{2} x \left(4 a^{3} + 6 a^{2} b + 4 a b^{2} + 4 a x^{2} + b^{3} + 2 b x^{2}\right) + x^{3} \left(4 a^{3} + 6 a^{2} b + 4 a b^{2} + b^{3}\right)\right)}{48 E I L^{3}}$$

#### Momentos fletores
$$M_A = \dfrac{b w x \left(8 L^{3} - 12 L^{2} a - 6 L^{2} b + 4 a^{3} + 6 a^{2} b + 4 a b^{2} + b^{3}\right)}{8 L^{3}}$$

$$M_B = \dfrac{w \left(4 L^{3} \left(- a^{2} + 2 a x + 2 b x - x^{2}\right) - 6 L^{2} b x \left(2 a + b\right) + b x \left(4 a^{3} + 6 a^{2} b + 4 a b^{2} + b^{3}\right)\right)}{8 L^{3}}$$

$$M_C = \dfrac{b w \left(4 L^{3} \left(2 a + b\right) - 6 L^{2} x \left(2 a + b\right) + x \left(4 a^{3} + 6 a^{2} b + 4 a b^{2} + b^{3}\right)\right)}{8 L^{3}}$$

#### Esforços cortantes
$$V_A = \dfrac{b w \left(8 L^{3} - 12 L^{2} a - 6 L^{2} b + 4 a^{3} + 6 a^{2} b + 4 a b^{2} + b^{3}\right)}{8 L^{3}}$$

$$V_B = \dfrac{w \left(8 L^{3} \left(a + b - x\right) - 6 L^{2} b \left(2 a + b\right) + b \left(4 a^{3} + 6 a^{2} b + 4 a b^{2} + b^{3}\right)\right)}{8 L^{3}}$$

$$V_C = \dfrac{b w \left(- 6 L^{2} \left(2 a + b\right) + 4 a^{3} + 6 a^{2} b + 4 a b^{2} + b^{3}\right)}{8 L^{3}}$$

#### Reações de apoio
$$R_1 = \dfrac{b w \left(8 L^{3} - 12 L^{2} a - 6 L^{2} b + 4 a^{3} + 6 a^{2} b + 4 a b^{2} + b^{3}\right)}{8 L^{3}}$$

$$R_2 = \dfrac{b w \left(12 L^{2} a + 6 L^{2} b - 4 a^{3} - 6 a^{2} b - 4 a b^{2} - b^{3}\right)}{8 L^{3}}$$

$$M_2 = \dfrac{b w \left(- 4 L^{2} a - 2 L^{2} b + 4 a^{3} + 6 a^{2} b + 4 a b^{2} + b^{3}\right)}{8 L^{2}}$$

#### Equações em Python
```python
# Flechas
deltaA = b*w*x*(-12*L**4*a - 6*L**4*b + 24*L**3*a**2 + 24*L**3*a*b + 8*L**3*b**2 + 8*L**3*x**2 - 12*L**2*a**3 - 18*L**2*a**2*b - 12*L**2*a*b**2 - 12*L**2*a*x**2 - 3*L**2*b**3 - 6*L**2*b*x**2 + 4*a**3*x**2 + 6*a**2*b*x**2 + 4*a*b**2*x**2 + b**3*x**2)/(48*E*I*L**3)
deltaB = w*(2*L**3*(-6*L*a*b*x - 3*L*b**2*x - a**4 + 4*a**3*x + 12*a**2*b*x - 6*a**2*x**2 + 12*a*b**2*x + 4*a*x**3 + 4*b**3*x + 4*b*x**3 - x**4) - 3*L**2*b*x*(4*a**3 + 6*a**2*b + 4*a*b**2 + 4*a*x**2 + b**3 + 2*b*x**2) + b*x**3*(4*a**3 + 6*a**2*b + 4*a*b**2 + b**3))/(48*E*I*L**3)
deltaC = b*w*(2*L**3*(-6*L*a*x - 3*L*b*x + 4*a**3 + 6*a**2*b + 4*a*b**2 + 12*a*x**2 + b**3 + 6*b*x**2) - 3*L**2*x*(4*a**3 + 6*a**2*b + 4*a*b**2 + 4*a*x**2 + b**3 + 2*b*x**2) + x**3*(4*a**3 + 6*a**2*b + 4*a*b**2 + b**3))/(48*E*I*L**3)
# Momentos fletores
MA = b*w*x*(8*L**3 - 12*L**2*a - 6*L**2*b + 4*a**3 + 6*a**2*b + 4*a*b**2 + b**3)/(8*L**3)
MB = w*(4*L**3*(-a**2 + 2*a*x + 2*b*x - x**2) - 6*L**2*b*x*(2*a + b) + b*x*(4*a**3 + 6*a**2*b + 4*a*b**2 + b**3))/(8*L**3)
MC = b*w*(4*L**3*(2*a + b) - 6*L**2*x*(2*a + b) + x*(4*a**3 + 6*a**2*b + 4*a*b**2 + b**3))/(8*L**3)
# Esforços cortantes
VA = b*w*(8*L**3 - 12*L**2*a - 6*L**2*b + 4*a**3 + 6*a**2*b + 4*a*b**2 + b**3)/(8*L**3)
VB = w*(8*L**3*(a + b - x) - 6*L**2*b*(2*a + b) + b*(4*a**3 + 6*a**2*b + 4*a*b**2 + b**3))/(8*L**3)
VC = b*w*(-6*L**2*(2*a + b) + 4*a**3 + 6*a**2*b + 4*a*b**2 + b**3)/(8*L**3)
# Reações de apoio
R1 = b*w*(8*L**3 - 12*L**2*a - 6*L**2*b + 4*a**3 + 6*a**2*b + 4*a*b**2 + b**3)/(8*L**3)
R2 = b*w*(12*L**2*a + 6*L**2*b - 4*a**3 - 6*a**2*b - 4*a*b**2 - b**3)/(8*L**3)
M2 = b*w*(-4*L**2*a - 2*L**2*b + 4*a**3 + 6*a**2*b + 4*a*b**2 + b**3)/(8*L**2)
```

---

### AE7-ev
- **Descrição:** Viga apoio-engaste com carga uniforme distribuída nos extremos do vão
- **Página offline:** `00. Site Offline/AE7-ev.html`
- **Legenda:**
  - $E$ - módulo de elasticidade do material da viga;
  - $I$ - inércia da seção transversal da viga (em torno no eixo que sai da tela);
  - $L$ - comprimento total da viga;
  - $a$ - comprimento do tramo A;
  - $b$ - comprimento do tramo B;
  - $w$ - carga distribuída uniforme;
  - $x$ - posição em uma parte qualquer de um tramo da viga;

#### Flechas
$$\delta_A = \dfrac{w x \left(- 6 L^{4} a^{2} + 8 L^{3} a^{3} + 8 L^{3} a x^{2} - 4 L^{3} b^{3} - 2 L^{3} x^{3} - 3 L^{2} a^{4} - 6 L^{2} a^{2} x^{2} + 3 L^{2} b^{4} + 4 L b^{3} x^{2} + a^{4} x^{2} - b^{4} x^{2}\right)}{48 E I L^{3}}$$

$$\delta_B = \dfrac{w \left(2 L^{3} \left(- 3 L a^{2} x + a^{4} + 6 a^{2} x^{2} - 2 b^{3} x\right) + 3 L^{2} x \left(- a^{4} - 2 a^{2} x^{2} + b^{4}\right) + 4 L b^{3} x^{3} + x^{3} \left(a^{4} - b^{4}\right)\right)}{48 E I L^{3}}$$

$$\delta_C = \dfrac{w \left(2 L^{3} \left(- L^{4} + 4 L^{3} b + 4 L^{3} x - 6 L^{2} b^{2} - 12 L^{2} b x - 6 L^{2} x^{2} - 3 L a^{2} x + 4 L b^{3} + 12 L b^{2} x + 12 L b x^{2} + 4 L x^{3} + a^{4} + 6 a^{2} x^{2} - b^{4} - 6 b^{3} x - 6 b^{2} x^{2} - 4 b x^{3} - x^{4}\right) + 3 L^{2} x \left(- a^{4} - 2 a^{2} x^{2} + b^{4}\right) + 4 L b^{3} x^{3} + x^{3} \left(a^{4} - b^{4}\right)\right)}{48 E I L^{3}}$$

#### Momentos fletores
$$M_A = \dfrac{w x \left(8 L^{3} a - 4 L^{3} x - 6 L^{2} a^{2} + 4 L b^{3} + a^{4} - b^{4}\right)}{8 L^{3}}$$

$$M_B = \dfrac{w \left(4 L^{3} a^{2} - 6 L^{2} a^{2} x + 4 L b^{3} x + x \left(a^{4} - b^{4}\right)\right)}{8 L^{3}}$$

$$M_C = \dfrac{w \left(4 L^{3} \left(- L^{2} + 2 L b + 2 L x + a^{2} - b^{2} - 2 b x - x^{2}\right) - 6 L^{2} a^{2} x + 4 L b^{3} x + x \left(a^{4} - b^{4}\right)\right)}{8 L^{3}}$$

#### Esforços cortantes
$$V_A = \dfrac{w \left(8 L^{3} a - 8 L^{3} x - 6 L^{2} a^{2} + 4 L b^{3} + a^{4} - b^{4}\right)}{8 L^{3}}$$

$$V_B = \dfrac{w \left(- 6 L^{2} a^{2} + 4 L b^{3} + a^{4} - b^{4}\right)}{8 L^{3}}$$

$$V_C = \dfrac{w \left(8 L^{3} \left(L - b - x\right) - 6 L^{2} a^{2} + 4 L b^{3} + a^{4} - b^{4}\right)}{8 L^{3}}$$

#### Reações de apoio
$$R_1 = \dfrac{w \left(8 L^{3} a - 6 L^{2} a^{2} + 4 L b^{3} + a^{4} - b^{4}\right)}{8 L^{3}}$$

$$R_2 = \dfrac{w \left(8 L^{3} b + 6 L^{2} a^{2} - 4 L b^{3} - a^{4} + b^{4}\right)}{8 L^{3}}$$

$$M_2 = \dfrac{w \left(- 2 L^{2} a^{2} - 4 L^{2} b^{2} + 4 L b^{3} + a^{4} - b^{4}\right)}{8 L^{2}}$$

#### Equações em Python
```python
# Flechas
deltaA = w*x*(-6*L**4*a**2 + 8*L**3*a**3 + 8*L**3*a*x**2 - 4*L**3*b**3 - 2*L**3*x**3 - 3*L**2*a**4 - 6*L**2*a**2*x**2 + 3*L**2*b**4 + 4*L*b**3*x**2 + a**4*x**2 - b**4*x**2)/(48*E*I*L**3)
deltaB = w*(2*L**3*(-3*L*a**2*x + a**4 + 6*a**2*x**2 - 2*b**3*x) + 3*L**2*x*(-a**4 - 2*a**2*x**2 + b**4) + 4*L*b**3*x**3 + x**3*(a**4 - b**4))/(48*E*I*L**3)
deltaC = w*(2*L**3*(-L**4 + 4*L**3*b + 4*L**3*x - 6*L**2*b**2 - 12*L**2*b*x - 6*L**2*x**2 - 3*L*a**2*x + 4*L*b**3 + 12*L*b**2*x + 12*L*b*x**2 + 4*L*x**3 + a**4 + 6*a**2*x**2 - b**4 - 6*b**3*x - 6*b**2*x**2 - 4*b*x**3 - x**4) + 3*L**2*x*(-a**4 - 2*a**2*x**2 + b**4) + 4*L*b**3*x**3 + x**3*(a**4 - b**4))/(48*E*I*L**3)
# Momentos fletores
MA = w*x*(8*L**3*a - 4*L**3*x - 6*L**2*a**2 + 4*L*b**3 + a**4 - b**4)/(8*L**3)
MB = w*(4*L**3*a**2 - 6*L**2*a**2*x + 4*L*b**3*x + x*(a**4 - b**4))/(8*L**3)
MC = w*(4*L**3*(-L**2 + 2*L*b + 2*L*x + a**2 - b**2 - 2*b*x - x**2) - 6*L**2*a**2*x + 4*L*b**3*x + x*(a**4 - b**4))/(8*L**3)
# Esforços cortantes
VA = w*(8*L**3*a - 8*L**3*x - 6*L**2*a**2 + 4*L*b**3 + a**4 - b**4)/(8*L**3)
VB = w*(-6*L**2*a**2 + 4*L*b**3 + a**4 - b**4)/(8*L**3)
VC = w*(8*L**3*(L - b - x) - 6*L**2*a**2 + 4*L*b**3 + a**4 - b**4)/(8*L**3)
# Reações de apoio
R1 = w*(8*L**3*a - 6*L**2*a**2 + 4*L*b**3 + a**4 - b**4)/(8*L**3)
R2 = w*(8*L**3*b + 6*L**2*a**2 - 4*L*b**3 - a**4 + b**4)/(8*L**3)
M2 = w*(-2*L**2*a**2 - 4*L**2*b**2 + 4*L*b**3 + a**4 - b**4)/(8*L**2)
```

---

### AE8-fa
- **Descrição:** Viga apoio-engaste com carga concentrada no vão
- **Equivalente nos formulários da prova:** **[J]**, **[AO]**, **[BL]**
- **Página offline:** `00. Site Offline/AE8-fa.html`
- **Legenda:**
  - $E$ - módulo de elasticidade do material da viga;
  - $F$ - carga concentrada;
  - $I$ - inércia da seção transversal da viga (em torno no eixo que sai da tela);
  - $L$ - comprimento total da viga;
  - $a$ - comprimento do tramo A;
  - $x$ - posição em uma parte qualquer de um tramo da viga;

#### Flechas
$$\delta_A = \dfrac{F x \left(- 3 L^{4} a + 6 L^{3} a^{2} + 2 L^{3} x^{2} - 3 L^{2} a^{3} - 3 L^{2} a x^{2} + a^{3} x^{2}\right)}{12 E I L^{3}}$$

$$\delta_B = \dfrac{F a \left(L^{3} \left(- 3 L x + 2 a^{2} + 6 x^{2}\right) - 3 L^{2} x \left(a^{2} + x^{2}\right) + a^{2} x^{3}\right)}{12 E I L^{3}}$$

#### Momentos fletores
$$M_A = \dfrac{F x \left(2 L^{3} - 3 L^{2} a + a^{3}\right)}{2 L^{3}}$$

$$M_B = \dfrac{F a \left(2 L^{3} - 3 L^{2} x + a^{2} x\right)}{2 L^{3}}$$

#### Esforços cortantes
$$V_A = F - \dfrac{3 F a}{2 L} + \dfrac{F a^{3}}{2 L^{3}}$$

$$V_B = \dfrac{F a \left(- 3 L^{2} + a^{2}\right)}{2 L^{3}}$$

#### Reações de apoio
$$R_1 = F - \dfrac{3 F a}{2 L} + \dfrac{F a^{3}}{2 L^{3}}$$

$$R_2 = \dfrac{F a \left(3 L^{2} - a^{2}\right)}{2 L^{3}}$$

$$M_2 = \dfrac{F a \left(- L^{2} + a^{2}\right)}{2 L^{2}}$$

#### Equações em Python
```python
# Flechas
deltaA = F*x*(-3*L**4*a + 6*L**3*a**2 + 2*L**3*x**2 - 3*L**2*a**3 - 3*L**2*a*x**2 + a**3*x**2)/(12*E*I*L**3)
deltaB = F*a*(L**3*(-3*L*x + 2*a**2 + 6*x**2) - 3*L**2*x*(a**2 + x**2) + a**2*x**3)/(12*E*I*L**3)
# Momentos fletores
MA = F*x*(2*L**3 - 3*L**2*a + a**3)/(2*L**3)
MB = F*a*(2*L**3 - 3*L**2*x + a**2*x)/(2*L**3)
# Esforços cortantes
VA = F - 3*F*a/(2*L) + F*a**3/(2*L**3)
VB = F*a*(-3*L**2 + a**2)/(2*L**3)
# Reações de apoio
R1 = F - 3*F*a/(2*L) + F*a**3/(2*L**3)
R2 = F*a*(3*L**2 - a**2)/(2*L**3)
M2 = F*a*(-L**2 + a**2)/(2*L**2)
```

---

### AE9-ff
- **Descrição:** Viga apoio-engaste com duas cargas concentradas no vão assimétricas
- **Página offline:** `00. Site Offline/AE9-ff.html`
- **Legenda:**
  - $E$ - módulo de elasticidade do material da viga;
  - $F$ - carga concentrada;
  - $I$ - inércia da seção transversal da viga (em torno no eixo que sai da tela);
  - $L$ - comprimento total da viga;
  - $a$ - comprimento do tramo A;
  - $b$ - comprimento do tramo B;
  - $x$ - posição em uma parte qualquer de um tramo da viga;

#### Flechas
$$\delta_A = \dfrac{F x \left(- 3 L^{4} a + 6 L^{3} a^{2} - 3 L^{3} b^{2} + 2 L^{3} x^{2} - 3 L^{2} a^{3} - 3 L^{2} a x^{2} + 3 L^{2} b^{3} + 3 L b^{2} x^{2} + a^{3} x^{2} - b^{3} x^{2}\right)}{12 E I L^{3}}$$

$$\delta_B = \dfrac{F \left(L^{3} \left(- 3 L a x + 2 a^{3} + 6 a x^{2} - 3 b^{2} x\right) + 3 L^{2} x \left(- a^{3} - a x^{2} + b^{3}\right) + 3 L b^{2} x^{3} + x^{3} \left(a^{3} - b^{3}\right)\right)}{12 E I L^{3}}$$

$$\delta_C = \dfrac{F \left(L^{3} \left(2 L^{3} - 6 L^{2} b - 6 L^{2} x - 3 L a x + 6 L b^{2} + 12 L b x + 6 L x^{2} + 2 a^{3} + 6 a x^{2} - 2 b^{3} - 9 b^{2} x - 6 b x^{2} - 2 x^{3}\right) + 3 L^{2} x \left(- a^{3} - a x^{2} + b^{3}\right) + 3 L b^{2} x^{3} + x^{3} \left(a^{3} - b^{3}\right)\right)}{12 E I L^{3}}$$

#### Momentos fletores
$$M_A = \dfrac{F x \left(2 L^{3} - 3 L^{2} a + 3 L b^{2} + a^{3} - b^{3}\right)}{2 L^{3}}$$

$$M_B = \dfrac{F \left(2 L^{3} a - 3 L^{2} a x + 3 L b^{2} x + x \left(a^{3} - b^{3}\right)\right)}{2 L^{3}}$$

$$M_C = \dfrac{F \left(2 L^{3} \left(L + a - b - x\right) - 3 L^{2} a x + 3 L b^{2} x + x \left(a^{3} - b^{3}\right)\right)}{2 L^{3}}$$

#### Esforços cortantes
$$V_A = \dfrac{F \left(2 L^{3} - 3 L^{2} a + 3 L b^{2} + a^{3} - b^{3}\right)}{2 L^{3}}$$

$$V_B = \dfrac{F \left(- 3 L^{2} a + 3 L b^{2} + a^{3} - b^{3}\right)}{2 L^{3}}$$

$$V_C = \dfrac{F \left(- 2 L^{3} - 3 L^{2} a + 3 L b^{2} + a^{3} - b^{3}\right)}{2 L^{3}}$$

#### Reações de apoio
$$R_1 = \dfrac{F \left(2 L^{3} - 3 L^{2} a + 3 L b^{2} + a^{3} - b^{3}\right)}{2 L^{3}}$$

$$R_2 = \dfrac{F \left(2 L^{3} + 3 L^{2} a - 3 L b^{2} - a^{3} + b^{3}\right)}{2 L^{3}}$$

$$M_2 = \dfrac{F \left(- L^{2} a - 2 L^{2} b + 3 L b^{2} + a^{3} - b^{3}\right)}{2 L^{2}}$$

#### Equações em Python
```python
# Flechas
deltaA = F*x*(-3*L**4*a + 6*L**3*a**2 - 3*L**3*b**2 + 2*L**3*x**2 - 3*L**2*a**3 - 3*L**2*a*x**2 + 3*L**2*b**3 + 3*L*b**2*x**2 + a**3*x**2 - b**3*x**2)/(12*E*I*L**3)
deltaB = F*(L**3*(-3*L*a*x + 2*a**3 + 6*a*x**2 - 3*b**2*x) + 3*L**2*x*(-a**3 - a*x**2 + b**3) + 3*L*b**2*x**3 + x**3*(a**3 - b**3))/(12*E*I*L**3)
deltaC = F*(L**3*(2*L**3 - 6*L**2*b - 6*L**2*x - 3*L*a*x + 6*L*b**2 + 12*L*b*x + 6*L*x**2 + 2*a**3 + 6*a*x**2 - 2*b**3 - 9*b**2*x - 6*b*x**2 - 2*x**3) + 3*L**2*x*(-a**3 - a*x**2 + b**3) + 3*L*b**2*x**3 + x**3*(a**3 - b**3))/(12*E*I*L**3)
# Momentos fletores
MA = F*x*(2*L**3 - 3*L**2*a + 3*L*b**2 + a**3 - b**3)/(2*L**3)
MB = F*(2*L**3*a - 3*L**2*a*x + 3*L*b**2*x + x*(a**3 - b**3))/(2*L**3)
MC = F*(2*L**3*(L + a - b - x) - 3*L**2*a*x + 3*L*b**2*x + x*(a**3 - b**3))/(2*L**3)
# Esforços cortantes
VA = F*(2*L**3 - 3*L**2*a + 3*L*b**2 + a**3 - b**3)/(2*L**3)
VB = F*(-3*L**2*a + 3*L*b**2 + a**3 - b**3)/(2*L**3)
VC = F*(-2*L**3 - 3*L**2*a + 3*L*b**2 + a**3 - b**3)/(2*L**3)
# Reações de apoio
R1 = F*(2*L**3 - 3*L**2*a + 3*L*b**2 + a**3 - b**3)/(2*L**3)
R2 = F*(2*L**3 + 3*L**2*a - 3*L*b**2 - a**3 + b**3)/(2*L**3)
M2 = F*(-L**2*a - 2*L**2*b + 3*L*b**2 + a**3 - b**3)/(2*L**2)
```

---

### AE10-m
- **Descrição:** Viga apoio-engaste com momento concentrado no vão
- **Equivalente nos formulários da prova:** **[L]**, **[AP]**
- **Página offline:** `00. Site Offline/AE10-m.html`
- **Legenda:**
  - $E$ - módulo de elasticidade do material da viga;
  - $I$ - inércia da seção transversal da viga (em torno no eixo que sai da tela);
  - $L$ - comprimento total da viga;
  - $M$ - momento concentrado;
  - $a$ - comprimento do tramo A;
  - $x$ - posição em uma parte qualquer de um tramo da viga;

#### Flechas
$$\delta_A = \dfrac{M x \left(- L^{4} + 4 L^{3} a - 3 L^{2} a^{2} - L^{2} x^{2} + a^{2} x^{2}\right)}{4 E I L^{3}}$$

$$\delta_B = \dfrac{M \left(L^{3} \left(- L x + 2 a^{2} + 2 x^{2}\right) - L^{2} x \left(3 a^{2} + x^{2}\right) + a^{2} x^{3}\right)}{4 E I L^{3}}$$

#### Momentos fletores
$$M_A = \dfrac{3 M x \left(- L^{2} + a^{2}\right)}{2 L^{3}}$$

$$M_B = M - \dfrac{3 M x}{2 L} + \dfrac{3 M a^{2} x}{2 L^{3}}$$

#### Esforços cortantes
$$V_A = \dfrac{3 M \left(- L^{2} + a^{2}\right)}{2 L^{3}}$$

$$V_B = \dfrac{3 M \left(- L^{2} + a^{2}\right)}{2 L^{3}}$$

#### Reações de apoio
$$R_1 = \dfrac{3 M \left(- L^{2} + a^{2}\right)}{2 L^{3}}$$

$$R_2 = \dfrac{3 M \left(L^{2} - a^{2}\right)}{2 L^{3}}$$

$$M_2 = \dfrac{M \left(- L^{2} + 3 a^{2}\right)}{2 L^{2}}$$

#### Equações em Python
```python
# Flechas
deltaA = M*x*(-L**4 + 4*L**3*a - 3*L**2*a**2 - L**2*x**2 + a**2*x**2)/(4*E*I*L**3)
deltaB = M*(L**3*(-L*x + 2*a**2 + 2*x**2) - L**2*x*(3*a**2 + x**2) + a**2*x**3)/(4*E*I*L**3)
# Momentos fletores
MA = 3*M*x*(-L**2 + a**2)/(2*L**3)
MB = M - 3*M*x/(2*L) + 3*M*a**2*x/(2*L**3)
# Esforços cortantes
VA = 3*M*(-L**2 + a**2)/(2*L**3)
VB = 3*M*(-L**2 + a**2)/(2*L**3)
# Reações de apoio
R1 = 3*M*(-L**2 + a**2)/(2*L**3)
R2 = 3*M*(L**2 - a**2)/(2*L**3)
M2 = M*(-L**2 + 3*a**2)/(2*L**2)
```

---

### AE11-mo
- **Descrição:** Viga apoio-engaste com momentos concentrados no vão assímetricos
- **Equivalente nos formulários da prova:** **[BJ]**
- **Página offline:** `00. Site Offline/AE11-mo.html`
- **Legenda:**
  - $E$ - módulo de elasticidade do material da viga;
  - $I$ - inércia da seção transversal da viga (em torno no eixo que sai da tela);
  - $L$ - comprimento total da viga;
  - $M$ - momento concentrado;
  - $a$ - comprimento do tramo A;
  - $b$ - comprimento do tramo B;
  - $x$ - posição em uma parte qualquer de um tramo da viga;

#### Flechas
$$\delta_A = \dfrac{M x \left(- L^{4} + 4 L^{3} a + 2 L^{3} b - 3 L^{2} a^{2} - 3 L^{2} b^{2} - L^{2} x^{2} - 2 L b x^{2} + a^{2} x^{2} + b^{2} x^{2}\right)}{4 E I L^{3}}$$

$$\delta_B = \dfrac{M \left(L^{3} \left(- L x + 2 a^{2} + 2 b x + 2 x^{2}\right) - L^{2} x \left(3 a^{2} + 3 b^{2} + x^{2}\right) - 2 L b x^{3} + x^{3} \left(a^{2} + b^{2}\right)\right)}{4 E I L^{3}}$$

$$\delta_C = \dfrac{M \left(L^{3} \left(2 L^{2} - 4 L b - 5 L x + 2 a^{2} + 2 b^{2} + 6 b x + 4 x^{2}\right) - L^{2} x \left(3 a^{2} + 3 b^{2} + x^{2}\right) - 2 L b x^{3} + x^{3} \left(a^{2} + b^{2}\right)\right)}{4 E I L^{3}}$$

#### Momentos fletores
$$M_A = \dfrac{3 M x \left(- L^{2} - 2 L b + a^{2} + b^{2}\right)}{2 L^{3}}$$

$$M_B = \dfrac{M \left(2 L^{3} - 3 L^{2} x - 6 L b x + 3 x \left(a^{2} + b^{2}\right)\right)}{2 L^{3}}$$

$$M_C = \dfrac{M \left(4 L^{3} - 3 L^{2} x - 6 L b x + 3 x \left(a^{2} + b^{2}\right)\right)}{2 L^{3}}$$

#### Esforços cortantes
$$V_A = \dfrac{3 M \left(- L^{2} - 2 L b + a^{2} + b^{2}\right)}{2 L^{3}}$$

$$V_B = \dfrac{3 M \left(- L^{2} - 2 L b + a^{2} + b^{2}\right)}{2 L^{3}}$$

$$V_C = \dfrac{3 M \left(- L^{2} - 2 L b + a^{2} + b^{2}\right)}{2 L^{3}}$$

#### Reações de apoio
$$R_1 = \dfrac{3 M \left(- L^{2} - 2 L b + a^{2} + b^{2}\right)}{2 L^{3}}$$

$$R_2 = \dfrac{3 M \left(L^{2} + 2 L b - a^{2} - b^{2}\right)}{2 L^{3}}$$

$$M_2 = \dfrac{M \left(L^{2} - 6 L b + 3 a^{2} + 3 b^{2}\right)}{2 L^{2}}$$

#### Equações em Python
```python
# Flechas
deltaA = M*x*(-L**4 + 4*L**3*a + 2*L**3*b - 3*L**2*a**2 - 3*L**2*b**2 - L**2*x**2 - 2*L*b*x**2 + a**2*x**2 + b**2*x**2)/(4*E*I*L**3)
deltaB = M*(L**3*(-L*x + 2*a**2 + 2*b*x + 2*x**2) - L**2*x*(3*a**2 + 3*b**2 + x**2) - 2*L*b*x**3 + x**3*(a**2 + b**2))/(4*E*I*L**3)
deltaC = M*(L**3*(2*L**2 - 4*L*b - 5*L*x + 2*a**2 + 2*b**2 + 6*b*x + 4*x**2) - L**2*x*(3*a**2 + 3*b**2 + x**2) - 2*L*b*x**3 + x**3*(a**2 + b**2))/(4*E*I*L**3)
# Momentos fletores
MA = 3*M*x*(-L**2 - 2*L*b + a**2 + b**2)/(2*L**3)
MB = M*(2*L**3 - 3*L**2*x - 6*L*b*x + 3*x*(a**2 + b**2))/(2*L**3)
MC = M*(4*L**3 - 3*L**2*x - 6*L*b*x + 3*x*(a**2 + b**2))/(2*L**3)
# Esforços cortantes
VA = 3*M*(-L**2 - 2*L*b + a**2 + b**2)/(2*L**3)
VB = 3*M*(-L**2 - 2*L*b + a**2 + b**2)/(2*L**3)
VC = 3*M*(-L**2 - 2*L*b + a**2 + b**2)/(2*L**3)
# Reações de apoio
R1 = 3*M*(-L**2 - 2*L*b + a**2 + b**2)/(2*L**3)
R2 = 3*M*(L**2 + 2*L*b - a**2 - b**2)/(2*L**3)
M2 = M*(L**2 - 6*L*b + 3*a**2 + 3*b**2)/(2*L**2)
```

---

## VÃO-BALANÇO

### VB1-w
- **Descrição:** Viga vão-balanço com carga uniformemente distribuída em toda a viga
- **Equivalente nos formulários da prova:** **[AQ]**, **[BN]**
- **Página offline:** `00. Site Offline/VB1-w.html`
- **Legenda:**
  - $E$ - módulo de elasticidade do material da viga;
  - $I$ - inércia da seção transversal da viga (em torno no eixo que sai da tela);
  - $L$ - comprimento total da viga;
  - $a$ - comprimento do tramo A;
  - $w$ - carga distribuída uniforme;
  - $x$ - posição em uma parte qualquer de um tramo da viga;

#### Flechas
$$\delta_A = \dfrac{w x \left(2 L^{2} a^{2} - 2 L^{2} x^{2} - 4 L a^{3} + 4 L a x^{2} + a^{4} - a x^{3}\right)}{24 E I a}$$

$$\delta_B = \dfrac{w \left(- 2 L^{2} a^{2} + 8 L^{2} a x - 6 L^{2} x^{2} - 4 L a^{2} x + 4 L x^{3} + a^{3} x - x^{4}\right)}{24 E I}$$

#### Momentos fletores
$$M_A = \dfrac{w x \left(- L^{2} + 2 L a - a x\right)}{2 a}$$

$$M_B = \dfrac{w \left(- L^{2} + 2 L x - x^{2}\right)}{2}$$

#### Esforços cortantes
$$V_A = - \dfrac{L^{2} w}{2 a} + L w - w x$$

$$V_B = w \left(L - x\right)$$

#### Reações de apoio
$$R_1 = \dfrac{L w \left(- L + 2 a\right)}{2 a}$$

$$R_2 = \dfrac{L^{2} w}{2 a}$$

#### Equações em Python
```python
# Flechas
deltaA = w*x*(2*L**2*a**2 - 2*L**2*x**2 - 4*L*a**3 + 4*L*a*x**2 + a**4 - a*x**3)/(24*E*I*a)
deltaB = w*(-2*L**2*a**2 + 8*L**2*a*x - 6*L**2*x**2 - 4*L*a**2*x + 4*L*x**3 + a**3*x - x**4)/(24*E*I)
# Momentos fletores
MA = w*x*(-L**2 + 2*L*a - a*x)/(2*a)
MB = w*(-L**2 + 2*L*x - x**2)/2
# Esforços cortantes
VA = -L**2*w/(2*a) + L*w - w*x
VB = w*(L - x)
# Reações de apoio
R1 = L*w*(-L + 2*a)/(2*a)
R2 = L**2*w/(2*a)
```

---

### VB2-wv
- **Descrição:** Viga vão-balanço com carga uniformemente distribuída no vão da viga
- **Página offline:** `00. Site Offline/VB2-wv.html`
- **Legenda:**
  - $E$ - módulo de elasticidade do material da viga;
  - $I$ - inércia da seção transversal da viga (em torno no eixo que sai da tela);
  - $a$ - comprimento do tramo A;
  - $w$ - carga distribuída uniforme;
  - $x$ - posição em uma parte qualquer de um tramo da viga;
  - $L$ - comprimento total da viga;

#### Flechas
$$\delta_A = \dfrac{w x \left(- a^{3} + 2 a x^{2} - x^{3}\right)}{24 E I}$$

$$\delta_B = \dfrac{a^{3} w \left(- a + x\right)}{24 E I}$$

#### Momentos fletores
$$M_A = \dfrac{w x \left(a - x\right)}{2}$$

$$M_B = 0$$

#### Esforços cortantes
$$V_A = \dfrac{w \left(a - 2 x\right)}{2}$$

$$V_B = 0$$

#### Reações de apoio
$$R_1 = \dfrac{a w}{2}$$

$$R_2 = \dfrac{a w}{2}$$

#### Equações em Python
```python
# Flechas
deltaA = w*x*(-a**3 + 2*a*x**2 - x**3)/(24*E*I)
deltaB = a**3*w*(-a + x)/(24*E*I)
# Momentos fletores
MA = w*x*(a - x)/2
MB = 0
# Esforços cortantes
VA = w*(a - 2*x)/2
VB = 0
# Reações de apoio
R1 = a*w/2
R2 = a*w/2
```

---

### VB3-wb
- **Descrição:** Viga vão-balanço com carga uniformemente distribuída no balanço da viga
- **Página offline:** `00. Site Offline/VB3-wb.html`
- **Legenda:**
  - $E$ - módulo de elasticidade do material da viga;
  - $I$ - inércia da seção transversal da viga (em torno no eixo que sai da tela);
  - $L$ - comprimento total da viga;
  - $a$ - comprimento do tramo A;
  - $w$ - carga distribuída uniforme;
  - $x$ - posição em uma parte qualquer de um tramo da viga;

#### Flechas
$$\delta_A = \dfrac{w x \left(L^{2} a^{2} - L^{2} x^{2} - 2 L a^{3} + 2 L a x^{2} + a^{4} - a^{2} x^{2}\right)}{12 E I a}$$

$$\delta_B = \dfrac{w \left(- 2 L^{2} a^{2} + 8 L^{2} a x - 6 L^{2} x^{2} - 4 L a^{2} x + 4 L x^{3} + a^{4} - x^{4}\right)}{24 E I}$$

#### Momentos fletores
$$M_A = \dfrac{w x \left(- L^{2} + 2 L a - a^{2}\right)}{2 a}$$

$$M_B = \dfrac{w \left(- L^{2} + 2 L x - x^{2}\right)}{2}$$

#### Esforços cortantes
$$V_A = \dfrac{w \left(- L^{2} + 2 L a - a^{2}\right)}{2 a}$$

$$V_B = w \left(L - x\right)$$

#### Reações de apoio
$$R_1 = \dfrac{w \left(- L^{2} + 2 L a - a^{2}\right)}{2 a}$$

$$R_2 = \dfrac{w \left(L^{2} - a^{2}\right)}{2 a}$$

#### Equações em Python
```python
# Flechas
deltaA = w*x*(L**2*a**2 - L**2*x**2 - 2*L*a**3 + 2*L*a*x**2 + a**4 - a**2*x**2)/(12*E*I*a)
deltaB = w*(-2*L**2*a**2 + 8*L**2*a*x - 6*L**2*x**2 - 4*L*a**2*x + 4*L*x**3 + a**4 - x**4)/(24*E*I)
# Momentos fletores
MA = w*x*(-L**2 + 2*L*a - a**2)/(2*a)
MB = w*(-L**2 + 2*L*x - x**2)/2
# Esforços cortantes
VA = w*(-L**2 + 2*L*a - a**2)/(2*a)
VB = w*(L - x)
# Reações de apoio
R1 = w*(-L**2 + 2*L*a - a**2)/(2*a)
R2 = w*(L**2 - a**2)/(2*a)
```

---

### VB4-pv
- **Descrição:** Viga vão-balanço com carga uniforme distribuída em parte do vão
- **Página offline:** `00. Site Offline/VB4-pv.html`
- **Legenda:**
  - $E$ - módulo de elasticidade do material da viga;
  - $I$ - inércia da seção transversal da viga (em torno no eixo que sai da tela);
  - $a$ - comprimento do tramo A;
  - $b$ - comprimento do tramo B;
  - $c$ - comprimento do tramo C;
  - $w$ - carga distribuída uniforme;
  - $x$ - posição em uma parte qualquer de um tramo da viga;
  - $L$ - comprimento total da viga;

#### Flechas
$$\delta_A = \dfrac{b w x \left(- 2 a^{2} b - 4 a^{2} c - 4 a b^{2} - 12 a b c - 8 a c^{2} - b^{3} - 4 b^{2} c - 4 b c^{2} + 2 b x^{2} + 4 c x^{2}\right)}{24 E I \left(a + b + c\right)}$$

$$\delta_B = \dfrac{w \left(- a^{5} - a^{4} b - a^{4} c + 4 a^{4} x + 4 a^{3} b x + 4 a^{3} c x - 6 a^{3} x^{2} - 2 a^{2} b^{2} x - 4 a^{2} b c x - 6 a^{2} b x^{2} - 6 a^{2} c x^{2} + 4 a^{2} x^{3} - 4 a b^{3} x - 12 a b^{2} c x - 8 a b c^{2} x + 4 a b x^{3} + 4 a c x^{3} - a x^{4} - b^{4} x - 4 b^{3} c x - 4 b^{2} c^{2} x + 2 b^{2} x^{3} + 4 b c x^{3} - b x^{4} - c x^{4}\right)}{24 E I \left(a + b + c\right)}$$

$$\delta_C = \dfrac{b w \left(4 a^{4} + 10 a^{3} b + 4 a^{3} c - 12 a^{3} x + 10 a^{2} b^{2} + 6 a^{2} b c - 26 a^{2} b x - 16 a^{2} c x + 12 a^{2} x^{2} + 5 a b^{3} + 4 a b^{2} c - 20 a b^{2} x - 24 a b c x + 18 a b x^{2} - 8 a c^{2} x + 12 a c x^{2} - 4 a x^{3} + b^{4} + b^{3} c - 5 b^{3} x - 8 b^{2} c x + 6 b^{2} x^{2} - 4 b c^{2} x + 6 b c x^{2} - 2 b x^{3}\right)}{24 E I \left(a + b + c\right)}$$

$$\delta_D = \dfrac{b w \left(- 4 a^{3} b - 8 a^{3} c - 8 a^{2} b^{2} - 24 a^{2} b c + 4 a^{2} b x - 12 a^{2} c^{2} + 8 a^{2} c x - 5 a b^{3} - 20 a b^{2} c + 4 a b^{2} x - 18 a b c^{2} + 12 a b c x - 4 a c^{3} + 4 a c^{2} x - b^{4} - 5 b^{3} c + b^{3} x - 6 b^{2} c^{2} + 4 b^{2} c x - 2 b c^{3} + 2 b c^{2} x\right)}{24 E I \left(a + b + c\right)}$$

#### Momentos fletores
$$M_A = \dfrac{b w x \left(b + 2 c\right)}{2 \left(a + b + c\right)}$$

$$M_B = \dfrac{w \left(- a^{3} - a^{2} b - a^{2} c + 2 a^{2} x + 2 a b x + 2 a c x - a x^{2} + b^{2} x + 2 b c x - b x^{2} - c x^{2}\right)}{2 \left(a + b + c\right)}$$

$$M_C = \dfrac{b w \left(2 a^{2} + 3 a b + 2 a c - 2 a x + b^{2} + b c - b x\right)}{2 \left(a + b + c\right)}$$

$$M_D = 0$$

#### Esforços cortantes
$$V_A = \dfrac{b w \left(b + 2 c\right)}{2 \left(a + b + c\right)}$$

$$V_B = \dfrac{w \left(2 a^{2} + 2 a b + 2 a c - 2 a x + b^{2} + 2 b c - 2 b x - 2 c x\right)}{2 \left(a + b + c\right)}$$

$$V_C = - \dfrac{b w \left(2 a + b\right)}{2 a + 2 b + 2 c}$$

$$V_D = 0$$

#### Reações de apoio
$$R_1 = \dfrac{b w \left(b + 2 c\right)}{2 \left(a + b + c\right)}$$

$$R_2 = \dfrac{b w \left(2 a + b\right)}{2 \left(a + b + c\right)}$$

#### Equações em Python
```python
# Flechas
deltaA = b*w*x*(-2*a**2*b - 4*a**2*c - 4*a*b**2 - 12*a*b*c - 8*a*c**2 - b**3 - 4*b**2*c - 4*b*c**2 + 2*b*x**2 + 4*c*x**2)/(24*E*I*(a + b + c))
deltaB = w*(-a**5 - a**4*b - a**4*c + 4*a**4*x + 4*a**3*b*x + 4*a**3*c*x - 6*a**3*x**2 - 2*a**2*b**2*x - 4*a**2*b*c*x - 6*a**2*b*x**2 - 6*a**2*c*x**2 + 4*a**2*x**3 - 4*a*b**3*x - 12*a*b**2*c*x - 8*a*b*c**2*x + 4*a*b*x**3 + 4*a*c*x**3 - a*x**4 - b**4*x - 4*b**3*c*x - 4*b**2*c**2*x + 2*b**2*x**3 + 4*b*c*x**3 - b*x**4 - c*x**4)/(24*E*I*(a + b + c))
deltaC = b*w*(4*a**4 + 10*a**3*b + 4*a**3*c - 12*a**3*x + 10*a**2*b**2 + 6*a**2*b*c - 26*a**2*b*x - 16*a**2*c*x + 12*a**2*x**2 + 5*a*b**3 + 4*a*b**2*c - 20*a*b**2*x - 24*a*b*c*x + 18*a*b*x**2 - 8*a*c**2*x + 12*a*c*x**2 - 4*a*x**3 + b**4 + b**3*c - 5*b**3*x - 8*b**2*c*x + 6*b**2*x**2 - 4*b*c**2*x + 6*b*c*x**2 - 2*b*x**3)/(24*E*I*(a + b + c))
deltaD = b*w*(-4*a**3*b - 8*a**3*c - 8*a**2*b**2 - 24*a**2*b*c + 4*a**2*b*x - 12*a**2*c**2 + 8*a**2*c*x - 5*a*b**3 - 20*a*b**2*c + 4*a*b**2*x - 18*a*b*c**2 + 12*a*b*c*x - 4*a*c**3 + 4*a*c**2*x - b**4 - 5*b**3*c + b**3*x - 6*b**2*c**2 + 4*b**2*c*x - 2*b*c**3 + 2*b*c**2*x)/(24*E*I*(a + b + c))
# Momentos fletores
MA = b*w*x*(b + 2*c)/(2*(a + b + c))
MB = w*(-a**3 - a**2*b - a**2*c + 2*a**2*x + 2*a*b*x + 2*a*c*x - a*x**2 + b**2*x + 2*b*c*x - b*x**2 - c*x**2)/(2*(a + b + c))
MC = b*w*(2*a**2 + 3*a*b + 2*a*c - 2*a*x + b**2 + b*c - b*x)/(2*(a + b + c))
MD = 0
# Esforços cortantes
VA = b*w*(b + 2*c)/(2*(a + b + c))
VB = w*(2*a**2 + 2*a*b + 2*a*c - 2*a*x + b**2 + 2*b*c - 2*b*x - 2*c*x)/(2*(a + b + c))
VC = -b*w*(2*a + b)/(2*a + 2*b + 2*c)
VD = 0
# Reações de apoio
R1 = b*w*(b + 2*c)/(2*(a + b + c))
R2 = b*w*(2*a + b)/(2*(a + b + c))
```

---

### VB5-fv
- **Descrição:** Viga vão-balanço com carga concentrada no vão
- **Página offline:** `00. Site Offline/VB5-fv.html`
- **Legenda:**
  - $E$ - módulo de elasticidade do material da viga;
  - $F$ - carga concentrada;
  - $I$ - inércia da seção transversal da viga (em torno no eixo que sai da tela);
  - $L$ - comprimento total da viga;
  - $a$ - comprimento do tramo A;
  - $b$ - comprimento do tramo B;
  - $x$ - posição em uma parte qualquer de um tramo da viga;

#### Flechas
$$\delta_A = \dfrac{F x \left(2 L^{2} a - 3 L a^{2} - 4 L a b - L x^{2} + a^{3} + 3 a^{2} b + 2 a b^{2} + a x^{2} + b x^{2}\right)}{6 E I \left(- L + b\right)}$$

$$\delta_B = \dfrac{F a \left(- 2 L^{2} x + L a^{2} + 4 L b x + 3 L x^{2} - a^{2} b - a^{2} x - 2 b^{2} x - 3 b x^{2} - x^{3}\right)}{6 E I \left(L - b\right)}$$

$$\delta_C = \dfrac{F a \left(- L^{3} + 3 L^{2} b + L^{2} x + L a^{2} - 3 L b^{2} - 2 L b x - a^{2} b - a^{2} x + b^{3} + b^{2} x\right)}{6 E I \left(L - b\right)}$$

#### Momentos fletores
$$M_A = \dfrac{F x \left(- L + a + b\right)}{- L + b}$$

$$M_B = \dfrac{F a \left(L - b - x\right)}{L - b}$$

$$M_C = 0$$

#### Esforços cortantes
$$V_A = \dfrac{F \left(- L + a + b\right)}{- L + b}$$

$$V_B = \dfrac{F a}{- L + b}$$

$$V_C = 0$$

#### Reações de apoio
$$R_1 = \dfrac{F \left(- L + a + b\right)}{- L + b}$$

$$R_2 = \dfrac{F a}{L - b}$$

#### Equações em Python
```python
# Flechas
deltaA = F*x*(2*L**2*a - 3*L*a**2 - 4*L*a*b - L*x**2 + a**3 + 3*a**2*b + 2*a*b**2 + a*x**2 + b*x**2)/(6*E*I*(-L + b))
deltaB = F*a*(-2*L**2*x + L*a**2 + 4*L*b*x + 3*L*x**2 - a**2*b - a**2*x - 2*b**2*x - 3*b*x**2 - x**3)/(6*E*I*(L - b))
deltaC = F*a*(-L**3 + 3*L**2*b + L**2*x + L*a**2 - 3*L*b**2 - 2*L*b*x - a**2*b - a**2*x + b**3 + b**2*x)/(6*E*I*(L - b))
# Momentos fletores
MA = F*x*(-L + a + b)/(-L + b)
MB = F*a*(L - b - x)/(L - b)
MC = 0
# Esforços cortantes
VA = F*(-L + a + b)/(-L + b)
VB = F*a/(-L + b)
VC = 0
# Reações de apoio
R1 = F*(-L + a + b)/(-L + b)
R2 = F*a/(L - b)
```

---

### VB6-fb
- **Descrição:** Viga vão-balanço com carga concentrada no balanço
- **Página offline:** `00. Site Offline/VB6-fb.html`
- **Legenda:**
  - $E$ - módulo de elasticidade do material da viga;
  - $F$ - carga concentrada;
  - $I$ - inércia da seção transversal da viga (em torno no eixo que sai da tela);
  - $a$ - comprimento do tramo A;
  - $b$ - comprimento do tramo B;
  - $x$ - posição em uma parte qualquer de um tramo da viga;
  - $L$ - comprimento total da viga;

#### Flechas
$$\delta_A = \dfrac{F b x \left(a^{2} - x^{2}\right)}{6 E I a}$$

$$\delta_B = \dfrac{F \left(- a^{3} - a^{2} b + 3 a^{2} x + 4 a b x - 3 a x^{2} - 3 b x^{2} + x^{3}\right)}{6 E I}$$

$$\delta_C = \dfrac{F b \left(2 a^{2} + 3 a b - 2 a x + b^{2} - 3 b x\right)}{6 E I}$$

#### Momentos fletores
$$M_A = - \dfrac{F b x}{a}$$

$$M_B = F \left(- a - b + x\right)$$

$$M_C = 0$$

#### Esforços cortantes
$$V_A = - \dfrac{F b}{a}$$

$$V_B = F$$

$$V_C = 0$$

#### Reações de apoio
$$R_1 = - \dfrac{F b}{a}$$

$$R_2 = \dfrac{F \left(a + b\right)}{a}$$

#### Equações em Python
```python
# Flechas
deltaA = F*b*x*(a**2 - x**2)/(6*E*I*a)
deltaB = F*(-a**3 - a**2*b + 3*a**2*x + 4*a*b*x - 3*a*x**2 - 3*b*x**2 + x**3)/(6*E*I)
deltaC = F*b*(2*a**2 + 3*a*b - 2*a*x + b**2 - 3*b*x)/(6*E*I)
# Momentos fletores
MA = -F*b*x/a
MB = F*(-a - b + x)
MC = 0
# Esforços cortantes
VA = -F*b/a
VB = F
VC = 0
# Reações de apoio
R1 = -F*b/a
R2 = F*(a + b)/a
```

---

### VB7-m
- **Descrição:** Viga vão-balanço com momento concentrado no vão
- **Página offline:** `00. Site Offline/VB7-m.html`
- **Legenda:**
  - $E$ - módulo de elasticidade do material da viga;
  - $I$ - inércia da seção transversal da viga (em torno no eixo que sai da tela);
  - $L$ - comprimento total da viga;
  - $M$ - momento concentrado;
  - $a$ - comprimento do tramo A;
  - $b$ - comprimento do tramo B;
  - $x$ - posição em uma parte qualquer de um tramo da viga;

#### Flechas
$$\delta_A = \dfrac{M x \left(2 L^{2} - 6 L a - 4 L b + 3 a^{2} + 6 a b + 2 b^{2} + x^{2}\right)}{6 E I \left(- L + b\right)}$$

$$\delta_B = \dfrac{M \left(- 2 L^{2} x + 3 L a^{2} + 4 L b x + 3 L x^{2} - 3 a^{2} b - 3 a^{2} x - 2 b^{2} x - 3 b x^{2} - x^{3}\right)}{6 E I \left(L - b\right)}$$

$$\delta_C = \dfrac{M \left(- L^{3} + 3 L^{2} b + L^{2} x + 3 L a^{2} - 3 L b^{2} - 2 L b x - 3 a^{2} b - 3 a^{2} x + b^{3} + b^{2} x\right)}{6 E I \left(L - b\right)}$$

#### Momentos fletores
$$M_A = \dfrac{M x}{- L + b}$$

$$M_B = \dfrac{M \left(L - b - x\right)}{L - b}$$

$$M_C = 0$$

#### Esforços cortantes
$$V_A = \dfrac{M}{- L + b}$$

$$V_B = \dfrac{M}{- L + b}$$

$$V_C = 0$$

#### Reações de apoio
$$R_1 = \dfrac{M}{- L + b}$$

$$R_2 = \dfrac{M}{L - b}$$

#### Equações em Python
```python
# Flechas
deltaA = M*x*(2*L**2 - 6*L*a - 4*L*b + 3*a**2 + 6*a*b + 2*b**2 + x**2)/(6*E*I*(-L + b))
deltaB = M*(-2*L**2*x + 3*L*a**2 + 4*L*b*x + 3*L*x**2 - 3*a**2*b - 3*a**2*x - 2*b**2*x - 3*b*x**2 - x**3)/(6*E*I*(L - b))
deltaC = M*(-L**3 + 3*L**2*b + L**2*x + 3*L*a**2 - 3*L*b**2 - 2*L*b*x - 3*a**2*b - 3*a**2*x + b**3 + b**2*x)/(6*E*I*(L - b))
# Momentos fletores
MA = M*x/(-L + b)
MB = M*(L - b - x)/(L - b)
MC = 0
# Esforços cortantes
VA = M/(-L + b)
VB = M/(-L + b)
VC = 0
# Reações de apoio
R1 = M/(-L + b)
R2 = M/(L - b)
```

---

### VB8-ma
- **Descrição:** Viga vão-balanço com momento concentrado no apoio
- **Página offline:** `00. Site Offline/VB8-ma.html`
- **Legenda:**
  - $E$ - módulo de elasticidade do material da viga;
  - $I$ - inércia da seção transversal da viga (em torno no eixo que sai da tela);
  - $M$ - momento concentrado;
  - $a$ - comprimento do tramo A;
  - $b$ - comprimento do tramo B;
  - $x$ - posição em uma parte qualquer de um tramo da viga;
  - $L$ - comprimento total da viga;

#### Flechas
$$\delta_A = \dfrac{M x \left(a^{2} - x^{2}\right)}{6 E I a}$$

$$\delta_B = \dfrac{M \left(- a^{2} + 4 a x - 3 x^{2}\right)}{6 E I}$$

$$\delta_C = \dfrac{M \left(2 a^{2} + 6 a b - 2 a x + 3 b^{2} - 6 b x\right)}{6 E I}$$

#### Momentos fletores
$$M_A = - \dfrac{M x}{a}$$

$$M_B = - M$$

$$M_C = 0$$

#### Esforços cortantes
$$V_A = - \dfrac{M}{a}$$

$$V_B = 0$$

$$V_C = 0$$

#### Reações de apoio
$$R_1 = - \dfrac{M}{a}$$

$$R_2 = \dfrac{M}{a}$$

#### Equações em Python
```python
# Flechas
deltaA = M*x*(a**2 - x**2)/(6*E*I*a)
deltaB = M*(-a**2 + 4*a*x - 3*x**2)/(6*E*I)
deltaC = M*(2*a**2 + 6*a*b - 2*a*x + 3*b**2 - 6*b*x)/(6*E*I)
# Momentos fletores
MA = -M*x/a
MB = -M
MC = 0
# Esforços cortantes
VA = -M/a
VB = 0
VC = 0
# Reações de apoio
R1 = -M/a
R2 = M/a
```

---

## DUPLO-VÃO

### DV1-w
- **Descrição:** Viga duplo-vão com carga uniformemente distribuída em toda a viga
- **Equivalente nos formulários da prova:** **[O]**
- **Página offline:** `00. Site Offline/DV1-w.html`
- **Legenda:**
  - $E$ - módulo de elasticidade do material da viga;
  - $I$ - inércia da seção transversal da viga (em torno no eixo que sai da tela);
  - $L$ - comprimento total da viga;
  - $a$ - comprimento do tramo A;
  - $w$ - carga distribuída uniforme;
  - $x$ - posição em uma parte qualquer de um tramo da viga;

#### Flechas
$$\delta_A = \dfrac{w x \left(L^{2} a^{2} - L^{2} x^{2} - 3 L a^{3} + 3 L a x^{2} + a^{4} + a^{2} x^{2} - 2 a x^{3}\right)}{48 E I a}$$

$$\delta_B = \dfrac{w \left(- L^{3} a^{2} + 4 L^{3} a x - 3 L^{3} x^{2} - L^{2} a^{3} - L^{2} a^{2} x - 3 L^{2} a x^{2} + 5 L^{2} x^{3} + L a^{4} + L a^{3} x + 3 L a^{2} x^{2} - 3 L a x^{3} - 2 L x^{4} - a^{4} x - a^{2} x^{3} + 2 a x^{4}\right)}{48 E I \left(L - a\right)}$$

#### Momentos fletores
$$M_A = \dfrac{w x \left(- L^{2} + 3 L a + a^{2} - 4 a x\right)}{8 a}$$

$$M_B = \dfrac{w \left(- L^{3} - L^{2} a + 5 L^{2} x + L a^{2} - 3 L a x - 4 L x^{2} - a^{2} x + 4 a x^{2}\right)}{8 \left(L - a\right)}$$

#### Esforços cortantes
$$V_A = \dfrac{w \left(- L^{2} + 3 L a + a^{2} - 8 a x\right)}{8 a}$$

$$V_B = \dfrac{w \left(5 L^{2} - 3 L a - 8 L x - a^{2} + 8 a x\right)}{8 \left(L - a\right)}$$

#### Reações de apoio
$$R_1 = \dfrac{w \left(- L^{2} + 3 L a + a^{2}\right)}{8 a}$$

$$R_2 = \dfrac{L w \left(- L^{2} - L a + a^{2}\right)}{8 a \left(- L + a\right)}$$

$$R_3 = \dfrac{w \left(- 3 L^{2} + 5 L a - a^{2}\right)}{8 \left(- L + a\right)}$$

#### Equações em Python
```python
# Flechas
deltaA = w*x*(L**2*a**2 - L**2*x**2 - 3*L*a**3 + 3*L*a*x**2 + a**4 + a**2*x**2 - 2*a*x**3)/(48*E*I*a)
deltaB = w*(-L**3*a**2 + 4*L**3*a*x - 3*L**3*x**2 - L**2*a**3 - L**2*a**2*x - 3*L**2*a*x**2 + 5*L**2*x**3 + L*a**4 + L*a**3*x + 3*L*a**2*x**2 - 3*L*a*x**3 - 2*L*x**4 - a**4*x - a**2*x**3 + 2*a*x**4)/(48*E*I*(L - a))
# Momentos fletores
MA = w*x*(-L**2 + 3*L*a + a**2 - 4*a*x)/(8*a)
MB = w*(-L**3 - L**2*a + 5*L**2*x + L*a**2 - 3*L*a*x - 4*L*x**2 - a**2*x + 4*a*x**2)/(8*(L - a))
# Esforços cortantes
VA = w*(-L**2 + 3*L*a + a**2 - 8*a*x)/(8*a)
VB = w*(5*L**2 - 3*L*a - 8*L*x - a**2 + 8*a*x)/(8*(L - a))
# Reações de apoio
R1 = w*(-L**2 + 3*L*a + a**2)/(8*a)
R2 = L*w*(-L**2 - L*a + a**2)/(8*a*(-L + a))
R3 = w*(-3*L**2 + 5*L*a - a**2)/(8*(-L + a))
```

---

### DV2-we
- **Descrição:** Viga duplo-vão com carga uniformemente distribuída no vão da esquerda
- **Equivalente nos formulários da prova:** **[M]**
- **Página offline:** `00. Site Offline/DV2-we.html`
- **Legenda:**
  - $E$ - módulo de elasticidade do material da viga;
  - $I$ - inércia da seção transversal da viga (em torno no eixo que sai da tela);
  - $L$ - comprimento total da viga;
  - $a$ - comprimento do tramo A;
  - $w$ - carga distribuída uniforme;
  - $x$ - posição em uma parte qualquer de um tramo da viga;

#### Flechas
$$\delta_A = \dfrac{w x \left(- 2 L a^{3} + 4 L a x^{2} - 2 L x^{3} + a^{4} - a^{2} x^{2}\right)}{48 E I L}$$

$$\delta_B = \dfrac{a^{3} w \left(- 2 L^{2} a + 2 L^{2} x + L a^{2} + 2 L a x - 3 L x^{2} - a^{2} x + x^{3}\right)}{48 E I L \left(L - a\right)}$$

#### Momentos fletores
$$M_A = \dfrac{w x \left(4 L a - 4 L x - a^{2}\right)}{8 L}$$

$$M_B = \dfrac{a^{3} w \left(- L + x\right)}{8 L \left(L - a\right)}$$

#### Esforços cortantes
$$V_A = \dfrac{a w}{2} - w x - \dfrac{a^{2} w}{8 L}$$

$$V_B = \dfrac{a^{3} w}{8 L \left(L - a\right)}$$

#### Reações de apoio
$$R_1 = \dfrac{a w \left(4 L - a\right)}{8 L}$$

$$R_2 = \dfrac{a w \left(- 4 L + 3 a\right)}{8 \left(- L + a\right)}$$

$$R_3 = \dfrac{a^{3} w}{8 L \left(- L + a\right)}$$

#### Equações em Python
```python
# Flechas
deltaA = w*x*(-2*L*a**3 + 4*L*a*x**2 - 2*L*x**3 + a**4 - a**2*x**2)/(48*E*I*L)
deltaB = a**3*w*(-2*L**2*a + 2*L**2*x + L*a**2 + 2*L*a*x - 3*L*x**2 - a**2*x + x**3)/(48*E*I*L*(L - a))
# Momentos fletores
MA = w*x*(4*L*a - 4*L*x - a**2)/(8*L)
MB = a**3*w*(-L + x)/(8*L*(L - a))
# Esforços cortantes
VA = a*w/2 - w*x - a**2*w/(8*L)
VB = a**3*w/(8*L*(L - a))
# Reações de apoio
R1 = a*w*(4*L - a)/(8*L)
R2 = a*w*(-4*L + 3*a)/(8*(-L + a))
R3 = a**3*w/(8*L*(-L + a))
```

---

### DV3-wd
- **Descrição:** Viga duplo-vão com carga uniformemente distribuída no vão da direita
- **Equivalente nos formulários da prova:** **[N]**
- **Página offline:** `00. Site Offline/DV3-wd.html`
- **Legenda:**
  - $E$ - módulo de elasticidade do material da viga;
  - $I$ - inércia da seção transversal da viga (em torno no eixo que sai da tela);
  - $L$ - comprimento total da viga;
  - $a$ - comprimento do tramo A;
  - $w$ - carga distribuída uniforme;
  - $x$ - posição em uma parte qualquer de um tramo da viga;

#### Flechas
$$\delta_A = \dfrac{w x \left(L^{3} a^{2} - L^{3} x^{2} - 3 L^{2} a^{3} + 3 L^{2} a x^{2} + 3 L a^{4} - 3 L a^{2} x^{2} - a^{5} + a^{3} x^{2}\right)}{48 E I L a}$$

$$\delta_B = \dfrac{w \left(L \left(- L^{2} a^{2} + 4 L^{2} a x - 3 L^{2} x^{2} - 2 L a^{3} + 3 L a^{2} x - 6 L a x^{2} + 5 L x^{3} + a^{4} + 2 a^{3} x - 3 a^{2} x^{2} + 2 a x^{3} - 2 x^{4}\right) + a^{2} x \left(- a^{2} + x^{2}\right)\right)}{48 E I L}$$

#### Momentos fletores
$$M_A = \dfrac{w x \left(- L^{3} + 3 L^{2} a - 3 L a^{2} + a^{3}\right)}{8 L a}$$

$$M_B = \dfrac{w \left(L \left(- L^{2} - 2 L a + 5 L x - a^{2} + 2 a x - 4 x^{2}\right) + a^{2} x\right)}{8 L}$$

#### Esforços cortantes
$$V_A = \dfrac{w \left(- L^{3} + 3 L^{2} a - 3 L a^{2} + a^{3}\right)}{8 L a}$$

$$V_B = \dfrac{w \left(L \left(5 L + 2 a - 8 x\right) + a^{2}\right)}{8 L}$$

#### Reações de apoio
$$R_1 = \dfrac{w \left(- L^{3} + 3 L^{2} a - 3 L a^{2} + a^{3}\right)}{8 L a}$$

$$R_2 = \dfrac{w \left(L^{2} + 2 L a - 3 a^{2}\right)}{8 a}$$

$$R_3 = \dfrac{w \left(3 L^{2} - 2 L a - a^{2}\right)}{8 L}$$

#### Equações em Python
```python
# Flechas
deltaA = w*x*(L**3*a**2 - L**3*x**2 - 3*L**2*a**3 + 3*L**2*a*x**2 + 3*L*a**4 - 3*L*a**2*x**2 - a**5 + a**3*x**2)/(48*E*I*L*a)
deltaB = w*(L*(-L**2*a**2 + 4*L**2*a*x - 3*L**2*x**2 - 2*L*a**3 + 3*L*a**2*x - 6*L*a*x**2 + 5*L*x**3 + a**4 + 2*a**3*x - 3*a**2*x**2 + 2*a*x**3 - 2*x**4) + a**2*x*(-a**2 + x**2))/(48*E*I*L)
# Momentos fletores
MA = w*x*(-L**3 + 3*L**2*a - 3*L*a**2 + a**3)/(8*L*a)
MB = w*(L*(-L**2 - 2*L*a + 5*L*x - a**2 + 2*a*x - 4*x**2) + a**2*x)/(8*L)
# Esforços cortantes
VA = w*(-L**3 + 3*L**2*a - 3*L*a**2 + a**3)/(8*L*a)
VB = w*(L*(5*L + 2*a - 8*x) + a**2)/(8*L)
# Reações de apoio
R1 = w*(-L**3 + 3*L**2*a - 3*L*a**2 + a**3)/(8*L*a)
R2 = w*(L**2 + 2*L*a - 3*a**2)/(8*a)
R3 = w*(3*L**2 - 2*L*a - a**2)/(8*L)
```

---

### DV4-wv
- **Descrição:** Viga duplo-vão com carga uniformemente distribuída em parte do vão esquerdo da viga
- **Página offline:** `00. Site Offline/DV4-wv.html`
- **Legenda:**
  - $E$ - módulo de elasticidade do material da viga;
  - $I$ - inércia da seção transversal da viga (em torno no eixo que sai da tela);
  - $L$ - comprimento total da viga;
  - $a$ - comprimento do tramo A;
  - $b$ - comprimento do tramo B;
  - $c$ - comprimento do tramo C;
  - $w$ - carga distribuída uniforme;
  - $x$ - posição em uma parte qualquer de um tramo da viga;

#### Flechas
$$\delta_A = \dfrac{b w x \left(- 12 L^{4} a - 6 L^{4} b + 24 L^{3} a^{2} + 24 L^{3} a b + 32 L^{3} a c + 8 L^{3} b^{2} + 16 L^{3} b c + 8 L^{3} x^{2} - 12 L^{2} a^{3} - 18 L^{2} a^{2} b - 48 L^{2} a^{2} c - 12 L^{2} a b^{2} - 48 L^{2} a b c - 24 L^{2} a c^{2} - 12 L^{2} a x^{2} - 3 L^{2} b^{3} - 16 L^{2} b^{2} c - 12 L^{2} b c^{2} - 6 L^{2} b x^{2} - 16 L^{2} c x^{2} + 16 L a^{3} c + 24 L a^{2} b c + 24 L a^{2} c^{2} + 16 L a b^{2} c + 24 L a b c^{2} + 16 L a c x^{2} + 4 L b^{3} c + 8 L b^{2} c^{2} + 8 L b c x^{2} + 8 L c^{2} x^{2} - 4 a^{3} c^{2} + 4 a^{3} x^{2} - 6 a^{2} b c^{2} + 6 a^{2} b x^{2} - 4 a b^{2} c^{2} + 4 a b^{2} x^{2} + 4 a c^{4} - 4 a c^{2} x^{2} - b^{3} c^{2} + b^{3} x^{2} + 2 b c^{4} - 2 b c^{2} x^{2}\right)}{48 E I L \left(L^{2} - 2 L c + c^{2}\right)}$$

$$\delta_B = \dfrac{w \left(- 12 L^{4} a b x - 6 L^{4} b^{2} x - 2 L^{3} a^{4} + 8 L^{3} a^{3} x + 24 L^{3} a^{2} b x - 12 L^{3} a^{2} x^{2} + 24 L^{3} a b^{2} x + 32 L^{3} a b c x + 8 L^{3} a x^{3} + 8 L^{3} b^{3} x + 16 L^{3} b^{2} c x + 8 L^{3} b x^{3} - 2 L^{3} x^{4} + 4 L^{2} a^{4} c - 12 L^{2} a^{3} b x - 16 L^{2} a^{3} c x - 18 L^{2} a^{2} b^{2} x - 48 L^{2} a^{2} b c x + 24 L^{2} a^{2} c x^{2} - 12 L^{2} a b^{3} x - 48 L^{2} a b^{2} c x - 24 L^{2} a b c^{2} x - 12 L^{2} a b x^{3} - 16 L^{2} a c x^{3} - 3 L^{2} b^{4} x - 16 L^{2} b^{3} c x - 12 L^{2} b^{2} c^{2} x - 6 L^{2} b^{2} x^{3} - 16 L^{2} b c x^{3} + 4 L^{2} c x^{4} - 2 L a^{4} c^{2} + 16 L a^{3} b c x + 8 L a^{3} c^{2} x + 24 L a^{2} b^{2} c x + 24 L a^{2} b c^{2} x - 12 L a^{2} c^{2} x^{2} + 16 L a b^{3} c x + 24 L a b^{2} c^{2} x + 16 L a b c x^{3} + 8 L a c^{2} x^{3} + 4 L b^{4} c x + 8 L b^{3} c^{2} x + 8 L b^{2} c x^{3} + 8 L b c^{2} x^{3} - 2 L c^{2} x^{4} - 4 a^{3} b c^{2} x + 4 a^{3} b x^{3} - 6 a^{2} b^{2} c^{2} x + 6 a^{2} b^{2} x^{3} - 4 a b^{3} c^{2} x + 4 a b^{3} x^{3} + 4 a b c^{4} x - 4 a b c^{2} x^{3} - b^{4} c^{2} x + b^{4} x^{3} + 2 b^{2} c^{4} x - 2 b^{2} c^{2} x^{3}\right)}{48 E I L \left(L^{2} - 2 L c + c^{2}\right)}$$

$$\delta_C = \dfrac{b w \left(- 12 L^{4} a x - 6 L^{4} b x + 8 L^{3} a^{3} + 12 L^{3} a^{2} b + 8 L^{3} a b^{2} + 32 L^{3} a c x + 24 L^{3} a x^{2} + 2 L^{3} b^{3} + 16 L^{3} b c x + 12 L^{3} b x^{2} - 16 L^{2} a^{3} c - 12 L^{2} a^{3} x - 24 L^{2} a^{2} b c - 18 L^{2} a^{2} b x - 16 L^{2} a b^{2} c - 12 L^{2} a b^{2} x - 24 L^{2} a c^{2} x - 48 L^{2} a c x^{2} - 12 L^{2} a x^{3} - 4 L^{2} b^{3} c - 3 L^{2} b^{3} x - 12 L^{2} b c^{2} x - 24 L^{2} b c x^{2} - 6 L^{2} b x^{3} + 8 L a^{3} c^{2} + 16 L a^{3} c x + 12 L a^{2} b c^{2} + 24 L a^{2} b c x + 8 L a b^{2} c^{2} + 16 L a b^{2} c x + 24 L a c^{2} x^{2} + 16 L a c x^{3} + 2 L b^{3} c^{2} + 4 L b^{3} c x + 12 L b c^{2} x^{2} + 8 L b c x^{3} - 4 a^{3} c^{2} x + 4 a^{3} x^{3} - 6 a^{2} b c^{2} x + 6 a^{2} b x^{3} - 4 a b^{2} c^{2} x + 4 a b^{2} x^{3} + 4 a c^{4} x - 4 a c^{2} x^{3} - b^{3} c^{2} x + b^{3} x^{3} + 2 b c^{4} x - 2 b c^{2} x^{3}\right)}{48 E I L \left(L^{2} - 2 L c + c^{2}\right)}$$

$$\delta_D = \dfrac{b w \left(- 4 L^{5} a - 2 L^{5} b + 8 L^{4} a c + 12 L^{4} a x + 4 L^{4} b c + 6 L^{4} b x + 4 L^{3} a^{3} + 6 L^{3} a^{2} b + 4 L^{3} a b^{2} - 24 L^{3} a c x - 12 L^{3} a x^{2} + L^{3} b^{3} - 12 L^{3} b c x - 6 L^{3} b x^{2} - 12 L^{2} a^{3} x - 18 L^{2} a^{2} b x - 12 L^{2} a b^{2} x - 8 L^{2} a c^{3} + 8 L^{2} a c^{2} x + 24 L^{2} a c x^{2} + 4 L^{2} a x^{3} - 3 L^{2} b^{3} x - 4 L^{2} b c^{3} + 4 L^{2} b c^{2} x + 12 L^{2} b c x^{2} + 2 L^{2} b x^{3} - 4 L a^{3} c^{2} + 12 L a^{3} x^{2} - 6 L a^{2} b c^{2} + 18 L a^{2} b x^{2} - 4 L a b^{2} c^{2} + 12 L a b^{2} x^{2} + 4 L a c^{4} + 8 L a c^{3} x - 12 L a c^{2} x^{2} - 8 L a c x^{3} - L b^{3} c^{2} + 3 L b^{3} x^{2} + 2 L b c^{4} + 4 L b c^{3} x - 6 L b c^{2} x^{2} - 4 L b c x^{3} + 4 a^{3} c^{2} x - 4 a^{3} x^{3} + 6 a^{2} b c^{2} x - 6 a^{2} b x^{3} + 4 a b^{2} c^{2} x - 4 a b^{2} x^{3} - 4 a c^{4} x + 4 a c^{2} x^{3} + b^{3} c^{2} x - b^{3} x^{3} - 2 b c^{4} x + 2 b c^{2} x^{3}\right)}{48 E I L c \left(L - c\right)}$$

#### Momentos fletores
$$M_A = \dfrac{b w x \left(8 L^{3} - 12 L^{2} a - 6 L^{2} b - 16 L^{2} c + 16 L a c + 8 L b c + 8 L c^{2} + 4 a^{3} + 6 a^{2} b + 4 a b^{2} - 4 a c^{2} + b^{3} - 2 b c^{2}\right)}{8 L \left(L^{2} - 2 L c + c^{2}\right)}$$

$$M_B = \dfrac{w \left(- 4 L^{3} a^{2} + 8 L^{3} a x + 8 L^{3} b x - 4 L^{3} x^{2} + 8 L^{2} a^{2} c - 12 L^{2} a b x - 16 L^{2} a c x - 6 L^{2} b^{2} x - 16 L^{2} b c x + 8 L^{2} c x^{2} - 4 L a^{2} c^{2} + 16 L a b c x + 8 L a c^{2} x + 8 L b^{2} c x + 8 L b c^{2} x - 4 L c^{2} x^{2} + 4 a^{3} b x + 6 a^{2} b^{2} x + 4 a b^{3} x - 4 a b c^{2} x + b^{4} x - 2 b^{2} c^{2} x\right)}{8 L \left(L^{2} - 2 L c + c^{2}\right)}$$

$$M_C = \dfrac{b w \left(8 L^{3} a + 4 L^{3} b - 16 L^{2} a c - 12 L^{2} a x - 8 L^{2} b c - 6 L^{2} b x + 8 L a c^{2} + 16 L a c x + 4 L b c^{2} + 8 L b c x + 4 a^{3} x + 6 a^{2} b x + 4 a b^{2} x - 4 a c^{2} x + b^{3} x - 2 b c^{2} x\right)}{8 L \left(L^{2} - 2 L c + c^{2}\right)}$$

$$M_D = \dfrac{b w \left(- 4 L^{3} a - 2 L^{3} b + 8 L^{2} a c + 4 L^{2} a x + 4 L^{2} b c + 2 L^{2} b x + 4 L a^{3} + 6 L a^{2} b + 4 L a b^{2} - 4 L a c^{2} - 8 L a c x + L b^{3} - 2 L b c^{2} - 4 L b c x - 4 a^{3} x - 6 a^{2} b x - 4 a b^{2} x + 4 a c^{2} x - b^{3} x + 2 b c^{2} x\right)}{8 L c \left(L - c\right)}$$

#### Esforços cortantes
$$V_A = \dfrac{b w \left(8 L^{3} - 12 L^{2} a - 6 L^{2} b - 16 L^{2} c + 16 L a c + 8 L b c + 8 L c^{2} + 4 a^{3} + 6 a^{2} b + 4 a b^{2} - 4 a c^{2} + b^{3} - 2 b c^{2}\right)}{8 L \left(L^{2} - 2 L c + c^{2}\right)}$$

$$V_B = \dfrac{w \left(8 L^{3} a + 8 L^{3} b - 8 L^{3} x - 12 L^{2} a b - 16 L^{2} a c - 6 L^{2} b^{2} - 16 L^{2} b c + 16 L^{2} c x + 16 L a b c + 8 L a c^{2} + 8 L b^{2} c + 8 L b c^{2} - 8 L c^{2} x + 4 a^{3} b + 6 a^{2} b^{2} + 4 a b^{3} - 4 a b c^{2} + b^{4} - 2 b^{2} c^{2}\right)}{8 L \left(L^{2} - 2 L c + c^{2}\right)}$$

$$V_C = \dfrac{b w \left(- 12 L^{2} a - 6 L^{2} b + 16 L a c + 8 L b c + 4 a^{3} + 6 a^{2} b + 4 a b^{2} - 4 a c^{2} + b^{3} - 2 b c^{2}\right)}{8 L \left(L^{2} - 2 L c + c^{2}\right)}$$

$$V_D = \dfrac{b w \left(4 L^{2} a + 2 L^{2} b - 8 L a c - 4 L b c - 4 a^{3} - 6 a^{2} b - 4 a b^{2} + 4 a c^{2} - b^{3} + 2 b c^{2}\right)}{8 L c \left(L - c\right)}$$

#### Reações de apoio
$$R_1 = \dfrac{b w \left(8 L^{3} - 12 L^{2} a - 6 L^{2} b - 16 L^{2} c + 16 L a c + 8 L b c + 8 L c^{2} + 4 a^{3} + 6 a^{2} b + 4 a b^{2} - 4 a c^{2} + b^{3} - 2 b c^{2}\right)}{8 L \left(L^{2} - 2 L c + c^{2}\right)}$$

$$R_2 = \dfrac{b w \left(4 L^{2} a + 2 L^{2} b - 4 a^{3} - 6 a^{2} b - 4 a b^{2} - 4 a c^{2} - b^{3} - 2 b c^{2}\right)}{8 c \left(L^{2} - 2 L c + c^{2}\right)}$$

$$R_3 = \dfrac{b w \left(- 4 L^{2} a - 2 L^{2} b + 8 L a c + 4 L b c + 4 a^{3} + 6 a^{2} b + 4 a b^{2} - 4 a c^{2} + b^{3} - 2 b c^{2}\right)}{8 L c \left(L - c\right)}$$

#### Equações em Python
```python
# Flechas
deltaA = b*w*x*(-12*L**4*a - 6*L**4*b + 24*L**3*a**2 + 24*L**3*a*b + 32*L**3*a*c + 8*L**3*b**2 + 16*L**3*b*c + 8*L**3*x**2 - 12*L**2*a**3 - 18*L**2*a**2*b - 48*L**2*a**2*c - 12*L**2*a*b**2 - 48*L**2*a*b*c - 24*L**2*a*c**2 - 12*L**2*a*x**2 - 3*L**2*b**3 - 16*L**2*b**2*c - 12*L**2*b*c**2 - 6*L**2*b*x**2 - 16*L**2*c*x**2 + 16*L*a**3*c + 24*L*a**2*b*c + 24*L*a**2*c**2 + 16*L*a*b**2*c + 24*L*a*b*c**2 + 16*L*a*c*x**2 + 4*L*b**3*c + 8*L*b**2*c**2 + 8*L*b*c*x**2 + 8*L*c**2*x**2 - 4*a**3*c**2 + 4*a**3*x**2 - 6*a**2*b*c**2 + 6*a**2*b*x**2 - 4*a*b**2*c**2 + 4*a*b**2*x**2 + 4*a*c**4 - 4*a*c**2*x**2 - b**3*c**2 + b**3*x**2 + 2*b*c**4 - 2*b*c**2*x**2)/(48*E*I*L*(L**2 - 2*L*c + c**2))
deltaB = w*(-12*L**4*a*b*x - 6*L**4*b**2*x - 2*L**3*a**4 + 8*L**3*a**3*x + 24*L**3*a**2*b*x - 12*L**3*a**2*x**2 + 24*L**3*a*b**2*x + 32*L**3*a*b*c*x + 8*L**3*a*x**3 + 8*L**3*b**3*x + 16*L**3*b**2*c*x + 8*L**3*b*x**3 - 2*L**3*x**4 + 4*L**2*a**4*c - 12*L**2*a**3*b*x - 16*L**2*a**3*c*x - 18*L**2*a**2*b**2*x - 48*L**2*a**2*b*c*x + 24*L**2*a**2*c*x**2 - 12*L**2*a*b**3*x - 48*L**2*a*b**2*c*x - 24*L**2*a*b*c**2*x - 12*L**2*a*b*x**3 - 16*L**2*a*c*x**3 - 3*L**2*b**4*x - 16*L**2*b**3*c*x - 12*L**2*b**2*c**2*x - 6*L**2*b**2*x**3 - 16*L**2*b*c*x**3 + 4*L**2*c*x**4 - 2*L*a**4*c**2 + 16*L*a**3*b*c*x + 8*L*a**3*c**2*x + 24*L*a**2*b**2*c*x + 24*L*a**2*b*c**2*x - 12*L*a**2*c**2*x**2 + 16*L*a*b**3*c*x + 24*L*a*b**2*c**2*x + 16*L*a*b*c*x**3 + 8*L*a*c**2*x**3 + 4*L*b**4*c*x + 8*L*b**3*c**2*x + 8*L*b**2*c*x**3 + 8*L*b*c**2*x**3 - 2*L*c**2*x**4 - 4*a**3*b*c**2*x + 4*a**3*b*x**3 - 6*a**2*b**2*c**2*x + 6*a**2*b**2*x**3 - 4*a*b**3*c**2*x + 4*a*b**3*x**3 + 4*a*b*c**4*x - 4*a*b*c**2*x**3 - b**4*c**2*x + b**4*x**3 + 2*b**2*c**4*x - 2*b**2*c**2*x**3)/(48*E*I*L*(L**2 - 2*L*c + c**2))
deltaC = b*w*(-12*L**4*a*x - 6*L**4*b*x + 8*L**3*a**3 + 12*L**3*a**2*b + 8*L**3*a*b**2 + 32*L**3*a*c*x + 24*L**3*a*x**2 + 2*L**3*b**3 + 16*L**3*b*c*x + 12*L**3*b*x**2 - 16*L**2*a**3*c - 12*L**2*a**3*x - 24*L**2*a**2*b*c - 18*L**2*a**2*b*x - 16*L**2*a*b**2*c - 12*L**2*a*b**2*x - 24*L**2*a*c**2*x - 48*L**2*a*c*x**2 - 12*L**2*a*x**3 - 4*L**2*b**3*c - 3*L**2*b**3*x - 12*L**2*b*c**2*x - 24*L**2*b*c*x**2 - 6*L**2*b*x**3 + 8*L*a**3*c**2 + 16*L*a**3*c*x + 12*L*a**2*b*c**2 + 24*L*a**2*b*c*x + 8*L*a*b**2*c**2 + 16*L*a*b**2*c*x + 24*L*a*c**2*x**2 + 16*L*a*c*x**3 + 2*L*b**3*c**2 + 4*L*b**3*c*x + 12*L*b*c**2*x**2 + 8*L*b*c*x**3 - 4*a**3*c**2*x + 4*a**3*x**3 - 6*a**2*b*c**2*x + 6*a**2*b*x**3 - 4*a*b**2*c**2*x + 4*a*b**2*x**3 + 4*a*c**4*x - 4*a*c**2*x**3 - b**3*c**2*x + b**3*x**3 + 2*b*c**4*x - 2*b*c**2*x**3)/(48*E*I*L*(L**2 - 2*L*c + c**2))
deltaD = b*w*(-4*L**5*a - 2*L**5*b + 8*L**4*a*c + 12*L**4*a*x + 4*L**4*b*c + 6*L**4*b*x + 4*L**3*a**3 + 6*L**3*a**2*b + 4*L**3*a*b**2 - 24*L**3*a*c*x - 12*L**3*a*x**2 + L**3*b**3 - 12*L**3*b*c*x - 6*L**3*b*x**2 - 12*L**2*a**3*x - 18*L**2*a**2*b*x - 12*L**2*a*b**2*x - 8*L**2*a*c**3 + 8*L**2*a*c**2*x + 24*L**2*a*c*x**2 + 4*L**2*a*x**3 - 3*L**2*b**3*x - 4*L**2*b*c**3 + 4*L**2*b*c**2*x + 12*L**2*b*c*x**2 + 2*L**2*b*x**3 - 4*L*a**3*c**2 + 12*L*a**3*x**2 - 6*L*a**2*b*c**2 + 18*L*a**2*b*x**2 - 4*L*a*b**2*c**2 + 12*L*a*b**2*x**2 + 4*L*a*c**4 + 8*L*a*c**3*x - 12*L*a*c**2*x**2 - 8*L*a*c*x**3 - L*b**3*c**2 + 3*L*b**3*x**2 + 2*L*b*c**4 + 4*L*b*c**3*x - 6*L*b*c**2*x**2 - 4*L*b*c*x**3 + 4*a**3*c**2*x - 4*a**3*x**3 + 6*a**2*b*c**2*x - 6*a**2*b*x**3 + 4*a*b**2*c**2*x - 4*a*b**2*x**3 - 4*a*c**4*x + 4*a*c**2*x**3 + b**3*c**2*x - b**3*x**3 - 2*b*c**4*x + 2*b*c**2*x**3)/(48*E*I*L*c*(L - c))
# Momentos fletores
MA = b*w*x*(8*L**3 - 12*L**2*a - 6*L**2*b - 16*L**2*c + 16*L*a*c + 8*L*b*c + 8*L*c**2 + 4*a**3 + 6*a**2*b + 4*a*b**2 - 4*a*c**2 + b**3 - 2*b*c**2)/(8*L*(L**2 - 2*L*c + c**2))
MB = w*(-4*L**3*a**2 + 8*L**3*a*x + 8*L**3*b*x - 4*L**3*x**2 + 8*L**2*a**2*c - 12*L**2*a*b*x - 16*L**2*a*c*x - 6*L**2*b**2*x - 16*L**2*b*c*x + 8*L**2*c*x**2 - 4*L*a**2*c**2 + 16*L*a*b*c*x + 8*L*a*c**2*x + 8*L*b**2*c*x + 8*L*b*c**2*x - 4*L*c**2*x**2 + 4*a**3*b*x + 6*a**2*b**2*x + 4*a*b**3*x - 4*a*b*c**2*x + b**4*x - 2*b**2*c**2*x)/(8*L*(L**2 - 2*L*c + c**2))
MC = b*w*(8*L**3*a + 4*L**3*b - 16*L**2*a*c - 12*L**2*a*x - 8*L**2*b*c - 6*L**2*b*x + 8*L*a*c**2 + 16*L*a*c*x + 4*L*b*c**2 + 8*L*b*c*x + 4*a**3*x + 6*a**2*b*x + 4*a*b**2*x - 4*a*c**2*x + b**3*x - 2*b*c**2*x)/(8*L*(L**2 - 2*L*c + c**2))
MD = b*w*(-4*L**3*a - 2*L**3*b + 8*L**2*a*c + 4*L**2*a*x + 4*L**2*b*c + 2*L**2*b*x + 4*L*a**3 + 6*L*a**2*b + 4*L*a*b**2 - 4*L*a*c**2 - 8*L*a*c*x + L*b**3 - 2*L*b*c**2 - 4*L*b*c*x - 4*a**3*x - 6*a**2*b*x - 4*a*b**2*x + 4*a*c**2*x - b**3*x + 2*b*c**2*x)/(8*L*c*(L - c))
# Esforços cortantes
VA = b*w*(8*L**3 - 12*L**2*a - 6*L**2*b - 16*L**2*c + 16*L*a*c + 8*L*b*c + 8*L*c**2 + 4*a**3 + 6*a**2*b + 4*a*b**2 - 4*a*c**2 + b**3 - 2*b*c**2)/(8*L*(L**2 - 2*L*c + c**2))
VB = w*(8*L**3*a + 8*L**3*b - 8*L**3*x - 12*L**2*a*b - 16*L**2*a*c - 6*L**2*b**2 - 16*L**2*b*c + 16*L**2*c*x + 16*L*a*b*c + 8*L*a*c**2 + 8*L*b**2*c + 8*L*b*c**2 - 8*L*c**2*x + 4*a**3*b + 6*a**2*b**2 + 4*a*b**3 - 4*a*b*c**2 + b**4 - 2*b**2*c**2)/(8*L*(L**2 - 2*L*c + c**2))
VC = b*w*(-12*L**2*a - 6*L**2*b + 16*L*a*c + 8*L*b*c + 4*a**3 + 6*a**2*b + 4*a*b**2 - 4*a*c**2 + b**3 - 2*b*c**2)/(8*L*(L**2 - 2*L*c + c**2))
VD = b*w*(4*L**2*a + 2*L**2*b - 8*L*a*c - 4*L*b*c - 4*a**3 - 6*a**2*b - 4*a*b**2 + 4*a*c**2 - b**3 + 2*b*c**2)/(8*L*c*(L - c))
# Reações de apoio
R1 = b*w*(8*L**3 - 12*L**2*a - 6*L**2*b - 16*L**2*c + 16*L*a*c + 8*L*b*c + 8*L*c**2 + 4*a**3 + 6*a**2*b + 4*a*b**2 - 4*a*c**2 + b**3 - 2*b*c**2)/(8*L*(L**2 - 2*L*c + c**2))
R2 = b*w*(4*L**2*a + 2*L**2*b - 4*a**3 - 6*a**2*b - 4*a*b**2 - 4*a*c**2 - b**3 - 2*b*c**2)/(8*c*(L**2 - 2*L*c + c**2))
R3 = b*w*(-4*L**2*a - 2*L**2*b + 8*L*a*c + 4*L*b*c + 4*a**3 + 6*a**2*b + 4*a*b**2 - 4*a*c**2 + b**3 - 2*b*c**2)/(8*L*c*(L - c))
```

---

### DV5-wd
- **Descrição:** Viga duplo-vão com carga uniformemente distribuída em parte do vão direito da viga
- **Página offline:** `00. Site Offline/DV5-wd.html`
- **Legenda:**
  - $E$ - módulo de elasticidade do material da viga;
  - $I$ - inércia da seção transversal da viga (em torno no eixo que sai da tela);
  - $L$ - comprimento total da viga;
  - $a$ - comprimento do tramo A;
  - $b$ - comprimento do tramo B;
  - $c$ - comprimento do tramo C;
  - $w$ - carga distribuída uniforme;
  - $x$ - posição em uma parte qualquer de um tramo da viga;

#### Flechas
$$\delta_A = \dfrac{c w x \left(a^{4} - 6 a^{3} x + 13 a^{2} x^{2} - 12 a x^{3} + 6 a x \left(a^{2} - 2 a x + x^{2}\right) + 4 x^{4} + 2 x \left(a^{3} - 5 a^{2} x + 8 a x^{2} - 4 x^{3}\right) - 2 x \left(a^{3} - 4 a^{2} x + 5 a x^{2} - 2 x^{3}\right)\right) \left(8 L^{2} b + 4 L^{2} c - 16 L a b - 8 L a c - 12 L b^{2} - 12 L b c - 4 L c^{2} + 8 a^{2} b + 4 a^{2} c + 12 a b^{2} + 12 a b c + 4 a c^{2} + 4 b^{3} + 6 b^{2} c + 4 b c^{2} + c^{3}\right)}{48 E I L a^{3} \left(L - a\right)}$$

$$\delta_B = \dfrac{c w \left(- 8 L^{3} a^{3} - 8 L^{3} a^{2} b - 4 L^{3} a^{2} c + 24 L^{3} a^{2} x + 32 L^{3} a b x + 16 L^{3} a c x - 24 L^{3} a x^{2} - 24 L^{3} b x^{2} - 12 L^{3} c x^{2} + 8 L^{3} x^{3} + 16 L^{2} a^{4} + 24 L^{2} a^{3} b + 12 L^{2} a^{3} c - 48 L^{2} a^{3} x + 12 L^{2} a^{2} b^{2} + 12 L^{2} a^{2} b c - 96 L^{2} a^{2} b x + 4 L^{2} a^{2} c^{2} - 48 L^{2} a^{2} c x + 48 L^{2} a^{2} x^{2} - 48 L^{2} a b^{2} x - 48 L^{2} a b c x + 72 L^{2} a b x^{2} - 16 L^{2} a c^{2} x + 36 L^{2} a c x^{2} - 16 L^{2} a x^{3} + 36 L^{2} b^{2} x^{2} + 36 L^{2} b c x^{2} + 12 L^{2} c^{2} x^{2} - 8 L a^{5} - 16 L a^{4} b - 8 L a^{4} c + 24 L a^{4} x - 12 L a^{3} b^{2} - 12 L a^{3} b c + 72 L a^{3} b x - 4 L a^{3} c^{2} + 36 L a^{3} c x - 24 L a^{3} x^{2} - 4 L a^{2} b^{3} - 6 L a^{2} b^{2} c + 60 L a^{2} b^{2} x - 4 L a^{2} b c^{2} + 60 L a^{2} b c x - 48 L a^{2} b x^{2} - L a^{2} c^{3} + 20 L a^{2} c^{2} x - 24 L a^{2} c x^{2} + 8 L a^{2} x^{3} + 16 L a b^{3} x + 24 L a b^{2} c x - 36 L a b^{2} x^{2} + 16 L a b c^{2} x - 36 L a b c x^{2} - 8 L a b x^{3} + 4 L a c^{3} x - 12 L a c^{2} x^{2} - 4 L a c x^{3} - 12 L b^{3} x^{2} - 18 L b^{2} c x^{2} - 12 L b^{2} x^{3} - 12 L b c^{2} x^{2} - 12 L b c x^{3} - 3 L c^{3} x^{2} - 4 L c^{2} x^{3} - 8 a^{4} b x - 4 a^{4} c x - 12 a^{3} b^{2} x - 12 a^{3} b c x - 4 a^{3} c^{2} x - 4 a^{2} b^{3} x - 6 a^{2} b^{2} c x - 4 a^{2} b c^{2} x + 8 a^{2} b x^{3} - a^{2} c^{3} x + 4 a^{2} c x^{3} + 12 a b^{2} x^{3} + 12 a b c x^{3} + 4 a c^{2} x^{3} + 4 b^{3} x^{3} + 6 b^{2} c x^{3} + 4 b c^{2} x^{3} + c^{3} x^{3}\right)}{48 E I L \left(L^{2} - 2 L a + a^{2}\right)}$$

$$\delta_C = \dfrac{w \left(- 2 L^{3} a^{4} - 8 L^{3} a^{3} b - 8 L^{3} a^{3} c + 8 L^{3} a^{3} x - 12 L^{3} a^{2} b^{2} - 8 L^{3} a^{2} b c + 24 L^{3} a^{2} b x - 4 L^{3} a^{2} c^{2} + 24 L^{3} a^{2} c x - 12 L^{3} a^{2} x^{2} - 8 L^{3} a b^{3} + 24 L^{3} a b^{2} x + 32 L^{3} a b c x - 24 L^{3} a b x^{2} + 16 L^{3} a c^{2} x - 24 L^{3} a c x^{2} + 8 L^{3} a x^{3} - 2 L^{3} b^{4} + 8 L^{3} b^{3} x - 12 L^{3} b^{2} x^{2} - 24 L^{3} b c x^{2} + 8 L^{3} b x^{3} - 12 L^{3} c^{2} x^{2} + 8 L^{3} c x^{3} - 2 L^{3} x^{4} + 4 L^{2} a^{5} + 16 L^{2} a^{4} b + 16 L^{2} a^{4} c - 16 L^{2} a^{4} x + 24 L^{2} a^{3} b^{2} + 24 L^{2} a^{3} b c - 48 L^{2} a^{3} b x + 12 L^{2} a^{3} c^{2} - 48 L^{2} a^{3} c x + 24 L^{2} a^{3} x^{2} + 16 L^{2} a^{2} b^{3} + 12 L^{2} a^{2} b^{2} c - 48 L^{2} a^{2} b^{2} x + 12 L^{2} a^{2} b c^{2} - 96 L^{2} a^{2} b c x + 48 L^{2} a^{2} b x^{2} + 4 L^{2} a^{2} c^{3} - 48 L^{2} a^{2} c^{2} x + 48 L^{2} a^{2} c x^{2} - 16 L^{2} a^{2} x^{3} + 4 L^{2} a b^{4} - 16 L^{2} a b^{3} x - 48 L^{2} a b^{2} c x + 24 L^{2} a b^{2} x^{2} - 48 L^{2} a b c^{2} x + 72 L^{2} a b c x^{2} - 16 L^{2} a b x^{3} - 16 L^{2} a c^{3} x + 36 L^{2} a c^{2} x^{2} - 16 L^{2} a c x^{3} + 4 L^{2} a x^{4} + 36 L^{2} b^{2} c x^{2} + 36 L^{2} b c^{2} x^{2} + 12 L^{2} c^{3} x^{2} - 2 L a^{6} - 8 L a^{5} b - 8 L a^{5} c + 8 L a^{5} x - 12 L a^{4} b^{2} - 16 L a^{4} b c + 24 L a^{4} b x - 8 L a^{4} c^{2} + 24 L a^{4} c x - 12 L a^{4} x^{2} - 8 L a^{3} b^{3} - 12 L a^{3} b^{2} c + 24 L a^{3} b^{2} x - 12 L a^{3} b c^{2} + 72 L a^{3} b c x - 24 L a^{3} b x^{2} - 4 L a^{3} c^{3} + 36 L a^{3} c^{2} x - 24 L a^{3} c x^{2} + 8 L a^{3} x^{3} - 2 L a^{2} b^{4} - 4 L a^{2} b^{3} c + 8 L a^{2} b^{3} x - 6 L a^{2} b^{2} c^{2} + 60 L a^{2} b^{2} c x - 12 L a^{2} b^{2} x^{2} - 4 L a^{2} b c^{3} + 60 L a^{2} b c^{2} x - 48 L a^{2} b c x^{2} + 8 L a^{2} b x^{3} - L a^{2} c^{4} + 20 L a^{2} c^{3} x - 24 L a^{2} c^{2} x^{2} + 8 L a^{2} c x^{3} - 2 L a^{2} x^{4} + 16 L a b^{3} c x + 24 L a b^{2} c^{2} x - 36 L a b^{2} c x^{2} + 16 L a b c^{3} x - 36 L a b c^{2} x^{2} - 8 L a b c x^{3} + 4 L a c^{4} x - 12 L a c^{3} x^{2} - 4 L a c^{2} x^{3} - 12 L b^{3} c x^{2} - 18 L b^{2} c^{2} x^{2} - 12 L b^{2} c x^{3} - 12 L b c^{3} x^{2} - 12 L b c^{2} x^{3} - 3 L c^{4} x^{2} - 4 L c^{3} x^{3} - 8 a^{4} b c x - 4 a^{4} c^{2} x - 12 a^{3} b^{2} c x - 12 a^{3} b c^{2} x - 4 a^{3} c^{3} x - 4 a^{2} b^{3} c x - 6 a^{2} b^{2} c^{2} x - 4 a^{2} b c^{3} x + 8 a^{2} b c x^{3} - a^{2} c^{4} x + 4 a^{2} c^{2} x^{3} + 12 a b^{2} c x^{3} + 12 a b c^{2} x^{3} + 4 a c^{3} x^{3} + 4 b^{3} c x^{3} + 6 b^{2} c^{2} x^{3} + 4 b c^{3} x^{3} + c^{4} x^{3}\right)}{48 E I L \left(L^{2} - 2 L a + a^{2}\right)}$$

$$\delta_D = \dfrac{c w \left(16 L^{3} a^{2} b + 8 L^{3} a^{2} c + 24 L^{3} a b^{2} + 24 L^{3} a b c - 16 L^{3} a b x + 8 L^{3} a c^{2} - 8 L^{3} a c x + 8 L^{3} b^{3} + 12 L^{3} b^{2} c - 24 L^{3} b^{2} x + 8 L^{3} b c^{2} - 24 L^{3} b c x + 2 L^{3} c^{3} - 8 L^{3} c^{2} x - 24 L^{2} a^{3} b - 12 L^{2} a^{3} c - 36 L^{2} a^{2} b^{2} - 36 L^{2} a^{2} b c - 12 L^{2} a^{2} c^{2} - 16 L^{2} a b^{3} - 24 L^{2} a b^{2} c - 16 L^{2} a b c^{2} + 24 L^{2} a b x^{2} - 4 L^{2} a c^{3} + 12 L^{2} a c x^{2} + 36 L^{2} b^{2} x^{2} + 36 L^{2} b c x^{2} + 12 L^{2} c^{2} x^{2} + 8 L a^{4} b + 4 L a^{4} c + 12 L a^{3} b^{2} + 12 L a^{3} b c + 24 L a^{3} b x + 4 L a^{3} c^{2} + 12 L a^{3} c x + 4 L a^{2} b^{3} + 6 L a^{2} b^{2} c + 36 L a^{2} b^{2} x + 4 L a^{2} b c^{2} + 36 L a^{2} b c x - 24 L a^{2} b x^{2} + L a^{2} c^{3} + 12 L a^{2} c^{2} x - 12 L a^{2} c x^{2} + 16 L a b^{3} x + 24 L a b^{2} c x - 36 L a b^{2} x^{2} + 16 L a b c^{2} x - 36 L a b c x^{2} - 8 L a b x^{3} + 4 L a c^{3} x - 12 L a c^{2} x^{2} - 4 L a c x^{3} - 12 L b^{3} x^{2} - 18 L b^{2} c x^{2} - 12 L b^{2} x^{3} - 12 L b c^{2} x^{2} - 12 L b c x^{3} - 3 L c^{3} x^{2} - 4 L c^{2} x^{3} - 8 a^{4} b x - 4 a^{4} c x - 12 a^{3} b^{2} x - 12 a^{3} b c x - 4 a^{3} c^{2} x - 4 a^{2} b^{3} x - 6 a^{2} b^{2} c x - 4 a^{2} b c^{2} x + 8 a^{2} b x^{3} - a^{2} c^{3} x + 4 a^{2} c x^{3} + 12 a b^{2} x^{3} + 12 a b c x^{3} + 4 a c^{2} x^{3} + 4 b^{3} x^{3} + 6 b^{2} c x^{3} + 4 b c^{2} x^{3} + c^{3} x^{3}\right)}{48 E I L \left(L^{2} - 2 L a + a^{2}\right)}$$

#### Momentos fletores
$$M_A = \dfrac{c w x \left(8 L^{2} b + 4 L^{2} c - 16 L a b - 8 L a c - 12 L b^{2} - 12 L b c - 4 L c^{2} + 8 a^{2} b + 4 a^{2} c + 12 a b^{2} + 12 a b c + 4 a c^{2} + 4 b^{3} + 6 b^{2} c + 4 b c^{2} + c^{3}\right)}{8 L a \left(- L + a\right)}$$

$$M_B = \dfrac{c w \left(- 8 L^{3} a - 8 L^{3} b - 4 L^{3} c + 8 L^{3} x + 16 L^{2} a^{2} + 24 L^{2} a b + 12 L^{2} a c - 16 L^{2} a x + 12 L^{2} b^{2} + 12 L^{2} b c + 4 L^{2} c^{2} - 8 L a^{3} - 16 L a^{2} b - 8 L a^{2} c + 8 L a^{2} x - 12 L a b^{2} - 12 L a b c - 8 L a b x - 4 L a c^{2} - 4 L a c x - 4 L b^{3} - 6 L b^{2} c - 12 L b^{2} x - 4 L b c^{2} - 12 L b c x - L c^{3} - 4 L c^{2} x + 8 a^{2} b x + 4 a^{2} c x + 12 a b^{2} x + 12 a b c x + 4 a c^{2} x + 4 b^{3} x + 6 b^{2} c x + 4 b c^{2} x + c^{3} x\right)}{8 L \left(L^{2} - 2 L a + a^{2}\right)}$$

$$M_C = \dfrac{w \left(- 4 L^{3} a^{2} - 8 L^{3} a b - 8 L^{3} a c + 8 L^{3} a x - 4 L^{3} b^{2} - 8 L^{3} b c + 8 L^{3} b x - 4 L^{3} c^{2} + 8 L^{3} c x - 4 L^{3} x^{2} + 8 L^{2} a^{3} + 16 L^{2} a^{2} b + 16 L^{2} a^{2} c - 16 L^{2} a^{2} x + 8 L^{2} a b^{2} + 24 L^{2} a b c - 16 L^{2} a b x + 12 L^{2} a c^{2} - 16 L^{2} a c x + 8 L^{2} a x^{2} + 12 L^{2} b^{2} c + 12 L^{2} b c^{2} + 4 L^{2} c^{3} - 4 L a^{4} - 8 L a^{3} b - 8 L a^{3} c + 8 L a^{3} x - 4 L a^{2} b^{2} - 16 L a^{2} b c + 8 L a^{2} b x - 8 L a^{2} c^{2} + 8 L a^{2} c x - 4 L a^{2} x^{2} - 12 L a b^{2} c - 12 L a b c^{2} - 8 L a b c x - 4 L a c^{3} - 4 L a c^{2} x - 4 L b^{3} c - 6 L b^{2} c^{2} - 12 L b^{2} c x - 4 L b c^{3} - 12 L b c^{2} x - L c^{4} - 4 L c^{3} x + 8 a^{2} b c x + 4 a^{2} c^{2} x + 12 a b^{2} c x + 12 a b c^{2} x + 4 a c^{3} x + 4 b^{3} c x + 6 b^{2} c^{2} x + 4 b c^{3} x + c^{4} x\right)}{8 L \left(L^{2} - 2 L a + a^{2}\right)}$$

$$M_D = \dfrac{c w \left(8 L^{2} a b + 4 L^{2} a c + 12 L^{2} b^{2} + 12 L^{2} b c + 4 L^{2} c^{2} - 8 L a^{2} b - 4 L a^{2} c - 12 L a b^{2} - 12 L a b c - 8 L a b x - 4 L a c^{2} - 4 L a c x - 4 L b^{3} - 6 L b^{2} c - 12 L b^{2} x - 4 L b c^{2} - 12 L b c x - L c^{3} - 4 L c^{2} x + 8 a^{2} b x + 4 a^{2} c x + 12 a b^{2} x + 12 a b c x + 4 a c^{2} x + 4 b^{3} x + 6 b^{2} c x + 4 b c^{2} x + c^{3} x\right)}{8 L \left(L^{2} - 2 L a + a^{2}\right)}$$

#### Esforços cortantes
$$V_A = \dfrac{c w \left(8 L^{2} b + 4 L^{2} c - 16 L a b - 8 L a c - 12 L b^{2} - 12 L b c - 4 L c^{2} + 8 a^{2} b + 4 a^{2} c + 12 a b^{2} + 12 a b c + 4 a c^{2} + 4 b^{3} + 6 b^{2} c + 4 b c^{2} + c^{3}\right)}{8 L a \left(- L + a\right)}$$

$$V_B = \dfrac{c w \left(8 L^{3} - 16 L^{2} a + 8 L a^{2} - 8 L a b - 4 L a c - 12 L b^{2} - 12 L b c - 4 L c^{2} + 8 a^{2} b + 4 a^{2} c + 12 a b^{2} + 12 a b c + 4 a c^{2} + 4 b^{3} + 6 b^{2} c + 4 b c^{2} + c^{3}\right)}{8 L \left(L^{2} - 2 L a + a^{2}\right)}$$

$$V_C = \dfrac{w \left(8 L^{3} a + 8 L^{3} b + 8 L^{3} c - 8 L^{3} x - 16 L^{2} a^{2} - 16 L^{2} a b - 16 L^{2} a c + 16 L^{2} a x + 8 L a^{3} + 8 L a^{2} b + 8 L a^{2} c - 8 L a^{2} x - 8 L a b c - 4 L a c^{2} - 12 L b^{2} c - 12 L b c^{2} - 4 L c^{3} + 8 a^{2} b c + 4 a^{2} c^{2} + 12 a b^{2} c + 12 a b c^{2} + 4 a c^{3} + 4 b^{3} c + 6 b^{2} c^{2} + 4 b c^{3} + c^{4}\right)}{8 L \left(L^{2} - 2 L a + a^{2}\right)}$$

$$V_D = \dfrac{c w \left(- 8 L a b - 4 L a c - 12 L b^{2} - 12 L b c - 4 L c^{2} + 8 a^{2} b + 4 a^{2} c + 12 a b^{2} + 12 a b c + 4 a c^{2} + 4 b^{3} + 6 b^{2} c + 4 b c^{2} + c^{3}\right)}{8 L \left(L^{2} - 2 L a + a^{2}\right)}$$

#### Reações de apoio
$$R_1 = \dfrac{c w \left(8 L^{2} b + 4 L^{2} c - 16 L a b - 8 L a c - 12 L b^{2} - 12 L b c - 4 L c^{2} + 8 a^{2} b + 4 a^{2} c + 12 a b^{2} + 12 a b c + 4 a c^{2} + 4 b^{3} + 6 b^{2} c + 4 b c^{2} + c^{3}\right)}{8 L a \left(- L + a\right)}$$

$$R_2 = \dfrac{c w \left(8 L^{2} a + 8 L^{2} b + 4 L^{2} c - 16 L a^{2} - 24 L a b - 12 L a c - 12 L b^{2} - 12 L b c - 4 L c^{2} + 8 a^{3} + 16 a^{2} b + 8 a^{2} c + 12 a b^{2} + 12 a b c + 4 a c^{2} + 4 b^{3} + 6 b^{2} c + 4 b c^{2} + c^{3}\right)}{8 a \left(L^{2} - 2 L a + a^{2}\right)}$$

$$R_3 = \dfrac{c w \left(8 L a b + 4 L a c + 12 L b^{2} + 12 L b c + 4 L c^{2} - 8 a^{2} b - 4 a^{2} c - 12 a b^{2} - 12 a b c - 4 a c^{2} - 4 b^{3} - 6 b^{2} c - 4 b c^{2} - c^{3}\right)}{8 L \left(L^{2} - 2 L a + a^{2}\right)}$$

#### Equações em Python
```python
# Flechas
deltaA = c*w*x*(a**4 - 6*a**3*x + 13*a**2*x**2 - 12*a*x**3 + 6*a*x*(a**2 - 2*a*x + x**2) + 4*x**4 + 2*x*(a**3 - 5*a**2*x + 8*a*x**2 - 4*x**3) - 2*x*(a**3 - 4*a**2*x + 5*a*x**2 - 2*x**3))*(8*L**2*b + 4*L**2*c - 16*L*a*b - 8*L*a*c - 12*L*b**2 - 12*L*b*c - 4*L*c**2 + 8*a**2*b + 4*a**2*c + 12*a*b**2 + 12*a*b*c + 4*a*c**2 + 4*b**3 + 6*b**2*c + 4*b*c**2 + c**3)/(48*E*I*L*a**3*(L - a))
deltaB = c*w*(-8*L**3*a**3 - 8*L**3*a**2*b - 4*L**3*a**2*c + 24*L**3*a**2*x + 32*L**3*a*b*x + 16*L**3*a*c*x - 24*L**3*a*x**2 - 24*L**3*b*x**2 - 12*L**3*c*x**2 + 8*L**3*x**3 + 16*L**2*a**4 + 24*L**2*a**3*b + 12*L**2*a**3*c - 48*L**2*a**3*x + 12*L**2*a**2*b**2 + 12*L**2*a**2*b*c - 96*L**2*a**2*b*x + 4*L**2*a**2*c**2 - 48*L**2*a**2*c*x + 48*L**2*a**2*x**2 - 48*L**2*a*b**2*x - 48*L**2*a*b*c*x + 72*L**2*a*b*x**2 - 16*L**2*a*c**2*x + 36*L**2*a*c*x**2 - 16*L**2*a*x**3 + 36*L**2*b**2*x**2 + 36*L**2*b*c*x**2 + 12*L**2*c**2*x**2 - 8*L*a**5 - 16*L*a**4*b - 8*L*a**4*c + 24*L*a**4*x - 12*L*a**3*b**2 - 12*L*a**3*b*c + 72*L*a**3*b*x - 4*L*a**3*c**2 + 36*L*a**3*c*x - 24*L*a**3*x**2 - 4*L*a**2*b**3 - 6*L*a**2*b**2*c + 60*L*a**2*b**2*x - 4*L*a**2*b*c**2 + 60*L*a**2*b*c*x - 48*L*a**2*b*x**2 - L*a**2*c**3 + 20*L*a**2*c**2*x - 24*L*a**2*c*x**2 + 8*L*a**2*x**3 + 16*L*a*b**3*x + 24*L*a*b**2*c*x - 36*L*a*b**2*x**2 + 16*L*a*b*c**2*x - 36*L*a*b*c*x**2 - 8*L*a*b*x**3 + 4*L*a*c**3*x - 12*L*a*c**2*x**2 - 4*L*a*c*x**3 - 12*L*b**3*x**2 - 18*L*b**2*c*x**2 - 12*L*b**2*x**3 - 12*L*b*c**2*x**2 - 12*L*b*c*x**3 - 3*L*c**3*x**2 - 4*L*c**2*x**3 - 8*a**4*b*x - 4*a**4*c*x - 12*a**3*b**2*x - 12*a**3*b*c*x - 4*a**3*c**2*x - 4*a**2*b**3*x - 6*a**2*b**2*c*x - 4*a**2*b*c**2*x + 8*a**2*b*x**3 - a**2*c**3*x + 4*a**2*c*x**3 + 12*a*b**2*x**3 + 12*a*b*c*x**3 + 4*a*c**2*x**3 + 4*b**3*x**3 + 6*b**2*c*x**3 + 4*b*c**2*x**3 + c**3*x**3)/(48*E*I*L*(L**2 - 2*L*a + a**2))
deltaC = w*(-2*L**3*a**4 - 8*L**3*a**3*b - 8*L**3*a**3*c + 8*L**3*a**3*x - 12*L**3*a**2*b**2 - 8*L**3*a**2*b*c + 24*L**3*a**2*b*x - 4*L**3*a**2*c**2 + 24*L**3*a**2*c*x - 12*L**3*a**2*x**2 - 8*L**3*a*b**3 + 24*L**3*a*b**2*x + 32*L**3*a*b*c*x - 24*L**3*a*b*x**2 + 16*L**3*a*c**2*x - 24*L**3*a*c*x**2 + 8*L**3*a*x**3 - 2*L**3*b**4 + 8*L**3*b**3*x - 12*L**3*b**2*x**2 - 24*L**3*b*c*x**2 + 8*L**3*b*x**3 - 12*L**3*c**2*x**2 + 8*L**3*c*x**3 - 2*L**3*x**4 + 4*L**2*a**5 + 16*L**2*a**4*b + 16*L**2*a**4*c - 16*L**2*a**4*x + 24*L**2*a**3*b**2 + 24*L**2*a**3*b*c - 48*L**2*a**3*b*x + 12*L**2*a**3*c**2 - 48*L**2*a**3*c*x + 24*L**2*a**3*x**2 + 16*L**2*a**2*b**3 + 12*L**2*a**2*b**2*c - 48*L**2*a**2*b**2*x + 12*L**2*a**2*b*c**2 - 96*L**2*a**2*b*c*x + 48*L**2*a**2*b*x**2 + 4*L**2*a**2*c**3 - 48*L**2*a**2*c**2*x + 48*L**2*a**2*c*x**2 - 16*L**2*a**2*x**3 + 4*L**2*a*b**4 - 16*L**2*a*b**3*x - 48*L**2*a*b**2*c*x + 24*L**2*a*b**2*x**2 - 48*L**2*a*b*c**2*x + 72*L**2*a*b*c*x**2 - 16*L**2*a*b*x**3 - 16*L**2*a*c**3*x + 36*L**2*a*c**2*x**2 - 16*L**2*a*c*x**3 + 4*L**2*a*x**4 + 36*L**2*b**2*c*x**2 + 36*L**2*b*c**2*x**2 + 12*L**2*c**3*x**2 - 2*L*a**6 - 8*L*a**5*b - 8*L*a**5*c + 8*L*a**5*x - 12*L*a**4*b**2 - 16*L*a**4*b*c + 24*L*a**4*b*x - 8*L*a**4*c**2 + 24*L*a**4*c*x - 12*L*a**4*x**2 - 8*L*a**3*b**3 - 12*L*a**3*b**2*c + 24*L*a**3*b**2*x - 12*L*a**3*b*c**2 + 72*L*a**3*b*c*x - 24*L*a**3*b*x**2 - 4*L*a**3*c**3 + 36*L*a**3*c**2*x - 24*L*a**3*c*x**2 + 8*L*a**3*x**3 - 2*L*a**2*b**4 - 4*L*a**2*b**3*c + 8*L*a**2*b**3*x - 6*L*a**2*b**2*c**2 + 60*L*a**2*b**2*c*x - 12*L*a**2*b**2*x**2 - 4*L*a**2*b*c**3 + 60*L*a**2*b*c**2*x - 48*L*a**2*b*c*x**2 + 8*L*a**2*b*x**3 - L*a**2*c**4 + 20*L*a**2*c**3*x - 24*L*a**2*c**2*x**2 + 8*L*a**2*c*x**3 - 2*L*a**2*x**4 + 16*L*a*b**3*c*x + 24*L*a*b**2*c**2*x - 36*L*a*b**2*c*x**2 + 16*L*a*b*c**3*x - 36*L*a*b*c**2*x**2 - 8*L*a*b*c*x**3 + 4*L*a*c**4*x - 12*L*a*c**3*x**2 - 4*L*a*c**2*x**3 - 12*L*b**3*c*x**2 - 18*L*b**2*c**2*x**2 - 12*L*b**2*c*x**3 - 12*L*b*c**3*x**2 - 12*L*b*c**2*x**3 - 3*L*c**4*x**2 - 4*L*c**3*x**3 - 8*a**4*b*c*x - 4*a**4*c**2*x - 12*a**3*b**2*c*x - 12*a**3*b*c**2*x - 4*a**3*c**3*x - 4*a**2*b**3*c*x - 6*a**2*b**2*c**2*x - 4*a**2*b*c**3*x + 8*a**2*b*c*x**3 - a**2*c**4*x + 4*a**2*c**2*x**3 + 12*a*b**2*c*x**3 + 12*a*b*c**2*x**3 + 4*a*c**3*x**3 + 4*b**3*c*x**3 + 6*b**2*c**2*x**3 + 4*b*c**3*x**3 + c**4*x**3)/(48*E*I*L*(L**2 - 2*L*a + a**2))
deltaD = c*w*(16*L**3*a**2*b + 8*L**3*a**2*c + 24*L**3*a*b**2 + 24*L**3*a*b*c - 16*L**3*a*b*x + 8*L**3*a*c**2 - 8*L**3*a*c*x + 8*L**3*b**3 + 12*L**3*b**2*c - 24*L**3*b**2*x + 8*L**3*b*c**2 - 24*L**3*b*c*x + 2*L**3*c**3 - 8*L**3*c**2*x - 24*L**2*a**3*b - 12*L**2*a**3*c - 36*L**2*a**2*b**2 - 36*L**2*a**2*b*c - 12*L**2*a**2*c**2 - 16*L**2*a*b**3 - 24*L**2*a*b**2*c - 16*L**2*a*b*c**2 + 24*L**2*a*b*x**2 - 4*L**2*a*c**3 + 12*L**2*a*c*x**2 + 36*L**2*b**2*x**2 + 36*L**2*b*c*x**2 + 12*L**2*c**2*x**2 + 8*L*a**4*b + 4*L*a**4*c + 12*L*a**3*b**2 + 12*L*a**3*b*c + 24*L*a**3*b*x + 4*L*a**3*c**2 + 12*L*a**3*c*x + 4*L*a**2*b**3 + 6*L*a**2*b**2*c + 36*L*a**2*b**2*x + 4*L*a**2*b*c**2 + 36*L*a**2*b*c*x - 24*L*a**2*b*x**2 + L*a**2*c**3 + 12*L*a**2*c**2*x - 12*L*a**2*c*x**2 + 16*L*a*b**3*x + 24*L*a*b**2*c*x - 36*L*a*b**2*x**2 + 16*L*a*b*c**2*x - 36*L*a*b*c*x**2 - 8*L*a*b*x**3 + 4*L*a*c**3*x - 12*L*a*c**2*x**2 - 4*L*a*c*x**3 - 12*L*b**3*x**2 - 18*L*b**2*c*x**2 - 12*L*b**2*x**3 - 12*L*b*c**2*x**2 - 12*L*b*c*x**3 - 3*L*c**3*x**2 - 4*L*c**2*x**3 - 8*a**4*b*x - 4*a**4*c*x - 12*a**3*b**2*x - 12*a**3*b*c*x - 4*a**3*c**2*x - 4*a**2*b**3*x - 6*a**2*b**2*c*x - 4*a**2*b*c**2*x + 8*a**2*b*x**3 - a**2*c**3*x + 4*a**2*c*x**3 + 12*a*b**2*x**3 + 12*a*b*c*x**3 + 4*a*c**2*x**3 + 4*b**3*x**3 + 6*b**2*c*x**3 + 4*b*c**2*x**3 + c**3*x**3)/(48*E*I*L*(L**2 - 2*L*a + a**2))
# Momentos fletores
MA = c*w*x*(8*L**2*b + 4*L**2*c - 16*L*a*b - 8*L*a*c - 12*L*b**2 - 12*L*b*c - 4*L*c**2 + 8*a**2*b + 4*a**2*c + 12*a*b**2 + 12*a*b*c + 4*a*c**2 + 4*b**3 + 6*b**2*c + 4*b*c**2 + c**3)/(8*L*a*(-L + a))
MB = c*w*(-8*L**3*a - 8*L**3*b - 4*L**3*c + 8*L**3*x + 16*L**2*a**2 + 24*L**2*a*b + 12*L**2*a*c - 16*L**2*a*x + 12*L**2*b**2 + 12*L**2*b*c + 4*L**2*c**2 - 8*L*a**3 - 16*L*a**2*b - 8*L*a**2*c + 8*L*a**2*x - 12*L*a*b**2 - 12*L*a*b*c - 8*L*a*b*x - 4*L*a*c**2 - 4*L*a*c*x - 4*L*b**3 - 6*L*b**2*c - 12*L*b**2*x - 4*L*b*c**2 - 12*L*b*c*x - L*c**3 - 4*L*c**2*x + 8*a**2*b*x + 4*a**2*c*x + 12*a*b**2*x + 12*a*b*c*x + 4*a*c**2*x + 4*b**3*x + 6*b**2*c*x + 4*b*c**2*x + c**3*x)/(8*L*(L**2 - 2*L*a + a**2))
MC = w*(-4*L**3*a**2 - 8*L**3*a*b - 8*L**3*a*c + 8*L**3*a*x - 4*L**3*b**2 - 8*L**3*b*c + 8*L**3*b*x - 4*L**3*c**2 + 8*L**3*c*x - 4*L**3*x**2 + 8*L**2*a**3 + 16*L**2*a**2*b + 16*L**2*a**2*c - 16*L**2*a**2*x + 8*L**2*a*b**2 + 24*L**2*a*b*c - 16*L**2*a*b*x + 12*L**2*a*c**2 - 16*L**2*a*c*x + 8*L**2*a*x**2 + 12*L**2*b**2*c + 12*L**2*b*c**2 + 4*L**2*c**3 - 4*L*a**4 - 8*L*a**3*b - 8*L*a**3*c + 8*L*a**3*x - 4*L*a**2*b**2 - 16*L*a**2*b*c + 8*L*a**2*b*x - 8*L*a**2*c**2 + 8*L*a**2*c*x - 4*L*a**2*x**2 - 12*L*a*b**2*c - 12*L*a*b*c**2 - 8*L*a*b*c*x - 4*L*a*c**3 - 4*L*a*c**2*x - 4*L*b**3*c - 6*L*b**2*c**2 - 12*L*b**2*c*x - 4*L*b*c**3 - 12*L*b*c**2*x - L*c**4 - 4*L*c**3*x + 8*a**2*b*c*x + 4*a**2*c**2*x + 12*a*b**2*c*x + 12*a*b*c**2*x + 4*a*c**3*x + 4*b**3*c*x + 6*b**2*c**2*x + 4*b*c**3*x + c**4*x)/(8*L*(L**2 - 2*L*a + a**2))
MD = c*w*(8*L**2*a*b + 4*L**2*a*c + 12*L**2*b**2 + 12*L**2*b*c + 4*L**2*c**2 - 8*L*a**2*b - 4*L*a**2*c - 12*L*a*b**2 - 12*L*a*b*c - 8*L*a*b*x - 4*L*a*c**2 - 4*L*a*c*x - 4*L*b**3 - 6*L*b**2*c - 12*L*b**2*x - 4*L*b*c**2 - 12*L*b*c*x - L*c**3 - 4*L*c**2*x + 8*a**2*b*x + 4*a**2*c*x + 12*a*b**2*x + 12*a*b*c*x + 4*a*c**2*x + 4*b**3*x + 6*b**2*c*x + 4*b*c**2*x + c**3*x)/(8*L*(L**2 - 2*L*a + a**2))
# Esforços cortantes
VA = c*w*(8*L**2*b + 4*L**2*c - 16*L*a*b - 8*L*a*c - 12*L*b**2 - 12*L*b*c - 4*L*c**2 + 8*a**2*b + 4*a**2*c + 12*a*b**2 + 12*a*b*c + 4*a*c**2 + 4*b**3 + 6*b**2*c + 4*b*c**2 + c**3)/(8*L*a*(-L + a))
VB = c*w*(8*L**3 - 16*L**2*a + 8*L*a**2 - 8*L*a*b - 4*L*a*c - 12*L*b**2 - 12*L*b*c - 4*L*c**2 + 8*a**2*b + 4*a**2*c + 12*a*b**2 + 12*a*b*c + 4*a*c**2 + 4*b**3 + 6*b**2*c + 4*b*c**2 + c**3)/(8*L*(L**2 - 2*L*a + a**2))
VC = w*(8*L**3*a + 8*L**3*b + 8*L**3*c - 8*L**3*x - 16*L**2*a**2 - 16*L**2*a*b - 16*L**2*a*c + 16*L**2*a*x + 8*L*a**3 + 8*L*a**2*b + 8*L*a**2*c - 8*L*a**2*x - 8*L*a*b*c - 4*L*a*c**2 - 12*L*b**2*c - 12*L*b*c**2 - 4*L*c**3 + 8*a**2*b*c + 4*a**2*c**2 + 12*a*b**2*c + 12*a*b*c**2 + 4*a*c**3 + 4*b**3*c + 6*b**2*c**2 + 4*b*c**3 + c**4)/(8*L*(L**2 - 2*L*a + a**2))
VD = c*w*(-8*L*a*b - 4*L*a*c - 12*L*b**2 - 12*L*b*c - 4*L*c**2 + 8*a**2*b + 4*a**2*c + 12*a*b**2 + 12*a*b*c + 4*a*c**2 + 4*b**3 + 6*b**2*c + 4*b*c**2 + c**3)/(8*L*(L**2 - 2*L*a + a**2))
# Reações de apoio
R1 = c*w*(8*L**2*b + 4*L**2*c - 16*L*a*b - 8*L*a*c - 12*L*b**2 - 12*L*b*c - 4*L*c**2 + 8*a**2*b + 4*a**2*c + 12*a*b**2 + 12*a*b*c + 4*a*c**2 + 4*b**3 + 6*b**2*c + 4*b*c**2 + c**3)/(8*L*a*(-L + a))
R2 = c*w*(8*L**2*a + 8*L**2*b + 4*L**2*c - 16*L*a**2 - 24*L*a*b - 12*L*a*c - 12*L*b**2 - 12*L*b*c - 4*L*c**2 + 8*a**3 + 16*a**2*b + 8*a**2*c + 12*a*b**2 + 12*a*b*c + 4*a*c**2 + 4*b**3 + 6*b**2*c + 4*b*c**2 + c**3)/(8*a*(L**2 - 2*L*a + a**2))
R3 = c*w*(8*L*a*b + 4*L*a*c + 12*L*b**2 + 12*L*b*c + 4*L*c**2 - 8*a**2*b - 4*a**2*c - 12*a*b**2 - 12*a*b*c - 4*a*c**2 - 4*b**3 - 6*b**2*c - 4*b*c**2 - c**3)/(8*L*(L**2 - 2*L*a + a**2))
```

---

### DV6-fe
- **Descrição:** Viga duplo-vão com carga concentrada no vão da esquerda
- **Página offline:** `00. Site Offline/DV6-fe.html`
- **Legenda:**
  - $E$ - módulo de elasticidade do material da viga;
  - $F$ - carga concentrada;
  - $I$ - inércia da seção transversal da viga (em torno no eixo que sai da tela);
  - $L$ - comprimento total da viga;
  - $a$ - comprimento do tramo A;
  - $b$ - comprimento do tramo B;
  - $x$ - posição em uma parte qualquer de um tramo da viga;

#### Flechas
$$\delta_A = \dfrac{F x \left(- 3 L^{4} a + 6 L^{3} a^{2} + 8 L^{3} a b + 2 L^{3} x^{2} - 3 L^{2} a^{3} - 12 L^{2} a^{2} b - 6 L^{2} a b^{2} - 3 L^{2} a x^{2} - 4 L^{2} b x^{2} + 4 L a^{3} b + 6 L a^{2} b^{2} + 4 L a b x^{2} + 2 L b^{2} x^{2} - a^{3} b^{2} + a^{3} x^{2} + a b^{4} - a b^{2} x^{2}\right)}{12 E I L \left(L^{2} - 2 L b + b^{2}\right)}$$

$$\delta_B = \dfrac{F a \left(- 3 L^{4} x + 2 L^{3} a^{2} + 8 L^{3} b x + 6 L^{3} x^{2} - 4 L^{2} a^{2} b - 3 L^{2} a^{2} x - 6 L^{2} b^{2} x - 12 L^{2} b x^{2} - 3 L^{2} x^{3} + 2 L a^{2} b^{2} + 4 L a^{2} b x + 6 L b^{2} x^{2} + 4 L b x^{3} - a^{2} b^{2} x + a^{2} x^{3} + b^{4} x - b^{2} x^{3}\right)}{12 E I L \left(L^{2} - 2 L b + b^{2}\right)}$$

$$\delta_C = \dfrac{F a \left(- L^{5} + 2 L^{4} b + 3 L^{4} x + L^{3} a^{2} - 6 L^{3} b x - 3 L^{3} x^{2} - 3 L^{2} a^{2} x - 2 L^{2} b^{3} + 2 L^{2} b^{2} x + 6 L^{2} b x^{2} + L^{2} x^{3} - L a^{2} b^{2} + 3 L a^{2} x^{2} + L b^{4} + 2 L b^{3} x - 3 L b^{2} x^{2} - 2 L b x^{3} + a^{2} b^{2} x - a^{2} x^{3} - b^{4} x + b^{2} x^{3}\right)}{12 E I L b \left(L - b\right)}$$

#### Momentos fletores
$$M_A = \dfrac{F x \left(2 L^{3} - 3 L^{2} a - 4 L^{2} b + 4 L a b + 2 L b^{2} + a^{3} - a b^{2}\right)}{2 L \left(L^{2} - 2 L b + b^{2}\right)}$$

$$M_B = \dfrac{F a \left(2 L^{3} - 4 L^{2} b - 3 L^{2} x + 2 L b^{2} + 4 L b x + a^{2} x - b^{2} x\right)}{2 L \left(L^{2} - 2 L b + b^{2}\right)}$$

$$M_C = \dfrac{F a \left(- L^{3} + 2 L^{2} b + L^{2} x + L a^{2} - L b^{2} - 2 L b x - a^{2} x + b^{2} x\right)}{2 L b \left(L - b\right)}$$

#### Esforços cortantes
$$V_A = \dfrac{F \left(2 L^{3} - 3 L^{2} a - 4 L^{2} b + 4 L a b + 2 L b^{2} + a^{3} - a b^{2}\right)}{2 L \left(L^{2} - 2 L b + b^{2}\right)}$$

$$V_B = \dfrac{F a \left(- 3 L^{2} + 4 L b + a^{2} - b^{2}\right)}{2 L \left(L^{2} - 2 L b + b^{2}\right)}$$

$$V_C = \dfrac{F a \left(L^{2} - 2 L b - a^{2} + b^{2}\right)}{2 L b \left(L - b\right)}$$

#### Reações de apoio
$$R_1 = \dfrac{F \left(2 L^{3} - 3 L^{2} a - 4 L^{2} b + 4 L a b + 2 L b^{2} + a^{3} - a b^{2}\right)}{2 L \left(L^{2} - 2 L b + b^{2}\right)}$$

$$R_2 = \dfrac{F a \left(L^{2} - a^{2} - b^{2}\right)}{2 b \left(L^{2} - 2 L b + b^{2}\right)}$$

$$R_3 = \dfrac{F a \left(L^{2} - 2 L b - a^{2} + b^{2}\right)}{2 L b \left(- L + b\right)}$$

#### Equações em Python
```python
# Flechas
deltaA = F*x*(-3*L**4*a + 6*L**3*a**2 + 8*L**3*a*b + 2*L**3*x**2 - 3*L**2*a**3 - 12*L**2*a**2*b - 6*L**2*a*b**2 - 3*L**2*a*x**2 - 4*L**2*b*x**2 + 4*L*a**3*b + 6*L*a**2*b**2 + 4*L*a*b*x**2 + 2*L*b**2*x**2 - a**3*b**2 + a**3*x**2 + a*b**4 - a*b**2*x**2)/(12*E*I*L*(L**2 - 2*L*b + b**2))
deltaB = F*a*(-3*L**4*x + 2*L**3*a**2 + 8*L**3*b*x + 6*L**3*x**2 - 4*L**2*a**2*b - 3*L**2*a**2*x - 6*L**2*b**2*x - 12*L**2*b*x**2 - 3*L**2*x**3 + 2*L*a**2*b**2 + 4*L*a**2*b*x + 6*L*b**2*x**2 + 4*L*b*x**3 - a**2*b**2*x + a**2*x**3 + b**4*x - b**2*x**3)/(12*E*I*L*(L**2 - 2*L*b + b**2))
deltaC = F*a*(-L**5 + 2*L**4*b + 3*L**4*x + L**3*a**2 - 6*L**3*b*x - 3*L**3*x**2 - 3*L**2*a**2*x - 2*L**2*b**3 + 2*L**2*b**2*x + 6*L**2*b*x**2 + L**2*x**3 - L*a**2*b**2 + 3*L*a**2*x**2 + L*b**4 + 2*L*b**3*x - 3*L*b**2*x**2 - 2*L*b*x**3 + a**2*b**2*x - a**2*x**3 - b**4*x + b**2*x**3)/(12*E*I*L*b*(L - b))
# Momentos fletores
MA = F*x*(2*L**3 - 3*L**2*a - 4*L**2*b + 4*L*a*b + 2*L*b**2 + a**3 - a*b**2)/(2*L*(L**2 - 2*L*b + b**2))
MB = F*a*(2*L**3 - 4*L**2*b - 3*L**2*x + 2*L*b**2 + 4*L*b*x + a**2*x - b**2*x)/(2*L*(L**2 - 2*L*b + b**2))
MC = F*a*(-L**3 + 2*L**2*b + L**2*x + L*a**2 - L*b**2 - 2*L*b*x - a**2*x + b**2*x)/(2*L*b*(L - b))
# Esforços cortantes
VA = F*(2*L**3 - 3*L**2*a - 4*L**2*b + 4*L*a*b + 2*L*b**2 + a**3 - a*b**2)/(2*L*(L**2 - 2*L*b + b**2))
VB = F*a*(-3*L**2 + 4*L*b + a**2 - b**2)/(2*L*(L**2 - 2*L*b + b**2))
VC = F*a*(L**2 - 2*L*b - a**2 + b**2)/(2*L*b*(L - b))
# Reações de apoio
R1 = F*(2*L**3 - 3*L**2*a - 4*L**2*b + 4*L*a*b + 2*L*b**2 + a**3 - a*b**2)/(2*L*(L**2 - 2*L*b + b**2))
R2 = F*a*(L**2 - a**2 - b**2)/(2*b*(L**2 - 2*L*b + b**2))
R3 = F*a*(L**2 - 2*L*b - a**2 + b**2)/(2*L*b*(-L + b))
```

---

### DV7-fe
- **Descrição:** Viga duplo-vão com carga concentrada no vão da direita
- **Página offline:** `00. Site Offline/DV7-fe.html`
- **Legenda:**
  - $E$ - módulo de elasticidade do material da viga;
  - $F$ - carga concentrada;
  - $I$ - inércia da seção transversal da viga (em torno no eixo que sai da tela);
  - $L$ - comprimento total da viga;
  - $a$ - comprimento do tramo A;
  - $b$ - comprimento do tramo B;
  - $x$ - posição em uma parte qualquer de um tramo da viga;

#### Flechas
$$\delta_A = \dfrac{F b x \left(- L^{2} a^{2} + L^{2} x^{2} + 2 L a^{3} - 2 L a x^{2} - a^{4} + a^{2} b^{2} + a^{2} x^{2} - b^{2} x^{2}\right)}{12 E I L a \left(- L + a\right)}$$

$$\delta_B = \dfrac{F b \left(- L^{3} a^{2} + 4 L^{3} a x - 3 L^{3} x^{2} - 3 L^{2} a^{2} x + 3 L^{2} x^{3} + L a^{4} + L a^{2} b^{2} + 3 L a^{2} x^{2} - 4 L a b^{2} x - 4 L a x^{3} + 3 L b^{2} x^{2} - a^{4} x + a^{2} b^{2} x + a^{2} x^{3} - b^{2} x^{3}\right)}{12 E I L \left(L^{2} - 2 L a + a^{2}\right)}$$

$$\delta_C = \dfrac{F \left(2 L^{6} - 4 L^{5} a - 6 L^{5} b - 6 L^{5} x + 2 L^{4} a^{2} + 12 L^{4} a b + 12 L^{4} a x + 6 L^{4} b^{2} + 12 L^{4} b x + 6 L^{4} x^{2} - 7 L^{3} a^{2} b - 6 L^{3} a^{2} x - 12 L^{3} a b^{2} - 20 L^{3} a b x - 12 L^{3} a x^{2} - 2 L^{3} b^{3} - 6 L^{3} b^{2} x - 9 L^{3} b x^{2} - 2 L^{3} x^{3} + 6 L^{2} a^{2} b^{2} + 9 L^{2} a^{2} b x + 6 L^{2} a^{2} x^{2} + 4 L^{2} a b^{3} + 12 L^{2} a b^{2} x + 12 L^{2} a b x^{2} + 4 L^{2} a x^{3} + 3 L^{2} b x^{3} + L a^{4} b - L a^{2} b^{3} - 6 L a^{2} b^{2} x - 3 L a^{2} b x^{2} - 2 L a^{2} x^{3} - 4 L a b^{3} x - 4 L a b x^{3} + 3 L b^{3} x^{2} - a^{4} b x + a^{2} b^{3} x + a^{2} b x^{3} - b^{3} x^{3}\right)}{12 E I L \left(L^{2} - 2 L a + a^{2}\right)}$$

#### Momentos fletores
$$M_A = \dfrac{F b x \left(L^{2} - 2 L a + a^{2} - b^{2}\right)}{2 L a \left(- L + a\right)}$$

$$M_B = \dfrac{F b \left(- L^{3} + 3 L^{2} x + L a^{2} - 4 L a x + L b^{2} + a^{2} x - b^{2} x\right)}{2 L \left(L^{2} - 2 L a + a^{2}\right)}$$

$$M_C = \dfrac{F \left(2 L^{4} - 4 L^{3} a - 3 L^{3} b - 2 L^{3} x + 2 L^{2} a^{2} + 4 L^{2} a b + 4 L^{2} a x + 3 L^{2} b x - L a^{2} b - 2 L a^{2} x - 4 L a b x + L b^{3} + a^{2} b x - b^{3} x\right)}{2 L \left(L^{2} - 2 L a + a^{2}\right)}$$

#### Esforços cortantes
$$V_A = \dfrac{F b \left(L^{2} - 2 L a + a^{2} - b^{2}\right)}{2 L a \left(- L + a\right)}$$

$$V_B = \dfrac{F b \left(3 L^{2} - 4 L a + a^{2} - b^{2}\right)}{2 L \left(L^{2} - 2 L a + a^{2}\right)}$$

$$V_C = \dfrac{F \left(- 2 L^{3} + 4 L^{2} a + 3 L^{2} b - 2 L a^{2} - 4 L a b + a^{2} b - b^{3}\right)}{2 L \left(L^{2} - 2 L a + a^{2}\right)}$$

#### Reações de apoio
$$R_1 = \dfrac{F b \left(L^{2} - 2 L a + a^{2} - b^{2}\right)}{2 L a \left(- L + a\right)}$$

$$R_2 = \dfrac{F b \left(L^{2} - a^{2} - b^{2}\right)}{2 a \left(L^{2} - 2 L a + a^{2}\right)}$$

$$R_3 = \dfrac{F \left(2 L^{3} - 4 L^{2} a - 3 L^{2} b + 2 L a^{2} + 4 L a b - a^{2} b + b^{3}\right)}{2 L \left(L^{2} - 2 L a + a^{2}\right)}$$

#### Equações em Python
```python
# Flechas
deltaA = F*b*x*(-L**2*a**2 + L**2*x**2 + 2*L*a**3 - 2*L*a*x**2 - a**4 + a**2*b**2 + a**2*x**2 - b**2*x**2)/(12*E*I*L*a*(-L + a))
deltaB = F*b*(-L**3*a**2 + 4*L**3*a*x - 3*L**3*x**2 - 3*L**2*a**2*x + 3*L**2*x**3 + L*a**4 + L*a**2*b**2 + 3*L*a**2*x**2 - 4*L*a*b**2*x - 4*L*a*x**3 + 3*L*b**2*x**2 - a**4*x + a**2*b**2*x + a**2*x**3 - b**2*x**3)/(12*E*I*L*(L**2 - 2*L*a + a**2))
deltaC = F*(2*L**6 - 4*L**5*a - 6*L**5*b - 6*L**5*x + 2*L**4*a**2 + 12*L**4*a*b + 12*L**4*a*x + 6*L**4*b**2 + 12*L**4*b*x + 6*L**4*x**2 - 7*L**3*a**2*b - 6*L**3*a**2*x - 12*L**3*a*b**2 - 20*L**3*a*b*x - 12*L**3*a*x**2 - 2*L**3*b**3 - 6*L**3*b**2*x - 9*L**3*b*x**2 - 2*L**3*x**3 + 6*L**2*a**2*b**2 + 9*L**2*a**2*b*x + 6*L**2*a**2*x**2 + 4*L**2*a*b**3 + 12*L**2*a*b**2*x + 12*L**2*a*b*x**2 + 4*L**2*a*x**3 + 3*L**2*b*x**3 + L*a**4*b - L*a**2*b**3 - 6*L*a**2*b**2*x - 3*L*a**2*b*x**2 - 2*L*a**2*x**3 - 4*L*a*b**3*x - 4*L*a*b*x**3 + 3*L*b**3*x**2 - a**4*b*x + a**2*b**3*x + a**2*b*x**3 - b**3*x**3)/(12*E*I*L*(L**2 - 2*L*a + a**2))
# Momentos fletores
MA = F*b*x*(L**2 - 2*L*a + a**2 - b**2)/(2*L*a*(-L + a))
MB = F*b*(-L**3 + 3*L**2*x + L*a**2 - 4*L*a*x + L*b**2 + a**2*x - b**2*x)/(2*L*(L**2 - 2*L*a + a**2))
MC = F*(2*L**4 - 4*L**3*a - 3*L**3*b - 2*L**3*x + 2*L**2*a**2 + 4*L**2*a*b + 4*L**2*a*x + 3*L**2*b*x - L*a**2*b - 2*L*a**2*x - 4*L*a*b*x + L*b**3 + a**2*b*x - b**3*x)/(2*L*(L**2 - 2*L*a + a**2))
# Esforços cortantes
VA = F*b*(L**2 - 2*L*a + a**2 - b**2)/(2*L*a*(-L + a))
VB = F*b*(3*L**2 - 4*L*a + a**2 - b**2)/(2*L*(L**2 - 2*L*a + a**2))
VC = F*(-2*L**3 + 4*L**2*a + 3*L**2*b - 2*L*a**2 - 4*L*a*b + a**2*b - b**3)/(2*L*(L**2 - 2*L*a + a**2))
# Reações de apoio
R1 = F*b*(L**2 - 2*L*a + a**2 - b**2)/(2*L*a*(-L + a))
R2 = F*b*(L**2 - a**2 - b**2)/(2*a*(L**2 - 2*L*a + a**2))
R3 = F*(2*L**3 - 4*L**2*a - 3*L**2*b + 2*L*a**2 + 4*L*a*b - a**2*b + b**3)/(2*L*(L**2 - 2*L*a + a**2))
```

---

### DV8-me
- **Descrição:** Viga duplo-vão com momento concentrado no vão da esquerda
- **Página offline:** `00. Site Offline/DV8-me.html`
- **Legenda:**
  - $E$ - módulo de elasticidade do material da viga;
  - $I$ - inércia da seção transversal da viga (em torno no eixo que sai da tela);
  - $L$ - comprimento total da viga;
  - $M$ - momento concentrado;
  - $a$ - comprimento do tramo A;
  - $b$ - comprimento do tramo B;
  - $x$ - posição em uma parte qualquer de um tramo da viga;

#### Flechas
$$\delta_A = \dfrac{M x \left(- 3 L^{4} + 12 L^{3} a + 8 L^{3} b - 9 L^{2} a^{2} - 24 L^{2} a b - 6 L^{2} b^{2} - 3 L^{2} x^{2} + 12 L a^{2} b + 12 L a b^{2} + 4 L b x^{2} - 3 a^{2} b^{2} + 3 a^{2} x^{2} + b^{4} - b^{2} x^{2}\right)}{12 E I L \left(L^{2} - 2 L b + b^{2}\right)}$$

$$\delta_B = \dfrac{M \left(- 3 L^{4} x + 6 L^{3} a^{2} + 8 L^{3} b x + 6 L^{3} x^{2} - 12 L^{2} a^{2} b - 9 L^{2} a^{2} x - 6 L^{2} b^{2} x - 12 L^{2} b x^{2} - 3 L^{2} x^{3} + 6 L a^{2} b^{2} + 12 L a^{2} b x + 6 L b^{2} x^{2} + 4 L b x^{3} - 3 a^{2} b^{2} x + 3 a^{2} x^{3} + b^{4} x - b^{2} x^{3}\right)}{12 E I L \left(L^{2} - 2 L b + b^{2}\right)}$$

$$\delta_C = \dfrac{M \left(- L^{5} + 2 L^{4} b + 3 L^{4} x + 3 L^{3} a^{2} - 6 L^{3} b x - 3 L^{3} x^{2} - 9 L^{2} a^{2} x - 2 L^{2} b^{3} + 2 L^{2} b^{2} x + 6 L^{2} b x^{2} + L^{2} x^{3} - 3 L a^{2} b^{2} + 9 L a^{2} x^{2} + L b^{4} + 2 L b^{3} x - 3 L b^{2} x^{2} - 2 L b x^{3} + 3 a^{2} b^{2} x - 3 a^{2} x^{3} - b^{4} x + b^{2} x^{3}\right)}{12 E I L b \left(L - b\right)}$$

#### Momentos fletores
$$M_A = \dfrac{M x \left(- 3 L^{2} + 4 L b + 3 a^{2} - b^{2}\right)}{2 L \left(L^{2} - 2 L b + b^{2}\right)}$$

$$M_B = \dfrac{M \left(2 L^{3} - 4 L^{2} b - 3 L^{2} x + 2 L b^{2} + 4 L b x + 3 a^{2} x - b^{2} x\right)}{2 L \left(L^{2} - 2 L b + b^{2}\right)}$$

$$M_C = \dfrac{M \left(- L^{3} + 2 L^{2} b + L^{2} x + 3 L a^{2} - L b^{2} - 2 L b x - 3 a^{2} x + b^{2} x\right)}{2 L b \left(L - b\right)}$$

#### Esforços cortantes
$$V_A = \dfrac{M \left(- 3 L^{2} + 4 L b + 3 a^{2} - b^{2}\right)}{2 L \left(L^{2} - 2 L b + b^{2}\right)}$$

$$V_B = \dfrac{M \left(- 3 L^{2} + 4 L b + 3 a^{2} - b^{2}\right)}{2 L \left(L^{2} - 2 L b + b^{2}\right)}$$

$$V_C = \dfrac{M \left(L^{2} - 2 L b - 3 a^{2} + b^{2}\right)}{2 L b \left(L - b\right)}$$

#### Reações de apoio
$$R_1 = \dfrac{M \left(- 3 L^{2} + 4 L b + 3 a^{2} - b^{2}\right)}{2 L \left(L^{2} - 2 L b + b^{2}\right)}$$

$$R_2 = \dfrac{M \left(L^{2} - 3 a^{2} - b^{2}\right)}{2 b \left(L^{2} - 2 L b + b^{2}\right)}$$

$$R_3 = \dfrac{M \left(L^{2} - 2 L b - 3 a^{2} + b^{2}\right)}{2 L b \left(- L + b\right)}$$

#### Equações em Python
```python
# Flechas
deltaA = M*x*(-3*L**4 + 12*L**3*a + 8*L**3*b - 9*L**2*a**2 - 24*L**2*a*b - 6*L**2*b**2 - 3*L**2*x**2 + 12*L*a**2*b + 12*L*a*b**2 + 4*L*b*x**2 - 3*a**2*b**2 + 3*a**2*x**2 + b**4 - b**2*x**2)/(12*E*I*L*(L**2 - 2*L*b + b**2))
deltaB = M*(-3*L**4*x + 6*L**3*a**2 + 8*L**3*b*x + 6*L**3*x**2 - 12*L**2*a**2*b - 9*L**2*a**2*x - 6*L**2*b**2*x - 12*L**2*b*x**2 - 3*L**2*x**3 + 6*L*a**2*b**2 + 12*L*a**2*b*x + 6*L*b**2*x**2 + 4*L*b*x**3 - 3*a**2*b**2*x + 3*a**2*x**3 + b**4*x - b**2*x**3)/(12*E*I*L*(L**2 - 2*L*b + b**2))
deltaC = M*(-L**5 + 2*L**4*b + 3*L**4*x + 3*L**3*a**2 - 6*L**3*b*x - 3*L**3*x**2 - 9*L**2*a**2*x - 2*L**2*b**3 + 2*L**2*b**2*x + 6*L**2*b*x**2 + L**2*x**3 - 3*L*a**2*b**2 + 9*L*a**2*x**2 + L*b**4 + 2*L*b**3*x - 3*L*b**2*x**2 - 2*L*b*x**3 + 3*a**2*b**2*x - 3*a**2*x**3 - b**4*x + b**2*x**3)/(12*E*I*L*b*(L - b))
# Momentos fletores
MA = M*x*(-3*L**2 + 4*L*b + 3*a**2 - b**2)/(2*L*(L**2 - 2*L*b + b**2))
MB = M*(2*L**3 - 4*L**2*b - 3*L**2*x + 2*L*b**2 + 4*L*b*x + 3*a**2*x - b**2*x)/(2*L*(L**2 - 2*L*b + b**2))
MC = M*(-L**3 + 2*L**2*b + L**2*x + 3*L*a**2 - L*b**2 - 2*L*b*x - 3*a**2*x + b**2*x)/(2*L*b*(L - b))
# Esforços cortantes
VA = M*(-3*L**2 + 4*L*b + 3*a**2 - b**2)/(2*L*(L**2 - 2*L*b + b**2))
VB = M*(-3*L**2 + 4*L*b + 3*a**2 - b**2)/(2*L*(L**2 - 2*L*b + b**2))
VC = M*(L**2 - 2*L*b - 3*a**2 + b**2)/(2*L*b*(L - b))
# Reações de apoio
R1 = M*(-3*L**2 + 4*L*b + 3*a**2 - b**2)/(2*L*(L**2 - 2*L*b + b**2))
R2 = M*(L**2 - 3*a**2 - b**2)/(2*b*(L**2 - 2*L*b + b**2))
R3 = M*(L**2 - 2*L*b - 3*a**2 + b**2)/(2*L*b*(-L + b))
```

---

### DV9-me
- **Descrição:** Viga duplo-vão com momento concentrado no vão da direita
- **Página offline:** `00. Site Offline/DV9-me.html`
- **Legenda:**
  - $E$ - módulo de elasticidade do material da viga;
  - $I$ - inércia da seção transversal da viga (em torno no eixo que sai da tela);
  - $L$ - comprimento total da viga;
  - $M$ - momento concentrado;
  - $a$ - comprimento do tramo A;
  - $b$ - comprimento do tramo B;
  - $x$ - posição em uma parte qualquer de um tramo da viga;

#### Flechas
$$\delta_A = \dfrac{M x \left(L^{2} a^{2} - L^{2} x^{2} - 2 L a^{3} + 2 L a x^{2} + a^{4} - 3 a^{2} b^{2} - a^{2} x^{2} + 3 b^{2} x^{2}\right)}{12 E I L a \left(- L + a\right)}$$

$$\delta_B = \dfrac{M \left(L^{3} a^{2} - 4 L^{3} a x + 3 L^{3} x^{2} + 3 L^{2} a^{2} x - 3 L^{2} x^{3} - L a^{4} - 3 L a^{2} b^{2} - 3 L a^{2} x^{2} + 12 L a b^{2} x + 4 L a x^{3} - 9 L b^{2} x^{2} + a^{4} x - 3 a^{2} b^{2} x - a^{2} x^{3} + 3 b^{2} x^{3}\right)}{12 E I L \left(L^{2} - 2 L a + a^{2}\right)}$$

$$\delta_C = \dfrac{M \left(6 L^{5} - 12 L^{4} a - 12 L^{4} b - 12 L^{4} x + 7 L^{3} a^{2} + 24 L^{3} a b + 20 L^{3} a x + 6 L^{3} b^{2} + 12 L^{3} b x + 9 L^{3} x^{2} - 12 L^{2} a^{2} b - 9 L^{2} a^{2} x - 12 L^{2} a b^{2} - 24 L^{2} a b x - 12 L^{2} a x^{2} - 3 L^{2} x^{3} - L a^{4} + 3 L a^{2} b^{2} + 12 L a^{2} b x + 3 L a^{2} x^{2} + 12 L a b^{2} x + 4 L a x^{3} - 9 L b^{2} x^{2} + a^{4} x - 3 a^{2} b^{2} x - a^{2} x^{3} + 3 b^{2} x^{3}\right)}{12 E I L \left(L^{2} - 2 L a + a^{2}\right)}$$

#### Momentos fletores
$$M_A = \dfrac{M x \left(- L^{2} + 2 L a - a^{2} + 3 b^{2}\right)}{2 L a \left(- L + a\right)}$$

$$M_B = \dfrac{M \left(L^{3} - 3 L^{2} x - L a^{2} + 4 L a x - 3 L b^{2} - a^{2} x + 3 b^{2} x\right)}{2 L \left(L^{2} - 2 L a + a^{2}\right)}$$

$$M_C = \dfrac{M \left(3 L^{3} - 4 L^{2} a - 3 L^{2} x + L a^{2} + 4 L a x - 3 L b^{2} - a^{2} x + 3 b^{2} x\right)}{2 L \left(L^{2} - 2 L a + a^{2}\right)}$$

#### Esforços cortantes
$$V_A = \dfrac{M \left(- L^{2} + 2 L a - a^{2} + 3 b^{2}\right)}{2 L a \left(- L + a\right)}$$

$$V_B = \dfrac{M \left(- 3 L^{2} + 4 L a - a^{2} + 3 b^{2}\right)}{2 L \left(L^{2} - 2 L a + a^{2}\right)}$$

$$V_C = \dfrac{M \left(- 3 L^{2} + 4 L a - a^{2} + 3 b^{2}\right)}{2 L \left(L^{2} - 2 L a + a^{2}\right)}$$

#### Reações de apoio
$$R_1 = \dfrac{M \left(L^{2} - 2 L a + a^{2} - 3 b^{2}\right)}{2 L a \left(L - a\right)}$$

$$R_2 = \dfrac{M \left(- L^{2} + a^{2} + 3 b^{2}\right)}{2 a \left(L^{2} - 2 L a + a^{2}\right)}$$

$$R_3 = \dfrac{M \left(3 L^{2} - 4 L a + a^{2} - 3 b^{2}\right)}{2 L \left(L^{2} - 2 L a + a^{2}\right)}$$

#### Equações em Python
```python
# Flechas
deltaA = M*x*(L**2*a**2 - L**2*x**2 - 2*L*a**3 + 2*L*a*x**2 + a**4 - 3*a**2*b**2 - a**2*x**2 + 3*b**2*x**2)/(12*E*I*L*a*(-L + a))
deltaB = M*(L**3*a**2 - 4*L**3*a*x + 3*L**3*x**2 + 3*L**2*a**2*x - 3*L**2*x**3 - L*a**4 - 3*L*a**2*b**2 - 3*L*a**2*x**2 + 12*L*a*b**2*x + 4*L*a*x**3 - 9*L*b**2*x**2 + a**4*x - 3*a**2*b**2*x - a**2*x**3 + 3*b**2*x**3)/(12*E*I*L*(L**2 - 2*L*a + a**2))
deltaC = M*(6*L**5 - 12*L**4*a - 12*L**4*b - 12*L**4*x + 7*L**3*a**2 + 24*L**3*a*b + 20*L**3*a*x + 6*L**3*b**2 + 12*L**3*b*x + 9*L**3*x**2 - 12*L**2*a**2*b - 9*L**2*a**2*x - 12*L**2*a*b**2 - 24*L**2*a*b*x - 12*L**2*a*x**2 - 3*L**2*x**3 - L*a**4 + 3*L*a**2*b**2 + 12*L*a**2*b*x + 3*L*a**2*x**2 + 12*L*a*b**2*x + 4*L*a*x**3 - 9*L*b**2*x**2 + a**4*x - 3*a**2*b**2*x - a**2*x**3 + 3*b**2*x**3)/(12*E*I*L*(L**2 - 2*L*a + a**2))
# Momentos fletores
MA = M*x*(-L**2 + 2*L*a - a**2 + 3*b**2)/(2*L*a*(-L + a))
MB = M*(L**3 - 3*L**2*x - L*a**2 + 4*L*a*x - 3*L*b**2 - a**2*x + 3*b**2*x)/(2*L*(L**2 - 2*L*a + a**2))
MC = M*(3*L**3 - 4*L**2*a - 3*L**2*x + L*a**2 + 4*L*a*x - 3*L*b**2 - a**2*x + 3*b**2*x)/(2*L*(L**2 - 2*L*a + a**2))
# Esforços cortantes
VA = M*(-L**2 + 2*L*a - a**2 + 3*b**2)/(2*L*a*(-L + a))
VB = M*(-3*L**2 + 4*L*a - a**2 + 3*b**2)/(2*L*(L**2 - 2*L*a + a**2))
VC = M*(-3*L**2 + 4*L*a - a**2 + 3*b**2)/(2*L*(L**2 - 2*L*a + a**2))
# Reações de apoio
R1 = M*(L**2 - 2*L*a + a**2 - 3*b**2)/(2*L*a*(L - a))
R2 = M*(-L**2 + a**2 + 3*b**2)/(2*a*(L**2 - 2*L*a + a**2))
R3 = M*(3*L**2 - 4*L*a + a**2 - 3*b**2)/(2*L*(L**2 - 2*L*a + a**2))
```

---

### DV10-mm
- **Descrição:** Viga duplo-vão com momento concentrado em ambos os vãos
- **Página offline:** `00. Site Offline/DV10-mm.html`
- **Legenda:**
  - $E$ - módulo de elasticidade do material da viga;
  - $I$ - inércia da seção transversal da viga (em torno no eixo que sai da tela);
  - $L$ - comprimento total da viga;
  - $M$ - momento concentrado;
  - $a$ - comprimento do tramo A;
  - $b$ - comprimento do tramo B;
  - $c$ - comprimento do tramo C;
  - $x$ - posição em uma parte qualquer de um tramo da viga;

#### Flechas
$$\delta_A = \dfrac{M x \left(- 4 L^{2} a^{3} - 12 L^{2} a^{2} b - 6 L^{2} a b^{2} + 4 L^{2} a x^{2} + 2 L^{2} b^{3} + 4 L^{2} b x^{2} + 8 L a^{4} + 26 L a^{3} b + 6 L a^{3} c + 27 L a^{2} b^{2} + 18 L a^{2} b c - 8 L a^{2} x^{2} + 8 L a b^{3} + 18 L a b^{2} c - 10 L a b x^{2} - 6 L a c x^{2} - L b^{4} + 6 L b^{3} c - 5 L b^{2} x^{2} - 6 L b c x^{2} - 4 a^{5} - 14 a^{4} b - 6 a^{4} c - 19 a^{3} b^{2} - 24 a^{3} b c - 3 a^{3} c^{2} + 4 a^{3} x^{2} - 13 a^{2} b^{3} - 36 a^{2} b^{2} c - 9 a^{2} b c^{2} + 6 a^{2} b x^{2} + 6 a^{2} c x^{2} - 5 a b^{4} - 24 a b^{3} c - 9 a b^{2} c^{2} + 3 a b^{2} x^{2} + 12 a b c x^{2} + 3 a c^{2} x^{2} - b^{5} - 6 b^{4} c - 3 b^{3} c^{2} + b^{3} x^{2} + 6 b^{2} c x^{2} + 3 b c^{2} x^{2}\right)}{12 E I L \left(- L a^{2} - 2 L a b - L b^{2} + a^{3} + 3 a^{2} b + 3 a b^{2} + b^{3}\right)}$$

$$\delta_B = \dfrac{M \left(- 6 L^{2} a^{4} - 12 L^{2} a^{3} b + 8 L^{2} a^{3} x - 6 L^{2} a^{2} b^{2} + 12 L^{2} a^{2} b x - 6 L^{2} a^{2} x^{2} + 6 L^{2} a b^{2} x - 12 L^{2} a b x^{2} + 4 L^{2} a x^{3} + 2 L^{2} b^{3} x - 6 L^{2} b^{2} x^{2} + 4 L^{2} b x^{3} + 6 L a^{5} + 18 L a^{4} b - 4 L a^{4} x + 18 L a^{3} b^{2} - 10 L a^{3} b x + 6 L a^{3} c x + 6 L a^{3} x^{2} + 6 L a^{2} b^{3} - 9 L a^{2} b^{2} x + 18 L a^{2} b c x + 18 L a^{2} b x^{2} - 8 L a^{2} x^{3} - 4 L a b^{3} x + 18 L a b^{2} c x + 18 L a b^{2} x^{2} - 10 L a b x^{3} - 6 L a c x^{3} - L b^{4} x + 6 L b^{3} c x + 6 L b^{3} x^{2} - 5 L b^{2} x^{3} - 6 L b c x^{3} - 4 a^{5} x - 14 a^{4} b x - 6 a^{4} c x - 19 a^{3} b^{2} x - 24 a^{3} b c x - 3 a^{3} c^{2} x + 4 a^{3} x^{3} - 13 a^{2} b^{3} x - 36 a^{2} b^{2} c x - 9 a^{2} b c^{2} x + 6 a^{2} b x^{3} + 6 a^{2} c x^{3} - 5 a b^{4} x - 24 a b^{3} c x - 9 a b^{2} c^{2} x + 3 a b^{2} x^{3} + 12 a b c x^{3} + 3 a c^{2} x^{3} - b^{5} x - 6 b^{4} c x - 3 b^{3} c^{2} x + b^{3} x^{3} + 6 b^{2} c x^{3} + 3 b c^{2} x^{3}\right)}{12 E I L \left(- L a^{2} - 2 L a b - L b^{2} + a^{3} + 3 a^{2} b + 3 a b^{2} + b^{3}\right)}$$

$$\delta_C = \dfrac{M \left(2 L^{3} a^{3} - 6 L^{3} a^{2} b + 4 L^{3} a^{2} x - 12 L^{3} a b^{2} + 20 L^{3} a b x - 6 L^{3} a x^{2} - 4 L^{3} b^{3} + 10 L^{3} b^{2} x - 6 L^{3} b x^{2} + 18 L^{2} a^{3} b + 6 L^{2} a^{3} c - 24 L^{2} a^{3} x + 45 L^{2} a^{2} b^{2} + 18 L^{2} a^{2} b c - 72 L^{2} a^{2} b x - 24 L^{2} a^{2} c x + 24 L^{2} a^{2} x^{2} + 36 L^{2} a b^{3} + 18 L^{2} a b^{2} c - 72 L^{2} a b^{2} x - 48 L^{2} a b c x + 30 L^{2} a b x^{2} + 18 L^{2} a c x^{2} + 9 L^{2} b^{4} + 6 L^{2} b^{3} c - 24 L^{2} b^{3} x - 24 L^{2} b^{2} c x + 15 L^{2} b^{2} x^{2} + 18 L^{2} b c x^{2} - 2 L a^{5} - 16 L a^{4} b - 6 L a^{4} c + 24 L a^{4} x - 41 L a^{3} b^{2} - 24 L a^{3} b c + 78 L a^{3} b x - 3 L a^{3} c^{2} + 30 L a^{3} c x - 18 L a^{3} x^{2} - 47 L a^{2} b^{3} - 36 L a^{2} b^{2} c + 99 L a^{2} b^{2} x - 9 L a^{2} b c^{2} + 90 L a^{2} b c x - 36 L a^{2} b x^{2} + 12 L a^{2} c^{2} x - 18 L a^{2} c x^{2} - 4 L a^{2} x^{3} - 25 L a b^{4} - 24 L a b^{3} c + 60 L a b^{3} x - 9 L a b^{2} c^{2} + 90 L a b^{2} c x - 27 L a b^{2} x^{2} + 24 L a b c^{2} x - 36 L a b c x^{2} - 2 L a b x^{3} - 9 L a c^{2} x^{2} - 6 L a c x^{3} - 5 L b^{5} - 6 L b^{4} c + 15 L b^{4} x - 3 L b^{3} c^{2} + 30 L b^{3} c x - 9 L b^{3} x^{2} + 12 L b^{2} c^{2} x - 18 L b^{2} c x^{2} - L b^{2} x^{3} - 9 L b c^{2} x^{2} - 6 L b c x^{3} - 4 a^{5} x - 14 a^{4} b x - 6 a^{4} c x - 19 a^{3} b^{2} x - 24 a^{3} b c x - 3 a^{3} c^{2} x + 4 a^{3} x^{3} - 13 a^{2} b^{3} x - 36 a^{2} b^{2} c x - 9 a^{2} b c^{2} x + 6 a^{2} b x^{3} + 6 a^{2} c x^{3} - 5 a b^{4} x - 24 a b^{3} c x - 9 a b^{2} c^{2} x + 3 a b^{2} x^{3} + 12 a b c x^{3} + 3 a c^{2} x^{3} - b^{5} x - 6 b^{4} c x - 3 b^{3} c^{2} x + b^{3} x^{3} + 6 b^{2} c x^{3} + 3 b c^{2} x^{3}\right)}{12 E I L \left(L^{2} a + L^{2} b - 2 L a^{2} - 4 L a b - 2 L b^{2} + a^{3} + 3 a^{2} b + 3 a b^{2} + b^{3}\right)}$$

$$\delta_D = \dfrac{M \left(8 L^{3} a^{3} + 12 L^{3} a^{2} b + 12 L^{3} a^{2} c - 8 L^{3} a^{2} x + 6 L^{3} a b^{2} + 24 L^{3} a b c - 4 L^{3} a b x + 6 L^{3} a c^{2} - 12 L^{3} a c x + 2 L^{3} b^{3} + 12 L^{3} b^{2} c - 2 L^{3} b^{2} x + 6 L^{3} b c^{2} - 12 L^{3} b c x - 12 L^{2} a^{4} - 30 L^{2} a^{3} b - 18 L^{2} a^{3} c - 27 L^{2} a^{2} b^{2} - 54 L^{2} a^{2} b c - 12 L^{2} a^{2} c^{2} + 12 L^{2} a^{2} x^{2} - 12 L^{2} a b^{3} - 54 L^{2} a b^{2} c - 24 L^{2} a b c^{2} + 6 L^{2} a b x^{2} + 18 L^{2} a c x^{2} - 3 L^{2} b^{4} - 18 L^{2} b^{3} c - 12 L^{2} b^{2} c^{2} + 3 L^{2} b^{2} x^{2} + 18 L^{2} b c x^{2} + 4 L a^{5} + 14 L a^{4} b + 6 L a^{4} c + 12 L a^{4} x + 19 L a^{3} b^{2} + 24 L a^{3} b c + 30 L a^{3} b x + 3 L a^{3} c^{2} + 18 L a^{3} c x - 12 L a^{3} x^{2} + 13 L a^{2} b^{3} + 36 L a^{2} b^{2} c + 27 L a^{2} b^{2} x + 9 L a^{2} b c^{2} + 54 L a^{2} b c x - 18 L a^{2} b x^{2} + 12 L a^{2} c^{2} x - 18 L a^{2} c x^{2} - 4 L a^{2} x^{3} + 5 L a b^{4} + 24 L a b^{3} c + 12 L a b^{3} x + 9 L a b^{2} c^{2} + 54 L a b^{2} c x - 9 L a b^{2} x^{2} + 24 L a b c^{2} x - 36 L a b c x^{2} - 2 L a b x^{3} - 9 L a c^{2} x^{2} - 6 L a c x^{3} + L b^{5} + 6 L b^{4} c + 3 L b^{4} x + 3 L b^{3} c^{2} + 18 L b^{3} c x - 3 L b^{3} x^{2} + 12 L b^{2} c^{2} x - 18 L b^{2} c x^{2} - L b^{2} x^{3} - 9 L b c^{2} x^{2} - 6 L b c x^{3} - 4 a^{5} x - 14 a^{4} b x - 6 a^{4} c x - 19 a^{3} b^{2} x - 24 a^{3} b c x - 3 a^{3} c^{2} x + 4 a^{3} x^{3} - 13 a^{2} b^{3} x - 36 a^{2} b^{2} c x - 9 a^{2} b c^{2} x + 6 a^{2} b x^{3} + 6 a^{2} c x^{3} - 5 a b^{4} x - 24 a b^{3} c x - 9 a b^{2} c^{2} x + 3 a b^{2} x^{3} + 12 a b c x^{3} + 3 a c^{2} x^{3} - b^{5} x - 6 b^{4} c x - 3 b^{3} c^{2} x + b^{3} x^{3} + 6 b^{2} c x^{3} + 3 b c^{2} x^{3}\right)}{12 E I L \left(L^{2} a + L^{2} b - 2 L a^{2} - 4 L a b - 2 L b^{2} + a^{3} + 3 a^{2} b + 3 a b^{2} + b^{3}\right)}$$

#### Momentos fletores
$$M_A = \dfrac{M x \left(4 L^{2} a + 4 L^{2} b - 8 L a^{2} - 10 L a b - 6 L a c - 5 L b^{2} - 6 L b c + 4 a^{3} + 6 a^{2} b + 6 a^{2} c + 3 a b^{2} + 12 a b c + 3 a c^{2} + b^{3} + 6 b^{2} c + 3 b c^{2}\right)}{2 L \left(- L a^{2} - 2 L a b - L b^{2} + a^{3} + 3 a^{2} b + 3 a b^{2} + b^{3}\right)}$$

$$M_B = \dfrac{M \left(- 2 L^{2} a^{2} - 4 L^{2} a b + 4 L^{2} a x - 2 L^{2} b^{2} + 4 L^{2} b x + 2 L a^{3} + 6 L a^{2} b - 8 L a^{2} x + 6 L a b^{2} - 10 L a b x - 6 L a c x + 2 L b^{3} - 5 L b^{2} x - 6 L b c x + 4 a^{3} x + 6 a^{2} b x + 6 a^{2} c x + 3 a b^{2} x + 12 a b c x + 3 a c^{2} x + b^{3} x + 6 b^{2} c x + 3 b c^{2} x\right)}{2 L \left(- L a^{2} - 2 L a b - L b^{2} + a^{3} + 3 a^{2} b + 3 a b^{2} + b^{3}\right)}$$

$$M_C = \dfrac{M \left(- 2 L^{3} a - 2 L^{3} b + 8 L^{2} a^{2} + 10 L^{2} a b + 6 L^{2} a c + 5 L^{2} b^{2} + 6 L^{2} b c - 6 L a^{3} - 12 L a^{2} b - 6 L a^{2} c - 4 L a^{2} x - 9 L a b^{2} - 12 L a b c - 2 L a b x - 3 L a c^{2} - 6 L a c x - 3 L b^{3} - 6 L b^{2} c - L b^{2} x - 3 L b c^{2} - 6 L b c x + 4 a^{3} x + 6 a^{2} b x + 6 a^{2} c x + 3 a b^{2} x + 12 a b c x + 3 a c^{2} x + b^{3} x + 6 b^{2} c x + 3 b c^{2} x\right)}{2 L \left(L^{2} a + L^{2} b - 2 L a^{2} - 4 L a b - 2 L b^{2} + a^{3} + 3 a^{2} b + 3 a b^{2} + b^{3}\right)}$$

$$M_D = \dfrac{M \left(4 L^{2} a^{2} + 2 L^{2} a b + 6 L^{2} a c + L^{2} b^{2} + 6 L^{2} b c - 4 L a^{3} - 6 L a^{2} b - 6 L a^{2} c - 4 L a^{2} x - 3 L a b^{2} - 12 L a b c - 2 L a b x - 3 L a c^{2} - 6 L a c x - L b^{3} - 6 L b^{2} c - L b^{2} x - 3 L b c^{2} - 6 L b c x + 4 a^{3} x + 6 a^{2} b x + 6 a^{2} c x + 3 a b^{2} x + 12 a b c x + 3 a c^{2} x + b^{3} x + 6 b^{2} c x + 3 b c^{2} x\right)}{2 L \left(L^{2} a + L^{2} b - 2 L a^{2} - 4 L a b - 2 L b^{2} + a^{3} + 3 a^{2} b + 3 a b^{2} + b^{3}\right)}$$

#### Esforços cortantes
$$V_A = \dfrac{M \left(4 L^{2} a + 4 L^{2} b - 8 L a^{2} - 10 L a b - 6 L a c - 5 L b^{2} - 6 L b c + 4 a^{3} + 6 a^{2} b + 6 a^{2} c + 3 a b^{2} + 12 a b c + 3 a c^{2} + b^{3} + 6 b^{2} c + 3 b c^{2}\right)}{2 L \left(- L a^{2} - 2 L a b - L b^{2} + a^{3} + 3 a^{2} b + 3 a b^{2} + b^{3}\right)}$$

$$V_B = \dfrac{M \left(4 L^{2} a + 4 L^{2} b - 8 L a^{2} - 10 L a b - 6 L a c - 5 L b^{2} - 6 L b c + 4 a^{3} + 6 a^{2} b + 6 a^{2} c + 3 a b^{2} + 12 a b c + 3 a c^{2} + b^{3} + 6 b^{2} c + 3 b c^{2}\right)}{2 L \left(- L a^{2} - 2 L a b - L b^{2} + a^{3} + 3 a^{2} b + 3 a b^{2} + b^{3}\right)}$$

$$V_C = \dfrac{M \left(- 4 L a^{2} - 2 L a b - 6 L a c - L b^{2} - 6 L b c + 4 a^{3} + 6 a^{2} b + 6 a^{2} c + 3 a b^{2} + 12 a b c + 3 a c^{2} + b^{3} + 6 b^{2} c + 3 b c^{2}\right)}{2 L \left(L^{2} a + L^{2} b - 2 L a^{2} - 4 L a b - 2 L b^{2} + a^{3} + 3 a^{2} b + 3 a b^{2} + b^{3}\right)}$$

$$V_D = \dfrac{M \left(- 4 L a^{2} - 2 L a b - 6 L a c - L b^{2} - 6 L b c + 4 a^{3} + 6 a^{2} b + 6 a^{2} c + 3 a b^{2} + 12 a b c + 3 a c^{2} + b^{3} + 6 b^{2} c + 3 b c^{2}\right)}{2 L \left(L^{2} a + L^{2} b - 2 L a^{2} - 4 L a b - 2 L b^{2} + a^{3} + 3 a^{2} b + 3 a b^{2} + b^{3}\right)}$$

#### Reações de apoio
$$R_1 = \dfrac{M \left(4 L^{2} a + 4 L^{2} b - 8 L a^{2} - 10 L a b - 6 L a c - 5 L b^{2} - 6 L b c + 4 a^{3} + 6 a^{2} b + 6 a^{2} c + 3 a b^{2} + 12 a b c + 3 a c^{2} + b^{3} + 6 b^{2} c + 3 b c^{2}\right)}{2 L \left(- L a^{2} - 2 L a b - L b^{2} + a^{3} + 3 a^{2} b + 3 a b^{2} + b^{3}\right)}$$

$$R_2 = \dfrac{M \left(4 L^{2} a + 4 L^{2} b - 12 L a^{2} - 18 L a b - 6 L a c - 9 L b^{2} - 6 L b c + 8 a^{3} + 18 a^{2} b + 6 a^{2} c + 15 a b^{2} + 12 a b c + 3 a c^{2} + 5 b^{3} + 6 b^{2} c + 3 b c^{2}\right)}{2 \left(L^{2} a^{2} + 2 L^{2} a b + L^{2} b^{2} - 2 L a^{3} - 6 L a^{2} b - 6 L a b^{2} - 2 L b^{3} + a^{4} + 4 a^{3} b + 6 a^{2} b^{2} + 4 a b^{3} + b^{4}\right)}$$

$$R_3 = \dfrac{M \left(4 L a^{2} + 2 L a b + 6 L a c + L b^{2} + 6 L b c - 4 a^{3} - 6 a^{2} b - 6 a^{2} c - 3 a b^{2} - 12 a b c - 3 a c^{2} - b^{3} - 6 b^{2} c - 3 b c^{2}\right)}{2 L \left(L^{2} a + L^{2} b - 2 L a^{2} - 4 L a b - 2 L b^{2} + a^{3} + 3 a^{2} b + 3 a b^{2} + b^{3}\right)}$$

#### Equações em Python
```python
# Flechas
deltaA = M*x*(-4*L**2*a**3 - 12*L**2*a**2*b - 6*L**2*a*b**2 + 4*L**2*a*x**2 + 2*L**2*b**3 + 4*L**2*b*x**2 + 8*L*a**4 + 26*L*a**3*b + 6*L*a**3*c + 27*L*a**2*b**2 + 18*L*a**2*b*c - 8*L*a**2*x**2 + 8*L*a*b**3 + 18*L*a*b**2*c - 10*L*a*b*x**2 - 6*L*a*c*x**2 - L*b**4 + 6*L*b**3*c - 5*L*b**2*x**2 - 6*L*b*c*x**2 - 4*a**5 - 14*a**4*b - 6*a**4*c - 19*a**3*b**2 - 24*a**3*b*c - 3*a**3*c**2 + 4*a**3*x**2 - 13*a**2*b**3 - 36*a**2*b**2*c - 9*a**2*b*c**2 + 6*a**2*b*x**2 + 6*a**2*c*x**2 - 5*a*b**4 - 24*a*b**3*c - 9*a*b**2*c**2 + 3*a*b**2*x**2 + 12*a*b*c*x**2 + 3*a*c**2*x**2 - b**5 - 6*b**4*c - 3*b**3*c**2 + b**3*x**2 + 6*b**2*c*x**2 + 3*b*c**2*x**2)/(12*E*I*L*(-L*a**2 - 2*L*a*b - L*b**2 + a**3 + 3*a**2*b + 3*a*b**2 + b**3))
deltaB = M*(-6*L**2*a**4 - 12*L**2*a**3*b + 8*L**2*a**3*x - 6*L**2*a**2*b**2 + 12*L**2*a**2*b*x - 6*L**2*a**2*x**2 + 6*L**2*a*b**2*x - 12*L**2*a*b*x**2 + 4*L**2*a*x**3 + 2*L**2*b**3*x - 6*L**2*b**2*x**2 + 4*L**2*b*x**3 + 6*L*a**5 + 18*L*a**4*b - 4*L*a**4*x + 18*L*a**3*b**2 - 10*L*a**3*b*x + 6*L*a**3*c*x + 6*L*a**3*x**2 + 6*L*a**2*b**3 - 9*L*a**2*b**2*x + 18*L*a**2*b*c*x + 18*L*a**2*b*x**2 - 8*L*a**2*x**3 - 4*L*a*b**3*x + 18*L*a*b**2*c*x + 18*L*a*b**2*x**2 - 10*L*a*b*x**3 - 6*L*a*c*x**3 - L*b**4*x + 6*L*b**3*c*x + 6*L*b**3*x**2 - 5*L*b**2*x**3 - 6*L*b*c*x**3 - 4*a**5*x - 14*a**4*b*x - 6*a**4*c*x - 19*a**3*b**2*x - 24*a**3*b*c*x - 3*a**3*c**2*x + 4*a**3*x**3 - 13*a**2*b**3*x - 36*a**2*b**2*c*x - 9*a**2*b*c**2*x + 6*a**2*b*x**3 + 6*a**2*c*x**3 - 5*a*b**4*x - 24*a*b**3*c*x - 9*a*b**2*c**2*x + 3*a*b**2*x**3 + 12*a*b*c*x**3 + 3*a*c**2*x**3 - b**5*x - 6*b**4*c*x - 3*b**3*c**2*x + b**3*x**3 + 6*b**2*c*x**3 + 3*b*c**2*x**3)/(12*E*I*L*(-L*a**2 - 2*L*a*b - L*b**2 + a**3 + 3*a**2*b + 3*a*b**2 + b**3))
deltaC = M*(2*L**3*a**3 - 6*L**3*a**2*b + 4*L**3*a**2*x - 12*L**3*a*b**2 + 20*L**3*a*b*x - 6*L**3*a*x**2 - 4*L**3*b**3 + 10*L**3*b**2*x - 6*L**3*b*x**2 + 18*L**2*a**3*b + 6*L**2*a**3*c - 24*L**2*a**3*x + 45*L**2*a**2*b**2 + 18*L**2*a**2*b*c - 72*L**2*a**2*b*x - 24*L**2*a**2*c*x + 24*L**2*a**2*x**2 + 36*L**2*a*b**3 + 18*L**2*a*b**2*c - 72*L**2*a*b**2*x - 48*L**2*a*b*c*x + 30*L**2*a*b*x**2 + 18*L**2*a*c*x**2 + 9*L**2*b**4 + 6*L**2*b**3*c - 24*L**2*b**3*x - 24*L**2*b**2*c*x + 15*L**2*b**2*x**2 + 18*L**2*b*c*x**2 - 2*L*a**5 - 16*L*a**4*b - 6*L*a**4*c + 24*L*a**4*x - 41*L*a**3*b**2 - 24*L*a**3*b*c + 78*L*a**3*b*x - 3*L*a**3*c**2 + 30*L*a**3*c*x - 18*L*a**3*x**2 - 47*L*a**2*b**3 - 36*L*a**2*b**2*c + 99*L*a**2*b**2*x - 9*L*a**2*b*c**2 + 90*L*a**2*b*c*x - 36*L*a**2*b*x**2 + 12*L*a**2*c**2*x - 18*L*a**2*c*x**2 - 4*L*a**2*x**3 - 25*L*a*b**4 - 24*L*a*b**3*c + 60*L*a*b**3*x - 9*L*a*b**2*c**2 + 90*L*a*b**2*c*x - 27*L*a*b**2*x**2 + 24*L*a*b*c**2*x - 36*L*a*b*c*x**2 - 2*L*a*b*x**3 - 9*L*a*c**2*x**2 - 6*L*a*c*x**3 - 5*L*b**5 - 6*L*b**4*c + 15*L*b**4*x - 3*L*b**3*c**2 + 30*L*b**3*c*x - 9*L*b**3*x**2 + 12*L*b**2*c**2*x - 18*L*b**2*c*x**2 - L*b**2*x**3 - 9*L*b*c**2*x**2 - 6*L*b*c*x**3 - 4*a**5*x - 14*a**4*b*x - 6*a**4*c*x - 19*a**3*b**2*x - 24*a**3*b*c*x - 3*a**3*c**2*x + 4*a**3*x**3 - 13*a**2*b**3*x - 36*a**2*b**2*c*x - 9*a**2*b*c**2*x + 6*a**2*b*x**3 + 6*a**2*c*x**3 - 5*a*b**4*x - 24*a*b**3*c*x - 9*a*b**2*c**2*x + 3*a*b**2*x**3 + 12*a*b*c*x**3 + 3*a*c**2*x**3 - b**5*x - 6*b**4*c*x - 3*b**3*c**2*x + b**3*x**3 + 6*b**2*c*x**3 + 3*b*c**2*x**3)/(12*E*I*L*(L**2*a + L**2*b - 2*L*a**2 - 4*L*a*b - 2*L*b**2 + a**3 + 3*a**2*b + 3*a*b**2 + b**3))
deltaD = M*(8*L**3*a**3 + 12*L**3*a**2*b + 12*L**3*a**2*c - 8*L**3*a**2*x + 6*L**3*a*b**2 + 24*L**3*a*b*c - 4*L**3*a*b*x + 6*L**3*a*c**2 - 12*L**3*a*c*x + 2*L**3*b**3 + 12*L**3*b**2*c - 2*L**3*b**2*x + 6*L**3*b*c**2 - 12*L**3*b*c*x - 12*L**2*a**4 - 30*L**2*a**3*b - 18*L**2*a**3*c - 27*L**2*a**2*b**2 - 54*L**2*a**2*b*c - 12*L**2*a**2*c**2 + 12*L**2*a**2*x**2 - 12*L**2*a*b**3 - 54*L**2*a*b**2*c - 24*L**2*a*b*c**2 + 6*L**2*a*b*x**2 + 18*L**2*a*c*x**2 - 3*L**2*b**4 - 18*L**2*b**3*c - 12*L**2*b**2*c**2 + 3*L**2*b**2*x**2 + 18*L**2*b*c*x**2 + 4*L*a**5 + 14*L*a**4*b + 6*L*a**4*c + 12*L*a**4*x + 19*L*a**3*b**2 + 24*L*a**3*b*c + 30*L*a**3*b*x + 3*L*a**3*c**2 + 18*L*a**3*c*x - 12*L*a**3*x**2 + 13*L*a**2*b**3 + 36*L*a**2*b**2*c + 27*L*a**2*b**2*x + 9*L*a**2*b*c**2 + 54*L*a**2*b*c*x - 18*L*a**2*b*x**2 + 12*L*a**2*c**2*x - 18*L*a**2*c*x**2 - 4*L*a**2*x**3 + 5*L*a*b**4 + 24*L*a*b**3*c + 12*L*a*b**3*x + 9*L*a*b**2*c**2 + 54*L*a*b**2*c*x - 9*L*a*b**2*x**2 + 24*L*a*b*c**2*x - 36*L*a*b*c*x**2 - 2*L*a*b*x**3 - 9*L*a*c**2*x**2 - 6*L*a*c*x**3 + L*b**5 + 6*L*b**4*c + 3*L*b**4*x + 3*L*b**3*c**2 + 18*L*b**3*c*x - 3*L*b**3*x**2 + 12*L*b**2*c**2*x - 18*L*b**2*c*x**2 - L*b**2*x**3 - 9*L*b*c**2*x**2 - 6*L*b*c*x**3 - 4*a**5*x - 14*a**4*b*x - 6*a**4*c*x - 19*a**3*b**2*x - 24*a**3*b*c*x - 3*a**3*c**2*x + 4*a**3*x**3 - 13*a**2*b**3*x - 36*a**2*b**2*c*x - 9*a**2*b*c**2*x + 6*a**2*b*x**3 + 6*a**2*c*x**3 - 5*a*b**4*x - 24*a*b**3*c*x - 9*a*b**2*c**2*x + 3*a*b**2*x**3 + 12*a*b*c*x**3 + 3*a*c**2*x**3 - b**5*x - 6*b**4*c*x - 3*b**3*c**2*x + b**3*x**3 + 6*b**2*c*x**3 + 3*b*c**2*x**3)/(12*E*I*L*(L**2*a + L**2*b - 2*L*a**2 - 4*L*a*b - 2*L*b**2 + a**3 + 3*a**2*b + 3*a*b**2 + b**3))
# Momentos fletores
MA = M*x*(4*L**2*a + 4*L**2*b - 8*L*a**2 - 10*L*a*b - 6*L*a*c - 5*L*b**2 - 6*L*b*c + 4*a**3 + 6*a**2*b + 6*a**2*c + 3*a*b**2 + 12*a*b*c + 3*a*c**2 + b**3 + 6*b**2*c + 3*b*c**2)/(2*L*(-L*a**2 - 2*L*a*b - L*b**2 + a**3 + 3*a**2*b + 3*a*b**2 + b**3))
MB = M*(-2*L**2*a**2 - 4*L**2*a*b + 4*L**2*a*x - 2*L**2*b**2 + 4*L**2*b*x + 2*L*a**3 + 6*L*a**2*b - 8*L*a**2*x + 6*L*a*b**2 - 10*L*a*b*x - 6*L*a*c*x + 2*L*b**3 - 5*L*b**2*x - 6*L*b*c*x + 4*a**3*x + 6*a**2*b*x + 6*a**2*c*x + 3*a*b**2*x + 12*a*b*c*x + 3*a*c**2*x + b**3*x + 6*b**2*c*x + 3*b*c**2*x)/(2*L*(-L*a**2 - 2*L*a*b - L*b**2 + a**3 + 3*a**2*b + 3*a*b**2 + b**3))
MC = M*(-2*L**3*a - 2*L**3*b + 8*L**2*a**2 + 10*L**2*a*b + 6*L**2*a*c + 5*L**2*b**2 + 6*L**2*b*c - 6*L*a**3 - 12*L*a**2*b - 6*L*a**2*c - 4*L*a**2*x - 9*L*a*b**2 - 12*L*a*b*c - 2*L*a*b*x - 3*L*a*c**2 - 6*L*a*c*x - 3*L*b**3 - 6*L*b**2*c - L*b**2*x - 3*L*b*c**2 - 6*L*b*c*x + 4*a**3*x + 6*a**2*b*x + 6*a**2*c*x + 3*a*b**2*x + 12*a*b*c*x + 3*a*c**2*x + b**3*x + 6*b**2*c*x + 3*b*c**2*x)/(2*L*(L**2*a + L**2*b - 2*L*a**2 - 4*L*a*b - 2*L*b**2 + a**3 + 3*a**2*b + 3*a*b**2 + b**3))
MD = M*(4*L**2*a**2 + 2*L**2*a*b + 6*L**2*a*c + L**2*b**2 + 6*L**2*b*c - 4*L*a**3 - 6*L*a**2*b - 6*L*a**2*c - 4*L*a**2*x - 3*L*a*b**2 - 12*L*a*b*c - 2*L*a*b*x - 3*L*a*c**2 - 6*L*a*c*x - L*b**3 - 6*L*b**2*c - L*b**2*x - 3*L*b*c**2 - 6*L*b*c*x + 4*a**3*x + 6*a**2*b*x + 6*a**2*c*x + 3*a*b**2*x + 12*a*b*c*x + 3*a*c**2*x + b**3*x + 6*b**2*c*x + 3*b*c**2*x)/(2*L*(L**2*a + L**2*b - 2*L*a**2 - 4*L*a*b - 2*L*b**2 + a**3 + 3*a**2*b + 3*a*b**2 + b**3))
# Esforços cortantes
VA = M*(4*L**2*a + 4*L**2*b - 8*L*a**2 - 10*L*a*b - 6*L*a*c - 5*L*b**2 - 6*L*b*c + 4*a**3 + 6*a**2*b + 6*a**2*c + 3*a*b**2 + 12*a*b*c + 3*a*c**2 + b**3 + 6*b**2*c + 3*b*c**2)/(2*L*(-L*a**2 - 2*L*a*b - L*b**2 + a**3 + 3*a**2*b + 3*a*b**2 + b**3))
VB = M*(4*L**2*a + 4*L**2*b - 8*L*a**2 - 10*L*a*b - 6*L*a*c - 5*L*b**2 - 6*L*b*c + 4*a**3 + 6*a**2*b + 6*a**2*c + 3*a*b**2 + 12*a*b*c + 3*a*c**2 + b**3 + 6*b**2*c + 3*b*c**2)/(2*L*(-L*a**2 - 2*L*a*b - L*b**2 + a**3 + 3*a**2*b + 3*a*b**2 + b**3))
VC = M*(-4*L*a**2 - 2*L*a*b - 6*L*a*c - L*b**2 - 6*L*b*c + 4*a**3 + 6*a**2*b + 6*a**2*c + 3*a*b**2 + 12*a*b*c + 3*a*c**2 + b**3 + 6*b**2*c + 3*b*c**2)/(2*L*(L**2*a + L**2*b - 2*L*a**2 - 4*L*a*b - 2*L*b**2 + a**3 + 3*a**2*b + 3*a*b**2 + b**3))
VD = M*(-4*L*a**2 - 2*L*a*b - 6*L*a*c - L*b**2 - 6*L*b*c + 4*a**3 + 6*a**2*b + 6*a**2*c + 3*a*b**2 + 12*a*b*c + 3*a*c**2 + b**3 + 6*b**2*c + 3*b*c**2)/(2*L*(L**2*a + L**2*b - 2*L*a**2 - 4*L*a*b - 2*L*b**2 + a**3 + 3*a**2*b + 3*a*b**2 + b**3))
# Reações de apoio
R1 = M*(4*L**2*a + 4*L**2*b - 8*L*a**2 - 10*L*a*b - 6*L*a*c - 5*L*b**2 - 6*L*b*c + 4*a**3 + 6*a**2*b + 6*a**2*c + 3*a*b**2 + 12*a*b*c + 3*a*c**2 + b**3 + 6*b**2*c + 3*b*c**2)/(2*L*(-L*a**2 - 2*L*a*b - L*b**2 + a**3 + 3*a**2*b + 3*a*b**2 + b**3))
R2 = M*(4*L**2*a + 4*L**2*b - 12*L*a**2 - 18*L*a*b - 6*L*a*c - 9*L*b**2 - 6*L*b*c + 8*a**3 + 18*a**2*b + 6*a**2*c + 15*a*b**2 + 12*a*b*c + 3*a*c**2 + 5*b**3 + 6*b**2*c + 3*b*c**2)/(2*(L**2*a**2 + 2*L**2*a*b + L**2*b**2 - 2*L*a**3 - 6*L*a**2*b - 6*L*a*b**2 - 2*L*b**3 + a**4 + 4*a**3*b + 6*a**2*b**2 + 4*a*b**3 + b**4))
R3 = M*(4*L*a**2 + 2*L*a*b + 6*L*a*c + L*b**2 + 6*L*b*c - 4*a**3 - 6*a**2*b - 6*a**2*c - 3*a*b**2 - 12*a*b*c - 3*a*c**2 - b**3 - 6*b**2*c - 3*b*c**2)/(2*L*(L**2*a + L**2*b - 2*L*a**2 - 4*L*a*b - 2*L*b**2 + a**3 + 3*a**2*b + 3*a*b**2 + b**3))
```

---
