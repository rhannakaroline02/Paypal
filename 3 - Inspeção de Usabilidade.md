# 3 - Inspeção de Usabilidade
### 3.1 - Planejamento
- A inspeção de usabilidade é um processo sistemático que avalia a qualidade de interação do usuário com um sistema.O processo é organizado em etapas claras, desde o planejamento até a análise e relatório, para garantir que todos os aspectos do sistema sejam avaliados e melhorados conforme necessário.
  
| **Etapa**    | **Descrição**                                                                                           |
|--------------|---------------------------------------------------------------------------------------------------------|
| Planejamento | Definir os objetivos da inspeção, selecionar os avaliadores  e planejar o processo. |
| Execução     | Conduzir a avaliação usando técnicas como Avaliação Heurística e Teste de Usabilidade. Ferramentas como protótipos ou sistemas reais são utilizados para simular cenários de uso. |
| Análise      | Coletar os dados, identificar os problemas de usabilidade encontrados, e classificá-los usando heurísticas e severidade. |
| Resultados    | Compilar um relatório detalhado com todas as descobertas, incluindo sugestões de melhoria para os problemas identificados. |


- As heurísticas de Nielsen são utilizadas para identificar problemas de usabilidade baseados em princípios gerais de design. Elas fornecem um framework para avaliar a eficácia do design do sistema.
- A classificação de severidade ajuda a priorizar os problemas encontrados durante a inspeção. Isso garante que os problemas mais críticos sejam resolvidos primeiro, melhorando significativamente a experiência do usuário.
### 3.2 - Detecção
Descrição: Cada inspetor realiza de forma isolada essa etapa, que envolve identificar potenciais problemas de usabilidade nas interações escolhidas.

**Inspetor**: **A1**
| ID | Descrição do problema | Heurística Violada | Severidade | Carga Horária |
|----|-----------------------|--------------------|------------|---------------|
| 1  |  Quando o usuário tenta se cadastrar no PayPal e pesquisa seu endereço, o sistema não fornece um feedback correto ou útil, resultando em dificuldades para completar o cadastro. |  H10 - Ajuda e documentação. | 4  Catastrófico |  40 min |
| 2  | Usuários ficam perdidos ao entrar no aplicativo após se cadastrarem, pois a interface é diferente de outros aplicativos bancários, dificultando a navegação e o uso eficiente. | H4 - Consistência e padrões. | 3 Grande|  1 horas |
| 3  |  As opções de pagamento são complexas, e poderia ser mais fácil se houvesse uma opção para pagar com Pix. | H7 - Flexibilidade e eficiência de uso. | 3 Grande| 40 min |
| 4  | Quando solicitado um pagamento, a opção para visualizar o histórico de pagamentos pendentes é difícil de encontrar, e não mostra se a mensagem foi vista, causando confusão e frustração. | H1 - Visibilidade do status do sistema. | 3 Grande | 40 min |
| 5  | Não fornecer feedback claro sobre o status de transações ou pagamentos em andamento, deixando os usuários incertos sobre se a transação foi bem-sucedida. | H1 - Visibilidade do status do sistema. | 4 Catastrófico |  30 min |
| 6  | Usa muitos termos técnicos e jargões financeiros que podem não ser familiares a todos os usuários, especialmente aqueles que não estão acostumados a transações online. | H2 - Compatibilidade entre o sistema e o mundo real. | 3 Grande | 40 min |
| 7  | Em alguns casos, pode ser difícil desfazer uma transação ou cancelar um pagamento, especialmente se a transação já estiver processada. | H3 - Controle e liberdade do usuário. | 4 Catastrófico | 20 min |
| 8  | Exigir que os usuários lembrem de informações específicas, como números de referência ou detalhes de transações passadas, sem fornecer uma maneira fácil de recuperar essas informações. | H6 - Reconhecimento em vez de memorização. | 4 Catastrófico | 4 horas |
| 9  | Não oferece atalhos ou opções de personalização suficientes para tornar o processo de pagamento mais rápido e eficiente. |  H7 - Flexibilidade e eficiência de uso. | 3 Grande |  40 min |
| 10  | Algumas partes são visualmente sobrecarregadas com informações e opções desnecessárias, dificultando a navegação. | H8 - Design estético e minimalista. |  3 Grande | 20 min |
| 11  | Embora o PayPal ofereça suporte, às vezes a documentação e os guias de ajuda podem ser difíceis de encontrar ou entender, especialmente para novos usuários. | H10 - Ajuda e documentação. | 3 Grande|  1 hora |
| 12  | As mensagens de erro podem ser vagas e não fornecer instruções claras sobre como resolver problemas específicos, deixando os usuários frustrados. | H5 - Prevenção de erros. |  4 Catastrófico|  30 min |

