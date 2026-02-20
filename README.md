# Projeto de Cálculo de Tensão em Engrenagens -  Equação de Lewis (AGMA-Mott)

Clique no botão abaixo para executar o calculador de Sigma diretamente no seu navegador:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/SeuUsuario/SeuRepositorio/blob/main/calculo_sigma.ipynb)
---
## 🛠️ Funcionalidades
* **Busca Automática de $Y_J$:** O script possui um banco de dados interno que associa o número de dentes ($Z$) ao fator geométrico correspondente.
* **Interface Amigável:** Utiliza formulários do Google Colab para entrada de dados (Força Tangencial, Módulo, Largura da Face).
* **Visualização Gráfica:** Gera gráficos da curva de comportamento do fator $Y_J$.

## 📐 Base de Cálculo
A equação implementada é:
$$\sigma = \frac{F_t}{b \cdot m_n \cdot Y_J}$$

Onde:
* **$F_t$**: Força Tangencial (N)
* **$b$**: Largura da face (mm)
* **$m_n$**: Módulo normal
* **$Y_J$**: Fator geométrico (obtido via tabela AGMA)

---
**Desenvolvido por:** Eng. [David Lira Nunez]
