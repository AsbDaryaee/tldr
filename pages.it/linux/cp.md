# cp

> Copia file e directory.
> Maggiori informazioni: <https://www.gnu.org/software/coreutils/manual/html_node/cp-invocation.html>.

- Copia un file in un'altra posizione:

`cp {{percorso/del/file_da_copiare.est}} {{percorso/del/file_di_destinazione.est}}`

- Copia un file all'interno di una directory, mantenendone uguale il nome:

`cp {{percorso/del/file_da_copiare.est}} {{percorso/della/directory}}`

- Copia ricorsivamente i contenuti di una directory in un'altra posizione (se la destinazione esiste, la directory è copiata al suo interno):

`cp {{[-r|--recursive]}} {{percorso/della/directory_da_copiare}} {{percorso/di/destinazione}}`

- Copia una directory ricorsivamente in modalità prolissa (mostra i file mentre vengono copiati):

`cp {{[-vr|--verbose --recursive]}} {{percorso/della/directory_da_copiare}} {{percorso/di/destinazione}}`

- Copia i file di testo in un'altra posizione, in modalità interattiva (richiede conferma all'utente prima di sovrascrivere):

`cp {{[-i|--interactive]}} {{*.txt}} {{percorso/di/destinazione}}`

- Segue i collegamenti simbolici prima di copiare:

`cp {{[-L|--dereference]}} {{collegamento}} {{percorso/di/destinazione}}`

- Utilizza il percorso completo dei file originali, creando ogni directory intermedia mancante mentre durante la copia:

`cp --parents {{percorso/dei/file/da/copiare}} {{percorso/del/file/destinazione}}`