**Inspetor**: **A2**

| ID | Descrição do problema | Heurística Violada | Severidade | Carga Horária |
|----|-----------------------|--------------------|------------|---------------|
| 1  |  Dificuldade em receber o código de autenticação pelo celular.	O sistema de verificação de dois fatores via SMS apresenta falhas recorrentes como atrasos ou a não chegada do código ao dispositivo do usuário. Isso impede o login no app e compromete a segurança e usabilidade. | H9 - Ajuda para usuário identificar, diagnosticar e corrigir erros. | 4 Catastrófico| 1 hora
| 2  | Interface confusa na navegação entre seções	A interface não deixa claro em qual seção o usuário está, com ícones e menus mal diferenciados. Isso causa confusão ao navegar entre áreas como "Carteira" e "Atividade". | H1 - Visibilidade do Status do Sistema.| 3 Grande| 40 min |
| 3  | Lentidão no carregamento de páginas.	O aplicativo apresenta demora nas seções, como "Enviar Dinheiro". Isso pode criar frustração e insegurança em relação à confiabilidade do sistema. | H4 - Consistência e Padrões. | 4 Catastrófico| 1 hora |
| 4  | Campos de formulário não claramente identificados.	Informações dos campos de formulários não são claros, levando a erros no preenchimento e frustração ao inserir informações pessoais. | H6 - Reconhecimento em vez de memorização. | 3 Grande| 30 min |
| 5  | Falta de feedback após realizar uma transação.	O usuário não recebe confirmação visual clara após completar uma transação, o que causa incerteza e pode levar a erros ou duplicações de pagamento. | H1 - Visibilidade do Status do Sistema. | 4 Catastrófico | 40 min |
| 6  | Botão de confirmação posicionado de forma não intuitiva.	O botão de confirmação de transações está mal localizado na interface, forçando o usuário a procurar ou rolar a tela. | H3 - Controle e liberdade do usuário.| 4 Catastrófico| 40 min |
| 7  | Layout não otimizado para dispositivos móveis. O layout não se ajusta adequadamente a diferentes tamanhos de tela, o que força o usuário a rolar ou redimensionar para visualizar elementos importantes. | H8 - Design estético e minimalista. | 4 Catastrófico| 1h |

**Inspetor**: **A3**

| ID | Descrição do problema | Heurística Violada | Severidade | Carga Horária |
|----|-----------------------|--------------------|------------|---------------|
| 1  | No cadastro o Paypal não valida o email corretamente, assim dificultando o acesso para validação do email. | H5 - Prevenção de erros | 4 Catastrófico| 1 Hora | 
| 2  | O aplicativo as vezes apresenta dificulades em sua interfacede usuário, como dificuldade em navegação, dificuldades em encontrar informações. | H1 - Visibilidade Do Status do sitema | 4 Catastrófico| 40 min |
| 3  | O aplicativo apresenta dificulades em encontrar informações relevantes e falta de feedback depois de realizar transações. | H5 - Prevenção de Erros | 4 Catastrófico| 30 min |
| 4  | Dficuldade em navegar pelo aplicativo devido muitas informações, causando em confusão durante execuções de tarefas simples, como enviar ou receber dinheiro. | H6 - Reconhecimento em vez de memorização | 3 Grande| 40 min | 
| 5  | Tem mensagens de erro durante o preeenchimentos de dados são vagas e não indicam de forma correta o que precisa ser corrigido. | H5 - Prevenção de erros | 4 Catastrófico| 30 min |
| 6  | Configurações de segurança e privacidade estão localizadas em um submenu difícil de acessar, que sifculta a personalização.  | H3 - Controle do usuário e liberdade. | 3 Grande| 35 min |



**Inspetor**: **A4**

