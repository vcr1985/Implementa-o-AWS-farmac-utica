# Projeto de Otimização de Custos com AWS - Abstergo Industries

## 🧾 Descrição
Este relatório documenta a implementação de serviços da AWS na empresa **Abstergo Industries**, com o objetivo de reduzir custos operacionais e aumentar a eficiência dos recursos computacionais. O projeto identificou três ferramentas essenciais para otimização de infraestrutura, armazenamento e monitoramento financeiro em nuvem.

---

## 🚀 Tecnologias AWS Utilizadas

- **Amazon EC2 Auto Scaling**
- **Amazon S3 com Intelligent-Tiering**
- **AWS Cost Explorer e AWS Budgets**

---

## 📅 Dados do Projeto

- **Data de Início:** 24/06/2025  
- **Empresa:** Abstergo Industries  
- **Responsável:** Vando Ramos  

---

## 🧩 Etapas da Implementação

### Etapa 1: Amazon EC2 Auto Scaling
- **Foco:** Escalabilidade automática e redução de custo com servidores ociosos
- **Descrição:**  
  A empresa mantinha instâncias em funcionamento 24/7 mesmo com baixa demanda em horários específicos. Com EC2 Auto Scaling, agora as instâncias escalam automaticamente conforme a carga de trabalho.

#### 📊 Economia com Auto Scaling:
![economia-servidores](anexos/graficos/economia-servidores.png)

---

### Etapa 2: Amazon S3 com Intelligent-Tiering
- **Foco:** Armazenamento automático baseado em frequência de acesso
- **Descrição:**  
  Dados laboratoriais e históricos médicos foram migrados para o Amazon S3 com política Intelligent-Tiering. Arquivos não acessados com frequência são movidos para camadas mais baratas automaticamente.

#### 📊 Economia com S3 Intelligent-Tiering:
![economia-armazenamento](anexos/graficos/economia-armazenamento.png)

---

### Etapa 3: AWS Cost Explorer + Budgets
- **Foco:** Monitoramento de gastos e alertas de orçamento
- **Descrição:**  
  Com o Cost Explorer e Budgets, cada departamento agora acompanha seus gastos e recebe alertas de consumo. Isso facilita o planejamento financeiro e evita surpresas no faturamento da AWS.

#### 📊 Projeção de Orçamento Mensal:
![previsao-orcamento](anexos/graficos/previsao-orcamento.png)

---

## 📈 Resultados Esperados

- 💰 Redução de até **40%** nos custos com instâncias EC2
- 💾 Redução de até **60%** nos custos de armazenamento
- 📉 Eliminação de gastos excedentes por meio de **alertas e orçamentos automáticos**

---

## 📂 Estrutura Sugerida do Repositório

📁 aws-cost-optimization/
├── relatorio_abstergo_aws.md
├── anexos/
│ ├── politica_s3.pdf
│ ├── relatorio_custos_before_after.xlsx
│ ├── manual_ec2_auto_scaling.pdf
│ └── graficos/
│ ├── economia-servidores.png
│ ├── economia-armazenamento.png
│ └── previsao-orcamento.png


---

## 📌 Conclusão

A adoção dos serviços AWS recomendados proporcionou ganhos imediatos para a **Abstergo Industries**, com redução de custos, automação inteligente de infraestrutura e maior visibilidade financeira.  
A continuidade do uso dessas ferramentas, bem como a expansão para outros serviços como **AWS Lambda**, **Amazon RDS** e **AWS Backup**, é altamente recomendada.

---

## 📎 Anexos

- 📄 `manual_ec2_auto_scaling.pdf`  
- 📄 `politica_s3.pdf`  
- 📊 `relatorio_custos_before_after.xlsx`  
- 📁 `graficos/*.png`  

---

## ✍️ Autor

**Vando Ramos**  
Engenheiro de Soluções em Nuvem (simulação)

📧 E-mail: [ramosvando@gmail.com](mailto:ramosvando@gmail.com)  
🔗 LinkedIn: [www.linkedin.com/in/vcr1985-br](https://www.linkedin.com/in/vcr1985-br)

---

*Relatório gerado automaticamente para fins acadêmicos e profissionais.*


