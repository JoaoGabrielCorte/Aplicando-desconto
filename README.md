Projeto ABAP: Cálculo de Desconto

Este é um projeto simulado em ABAP desenvolvido no VS Code, com o objetivo de treinar lógica de programação sem a necessidade de um sistema SAP conectado.

---

Objetivo

Praticar conceitos fundamentais de programação ABAP, com foco em:

- Declaração e uso de variáveis
- Tipos de dados numéricos com ponto fixo (`p decimals`)
- Entrada e processamento de dados simulados
- Cálculo percentual
- Exibição de resultados no console com `WRITe`

---

O que o código faz?

O programa simula uma situação de compra com desconto:

- Valor da compra: informado diretamente na variável `v_valor_compra
- Percentual de desconto: definido em `v_percentual_desc`
- Valor do desconto: calculado automaticamente
- Total final: valor da compra com desconto aplicado

---

Principais variáveis

DATA: 
    v_valor_compra      TYPE p DECIMALS 2,  " valor original da compra
    v_percentual_desc   TYPE p DECIMALS 2,  " percentual de desconto (ex: 10%)
    v_valor_desconto    TYPE p DECIMALS 2,  " valor calculado do desconto
    v_total_final       TYPE p DECIMALS 2.  " valor final a ser pago