| ID | Descrição do problema | Heurística Violada | Severidade | Carga Horária |
|----|-----------------------|--------------------|------------|---------------|
| 1  | A interface principal(home) possui pouca ou nenhuma informação que possa ajudar o usuário a se localizar, bem como encontrar de forma rápida e intuitiva as outras funcionalidades fornecidas pelo aplicativo. | H7 - Eficiência e flexibilidade de uso | 2 Leve| 20 min |               
| 2  | A forma de busca por contato, seja para efetuar um pagamento ou fazer uma cobrança, não é eficiente. | H7 - Eficiência e flexibilidade de uso | 3 Grande| 30 min |       
| 3  | A todo momento fica pedindo confirmação de segurança, o que acaba frustrando os usuário por fazer processos repetitivos e desnecessarios. | H10 - Ajuda e documentação | 3 Grande| 30 min |      
| 4  | Algumas funcionalidades não estão disponiveis no Brasil tornando a experiencia do usuario frustrante. | H2 - Compatibilidade entre o sistema e o mundo real | 3 Grande| 20 min |         
| 5  | Mensagens de erro muito vagas, não esclarecem de forma objetiva e clara a causa do erro, deixando o usuario com duvida e sentimento de culpa. | H5 - Prevenção de erros | 3 Grande| 1h |      
| 6  | Encontrar a função que mostra as atividade da conta é um tanto difil, não existem atalhos, é necessário seguir varias etapas, isso se torna algo cansativo para os usuários. | H1 - Visibilidade do Status do Sistema | 3 Grande| 30 min |    
| 7  | As interfaces não seguem um padrão, muda o layout de uma para outra dificultando a memorização de ações executadas. | H4 - Consistência e Padronização | 2 Leve| 30 min |     


**Inspetor**: **A5**


| ID | Descrição problema | Heurística Violada | Severidade | Carga Horária | 
|----|-----------------------|--------------------|------------|---------------|
| 1  |Há uma certa difificulade para o aplicativo mostrar que o pagamento foi concluido | H1-Visibilidade do sistema | 3 Grande| 0:25 |
| 2  |Ao enviar dinheiro por engano é dificultoso encontar uma opçao clara para corrigir/cancelar a transação| H3-controle e liberdade do usúario | 4 Catastrófico| 0:42 |
| 3  |Ao fazer transferências o aplicativo não da a opção do usúario verificar pela segunda vez se o destinatário está correto|H5- Prevenção de erros | 3 Grande|00:20|
| 4  | Os ícones que remetem a "pagamentos" no aplicativos são diferentes dos que já estamos acostumados que dificulta a parte intuitiva do usúario|H6- Reconhecer ao invés de relembrar| 1 Cosmético |00:5 |
| 5  | Apesar de minimalista em seu menu a tela inicial que aparece após fazer login no aplicativo transmite o aspecto de bagunçado no qual não transmite o profissionalismo que deveria|H8- Estética e desing minimalista| 3 Grande|00:10 |


**Inspetor**: **A6**

| ID | Descrição do problema | Heurística Violada | Severidade | Carga Horária |
|----|-----------------------|--------------------|------------|---------------|
|  1 | Na tela inicial contem informações irrelevantes e tela pouca intuitiva. | H8- Estética e design minimalista | 1 cosmético| 15 min  | 
|  2 | Na aba “informações pessoais” há uma mistura de idioma, dificultando o entedimento do usuário. | H2- Compatibilidade do sistema com o mundo real |  1 Cosmético| 00:15 |
|  3 | Ao clicar em “pagamentos” e depois na aba “doar” há muita informação desnecessária, confundindo o usuário. | H8- Estética e design minimalista |  1 Cosmético| 00:18 |
|  4 | Problemas de acessibilidade, aplicativo não otimizado para todos os usuários. | H10- Ajuda e documentação |  2 Leve| 00:20 |
|  5 | Limitação de idioma, a falta da opção de escolher um idioma, limiatando alguns usuários a usar o aplicativo. | H10- Ajuda e documentação |  2 Leve| 00:20 |
|  6 | Falta da opção de voltar a um estado anterior. | H3- Controle e liberdade do usuário |  1 Cosmético| 00:10 |
|  7 | Opção de "menu" e "perfil" pouco visível. | H8 - Estática e design minimalista | 1 Cosmético| 00:05 | 



## 3.3 Coleção 
Agrupamento de todas os problemas identificados e eliminaça o de duplicatas. 

