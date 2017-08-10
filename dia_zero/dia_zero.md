## Dia Zero

*Vulnerabilidade de Dia Zero é uma vulnerabilidade de software que ainda não
foi revelada, podendo ser explorada por pessoas mal intencionadas sem que os
autores do software atacado tenham tempo de corrigir a vulnerabilidade*

No mês de Março, o site WikiLeaks publicou um [conjunto de
documentos](https://wikileaks.org/ciav7p1/) contendo supostas informações sobre
o arsenal de armas cibernéticas da Agência Central de Inteligência (CIA) dos
Estados Unidos. Dentre as informações presentes nos documentos, existem
descrições das capacidades e do funcionamento de alguns dos mais de 1000 vírus,
cavalos-de-troia e ataques de dia zero utilizados pela agência norte-americana. Ainda segundo
o portal, tal arsenal é composto por centenas de milhões de linhas
de código e possui recursos como ativar microfones de Smart TVs (mesmo
desligadas), acessar dados de celulares (como geolocalização e comunicações via
áudio ou texto) e ter algum nível de acesso a sistemas operacionais. Algumas
técnicas permitem ainda que a agência tenha acesso a dados que acreditamos
estarem seguros devido à criptografia, como mensagens de aplicativos como
WhatsApp e Telegram. Dentre os produtos afetados estão Android, iOS, OSx, Linux
e Windows.

Essa coleção de armas cibernéticas aparentemente tem circulado
entre ex-agentes do governo dos Estados Unidos sem necessidade de qualquer tipo de autorização,
forma pela qual o próprio WikiLeaks teve acesso a parte dos dados. É
importante entender que, como se tratam de dados, como código ou programas de
computador, copiar e redistribuir essas armas passa a ser uma tarefa trivial a
partir do momento em que a agência não tem mais o controle sobre quem as possui
(considere ainda que as pessoas redistribuindo tais ferramentas têm a
capacidade técnica de fazê-lo de maneira discreta, deixando poucos ou nenhum
rastro). Com isso, temos pessoas, governos e empresas com capacidades
de espionagem similares às da CIA (observe que o preço de um único vírus de
computador pode chegar à casa dos milhões de dólares). O famoso
professor Andrew Tanenbaum, autor de trabalhos importantes nas áreas de
sistemas operacionais e redes de computadores, menciona em um de seus livros
que um vírus de computador pode trazer prejuízos à sociedade parecidos com os
de desastres naturais, como furacões ou terremotos (se você tem alguma dúvida,
certamente não ouviu falar do
[Stuxnet](https://pt.wikipedia.org/wiki/Stuxnet)).

#### Mas o que isto tudo tem a ver com software livre?

Vulnerabilidades de software são publicadas todos os dias por pesquisadores e
empresas em [bases de dados abertas](https://nvd.nist.gov), permitindo que
desenvolvedores, distribuidores e usuários de software se protejam de eventuais
ataques e que pesquisadores investiguem vários aspectos quanto à natureza
dessas vulnerabilidades.

Em [um destes estudos](http://dl.acm.org/citation.cfm?id=1920299),
pesquisadores da Universidade da Pennsylvania mostram que, após o lançamento de
uma nova versão, um software livre demora, em média, algumas semanas
a mais do que um software não-livre para ter a primeira vulnerabilidade
descoberta e que a taxa em que as vulnerabilidades subsequentes aparecem é
menor no software livre. Ou seja, o velho argumento de que software de código
aberto pode estar mais vulnerável a ataques (uma vez que o atacante tem acesso
ao código-fonte) não só é inválido, como há evidências de que o contrário
acontece: sistemas restritos podem estar mais suscetíveis a ataques.

Independentemente da veracidade das recentes publicações do portal WikiLeaks,
existe uma forte tendência de adoção de software livre em governos ao redor do mundo.
[O governo dos Estados Unidos acredita que utilizar e contribuir com software
livre e dados abertos facilita o compartilhamento de dados no governo, melhora
os serviços e promove novos produtos e
empregos](https://obamawhitehouse.archives.gov/developers). Enquanto isso, o
governo brasileiro voltou recentemente a insistir em adquirir soluções não-livres, como anunciado
pela
[SLTI](http://link.estadao.com.br/blogs/codigo-aberto/soft-livre-no-governo/),
estimulando pessoas em cargos técnicos, no governo ou não, a serem apenas
usuários passivos de tecnologias fechadas ao invés de explorarem seus
potenciais criativos estudando, modificando e, por que não, descobrindo
vulnerabilidades importantes em sistemas em uso (mas apenas em sistemas abertos,
já essa atividade poderia ser considerada ilegal em muitos sistemas restritos).
