# Desafio-do-sem-foro-arduino
Projeto educacional de Semáforo Inteligente para Segurança Escolar utilizando Arduino e Tinkercad, integrando Ciências, Tecnologia e Educação para o Trânsito na investigação e solução de problemas relacionados à mobilidade e à segurança da comunidade escolar.
PROPOSTA DE ATIVIDADE PEDAGÓGICA INTERDISCIPLINAR
Semáforo inteligente:
Eletrônica, programação e sustentabilidade
Plano de aula para a Educação Básica
1. Identificação
Tema da aula	Semáforo inteligente: funcionamento de circuitos eletrônicos, lógica de programação e reaproveitamento de materiais.
Público-alvo	8º ou 9º ano do Ensino Fundamental – anos finais (adaptável ao Ensino Médio).
Áreas envolvidas	Ciências, Matemática, Tecnologia/Computação, Geografia e Educação Ambiental.
Duração	2 aulas de 50 minutos (100 minutos no total).
Organização	Turmas em grupos de 3 a 5 estudantes.
2. Objetivos de aprendizagem
•	Compreender, em nível introdutório, como um circuito elétrico fechado permite o funcionamento de componentes eletrônicos.
•	Identificar a função de Arduino, protoboard, LEDs, resistores, fios e fonte de alimentação em uma simulação.
•	Interpretar uma sequência lógica de programação e relacioná-la aos estados do semáforo.
•	Observar e registrar a duração dos sinais, organizar dados e comparar intervalos de tempo.
•	Reconhecer a presença de componentes eletrônicos em equipamentos descartados e discutir impactos do lixo eletrônico.
•	Propor formas seguras de reaproveitamento não funcional ou cenográfico de materiais, distinguindo reutilização de reciclagem.
•	Trabalhar colaborativamente, formular hipóteses, testar ideias e comunicar conclusões.
3. Conteúdos e conceitos trabalhados
•	Ciências/Física: corrente elétrica (noção introdutória), circuito aberto e fechado, condutores e isolantes, tensão, resistência e função do resistor.
•	Tecnologia/Computação: pensamento computacional, algoritmo, sequência, entrada/saída, programação por blocos ou texto e simulação.
•	Matemática: contagem, medidas de tempo em segundos, tabelas, comparação de durações e representação de dados.
•	Geografia/Educação Ambiental: consumo de equipamentos, ciclo de vida dos produtos, descarte correto, logística reversa e impactos do lixo eletrônico.
•	Linguagens: leitura de esquemas, produção de registro explicativo, argumentação e apresentação oral.
4. Materiais e recursos necessários
Recursos digitais e de sala
•	Computadores ou tablets com acesso à internet; projetor ou tela para demonstração.
•	Acesso ao Tinkercad Circuits (conta gratuita pode ser necessária para copiar e editar o projeto; a visualização e a simulação do projeto público podem estar disponíveis sem cópia).
•	Quadro, folhas de registro, lápis/canetas e cronômetro.
Materiais representados no circuito simulado
•	Arduino Uno, protoboard, três LEDs (vermelho, amarelo e verde), três resistores adequados, fios jumper e computador.
•	O circuito público indicado utiliza três LEDs ligados a pinos digitais do Arduino e demonstra uma sequência de sinalização. Os estudantes deverão observar a montagem e a lógica antes de propor alterações.
Materiais reaproveitados de lixo eletrônico (para observação e planejamento)
•	Placas eletrônicas já separadas e previamente verificadas pelo professor, sem alimentação elétrica, para observação de trilhas e identificação visual de componentes.
•	Cabos USB ou de rede inutilizados, conectores, teclas de teclado, carcaças plásticas, botões e pequenas peças de equipamentos descartados.
•	LEDs ou resistores retirados previamente por profissional capacitado, apenas para observação/classificação, sem ligação elétrica na atividade.
•	Caixas de papelão, embalagens limpas e retalhos de plástico para esboçar uma estrutura externa cenográfica para o semáforo.
Orientação de segurança: os materiais de descarte devem ser selecionados e preparados previamente pelo professor ou por equipe responsável. Não solicitar que estudantes abram fontes de alimentação, monitores/televisores, baterias ou equipamentos desconhecidos. Não utilizar pilhas/baterias, componentes danificados, placas energizadas ou peças com risco de corte. A atividade com e-lixo é de observação, classificação e planejamento; não exige desmontagem nem energização.
5. Link para o circuito simulado no Tinkercad
Projeto: “4. Projeto - Semáforo” – Arduino Uno com LEDs vermelho, amarelo e verde.
Link direto: https://www.tinkercad.com/things/1HJZuqNrooJ/editel?returnTo=%2Fdashboard 
Página de referência e descrição do projeto: https://www.escalada.dev/modelos/robotica/circuitos-no-tinkercad/
Como utilizar: abrir o link, localizar o botão de iniciar a simulação e observar a alternância dos LEDs. O material de referência descreve a sequência do exemplo como amarelo, vermelho e verde, com intervalos programados; o professor deve conferir a ordem e os tempos diretamente na simulação antes da aula. Para editar o projeto, pode ser necessário entrar no Tinkercad e criar uma cópia.
 <img width="1604" height="819" alt="image" src="https://github.com/user-attachments/assets/ef4ef0fd-2c89-4333-94cd-9f085cdf0cad" />

