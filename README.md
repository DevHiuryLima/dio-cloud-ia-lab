# Desafio DIO – Criação e Configuração de Instância de Banco de Dados no Azure

## 🔍 Entendendo o Desafio
Este repositório documenta o **processo de criação e configuração de uma instância de banco de dados gerenciada** na plataforma Microsoft Azure, aplicando os conceitos vistos até aqui no bootcamp.

## 🎯 Descrição do Desafio
- Criar uma **Instância Gerenciada de Banco de Dados** (Azure SQL Managed Instance) ou **Banco de Dados SQL** no Azure usando o **Portal** (sem pular etapas).  
- Documentar **resumos**, **anotações** e **dicas** sobre cada passo.  
- Entregar tudo em um repositório público no GitHub, contendo:  
  - `README.md` detalhado  
  - Pasta `/images/` com capturas de tela  
  - Arquivos adicionais (ex.: `resumo.md`, `dicas.md`)

> **Referência oficial**:  
> [Início Rápido: Criar Instância Gerenciada de SQL do Azure](https://learn.microsoft.com/pt-br/azure/azure-sql/managed-instance/instance-create-quickstart?view=azuresql&tabs=azure-portal)

## 📝 Objetivos de Aprendizagem
- Aplicar conceitos de serviços de nuvem para bancos de dados (IaaS vs PaaS).  
- Configurar rede, segurança e firewall para acesso ao banco.  
- Documentar processos técnicos de forma clara e estruturada.  
- Usar o GitHub como ferramenta de versionamento e compartilhamento.

## ⚙️ Ferramentas e Tecnologias
- **Microsoft Azure Portal**  
- **Azure CLI** (opcional)  
- **Azure Data Studio** ou **SQL Server Management Studio**  
- **Visual Studio Code**  
- **Git & GitHub**  
- **Markdown** para documentação

## 🚀 Passo a Passo Executado

1. **Login no Azure Portal**  
   - Acesse o portal e faça login com sua conta.

2. **Guia Básico**  
   - Selecione assinatura e grupo de recursos.  
   - Informe nome do banco de dados e escolha/crie um servidor.  
   - Defina tier (compute + armazenamento) e opções de backup.

3. **Guia Rede**  
   - Configure regras de firewall para permitir seu IP.  
   - Ajuste endpoints privados ou públicos conforme necessário.

4. **Guia Segurança**  
   - Habilite (ou não) o Microsoft Defender para SQL.  
   - Configure Transparent Data Encryption e identidades gerenciadas.

5. **Guia Configurações Adicionais**  
   - Escolha dados de inicialização (em branco, amostra ou restore).  
   - Defina collation se precisar de padrão diferente.

6. **Guia Rótulos**  
   - Adicione tags (nome/valor) para organização e cobrança.

7. **Revisar + Criar**  
   - Revise todas as configurações e clique em **Criar**.  
   - Aguarde a implantação e verifique o status da instância.  
