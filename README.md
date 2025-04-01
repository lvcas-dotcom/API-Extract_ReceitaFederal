# 🚀 API de Extração de Dados CNPJ & Simples Nacional  

🔍 **Uma API para extrair dados do CNPJ e do Simples Nacional diretamente da Receita Federal!**  

---

## 🛠️ Sobre o Projeto  

Esta API permite a extração eficiente dos dados do **CNPJ** disponibilizados pela **Receita Federal**, incluindo informações do **Simples Nacional**. A versão original apresentava algumas desatualizações, então realizei melhorias e ajustes para garantir seu pleno funcionamento.  

📌 **Principais Atualizações:**  
✅ Correções em endpoints desatualizados  
✅ Melhorias na performance da extração  
✅ Ajustes para compatibilidade com versões recentes  

📜 **Todos os créditos estão no arquivo [`LICENSE`](./LICENSE)**.  

---

## 🔄 Como Funciona?  

1️⃣ **Coleta:** A API baixa os arquivos disponibilizados pela Receita Federal.  
2️⃣ **Extração:** Os arquivos são descompactados na pasta especificada no script.  
3️⃣ **Banco de Dados:** Cria uma database no banco de dados escolhido.  
4️⃣ **Estruturação:** Gera automaticamente as tabelas necessárias.  
5️⃣ **Carga:** Insere os dados extraídos diretamente no banco.  

## 📊 Estrutura do Banco  

![Estrutura do Banco](https://github.com/aphonsoar/Receita_Federal_do_Brasil_-_Dados_Publicos_CNPJ/blob/master/Dados_RFB_ERD.png)  

---

## 🚀 Como Usar  

1️⃣ Clone o repositório  
2️⃣ Configure o arquivo .env_template
3️⃣ Rode a API apartir do arquivo .py
```bash
git clone https://github.com/lvcas-dotcom/API-Extract_ReceitaFederal.git
