# Desafio_Certi
Arquivos referentes ao desafio para Fundação Certi para vaga de Analista de qualidade

1. Testes WEB
Teste Exploratóro – Documentação e Evidências

Este repositório contém os materiais produzidos durante a realização do teste exploratório. Foram elaborados dois arquivos principais:

Um arquivo em PDF: Texte_Exploratorio. Para o mesmo documento existe a versão em excel, caso ocorra algum problema de visualização.


Evidências e Descrição dos Problemas

Todas as descrições dos problemas encontrados durante o teste estão documentadas no arquivo:

Evidencias_teste_exploratorio

Além disso, as imagens dos bugs identificados podem ser consultadas dentro da pasta:

/evidencia

Essa pasta contém capturas de tela coletadas durante os testes. Imagens essas também presentes dentro do arquivo: Evidencias_teste_exploratorio.


1.2 Casos de teste WEB
Casos de teste Web – Documentação

Este repositório contém os materiais gerados para execução de casos de teste Web:

Arquivos Incluídos

PDF com o Descrição dos casos de testes: Casos_de_Teste. Arquivo esse possui sua versão Word, caso aconteça problemas de visualização.

Foram utilizados cards de passo a passo para cada teste, abrangendo parte funcional com teste de caixa-preta, sem nenhum acesso ao código fonte da pagina Web.



2. Automação de testes WEB
Automação de testes WEB – 
Este repositório contém os materiais produzidos durante a realização do Automação de testes WEB utilizando Robot Framework. 
Foram realizados 4 casos de testes automatizados:

1 - Cadastrar com Sucesso
Realiza cadastro preenchendo todos os campos corretamente e tenta finalizar no botão: Submit.

2 - Validar Campos Obrigatórios
Valida mensagens de erro ao tentar enviar sem preencher os campos obrigatórios do formulário.

3 - Cadastrar sem preencher todos os campos
Tenta cadastrar preenchendo apenas alguns campos e valida impedimento no envio.

4 - Upload de Imagem no Formulário
Teste para fazer upload de uma imagem usando o botão "Escolher Arquivo"

Instruções:

- Instalar LibrarySelenium;
- instalar Python;
- Os testes serem executados um a um preferencialmente;
- Disponibilizei arquivo .TXT com código fonte;
- Utilizar o arquivo Desafio_Certi.robot e importar no VSCode;

 OBS. O teste 1 está com FAIL e não realiza gravação de Tela, mas disponibilizei print (Erro) juntamente com documentação que o descreve reportando detalhadamente ao desenvolvedor: Relatorio_erro_formulario_atualizado_dropdown_Country.PDF;

- O teste: 4 - Upload de Imagem no Formulário, precisa que na variável:
${FILE_PATH}     E:\\Robot\\Foto\\perfil.jpg    #informar aqui o caminho completo da imagem para upload

Arquivos gerados:
Pasta:Gravação tela - Contem as gravações de telas de cada teste juntamente print de cada resultado de teste realizado;
Arquivo .TXT - Contem código fonte dos casos de testes realizados;
Desafio_Certi.robot - Arquivo gerado pela ferramenta Robot com testes;
Relatorio_erro_formulario_atualizado_dropdown_Country.PDF - Contem relatório detalhado do FAIL referente ao teste: 1 - Cadastrar com Sucesso;


3. Testes de API
Testes de API - Arquivos e instruções

Este repositório contém os materiais produzidos durante a realização dos teste Testes de API:

 3 casos de teste que você considera básicos:
 Get - Listar Produtos;
 Get - Buscar produto por ID;
 Post - Criar Usuário;

 3 casos de teste que você considera intermediários:
 Put - Atualizar Produto;
 Delete - Remover Produto;
 Get - Produtos por Categoria;
 
 3 casos de teste que você considera avançados:
 Post - Login;
 Post - Criar Carrinho;
 Get - Listar Carrinho;
 Put - Atualizar Carrinho;
 
 Instruções: 
  - Importar o aquivo: FakeStoreAPI Collection.postman_collection.Json na ferramenta Postman;
  - As evidencias de cada teste estão na pasta: Evidencias;














