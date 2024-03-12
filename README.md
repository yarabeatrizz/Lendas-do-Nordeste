# Projeto NomedoProjeto

**Instituto Federal do Piauí - Campus Pedro II**

**Número do Grupo:** XX  
**Curso:** Análise e Desenvolvimento de Sistemas  
**Módulo:** III
**Disciplina:** Engenharia de Software I  
**Professor:** Cleber Araújo  

## Equipe de Desenvolvimento

| Matrícula   | Aluno             | Função| 
|-------------|-------------------|-------|
| xx/xxxxxx   | xxxx xxxx xxxxx  |xxxxxxx|
| xx/xxxxxx   | xxxx xxxx xxxxx  |xxxxxx|

## Visão Geral do Projeto
Uma descrição concisa do jogo, destacando sua proposta única e os principais aspectos que o diferenciam.

## Objetivos do Projeto
Defina claramente os objetivos que você espera alcançar com o desenvolvimento do jogo. Isso pode incluir metas de mercado, experiência do usuário ou características específicas do jogo.

## Principal(is) Metodologia(s) Adotada(s)
- Exemplo.: Scrum

## Metodologia Scrum
Explicação breve sobre como a metodologia Scrum está sendo aplicada no desenvolvimento do jogo. Isso pode incluir detalhes sobre sprints, reuniões diárias, revisões de sprint, etc.

## Principais Tecnologias Utilizadas e/ou Pretendidas
- Exemplo: React
- Exemplo: Django

## Cronograma de Desenvolvimento
Apresente uma visão geral do cronograma do projeto, destacando as sprints planejadas, marcos importantes e as entregas esperadas.

## Recursos Necessários
Liste os recursos necessários para o desenvolvimento, incluindo recursos humanos, materiais, financeiros, etc.

## Desafios Antecipados
Identifique desafios que você antecipa ao longo do desenvolvimento e como planeja enfrentá-los.

## O Projeto está rodando?
( ) SIM (x) NÃO

## Screenshots
![Screenshot 1](URL_da_Imagem_1)
![Screenshot 2](URL_da_Imagem_2)
![Screenshot 3](URL_da_Imagem_3)


## Introdução

Este repositório traz um template de documentação a ser seguido pelos grupos.

## Tecnologia

A geração do site estático é realizada utilizando o [MkDocs](https://www.mkdocs.org/).

> "MkDocs is a fast, simple and downright gorgeous static site generator that's geared towards building project documentation."

### Instalando o MkDocs

Para instalar o MkDocs, você pode executar o comando:

```shell
pip install mkdocs
```

Para mais detalhes, consulte o [Guia de Instalação](#).

# Criando um Novo Projeto

Começar é super fácil. Para criar um novo projeto, execute o seguinte comando a partir da linha de comando:

```shell
mkdocs new meu-projeto
cd meu-projeto
```

Dê um momento para revisar o projeto inicial que foi criado para você.

## Estrutura Inicial do MkDocs

Existe um único arquivo de configuração chamado `mkdocs.yml` e uma pasta chamada `docs`, que conterá os arquivos de origem da sua documentação (o valor padrão para a configuração `docs_dir` é `docs`). No momento, a pasta `docs` contém apenas uma página de documentação, chamada `index.md`.

O MkDocs vem com um servidor de desenvolvimento integrado que permite visualizar sua documentação enquanto você trabalha nela. Certifique-se de estar no mesmo diretório do arquivo de configuração `mkdocs.yml` e, em seguida, inicie o servidor executando o comando `mkdocs serve`:

```shell
$ mkdocs serve
```

```shell
INFO    -  Construindo documentação...
INFO    -  Limpando o diretório do site
INFO    -  Documentação construída em 0.22 segundos
INFO    -  [15:50:43] Observando alterações nos caminhos: 'docs', 'mkdocs.yml'
INFO    -  [15:50:43] Servindo em http://127.0.0.1:8000/
```

Abra [http://127.0.0.1:8000/](http://127.0.0.1:8000/) no seu navegador, e você verá a página inicial padrão sendo exibida:

![O servidor MkDocs ao vivo](http://127.0.0.1:8000/)

O servidor de desenvolvimento também suporta recarregamento automático e reconstruirá sua documentação sempre que algo no arquivo de configuração, diretório de documentação ou diretório do tema for alterado.

Abra o documento `docs/index.md` no seu editor de texto preferido, altere o título inicial para "MkLorum" e salve suas alterações. Seu navegador recarregará automaticamente e você verá sua documentação atualizada imediatamente.

Agora tente editar o arquivo de configuração: `mkdocs.yml`. Altere a configuração `site_name` para "MkLorum" e salve o arquivo.

```yaml
site_name: MkLorum
site_url: https://example.com/
```
