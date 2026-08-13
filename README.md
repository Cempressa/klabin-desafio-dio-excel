# 📊 Xbox Game Subscription Sales Dashboard  
### Klabin – Excel Dashboards (DIO)

Este repositório contém o **Dashboard de Vendas de Assinaturas Xbox**, desenvolvido como entrega do desafio do curso **Klabin – Excel Dashboards**, da plataforma DIO.

O objetivo do projeto é transformar uma base de assinaturas em **insights visuais**, utilizando **Excel**, tabelas dinâmicas, segmentadores e gráficos interativos.

---

## 📁 Estrutura do Repositório

📦 klabin-desafio-dio-excel
┣ 📁 assets/              → imagens usadas no README
┣ 📁 data/                → base de dados original (opcional)
┣ 📄 Dashboard_Xbox.xlsx  → dashboard final em Excel
┗ 📄 README.md            → documentação do projeto

---

## 📄 Sobre o Projeto

O dashboard apresenta uma visão clara e objetiva sobre:

- Faturamento total por tipo de assinatura  
- Comparação entre assinaturas com e sem renovação automática  
- Vendas de passes adicionais (EA Play e Minecraft Season Pass)  
- Distribuição dos planos (Core, Standard, Ultimate)  
- Evolução das assinaturas ao longo do tempo  

A proposta é permitir uma análise rápida e visual da performance das assinaturas Xbox.

---

## 🗂️ Dados Utilizados

A base contém milhares de registros, incluindo:

- **Subscriber ID**  
- **Name**  
- **Plan** (Core, Standard, Ultimate)  
- **Start Date**  
- **Auto Renewal** (Yes/No)  
- **Subscription Price**  
- **Subscription Type** (Monthly, Quarterly, Annual)  
- **EA Play Season Pass** + Price  
- **Minecraft Season Pass** + Price  
- **Coupon Value**  
- **Total Value** (faturamento final por assinatura)

Trecho da base (extraído do arquivo):

> “Subscriber ID — Name — Plan — Start Date — Auto Renewal — Subscription Price — Subscription Type — EA Play Season Pass — EA Play Season Pass Price — Minecraft Season Pass Price — Coupon Value — Total Value.”

---

## 🧮 Cálculos de Negócio

A análise responde perguntas importantes, como:

### **1️⃣ Faturamento total de planos anuais**  
Somatório de todas as assinaturas com **Subscription Type = Annual**.

### **2️⃣ Faturamento total de planos anuais por renovação automática**  
Separação entre:
- Auto Renewal = Yes  
- Auto Renewal = No  

Trecho da tabela presente no arquivo:

> “Auto Renewal — No: 2824 — Yes: 747 — Total Geral: 3571.”

### **3️⃣ Total de vendas do EA Play Season Pass**  
> “Ultimate: 1350 — Total Geral: 1350.”

### **4️⃣ Total de vendas do Minecraft Season Pass**  
> “Standard: 900 — Ultimate: 900 — Total Geral: 1800.”

Esses valores foram utilizados como KPIs no dashboard.

---

## 📊 Dashboard (Excel)

O dashboard foi construído com:

- Tabelas dinâmicas  
- Gráficos dinâmicos  
- Segmentadores (Slicers)  
- Paleta de cores fornecida no arquivo  
- Indicadores de faturamento  
- KPIs por plano e tipo de assinatura  

Título do dashboard conforme o arquivo:

> “XBOX GAME SUBSCRIPTION SALES”

---

## 📸 Imagens do Dashboard

*(Adicione aqui prints do seu arquivo Excel)*

---

## 🛠️ Como Reproduzir

1. Baixe o arquivo **Dashboard_Xbox.xlsx**  
2. Abra no Excel (versão 2016 ou superior recomendada)  
3. Navegue pelas abas:
   - Dados  
   - Tabelas Dinâmicas  
   - Dashboard  
4. Utilize os segmentadores para filtrar:
   - Plano  
   - Tipo de assinatura  
   - Renovação automática  
5. Explore os gráficos e KPIs interativos

---

## 🎓 Curso

Este projeto foi desenvolvido como parte do curso:

**Klabin – Excel Dashboards (DIO)**

