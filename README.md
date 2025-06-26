# ATIVIDADE: Engenharia de Software - Análise de Conceitos e Modelos de Maturidade

## 1. Índice do Documento

- 2. Resumo dos Conceitos
- 3. Resumo das Referências Fornecidas e Ampliadas
- 4. Resumo das Aulas da Semana
  - a. Reginaldo (Plano de Mitigação)
  - b. Simulação em Sala (Destaques)
  - c. Modelo de Maturidade de Processo de Software (CMMi e CMMC)
- 5. Comentário Geral sobre o Curso

## 2. Resumo dos Conceitos (Fonte: Quadros Miro das instruções da Semana)

Os conceitos abordados nas instruções da semana focaram em três pilares principais:

- **AULA 1: Estratégias de Mitigação**
  - **Tema:** Revisar a arquitetura e o processo com base nas táticas de segurança, aprofundando sobre as táticas arquiteturais. O objetivo é entender como a arquitetura de software pode ser projetada para resistir a ataques e reduzir o impacto de vulnerabilidades.

- **AULA 2: Negociação entre stakeholders em crise simulada de vazamento de dados do GitHub Secure Code Game**
  - **Tema:** Oferecer uma oportunidade para o aluno refletir sobre contramedidas (técnicas e de gestão) em uma situação de crise simulada. A simulação de uma crise de segurança cibernética, envolvendo vazamento de dados e diferentes stakeholders, enfatiza a necessidade de uma gestão de crise coordenada entre os grupos.

- **AULA 3: Avaliação de Risco entre Grupos para Avaliar Nível de Maturidade Cyber**
  - **Tema:** Discutir a integridade não apenas de dados e transações, mas também a integridade física de usuários, operadores e gestores, que podem ser afetados por vulnerabilidades no atributo de integridade de um sistema. Isso amplia a compreensão de que a segurança vai além da proteção de informações digitais.

## 3. Resumo das Referências Fornecidas e Ampliadas

As referências principais para esta semana são capítulos do livro "Software Architecture in Practice" de BASS, Len; CLEMENTS, Paul; KAZMAN, Rick.

- **Capítulo 11 - Security (Segurança):** Este capítulo aborda a segurança como um atributo de qualidade crucial na arquitetura de software. Ele explora cenários gerais de segurança, táticas arquiteturais para implementar a segurança (como verificar a integridade de mensagens, autenticação, autorização, não repúdio, etc.), questionários baseados em táticas para avaliar a segurança de uma arquitetura e padrões de segurança que podem ser aplicados. O foco é como as decisões arquiteturais podem fortalecer a postura de segurança de um sistema, tornando-o mais resiliente contra ameaças e ataques cibernéticos.

- **Capítulo 10 - Safety (Segurança Operacional/Integridade Física):** Este capítulo trata da segurança operacional, que se refere à capacidade de um sistema de evitar ou mitigar condições que possam levar a acidentes, lesões ou perdas de vida. Ele discute cenários gerais de segurança operacional, táticas para garantir a segurança (como redundância, detecção de falhas, recuperação de erros e mecanismos de fail-safe), questionários baseados em táticas e padrões de design para sistemas seguros. A ênfase é dada à proteção da integridade física de usuários, operadores e gestores, reconhecendo que vulnerabilidades em sistemas podem ter consequências no mundo real.

## 4. Resumir sobre as aulas da semana:

### a. Reginaldo (Plano de Mitigação)

A aula com Reginaldo sobre Planos de Mitigação se alinha diretamente com as "Estratégias de Mitigação" da Aula 1. Um plano de mitigação em engenharia de software e cibersegurança envolve a identificação proativa de riscos e vulnerabilidades, e a definição de ações para reduzir a probabilidade de sua ocorrência ou minimizar seu impacto caso se concretizem. Isso inclui a aplicação de táticas arquiteturais de segurança, como as discutidas no Capítulo 11 do "Software Architecture in Practice", que visam construir sistemas mais robustos e resistentes a ataques desde a fase de design. A mitigação não é apenas reativa, mas um processo contínuo de avaliação e aprimoramento da arquitetura e dos processos de desenvolvimento.

### b. Simulação em Sala (Destaques)

