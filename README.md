# TaxFlow Varejo 📊

**TaxFlow Varejo** é uma ferramenta de suporte à decisão desenvolvida para automatizar o cálculo de ICMS por Substituição Tributária (ICMS-ST) em operações interestaduais, com foco inicial no varejo supermercadista do estado do Pará.

---

## 🚀 O Problema
No varejo supermercadista, o cálculo manual de impostos na entrada de mercadorias é suscetível a erros humanos, o que pode resultar em precificação incorreta, multas fiscais ou perda de margem de lucro. 

## 💡 A Solução
Este sistema simplifica a complexidade fiscal, permitindo que gestores administrativos e PMs de varejo calculem em segundos:
- Crédito de ICMS da operação própria.
- Base de Cálculo da Substituição Tributária (BC-ST).
- Valor final do ICMS-ST a recolher.
- Custo real de aquisição da mercadoria (Valor nominal + Impostos).

## 🛠️ Tecnologias Utilizadas
- **HTML5/CSS3:** Interface responsiva e limpa.
- **JavaScript (Vanilla):** Lógica de cálculo e processamento de dados.
- **GitHub Pages:** Hospedagem e deploy contínuo.

## 📈 Regra de Negócio & Lógica de Cálculo
O sistema utiliza a fórmula padrão de Substituição Tributária:

1.  **Crédito:** $Valor_{Produto} \times Alíquota_{Interestadual}$
2.  **Base ST:** $Valor_{Produto} \times (1 + MVA)$
3.  **Débito ST:** $(Base_{ST} \times Alíquota_{Interna}) - Crédito$
4.  **Custo Real:** $Valor_{Produto} + Débito_{ST}$

> **Nota:** Este projeto foi desenvolvido como parte de um estudo de viabilidade para ferramentas de auxílio à gestão de produtos digitais no setor varejista.

## 🏁 Como Utilizar
1. Acesse o link do projeto: `[SEU-LINK-AQUI]`
2. Insira o valor da mercadoria.
3. Informe a alíquota interestadual (origem) e a alíquota interna (destino).
4. Insira o MVA (Margem de Valor Agregado) do produto.
5. Clique em **Calcular** para obter o custo real e os impostos.

## 🔮 Backlog de Futuras Implementações (Visão de PM)
- [ ] Implementação de **MVA Ajustado** automático.
- [ ] Integração com banco de dados para consulta de alíquotas por UF.
- [ ] Exportação de relatórios em CSV/Excel para análise de dados.
- [ ] Gráfico comparativo de impacto tributário por categoria de produto.

---
Desenvolvido por **[Seu Nome]**
*Gerente Administrativo | IA Product Manager & Data Analyst em formação.*
