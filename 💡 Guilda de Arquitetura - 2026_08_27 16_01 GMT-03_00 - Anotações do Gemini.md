ago. 27, 2026

## **💡 Guilda de Arquitetura**

convidado [Ozair Garcia Campos Júnior (TL Marketplace Magalu)](mailto:ozair.junior@luizalabs.com) [Eli França (TL - Mktplace Magalu)](mailto:elivando.franca@luizalabs.com) [João Darcy Tinoco Santanna Neto (TL - Marketplace Magalu)](mailto:joao.neto@luizalabs.com) [Luiz Carlos Buiatte (Tech Lead Mktplace Nets)](mailto:luiz.buiatte@luizalabs.com) [Eduardo Santos (TL Marketplace Magalu)](mailto:eduardo.santos@luizalabs.com) [Tarcísio A. de Magalhães Júnior](mailto:tarcisio.junior@luizalabs.com) [Guilherme Alves Borges (TL - Mktplace Magalu)](mailto:guilherme.borges@luizalabs.com) [Eduardo Elias Lima (Esp. - Mktplace Magalu)](mailto:eduardo.filho@luizalabs.com) [Felipe Podestá (Especialista Mktplace Magalu)](mailto:felipe.psantos@luizalabs.com) [Filipe Rocha](mailto:filipe.prates@luizalabs.com) [Guilherme Alves Barroso](mailto:guilherme.barroso@luizalabs.com) [Igor Alvarenga](mailto:igor.alvarenga@luizalabs.com) [Pimentel (Esp. - MP Nets)](mailto:rogerio.pimentel@luizalabs.com) [wellington1.alv@luizalabs.com](mailto:wellington1.alv@luizalabs.com) [Fernando Watanabe (Desenvolvedor - Seller)](mailto:fernando.watanabe@luizalabs.com) [Deyvid Souza (Expert Developer - MKTP)](mailto:deyvid.souza@luizalabs.com) [Erivelto Ximenes (Desenvolvedor - Seller)](mailto:erivelto.filho@luizalabs.com)

