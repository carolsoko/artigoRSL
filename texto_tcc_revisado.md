1 INTRODUÇÃO
As doenças cardiovasculares (DCVs) permanecem como a principal causa de mortalidade em âmbito mundial, configurando-se como um problema de saúde pública de elevada magnitude. Segundo estimativas da Organização Mundial da Saúde, em 2022 foram registrados aproximadamente 19,8 milhões de óbitos atribuídos às DCVs, o que corresponde a cerca de 32% do total de mortes globais (OMS, 2025). Paralelamente, o diabetes mellitus (DM) — nos tipos 1 (DM1) e 2 (DM2), que apresentam demandas distintas de cuidado e manejo clínico — tem mostrado crescimento sustentado e impacto relevante nos indicadores de morbimortalidade. De acordo com o IDF Diabetes Atlas, estima-se que 589 milhões de adultos entre 20 e 79 anos viviam com diabetes em 2024, com projeções de aumento expressivo nas próximas décadas (IDF, 2024).
Esse cenário evidencia a urgência de estratégias eficazes voltadas à prevenção, ao acompanhamento contínuo e ao fortalecimento do autocuidado, considerando que tanto as DCVs quanto o DM são condições crônicas que exigem manejo prolongado, monitoramento constante e tomadas de decisão frequentes no cotidiano dos indivíduos.
O controle adequado e a redução das complicações associadas às DCVs e ao DM dependem, em grande medida, do engajamento ativo do paciente em práticas de autocuidado, tais como a compreensão da própria condição de saúde, a adesão ao tratamento prescrito, o reconhecimento precoce de sinais de alerta e a manutenção de rotinas baseadas em hábitos de vida protetores.

1.1 Delimitação do tema
Diante desse panorama, este trabalho delimita-se ao desenvolvimento do Educacardio+, um aplicativo móvel para a plataforma Android que integra educação em saúde estruturada, progressão gamificada do usuário, notificações personalizadas e sincronização automatizada de indicadores por meio do Health Connect. O aplicativo organiza seus conteúdos em módulos educativos voltados às cardiopatias e ao diabetes mellitus, estruturados em três componentes principais: (i) conteúdos de aprendizagem, (ii) questionários destinados ao reforço do conhecimento adquirido e (iii) recomendações práticas organizadas em formato de checklist de hábitos, com o objetivo de facilitar a compreensão e a aplicação das orientações no cotidiano dos usuários.
Como suporte ao acompanhamento contínuo da rotina de saúde, o Educacardio+ integra-se ao Health Connect para a sincronização de indicadores como número de passos, frequência cardíaca e dados de sono, contribuindo para a consolidação dessas informações em um fluxo único e para a redução da fragmentação de dados provenientes de diferentes fontes. Adicionalmente, a progressão do usuário é registrada e pontuada a partir da conclusão dos módulos educativos, e recursos de lembretes e notificações são disponibilizados como apoio à manutenção da rotina de cuidados.
Do ponto de vista metodológico, o estudo caracteriza-se como pesquisa aplicada, com foco no desenvolvimento de uma solução tecnológica. As etapas contemplaram o levantamento e a consolidação de requisitos, a prototipação e a implementação do aplicativo, a integração com serviços de autenticação e persistência de dados, bem como a realização de testes funcionais e de integração para verificação do correto funcionamento da solução proposta.

1.2 Problema de pesquisa
Na prática assistencial, fatores como tempo reduzido disponível para as consultas, barreiras de acesso aos serviços de saúde, descontinuidade das orientações e dificuldade de traduzir recomendações clínicas em ações sustentáveis no cotidiano dos pacientes podem comprometer significativamente a adesão ao tratamento. Nesse contexto, as soluções de saúde móvel (mobile health – mHealth) têm sido amplamente exploradas como apoio ao autocuidado. Contudo, uma limitação recorrente dessas iniciativas refere-se à fragmentação dos dados: indicadores relevantes para o acompanhamento da saúde — como nível de atividade física, padrões de sono e sinais vitais — frequentemente permanecem distribuídos em múltiplos aplicativos e dispositivos, dificultando a construção de uma visão integrada do estado de saúde do indivíduo e reduzindo o valor prático do monitoramento contínuo.
Adicionalmente, a simples centralização de informações não é suficiente para assegurar adesão terapêutica ou promover mudanças comportamentais duradouras. A efetividade de aplicações voltadas ao autocuidado está diretamente associada ao engajamento do usuário e à continuidade de uso, sendo comum a descontinuidade quando não há percepção clara de valor, feedback sobre o progresso alcançado ou quando existem barreiras relacionadas à usabilidade. Nesse sentido, identificam-se oportunidades para o desenvolvimento de tecnologias que, além de integrar dados de forma automatizada — por exemplo, por meio do Health Connect —, incorporem estratégias de engajamento, como gamificação e notificações personalizadas, com o objetivo de favorecer a constância de uso e apoiar a manutenção de rotinas de cuidado (Johnson et al., 2016; Koivisto; Hamari, 2019; Yu et al., 2025).
Diante desse contexto, formula-se a seguinte questão de pesquisa: como uma aplicação móvel integrada ao Health Connect e apoiada por estratégias de engajamento pode contribuir para a educação em saúde e o autocuidado de pessoas com diabetes mellitus e demandas relacionadas à saúde cardiovascular?

1.3 Justificativa
A opção pelo desenvolvimento da solução para o ecossistema Android, bem como pela utilização do Health Connect, justifica-se pela necessidade de armazenamento, padronização e interoperabilidade dos dados de saúde no próprio dispositivo, possibilitando a centralização de métricas relevantes ao autocuidado em um ambiente unificado (Android Developers, 2025). Essa abordagem contribui para reduzir a fragmentação de informações provenientes de diferentes aplicativos e dispositivos, ampliando a utilidade prática dos dados para o acompanhamento contínuo da saúde do usuário.
Adicionalmente, a escolha da plataforma Android fundamenta-se em seu amplo alcance no contexto brasileiro, o que favorece o potencial de adoção e disseminação da solução em âmbito nacional (StatCounter, 2025). Dessa forma, a proposta do Educacardio+ consiste em oferecer uma solução integrada que articula educação em saúde, monitoramento de indicadores e mecanismos de engajamento, atuando como um instrumento complementar de apoio ao autocuidado, sem a pretensão de substituir o acompanhamento clínico ou a orientação de profissionais de saúde.

1.4 Objetivos
1.4.1 Objetivo geral
Desenvolver o aplicativo Educacardio+, integrado ao Health Connect, com a finalidade de apoiar a educação em saúde e o autocuidado de pessoas com diabetes mellitus tipo 1 (DM1) e tipo 2 (DM2), bem como de indivíduos com demandas relacionadas à saúde cardiovascular, por meio da oferta de conteúdos educativos estruturados, acompanhamento de indicadores de saúde, estratégias de gamificação e notificações personalizadas.

1.4.2 Objetivos específicos
- Estruturar módulos educativos sobre cardiopatias e diabetes mellitus;
- Implementar questionários para reforço e consolidação do aprendizado;
- Disponibilizar recomendações práticas organizadas em formato de checklist;
- Integrar o aplicativo ao Health Connect para sincronização de indicadores como número de passos, frequência cardíaca e dados de sono;
- Implementar mecanismos de persistência do progresso e de pontuação por usuário;
- Desenvolver alertas e notificações personalizadas como suporte à manutenção de rotinas de autocuidado.

2 REFERENCIAL TEÓRICO
A fundamentação teórica deste trabalho estabelece os alicerces conceituais, metodológicos e técnicos que sustentam o desenvolvimento do aplicativo Educacardio+. Considerando a natureza interdisciplinar da pesquisa, situada na convergência entre a Ciência da Computação e a Saúde Pública, torna-se necessária uma abordagem integrada que articule os aspectos clínicos e educacionais relacionados às condições crônicas com as potencialidades oferecidas pelas tecnologias digitais móveis contemporâneas. Essa articulação é fundamental para compreender tanto as demandas do público-alvo quanto as escolhas projetuais e tecnológicas adotadas na construção da solução proposta.
Inicialmente, o capítulo contextualiza o cenário epidemiológico das Doenças Crônicas Não Transmissíveis (DCNT), com ênfase nas particularidades do diabetes mellitus, nos tipos 1 e 2, e das doenças cardiovasculares. A análise desses agravos considera sua elevada prevalência, impacto na morbimortalidade e implicações socioeconômicas, bem como as exigências de manejo contínuo e tomada de decisão frequente por parte dos indivíduos acometidos. Esse panorama clínico-epidemiológico fundamenta a relevância social do projeto e evidencia a necessidade de estratégias que ampliem a literacia em saúde, fortaleçam o autocuidado e apoiem a adesão terapêutica ao longo do tempo.
Na sequência, discute-se o paradigma do mobile health (mHealth), abordando o papel das tecnologias móveis como mediadoras do processo educativo e como ferramentas de apoio ao acompanhamento em saúde. São analisadas as contribuições das aplicações digitais para a promoção do autocuidado, o monitoramento de indicadores e a comunicação de informações em tempo oportuno. Nesse contexto, a gamificação é apresentada como estratégia projetual relevante, capaz de estimular o engajamento, favorecer a continuidade de uso e mitigar as elevadas taxas de abandono frequentemente observadas em intervenções digitais em saúde. A incorporação de elementos lúdicos, feedback de progresso e recompensas simbólicas é discutida à luz de estudos que associam tais mecanismos à motivação e à mudança de comportamento em ambientes digitais.
Por fim, o referencial teórico explora os fundamentos técnicos da arquitetura da solução proposta, com destaque para o funcionamento da API Health Connect no ecossistema Android, enquanto mecanismo de interoperabilidade e padronização de dados fisiológicos provenientes de múltiplas fontes e dispositivos. Essa abordagem permite compreender como a centralização de informações pode reduzir a fragmentação de dados e ampliar o valor prático do acompanhamento em saúde. Concomitantemente, são discutidos os requisitos não funcionais relacionados à privacidade, segurança da informação e controle de acesso, analisados à luz da Lei Geral de Proteção de Dados Pessoais (LGPD). Essa análise assegura que o desenvolvimento do Educacardio+ esteja alinhado aos princípios éticos, legais e regulatórios aplicáveis ao tratamento de dados sensíveis de saúde, reforçando a confiabilidade e a responsabilidade da solução proposta.

