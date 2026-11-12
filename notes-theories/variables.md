# Variáveis

Variáveis são uma maneira de armazenar valores que podem ter alterações, o Go é uma linguagem fortemente tipada, que quer dizer que todo valor deve ter seu tipo informado, mas o tem várias maneira de realizar essa ação.

1.  O padrão:
```go
var nome-da-variavel <tipo> = valor
// É possível emitir o valor e inicializar a variável com valor padrão do tipo definido.
```
2. Inferência de tipo:
```go
// Aqui o Go pega o tipo da variável pelo valor.
nome-da-variavel := 10.2
nome, endereco := "Jhonata", "Teixeira de Freitas"
```
3. Declarando várias variáveis com apenas uma chamada:
```go
// Existem 2 maneiras de realizar essa ação:
var (
    nome-da-variavel1 <tipo> = valor
    teste string = "Teste"
)

var escola, nome string = "valor1", "valor2"
```

## Constantes

Constantes também armazenam valores, mas o seu valor não pode ser alterado após declara-los.

```go
const nome-da-constante <tipo> := valor

const (
    const2 int = 45
    const3 string = "Qual o nome?"
)
```