Anexos [💡 Guilda de Arquitetura](https://calendar.google.com/calendar/event?eid=cnBua2ZwYmdkZG4wbXR0Y2w0MXJ1YW5tcjJfMjAyNjA4MjdUMTkwMDAwWiBlZHVhcmRvLnNhbnRvc0BsdWl6YWxhYnMuY29t)

Registros da reunião [Gravação](https://drive.google.com/file/d/1rMQgxr82Y80pgUTMbp-gxPrOA42Le_mN/view?usp=drive_web) 

### **Resumo**

Reunião de engenharia abordou fundamentos da arquitetura, debateu processos de design e estabeleceu maior rigor documental.

**Fundamentos de Arquitetura Discutidos**  
A sessão definiu arquitetura como a combinação consistente de estrutura, características de qualidade e diretrizes, distinguindo-a claramente do design de código e padrões de projeto. Foi enfatizada a necessidade de evitar o modelo centralizador, incentivando o arquiteto a colaborar diretamente com o time de desenvolvimento.

**Padronização de Documentação Técnica**  
Os participantes identificaram a necessidade de maior rigor na criação de documentos de design, priorizando a análise de alternativas e trade-offs. Ficou decidido que a adoção sistemática de registros de decisões arquiteturais e solicitações de comentários antes da implementação é mandatória para evitar retrabalho.

**Otimização do Formato de Reunião**  
O grupo analisou a dinâmica do clube de leitura e a profundidade dos debates técnicos realizados. Ajustes na agenda foram considerados para permitir tempo adequado para a exploração de temas complexos como observabilidade em sessões futuras.

### **Próximas etapas**

- [ ] \[Deyvid Souza\] Registrar decisões: Registrar decisões arquiteturais e propostas técnicas em todos os projetos utilizando os formatos de registro de decisão arquitetural e solicitação de comentários.

- [ ] \[Deyvid Souza\] Mapear CI/CD: Mapear os problemas encontrados no processo de integração contínua e entrega contínua para identificar oportunidades de melhoria e automação.

- [ ] \[A equipe\] Incluir tradeoffs: Incluir explicitamente a análise de tradeoffs, considerando diferentes caminhos e cenários, em todos os documentos de desenho de arquitetura.

- [ ] \[The group\] Melhorar Design Docs: Puxar especialistas dos times para ajudar na redação e revisão dos documentos de design. Garantir que o plano arquitetural seja definido antes do início do desenvolvimento dos projetos.

- [ ] \[Eduardo Santos\] Organizar Próximo Encontro: Definir uma lista de temas para as próximas reuniões no grupo assíncrono. Coletar os votos dos participantes para selecionar a pauta do próximo encontro.

- [ ] \[Eduardo Santos\] Aumentar Agenda: Ampliar a duração dos próximos encontros em 30 minutos. Viabilizar um espaço maior para discussões e interações entre os membros da equipe.

- [ ] \[Pimentel\] Documentar Discussão: Registrar os pontos principais abordados durante a reunião realizada. Disponibilizar o documento com o resumo das decisões para a equipe.

### **Detalhes**

* **Início do Encontro e Definição de Papéis**: No início da reunião, Eduardo Santos (TL Marketplace Magalu) introduziu o formato dinâmico de clube de leitura focado em engenharia de software. Deyvid Souza (Expert Developer \- MKTP) assumiu a cadeira de facilitador para apresentar o primeiro ciclo sobre fundamentos de arquitetura, enquanto Ozair Garcia Campos Júnior (TL Marketplace Magalu) atuou como questionador e Eduardo Santos como o controlador do tempo (timekeeper).

* **Visão Geral dos Autores e Conceito de Reversibilidade**: Deyvid Souza (Expert Developer \- MKTP) apresentou os materiais recomendados por Eduardo Santos (TL Marketplace Magalu), escritos por Martin Fowler, Richard Ford e Gregor Hope. Deyvid destacou o conceito de reversibilidade trazido por Martin Fowler, que orienta postergar decisões arquiteturais de alto custo de reversão e evitar a postura do "arquiteto de torre de marfim" em favor de um arquiteto guia que colabora diretamente com o time de desenvolvimento.

* **Debate sobre Estilos de Arquitetura e Decisões**: Filipe Rocha ponderou sobre a analogia de Martin Fowler em relação aos estilos de arquitetura, questionando se o modelo centralizador é totalmente inadequado, dado que equipes enxutas muitas vezes forçam um único profissional a tomar decisões sozinhas. Deyvid Souza (Expert Developer \- MKTP) concordou com a reflexão e destacou o peso dos \*trade-offs\* inevitáveis em qualquer decisão arquitetural e a tendência de focar apenas no "como" em detrimento do "porquê".

* **Níveis Organizacionais e a Metáfora do Elevador**: Deyvid Souza (Expert Developer \- MKTP) abordou a analogia do elevador de Gregor Hope, enfatizando a importância de transitar entre o nível estratégico dos executivos (nível C-level) e o nível operacional ("chão de fábrica"), conectando as necessidades financeiras e de infraestrutura da empresa com as soluções tecnológicas desenvolvidas pelas equipes.

* **Diferenciação entre Arquitetura e Design de Software**: Deyvid Souza (Expert Developer \- MKTP) explicou a base da arquitetura e destacou o que ela não é, esclarecendo que o uso de padrões de projeto (\*design patterns\*), frameworks como React, Java ou Angular, e a organização de pastas em modelo MVC pertencem ao design de código e de projeto, e não à arquitetura isoladamente.

* **Ergonomia e Dimensões da Arquitetura**: Deyvid Souza (Expert Developer \- MKTP) introduziu o conceito de ergonomia nos processos de tecnologia, comparando processos manuais burocráticos a processos automatizados de integração e entrega contínua e testes. Além disso, apresentou as quatro dimensões da arquitetura segundo Richard Ford (estrutura, características de qualidade, diretrizes de design e decisões arquiteturais), definindo arquitetura como a combinação consistente desses elementos.

* **Papéis de Arquitetura e Documentação Corporativa**: Deyvid Souza (Expert Developer \- MKTP) detalhou a divisão dos papéis arquiteturais na organização, abrangendo o nível corporativo (estratégia e portfólio, como o Magalu Cloud), soluções, especialistas e software. Para documentar e comunicar essas decisões, destacou o uso de registros de decisões arquiteturais (ADRs), solicitações de comentários (RFCs), modelo C4 e pós-mortes, além de citar o framework TOGAF para arquitetura corporativa.

* **Exercícios Práticos sobre Migração para Magalu Cloud e ID Magalu**: Deyvid Souza (Expert Developer \- MKTP) propôs exercícios práticos baseados em casos reais, abordando os \*trade-offs\* na migração de microsserviços e bancos de dados críticos da vertical do Seller para a infraestrutura do Magalu Cloud, e as consequências de requisições de rede síncronas ou acoplamento de kit de desenvolvimento de software (SDK) do ID Magalu em picos de tráfego como a Black Friday.

* **Discussão sobre o Problema Resolvido pela Arquitetura e Qualidade dos Design Docs**: Eduardo Elias Lima (Esp. \- Mktplace Magalu) e Pimentel (Esp. \- MP Nets) questionaram como formalizar o problema que a arquitetura resolve e a falta de clareza nas regras aplicadas. Ozair Garcia Campos Júnior (TL Marketplace Magalu) e Eduardo Santos (TL Marketplace Magalu) criticaram a prática comum de escrever documentos de design (\*design docs\*) após o término do desenvolvimento, apontando a ausência de análise de alternativas (caminhos A, B ou C) e \*trade-offs\* nesses artefatos.

* **Rigor nas Aprovações de Mudanças e Propostas de RFCs**: Deyvid Souza (Expert Developer \- MKTP) relatou superficialidade em seções de segurança e resiliência em documentos de design avaliados durante aprovações de mudança (GMUD). Eduardo Santos (TL Marketplace Magalu) e Deyvid debateram a importância de adotar o hábito de criar propostas de solicitação de comentários (RFCs) e registros de decisões arquiteturais (ADRs) antes de iniciar a implementação para evitar retrabalho e padronizar as soluções técnicas.

* **Retrospectiva do Encontro e Próximos Passos**: Ao final da reunião, o grupo realizou uma retrospectiva sobre o formato do clube de leitura. Pimentel (Esp. \- MP Nets) e Eduardo Santos (TL Marketplace Magalu) concordaram que o tempo foi curto para a profundidade do tema, sugerindo estender a agenda em mais trinta minutos para futuras sessões. O grupo também discutiu a possibilidade de abordar temas como observabilidade nos próximos encontros e a participação ativa por meio de canais síncronos e assíncronos.

*Revise as anotações do Gemini para checar se estão corretas. [Confira dicas e saiba como o Gemini faz anotações](https://support.google.com/meet/answer/14754931)*

*Como está a qualidade de **destas observações?** [Responda a uma breve pesquisa](https://google.qualtrics.com/jfe/form/SV_5bXzKQfylMIhSXc?confid=YfTifKABmFU9DGYwv23IDxIROBEBMgUIigIgABgFCA&detailLevel=standard&hasImages=False&entryPoint=footerMain&isGoogler=False) para nos dar seu feedback, incluindo o quanto as observações foram úteis para o que você precisa.*