2.1 Doenças crônicas
As Doenças Crônicas Não Transmissíveis (DCNT) constituem um conjunto heterogêneo de condições de origem não infecciosa, caracterizadas por etiologia multifatorial, presença de múltiplos fatores de risco, longos períodos de latência e curso clínico prolongado. Além de representarem a principal causa de mortalidade em escala global, as DCNT impõem um expressivo ônus aos sistemas de saúde e à sociedade, estando associadas a diferentes graus de incapacidade funcional e à redução da qualidade de vida dos indivíduos acometidos (OMS, 2023). Nesse conjunto, as doenças cardiovasculares (DCVs) assumem papel de destaque, sendo responsáveis pela maior proporção de óbitos prematuros e evitáveis.
O espectro clínico das DCVs é amplo e abrange afecções que acometem o coração e os vasos sanguíneos, incluindo a doença arterial coronariana — frequentemente associada ao infarto agudo do miocárdio —, as doenças cerebrovasculares, como o acidente vascular cerebral (AVC), a insuficiência cardíaca, as arritmias, as cardiopatias congênitas e as valvopatias. A fisiopatologia de grande parte dessas condições está intimamente relacionada a processos como a aterosclerose e a hipertensão arterial sistêmica, que evoluem de forma progressiva e, muitas vezes, silenciosa, manifestando-se clinicamente apenas diante de eventos agudos. A Organização Mundial da Saúde destaca que a maioria das DCVs é passível de prevenção por meio do controle de fatores de risco comportamentais, tais como tabagismo, alimentação inadequada, sedentarismo e consumo nocivo de álcool, evidenciando que a modificação do estilo de vida constitui um pilar fundamental tanto na prevenção quanto no manejo dessas doenças (OMS, 2025).
Estreitamente associado ao risco cardiovascular, o diabetes mellitus configura-se como uma síndrome metabólica de etiologia complexa e elevada prevalência. O diabetes mellitus tipo 1 (DM1) resulta de um processo autoimune que culmina na destruição das células beta pancreáticas, levando à deficiência absoluta de insulina e à necessidade de reposição exógena contínua. Por sua vez, o diabetes mellitus tipo 2 (DM2), responsável pela ampla maioria dos casos em âmbito global, caracteriza-se pela resistência à ação da insulina nos tecidos periféricos, associada a uma falência progressiva da secreção pancreática. A hiperglicemia crônica, comum a ambas as condições, quando não adequadamente controlada, desencadeia danos sistêmicos de longo prazo, culminando em disfunção de múltiplos órgãos e elevando substancialmente o risco de complicações microvasculares — como retinopatia, nefropatia e neuropatia — e macrovasculares. Nesse contexto, as doenças cardiovasculares figuram como a principal causa de mortalidade entre pessoas com diabetes (American Diabetes Association, 2024).

Figura 1 – Projeção do crescimento global de casos de diabetes mellitus.
Fonte: Adaptado de IDF (2024).

O cenário epidemiológico contemporâneo, corroborado por relatórios da International Diabetes Federation (IDF) e da Sociedade Brasileira de Diabetes (SBD), evidencia um crescimento sustentado na prevalência dessas condições, impulsionado sobretudo pelo envelhecimento populacional e pelos processos acelerados de urbanização, especialmente em países emergentes. Esse aumento progressivo de casos impõe desafios significativos à organização e à sustentabilidade dos sistemas de saúde, uma vez que o manejo eficaz dessas doenças crônicas requer do paciente a realização de múltiplas tomadas de decisão no cotidiano.
Tais decisões abrangem desde o monitoramento glicêmico e a contagem de carboidratos, no caso do diabetes, até o controle da pressão arterial, a adoção de hábitos de vida saudáveis e a adesão rigorosa ao tratamento medicamentoso no contexto das doenças cardiovasculares. Nesse sentido, a complexidade inerente ao autocuidado reforça a necessidade de estratégias educativas contínuas e do uso de ferramentas tecnológicas capazes de apoiar o indivíduo nos intervalos entre as consultas presenciais. A implementação dessas abordagens mostra-se fundamental para favorecer a adesão terapêutica, promover o empoderamento do paciente e contribuir para a redução do risco de complicações associadas às doenças crônicas (IDF, 2021; SBD, 2023).

2.2 Educação em saúde e tecnologias digitais
A educação em saúde ultrapassa a mera transmissão de informações, configurando-se como componente estratégico essencial para a promoção da saúde, a prevenção de agravos e o fortalecimento do autocuidado. Trata-se de um processo orientado ao desenvolvimento da autonomia do indivíduo e de sua capacidade de tomar decisões informadas e conscientes sobre sua própria condição de saúde. No contexto das Doenças Crônicas Não Transmissíveis (DCNT), em que o paciente assume papel central no gerenciamento cotidiano da terapia, as ações educativas devem fundamentar-se em referenciais teóricos consistentes que favoreçam a mudança de comportamento e a adoção de práticas sustentáveis de cuidado.
Nesse sentido, destacam-se a Teoria Social Cognitiva de Bandura e a Teoria da Aprendizagem Significativa de Ausubel como aportes teóricos relevantes. A Teoria Social Cognitiva introduz o conceito de autoeficácia, definido como a crença do indivíduo em sua própria capacidade de organizar e executar ações necessárias para alcançar determinados resultados, sendo reconhecida como fator determinante para a adesão a comportamentos de saúde. Já a Teoria da Aprendizagem Significativa postula que novos conhecimentos são assimilados e aplicados de maneira mais efetiva quando ancorados em estruturas cognitivas pré-existentes, isto é, quando se relacionam a conceitos previamente compreendidos e considerados relevantes pelo aprendiz. Ambas as abordagens reforçam a importância de estratégias educativas que promovam significado, confiança e aplicabilidade prática.
Complementarmente, o conceito de literacia em saúde — ou letramento em saúde — assume papel central no sucesso das intervenções educativas. A literacia em saúde pode ser compreendida como a capacidade do indivíduo de acessar, compreender, avaliar e aplicar informações relacionadas à saúde para a tomada de decisões adequadas. Evidências apontam que baixos níveis de literacia estão associados a dificuldades na compreensão de prescrições médicas, interpretação de resultados de exames e reconhecimento de sinais de alerta, resultando em piores desfechos clínicos, maior risco de complicações e uso mais frequente de serviços de urgência. Dessa forma, estratégias educativas eficazes devem necessariamente considerar o nível de compreensão do público-alvo, traduzindo conteúdos técnicos complexos em informações claras, acessíveis e acionáveis.
Apesar de sua reconhecida relevância, os métodos tradicionais de educação em saúde — frequentemente restritos a orientações verbais breves durante consultas clínicas ou à distribuição de materiais impressos padronizados — mostram-se, em muitos casos, insuficientes frente à complexidade do manejo do diabetes mellitus e das doenças cardiovasculares. A sobrecarga cognitiva associada ao momento do diagnóstico, aliada à limitação de tempo dos profissionais de saúde e à ausência de reforço educativo contínuo, contribui para a perda ou interpretação inadequada das informações transmitidas. Esse modelo episódico e fragmentado revela-se incapaz de oferecer o suporte longitudinal necessário para a consolidação de conhecimentos e a incorporação de novos hábitos ao longo do tempo.
Diante dessas limitações, as tecnologias digitais emergem não apenas como instrumentos de apoio, mas como catalisadoras de um novo paradigma para a educação em saúde. Ao possibilitar acesso contínuo, personalizado e contextualizado à informação, as soluções digitais ampliam o alcance do processo educativo para além do ambiente clínico, superando barreiras temporais e espaciais. Nesse contexto, a Organização Mundial da Saúde, em sua estratégia global para a saúde digital, reconhece o potencial dessas tecnologias para democratizar o acesso ao conhecimento, ampliar a cobertura das ações em saúde e, sobretudo, fortalecer o engajamento do paciente, posicionando-o como agente ativo e corresponsável em seu plano de cuidados (OMS, 2021).

2.3 mHealth: aplicativos móveis em saúde
O uso de tecnologias móveis aplicadas à saúde, denominado mobile health (mHealth), é definido pela Organização Mundial da Saúde como a utilização de dispositivos móveis, redes sem fio, sensores e tecnologias associadas para apoiar processos de cuidado, prevenção, monitoramento e educação em saúde (OMS, 2011). A ampla disseminação e o acesso crescente a smartphones transformaram esses dispositivos em plataformas estratégicas para a implementação de intervenções em saúde, especialmente no contexto das Doenças Crônicas Não Transmissíveis (DCNT), cujos portadores se beneficiam de acompanhamento contínuo, registro sistemático de indicadores e estímulos permanentes ao autocuidado.
Nesse cenário, os aplicativos mHealth destacam-se por possibilitar a integração de dimensões educacionais, comportamentais e clínicas em um único ambiente digital. Essas aplicações reúnem funcionalidades como disponibilização de conteúdos educativos estruturados, monitoramento de parâmetros fisiológicos, lembretes terapêuticos, registro de metas, acompanhamento de hábitos de vida e suporte à mudança comportamental. Tal integração contribui para aproximar o conhecimento teórico das práticas cotidianas de cuidado, favorecendo a tomada de decisão informada pelo usuário.
Evidências da literatura apontam que o uso contínuo de aplicativos móveis em saúde pode resultar em melhorias em indicadores clínicos relevantes. Estudos recentes indicam, por exemplo, redução dos níveis de hemoglobina glicada (HbA1c) e maior regularidade no registro de dados de saúde entre pessoas com diabetes que utilizam soluções mHealth de forma sistemática (Silva et al., 2023; Batista; Souza, 2022). Além de favorecer a adesão ao tratamento, essas tecnologias distinguem-se por sua portabilidade, pela capacidade de oferecer intervenções no contexto real do cotidiano do usuário e pela possibilidade de personalização baseada em dados coletados em tempo quase real.
Entretanto, o impacto positivo das soluções mHealth está diretamente condicionado a fatores como clareza da interface, facilidade de uso, confiabilidade das informações e integração com outras plataformas e dispositivos. A ausência de interoperabilidade pode resultar em fragmentação de dados e limitar o valor prático do acompanhamento em saúde. Nesse contexto, soluções como o Health Connect assumem papel relevante ao viabilizar a padronização, a centralização e o compartilhamento seguro de dados, ampliando a consistência das informações e fortalecendo o potencial das aplicações móveis como instrumentos de apoio ao autocuidado e à adesão terapêutica.

