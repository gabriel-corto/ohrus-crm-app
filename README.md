Aqui vai um **novo enunciado completo**, já estruturado como documentação de teste técnico — **versão para Nuxt 3**, com API real, CRUD completo, modal, tabela e página dedicada.
Direto ao ponto, claro e pronto para copiar para um README.

---

# 🧪 Teste Técnico – Mini CRM em **Nuxt ** (CRUD + API + Modal + Tabela)

## 🎯 Objetivo

Avaliar a capacidade do candidato em:

* Construir uma aplicação real usando **Nuxt 3** (Composition API)
* Consumir uma **API REST** (listar, criar e apagar clientes)
* Estruturar **CRUD completo**
* Utilizar **TailwindCSS** para UI
* Criar **componentes reutilizáveis**
* Trabalhar com **modais**, **tabelas** e **formas corretas de organizar pastas**
* Demonstrar noções de engenharia de software com TypeScript
* Utilizar O Nuxt UI Para design da aplicação

Este teste faz parte do processo de **admissão ao Estágio de Engenheiro de Software na Ohrus**.

---

## 📦 Descrição Geral do Projeto

Desenvolver um **Mini CRM** com:

1. **Uma página principal** `/clientes`
2. **Um modal** para criar clientes
3. **Uma tabela** para listar clientes vindos de uma API
4. Funcionalidades:

   * **Listar**
   * **Criar**
   * **Eliminar**

**Obs.:** Não existe página de arquivados neste teste. Apenas a página `/clientes`.

---

## 🔗 API

O candidato deve consumir **uma API REST** (pode ser mockada com JSON Server, Mirage, API interna do Nuxt, etc.).

### A API deve suportar:

#### `GET /customers`

Retorna lista de clientes.

#### `POST /customers`

Cria um novo cliente.

#### `DELETE /customers/:id`

Apaga um cliente.

---

## 🧑‍🤝‍🧑 Funcionalidades Detalhadas

### 1. **Página `/clientes`**

Deve conter:

#### ✔ **Tabela de Listagem**

Com colunas:

* Nome
* Email
* Telefone
* Ações (botão de apagar)

#### ✔ **Modal de Criação**

Abertura por um botão **“Novo Cliente”**.

O modal deve conter:

* Nome
* Email
* Telefone
* Botão de “Criar Cliente”

Ao salvar:

* Chamar a API
* Fechar o modal
* Atualizar a tabela

#### ✔ **Botão de Apagar**

Em cada linha da tabela:

* Deve chamar `DELETE /customers/:id`
* Atualizar a tabela

---

## 🛠 Regras Técnicas Obrigatórias

### ✔ **Nuxt 3** com Composition API

* Todo o código deve estar em `<script setup>`.
* Sem Options API.

### ✔ **TypeScript Obrigatório**

* Tipagem explícita em funções e respostas de API
* Não usar `any`

### ✔ **TailwindCSS**

* UI construída somente com classes utilitárias.

### ✔ **Modularização**

Estrutura sugerida:

```
src/
 ├─ components/
 │   ├─ customers/
 │   │     ├─ CustomerTable.vue
 │   │     └─ CustomerCreateModal.vue
 ├─ pages/
 │   └─ clientes.vue
 ├─ composables/
 │   └─ useCustomers.ts
```

Organização será avaliada.

---

## 🧬 O que o candidato precisa implementar

### 1. Criar um projeto Nuxt 3 com Tailwind

### 2. Configurar API (interna ou externa)

### 3. Criar:

* Página `/clientes`
* Modal reutilizável de criação
* Tabela de listagem
* Composable ou service para lidar com a API

### 4. Implementar o CRUD:

* **GET**: listar clientes
* **POST**: criar cliente
* **DELETE**: apagar cliente

### 5. Garantir:

* Tipagem forte (TypeScript)
* Componentização
* Código limpo e organizado

---

## 🧮 Critérios de Avaliação

### 1. **Arquitetura e organização**

* Clareza de pastas
* Isolamento da lógica em composables/services
* Componentização correta

### 2. **Domínio do Nuxt 3 + Composition API**

* Uso de `useFetch`, `useAsyncData` ou abstrações próprias
* Lógica bem encapsulada

### 3. **Qualidade do TypeScript**

* Nada de `any`
* Modelos e tipagem consistente

### 4. **Qualidade da UI com Tailwind**

* Layout limpo
* Responsividade mínima
* Usabilidade

### 5. **Fluxo do CRUD funcionando sem erros**

* README contendo:

  * Como instalar
  * Como rodar a API
  * Como executar a aplicação
  * Breve explicação das escolhas técnicas

---

