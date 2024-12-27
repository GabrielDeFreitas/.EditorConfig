## Como funciona

O arquivo `.editorconfig` é colocado na raiz do projeto e contém uma série de regras que definem como o código deve ser formatado. Essas regras podem incluir:

- Tipo de indentação (espaços ou tabulações)
- Tamanho da indentação
- Codificação de caracteres (por exemplo, UTF-8)
- Fim de linha (LF, CRLF)
- Inserção de uma nova linha no final do arquivo

Para usar o EditorConfig, basta instalar o plugin correspondente ao seu editor, se necessário, e adicionar um arquivo .editorconfig ao seu projeto.

Abaixo está um exemplo de arquivo `.editorconfig` com as regras que mais utilizo. Deixei registrado para facilitar o uso e garantir a consistência na formatação do código.

Para mais informações sobre as regras, acesse o site: https://editorconfig.org

## Exemplo de arquivo .editorconfig

```ini
root = true

[*]
end_of_line = lf
indent_style = space
indent_size = 2
charset = utf-8
trim_trailing_whitespace = true
insert_final_newline = true
```

```ini
## Descrição das Regras do Arquivo .editorconfig

### root = true

Indica que este é o arquivo de configuração raiz. Se houver outros arquivos `.editorconfig` em diretórios superiores, eles serão ignorados.

### [*]

Aplica as regras a todos os arquivos no projeto. O asterisco (\*) é um curinga que representa todos os arquivos.

### end_of_line = lf

Define o caractere de fim de linha como LF (Line Feed), que é o padrão em sistemas Unix/Linux.

### indent_style = space

Define o estilo de indentação como espaços, em vez de tabulações.

### indent_size = 2

Define o tamanho da indentação como 2 espaços.

### charset = utf-8

Define a codificação de caracteres como UTF-8.

### trim_trailing_whitespace = true

Remove automaticamente os espaços em branco no final de cada linha.

### insert_final_newline = true

Garante que haja uma nova linha no final de cada arquivo.

```
