# Packages

Pacotes são grupo de arquivos que podem ser reutilizados dentro de outros pacotes/projetos em Go.  Eles são organizados em pastas e arquivos, onde basicamente cada pasta são um pacote diferente. Também é possível utilizar pacotes da biblioteca padrão e externos (terceiros).
Para organizar os pacotes e suas dependências utilizamos o modulo, que é um arquivo que possui a informações do pacote utilizado (nome e versão utilizada) e suas dependências.
Para gerar um novo modulo, no terminal, dentro da pasta do projeto, execute o comando: `go mod init <nome-do-projeto>`. O arquivo gerado, guarda as informações como: nome do projeto, versão utilizada do Go, nome dos pacotes e suas versões utilizadas.

Com o módulo criado, é possível gerar um arquivo binário executável, onde compila todos os pacotes utilizados na pasta raiz do projeto. Para gerar o arquivo binário é utilizado o comando `go build` e ele criar um arquivo na pasta raiz.
Para construir outros pacotes, é preciso gerar um nova pasta dentro de uma pasta, e criar um novo arquivo Go e colocar o nome do pacote na primeira linha do arquivo. Exemplo:
```go
package auxiliar
import “fmt”
func Escrever() {
	fmt.Println(“imprimindo dentro do pacote auxiliar”)
}
```
Como no exemplo acima a função “Escrever” está escrita com a primeira letra maiúscula, desse jeito, a função fica visível para que estiver importando o pacote conseguir utiliza-la. Porém se a função fosse escrita com a primeira letra minúscula, essa função seria visível apenas dentro do escopo do pacote. O Go não é uma linguagem com orientação ao objeto como Java, que possível “Public” e “Private”.