6. Desenvolvimento da atividade
Aula 1 – Investigação do circuito e da lógica (50 minutos)
1.	Acolhida e problematização (8 min). Apresentar a pergunta: “Como um semáforo consegue controlar a sinalização usando eletrônica e programação?” Conversar brevemente sobre segurança viária, função das cores e situações em que a sinalização é importante.
2.	Levantamento de hipóteses (7 min). Em pequenos grupos, os estudantes desenham ou descrevem o que imaginam existir dentro de um semáforo eletrônico. O professor registra ideias sobre energia, fios, lâmpadas/LEDs e controle.
3.	Exploração guiada no Tinkercad (20 min). Projetar o circuito e, em seguida, permitir que os grupos abram o link. Os alunos identificam Arduino, protoboard, LEDs, resistores e conexões; predizem qual LED acenderá primeiro; iniciam a simulação e anotam a sequência e os tempos aproximados. O professor explica que o LED é um componente emissor de luz e que o resistor limita a corrente no circuito.
4.	Leitura do algoritmo (10 min). Com apoio do professor, observar no código as instruções de configuração dos pinos, acionamento dos LEDs e pausas temporizadas. Relacionar “ligado/desligado” aos estados lógicos e construir um fluxograma simples.
5.	Síntese (5 min). Cada grupo registra uma descoberta e uma dúvida sobre o funcionamento do circuito.
Aula 2 – Lixo eletrônico, reaproveitamento e proposta de melhoria (50 minutos)
6.	Observação dos materiais (10 min). O professor apresenta os materiais reaproveitados previamente selecionados. Os grupos observam sem desmontar ou energizar, agrupam por tipo (cabos, conectores, placas, carcaças, botões, componentes) e levantam hipóteses sobre a função original de cada item.
7.	Conexão entre circuito e e-lixo (10 min). Os alunos relacionam, quando possível, os componentes observados aos elementos do circuito simulado: LEDs, resistores, fios, conectores e placas de controle. Diferenciam o uso funcional (que exigiria testes técnicos e condições de segurança) do reaproveitamento cenográfico ou didático.
8.	Desafio de projeto (20 min). Cada grupo elabora um esboço de um semáforo educativo ou de uma maquete de cruzamento. Deve indicar quais materiais descartados poderiam ser reutilizados na estrutura externa (por exemplo, carcaça plástica como corpo, teclas como marcadores, cabos sem uso como representação visual de fiação, caixa de papelão como suporte) e quais componentes eletrônicos seriam apenas identificados/representados. A lógica luminosa permanece demonstrada pelo Tinkercad; não é necessário construir o protótipo.
9.	Socialização e fechamento (10 min). Os grupos apresentam o esboço, explicam a relação entre o circuito e a proposta de reaproveitamento e apontam cuidados para o descarte correto do que não puder ser reutilizado.
7. Integração dos materiais reaproveitados
Os materiais de lixo eletrônico cumprem três funções pedagógicas, sem serem conectados ao circuito:
•	Reconhecimento e classificação: observar placas, fios, conectores, botões e carcaças para relacionar forma, material e possível função.
•	Reutilização criativa: planejar o uso de carcaças, teclas, cabos e embalagens como elementos de uma maquete ou suporte visual do semáforo.
•	Educação ambiental: discutir por que equipamentos eletrônicos não devem ser descartados no lixo comum e pesquisar, com orientação do professor, pontos de coleta ou sistemas locais de logística reversa.
8. Estratégias de avaliação
A avaliação será processual, formativa e baseada em evidências produzidas durante as duas aulas:
•	Diagnóstica: participação na conversa inicial e qualidade das hipóteses sobre o funcionamento do semáforo.
•	Observação: identificação correta dos componentes e compreensão básica da sequência de acionamento dos LEDs.
•	Registro do grupo: tabela com sequência de cores/tempos, desenho ou fluxograma da lógica e breve explicação do papel do Arduino e dos resistores.
•	Produto de planejamento: esboço da maquete com indicação dos materiais reaproveitados e justificativa de uso seguro e ambientalmente responsável.
•	Apresentação oral: clareza, colaboração, uso de conceitos e capacidade de relacionar tecnologia e sustentabilidade.
Critérios sugeridos (0–2 pontos cada): compreensão do circuito; interpretação da sequência lógica; identificação e classificação dos materiais; pertinência do reaproveitamento proposto; participação e comunicação. Total: 10 pontos, podendo ser convertido em conceito.
9. Adequações e possibilidades de ampliação
•	Para turmas com pouca experiência em programação, utilizar blocos visuais ou apresentar o código já pronto, concentrando a investigação na sequência e na função dos componentes.
•	Para aprofundamento, solicitar que os estudantes proponham uma nova temporização, comparem os intervalos em tabela ou incluam um botão de travessia em uma versão editada do circuito.
•	Em turmas do Ensino Médio, ampliar a discussão para cálculo simplificado de resistência/corrente, consumo energético, obsolescência programada e logística reversa.
10. Referências e recursos
•	Autodesk Tinkercad – Circuits. https://www.tinkercad.com/circuits
•	Escalada.dev. Circuitos no Tinkercad – projeto público “4. Projeto - Semáforo”. https://www.escalada.dev/modelos/robotica/circuitos-no-tinkercad/
•	Lei nº 12.305/2010 – Política Nacional de Resíduos Sólidos (referência para discussão sobre gestão e destinação de resíduos). https://www.planalto.gov.br/ccivil_03/_ato2007-2010/2010/lei/l12305.htm
