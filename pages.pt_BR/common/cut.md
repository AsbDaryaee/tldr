# cut

> Recorta campos do `stdin` ou de arquivos.
> Mais informações: <https://www.gnu.org/software/coreutils/manual/html_node/cut-invocation.html>.

- Imprime um intervalo específico de caracteres/campos de cada linha:

`{{comando}} | cut --{{characters|fields}} {{1|1,10|1-10|1-|-10}}`

- Imprime um intervalo de campos de cada linha com um delimitador específico:

`{{comando}} | cut --delimiter "{{,}}" --fields {{1}}`

- Imprime um intervalo de caracteres de cada linha de um arquivo específico:

`cut --characters {{1}} {{caminho/para/arquivo}}`

- Imprime campos específicos de linhas terminadas em `NUL` (ex.: assim como em `find . -print0`) ao invés de novas linhas:

`{{comando}} | cut --zero-terminated --fields {{1}}`
