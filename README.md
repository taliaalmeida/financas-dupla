<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:D01117,50:EC4899,100:F9A8D4&height=180&section=header&text=FINAN%C3%87AS%20EM%20DUPLA&fontSize=32&fontColor=FDF2F8&fontAlignY=35&desc=Controle%20compartilhado%20de%20receitas%20e%20despesas&descAlignY=58&descSize=15&descColor=F9A8D4" alt="Banner Finanças em Dupla" />
</p>

<p align="center">
  <strong>Aplicativo web para duas pessoas acompanharem a vida financeira de forma simples e colaborativa.</strong>
</p>

<p align="center">
  <a href="https://taliaalmeida.github.io/financas-dupla/"><img src="https://img.shields.io/badge/DEMO-ONLINE-EC4899?style=for-the-badge&labelColor=0D1117" alt="Demo online" /></a>
  <img src="https://img.shields.io/badge/STATUS-FEATURED-F9A8D4?style=for-the-badge&labelColor=0D1117" alt="Status featured" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5" />
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript" />
  <img src="https://img.shields.io/badge/Firebase%20Firestore-FFCA28?style=for-the-badge&logo=firebase&logoColor=black" alt="Firebase Firestore" />
</p>

> **01 // PROJECT_OVERVIEW**  
> O Finanças em Dupla transforma o controle financeiro compartilhado em um fluxo direto: cada participante entra em uma sala, registra receitas e despesas e acompanha o saldo do mês em tempo real.

## 02 // RECURSOS

| Recurso | Descrição |
| --- | --- |
| **Salas compartilhadas** | Duas pessoas usam o mesmo código de sala para acessar os lançamentos. |
| **Receitas e despesas** | Registra entradas e saídas com valor, categoria, data e observação. |
| **Saldo automático** | Calcula receitas, despesas e saldo do período selecionado. |
| **Categorias** | Organiza lançamentos por grupos como salário, moradia, alimentação, transporte, saúde e lazer. |
| **Gráficos** | Apresenta uma visão visual da distribuição das despesas. |
| **Metas** | Disponibiliza um espaço para acompanhar objetivos financeiros. |
| **Navegação mensal** | Permite consultar o mês de referência e seus lançamentos. |

## 03 // INTERFACE

A imagem abaixo mostra o dashboard publicado após entrar em uma sala de demonstração. A tela apresenta o código da sala, o participante, o mês selecionado, os cartões de receitas, despesas e saldo, a navegação principal e as áreas de gastos por categoria e últimos lançamentos.

<p align="center">
  <img src="C:\Users\DELL\Downloads\04_financas_em_dupla_dashboard.webp"/>
</p>

<p align="center"><sub>Captura real da aplicação publicada, utilizando uma sala de demonstração sem dados pessoais.</sub></p>

## 04 // TECNOLOGIAS

| Camada | Tecnologia |
| --- | --- |
| Interface | HTML5 e CSS3. |
| Comportamento | JavaScript puro e manipulação do DOM. |
| Persistência/sincronização | Firebase Cloud Firestore, conforme os imports do `index.html`. |
| Publicação | GitHub Pages. |
| Identidade visual | Fundo azul-marinho/roxo com detalhes lilás, rosa e tipografia de alto contraste. |

## 05 // COMO USAR

### Demo online

Acesse [taliaalmeida.github.io/financas-dupla](https://taliaalmeida.github.io/financas-dupla/).

1. Informe seu nome.
2. Crie ou informe um código de sala.
3. Compartilhe o mesmo código com a outra pessoa.
4. Registre receitas e despesas e acompanhe o saldo, os gráficos e as metas.

### Execução local

```bash
git clone https://github.com/taliaalmeida/financas-dupla.git
cd financas-dupla
python3 -m http.server 8000
```

Abra [http://localhost:8000](http://localhost:8000) no navegador. Como o projeto importa módulos do Firebase por CDN, executar por HTTP local é preferível a abrir o arquivo diretamente.

## 06 // ESTRUTURA ATUAL

```text
financas-dupla/
├── index.html    # Interface, estilos e lógica da aplicação
└── README.md     # Documentação do projeto
```

> A documentação anterior citava `style.css` e `script.js`, mas esses arquivos não aparecem na raiz pública consultada. A versão atual do projeto concentra a implementação observada no `index.html`; mantenha esta seção atualizada quando a separação de arquivos for realizada.

## 07 // CONFIGURAÇÃO E SEGURANÇA

O aplicativo utiliza configuração de cliente do Firebase no front-end. Antes de usar dados reais, revise as regras do Firestore, restrinja as operações por sala e valide o formato dos dados no cliente e no banco. Nunca coloque credenciais administrativas, dados financeiros reais ou informações pessoais em exemplos públicos.

## 08 // ROADMAP

| Prioridade | Evolução sugerida |
| --- | --- |
| Alta | Implementar autenticação e autorização por usuário, em vez de confiar somente no código da sala. |
| Alta | Validar regras de segurança do Firestore por sala e por participante. |
| Média | Separar HTML, CSS e JavaScript em arquivos independentes. |
| Média | Adicionar edição, exclusão, exportação e testes dos cálculos mensais. |

## 09 // AUTORIA

Desenvolvido por **Natalia Almeida — By Natalia Dev**.

- [Demo online](https://taliaalmeida.github.io/financas-dupla/)
- [Código-fonte](https://github.com/taliaalmeida/financas-dupla)
- [Perfil no GitHub](https://github.com/taliaalmeida/taliaalmeida)
- [Instagram](https://www.instagram.com/nataliaalmeidatech)

<p align="center">
  <sub>Learn. Build. Automate. Evolve.</sub>
</p>
