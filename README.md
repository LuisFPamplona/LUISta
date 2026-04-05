<h1 align="center">LUISta de tarefas</h1>
<p align="center">Organize sua rotina em qualquer lugar, de forma prática e intuitiva.</p>

---

## Demonstração

<table align="center">
  <tr>
    <td>
      <img src="https://i.imgur.com/a0tojcn.gif" width="250"/>
    </td>
    <td align="center">
      <img src="https://i.imgur.com/LUUbkmf.png" width="450"/>
      <br><br><br><br>
      <p>
        Aplicação de lista de tarefas desenvolvida em React, com foco em produtividade e organização. Possui interface moderna e responsiva (mobile-first), permitindo o gerenciamento eficiente de tarefas. Utiliza conceitos como componentes reutilizáveis, controle de estado e persistência de dados com localStorage.
      </p>
      <p>
        Experimente aqui: https://lui-sta.vercel.app/
      </p>
    </td>
  </tr>
</table>

---

## Funcionalidades

- Adicionar novas tarefas
- Marcar tarefas como concluídas
- Editar tarefas existentes
- Excluir tarefas com confirmação
- Filtros: todas, pendentes e concluídas
- Buscar tarefas por texto (search bar)
- Salvar automaticamente no **localStorage**
- Estilização com **Tailwind CSS**
- Responsivo (Mobile First)

---

## Estrutura do Projeto

```
src/
├── components/
│   ├── AdicionarTask.jsx
│   ├── Task.jsx
│   ├── Header.jsx
│   ├── Filter.jsx
│   ├── SearchBar.jsx
│   ├── ButtonBar.jsx
│   ├── EditInput.jsx
│   └── DeleteAlerts.jsx
├── storage/
│   └── localStorageUtils.js
├── TodoList.jsx
├── App.jsx
└── main.jsx
```

---

## Tecnologias utilizadas

- React
- Tailwind CSS
- Lucide Icons
- Local Storage (API Web)
- Vite (build tool)

---

## Como executar o projeto localmente

1. Clone o repositório:
```bash
git clone https://github.com/LuisFPamplona/react-todolist.git
```

2. Instale as dependências:
```bash
npm install
```

3. Execute localmente:
```bash
npm run dev
```

---


## Autor

**Luis Pamplona**  
[GitHub](https://github.com/LuisFPamplona)

---

## 📌 Observações

Esse projeto foi feito com fins educativos como parte do meu aprendizado em desenvolvimento front-end com React. Toda contribuição ou feedback é bem-vindo!
