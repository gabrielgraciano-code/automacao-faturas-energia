# ⚡ Automação de Captura e Processamento de Faturas de Energia

Sistema automatizado desenvolvido em Python para captura, download e extração estruturada de dados de faturas de energia elétrica das concessionárias **Energisa**, **CELPE (Neoenergia PE)** e **Cosern (Neoenergia RN)**.

## 📌 Funcionalidades
- **Navegação e Extração Automática:** Automação de rotinas de login e download de PDFs em portais de concessionárias.
- **Processamento de PDFs:** Leitura e extração de metadados críticos das faturas (datas de vencimento, valores, consumo em kWh, tarifas e compensações de Geração Distribuída).
- **Estruturação de Dados:** Organização automatizada das informações extraídas para planilhas e integração com relatórios analíticos.

## 🛠️ Tecnologias Utilizadas
- **Linguagem:** Python
- **Automação Web:** Playwright / Selenium
- **Extração de Dados em PDF:** `pdfplumber` / `PyMuPDF`
- **Manipulação de Dados:** Pandas / `openpyxl`
- **Integração:** Gmail API (para captura de faturas recebidas por e-mail)

## 🎯 Objetivo do Projeto
Eliminar tarefas manuais e repetitivas de gestão de faturas no setor elétrico, reduzindo erros operacionais e garantindo agilidade na consolidação de dados para auditoria e alocação de créditos de energia.
