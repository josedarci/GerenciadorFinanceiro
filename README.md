# Gerenciador Financeiro

Este projeto é um **Gerenciador Financeiro Pessoal Web**, desenvolvido com HTML, CSS, JavaScript e Bootstrap. Ele permite o controle de receitas, despesas, investimentos, saldo e visualização gráfica dos dados mensais. Também exibe cotações em tempo real de moedas e ativos como dólar, euro, bitcoin e ouro.

## Funcionalidades

- **Recebimentos**: Controle de diferentes tipos de entrada de receita mensal.
- **Gastos Fixos e Variáveis**: Registro e acompanhamento dos gastos mensais fixos e variáveis.
- **Gastos Extras**: Lançamentos esporádicos como manutenção, saúde, educação etc.
- **Investimentos**: Inclusão de aplicações em diversas categorias.
- **Patrimônio**: Controle patrimonial por mês e categoria.
- **Saldo**: Cálculo automático do saldo mensal com base nas entradas e saídas.
- **Gráficos**:
  - Pizza com proporção de gastos.
  - Pizza com proporção de investimentos.
  - Linha com tendência de evolução dos investimentos mês a mês.
- **Cotações em tempo real**: Dólar, euro, bitcoin, ouro e moedas de países da América do Sul (UYU, PYG, ARS, etc.).

## Tecnologias Utilizadas

- **HTML5** e **CSS3** (com Bootstrap 5)
- **JavaScript puro**
- **Font Awesome** para ícones
- **Chart.js** para gráficos
- **IndexedDB** para armazenamento local persistente
- **AwesomeAPI** para cotações cambiais

## Organização da Interface

- **Sidebar Recolhível**: Menu lateral com ícones e botões para navegação entre as seções.
- **Telas de Cadastro e Visualização**: Cada categoria (recebimentos, gastos, investimentos, etc.) possui sua própria tela com grid mensal.
- **Modais Bootstrap** para adição de novos registros.
- **Atualização automática** dos gráficos ao inserir dados.
- **Visualização Responsiva** com layout adaptado para diferentes tamanhos de tela.

## Como Utilizar

1. Clone o repositório:
```bash
git clone https://github.com/josedarci/GerenciadorFinanceiro.git
```

2. Abra o arquivo `index.html` em seu navegador.

3. Interaja com os menus e cadastre seus dados financeiros mês a mês.

4. Os dados ficam armazenados localmente no navegador (IndexedDB).

## Observações

- **Não é necessário backend** — funciona inteiramente no navegador.
- Os dados permanecem no navegador mesmo após recarregar ou fechar a aba.

## Licença

Este projeto está licenciado sob a licença MIT.

---

Desenvolvido por [José Darci Rodrigues Junior](https://github.com/josedarci) com o objetivo de auxiliar sua organização de dados financeiros com interface limpa, responsiva e interativa.

