# ⚡ FlowPay | Central de Atendimento Inteligente

Bem-vindo ao projeto **FlowPay**. Esta é uma solução Full Stack completa desenvolvida para gerenciar fluxos de atendimento, triagem automática de chamados e distribuição inteligente de carga entre especialistas.

---

## 🏛️ Arquitetura do Sistema

Para garantir o desacoplamento e seguir as melhores práticas de mercado, o projeto foi dividido em dois repositórios independentes:

### 🎨 [Frontend - Dashboard Operacional](LINK_AQUI_DO_SEU_REPO_FRONT)
* **Tecnologias:** Angular 19, RxJS, CSS Moderno (Glassmorphism).
* **Destaque:** Dashboard reativo com polling adaptativo que elimina a necessidade de refresh, proporcionando uma experiência em tempo real para o operador.

### 🧠 [Backend - API de Gestão & Triagem](LINK_AQUI_DO_SEU_REPO_BACK)
* **Tecnologias:** Java 21, Spring Boot 3, Spring Data JPA, H2 Database.
* **Destaque:** Motor de triagem automática que classifica chamados por assunto e distribui para especialistas com menor carga de trabalho, respeitando limites operacionais.

---

## 🚀 Como testar o ecossistema completo

1. **Inicie o Backend:** Siga as instruções no [Repositório do Backend](https://github.com/JGMeneses/FlowPay) para subir a API na porta `8080`.
2. **Inicie o Frontend:** Siga as instruções no [Repositório do Frontend](https://github.com/JGMeneses/flowpay-frontend) para subir o dashboard na porta `4200`.
3. **Integração:** O dashboard consumirá automaticamente os dados da API local.

---

## ✒️ Autor
**João Meneses** - Desenvolvedor Full Stack
> "Focado em construir software escalável, limpo e com foco total na experiência do usuário final."

---

## 📸 Demonstração da Solução

### 🖥️ Dashboard Operacional (Frontend)
O painel administrativo utiliza **Angular 19** para monitoramento em tempo real. Observe a distribuição de carga entre os especialistas e a fila de espera dinâmica.

<p align="center">
  <img src="https://github.com/user-attachments/assets/8687ecf9-14ad-4188-b125-a900f88862ca" width="100%" alt="Dashboard FlowPay">
</p>

### 🧠 Documentação da API (Backend)
Toda a lógica de triagem e persistência é exposta via **Swagger UI**, permitindo testes rápidos e integração facilitada. A arquitetura segue padrões RESTful com respostas semânticas.

<p align="center">
  <img src="https://github.com/user-attachments/assets/636e9bf1-8c97-48c6-9d79-cc68022b7fcf" width="100%" alt="Swagger Documentation">
</p>

---