A simulação em sala sobre a crise de vazamento de dados do GitHub Secure Code Game foi um destaque importante, conforme a Aula 2. Ela proporcionou uma experiência prática sobre a complexidade da gestão de crises de segurança cibernética. Os principais destaques incluem:

- **Negociação entre Stakeholders:** A dificuldade e a importância de coordenar diferentes partes interessadas (equipes técnicas, gerência, jurídico, comunicação, etc.) com objetivos e perspectivas distintas.
- **Contramedidas Técnicas e de Gestão:** A necessidade de aplicar tanto soluções técnicas (ex: correção de vulnerabilidades, isolamento de sistemas) quanto estratégias de gestão (ex: comunicação de crise, planos de recuperação) de forma integrada.
- **Gestão Coordenada da Crise:** A simulação demonstrou que a eficácia na resposta a um incidente de segurança depende criticamente da colaboração e da coordenação entre todos os envolvidos, evitando ações isoladas que possam agravar a situação.

### c. Modelo de Maturidade de Processo de Software (CMMi e CMMC)

- **CMMI (Capability Maturity Model Integration):** O CMMI é uma estrutura de melhoria de processos que ajuda as organizações a aprimorar seus processos de desenvolvimento e entrega de produtos e serviços de alta qualidade. Ele fornece um roteiro para a melhoria contínua e a excelência organizacional, com cinco níveis de maturidade:

  - **Nível 1: Inicial:** Processos imprevisíveis e reativos.
  - **Nível 2: Gerenciado:** Processos planejados e controlados para projetos específicos.
  - **Nível 3: Definido:** Processos padronizados e documentados em toda a organização.
  - **Nível 4: Gerenciado Quantitativamente:** Processos medidos e controlados estatisticamente.
  - **Nível 5: Otimizado:** Foco na melhoria contínua dos processos.

  Originalmente focado em desenvolvimento de software, o CMMI expandiu seu escopo para incluir engenharia de sistemas, entrega de serviços e desenvolvimento de produtos, tornando-o mais versátil para diversas indústrias.

- **CMMC (Cybersecurity Maturity Model Certification):** O CMMC é uma estrutura de cibersegurança em camadas introduzida pelo Departamento de Defesa (DoD) dos EUA. Seu objetivo é garantir que contratados e empresas que lidam com informações governamentais sensíveis (como Informações de Contrato Federal - FCI e Informações Não Classificadas Controladas - CUI) atendam a rigorosos padrões de cibersegurança. O CMMC possui vários níveis, cada um construindo sobre o anterior, exigindo que as organizações implementem práticas de cibersegurança progressivamente mais robustas e passem por avaliações. Isso visa fortalecer as defesas cibernéticas da Base Industrial de Defesa (DIB) contra ameaças em constante evolução.

## 5. Comentário Geral sobre o Curso

O curso de engenharia de software, com foco em cibersegurança, foi extremamente valioso para aprofundar meu entendimento sobre conceitos fundamentais e práticos da área. Pude assimilar conhecimentos sobre termos que antes desconhecia, como ransomware, XML, autenticação quebrada (broken authentication) e path traversal, o que me permitiu abstrair e identificar potenciais vulnerabilidades em aplicações de forma mais eficaz. Foi esclarecedor perceber que muitas ferramentas e provedores de software atuais já incorporam soluções para grandes falhas de segurança, o que otimiza o desenvolvimento de sistemas mais seguros.

Além do aspecto técnico, o curso contribuiu significativamente para o desenvolvimento de minhas habilidades de negociação. A experiência em simulações de crise demonstrou a complexidade e a necessidade de coordenar equipes e stakeholders em direção a um objetivo comum, de forma colaborativa e não competitiva, revelando técnicas essenciais para essa coordenação. Reforcei também meus conhecimentos sobre a metodologia ATAM (Architecture Tradeoff Analysis Method) e compreendi a importância das regras de negócio na criação de malhas fechadas, que são cruciais para a segurança e o controle de sistemas. Por fim, o curso me ensinou a "respeitar o adversário", ou seja, a pensar como um atacante para implementar formas eficazes de detecção, recuperação e resistência contra ameaças cibernéticas, além de aprofundar meu conhecimento sobre a avaliação de maturidade de software, como o modelo CMMI.
