# Plano de Testes de Software

<span style="color:red">Pré-requisitos: <a href="2-Especificação do Projeto.md"> Especificação do Projeto</a></span>, <a href="3-Projeto de Interface.md"> Projeto de Interface</a>


<ol>
 
 
  Os requisitos para realização dos testes de software são:
   
   ● Aplicativo publicado na Play Store.
 
   ● Conectividade de Internet.

 Os testes funcionais a serem realizados no aplicativo são descritos a seguir.
 
## CASOS DE TESTES SUCESSO: 
<ol>



  | CASO DE TESTE| CT-01 – CADASTRO |
  |--------------|------------------------|
  |REQUISITOS ASSOCIADOS	|RF-001|
  |                                                   |
  |OBJETIVO DO TESTE	| Verificar se o cadastro foi realizado com sucesso e se o redirecionamento ocorreu de forma correta.|
  |      |	1) Acessar o app|
  |PASSOS| 2) Clicar no botão do botão cadastro|
  |      | 3) Visualizar a pagina de login para entrar no app|
  |                                                          |
  |CRITÉRIO DE ÊXITO| ●	O app deve apresentar na página principal o botão Cadastro e após efetivação da conta redirecionar para tela de Login.|

 
|CASO DE TESTE |CT-02 – LOGIN , ALTERAÇÃO E EXCLUSÃO DE CONTA |
|--------------|-------------------------------------|
|REQUISITOS ASSOCIADOS	|RF-002 – RF-003 – RF-004| 
|OBJETIVO DO TESTE|	Verificar se os botões estão posicionados de forma correta e se está ocorrendo o login,alteração e exclusão da conta de forma efetiva.|
|      	|1)	Acessar o app|
|       |2)	Clicar no botão de Login|
|       |3)	Fazer o Login|
|       |4)	Clicar em Meu Perfil|
|Passos |5)	Clicar em Alterar Conta|
|       |6)	Digitar os dados a serem alterados|
|       |7)	Clicar em concluir|
|       |8)	Clicar no botão Excluir Conta|
|       |9)	Clicar em Concluir|
|       |10)	Sair da Conta|
|                 	| ●	Após realização do login o app deve apresentar um menu central com todas as opções para buscar um profissional|
|CRITÉRIO DE ÊXITO	| ●	Após realização do login o app deve apresentar a opção meu perfil com o botão Alterar Conta e redirecionando para tela de alterar os dados. |
|                 	| ●	Após realização do login o site deve apresentar a opção meu perfil com o botão Excluir Conta e redirecionando para tela de excluir os dados. |

|CASO DE TESTE |	CT-03 – CADASTRO, ALTERAR E EXCLUIR CUPONS|
|-------------|------------------------------------------------| 
|REQUISITOS ASSOCIADOS|RF-005, RF-006,  RF-007|
|OBJETIVO DO TESTE|	Verificar se os botões estão posicionados de forma correta e se está ocorrendo o login,alteração e exclusão da conta de forma efetiva.|
|      	|1)	Acessar o app|
|       |2)	Clicar no botão de Login|
|       |3)	Fazer o Login|
|       |4)	Clicar em Meu Perfil|
|Passos |5)	Clicar em incluir cupom|
|       |6)	Digitar os dados do Cupom|
|       |7)	Clicar em concluir|
|       |8)	Clicar no botão Excluir Cupom|
|       |9)	Clicar em Concluir|
|       |10)	Sair da Conta|
|CRITÉRIO DE ÊXITO	| ●	Após realização do login o app deve apresentar um menu central com todas as opções de CRUD para sua conta|
|||
  
 </ol>

 
## CASOS DE TESTE INSUCESSO: CT-01 (RF-001,RF-002)
<ol>
 
 |CASO DE TESTE |	CT-01 – CADASTRO E LOGIN INCORRETOS| 
 |-------------|-----------------------|
 |REQUISITOS ASSOCIADOS	|RF-001-RF-002|
 |OBJETIVO DO TESTE|Verificar se todos os redirecionamento e validação do formulário de cadastro e login estão com validação.|
 |                 |1) Acessar o app|
 |Passos           |2) Clicar no botão de cadastro|
 |                 |3) Digitar vários caracteres especiais|
 |                 |4) Clicar em cadastrar|
 |                  	| ●	Clicar no botão cadastro e digitar caracteres especiais e validar se ocorre o redirecionamento para tela cadastro|
 |Critérios de Êxito	| ●	Clicar no botão login e digitar caracteres especiais e validar se ocorre o redirecionamento para tela cadastro|
 


  </ol>
 </ol>
