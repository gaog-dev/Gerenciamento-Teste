# Sistema de Gerenciamento de Funcionários

## Descrição
Sistema desenvolvido em JavaScript para gerenciar funcionários de uma indústria, com funcionalidades de cadastro, remoção, aumento salarial, agrupamento por função, entre outros.

## Autor
Guilherme Oliveira

## Tecnologias Utilizadas
- HTML5
- CSS3
- JavaScript (ES6)

## Como Executar

1. Faça o download dos arquivos do projeto.
2. Extraia o arquivo compactado (se necessário).
3. Abra o arquivo `index.html` em um navegador de sua preferência (Chrome, Firefox, Edge, etc).

## Como Testar

Ao abrir o arquivo `index.html` no navegador, o sistema executará automaticamente todas as operações. Além disso, você pode interagir com os botões na interface:

- **Executar Todas as Ações**: Executa todas as operações em sequência.
- **Listar Funcionários**: Exibe a lista de funcionários em formato de tabela.
- **Aumentar Salários (10%)**: Aplica um aumento de 10% nos salários de todos os funcionários e atualiza a tabela.
- **Agrupar por Função**: Exibe os funcionários agrupados por função.

## Funcionalidades Implementadas

1. **Classe Pessoa**: Com atributos nome e data de nascimento.

2. **Classe Funcionário**: Estende Pessoa e adiciona atributos salário e função.

3. **Operações**:

   - Inserção de funcionários.
   - Remoção do funcionário "João".
   - Impressão de todos os funcionários com formatação de data e salário.
   - Aumento de 10% nos salários.
   - Agrupamento de funcionários por função.
   - Impressão de funcionários agrupados por função.
   - Listagem de funcionários que fazem aniversário nos meses 10 e 12.
   - Identificação do funcionário mais velho.
   - Ordenação alfabética dos funcionários.
   - Cálculo do total dos salários.
   - Cálculo de quantos salários mínimos cada funcionário recebe.

## Observações

- O sistema utiliza o formato de data `dd/mm/aaaa` para exibição.
- O salário é exibido com separador de milhar como ponto e decimal como vírgula.
- O salário mínimo considerado é R$ 1212.00.

## Estrutura do Projeto

├── index.html # Página principal do sistema
└── README.md # Este arquivo

## Contato
Desenvolvido por Guilherme Oliveira.