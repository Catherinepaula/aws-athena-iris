# AWS Athena com Dataset Iris (EBAC - Módulo 37)

Este projeto foi desenvolvido como parte do curso Profissão Analista de Dados (Módulo 37) da EBAC, com o objetivo de aplicar serviços da AWS no processo de extração, armazenamento e análise de dados.

## 🧩 Tecnologias utilizadas
- **AWS S3**: armazenamento de dados brutos (CSV)
- **AWS Athena**: criação de tabela externa e execução de consultas SQL
- **Google Colab**: geração e exportação do dataset
- **OpenCSVSerde**: parser para CSVs no Athena

## 📊 Descrição do projeto
O projeto consiste em:

1. Geração do dataset `iris.csv` via Colab (com sklearn)
2. Upload no bucket S3
3. Criação de tabela externa no Athena apontando para o bucket
4. Execução de queries analíticas usando SQL
5. Documentação no notebook com imagens dos resultados

## 📂 Estrutura
- `M37_AWS_Athena_iris_dataset_com_prints.ipynb`: notebook com todos os passos e prints

## ✅ Status
✔️ Finalizado e funcional

---
*Projeto realizado por Catherine Paula Chitolina Cornelio – Junho de 2025*
