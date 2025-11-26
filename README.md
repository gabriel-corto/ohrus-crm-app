# Teste Técnico – Mini CRM em Vue 3

## Descrição

Este teste faz parte do processo de **admissão para Estágio de Engenheiro de Software na Ohrus**.

## Resumo

Desenvolver um **Mini CRM** com duas páginas: **Clientes Ativos** e **Clientes Arquivados**. O projeto deve usar Vue 3 (Composition API), Pinia, Vue Router, TailwindCSS e **TypeScript — valorizado e fortemente recomendado**.

Todos os dados de clientes encontram-se em **`mocks/customers.ts`**.

---

## Páginas

### 1. Clientes Ativos

* Listar **Nome**, **E-mail**, **Telefone**.
* Ações: **Arquivar** (envia para Pinia) e **Eliminar**.
* Estado desta página deve existir **apenas localmente**.

### 2. Clientes Arquivados

* Listar clientes armazenados no **Pinia**.
* Evitar duplicação de lógica.

---

## Requisitos Técnicos

* Vue 3 (Composition API, sem Options API).
* Pinia apenas para clientes arquivados.
* Vue Router com rota para **/clientes** e navegação visível.
* TailwindCSS para estilização.
* **Uso consistente de TypeScript**: tipagem explícita para clientes, stores, props e estados.

---

## Organização Recomendada

```
src/
 ├─ components/
 ├─ pages/ ou views/
 ├─ stores/
 ├─ routers/
 ├─ mocks/
 ├─ app.vue
 ├─ main.ts
```

---

## Tarefas

1. Criar o projeto com Vite + Vue 3.
2. Configurar Router, Pinia e Tailwind.
4. Implementar páginas de **Clientes Ativos** e **Arquivados**.
5. Implementar as ações: Arquivar, Eliminar.
6. Utilizar Pinia **exclusivamente** para arquivados.
7. Criar navegação entre páginas.
8. Garantir código limpo, organizado, componentizado e **tipado**.

---

## Critérios de Avaliação

* Organização do código e componentização.
* Domínio da Composition API.
* Qualidade da store Pinia.
* Uso correto do Router.
* Interface limpa com Tailwind.
* Funcionalidades coerentes.
* **Aproveitamento sólido do TypeScript** para aumentar segurança e clareza.

---

Crie um repositório e faça o convite para: gabriel-corto para posterior revisão!

By: Ageus Matheus (CEO at Ohrus)
