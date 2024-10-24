
# Alreo

## Descrição
O **Alreo** é uma ferramenta voltada para o auxílio no aprendizado da álgebra relacional. O Alreo é gratuito, completamente em português, e foi desenvolvido para operar na web, proporcionando uma interface intuitiva que permite a construção e execução de consultas em álgebra relacional utilizando notações semelhantes às dos livros-texto de bancos de dados.

A arquitetura do sistema conta com três módulos principais:
- **Interface de usuário (Front-end)**: Elaborada em HTML com página única.
- **Servidor (Back-end)**: Desenvolvido com o framework Flask em Python.
- **[radb](https://github.com/junyang/radb)**: Um pacote utilizado para interpretar e traduzir consultas em álgebra relacional para SQL. O servidor implementa nativamente o SGBD SQLite3 em Python.

Atualmente, existem ferramentas que interpretam álgebra relacional, auxiliam na correção sintática e permitem a visualização dos resultados das consultas. No entanto, muitas dessas ferramentas não estão disponíveis em formato web e requerem a instalação de um SGBD local, o que exige a instalação prévia de programas no computador. O **Alreo** oferece um ambiente virtual na web que retorna os resultados das consultas e proporciona uma interface simples para a criação e manipulação de consultas em um SGBD real.

## Instruções de instalação

### Pré-requisitos
- **Python 3.11.4**

### Etapas

1. **Instalando o pacote radb**
   ```bash
   pip install radb
   ```

2. **Instalando os demais pacotes**
   ```bash
   pip install Flask Flask-Session
   pip install -r requirements.txt
   ```

## Configuração

### Etapas de configuração

1. **Navegue até a pasta `ralib` dentro do projeto**:
   - Localize o diretório `ralib` no projeto. Esse diretório deve conter o arquivo `sys.ini`.
     - Caminho: `Alreo/ralib/sys.ini`

2. **Editar o arquivo `sys.ini`**:
   - Abra o arquivo `sys.ini` com um editor de texto.
   - Dentro do arquivo, localize o campo `configfile` e altere o valor para o caminho relativo do arquivo `radb.ini`.
   - Exemplo de valor para o `configfile`: 
     ```ini
     configfile = C:\Users\lucas\OneDrive\Documentos\RAproject\ralib\radb.ini
     ```

## Licença

### Permissão para uso educacional
Este projeto está disponível para uso educacional. Sinta-se à vontade para usar e modificar para propósitos não comerciais.
