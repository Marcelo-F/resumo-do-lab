Modulo 1  - tipo de cloud 

privada - Tem acesso aquele servidor na nuvem para exclusivamente uma filial da empresa.

publica -
Fornecer acesso a recursos e serviços a várias empresas e usuários

CapEx - despesas capital, um custo maior para a implementação, por causa da estrutura fisica, mas costuma normalizar após as implementações tendo custo basicos com manutenções, como por exemplo energia eletrica e internet...


OpEx - despesas na operação, usa nuvem e custo vai aumentando conforme vai alocando mais recurso na azure. Paga só o que usar. 
Implementação mais rapida do que capEx.

Modulo 2 Benefícios da nuvem 

Alta disponibilidade - esta disponivel o maior tempo disponível

Escalabilidade -  ajustar os recursos ao cliente conforme a demanda

Elasticidade -  Ajusta conforme o serviço é requisitado, ajusta de forma dinamica. O cliente deixa pré definido o recurso  limite, quando se tem requisições
em alta demanda e atinge esse limite que o cliente deixou pré definido, automaticamente se aloca mais recursos para evitar a queda do sistema. 

confiabilidade - Se o sistema falhar ele volta a funcionar sem sofrer dano. Carcteristica, pode ter o sistema em qual quer parte do mundo pela azure. Garantia que 
o sistema terá minima queda ou nenhuma. 

previsibilidade - Confiança e desempenho.

segurança - Cliente e provedor devem esta alinhados. Provedor disponibiliza as ferramentas, mas cabe ao cliente usar e aplicar as ferramentas.

Governança - Auditoria de nuvem sinalizar qualquer recurso que esteja fora de conformidade. Exemplo: Farmacia tem padrões de codigo de remedios  e regras que precisa ser seguidas 
pelo estado,  essa empresa gerar esse padrões na nuvem para que a plataforma fique nos conformes e na auditoria não seja sinalizada negativamente. Padrões corporativas de gestão.

Gerenciabilidade - Criação de recusros na azure atraves de varias ferramentas..  visual studiom, terminal, power shell  etc...




Aula 3 - Tipos de serviços na nuvem 

Iaas - Infra estrutura para serviço é maior gerenciamento e gestão do contratante e menos do provedor(azure)
Mais trabalhoso  para quem contrata os serviços na nuvem. 
útil para lidar com demandas impreviísveis e necessidades armazenamento constante.

Forma de pagamento é de assinatura, paga o que foi contratado.

Paas -
A nível de desenvolvimento, o dev pode compilar para desenvolver ou personalizar aplicativos que estejam em nuvem.  

A nível de negócio aprimoramento nas previsões de resultas através de padrões que auxiliam na decisão de negócio.


Acesso ao ambiente de desenvolvimento de qual quer lugar do mundo, basta ter internet
Forma de pagamento é pagar conforme o uso.

Saas - É o inverso iaas, o contratante tem menos trabalho com a gestão que passa a ser do provedor inclusive da segurança.  

Forma de pagamento paga pelo uso através de assinatura que estará relacionado ao nível de uso.

O Saas é basiado em escala verticalmente e horizontalmente de acordo com o nível de uso. 

Esse é o nĩ́vel mais alto entre esses três mencionados.



Modelo de responsabilidade compartilhada




Identidade acesso e segurança 

Microsoft entra Id - Gerenciamento de id e acesso

valida por exemplo a autenticação de email e senha 


Id do Microsoft Entra 

Garantir a autenticação
Logon único (SSO) - após login realizado o usuário não precisa passar mas os dados novamente para acessar outras abas de autetnicação


Microsoft Entra domain Service ->

tudo que é feito no onPrimes é sicronizado com a nuvem, porém se um usuario for criado na nuvem ele não será sicronizado com a  empresa.

A unica informação que será sicronizado da nuvem será a senha. 




Aula autenticação e autorização 

Autenticação - identifica a pessoa 
Autorização  - Autoriza a pessoa conforme o nível de acesso dela.


Autenticação B2B ->
Entidades externas, usuario fica salvo  em um diretório diferenciado, por exemplo convidado. 

B2c - Por exemplo logar no linkedin com a conta do facebook


ACESSO CONDICIONAL 
Monitoramento para verificar se o login é comum ou se esta acessando de lugares diferentes

Confiança zero -> Sempre prevendo po pior cenário  para aplicar o máximo de proteção.

Usuario ter só os acessos necessarios.

Desconfiar de tudo e não confiar em ninguém. 





