# 🛡️ PromptGuard — Sistema de Detecção de Vazamento de Dados em IA

> “Privacidade não é algo que você possa perder apenas uma vez.” – Edward Snowden

## 🔍 Visão Geral

**PromptGuard** é um sistema inteligente de monitoramento e detecção de vazamento de dados sensíveis em interações com modelos de linguagem baseados em IA, como ChatGPT, Bard, Claude, entre outros. Ele atua como uma camada protetora entre o usuário e o modelo de IA, garantindo que nenhuma informação confidencial seja compartilhada por engano.

---

## 🎯 Objetivo

Prevenir que desenvolvedores, analistas e outros profissionais compartilhem acidentalmente:
- 🔑 Chaves de API
- 📄 Documentos confidenciais
- 📇 CPFs, nomes de clientes, e-mails internos
- 🧠 Conhecimento estratégico de projetos

---

## 🧱 Arquitetura

O PromptGuard é dividido em três camadas principais:

1. **Extensão de Navegador**: Intercepta os prompts antes de serem enviados ao modelo de IA.
2. **API PromptGuard**: Analisa os dados recebidos usando regras definidas pelo administrador.
3. **Banco de Dados + Logs**: Armazena regras de segurança, registros de vazamento e perfis de usuários.

---

## 👤 Atores do Sistema

- 👩‍💻 **Usuário Final**: Desenvolvedores e analistas que utilizam IA no dia a dia.
- 🔐 **Administrador**: Responsável por configurar regras e monitorar incidentes.
- 🤖 **Modelo de IA (ChatGPT, etc.)**: Sistema externo que responde aos prompts filtrados.
- 🌐 **Extensão do Navegador**: Interface direta com o usuário.

---

## 📦 Funcionalidades

- ✅ Submissão segura de prompts
- 🧠 Detecção de termos sensíveis com base em regras configuráveis
- 🔔 Alerta visual em tempo real
- 📊 Relatórios de vazamento por administrador
- 🔧 Cadastro e gerenciamento de termos confidenciais

---

## 🧪 Casos de Uso

| Código  | Nome                         | Atores Envolvidos         |
|---------|------------------------------|---------------------------|
| UC-01   | Submeter Prompt              | Usuário Final             |
| UC-02   | Detectar Vazamento           | Sistema, Extensão         |
| UC-03   | Gerenciar Regras             | Administrador             |
| UC-04   | Visualizar Relatórios        | Administrador             |
| UC-05   | Registrar Dados Sensíveis    | Administrador             |

---

## 🖼️ Diagramas UML

- 🔷 Diagrama de Casos de Uso
- 📤 Diagrama de Sequência
- 🧩 Diagrama de Componentes
- 🧱 Diagrama de Classes
- 🔄 Diagrama de Estados
- 💾 Modelo de Dados

Todos os diagramas estão disponíveis na pasta `/Diagramas`.
