  
 
</p>
<h1 align="center">
    <img alt="NextLevelWeek" title="#NextLevelWeek" src="./assets/banner.png" />
</h1>

<h4 align="center"> 
	🚧  Conecta ♻️ E-cidade 🚀 🚧
</h4>

<p align="center">
 <a href="#-sobre-o-projeto">Sobre</a> •
 <a href="#-funcionalidades">Funcionalidades</a> • 
 <a href="#-como-acessar-a-rota">Rotas</a> • 
 <a href="#-contribuidores">Contribuidores</a> • 

</p>


## 💻 Sobre o projeto

♻️ Api Conecta - é uma forma de disponibilizar a informação sobre as Unidades escolares, através dessa Api é possível consultar a informação de 
uma determinada Unidade escolar ou uma lista com todas as Unidades escolares do Município de Maricá.


Projeto foi desenvolvido por um grupo de estagiários da Prefeitura de Maricá.

---

## ⚙️ Funcionalidades

- [x] Consultar uma determinada Unidade Escolar
  - [x] É necessário estar logado no E-cidade
  - [x] Digitar na barra de endereço do navegador a seguinte URL:  http://localhost:8080/v4/api/educacao/conecta/dadosescola/ID
  - [x] Substitua o 'ID' pelo número da Unidade escolar que deseja consultar
  - [x] Após carregar a página as seguintes informações serão carregadas em um arquivo JSON: 

    - codigo_escola -> Código de registro do sistema E-cidade, esse deve ser o ID usado para consulta.
    - nome_fantasia -> Nome fantasia da Unidade escolar.
    - nome_completo -> Nome completo da Unidade escolar.
    - cnpj -> CNPJ da Unidade escolar.
    - telefone -> Telefones da Unidade escolar.
    - endereco -> Endereço que a Unidade escolar está localizada.
    - complemento -> Complemento do endereço da Unidade escolar. 
    - cep -> CEP da Unidade escolar.
    - bairro -> Bairro da Unidade escolar.
    - cidade -> Cidade da Unidade escolar.
    - estado -> Estado da Unidade escolar.
    - codigo_inep -> Código da Unidade escolar junto ao órgão INEP.
    - nome_diretor -> Nome do diretor geral da Unidade escolar.
    - celular_diretor -> Celular do diretor geral da Unidade escolar.
    - email_diretor -> E-mail do diretor geral da Unidade escolar.
    - info_lab -> Informa se tem Laboratório de informática na Unidade escolar / S -> Sim ou N -> Não.
    - comp_admin ->Informa se tem computador na administração da Unidade escolar / S -> Sim ou N -> Não.
    - banda_larga ->Informa se tem internet Banda Larga na Unidade escolar / S -> Sim ou N -> Não.


- [x] Consultar uma lista completa com todas as Unidades escolares
  - [x] É necessário estar logado no E-cidade
  - [x] Digitar na barra de endereço do navegador a seguinte URL:  http://localhost:8080/v4/api/educacao/conecta/listaescola
  - [x] Após carregar a página as seguintes informações serão carregadas em um arquivo JSON: 

    - codigo_escola -> Código de registro do sistema E-cidade, esse deve ser o ID usado para consulta.
    - nome_fantasia -> Nome fantasia da Unidade escolar.
    - nome_completo -> Nome completo da Unidade escolar.
    - cnpj -> CNPJ da Unidade escolar.
    - telefone -> Telefones da Unidade escolar.
    - endereco -> Endereço que a Unidade escolar está localizada.
    - complemento -> Complemento do endereço da Unidade escolar. 
    - cep -> CEP da Unidade escolar.
    - bairro -> Bairro da Unidade escolar.
    - cidade -> Cidade da Unidade escolar.
    - estado -> Estado da Unidade escolar.
    - codigo_inep -> Código da Unidade escolar junto ao órgão INEP.
    - nome_diretor -> Nome do diretor geral da Unidade escolar.
    - celular_diretor -> Celular do diretor geral da Unidade escolar.
    - email_diretor -> E-mail do diretor geral da Unidade escolar.
    - info_lab -> Informa se tem Laboratório de informática na Unidade escolar / S -> Sim ou N -> Não.
    - comp_admin ->Informa se tem computador na administração da Unidade escolar / S -> Sim ou N -> Não.
    - banda_larga ->Informa se tem internet Banda Larga na Unidade escolar / S -> Sim ou N -> Não.



## 🚀 Como acessar Rotas

Este projeto é divido em três partes:
1. Backend (pasta server) 
2. Frontend (pasta web)
3. Mobile (pasta mobile)

💡Tanto o Frontend quanto o Mobile precisam que o Backend esteja sendo executado para funcionar.
