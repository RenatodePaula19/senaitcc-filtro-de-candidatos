<h3>Filtro de Candidatos</h3>
Trabalho de Conclusão de Curso SENAIMG.

<h2>FILTRO DE CANDIDATOS</h2>
Um site para as empresas filtrarem  se cadastrarem em busca de empresas, para encontrar os melhores perfis que se enquadram 

<h3>Requisitos Funcionais do Sistema</h3>

RF-001: O sistema deve permitir a busca de informação de candidatos pelas empresas e empresas procurarem informações dos candidatos que vão se cadastrar no site.

RF-002: O sistema deve gravar os dados retornados pela consulta em um banco de dados, os dados armazenados são: Nome do candidato, Nome da empresa, Gênero, Data de Nascimento, Endereço do candidato, Endereço da empresa, Cadastro de envio de currículo.

RF-003: O cadastro dos dados da empresa e do candidato serão gravados no banco de dados.


<h3>Requisitos Não Funcionais</h3>
RNF:001 - Garantir o funcionamento do site nos navegadores: Edge,google chrome.

RNF:002 - O sistema deve ter acesso a internet.

RNF:003 - O usuário deve ter instalado em seu computador o python na versao 3.8.10 ou superior.
<hr>
<h3>Regras de Negócio</h3> 

1- A consulta aos dados do candidato/empresa deverá ser feita através do site preechendo os campos requisitados pelo sistema e após será enviado para o banco de dados para análise interna. O nosso sistema irá filtrar os dados que mais se encaixaram com a vaga requisitada.

<h3>CASO DE USO: REGISTRO DE CANDIDATOS </h3>

<H2>IMAGEM VAMO PÔ</H2>

1-O usuário deve acessar o site e realizar um cadastro das informações pessoais juntamente do seu currículo e filtros selecionados e enviar para análise.
2-O sistema salva o cadastro do usuário em um banco de dados e logo após a análise,será exibido para as empresas(a análise levará até 24hrs).

<h3>CASO DE USO: CADASTRO EMPRESA </h3>
<hr>
1-A empresa acessará uma página específica para cadastro,aceitará os termos de uso.
2-A empresa deve acessar o site e realizar um cadastro das informações jurídicas e enviar para análise.
3-O sistema salva o cadastro da empresa em um banco de dados e logo após a análise,será exibido na plataforma(a análise levará até 24hrs).
 


<h3> caso de uso: gerar planilha excel baseado na tabela FIPE </h3>
# -----------------------------------------------

O sistema deve realizar uma busca através de uma API Web que traz dados oficias 
