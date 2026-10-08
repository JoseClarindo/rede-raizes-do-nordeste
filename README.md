# Rede Raízes do Nordeste — Projeto Front-End

Protótipo funcional desenvolvido com HTML, CSS e JavaScript puros, usando dados mockados.

## O que foi contemplado
- App/celular, Web/computador e Totem em uma mesma interface responsiva.
- Cadastro, login e recuperação de senha simulados.
- Cardápio por unidade, categorias, produto indisponível e carrinho.
- Pedido para retirada e acompanhamento de status.
- Raízes+ com pontos e recompensas.
- Promoções e campanhas.
- Pagamento desacoplado: o front-end simula envio e retorno de um serviço externo, sem pagamento real.
- Caminho de erro para indisponibilidade do serviço de pagamento.
- Consentimento e tela de privacidade.
- Demonstração dos atores Atendente, Cozinha e Gerente/Administrador.
- CSS Mobile First e breakpoints para telas maiores.

## Como testar
Abra `index.html` em um navegador moderno.

Conta de demonstração:
- e-mail: `joao@raizes.local`
- senha: `123456`

Para testar a falha de pagamento, monte um carrinho, avance até pagamento e marque **Simular falha do serviço de pagamento**.

## Estrutura
- `index.html` — telas e componentes da interface.
- `style.css` — estilos responsivos, com base Mobile First.
- `app.js` — dados mockados, navegação e regras da demonstração.
- `assets/` — diagramas, jornada, wireframes e evidências visuais.
- `documentacao/` — material de apoio para o relatório.