2.4 Gamificação aplicada à saúde
A gamificação, compreendida como a aplicação de elementos, mecânicas e dinâmicas típicas de jogos em contextos não relacionados ao entretenimento, tem se consolidado como estratégia promissora para o fortalecimento da motivação, o aumento do engajamento e o apoio a processos de mudança comportamental. Evidências da literatura indicam que a incorporação de componentes como pontos, níveis, metas, desafios e recompensas simbólicas pode contribuir para a ampliação da adesão a rotinas de autocuidado, o incentivo à prática regular de atividade física e o aprimoramento do acompanhamento terapêutico em diferentes contextos de saúde (Johnson et al., 2016; Koivisto; Hamari, 2019).
No campo da saúde, a gamificação não tem como objetivo trivializar o cuidado ou transformá-lo em experiência lúdica desprovida de significado clínico, mas mobilizar mecanismos psicológicos associados à motivação intrínseca. Elementos como a percepção de progresso, o senso de autonomia e o desenvolvimento da competência pessoal — amplamente discutidos em teorias motivacionais — desempenham papel fundamental na manutenção do engajamento ao longo do tempo. Esses aspectos tornam-se particularmente relevantes para indivíduos com Doenças Crônicas Não Transmissíveis (DCNT), que convivem com rotinas terapêuticas contínuas, exigentes e, frequentemente, percebidas como desgastantes.
Ao tornar o processo de cuidado mais estruturado, interativo e orientado a metas alcançáveis, a gamificação pode contribuir para a redução das taxas de abandono de hábitos saudáveis, estimular o interesse pelo próprio processo de aprendizagem e fortalecer o senso de responsabilidade individual no manejo da condição crônica. Dessa forma, quando aplicada de maneira ética, contextualizada e alinhada a objetivos clínicos e educativos, a gamificação configura-se como recurso relevante para potencializar intervenções digitais em saúde, favorecendo a constância de uso e a sustentabilidade das práticas de autocuidado.

2.5 Integração de dados no Android: Health Connect
A fragmentação de dados entre diferentes aplicativos e dispositivos constitui um desafio recorrente no contexto das soluções digitais em saúde, comprometendo a integração das informações e limitando o valor prático do acompanhamento contínuo. Com o objetivo de mitigar esse problema, o ecossistema Android introduziu o Health Connect, uma plataforma concebida para padronizar os processos de armazenamento, gerenciamento e compartilhamento de dados de saúde no nível do dispositivo.
O Health Connect atua como repositório centralizado, no qual as informações de saúde são armazenadas de forma local e criptografada, ampliando os níveis de segurança e privacidade. Além disso, a plataforma adota um modelo de controle centrado no usuário, permitindo que este defina explicitamente quais aplicativos estão autorizados a ler ou gravar tipos específicos de dados, como atividade física, sinais vitais e padrões de sono. Essa abordagem favorece a interoperabilidade entre aplicações, reduz a duplicidade de registros e fortalece a transparência no uso de dados sensíveis, alinhando-se às boas práticas de proteção da informação em saúde.

Figura 2 – Arquitetura de integração de dados da plataforma Health Connect.
Fonte: Android Developers (2022).

Ao oferecer interoperabilidade entre diferentes aplicativos e padronizar dezenas de categorias de dados — como número de passos, frequência cardíaca, padrões de sono e medidas corporais —, o Health Connect contribui para a redução de redundâncias e para o aumento da consistência das informações utilizadas por soluções mHealth (Google, 2024). Essa padronização favorece análises mais confiáveis e comparáveis, além de minimizar inconsistências decorrentes de registros duplicados ou divergentes entre plataformas.
Nesse contexto, a integração com o Health Connect permite que aplicações, como o Educacardio+, associem dados fisiológicos reais ao processo educativo, promovendo aprendizagem mais contextualizada e significativa. Ao relacionar conteúdos teóricos com indicadores extraídos da rotina do próprio usuário, a aplicação tende a reforçar a percepção de utilidade, estimular o engajamento contínuo e apoiar a tomada de decisões mais informadas no autocuidado.

2.6 Privacidade e segurança de dados em saúde
As informações relacionadas à saúde são classificadas pela legislação brasileira como dados pessoais sensíveis, o que impõe elevados requisitos de proteção, governança e transparência no seu tratamento. A Lei Geral de Proteção de Dados Pessoais (LGPD) estabelece princípios fundamentais que devem nortear o uso dessas informações, entre os quais se destacam a finalidade específica, a necessidade e a minimização da coleta, bem como a segurança, a prevenção, a transparência e a responsabilização dos agentes envolvidos (Brasil, 2018). No contexto de ambientes digitais, o atendimento a esses princípios demanda a adoção de práticas técnicas e organizacionais robustas, tais como mecanismos de autenticação segura, criptografia de dados em repouso e em trânsito, controle rigoroso de permissões, políticas de privacidade claras e acessíveis, além do monitoramento contínuo da infraestrutura com vistas à prevenção de incidentes e vazamentos.
Nesse sentido, aplicações móveis voltadas à saúde devem observar diretrizes amplamente reconhecidas no campo da segurança da informação, como as recomendações do OWASP Mobile Top 10, que orientam boas práticas para o desenvolvimento seguro de aplicativos e a mitigação de vulnerabilidades comuns. Inserido nesse contexto, o Health Connect contribui de forma significativa para a governança de dados sensíveis ao adotar um modelo de consentimento granular, no qual o usuário autoriza explicitamente o acesso e a operação sobre tipos específicos de dados. Ademais, a possibilidade de revogação de permissões a qualquer momento reforça o controle do usuário sobre suas informações pessoais, ampliando a proteção da privacidade e fortalecendo a confiança nas soluções digitais destinadas ao acompanhamento e ao cuidado em saúde.

3 METODOLOGIA
Este capítulo apresenta o percurso metodológico adotado para o desenvolvimento e a avaliação do aplicativo Educacardio+. A abordagem escolhida busca assegurar que a solução tecnológica proposta esteja alinhada às necessidades clínicas e educacionais dos usuários, ao mesmo tempo em que observa boas práticas de engenharia de software, usabilidade e os requisitos de interoperabilidade do ecossistema Android.

3.1 Tipo de pesquisa
Quanto à sua natureza, este trabalho caracteriza-se como pesquisa aplicada, uma vez que objetiva gerar conhecimentos voltados à aplicação prática e à solução de problemas específicos — neste caso, o apoio ao autocuidado de pessoas com doenças crônicas (Gil, 2019). O estudo busca, portanto, o desenvolvimento de uma ferramenta tecnológica funcional, capaz de intervir de forma concreta na realidade do público-alvo.
Em relação aos objetivos, a pesquisa possui caráter exploratório e descritivo. É exploratória na etapa inicial, ao aprofundar a compreensão sobre o uso do Health Connect e sobre as diretrizes clínicas relacionadas ao tratamento do diabetes e das cardiopatias. Assume caráter descritivo nas fases de desenvolvimento e avaliação, ao detalhar as características da solução proposta e analisar a percepção dos usuários quanto à sua utilidade e aplicabilidade no contexto do autocuidado.
No que se refere aos procedimentos técnicos, adota-se a pesquisa bibliográfica para a fundamentação teórica do estudo, aliada ao desenvolvimento experimental de software. Complementarmente, realiza-se um estudo de caso preliminar, com o objetivo de avaliar aspectos de usabilidade e adequação da solução desenvolvida.

3.2 Engenharia de requisitos
A etapa de engenharia de requisitos foi conduzida com o objetivo de identificar e especificar os requisitos funcionais e não funcionais do sistema. O processo de elicitação fundamentou-se em duas fontes primárias de informação:
- Análise documental: compreendeu o estudo das diretrizes da Sociedade Brasileira de Diabetes (SBD) e da Organização Mundial da Saúde (OMS), com a finalidade de definir os conteúdos educativos e os principais indicadores de saúde a serem contemplados pela aplicação, tais como glicemia, nível de atividade física e padrões de sono;
- Análise técnica: consistiu no exame da documentação oficial do Android Developers, visando mapear as capacidades, restrições e boas práticas relacionadas à integração de dados por meio do Health Connect, bem como seus requisitos de interoperabilidade e segurança.
Os requisitos identificados foram documentados e priorizados por meio da técnica MoSCoW (Must have, Should have, Could have, Won’t have), assegurando o direcionamento do desenvolvimento para as funcionalidades essenciais e compatíveis com os objetivos do projeto.

3.3 Especificação de software
Antecedendo a fase de codificação, foi realizada a etapa de modelagem do sistema por meio da Linguagem de Modelagem Unificada (UML), com o propósito de garantir a organização lógica dos requisitos, a clareza da arquitetura proposta e a escalabilidade dos componentes da aplicação. Para esse fim, foram elaborados artefatos visuais e documentais capazes de representar tanto o comportamento funcional do sistema quanto a estrutura de dados, servindo como base para o desenvolvimento e para futuras manutenções e evoluções da solução.

3.3.1 Requisitos funcionais
Os requisitos funcionais (RF) descrevem os comportamentos, serviços e funcionalidades específicas que o sistema deve executar a fim de atender às necessidades dos usuários e aos objetivos da aplicação. A priorização desses requisitos foi realizada com base na técnica MoSCoW, assegurando que as funcionalidades consideradas críticas para o monitoramento de indicadores de saúde e para os processos educativos fossem implementadas de forma prioritária, sem comprometer a consistência e a viabilidade do sistema.

Quadro 1 – Requisitos funcionais do Educacardio+
| ID | Descrição | Prioridade |
| --- | --- | --- |
| RF01 | O sistema deve permitir a autenticação de usuários via e-mail/senha e provedor externo (Google Sign-In). | Alta |
| RF02 | O sistema deve sincronizar dados de passos, sono e frequência cardíaca automaticamente por meio da API Health Connect. | Alta |
| RF03 | O usuário poderá registrar manualmente indicadores de saúde (glicemia, peso e frequência cardíaca) caso não possua dispositivos wearables. | Alta |
| RF04 | O sistema deve exibir painéis (dashboards) com gráficos de histórico diário e semanal dos indicadores monitorados. | Alta |
| RF05 | O sistema deve disponibilizar módulos educativos multimídia (texto, vídeo e imagem) sobre diabetes e doenças cardiovasculares. | Alta |
| RF06 | O sistema deve controlar o desbloqueio progressivo das aulas, permitindo acesso ao próximo módulo apenas após a conclusão do anterior. | Alta |
| RF07 | O usuário poderá realizar quizzes de fixação ao final de cada módulo para validar o aprendizado. | Alta |
| RF08 | O sistema deve atribuir pontos e medalhas virtuais ao usuário conforme o cumprimento de metas e conclusão de aulas (gamificação). | Média |
| RF09 | O usuário poderá cadastrar e gerenciar alertas personalizados para horários de medicamentos e aferições de saúde. | Média |
| RF10 | O usuário poderá visualizar seu perfil e editar informações cadastrais básicas. | Baixa |
| RF11 | O sistema deve permitir a configuração de preferências para notificações push (lembretes diários e mensagens motivacionais). | Média |
| RF12 | O sistema deve fornecer atalhos para canais externos de suporte via WhatsApp e e-mail. | Baixa |

