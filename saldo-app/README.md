# Saldo+

Aplicativo de controle financeiro pessoal — acompanhe receitas, despesas e configurações da sua conta em um só lugar.

Este repositório contém a implementação em HTML/CSS da tela de **Perfil**, construída a partir do design feito no Figma (`design/perfil-v1.png`).

## Estrutura do projeto

```
saldo-app/
├── design/
│   └── perfil-v1.png   # print da tela de Perfil exportada do Figma
├── index.html           # estrutura da tela de Perfil
├── style.css             # estilos, paleta de cores e tipografia
└── README.md
```

## Como visualizar

Basta abrir o arquivo `index.html` em qualquer navegador — não há dependências ou build necessário.

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

- [ ] Adicionar as telas de Login, Dashboard e Receitas/Despesas nessa mesma paleta
- [ ] Conectar o formulário de "Dados pessoais" a uma API/backend
- [ ] Implementar a lógica de autenticação e persistência de dados
