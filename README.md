IA Aplicada à Análise das Demonstrações Contábeis

Contexto e Objetivos
Contexto
O objetivo deste projeto foi explorar o uso do NotebookLM como ferramenta de aprendizagem ativa aplicada à análise das demonstrações contábeis. O tema foi escolhido por estar diretamente relacionado à minha formação em Ciências Contábeis e à minha experiência profissional com planilhamento e organização de balanços patrimoniais.

Durante o desenvolvimento do projeto, utilizei diferentes fontes de estudo para compreender como o Balanço Patrimonial e a Demonstração do Resultado do Exercício (DRE) podem ser interpretados de forma integrada, permitindo avaliar a situação patrimonial, financeira e econômica de uma empresa.

Além da compreensão dos conceitos contábeis, o projeto buscou demonstrar como a Inteligência Artificial pode auxiliar na organização do conhecimento, comparação entre fontes, elaboração de resumos e construção de materiais de revisão, tornando o processo de aprendizagem mais eficiente e estruturado.

Objetivos
Este projeto teve como principais objetivos:
- Compreender a estrutura e a finalidade do Balanço Patrimonial e da DRE; 
- Entender a relação entre Ativo, Passivo e Patrimônio Líquido; 
- Estudar a organização das contas patrimoniais; 
- Compreender como analistas financeiros, investidores e instituições financeiras utilizam as demonstrações contábeis; 
- Explorar indicadores financeiros utilizados na análise de empresas; 
- Utilizar o NotebookLM como ferramenta de apoio ao estudo, organização e revisão do conhecimento; 
- Desenvolver um conjunto de prompts reutilizáveis para futuras consultas e revisões.

Curadoria de Fontes

As fontes foram selecionadas buscando combinar materiais acadêmicos e conteúdos didáticos para compreender os fundamentos do Balanço Patrimonial, do Balancete de Verificação, da Demonstração do Resultado do Exercício (DRE) e da análise financeira. A diversidade de formatos permitiu comparar explicações, validar conceitos e utilizar o NotebookLM como ferramenta de aprendizagem ativa baseada em diferentes perspectivas.

https://youtu.be/DH3PD5fGBOk?si=JhDt-WOd7ia5ApX7 | Youtube | Complementar os conceitos apresentados nos materiais escritos por meio de explicações práticas. |
https://www.youtube.com/live/KZjRVsFxkRQ?si=rLAU1xgFtU3Ot1aK | Youtube | Reforçar a interpretação do Balanço Patrimonial e sua aplicação na análise financeira. |
https://github.com/jusgw/notebooklm-analise-demonstracoes-contabeis/blob/main/Balanc%CC%A7o%20Patrimonial.pdf | PDF | Compreender a estrutura, composição e classificação das contas do Balanço Patrimonial. |
https://github.com/jusgw/notebooklm-analise-demonstracoes-contabeis/blob/main/Ana%CC%81lise%20de%20Balanc%CC%A7os.pdf | PDF | Estudar técnicas de análise financeira, indicadores e interpretação das demonstrações contábeis. |
https://github.com/jusgw/notebooklm-analise-demonstracoes-contabeis/blob/main/Balancete%20de%20Verificac%CC%A7a%CC%83o.pdf | PDF | Entender a finalidade do balancete e sua relação com as demonstrações contábeis. |

Engenharia de Prompts
Estratégia utilizada
Ao invés de utilizar perguntas isoladas, os prompts foram organizados em categorias que simulam uma sequência de aprendizagem, iniciando pelos conceitos fundamentais, passando pela estrutura das demonstrações contábeis e evoluindo para aplicações práticas e análise financeira.
Essa organização permitiu utilizar o NotebookLM não apenas como uma ferramenta de resumo, mas como um ambiente de estudo capaz de relacionar informações provenientes de diferentes fontes.

Categoria 1 — Conceituação
Objetivo: Construir uma base conceitual sobre as demonstrações contábeis.
Prompts utilizados:
- Explique o que é um balanço patrimonial para um estudante de Ciências Contábeis. 
- Explique a diferença entre Balanço Patrimonial, Balancete e DRE. 
- Explique a relação entre Ativo, Passivo e Patrimônio Líquido utilizando exemplos. 

Resultado obtido: O NotebookLM apresentou definições claras, exemplos práticos e relacionou corretamente os conceitos fundamentais da contabilidade, facilitando a compreensão da Equação Patrimonial e da função de cada demonstração.