3.3.2 Requisitos não funcionais
Enquanto os requisitos funcionais definem o que o sistema deve realizar, os requisitos não funcionais (RNF) estabelecem como o sistema deve se comportar, especificando restrições técnicas, atributos de qualidade e critérios de desempenho indispensáveis para a aceitação do software. No contexto do desenvolvimento do Educacardio+, a definição desses requisitos assumiu caráter central, uma vez que aplicações voltadas à área da saúde demandam padrões elevados de confiabilidade, segurança da informação, privacidade e acessibilidade.
A especificação dos RNF considerou tanto o perfil do público-alvo — que pode incluir idosos e usuários com limitações visuais associadas ao diabetes — quanto as condições inerentes ao ambiente móvel, como variações de desempenho e conectividade. Nesse sentido, priorizou-se a experiência do usuário (UX) por meio de interfaces intuitivas, fluidas e responsivas; a proteção de dados pessoais sensíveis, mediante mecanismos de segurança adequados; e a capacidade de funcionamento em cenários de conectividade limitada, adotando princípios de arquitetura offline-first.
O Quadro 2 apresenta o conjunto de requisitos não funcionais identificados para o projeto, organizados e classificados de acordo com sua prioridade de implementação.

Quadro 2 – Requisitos não funcionais do Educacardio+
| ID | Descrição | Prioridade |
| --- | --- | --- |
| RNF01 | O aplicativo deve operar com arquitetura offline-first, garantindo acesso aos dados cacheados e conteúdo educativo mesmo sem conexão ativa com a internet. | Alta |
| RNF02 | O sistema deve ser compatível com dispositivos móveis executando o sistema operacional Android na versão 8.0 (API nível 26) ou superior. | Alta |
| RNF03 | O acesso aos dados de saúde via API Health Connect deve ocorrer estritamente mediante a concessão explícita de permissões de leitura pelo usuário, garantindo a privacidade. | Alta |
| RNF04 | A interface gráfica deve seguir as diretrizes de acessibilidade do Material Design, utilizando tipografia legível e contraste adequado para usuários com limitações visuais. | Alta |
| RNF05 | As transições de tela e animações de feedback devem manter taxa de atualização mínima de 60 quadros por segundo (fps) para assegurar fluidez na navegação. | Média |
| RNF06 | O tempo de resposta para a sincronização de dados e carregamento de gráficos não deve exceder 3 segundos em condições normais de processamento. | Média |
| RNF07 | O tráfego de dados sensíveis entre o aplicativo e os serviços em nuvem (Firebase) deve ser realizado exclusivamente via protocolo seguro (HTTPS/SSL). | Alta |
| RNF08 | O aplicativo deve possuir tamanho final de instalação otimizado (abaixo de 150 MB) para facilitar o download em redes móveis limitadas. | Baixa |

3.3.3 Modelagem de dados
Para a persistência das informações do sistema, adotou-se o Google Cloud Firestore, um banco de dados NoSQL orientado a documentos, amplamente utilizado em aplicações móveis e distribuídas. Diferentemente dos sistemas gerenciadores de bancos de dados relacionais (RDBMS), nos quais os dados são organizados em tabelas com esquemas rígidos e relações previamente definidas, o Firestore armazena informações em documentos estruturados, geralmente representados em formato JSON, agrupados em coleções hierárquicas. Essa abordagem favorece uma modelagem de dados mais alinhada ao domínio da aplicação e aos padrões de consumo de dados típicos de interfaces reativas.
A escolha do Firestore fundamenta-se principalmente em três aspectos: flexibilidade de esquema, sincronização em tempo real e suporte nativo ao funcionamento offline. Por adotar um modelo schema-less, o banco de dados permite a evolução incremental dos atributos associados aos usuários, aos indicadores fisiológicos e aos registros educacionais, reduzindo a necessidade de migrações estruturais complexas ao longo do ciclo de desenvolvimento. Essa característica mostra-se particularmente relevante em projetos de natureza exploratória e iterativa, como o Educacardio+.
Adicionalmente, os mecanismos nativos de atualização em tempo real possibilitam que alterações persistidas no banco sejam refletidas imediatamente na interface do usuário, contribuindo para uma experiência de uso mais dinâmica e responsiva, característica essencial em aplicações de monitoramento e acompanhamento em saúde. O suporte ao modo offline, por sua vez, garante a continuidade das operações de leitura e escrita mesmo na ausência de conectividade, por meio de cache local e sincronização automática assim que a conexão é restabelecida, alinhando-se aos requisitos de disponibilidade definidos para o sistema.
A organização do armazenamento foi estruturada por meio de coleções raiz, de modo a separar responsabilidades relacionadas à autenticação dos usuários, aos dados biométricos integrados via Health Connect e ao conteúdo educativo disponibilizado pela aplicação. Essa segmentação contribui para a manutenibilidade, escalabilidade e clareza do modelo de dados, além de reduzir o acoplamento entre os diferentes módulos do sistema. A Figura 3 apresenta o esquema lógico das principais coleções definidas para o Educacardio+, evidenciando suas relações e responsabilidades no contexto da arquitetura proposta.

Figura 3 – Esquema da estrutura de dados NoSQL.
Fonte: Elaborado pelo autor.

3.3.4 Casos de uso
Uma vez definidos os requisitos funcionais e não funcionais, tornou-se necessário detalhar de que forma as interações entre o usuário e o sistema se materializam no uso cotidiano da aplicação. Para esse fim, adotou-se a técnica de especificação de casos de uso, cujo objetivo é descrever, de forma estruturada e textual, os fluxos de interação, as condições de exceção e o comportamento esperado do software em cenários representativos do mundo real.
De acordo com Sommerville (2011, p. 86), os casos de uso desempenham papel central no processo de modelagem, uma vez que “representam uma tarefa que envolve uma interação com o sistema”, constituindo-se como importante artefato de comunicação entre desenvolvedores e partes interessadas (stakeholders). Essa característica favorece a validação dos requisitos levantados, assegurando que as funcionalidades especificadas estejam alinhadas às necessidades e expectativas dos usuários finais.
Nesse contexto, os principais fluxos do aplicativo Educacardio+ foram documentados com o propósito de garantir compreensão inequívoca das regras de negócio e do comportamento do sistema. Os Quadros 3 a 7 apresentam a especificação detalhada dos casos de uso considerados críticos, contemplando desde processos de autenticação e gamificação até funcionalidades de monitoramento de indicadores de saúde e configurações do sistema, oferecendo visão integrada das interações essenciais da aplicação.

Figura 4 – Diagrama de casos de uso.
Fonte: Elaborado pelo autor.

Quadro 3 – Caso de uso: autenticar e registrar usuário
- Identificador: UC001
- Breve descrição: o usuário realiza o acesso ao aplicativo por login (e-mail/Google) ou cria nova conta, estabelecendo uma sessão segura.
- Atores primários: usuário.
- Atores secundários: Firebase Authentication, sistema (aplicativo).
- Pré-condições: dispositivo com conexão à internet ativa.
- Fluxo principal:
  1. O usuário abre o aplicativo e o sistema verifica se já existe sessão ativa.
  2. Caso não autenticado, o sistema exibe a tela de pré-login.
  3. O usuário seleciona o método de entrada:
     a) Login Google: o sistema inicia o fluxo OAuth 2.0; o usuário autoriza a conta e o Firebase valida o token.
     b) Login e-mail: o usuário insere credenciais; o sistema valida o formato e o Firebase autentica.
     c) Registrar: o usuário preenche nome, e-mail e senha; o sistema valida os campos e cria o documento do usuário no banco de dados (users/{userId}).
  4. Após validação bem-sucedida, o sistema carrega o perfil do usuário e inicializa o contexto de autenticação.
  5. O sistema redireciona o usuário para a tela inicial (Home).
- Pós-condições: usuário autenticado, token de sessão salvo localmente e perfil carregado.

Quadro 4 – Caso de uso: visualizar dashboard e gamificação
- Identificador: UC002
- Breve descrição: o sistema exibe a tela principal com o progresso do usuário (nível/pontos) e sugestões de conteúdo.
- Atores primários: usuário (paciente).
- Atores secundários: Firebase Firestore.
- Pré-condições: usuário autenticado (UC001).
- Fluxo principal:
  1. O sistema carrega a tela Home e exibe mensagem de boas-vindas.
  2. Paralelamente, o sistema executa as seguintes buscas no backend:
     a) consulta o histórico de progresso (users/{userId}/progress) para somar o total de pontos;
     b) calcula o nível atual (Total de pontos / 30) e renderiza a medalha correspondente;
     c) carrega tópicos de conscientização e módulos educativos disponíveis.
  3. O usuário visualiza seu progresso e pode interagir com os cards informativos ou navegar para outras abas.
  4. Caso o usuário selecione um artigo de conscientização, o sistema exibe o conteúdo estático detalhado.
- Pós-condições: dados de gamificação atualizados e interface de navegação disponível.

Quadro 5 – Caso de uso: consumir conteúdo educativo
- Identificador: UC003
- Breve descrição: o usuário acessa módulos de doenças, consome aulas multimídia, realiza quizzes e desbloqueia novas etapas.
- Atores primários: usuário (paciente).
- Atores secundários: Firebase Firestore.
- Pré-condições: estar na tela de tópicos e ter o módulo anterior concluído (para módulos > 0).
- Fluxo principal:
  1. O usuário seleciona uma doença (ex.: diabetes) e o sistema lista os módulos.
  2. O sistema verifica no Firebase quais módulos já foram concluídos para liberar ou bloquear o acesso.
  3. O usuário seleciona um módulo desbloqueado.
  4. O sistema apresenta o conteúdo conforme o tipo:
     a) Aprender: textos, imagens e vídeos;
     b) Quiz: questionário interativo com validação de respostas;
     c) Hábitos: lista de verificação.
  5. Ao finalizar, o usuário marca como “Concluído”.
  6. O sistema atualiza o progresso no servidor, atribui +10 pontos e verifica se houve subida de nível.
  7. O módulo seguinte é desbloqueado automaticamente.
- Pós-condições: progresso salvo, pontos atribuídos e próximo módulo liberado.

