# Projeto_Integrador_III

Descrição das funcionalidades e características das aplicações que serão desenvolvidas para este projeto integrador.

API:
* Comunicação com banco de dados MySQL para enviar e receber dados.
* Condicionais específicas para determinadas tarefas do projeto.
* Chave de segurança que será requisitada de todos que assesam a API.
* Controle de conexões dos gateways para o envio de dados.

- Será fornecida para o equipamento denominado "gateway" que realizará 
  envio de dados para atualização de dados existentes no banco e inserção de novos
  dados, comando para excluir dados expecíficos do banco.

- Será fornecida para o aplicativo mobile, ao acessar o aplicativo o mesmo 
  realizará solicitações de dados através da API afim de monitorar o conjunto 
  de dados determinado a abaixo.


APLICATIVO DE MONITORAMENTO:
* Visualizar em tempo real gateways online e offline.
* Usuários online no site de controle e monitaramento dos gateways.
* Quantidades de relatórios emitidos no site de controle e monitoramento dos gateways.
* Acessibilidade para pessoas com deficiência.

- O aplicativo tem o objetivo de monitorar as atividades que ocorrem no banco de dados, 
  exclusivamente as que foram citadas à cima. 
  

BANCO DE DADOS(MySQL):
* Os dados dos gateways serão armazenados aqui, bem como registros de históricos, nomes dos
  periféricos conectados ao gateway, configurações e etc...
* Somente a API realizará conexão com o banco de dados, tanto para o aplicativo como também
  para o gateway.
* Os dados armazenados pelo banco com exeção daqueles que tem o objetivo de definir configurações
  de todos o sistema, foram gerados por usuários reais (alunos) e gateway real 
  (equipamento fornecido pela comunidade externa) conectado a API. 
  
CLOUD COMPUTING:
* Realiza a emissão de relatórios de gateway.
* No momento em que é realizado um relatório realiza o cálculo da quantidade de memória utilizada
  para gerar o relatório.
* Extrai o timestamp do início e fim do período solicitado para relatório.
* Contabiliza o tempo de início e fim da geração do relatório.
* Obtém dos dados de qual das máquina foi requerido dados para gerar o relatório.
* Obtém o tempo de conexão de cada usuário.

- Em todas as funcionalidades descritas à cima o armazenamento dos dados obtidos será realizado para 
  consulta posterior.












