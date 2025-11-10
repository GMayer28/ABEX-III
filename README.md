# ABEX-III
# Projeto CodeStudy — Aplicativo de Aprendizado de Programação

## Objetivo
Este documento apresenta o processo completo de Design Thinking aplicado ao desenvolvimento do projeto **CodeStudy**, uma plataforma digital gamificada que utiliza Inteligência Artificial (IA) para apoiar o aprendizado inicial de programação. O objetivo do projeto é tornar o ensino de programação mais acessível, interativo e personalizado, reduzindo a taxa de desistência e promovendo o engajamento contínuo dos alunos.

---

## 1) Imersão e Empatia

### 1.1 Stakeholders

**Clientes**
- Instituições de ensino interessadas em adotar ferramentas tecnológicas inovadoras.
- Empresas de tecnologia voltadas à educação (edtechs).

**Usuários**
- Estudantes iniciantes na área de programação.
- Pessoas que desejam migrar para a área de tecnologia.
- Professores e tutores que buscam novas metodologias de ensino.

**Ambiente Interno**
- Equipe de desenvolvimento do aplicativo (programadores, designers e analistas).
- Equipe de suporte e manutenção técnica.
- Setor de marketing responsável pela divulgação do produto.

**Ambiente Externo**
- Plataformas de distribuição (Play Store e App Store).
- APIs e ferramentas de IA utilizadas na personalização do ensino.
- Instituições parceiras para testes e feedback.

**Macroambiente**
- Fatores sociais: falta de incentivo à educação tecnológica de base.
- Fatores econômicos: acesso desigual a tecnologias digitais.
- Fatores políticos: incentivos governamentais à formação tecnológica.
- Fatores legais: aplicação da LGPD para proteção dos dados dos usuários.

---

### 1.2 Necessidades e Dificuldades

**Necessidades**
- Tornar o ensino de programação mais prático e atrativo.
- Estimular o aprendizado contínuo e autônomo.
- Garantir que o usuário tenha feedback imediato sobre seu progresso.
- Oferecer uma experiência interativa e compatível com dispositivos móveis.

**Dificuldades**
- Linguagem técnica e abstrata que afasta iniciantes.
- Falta de metodologias interativas nas aulas tradicionais.
- Escassez de tempo dos alunos para estudo.
- Manutenção do engajamento ao longo do tempo.

**Restrições**
- Limitações orçamentárias e técnicas para desenvolvimento do protótipo.
- Necessidade de integração com sistemas de IA e APIs externas.
- Dependência de conexões estáveis com servidores de dados.

**Padrões**
- Interface responsiva e intuitiva.
- Estrutura modular com trilhas progressivas.
- Sistema de pontuação e recompensas.

---

### 1.3 Empatia (Perfil e Comportamentos)

**Sentimentos predominantes**
- Insegurança em relação à capacidade de aprender a programar.
- Frustração com métodos de ensino pouco dinâmicos.
- Desejo de compreender e aplicar conceitos de forma prática.

**Expectativas**
- Aprender de maneira leve e divertida.
- Receber incentivos e reconhecimento pelo progresso.
- Acompanhar a própria evolução de forma clara.

**Medos**
- Falhar ou desistir antes de compreender o conteúdo.
- Sentir-se sobrecarregado com a complexidade do tema.

**Aspirações**
- Desenvolver autonomia em programação.
- Criar projetos próprios e atuar na área de tecnologia.

**Aspectos culturais**
- Interesse crescente por tecnologias acessíveis e gamificadas.
- Valorização de métodos de ensino adaptáveis e digitais.

---

### 1.4 Matriz CSD (Certezas, Suposições, Dúvidas)

