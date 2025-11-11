ABEX-III: Projeto CodeStudy

"Aprenda a programar de um jeito fácil, divertido e interativo!"

🚀 Pitch (Visão Rápida)

Problema: A dificuldade dos iniciantes em compreender e manter o interesse no aprendizado de programação, levando a altas taxas de desistência.

Solução: CodeStudy, um aplicativo mobile gamificado que utiliza Inteligência Artificial (IA) para personalizar o aprendizado e aumentar a motivação dos estudantes.

Diferenciais: Adaptação automática ao nível do usuário, experiência de aprendizado em formato de jogo e engajamento contínuo com recompensas e ranking.

Impacto: Maior acessibilidade ao ensino de programação, redução da evasão e estímulo à formação de novos profissionais da área tecnológica.


| Etapa | Status | Referência |
| :--- | :--- | :--- |
| **Repositório e Organização** | | |
| Repositório Criado no GitHub | **\[x] Concluído** | |
| Pasta `docs/` para artefatos | **\[ ] Pendente** | Criar pastas `docs/diagramas` e `docs/testes`. |
| Ativar Project (Kanban) | **\[ ] Pendente** | Ligar o GitHub Project ao repositório. |
| **Design Thinking (DT)** | | |
| DT: Empatia/Imersão | **\[x] Concluído** | Seção 2.1 |
| DT: Definição (Persona, Jornada, "Como Podemos...") | **\[x] Concluído** | Seção 2.2 |
| DT: Ideação (Matriz de Ideias) | **\[x] Concluído** | Seção 2.3 |
| DT: Prototipação (Mockups Figma) | **\[x] Concluído** | Seção 2.4 |
| DT: Testes/Validação (Roteiro) | **\[ ] Pendente** | `docs/testes/roteiro_teste_rapido.md` |
| **Requisitos (IEEE)** | | |
| Visão, Escopo, Interfaces Externas, Restrições | **\[x] Concluído** | Seção 3.1 |
| Requisitos Funcionais (RF) | **\[x] Concluído** | Seção 3.2 |
| Requisitos Não Funcionais (RNF) | **\[x] Concluído** | Seção 3.3 |
| **Arquitetura e Modelagem (UML/MER)** | | |
| Diagrama de Componentes (Cliente ↔ API ↔ BD) | **\[x] Concluído** | Seção 4.1 |
| Visão de Dados (DER/MER) | **\[x] Concluído** | Seção 4.2 |
| Modelo de Casos de Uso (UML) | **\[x] Concluído** | Seção 4.3 |
| Descrição Textual de Caso de Uso (Fluxos) | **\[x] Concluído** | Seção 4.4 |
| Diagrama de Atividades (Fluxo Crítico) | **\[x] Concluído** | Seção 4.5 |
| **Entrega** | | |
| Gerar Release `v0.3-ABEXIII` (Pós-apresentação) | **\[ ] Pendente** | |

1. Visão Geral do Projeto

1.1 Objetivo

Este documento apresenta o processo completo de Design Thinking aplicado ao desenvolvimento do projeto CodeStudy, uma plataforma digital gamificada que utiliza Inteligência Artificial (IA) para apoiar o aprendizado inicial de programação. O objetivo do projeto é tornar o ensino de programação mais acessível, interativo e personalizado, reduzindo a taxa de desistência e promovendo o engajamento contínuo dos alunos.

1.2 O Problema

Muita gente começa a aprender programação cheia de vontade, mas acaba se perdendo no caminho. A linguagem técnica, os conceitos abstratos e a falta de prática tornam o processo mais difícil do que precisa ser. As aulas tradicionais nem sempre conseguem prender a atenção ou se adaptar ao ritmo de cada aluno, o que só aumenta a frustração.

Dores Identificadas:

Dificuldade para dar os primeiros passos no mundo da programação.

Falta de interesse dos alunos em aula presencial (Forma de ensino não adaptada).

Dificuldade em prender a atenção do aluno durante o aprendizado.

Garantir que o aluno use a IA apenas como ferramenta de auxílio, não como solução completa.

Necessidade de desmistificar a ideia de que programação é algo extremamente difícil.

Falta de prática regular e falta de tempo para estudo.

1.3 A Solução: CodeStudy

Uma plataforma no estilo “Duolingo” para programação. O aplicativo utiliza inteligência artificial para personalizar o ensino de acordo com o nível do aluno, oferecendo atividades interativas que estimulam a curiosidade.

Lembretes e incentivos gamificados ajudam a manter a motivação e o hábito de estudo, tornando o aprendizado acessível e envolvente.

1.4 Funcionalidades Chave

Aprendizado Progressivo: O ensino começa pela lógica da programação (múltipla escolha), seguido de introdução a algoritmos e desafios práticos.

Problemas Personalizados: A IA cria problemas de programação e ajusta a complexidade conforme a evolução do usuário, além de verificar automaticamente as soluções.

Engajamento e Motivação: O app inclui rankings, métricas de aprendizado e metas diárias.

Estudo em Qualquer Lugar: Pensado para momentos curtos do dia (ex: no ônibus), permitindo ao usuário estudar a qualquer hora e lugar.

2. Design Thinking (DT)

2.1 Imersão e Empatia

2.1.1 Stakeholders

Clientes: Instituições de ensino, Empresas de tecnologia (edtechs).

Usuários: Estudantes iniciantes, Pessoas em migração de carreira, Professores e tutores.

Ambiente Externo: Plataformas (Play Store/App Store), APIs de IA, Instituições parceiras.

Macroambiente: Fatores sociais (falta de incentivo), econômicos (acesso desigual) e legais (LGPD).

2.1.2 Matriz CSD (Certezas, Suposições, Dúvidas)
### 2.1.2 Matriz CSD (Certezas, Suposições, Dúvidas)

| Categoria | Certezas | Suposições | Dúvidas |
| :--- | :--- | :--- | :--- |
| **Problemas** | O aprendizado de programação é desafiador para iniciantes. | A gamificação aumenta a motivação e o engajamento. | Qual é o equilíbrio ideal entre jogo e conteúdo educacional? |
| **Oportunidades** | O mercado carece de ferramentas práticas e personalizadas. | IA pode ajustar o nível de dificuldade com base no desempenho. | Qual será o impacto da IA na autonomia do aprendizado? |
| **Informações** | Há uma alta taxa de evasão em cursos introdutórios. | O público jovem é mais propenso a utilizar apps mobile para estudar. | Quais métricas devem ser usadas para medir o progresso real? |
