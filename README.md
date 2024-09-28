# resumo-lab-azure-seguranca
"Este repositório contém o resumo das lições aprendidas durante o desenvolvimento do lab na DIO"

Apredemos nessa aula os seuintes tópicos: 

Identidade, acesso e segurança: 

* Serviços de diretório 
* Métodos de autenticação 
* Modelo de Segurança. 

Segurança é sempre de responsabilidade de cliente.

Entedemos o que é: 

***Serviços de diretorio no Azure:***
  
***Como microsoft Entra ID*** que é o serviço de gerenciamento de identidades e acesso baseado em núvem do microsoft azure.(Active Directory), ou seja uma serviço de diretorio  que vai permitir que se faça login tanto dos aplicativos de núvem da microsoft, quanto os aplicativos que desenvolvemos, fazendo o controle de gerenciamento de identidade. 

***É de responsabilidade do "Entra":*** 

* Garantir a autenticação ( Os funcionários entram para acessar os recuros). 
* Garantir o logon unico (SSO) 
* Realizar o gerencimento de aplicativos 
* Realizar o gerencimento Negócios para Negócios: B2B
* Realizar o gerencimento de dispositivos. 


  ***Como microsoft Entra Domain Services:***  É onde temos que sicronizar o AD local com domínio gerenciado na núvem ( Domínio gerenciado)   


***Diferença entre autenticação e autorização:*** 

Autenticação: Identifica a pessoa ou serviço buscando acesso a um recurso, solicita credencias de acesso legitmo  e é baseada para criar principios de identidade e controle de acesso seguro. 

Autorização: Determina o nível de acesso de uma pessoa ou serviço, define quais dados eles podem acessar e o que podem fazer com eles. 

* Métodos de autenticação no Azure: 

* SSO( Logon único)
* MFA ( Autenticação Muiltifator.) 
* Sem senha: 

* As identidades extenas com utilização do B2C ( Autenticação com base de dados do azure usando outras plataformas de acesso como o google e facebook ) 

* O acesso condicional do Entra: É uma ferramenta que é usada tanto para permitir quanto para bloquear sinais de acesso de usuário ou grupo, local do Ip , dispositivos, aplicativos e detecção de risco. 

* O controle de acesso baseado em função ( RBAC ou permissionamento ): Realiza o gerencimanto de acesso de granulidade fina, divide  as tarefas dentro da equipe e concede somente a quantidade de acesso de que os usuários precisam para trabalhar elém de  habilitar o cesso ao portal do Azure  para controlar o acesso aos recursos por meio de permissões. 
 
* O conceito de confiaça Zero: Proteja os ativos onde eles estiverem . 
* A finalidade de modelo de defesa em profundidade por niveis de acesso de camadas.  

* A finalidade do microfoft Defender para nuvem: É um serviço de monitoramente que fornece proteção de ameaças nos datacenters do Azure e locais, trazendo uma visão do que ta certo ou errado na organização.

* E por fim, demonstrou por meio de laboratório a aplicação dos conceitos apresentados acima. 