| Categoria        | Certezas                                                                 | Suposições                                                                 | Dúvidas                                                        |
|------------------|---------------------------------------------------------------------------|----------------------------------------------------------------------------|----------------------------------------------------------------|
| Problemas        | O aprendizado de programação é desafiador para iniciantes.                | A gamificação aumenta a motivação e o engajamento.                         | Qual é o equilíbrio ideal entre jogo e conteúdo educacional?   |
| Oportunidades    | O mercado carece de ferramentas de ensino práticas e personalizadas.      | IA pode ajustar o nível de dificuldade com base no desempenho do usuário.  | Qual será o impacto da IA na autonomia do aprendizado?          |
| Informações      | Há uma alta taxa de evasão em cursos introdutórios de programação.        | O público jovem é mais propenso a utilizar apps mobile para estudar.       | Quais métricas devem ser usadas para medir o progresso real?   |

---

## 2) Definição e Síntese

### 2.1 Persona

**Nome:** João Alves  
**Idade:** 19 anos  
**Perfil:** Estudante do primeiro semestre de Ciência da Computação.  
**Necessidades:** Melhorar sua base em lógica e programação de forma prática.  
**Motivações:** Interesse em tecnologia e busca por um método de aprendizado mais dinâmico.  
**Dores:** Falta de didática nas aulas tradicionais e dificuldade de acompanhar o ritmo do curso.  

---

### 2.2 Jornada do Usuário

1. João descobre o aplicativo CodeStudy em uma rede social.  
2. Realiza o cadastro e escolhe a linguagem de programação desejada.  
3. Inicia as lições introdutórias com desafios curtos e pontuação.  
4. Recebe feedback imediato e avança para novos níveis.  
5. Compete em rankings com outros usuários e acompanha sua evolução.  
6. Sente-se motivado a continuar e explorar conteúdos mais avançados.

---

### 2.3 Agrupamento das Informações

**Principais categorias identificadas:**
- **Motivação:** necessidade de reconhecimento e progresso visível.  
- **Aprendizado:** desejo por atividades práticas e curtas.  
- **Interatividade:** preferência por ambientes visuais e dinâmicos.  
- **Autonomia:** busca por estudo independente com suporte da IA.  

---

### 2.4 Insights Principais

- A gamificação favorece o engajamento e a permanência do aluno.  
- A personalização de conteúdo melhora a experiência de aprendizado.  
- O acompanhamento em tempo real aumenta a confiança do estudante.  
- A competição saudável reforça o hábito de estudo diário.  

---

### 2.5 Problema Central

**Como podemos tornar o aprendizado de programação mais acessível, dinâmico e personalizado, utilizando recursos de IA e gamificação, de forma a reduzir a evasão e aumentar a motivação dos alunos iniciantes?**

---

### 2.6 Requisitos

**Requisitos Funcionais**
- Cadastro e autenticação de usuários.  
- Seleção de linguagens de programação.  
- Sistema de pontuação e ranking.  
- Feedback automatizado por IA.  
- Criação e evolução de trilhas personalizadas.  

**Requisitos Não Funcionais**
- Interface responsiva e intuitiva.  
- Desempenho otimizado em dispositivos móveis.  
- Proteção de dados conforme a LGPD.  
- Alta disponibilidade e estabilidade do sistema.  

---

## 3) Ideação

### 3.1 Geração de Ideias

- Aplicativo com desafios gamificados.  
- Sistema de recompensas e conquistas.  
- Feedback automatizado por IA.  
- Ranking entre amigos e comunidades.  
- Trilhas adaptativas de aprendizado.  
- Integração com universidades e empresas.  

---

### 3.2 Avaliação das Ideias

| Ideia                                   | Impacto | Viabilidade | Inovação | Total |
|----------------------------------------|----------|--------------|-----------|--------|
| Aplicativo gamificado                  | 3        | 3            | 2         | 8      |
| Feedback automatizado por IA           | 3        | 2            | 3         | 8      |
| Ranking e competições                  | 3        | 3            | 1         | 7      |
| Trilhas personalizadas de aprendizado  | 3        | 2            | 3         | 8      |
| Sistema de recompensas e skins         | 2        | 3            | 2         | 7      |

**Ideias Selecionadas:**
- Gamificação com recompensas.  
- IA adaptativa para personalização.  
- Rankings e desafios sociais.  

---

## 4) Prototipação