Quadro 6 – Caso de uso: gerenciar indicadores de saúde
- Identificador: UC004
- Breve descrição: o usuário sincroniza dados via Health Connect, registra medições manuais e gerencia alertas de saúde.
- Atores primários: usuário (paciente).
- Atores secundários: Health Connect API (Android), Firebase Firestore.
- Pré-condições: acesso à aba “Indicadores”.
- Fluxo principal:
  1. Sincronização: o usuário solicita sincronização. O sistema verifica permissões do Health Connect. Se concedidas, lê dados de passos, sono e frequência cardíaca e atualiza a interface.
  2. Registro manual: o usuário aciona a inclusão manual, insere dados (glicemia, peso, BPM) e o sistema salva no histórico.
  3. Alertas: o usuário pode criar lembretes personalizados (medicamentos/medições). O sistema salva a configuração no Firebase e agenda uma notificação local no dispositivo.
  4. O sistema exibe gráficos históricos combinando dados automáticos e manuais.
- Pós-condições: base de dados de saúde atualizada e alertas agendados no dispositivo.

Quadro 7 – Caso de uso: configurações e suporte
- Identificador: UC005
- Breve descrição: o usuário gerencia preferências de notificação, acessa canais de suporte e encerra a sessão.
- Atores primários: usuário (paciente).
- Atores secundários: aplicativos externos (WhatsApp/e-mail), armazenamento local.
- Pré-condições: menu lateral (Drawer) acessível.
- Fluxo principal:
  1. O usuário acessa as Configurações via menu lateral.
  2. Notificações: o usuário altera os switches de “Lembrete diário” ou “Motivacional”. O sistema atualiza o armazenamento local (AsyncStorage) e agenda/cancela as notificações correspondentes.
  3. Suporte: o usuário seleciona “Fale conosco” ou “E-mail”. O sistema invoca aplicativos externos (WhatsApp/Gmail) para contato direto.
  4. Logout: o usuário seleciona “Sair”. O sistema limpa o contexto de autenticação, encerra a sessão no Firebase e redireciona para a tela de login.
- Pós-condições: preferências salvas ou sessão do usuário encerrada com segurança.

3.4 Prototipação e design da interface
O design das interfaces priorizou a experiência do usuário (UX) e a acessibilidade, considerando que o público-alvo pode incluir idosos ou pessoas com limitações visuais decorrentes do diabetes. Utilizou-se a ferramenta Figma para a criação de protótipos de alta fidelidade. O sistema de design adotou componentes visuais claros, tipografia legível e cores que facilitam a distinção de elementos, seguindo as diretrizes do Material Design do Google.

Figura 5 – Protótipo inicial.
Fonte: Elaborado pelo autor.

A organização das telas, apresentada na Figura 5, reflete a jornada do usuário mapeada nos diagramas de caso de uso. O fluxo inicia-se com interfaces de onboarding e autenticação (login e cadastro) com formulários simplificados para reduzir a barreira de entrada. Após o acesso, o usuário é direcionado à tela de menu principal, que centraliza as informações de gamificação e oferece atalhos rápidos para as funcionalidades críticas. Destacam-se as telas de monitoramento de indicadores, que empregam feedbacks visuais imediatos por meio de janelas modais como as mensagens de “Tudo bem!” ou “Muito bem!”, reforçando positivamente o engajamento do paciente. Por fim, o módulo educativo utiliza um layout baseado em cards para organizar temas complexos, como diabetes e insuficiência cardíaca, em pílulas de conhecimento mais digeríveis.

3.5 Ferramentas e tecnologias utilizadas
A seleção do conjunto de tecnologias para o desenvolvimento do Educacardio+ baseou-se em critérios de desempenho, escalabilidade, facilidade de manutenção e suporte da comunidade. A seguir, detalham-se as ferramentas adotadas em cada camada da aplicação.

3.5.1 Ambiente de desenvolvimento (IDE)
Para a escrita e orquestração do código, estruturou-se um ambiente de desenvolvimento configurado para maximizar a produtividade e facilitar a detecção precoce de erros.
Nesse contexto, o Visual Studio Code (VS Code) foi adotado como editor de código-fonte principal. A escolha desta ferramenta justifica-se pelo seu vasto ecossistema de extensões, incluindo ESLint e Prettier, fundamentais para a padronização estilística do código, bem como pela sua integração nativa com o sistema de versionamento Git e pelo suporte robusto à linguagem TypeScript.
Concomitantemente, utilizou-se o Android Studio para tarefas específicas da plataforma móvel, como o gerenciamento do Android SDK, a configuração de emuladores (Android Virtual Devices – AVD) e a análise de logs nativos via Logcat. O uso desta ferramenta foi imprescindível para realizar configurações críticas de sistema, tais como a definição das versões de compilação do Gradle (compileSdkVersion 36) e a garantia de compatibilidade da aplicação com o Android 8.0 (API 26) ou superior.

3.5.2 Framework de desenvolvimento e linguagem
A camada de frontend móvel foi construída utilizando uma abordagem híbrida com renderização nativa, tendo como base o React Native (v0.72.10). Desenvolvido pelo Facebook (Meta), este framework foi escolhido pela sua capacidade de gerar interfaces nativas utilizando JavaScript e React, garantindo desempenho próximo ao de aplicações desenvolvidas nativamente em Java ou Kotlin. Além disso, a ferramenta viabiliza o compartilhamento de código entre plataformas e oferece o recurso de Hot Reload, essencial para a aceleração do ciclo de desenvolvimento (Facebook, 2023).
Integrado a esse ecossistema, o Expo SDK (v49.0.0) foi adotado como camada de abstração e ferramental sobre o React Native. Sua utilização simplificou substancialmente a integração de recursos nativos complexos que, de outra forma, exigiriam configuração manual extensa, tais como o gerenciamento de notificações (expo-notifications), o carregamento de fontes personalizadas (expo-font) e os fluxos de autenticação via OAuth (expo-auth-session).
Para garantir a robustez e a manutenibilidade do código, o projeto foi escrito em TypeScript (v5.1.3), um superset do JavaScript desenvolvido pela Microsoft. A adoção desta linguagem adicionou tipagem estática ao projeto, proporcionando maior segurança de tipos e um IntelliSense aprimorado no ambiente de desenvolvimento. Essa escolha facilitou a refatoração segura do código e contribuiu significativamente para a redução da incidência de bugs em tempo de execução (Microsoft, 2023).

3.5.3 Backend e serviços em nuvem (BaaS)
Para a infraestrutura do projeto, optou-se pela adoção de uma arquitetura serverless baseada na plataforma Google Firebase, estratégia que eliminou a complexidade associada ao provisionamento e gerenciamento de servidores físicos.
No que tange à segurança e gestão de identidade, implementou-se o Firebase Authentication (v11.8.1). Este serviço gerencia integralmente o ciclo de vida da autenticação, suportando desde o login tradicional (e-mail e senha) até a integração OAuth 2.0 com Google Sign-In, além de automatizar fluxos críticos como a recuperação de senhas e garantir a persistência segura da sessão do usuário.
Complementarmente, a camada de persistência de dados foi estruturada sobre o Firebase Firestore (v11.8.1), um banco de dados NoSQL orientado a documentos. A ferramenta foi utilizada para o armazenamento escalável do perfil do usuário, do histórico de indicadores de saúde e do progresso nos módulos educativos. A escolha por esta tecnologia fundamentou-se, de modo determinante, em sua capacidade nativa de sincronização em tempo real e no suporte robusto ao funcionamento offline (cache local), garantindo a usabilidade do aplicativo mesmo em condições de conectividade instável.

3.5.4 Integração com API de saúde e interoperabilidade
Visando cumprir o requisito de monitoramento de indicadores de saúde sem a dependência exclusiva de wearables proprietários, recorreu-se à capacidade de integração nativa do sistema operacional. Para operacionalizar essa comunicação, adotou-se a biblioteca React Native Health Connect (v3.3.3).
Este componente atua como ponte de interoperabilidade entre a aplicação desenvolvida e a API Health Connect do Android, permitindo a leitura padronizada e granular de dados fisiológicos tais como contagem de passos, frequência cardíaca e padrões de sono, assegurando, simultaneamente, o respeito às permissões de privacidade concedidas pelo usuário.

3.5.5 Navegação, interface e animações
A construção da interface gráfica priorizou fluidez e intuitividade, elementos cruciais para a retenção de usuários em aplicações de saúde. Para a orquestração das rotas e gestão do fluxo de telas, adotou-se o React Navigation (v6.x). Esta biblioteca permitiu estruturar a arquitetura de informação do aplicativo combinando estratégias de navegação em pilha (Stack Navigation), ideal para fluxos lineares e aprofundamento de conteúdo, com a navegação em abas (Bottom Tabs), utilizada para o acesso rápido às seções principais da aplicação.
Visando enriquecer a interatividade e fornecer feedbacks visuais consistentes, integrou-se ao projeto a biblioteca React Native Reanimated (v3.3.0). A ferramenta foi selecionada por sua capacidade de executar animações de alta performance diretamente na thread de UI nativa, garantindo transições suaves e responsivas a 60 quadros por segundo, evitando gargalos de processamento comuns na ponte de comunicação do JavaScript.
Complementarmente, o refino estético da interface apoiou-se em bibliotecas especializadas de UI. Utilizou-se o React Native Vector Icons, especificamente os conjuntos Ionicons e Feather para uma iconografia limpa e semântica, enquanto a tipografia foi gerenciada pelo Expo Google Fonts, assegurando o carregamento otimizado e a padronização visual da família Poppins em todas as telas.

3.5.6 Qualidade de código
Para assegurar a confiabilidade do software, foram empregadas ferramentas de análise estática e testes automatizados. O Jest foi o framework escolhido para a execução de testes unitários, cobrindo funções de lógica de negócio como cálculos de conversão de unidades e regras de pontuação, além de testes de componentes isolados. Em paralelo, utilizou-se o conjunto ESLint e Prettier para linting e formatação, garantindo a padronização do estilo de código e prevenindo erros de sintaxe comuns durante o fluxo de desenvolvimento.

3.5.7 Versionamento e distribuição (CI/CD)
O gerenciamento do ciclo de vida do código e a integridade do projeto foram assegurados pela utilização do sistema de controle de versão distribuído Git, hospedado na plataforma GitHub. Essa infraestrutura permitiu o rastreamento granular de alterações e a organização do fluxo de trabalho por meio de branches de funcionalidades, facilitando o desenvolvimento paralelo e o histórico de evoluções do software. Para a etapa de construção e distribuição automatizada, adotou-se o Expo Application Services (EAS). Esta plataforma de build em nuvem foi responsável pela geração dos binários finais para o sistema Android (formatos .apk e .aab), abstraindo a complexidade das configurações de ambiente nativo local. Além disso, o EAS gerenciou de forma segura as credenciais de assinatura digital (keystore), otimizando o processo de deploy e garantindo a padronização das entregas.