Categoria 2 — Estrutura
Objetivo: Compreender como as contas são organizadas dentro do Balanço Patrimonial.
Prompts utilizados:
•	Organize as principais contas do Ativo Circulante e Não Circulante. 
•	Organize as principais contas do Passivo e Patrimônio Líquido. 
•	Explique por que a ordem das contas no balanço é importante. 

Resultado obtido: As respostas apresentaram a classificação das contas segundo critérios de liquidez e exigibilidade, além de explicar como essa organização facilita a análise financeira e a tomada de decisão.

Categoria 3 — Aplicação
Objetivo: Relacionar os conceitos contábeis ao mercado financeiro.
Prompts utilizados:
- Como um analista financeiro utiliza o balanço patrimonial para avaliar uma empresa? 
- Quais informações do balanço e da DRE são importantes para concessão de crédito? 
- Como um investidor utiliza essas demonstrações? 

Resultado obtido: O NotebookLM explicou como investidores, analistas e instituições financeiras utilizam indicadores de liquidez, estrutura de capital, rentabilidade e endividamento para avaliar empresas.

Categoria 4 — Análise
Objetivo: Desenvolver pensamento crítico sobre interpretação das demonstrações financeiras.
Prompts utilizados:
- O que são ratios de balanço e índices financeiros e como eles podem ser utilizados? 
- Quais são os índices financeiros e quando é importante utilizar cada um deles na análise da situação de uma empresa considerando apenas Ativo, Passivo e Patrimônio Líquido? 
- Quais sinais indicam uma empresa financeiramente saudável?
- Quais sinais podem indicar dificuldades financeiras? 
- Se você fosse treinar um estagiário para analisar um balanço patrimonial, quais seriam os cinco primeiros conceitos que ele deveria dominar? 
- Quais erros são mais comuns ao interpretar um balanço patrimonial? 
- Quais perguntas um analista financeiro faria antes de concluir que uma empresa está saudável?
- Quais contas do balanço merecem maior atenção em uma análise inicial?

Resultado obtido: As respostas apresentaram critérios utilizados por profissionais para avaliar riscos, capacidade de pagamento, solvência e estrutura financeira das organizações.

Cicatrizes (Troubleshooting)
Durante os testes, foram identificados alguns pontos importantes:
- Prompts muito amplos geravam respostas excessivamente longas; 
- Dividir as perguntas em categorias tornou o estudo mais organizado; 
- Prompts contextualizados produziram respostas mais completas do que perguntas genéricas; 
- Solicitar exemplos práticos facilitou significativamente a compreensão dos conceitos; 
- Utilizar exclusivamente as fontes anexadas aumentou a confiabilidade das respostas e permitiu rastrear as referências utilizadas pelo NotebookLM. 

Miniguia de Estudo
O Balanço Patrimonial representa a posição patrimonial e financeira da empresa em determinada data, enquanto a DRE demonstra o desempenho econômico ao longo de um período. A interpretação conjunta dessas demonstrações permite avaliar liquidez, endividamento, rentabilidade e capacidade de geração de resultados, fornecendo informações essenciais para gestores, investidores e instituições financeiras.

Os ativos representam os bens e direitos da empresa; os passivos correspondem às obrigações perante terceiros; e o patrimônio líquido representa os recursos próprios dos proprietários. A relação entre esses elementos é expressa pela Equação Fundamental da Contabilidade: Ativo = Passivo + Patrimônio Líquido

Além da compreensão das demonstrações, o estudo evidenciou a importância dos indicadores financeiros, da análise horizontal e vertical e da integração entre diferentes informações para uma avaliação financeira consistente.

Glossário
Ativo: Bens e direitos controlados pela empresa.
Passivo: Obrigações assumidas perante terceiros.
Patrimônio Líquido: Recursos próprios pertencentes aos sócios.
Balanço Patrimonial: Demonstração da posição patrimonial em uma data específica.
DRE: Demonstração que evidencia o resultado econômico de um período.
Liquidez: Capacidade da empresa de cumprir suas obrigações financeiras.
ROE: Indicador de retorno sobre o patrimônio líquido.
ROA: Indicador de retorno sobre os ativos.
Endividamento: Grau de utilização de capital de terceiros.

Prompts reutilizáveis
- Explique determinado conceito considerando apenas as fontes anexadas. 
- Compare como as diferentes fontes abordam determinado tema. 
- Relacione o Balanço Patrimonial com a DRE utilizando exemplos. 
- Identifique indicadores financeiros aplicáveis ao cenário apresentado. 
- Explique quais decisões podem ser tomadas com base nas demonstrações financeiras. 
- Identifique conceitos importantes que ainda não foram abordados nas respostas anteriores.
