# 🌈 SpectraLab

**SpectraLab** é uma calculadora interativa que converte valores de energia em elétron-volts (eV) para **frequência (Hz)** e **comprimento de onda (μm)**. O projeto também identifica a **cor correspondente** dentro do espectro visível, sendo uma ferramenta útil para estudos de física, química, espectroscopia e áreas relacionadas.

## 🧪 Funcionalidades

- Inserção de valores em **eV**, **frequência (Hz)** ou **comprimento de onda (μm)**.
- Cálculo automático dos outros dois valores com base na entrada.
- Identificação da cor no espectro visível correspondente ao comprimento de onda.
- Adição dinâmica de múltiplas linhas de cálculo.
- Exportação dos dados como **arquivo CSV**, incluindo fórmulas do Excel/LibreOffice.

## 🔬 Fórmulas Utilizadas

- **Conversão de eV para J**  
  `E (J) = eV × 1.602 × 10⁻¹⁹`

- **Frequência:**  
  `f = E / h`

- **Comprimento de onda:**  
  `λ = c / f`

> Onde:  
> - `h = 6.626 × 10⁻³⁴ J·s` (Constante de Planck)  
> - `c = 3.0 × 10⁸ m/s` (Velocidade da luz)

## 🎨 Faixas de Cor (Espectro Visível)

- **Vermelho:** 0.62 – 0.75 μm  
- **Laranja:** 0.59 – 0.62 μm  
- **Amarelo:** 0.57 – 0.59 μm  
- **Verde:** 0.495 – 0.57 μm  
- **Azul:** 0.45 – 0.495 μm  
- **Violeta:** 0.38 – 0.45 μm

Valores fora dessa faixa são classificados como **Infravermelho** ou **Ultravioleta**.

## 💻 Como usar

1. Abra o arquivo `index.html` em qualquer navegador moderno.
2. Insira um valor em qualquer uma das colunas (eV, Hz ou μm).
3. O sistema calculará automaticamente os demais campos e exibirá a cor.
4. Clique em **"Adicionar Linha"** para inserir novos valores.
5. Clique em **"Exportar como CSV"** para gerar um arquivo compatível com planilhas.