3.6 Estratégia de testes e avaliação
A validação do Educacardio+ foi estruturada em duas dimensões complementares: a verificação técnica, visando assegurar a corretude do código e a estabilidade da aplicação; e a validação com usuários, focada na percepção de valor e usabilidade da solução proposta.

3.6.1 Testes de software e integração
Para garantir a confiabilidade técnica, adotou-se uma abordagem mista de testes. Foram aplicados testes unitários utilizando o framework Jest para validar funções isoladas e garantir que os componentes individuais operassem conforme o esperado.
Em seguida, realizaram-se testes funcionais (caixa-preta) manualmente em emuladores e dispositivos físicos, com foco nos fluxos críticos como autenticação e persistência de dados. Por fim, executaram-se testes de integração com Health Connect em dispositivos reais, verificando a precisão na leitura de dados (passos, sono, frequência cardíaca) e o tratamento de exceções no fluxo de permissões.

3.6.2 Avaliação de usabilidade e utilidade
Após a estabilização da versão beta do aplicativo, procedeu-se à avaliação subjetiva com um grupo amostral de usuários potenciais. O instrumento de coleta de dados foi um questionário eletrônico estruturado (Google Forms), aplicado após um período de uso assistido da aplicação.
O questionário foi desenhado para mensurar três aspectos fundamentais:
- Usabilidade percebida: facilidade de navegação, clareza da interface e legibilidade das fontes (Poppins);
- Utilidade percebida: relevância do conteúdo educativo sobre diabetes e DCVs e a utilidade dos gráficos de monitoramento;
- Engajamento: impacto dos elementos de gamificação (pontos e conquistas) na motivação para o uso contínuo.
Os dados coletados foram tratados estatisticamente de forma descritiva e serviram de base para a análise dos resultados apresentada no capítulo subsequente.

4 DESENVOLVIMENTO
Este capítulo dedica-se à descrição do processo de implementação do aplicativo Educacardio+, evidenciando a forma como os requisitos definidos nos capítulos anteriores foram traduzidos em uma solução de software funcional e operacional. A etapa de desenvolvimento foi conduzida à luz dos princípios da engenharia de software contemporânea, com ênfase em modularidade, escalabilidade e manutenibilidade, bem como na centralidade da experiência do usuário.
Para viabilizar esses objetivos, adotou-se o framework React Native, associado ao ecossistema Expo, o que permitiu acelerar o ciclo de desenvolvimento e facilitar a integração com recursos nativos do sistema operacional Android, incluindo sensores e serviços de saúde. Essa escolha tecnológica favoreceu a reutilização de componentes, a padronização da interface e a implementação de boas práticas de desenvolvimento, assegurando maior consistência, desempenho e qualidade ao produto final.

4.1 Visão geral da solução
A solução desenvolvida consiste em um aplicativo móvel híbrido, concebido para atuar como um hub centralizador de apoio ao gerenciamento do diabetes e da saúde cardiovascular. O Educacardio+ foi projetado para operar de forma resiliente em cenários de conectividade intermitente, adotando uma abordagem offline-first, na qual dados essenciais — como conteúdos educativos e o histórico recente de interações e indicadores — são armazenados em cache local no dispositivo e sincronizados automaticamente com a infraestrutura em nuvem (Firebase) assim que a conexão é restabelecida.
A interface do usuário (UI) foi desenvolvida em conformidade com um design system previamente definido, assegurando consistência visual, acessibilidade e previsibilidade nas interações. Essa padronização contribui para uma experiência de navegação fluida e intuitiva, reduzindo a curva de aprendizado e favorecendo a adoção contínua da aplicação, conforme exemplificado pela tela principal do aplicativo.

4.2 Arquitetura e estrutura do projeto
A organização do código-fonte foi concebida de modo a refletir explicitamente o princípio de Separação de Responsabilidades (Separation of Concerns), considerado fundamental para assegurar a manutenibilidade, extensibilidade e testabilidade do sistema ao longo de seu ciclo de vida. Essa abordagem permite que alterações em um componente específico — como regras de negócio, camadas de dados ou apresentação — ocorram com impacto mínimo sobre os demais módulos da aplicação.
No diretório raiz src, os arquivos e pastas foram organizados de forma semântica e funcional, promovendo a clara distinção entre lógica de negócio, componentes de interface, serviços de integração, gerenciamento de estado e utilitários compartilhados. Tal estrutura reduz o acoplamento entre camadas, favorece a reutilização de código e facilita a compreensão do projeto por novos desenvolvedores.
A Figura 6 apresenta a árvore de diretórios final do projeto, evidenciando a hierarquia adotada e a distribuição dos módulos, bem como a aderência aos princípios de modularidade e organização recomendados para aplicações móveis desenvolvidas com React Native.

Figura 6 – Estrutura de pastas e arquivos.
Fonte: Elaborado pelo autor.

Nessa arquitetura, o diretório components concentra elementos de interface reutilizáveis e de granularidade atômica, como botões, cartões e outros componentes visuais independentes de contexto, favorecendo a padronização visual e a reutilização ao longo da aplicação. O diretório screens, por sua vez, abriga as telas completas do aplicativo, responsáveis por compor esses componentes e orquestrar fluxos de interação, lógica de apresentação e chamadas aos serviços necessários.
A comunicação com serviços externos, APIs e camadas de persistência foi devidamente isolada no diretório services, de modo a encapsular as complexidades relacionadas à rede, autenticação e acesso a dados, preservando a coesão das camadas superiores da aplicação. Essa separação contribui para maior testabilidade e facilita a substituição ou evolução de serviços sem impacto direto na interface do usuário.
O gerenciamento de estado global, fundamental para garantir a consistência das informações do usuário entre diferentes telas e fluxos de navegação, foi implementado por meio da Context API do React, com seus respectivos provedores e consumidores organizados no diretório contexts. Essa abordagem permite o compartilhamento controlado de estados e ações, reduzindo a necessidade de prop drilling e simplificando a comunicação entre componentes distantes na hierarquia.
Por fim, as definições de rotas, pilhas de navegação e regras de transição entre telas foram centralizadas no diretório navigation, assegurando uma visão unificada dos fluxos de navegação e facilitando a manutenção e evolução da experiência do usuário.

4.3 Design navegacional e fluxos
O planejamento da interação do usuário com o aplicativo foi fundamentado na metodologia OOHDM (Object-Oriented Hypermedia Design Method), amplamente utilizada no projeto de sistemas hipermídia orientados a objetos. De acordo com Berbo e Baesso (2004), essa metodologia estrutura o desenvolvimento em três macroetapas — análise, projeto e implementação — combinando o paradigma da orientação a objetos com o uso de modelos de estados, de modo a abranger de forma sistemática os diferentes aspectos funcionais e interacionais de um sistema.
No âmbito do OOHDM, a fase de design navegacional assume papel central, uma vez que tem por objetivo definir os nós de informação, os links de navegação, as estruturas de acesso e os elementos de interface que mediam a interação entre o usuário e o sistema. O principal artefato resultante dessa etapa é o esquema de contexto, um diagrama que modela as interações disponíveis a partir da perspectiva do usuário final, considerando seu perfil, os casos de uso identificados e os princípios de usabilidade.
No contexto do desenvolvimento do Educacardio+, essa modelagem conceitual mostrou-se fundamental para mapear previamente a jornada do usuário/paciente, antes da etapa de codificação, assegurando que o acesso às informações de saúde e às funcionalidades do aplicativo fosse organizado de maneira lógica, progressiva e intuitiva. A Figura 7 apresenta o diagrama navegacional elaborado, evidenciando a hierarquia das telas, os pontos de entrada do sistema e os principais fluxos de navegação disponíveis ao usuário.

Figura 7 – Diagrama navegacional (OOHDM).
Fonte: Elaborado pelo autor.

Na etapa de implementação, o fluxo de navegação previamente modelado foi materializado por meio da biblioteca React Navigation, amplamente adotada no ecossistema React Native para gerenciamento de rotas e estados de navegação. O controle central da navegação é realizado por um orquestrador principal, representado pelo arquivo AppNavigator.tsx, responsável por aplicar lógica de roteamento condicional baseada no estado de autenticação do usuário.
Usuários não autenticados são direcionados a um fluxo controlado e linear, composto pelas etapas de onboarding e autenticação, assegurando que o acesso às funcionalidades do sistema ocorra somente após a identificação adequada. Uma vez autenticado, o usuário passa a integrar a estrutura principal da aplicação, que adota uma arquitetura de navegação híbrida. Essa arquitetura combina um menu lateral (Drawer Navigator), destinado ao acesso a configurações globais e informações institucionais, com uma barra de navegação inferior (Tab Navigator), que possibilita a alternância rápida e intuitiva entre os principais módulos do aplicativo, tais como educação em saúde, monitoramento de indicadores e gamificação.
Essa abordagem contribui para a coerência entre o modelo navegacional concebido na fase de projeto e a experiência efetivamente oferecida ao usuário, favorecendo a usabilidade, a previsibilidade das interações e a eficiência no acesso às funcionalidades essenciais do Educacardio+.

4.4 Implementação das funcionalidades
A etapa de codificação consistiu na tradução dos requisitos especificados e dos modelos conceituais em funcionalidades plenamente operacionais. Nessa fase, os artefatos produzidos nas etapas de análise e projeto foram concretizados por meio da implementação dos componentes de software, respeitando as diretrizes arquiteturais definidas. A seguir, são descritas as implementações dos módulos críticos do sistema, estabelecendo-se a correlação entre as decisões técnicas adotadas e os objetivos de promoção da saúde, apoio ao autocuidado e estímulo ao engajamento do usuário que orientaram o desenvolvimento do Educacardio+.

4.4.1 Autenticação e gestão de sessão
A segurança e a personalização da experiência do usuário foram implementadas por meio do serviço Firebase Authentication, escolhido em razão de sua robustez no gerenciamento de credenciais, suporte a múltiplos métodos de autenticação e integração nativa com o ecossistema Android. Essa solução permite o controle confiável de identidade, requisito essencial para aplicações que manipulam dados sensíveis de saúde.
Para o gerenciamento global do estado de autenticação, foi adotada a Context API do React, evitando acoplamento excessivo entre componentes e a necessidade de propagação manual de propriedades (prop drilling). O componente AuthContext atua como repositório central da sessão do usuário, assegurando que informações críticas — como identificador único e nome — estejam acessíveis de forma consistente em todas as telas da aplicação.
Um aspecto central da implementação diz respeito à persistência da sessão. Com o objetivo de aprimorar a usabilidade e reduzir fricções no acesso, o aplicativo monitora continuamente as mudanças no estado de autenticação. Para isso, utiliza-se um listener em tempo real fornecido pelo Firebase Authentication, permitindo identificar automaticamente se há token de sessão válido no momento da inicialização do aplicativo. Quando identificado, o sistema carrega de forma transparente o perfil do usuário previamente armazenado no banco de dados, dispensando a necessidade de um novo processo de login. O Código 1 ilustra a utilização do hook useEffect para implementar esse mecanismo de verificação e recuperação automática da sessão ativa.

