# Gerenciador Financeiro

Este projeto � um **Gerenciador Financeiro Pessoal Web**, desenvolvido com HTML, CSS, JavaScript e Bootstrap. Ele permite o controle de receitas, despesas, investimentos, saldo e visualiza��o gr�fica dos dados mensais. Tamb�m exibe cota��es em tempo real de moedas e ativos como d�lar, euro, bitcoin e ouro.

## Funcionalidades

- **Recebimentos**: Controle de diferentes tipos de entrada de receita mensal.
- **Gastos Fixos e Vari�veis**: Registro e acompanhamento dos gastos mensais fixos e vari�veis.
- **Gastos Extras**: Lan�amentos espor�dicos como manuten��o, sa�de, educa��o etc.
- **Investimentos**: Inclus�o de aplica��es em diversas categorias.
- **Patrim�nio**: Controle patrimonial por m�s e categoria.
- **Saldo**: C�lculo autom�tico do saldo mensal com base nas entradas e sa�das.
- **Gr�ficos**:
  - Pizza com propor��o de gastos.
  - Pizza com propor��o de investimentos.
  - Linha com tend�ncia de evolu��o dos investimentos m�s a m�s.
- **Cota��es em tempo real**: D�lar, euro, bitcoin, ouro e moedas de pa�ses da Am�rica do Sul (UYU, PYG, ARS, etc.).

## Tecnologias Utilizadas

- **HTML5** e **CSS3** (com Bootstrap 5)
- **JavaScript puro**
- **Font Awesome** para �cones
- **Chart.js** para gr�ficos
- **IndexedDB** para armazenamento local persistente
- **AwesomeAPI** para cota��es cambiais

## Organiza��o da Interface

- **Sidebar Recolh�vel**: Menu lateral com �cones e bot�es para navega��o entre as se��es.
- **Telas de Cadastro e Visualiza��o**: Cada categoria (recebimentos, gastos, investimentos, etc.) possui sua pr�pria tela com grid mensal.
- **Modais Bootstrap** para adi��o de novos registros.
- **Atualiza��o autom�tica** dos gr�ficos ao inserir dados.
- **Visualiza��o Responsiva** com layout adaptado para diferentes tamanhos de tela.

## Como Utilizar

1. Clone o reposit�rio:
```bash
git clone https://github.com/josedarci/GerenciadorFinanceiro.git
```

2. Abra o arquivo `index.html` em seu navegador.

3. Interaja com os menus e cadastre seus dados financeiros m�s a m�s.

4. Os dados ficam armazenados localmente no navegador (IndexedDB).

## Observa��es

- **N�o � necess�rio backend** � funciona inteiramente no navegador.
- Os dados permanecem no navegador mesmo ap�s recarregar ou fechar a aba.

## Licen�a

Este projeto est� licenciado sob a licen�a MIT.

---

Desenvolvido por [Jos� Darci Rodrigues Junior](https://github.com/josedarci) com o objetivo de auxiliar sua organiza��o de dados financeiros com interface limpa, responsiva e interativa.

