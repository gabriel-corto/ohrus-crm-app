# Teste Técnico – Mini CRM em Vue 3

## Descrição

Este teste faz parte do processo de admissão para Vaga de Estágio de Engenheiro de Software na Ohrus.

## Resumo

Desenvolver um **Mini CRM** com duas páginas: **Clientes Ativos** e **Clientes Arquivados**. O projeto deve usar Vue 3 (Composition API), Pinia, Vue Router, TailwindCSS e **TypeScript — valorizado e fortemente recomendado**.

Todos os dados de clientes encontram-se em **`mocks/customers.ts`**.

---

## Páginas

### 1. Clientes Ativos

- Listar **Nome**, **E-mail**, **Telefone**.
- Estado desta página deve existir **apenas localmente**.

### 2. Clientes Arquivados

- Listar clientes armazenados no **Pinia**.
- Evitar duplicação de lógica.

---

## Requisitos Técnicos

- Vue 3 (Composition API, sem Options API).
- Pinia apenas para clientes arquivados.
- Vue Router com rota para **/clientes** e navegação visível.
- TailwindCSS para estilização.
- **Uso consistente de TypeScript**: tipagem explícita para clientes, stores, props e estados.

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

1. Criar projeto com Vite + Vue 3.
2. Configurar Router, Pinia e Tailwind.
3. Implementar páginas de **Clientes Ativos** e **Arquivados**.
4. Utilizar Pinia **exclusivamente** para arquivados.
5. Criar navegação entre páginas.
6. Garantir código limpo, organizado, componentizado e **tipado**.

---

## Critérios de Avaliação

- Organização do código e componentização.
- Domínio da Composition API.
- Qualidade da store Pinia.
- Uso correto do Router.
- Interface limpa com Tailwind.
- Funcionalidades coerentes.
- **Aproveitamento sólido do TypeScript** para aumentar segurança e clareza.

---

By: Ageus Matheus (CEO at Ohrus)