Código 1 – Lógica de persistência de sessão no AuthContext
```typescript
useEffect(() => {
  const unsubscribe = onAuthStateChanged(auth, async (firebaseUser) => {
    try {
      if (firebaseUser) {
        const userDocRef = doc(db, 'users', firebaseUser.uid);
        const userDoc = await getDoc(userDocRef);

        if (userDoc.exists()) {
          setUser(userDoc.data() as User);
        }
      } else {
        setUser(null);
      }
    } catch (error) {
      console.error('Erro na verificação de sessão:', error);
    } finally {
      setLoading(false);
    }
  });

  return () => unsubscribe();
}, []);
```

As interfaces de acesso foram projetadas com foco na usabilidade e na prevenção de erros, incorporando formulários claros, campos bem rotulados e mecanismos de validação de entrada que orientam o usuário durante o preenchimento e reduzem a ocorrência de inconsistências e erros de digitação.

Figura 8 – Fluxo de autenticação: telas de login e cadastro.
Fonte: Elaborado pelo autor.

4.4.2 Módulo educativo dinâmico
A arquitetura de conteúdo do aplicativo foi concebida de modo a desacoplar a lógica de programação do material didático, promovendo maior flexibilidade e facilidade de manutenção. Em vez de incorporar textos e informações clínicas diretamente nas interfaces (hardcoded), adotou-se uma abordagem data-driven (orientada a dados), na qual o conteúdo é estruturado e gerenciado de forma independente do código de apresentação.
O elemento central dessa estratégia é o arquivo diseaseModules.ts, que funciona como repositório estruturado de conhecimento, organizando as patologias em objetos JSON complexos e semanticamente definidos. Essa modelagem permite que o aplicativo renderize dinamicamente diferentes tipos de mídia — como textos explicativos, vídeos educativos e referências bibliográficas — sem a necessidade de alterações no código-fonte ou recompilação da aplicação.
O Código 2 apresenta um fragmento representativo do módulo de insuficiência cardíaca, evidenciando a declaração estruturada dos conteúdos textuais, a incorporação de vídeos educacionais provenientes do YouTube e a associação de fontes bibliográficas, demonstrando a extensibilidade e a reutilização proporcionadas por essa abordagem.

Código 2 – Estrutura de dados mista
```typescript
export const diseaseModules = {
  "1": {
    "name": "Insuficiência Cardíaca",
    "modules": [
      {
        "type": "learn",
        "title": "Entendendo a Insuficiência Cardíaca",
        "content": [
          {
            "type": "paragraph",
            "text": "A Insuficiência Cardíaca (IC) é definida pela Sociedade Brasileira de Cardiologia..."
          },
          {
            "type": "video",
            "src": "https://www.youtube.com/watch?v=yIpXxwin64Q"
          },
          {
            "type": "list",
            "items": [
              "Ortopneia: falta de ar imediata ao se deitar reto na cama.",
              "Ganho de peso súbito: aumento de >2 kg em 3 dias..."
            ]
          }
        ],
        "references": [
          "Diretriz Brasileira de Insuficiência Cardíaca Crônica e Aguda - SBC."
        ]
      }
    ]
  }
};
```

Além do conteúdo expositivo, o sistema oferece recursos interativos por meio de estruturas de questionários (quizzes) e hábitos, ampliando o envolvimento do usuário no processo de aprendizagem. A lógica de verificação do aprendizado foi incorporada diretamente à estrutura de dados, na qual são definidos os enunciados das perguntas, as alternativas de resposta e a opção correta, possibilitando validação imediata das interações na interface do usuário.
O componente responsável pela apresentação, denominado DiseaseModuleScreen, percorre essa árvore de dados e determina, em tempo de execução, qual componente visual deve ser renderizado, como um reprodutor de vídeo, uma lista de verificação (checklist) ou um cartão de pergunta interativa. Essa abordagem favorece a reutilização de componentes e confere maior flexibilidade à aplicação. A Figura 9 ilustra o resultado da renderização dinâmica do conteúdo, apresentando um módulo educativo sobre hipertensão arterial com elementos multimídia e interativos integrados em uma única experiência de aprendizagem.

Figura 9 – Dinâmica de conteúdo educativo.
Fonte: Elaborado pelo autor.

4.4.3 Monitoramento de saúde e integração Health Connect
O sistema de monitoramento foi concebido a partir de uma arquitetura híbrida estratégica, projetada para superar limitações recorrentes em aplicações de saúde convencionais. Essa abordagem viabiliza a coexistência de dois fluxos complementares de dados: (i) a entrada ativa de informações clínicas, de caráter subjetivo ou manual, e (ii) a coleta passiva de métricas fisiológicas objetivas, obtidas automaticamente por sensores do dispositivo.
Para os indicadores que requerem aferição externa ou autorrelato — como glicemia capilar, peso corporal e pressão arterial — foi implementado um serviço de persistência em nuvem por meio do Google Cloud Firestore. A lógica de negócio associada a esses registros encontra-se centralizada no arquivo indicatorService.ts, responsável por gerenciar as operações de escrita no banco de dados. Os dados são armazenados em subcoleção específica por usuário (users/{uid}/indicators), assegurando isolamento lógico, organização hierárquica e reforço à privacidade das informações sensíveis.
Em paralelo, a coleta automatizada de dados via API Health Connect constitui o principal avanço técnico da solução. O processo de sincronização é orquestrado no componente UserIndicatorsScreen.tsx, seguindo fluxo estruturado que compreende: verificação e solicitação de permissões, definição do intervalo temporal de coleta (base diária) e leitura dos dados brutos referentes à atividade física (passos), frequência cardíaca e padrões de sono. Esses dados são posteriormente processados e agregados, permitindo sua visualização imediata na interface do usuário, sem necessidade de intervenção manual.
O Código 3 ilustra a implementação da função handleSyncHealth, responsável por materializar essa lógica de integração, conectando o front-end do aplicativo aos sensores do ecossistema Android por meio do Health Connect, consolidando métricas fisiológicas reais no fluxo de acompanhamento do Educacardio+.

Código 3 – Lógica de sincronização e processamento de dados do Health Connect
```typescript
const handleSyncHealth = useCallback(async () => {
  if (Platform.OS !== 'android') return;

  setLoadingHealth(true);
  try {
    await ensureHealthConnectInitialized();
    const permissions = await checkPermissions();

    if (!permissions.length) {
      setHasPermission(false);
      setHealthError("Permissão não concedida.");
      return;
    }

    const startTime = new Date(new Date().setHours(0, 0, 0, 0)).toISOString();
    const endTime = new Date().toISOString();
    const stepsResult = await readRecords('Steps', {
      timeRangeFilter: { operator: 'between', startTime, endTime },
    });

    const safeSteps = aggregateDailySteps(stepsResult.records.map(r => ({
      value: r.count,
      startDate: r.startTime
    })));

    setHcSteps(safeSteps);
  } catch (error) {
    console.error(error);
    setHealthError('Erro ao buscar dados de saúde.');
  } finally {
    setLoadingHealth(false);
  }
}, []);
```

A interface resultante dessa integração é ilustrada na Figura 10, evidenciando a convergência dos diferentes fluxos de informação. Na porção superior da tela, o painel de indicadores automáticos apresenta as métricas reais sincronizadas diretamente do dispositivo, enquanto, na seção subsequente, são exibidos os registros manuais históricos, recuperados do servidor e organizados de forma cronológica, possibilitando visão integrada e contínua do acompanhamento em saúde.

Figura 10 – Painel de monitoramento: integração Health Connect e lista.
Fonte: Elaborado pelo autor.

4.4.4 Sistema de gamificação e engajamento
Com o objetivo de reduzir a evasão do uso e estimular o aprendizado contínuo, o aplicativo incorpora estratégias de gamificação (game design elements) diretamente integradas ao fluxo de navegação. A arquitetura desse módulo foi concebida para oferecer feedback imediato ao usuário, especialmente por meio de quizzes interativos que recompensam a conclusão de etapas educacionais, convertendo a jornada de cuidado em uma experiência de progressão mensurável e motivadora.
A lógica de validação, cálculo e persistência do progresso do usuário foi centralizada no serviço progressService.ts, responsável pela comunicação com o banco de dados Cloud Firestore. Diferentemente de abordagens simplificadas baseadas apenas em contadores incrementais, o sistema implementa regras de negócio estruturadas para assegurar a integridade e a consistência dos dados de gamificação. A função canEarnPoints verifica a idempotência das ações, impedindo a atribuição de pontuação duplicada quando um módulo já concluído é reexecutado. Complementarmente, a função calculateScore impõe limite máximo de pontuação por tópico (30 pontos), garantindo que o nível do usuário represente efetivamente seu progresso educacional, e não apenas a repetição mecânica de atividades.
O Código 4 apresenta a implementação da função markModuleComplete, responsável por orquestrar essas validações e registrar a conclusão dos módulos. Destaca-se o uso do operador arrayUnion do Firebase, que possibilita a inserção do identificador do módulo no conjunto de módulos concluídos de forma atômica e eficiente, prevenindo duplicidades e fortalecendo a confiabilidade do mecanismo de persistência do progresso.

Código 4 – Lógica de atribuição de pontos e conclusão de módulos
```typescript
export const markModuleComplete = async (diseaseId: string, moduleIndex: number) => {
  const uid = auth.currentUser?.uid;
  const ref = doc(db, 'users', uid, 'progress', diseaseId);
  const snap = await getDoc(ref);

  const completed = snap.exists() ? snap.data().completedModules : [];
  const currentPoints = snap.exists() ? snap.data().totalPoints : 0;

  if (!canEarnPoints(completed, moduleIndex)) return;

  const newPoints = calculateScore(currentPoints, 10, 30);

  if (snap.exists()) {
    await updateDoc(ref, {
      completedModules: arrayUnion(moduleIndex),
      totalPoints: newPoints,
    });
  } else {
    await setDoc(ref, {
      completedModules: [moduleIndex],
      totalPoints: 10,
    });
  }
};
```