| ID | Inspetores | Descrição do problema | Heuristicas violadas  | Severidade |
|----|-----------------------|--------------------|------------|---------------|
| 1 |A1| Quando o usuário tenta se cadastrar no PayPal e pesquisa seu endereço, o sistema não fornece um feedback correto ou útil, resultando em dificuldades para completar o cadastro.| H4-Ajuda e documentação | 4 Catastrófico| 
|2| A1, A2, A3 | Usuários ficam perdidos ao entrar no aplicativo após se cadastrarem, pois a interface é diferente de outros aplicativos bancários, dificultando a navegação e o uso eficiente. A confusão é agravada pela falta de clareza sobre a seção em que o usuário está, devido a ícones e menus mal diferenciados| H4-Consistência e padronização| 3 Grande|
|3| A1, A1, A6| As opções de pagamento são complexas, e poderia ser mais fácil se houvesse uma opção para pagar com Pix pois não oferece atalhos ou opções de personalização suficientes para tornar o processo de pagamento mais rápido e eficiente aoclicar em “pagamentos” e depois na aba “doar” há muita informação desnecessária, confundindo o usuário.  |  H7- Eficiência e flexibilidade de uso. | 3 Grande|
|4| A1, A2, A3, A5 | A opção para visualizar o histórico de pagamentos pendentes é difícil de encontrar, e o aplicativo não fornece feedback claro sobre o status das transações, causando confusão e frustração, o que gera incertezas e pode levar a erros ou duplicações de pagamento.|H5- Prevenção de erros | 4 Catastrófico|
|5|A1,A2| Usa muitos termos técnicos e jargões financeiros que podem não ser familiares a todos os usuários, especialmente aqueles que não estão acostumados a transações online além do campo de formulário não ser claramente identificado as	informações dos campos de formulários não são claras, levando a erros no preenchimento e frustração ao inserir informações pessoais. | H2-Correspondência entre o sistema e o mundo real. | 3 Grande|
|6| A1, A5 | Em alguns casos, pode ser difícil desfazer uma transação ou cancelar um pagamento, especialmente se a transação já estiver processada. Além disso, ao fazer transferências, o aplicativo não oferece ao usuário a opção de verificar novamente se o destinatário está correto|H5- Prevenção de erros| 4 Catastrófico|
|7| A1| Exigir que os usuários lembrem de informações específicas, como números de referência ou detalhes de transações passadas, sem fornecer uma maneira fácil de recuperar essas informações. |H6-Reconhecimento ao em vez de relembrar. | 4 Catastrófico|
|8| A1, A4, A5, A6| Algumas partes do aplicativo são visualmente sobrecarregadas com informações e opções desnecessárias, dificultando a navegação. Apesar de um menu minimalista, a tela inicial que aparece após o login transmite uma sensação de desordem, não refletindo o profissionalismo esperado e acaba comprometendo a experiência do usuário| H8-Estética e design minimalista| 2 Leve|
|9| A1| Embora o PayPal ofereça suporte, às vezes a documentação e os guias de ajuda podem ser difíceis de encontrar ou entender, especialmente para novos usuários. | H10-Ajuda e documentação. | 3 Grande|
|10| A1, A3, A4 | As mensagens de erro no aplicativo são vagas e não oferecem instruções claras sobre como resolver problemas específicos, o que deixa os usuários frustrados. Durante o preenchimento de dados, essas mensagens não indicam corretamente o que precisa ser corrigido, gerando dúvidas e um sentimento de culpa nos usuários, que não conseguem entender de forma objetiva a causa do erro|H5-Prevenção de erros| 2 Leve| 
|11| A2, A3 | Os usuários enfrentam dificuldades em receber o código de autenticação pelo celular, já que o sistema de verificação de dois fatores via SMS apresenta falhas recorrentes, como atrasos ou a não chegada do código, o que impede o login no app e compromete a segurança e usabilidade. Além disso, o PayPal não valida corretamente o email durante o cadastro, dificultando o acesso à validação necessária.|H9-Ajuda aos usuários a reconhecerem, diagnosticar e corrigir erros| 2 Leve| 
|12| A2| Lentidão no carregamento de páginas.	O aplicativo apresenta demora nas seções, como "Enviar Dinheiro". Isso pode criar frustração e insegurança em relação à confiabilidade do sistema. | H7-Flexibilidade e eficiencia de uso| 3 Grande|
|13| A2|  Botão de confirmação posicionado de forma não intuitiva.	O botão de confirmação de transações está mal localizado na interface, forçando o usuário a procurar ou rolar a tela. | H4- Consistencia e padrão | 2 Leve|
|14| A2| Layout não otimizado para dispositivos móveis. O layout não se ajusta adequadamente a diferentes tamanhos de tela, o que força o usuário a rolar ou redimensionar para visualizar elementos importantes. |H8- Estética e desing minimalista | 2 Leve|
|15| A3|  Configurações de segurança e privacidade estão localizadas em um submenu difícil de acessar, que difculta a personalização.  | H3-Controle do usuário e liberdade. | 3 Grande|
|16| A4|  A forma de busca por contato, seja para efetuar um pagamento ou fazer uma cobrança, não é eficiente. | H7 - Eficiência e flexibilidade de uso | 3 Grande|
|17| A4| A todo momento fica pedindo confirmação de segurança, o que acaba frustrando os usuário por fazer processos repetitivos e desnecessarios. | H10 - Ajuda e documentação | 3 Grande|
|18| A4| Algumas funcionalidades não estão disponiveis no Brasil tornando a experiencia do usuario de outro país frustrante. | H2 - Compatibilidade entre o sistema e o mundo real | 3 Grande| 
|19| A4| Encontrar a função que mostra as atividade da conta é um tanto difil, não existem atalhos, é necessário seguir varias etapas, isso se torna algo cansativo para os usuários. | H1 - Visibilidade do Status do Sistema | 3 Grande|
|20| A4| As interfaces não seguem um padrão, muda o layout de uma para outra dificultando a memorização de ações executadas. | H4 - Consistência e Padronização | 2 Leve|
|21| A5| Os ícones que remetem a "pagamentos" no aplicativos são diferentes dos que já estamos acostumados que dificulta a parte intuitiva do usúario|H6- Reconhecer ao invés de relembrar| 1 Cosmético|
|22| A6| Na aba “informações pessoais” há uma mistura de idioma, dificultando o entedimento do usuário. | H2- Compatibilidade do sistema com o mundo real |  1 Cosmético|
| 23| A6| Problemas de acessibilidade, aplicativo não otimizado para todos os usuários, a opção de "menu" e "perfil" é pouco visível. | H10- Ajuda e documentação |  2 Leve|
| 24| A6| Limitação de idioma, a falta da opção de escolher um idioma, limiatando alguns usuários a usar o aplicativo. | H10- Ajuda e documentação |  2 Leve|
| 25| A6 | Falta da opção de voltar a um estado anterior. | H3- Controle e liberdade do usuário |  1 Cosmético|
### 3.4 – Discriminação
| ID | Descrição do problema | Classificação |
|----|-----------------------|-----------------|
| 1 | Quando o usuário tenta se cadastrar no PayPal e pesquisa seu endereço, o sistema não fornece um feedback correto ou útil, resultando em dificuldades para completar o cadastro.| Falso-Positivo   |
| 2 | Usuários ficam perdidos ao entrar no aplicativo após se cadastrarem, pois a interface é diferente de outros aplicativos bancários, dificultando a navegação e o uso eficiente. A confusão é agravada pela falta de clareza sobre a seção em que o usuário está, devido a ícones e menus mal diferenciados | Real |
| 3 | As opções de pagamento são complexas, e poderia ser mais fácil se houvesse uma opção para pagar com Pix pois não oferece atalhos ou opções de personalização suficientes para tornar o processo de pagamento mais rápido e eficiente aoclicar em “pagamentos” e depois na aba “doar” há muita informação desnecessária, confundindo o usuário. | Real |
| 4 | A opção para visualizar o histórico de pagamentos pendentes é difícil de encontrar, e o aplicativo não fornece feedback claro sobre o status das transações, causando confusão e frustração, o que gera incertezas e pode levar a erros ou duplicações de pagamento. | Falso-Positivo |
| 5 | Usa muitos termos técnicos e jargões financeiros que podem não ser familiares a todos os usuários, especialmente aqueles que não estão acostumados a transações online além do campo de formulário não ser claramente identificado as informações dos campos de formulários não são claras, levando a erros no preenchimento e frustração ao inserir informações pessoais. | Falso-Positivo |
| 6 | Em alguns casos, pode ser difícil desfazer uma transação ou cancelar um pagamento, especialmente se a transação já estiver processada. Além disso, ao fazer transferências, o aplicativo não oferece ao usuário a opção de verificar novamente se o destinatário está correto | Real |
| 7 | Exigir que os usuários lembrem de informações específicas, como números de referência ou detalhes de transações passadas, sem fornecer uma maneira fácil de recuperar essas informações. | Real |
| 8 | Algumas partes do aplicativo são visualmente sobrecarregadas com informações e opções desnecessárias, dificultando a navegação. Apesar de um menu minimalista, a tela inicial que aparece após o login transmite uma sensação de desordem, não refletindo o profissionalismo esperado e acaba comprometendo a experiência do usuário | Real |
| 9 | Embora o PayPal ofereça suporte, às vezes a documentação e os guias de ajuda podem ser difíceis de encontrar ou entender, especialmente para novos usuários. | Falso-Positivo |
| 10 | As mensagens de erro no aplicativo são vagas e não oferecem instruções claras sobre como resolver problemas específicos, o que deixa os usuários frustrados. Durante o preenchimento de dados, essas mensagens não indicam corretamente o que precisa ser corrigido, gerando dúvidas e um sentimento de culpa nos usuários, que não conseguem entender de forma objetiva a causa do erro. | Real |
| 11 | Os usuários enfrentam dificuldades em receber o código de autenticação pelo celular, já que o sistema de verificação de dois fatores via SMS apresenta falhas recorrentes, como atrasos ou a não chegada do código, o que impede o login no app e compromete a segurança e usabilidade. Além disso, o PayPal não valida corretamente o email durante o cadastro, dificultando o acesso à validação necessária. | Falso-Positivo |
| 12 | Lentidão no carregamento de páginas. O aplicativo apresenta demora nas seções, como "Enviar Dinheiro". Isso pode criar frustração e insegurança em relação à confiabilidade do sistema. | Real |
| 13 | Botão de confirmação posicionado de forma não intuitiva. O botão de confirmação de transações está mal localizado na interface, forçando o usuário a procurar ou rolar a tela. | Falso-Positivo |
| 14 | Layout não otimizado para dispositivos móveis. O layout não se ajusta adequadamente a diferentes tamanhos de tela, o que força o usuário a rolar ou redimensionar para visualizar elementos importantes | Falso-Positivo |
| 15 | Configurações de segurança e privacidade estão localizadas em um submenu difícil de acessar, que difculta a personalização. | Falso-Positivo |
| 16 | A forma de busca por contato, seja para efetuar um pagamento ou fazer uma cobrança, não é eficiente. | Real |
| 17 | A todo momento fica pedindo confirmação de segurança, o que acaba frustrando os usuário por fazer processos repetitivos e desnecessarios. | Falso-Positivo |
| 18 | Algumas funcionalidades não estão disponiveis no Brasil tornando a experiencia do usuario de outro país frustrante. | Falso-Positivo |
| 19 | Encontrar a função que mostra as atividade da conta é um tanto difil, não existem atalhos, é necessário seguir varias etapas, isso se torna algo cansativo para os usuários. | Real |
| 20 | As interfaces não seguem um padrão, muda o layout de uma para outra dificultando a memorização de ações executadas. | Real |
| 21 | Os ícones que remetem a "pagamentos" no aplicativos são diferentes dos que já estamos acostumados que dificulta a parte intuitiva do usúario | Real |
| 22 | Na aba “informações pessoais” há uma mistura de idioma, dificultando o entedimento do usuário. | Falso-Positivo |
| 23 | Problemas de acessibilidade, aplicativo não otimizado para todos os usuários, a opção de "menu" e "perfil" é pouco visível. | Real |
| 24 | Limitação de idioma, a falta da opção de escolher um idioma, limiatando alguns usuários a usar o aplicativo. | Real |
| 25 | Falta da opção de voltar a um estado anterior. | Falso-Positivo |


### 3.5 – Consolidação (ou Priorização)
| Heurísticas violadas | Quantidade |
| ---------------------|------------|
| Visibilidade do estado do sistema (H1)| 1|
| Corresponde ncia entre o sistema e o mundo real (H2)| 3 |
| Controle e liberdade do usua rio (H3) | 2 |
| Consiste ncia e padronizaça o (H4) | 4 |
| Prevença o de erros (H5) | 3 |
| Reconhecer ao inve s de relembrar (H6)  | 2 |
| Flexibilidade e eficie ncia de uso (H7)  | 3 |
|  Este tica e design minimalista (H8)  | 2 |
| Ajudar os usua rios a reconhecerem, diagnosticar e corrigir erros (H9) | 1 |
| Ajuda e documentaça o (H10) | 4 |


| Severidade | Quantidade|
|------------|-----------|
| 0 - Falso-Positivo |  |
| 1 - Cosmetico |  |
| 2 - Leve |  |
| 3 - Grande |   |
| 4 - Catastrofico |  



