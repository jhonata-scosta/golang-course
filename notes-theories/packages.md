# Packages

Pacotes são grupo de arquivos que podem ser reutilizados dentro de outros pacotes/projetos em Go.  Eles são organizados em pastas e arquivos, onde basicamente cada pasta são um pacote diferente. Também é possível utilizar pacotes da biblioteca padrão e externos (terceiros).
Para organizar os pacotes e suas dependências utilizamos o modulo, que é um arquivo que possui a informações do pacote utilizado (nome e versão utilizada) e suas dependências.
Para gerar um novo modulo, no terminal, dentro da pasta do projeto, execute o comando: `go mod init <nome-do-projeto>`. O arquivo gerado, guarda as informações como: nome do projeto, versão utilizada do Go, nome dos pacotes e suas versões utilizadas.

