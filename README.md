# Cuidaro Print Agent (Releases)

🤖 **Repositório de Distribuição Oficial**

Este repositório atua como o banco de dados de artefatos primário para o motor de **Atualização Automática (OTA)** do **Cuidaro Print Agent**.

## 📦 Como Funciona
Sempre que a Cuidaro finaliza e aprova uma nova arquitetura, o GitHub Actions (CI/CD) orquestra a build das rotinas do Agente Go e disponibiliza abertamente os instaladores `Windows (amd64)`, `macOS (arm64)` e `Linux (amd64)` na aba de **Releases** à direita desta tela.

> **Importante:** Este repositório é apenas a ponta do iceberg de entrega. Ele **não contém o código fonte** da plataforma ou do agente e atua essencialmente como Content Delivery sem custos adicionais de infraestrutura interna.

## 🔐 Segurança e Integridade Garantidas
A fim de prevenir vetores de ataque (*Man-in-the-middle* ou arquivos corrompidos na internet), usamos **Strict Hash Verification** SHA-256. Nenhuma atualização é aplicada no servidor do cliente (Hot-Swap) caso o arquivo recém-baixado não possua a assinatura exata reportada neste repositório!