### 4.1 Modelos Conceituais

- **Diagrama de Casos de Uso:** cadastro, login, execução de atividades, acompanhamento de progresso, acesso ao ranking.  
- **Diagrama de Atividades:** fluxo de aprendizado (cadastro → lições → avaliação → recompensas).  
- **BPMN:** processo geral de interação entre usuário, IA e banco de dados.

---

### 4.2 Protótipos Visuais

Wireframes / Mockups / Storyboards
-
O protótipo foi desenvolvido no Figma e apresenta as principais telas do CodeStudy, incluindo o menu inicial, tela de lições, progresso do usuário e ranking geral.  
**Link do protótipo:** [https://www.figma.com/proto/rvt8KGKre7Cs6IbshaywvO](https://www.figma.com/proto/rvt8KGKre7Cs6IbshaywvO)

**Telas:**

<div align="center">
<img src="https://github.com/GMayer28/ABEX-III/blob/04f74d659de99016faea05a185a7d4a3fc81db9d/img/login_criar%20conta.png" />
</div>
<div align="center">
<img src="https://github.com/GMayer28/ABEX-III/blob/daa5980e05042381f80d6e98c742bc404caf2b9a/img/2.png" />
</div>
<div align="center">
<img src="https://github.com/GMayer28/ABEX-III/blob/daa5980e05042381f80d6e98c742bc404caf2b9a/img/3.png" />
</div>
<div align="center">
<img src="https://github.com/GMayer28/ABEX-III/blob/daa5980e05042381f80d6e98c742bc404caf2b9a/img/4.png" />
</div>
<div align="center">
<img src="https://github.com/GMayer28/ABEX-III/blob/daa5980e05042381f80d6e98c742bc404caf2b9a/img/5.png" />
</div>
<div align="center">
<img src="https://github.com/GMayer28/ABEX-III/blob/daa5980e05042381f80d6e98c742bc404caf2b9a/img/6.png" />
</div>
<div align="center">
<img src="https://github.com/GMayer28/ABEX-III/blob/daa5980e05042381f80d6e98c742bc404caf2b9a/img/7.png" />
</div>
<div align="center">
<img src="https://github.com/GMayer28/ABEX-III/blob/daa5980e05042381f80d6e98c742bc404caf2b9a/img/8.png" />
</div>

---

### 4.3 Modelo Lógico

- Banco de dados relacional com tabelas para usuários, atividades, progresso e resultados.  
- Integração com módulos de IA responsáveis pela geração e correção de desafios.  
- Estrutura modular que permite atualizações e inclusão de novas linguagens.

---

## 5) Testes e Validação

**Planejamento de Testes**
- Teste funcional das principais telas (cadastro, lições, ranking).  
- Teste de usabilidade com usuários iniciantes.  
- Avaliação de desempenho e tempo de resposta.

**Feedback**
- Usuários destacaram a clareza das atividades e a sensação de progresso contínuo.  
- Sugestão de ampliar a variedade de linguagens disponíveis.

---

## 6) Pitch e Entrega

**Problema:**  
A dificuldade dos iniciantes em compreender e manter o interesse no aprendizado de programação.

**Solução:**  
CodeStudy, um aplicativo gamificado que utiliza IA para personalizar o aprendizado e aumentar a motivação dos estudantes.

**Diferenciais:**  
- Adaptação automática ao nível do usuário.  
- Experiência de aprendizado em formato de jogo.  
- Engajamento contínuo com recompensas e ranking.

**Impacto:**  
Maior acessibilidade ao ensino de programação, redução da evasão e estímulo à formação de novos profissionais da área tecnológica.

---

## Anexos
- Documento de requisitos detalhados.  
- Diagramas UML e BPMN.  
- Protótipo no Figma.  
- Relatório de entrevistas e validação.

---

## Histórico de Alterações

| Data       | Alteração                              | Autor               |
|-------------|----------------------------------------|---------------------|
| 2025-10-17  | Criação e preenchimento do documento   | Guilherme Mayer     |

