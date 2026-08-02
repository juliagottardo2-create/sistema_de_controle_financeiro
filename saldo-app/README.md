# Saldo+

Aplicativo de controle financeiro pessoal — acompanhe receitas, despesas e configurações da sua conta em um só lugar.

Este repositório contém a implementação em HTML/CSS das telas construídas a partir do design feito no Figma (pasta `design/`).

## Estrutura do projeto

```
saldo-app/
├── design/
│   ├── perfil-v1.png              # print da tela de Perfil exportada do Figma
│   └── despesas-e-receitas-v1.png # print da tela de Receitas e Despesas
├── index.html                      # tela de Perfil
├── despesas-e-receitas.html        # tela de Receitas e Despesas
├── style.css                        # estilos, paleta de cores e tipografia (compartilhado)
└── README.md
```

## Como visualizar

Abra `index.html` ou `despesas-e-receitas.html` em qualquer navegador — não há dependências ou build necessário. As páginas se linkam entre si pelo menu lateral.

## Paleta de cores

| Cor | Uso | Valor |
|---|---|---|
| 🟠 Laranja | Marca, ações principais (salvar), pendências | `#F2793A` |
| 🟢 Verde | Receitas, saldo positivo | `#34C77B` |
| 🔴 Vermelho | Despesas, zona de risco (excluir conta) | `#E5534B` |
| 🔵 Azul | Ações neutras (transferências) | `#6E85B7` |
| Fundo | Página e barra lateral | `#0B1220` |
| Superfície | Cards e painéis | `#121B2E` |

## Tipografia

Fonte principal: **Inter** (com fallback para fontes de sistema).

## Próximos passos

- [ ] Adicionar as telas de Login e Dashboard nessa mesma paleta
- [ ] Conectar as tabelas e formulários a uma API/backend
- [ ] Implementar a lógica de autenticação e persistência de dados
- [ ] Deixar as abas (Todas/Receitas/Despesas/Pendentes) e os botões funcionais com JavaScript
