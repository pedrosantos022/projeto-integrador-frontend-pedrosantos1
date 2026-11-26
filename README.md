# Painel de Controle Financeiro Pessoal
 
Aplicação web acadêmica para o gerenciamento financeiro pessoal, desenvolvida como projeto do curso de Análise e Desenvolvimento de Sistemas.
 
 **Projeto** 
 
> **Status:** versão 1.0, estrutura HTML5 semântica. Os recursos de cálculo e de armazenamento local estão planejados.
 
## Objetivo e público-alvo
 
Ajudar pessoas que estão começando a organizar a vida financeira a registrar receitas e despesas mensais de forma simples, com uma divisão de orçamento como referência didática (50% essenciais, 30% estilo de vida, 20% metas e reserva).
 
## Principais funcionalidades
 
- **Resumo do orçamento** em três categorias: Essenciais, Estilo de Vida e Metas e Reserva.
- **Tabela de movimentações** com descrição, categoria e valor (dados de exemplo fictícios).
- **Formulário de nova transação** com descrição, valor, data, tipo (receita/despesa) e categoria, com validação nativa do navegador (`required`, `min`, `step`, `maxlength`, `pattern`).
- **Link para a [Calculadora do Cidadão (Banco Central)](https://www3.bcb.gov.br/CALCIDADAO/)** para simular juros compostos e rendimento da reserva.
## Como visualizar / executar localmente
 
O projeto é estático: não precisa de instalação, build ou servidor.


## Créditos e licenças de terceiros
 
| Recurso | Origem | Licença |
|---|---|---|
| HTML, textos e estrutura da página | Autoria própria |
| Calculadora do Cidadão | [Banco Central do Brasil](https://www3.bcb.gov.br/CALCIDADAO/)|
 
O projeto **não utiliza** frameworks, bibliotecas JavaScript, fontes web nem ícones de terceiros.
 
## Decisões éticas e técnicas (resumo)
 
- **Privacidade:** não há backend, cookies, analytics nem coleta de dados pessoais; os dados do exemplo são fictícios. O formulário ainda usa `method="post"`, ponto que será corrigido (processamento local com JavaScript).
- **Acessibilidade:** `lang="pt-BR"`, HTML semântico, `<label>` associado a cada campo, `fieldset`/`legend`, tabela com `th scope="col"` e texto de ajuda via `aria-describedby`.
- **Sustentabilidade:** sem dependências externas e sem JavaScript, o que reduz tráfego de rede e processamento.
- **IA:** uso declarado de ferramentas de IA na documentação, com revisão e responsabilidade humanas. Detalhes no relatório.
- **Legal:** análise com base na LGPD (Lei nº 13.709/2018), com os limites de aplicação ao projeto acadêmico explicados no relatório.
📄 **A análise completa está no Relatório Técnico (PDF):** [PREENCHER: link ou caminho do arquivo, ex. `docs/relatorio-tecnico.pdf`]
 
## Próximos passos
 
- [ ] Processar o formulário com JavaScript e salvar no `localStorage`.
- [ ] Calcular saldo e percentual por grupo de orçamento.
- [ ] Formatar valores em reais com `Intl.NumberFormat`.
- [ ] Criar CSS.
## Licença
 
[ESCOLHER: ex. Licença MIT. Adicione o arquivo `LICENSE` à raiz do repositório.]
 
## Autor
 
Pedro Henrique Dos Santos Silva · https://github.com/pedrosantos022 · Curso de Análise e Desenvolvimento de Sistemas
 