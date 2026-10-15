![Controle de Horas — Organize sua jornada de estágio](https://github.com/EduardaLima-09/ControleDeHoras/blob/main/Controle%20de%20horas.png)

<div align="center">

# Controle de Horas • Estágio

**Sua rotina organizada, suas horas sob controle.**

Uma aplicação web para registrar atividades, acompanhar a jornada de estágio e visualizar o progresso mensal de forma simples, prática e intuitiva.

<br>

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Status](https://img.shields.io/badge/Status-Em%20desenvolvimento-DB7093?style=for-the-badge)

<br>

</div>

---

## Sobre o projeto

O **Controle de Horas** é uma aplicação web desenvolvida para facilitar a organização e o acompanhamento das horas de estágio.

A proposta é centralizar os registros de atividades em um único lugar, permitindo consultar as horas realizadas, acompanhar metas mensais e organizar informações importantes da rotina profissional.

Com uma interface visual personalizada em tons de rosa, o sistema combina praticidade, organização e facilidade de uso para tornar o controle da jornada mais intuitivo.

## Funcionalidades

### Dashboard

- Visualização do total de horas realizadas.
- Acompanhamento da meta mensal e do saldo de horas.
- Indicador percentual de progresso.
- Cálculo da média diária e dos dias trabalhados.
- Contagem de feriados e dias de férias.
- Gráficos de horas por dia e por categoria.
- Resumo diário com status da jornada.

### Lançamentos

- Cadastro de atividades realizadas durante o estágio.
- Registro de data, duração, categoria e observações.
- Edição e exclusão de lançamentos.
- Organização das atividades por categorias.
- Filtros por dia, mês e categoria.
- Pesquisa por nome da atividade ou observação.
- Exibição da quantidade de registros encontrados e do total de horas filtradas.

### Resumo mensal

- Consulta do total de horas realizadas no mês.
- Visualização da meta mensal.
- Cálculo do saldo de horas.
- Acompanhamento do percentual de progresso.

### Feriados & Férias

- Cadastro, edição e exclusão de feriados.
- Registro de períodos de férias.
- Cálculo dos dias de férias dentro do mês.
- Desconto de feriados e férias da meta mensal de horas.

### Importação e exportação

- Exportação de relatórios mensais em PDF.
- Inclusão de indicadores e lançamentos no relatório.
- Importação de dados a partir de arquivos JSON.
- Preservação dos registros no armazenamento local do navegador.

## Interface

O projeto possui uma proposta visual delicada e funcional, com foco em uma experiência de uso agradável.

- Identidade visual personalizada em tons de rosa.
- Layout adaptável a diferentes tamanhos de tela.
- Navegação por seções para facilitar o acesso às informações.
- Indicadores e gráficos para tornar os dados mais compreensíveis.
- Mensagens de estado vazio quando ainda não existem registros.

## Tecnologias

| Tecnologia | Utilização |
|---|---|
| HTML5 | Estrutura da aplicação e dos formulários |
| CSS3 | Estilização, identidade visual e responsividade |
| JavaScript | Regras de negócio, cálculos, filtros e interatividade |
| LocalStorage | Armazenamento local dos registros no navegador |
| jsPDF | Geração de relatórios em PDF |
| JSON | Formato para importação de dados |

## Regras de cálculo

O sistema utiliza uma jornada de referência de **6 horas por dia útil** para calcular a meta mensal.

A meta considera os dias de segunda a sexta-feira, descontando os feriados cadastrados e os dias abrangidos por períodos de férias.

| Indicador | Descrição |
|---|---|
| Total realizado | Soma das horas registradas no mês |
| Meta mensal | Quantidade de dias úteis válidos multiplicada por 6 horas |
| Saldo | Total realizado menos a meta mensal |
| Progresso | Percentual da meta mensal alcançado |
| Média diária | Média de horas por dia com registros de trabalho |

*Observação: os cálculos seguem as regras implementadas no código e dependem dos registros cadastrados.*

## Como executar

### Pré-requisitos

- Um navegador atualizado.
- [Visual Studio Code](https://code.visualstudio.com/) (opcional, recomendado para desenvolvimento).

### Instalação

**1. Clone o repositório**

```bash
git clone https://github.com/EduardaLima-09/ControleDeHoras.git
```

**2. Acesse a pasta do projeto**

```bash
cd ControleDeHoras
```

**3. Abra o projeto**

Abra a pasta no Visual Studio Code e execute o arquivo `index.html` no navegador. Você também pode utilizar a extensão Live Server para facilitar a execução durante o desenvolvimento.

Não é necessário configurar um servidor backend para utilizar a versão atual da aplicação.

## Estrutura do projeto

```text
ControleDeHoras/
├── assets/
│   └── banner-controle-horas.png
├── css/
│   └── index.css
├── index.html
└── README.md
```

*Estrutura ilustrativa: mantenha no README apenas os caminhos que realmente existem no repositório.*

## Armazenamento dos dados

Os registros são armazenados no `LocalStorage` do navegador, permitindo que as informações continuem disponíveis entre acessos no mesmo ambiente de navegação.

**Importante:** os dados não são sincronizados automaticamente entre dispositivos ou navegadores. Para transferir os registros, utilize a funcionalidade de importação e exportação disponibilizada pela aplicação.

## Melhorias futuras

- [ ] Implementar backup automático dos registros.
- [ ] Criar sincronização de dados entre dispositivos.
- [ ] Adicionar novas opções de visualização dos relatórios.
- [ ] Aprimorar os indicadores de acompanhamento da jornada.
- [ ] Evoluir a aplicação conforme as necessidades dos usuários.

## Objetivo de aprendizado

Este projeto também representa uma oportunidade de colocar em prática conhecimentos de desenvolvimento web, incluindo:

- Estruturação de interfaces com HTML.
- Criação de layouts responsivos com CSS.
- Manipulação do DOM com JavaScript.
- Manipulação de datas e cálculos de duração.
- Persistência de dados no navegador.
- Implementação de filtros e operações CRUD.
- Geração e organização de relatórios.

## Autora

**Maria Eduarda Lima**

<div align="center">

[![GitHub](https://img.shields.io/badge/GitHub-EduardaLima--09-181717?style=for-the-badge&logo=github)](https://github.com/EduardaLima-09)

<br>

Feito com , código e dedicação.

Se gostou do projeto, deixe uma estrela no repositório!

</div>