A materialização visual dessa lógica ocorre na interface por meio de barras de progresso dinâmicas, cujo cálculo é realizado pela função auxiliar calculateProgressPercentage. Esses componentes de engajamento traduzem o avanço do usuário em representações visuais imediatas e intuitivas. A Figura 11 exemplifica a integração dessas barras tanto na tela inicial quanto nas telas de detalhamento dos tópicos educativos, permitindo que o usuário acompanhe de forma clara o preenchimento progressivo da barra à medida que avança no percurso de aprendizagem e no manejo educativo de sua condição de saúde.

Figura 11 – Recursos de gamificação do aplicativo.
Fonte: Elaborado pelo autor.

4.4.5 Funcionalidades auxiliares
Com o objetivo de ampliar a experiência do usuário, favorecer a retenção e assegurar conformidade legal e clínica, foram implementados módulos auxiliares voltados à notificação, privacidade e segurança da informação. O sistema de notificações foi desenvolvido com o auxílio da biblioteca expo-notifications, operando em duas frentes complementares: agendamento proativo e feedback reativo.
A estratégia de feedback reativo é acionada no momento do registro dos indicadores de saúde. Nessa etapa, o sistema avalia os valores inseridos pelo usuário e, ao identificar resultados fora das faixas recomendadas — como níveis glicêmicos compatíveis com hipoglicemia ou variações abruptas de peso corporal —, emite alertas imediatos, acompanhados de mensagens de orientação e incentivo. Essa abordagem transforma o simples ato de registro em momento ativo de cuidado, reduzindo a sensação de desamparo frente a resultados adversos e reforçando o vínculo do usuário com o aplicativo.
De forma complementar, o mecanismo de agendamento local de notificações, operando em modo offline, garante o disparo de lembretes diários relacionados à medicação, aferições e rotinas de cuidado, mesmo na ausência de conectividade com a internet. Essa característica é particularmente relevante para assegurar a continuidade do tratamento em contextos de acesso limitado à rede. O Código 5 exemplifica a configuração desse canal de notificações, destacando a definição de prioridade máxima, de modo a assegurar que os alertas sejam devidamente percebidos pelo usuário.

Código 5 – Configuração e agendamento de notificações
```typescript
export const scheduleDailyRegisterReminder = async () => {
  await Notifications.cancelScheduledNotificationAsync('daily-register');
  await Notifications.scheduleNotificationAsync({
    content: {
      title: 'Hora de se cuidar!',
      body: 'Seu futuro agradece os cuidados que você tem hoje. Continue firme!',
      sound: 'default',
      priority: Notifications.AndroidNotificationPriority.HIGH,
    },
    trigger: {
      hour: 19, // Horário estratégico (pós-jantar)
      minute: 0,
      repeats: true,
    },
  });
};
```

Figura 12 – Tela de configurações e exemplos de alertas personalizados.
Fonte: Elaborado pelo autor.

4.5 Padrões e boas práticas adotadas
A garantia da qualidade e a sustentabilidade a longo prazo do software desenvolvido fundamentaram-se na adoção sistemática de boas práticas de engenharia de software, com ênfase na manutenibilidade, escalabilidade e robustez do código-fonte. O processo de desenvolvimento ultrapassou a simples implementação funcional, incorporando princípios de arquitetura limpa e padrões de projeto consolidados na literatura técnica, de modo a assegurar a estabilidade da aplicação em cenários reais de uso e em ambientes de produção.
Um dos pilares metodológicos centrais foi a adoção do TypeScript, que introduz tipagem estática ao ecossistema JavaScript. Em contraste com a flexibilidade inerente à tipagem dinâmica, essa abordagem possibilitou a definição de contratos de interface rigorosos para as entidades do domínio, como usuários, módulos educativos e indicadores de saúde. Sob a perspectiva da confiabilidade, a tipagem estática contribui para a detecção precoce de inconsistências em tempo de compilação, reduzindo a ocorrência de falhas em tempo de execução. Adicionalmente, os tipos e interfaces funcionam como forma de documentação técnica viva, favorecendo a compreensão e a evolução do sistema ao longo do tempo.
Do ponto de vista arquitetural, o projeto seguiu o princípio da separação de preocupações (Separation of Concerns – SoC), promovendo o desacoplamento entre as diferentes responsabilidades do sistema. A aplicação foi estruturada em camadas lógicas bem definidas, nas quais a camada de serviços (services) é responsável exclusivamente pela comunicação com o banco de dados e com APIs externas, enquanto a camada de estado (contexts) atua como fonte única da verdade para os dados globais da aplicação. Essa organização permite que alterações na lógica de persistência ou integração sejam realizadas com impacto mínimo sobre a interface gráfica, favorecendo a testabilidade, a modularização e a evolução incremental do software.
De forma complementar, o desenvolvimento da interface gráfica adotou a metodologia de componentização, aliada ao princípio DRY (Don't Repeat Yourself). Elementos visuais recorrentes foram decompostos em componentes genéricos e reutilizáveis, assegurando consistência visual, redução de redundâncias e aderência ao design system definido para a aplicação. Essa estratégia contribui tanto para a qualidade estética quanto para a eficiência do desenvolvimento e da manutenção do Educacardio+.

5 RESULTADOS E DISCUSSÃO
Este capítulo apresenta os resultados alcançados com o desenvolvimento do aplicativo, abrangendo desde os aspectos técnicos de implementação até a validação de uso conduzida com usuários reais. A análise integra o desempenho funcional da solução com a percepção dos participantes, contemplando critérios de usabilidade, utilidade percebida e engajamento ao longo da interação com o sistema.

5.1 Implementação e disponibilidade técnica
A aplicação foi implementada e disponibilizada em ambiente de produção, com controle de acesso aos usuários participantes dos testes. O processo de publicação incluiu a configuração dos requisitos de segurança e proteção de dados (Data Safety), bem como a integração com a API Health Connect, garantindo que a coleta de métricas de passos, sono e frequência cardíaca ocorresse em conformidade com as diretrizes de privacidade e consentimento estabelecidas.
A adoção da estratégia de distribuição por meio da trilha de Teste Fechado possibilitou a instalação e a execução do aplicativo em uma diversidade de dispositivos reais. Esse procedimento viabilizou a validação da responsividade da interface e da estabilidade da comunicação com os sensores do smartphone, reproduzindo de forma fidedigna as condições da experiência de uso em cenário real.

5.2 Avaliação de uso e percepção dos usuários
A avaliação da ferramenta fundamentou-se, inicialmente, na validação oficial dos processos de revisão da Google Play Store. A aprovação nas trilhas de Teste Interno e Teste Fechado constituiu critério preliminar de qualidade, evidenciando a conformidade do aplicativo com os requisitos de segurança, estabilidade e desempenho estabelecidos pela plataforma.
A partir dessa base validada, foi conduzido um estudo de caso com 12 participantes. A coleta de dados ocorreu por meio de questionário estruturado, aplicado após o período de uso da aplicação. A análise do perfil dos participantes indicou heterogeneidade tanto em relação à faixa etária quanto ao nível de familiaridade com tecnologias digitais. Essa diversidade foi particularmente relevante para avaliar a acessibilidade da interface e a adequação da solução a diferentes perfis de usuários.

Figura 13 – Perfil demográfico e tecnológico dos participantes.
Fonte: Elaborado pelo autor.

No que se refere à usabilidade, a adoção da tipografia Poppins, aliada ao alto contraste entre os elementos visuais, teve como objetivo facilitar a leitura e a interação com a interface. Os resultados obtidos indicam que a maioria dos participantes percebeu a navegação como intuitiva, o que valida o fluxo de interação proposto e sugere adequação das decisões de design às necessidades dos usuários.

Figura 14 – Avaliação da facilidade de navegação e usabilidade.
Fonte: Elaborado pelo autor.

No que diz respeito à utilidade percebida, os resultados indicam que a fragmentação do conteúdo educativo em cards, associada ao uso de vídeos explicativos, favoreceu a assimilação das informações pelos usuários. Além disso, a funcionalidade de checklist de hábitos foi recorrentemente destacada como diferencial prático, por apoiar a organização da rotina de cuidados e incentivar a adoção de comportamentos saudáveis no cotidiano.

Figura 15 – Percepção de valor do conteúdo educativo disponibilizado.
Fonte: Elaborado pelo autor.

Por fim, avaliou-se o engajamento. Observou-se correlação positiva entre os elementos lúdicos (pontos e medalhas) e a intenção de uso contínuo, com a maioria dos respondentes indicando que os feedbacks imediatos tornam o processo mais estimulante.

Figura 16 – Impacto dos elementos de gamificação na motivação de uso.
Fonte: Elaborado pelo autor.

6 CONCLUSÕES
A tecnologia adotada atendeu integralmente aos requisitos estabelecidos para o desenvolvimento da aplicação. A simulação em contexto de uso real evidenciou desempenho satisfatório, indicando que a solução apresenta robustez técnica e completude funcional para a proposta de centralização de dados e educação em saúde. O aplicativo concretiza os objetivos definidos ao integrar ações de prevenção e monitoramento pessoal, configurando-se como base tecnológica sólida, passível de adaptações e evoluções futuras com vistas à implantação em larga escala.
O principal diferencial da proposta reside no empoderamento do indivíduo, ao aproximar o diagnóstico clínico da vivência cotidiana do paciente. Os resultados positivos quanto à aceitação da tecnologia móvel pelos participantes reforçam o potencial de ampliação do alcance da ferramenta, com o propósito de fomentar a literacia em saúde no âmbito comunitário. Nesse sentido, a gamificação e a centralização de informações são empregadas não apenas como recursos técnicos, mas como estratégias de promoção da adesão terapêutica, apoiando o usuário em trajetória contínua de autocuidado e prevenção de complicações.
Entre os benefícios estratégicos validados pelo estudo, destacam-se a democratização do acesso a conteúdos preventivos relacionados ao diabetes e às cardiopatias, contribuindo para o enfrentamento da desinformação em saúde, bem como o incentivo à manutenção de hábitos saudáveis por meio de feedbacks constantes e personalizados. Ademais, a solução favorece a organização pessoal ao centralizar automaticamente indicadores fisiológicos, otimizando o tempo do usuário, que deixa de realizar registros manuais extensivos e pode concentrar-se na compreensão e interpretação de seu estado de saúde. Em síntese, a aplicação demonstrou capacidade de traduzir diretrizes clínicas em ações cotidianas acessíveis, estimulando o engajamento ativo dos usuários no gerenciamento de sua própria condição de saúde.
