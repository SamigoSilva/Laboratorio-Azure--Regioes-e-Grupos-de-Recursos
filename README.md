# 🌐 Laboratório Azure: Regiões e Grupos de Recursos

![Azure Global Infrastructure](https://img.shields.io/badge/Microsoft_Azure-0089D6?style=for-the-badge&logo=microsoft-azure&logoColor=white)

## 📋 Objetivos do Laboratório
- Explorar a infraestrutura global do Azure
- Compreender o conceito de regiões e zonas de disponibilidade
- Criar e configurar grupos de recursos
- Praticar a implantação de recursos básicos

## 🌍 Explorando a Infraestrutura Global

### 🔍 Principais Descobertas
1. **Região Brasil**:
   - Localização física: São Paulo
   - Replicação padrão para Leste dos EUA
   - Opção de replicação local para Rio de Janeiro (Brasil Southeast) para clientes com requisitos de LGPD

2. **Zonas de Disponibilidade**:
   - 3 zonas fisicamente separadas por região
   - SLA de 99.99% quando utilizadas

3. **Tour Virtual**:
   - Visita interativa aos datacenters Microsoft
   - [Explore aqui](https://datacenters.microsoft.com/)

## 🛠️ Parte Prática - Portal Azure

### 1. Criando Grupo de Recursos
```powershell
az group create --name AZ900-Lab --location eastus
