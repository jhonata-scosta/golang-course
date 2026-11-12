🚀 Jornada de Estudos: Engenharia de Software com Go (Golang)

📌 Sobre o Repositório

Este repositório é o meu diário de bordo (Learning Tracker) focado no desenvolvimento Back-end utilizando a linguagem Go. O objetivo não é apenas aprender a sintaxe, mas dominar a criação de sistemas escaláveis, performáticos e resilientes.

O plano de estudos documentado aqui foi desenhado com base no Roadmap Oficial de Go (referência: golang.pdf) e está diretamente alinhado com as anotações teóricas e práticas de arquitetura que mantenho no meu material de Engenharia de Software.

🗺️ Mapa de Progresso (Roadmap)

Aqui está a ementa detalhada do meu caminho de aprendizado. Marcadores com [x] indicam módulos já concluídos ou em andamento.

🧱 Módulo 1: Fundamentos da Linguagem

[x] Introdução e Setup: Comandos básicos (go run, go build, go env).

[-] Variáveis e Tipos Básicos: Declarações, Zero Values, Tipos Numéricos e Strings.

[ ] Controle de Fluxo: if-else, switch, e o laço universal for (incluindo for range).

[ ] Ponteiros Básicos: Gerenciamento direto de memória e passagem por referência.

📦 Módulo 2: Estruturas de Dados Compostas e Funções

[ ] Arrays e Slices: Capacidade, crescimento, e a função make().

[ ] Maps: Chave-valor e o "Comma-Ok Idiom".

[ ] Structs: Agrupamento de dados, Struct Tags (JSON) e Embedding.

[ ] Funções Avançadas: Closures, Retornos Múltiplos, Funções Anônimas e Variádicas.

🏗️ Módulo 3: Métodos, Interfaces e Generics

[ ] Métodos: Receivers por valor vs. Receivers por ponteiro.

[ ] Interfaces: Duck typing, Type Assertions e Type Switches.

[ ] Generics: Funções e Tipos genéricos, Type Constraints.

🛡️ Módulo 4: Organização de Código e Tratamento de Erros

[x] Módulos (go mod): Gerenciamento de pacotes e dependências de terceiros.

[ ] Tratamento de Erros: A interface error, encapsulamento (wrapping) e Sentinel Errors.

[ ] Panic & Recover: Lidar com falhas críticas e Stack Traces.

⚡ Módulo 5: Concorrência (O Superpoder do Go)

[ ] Goroutines: Execução assíncrona leve.

[ ] Channels: Comunicação segura entre processos (Buffered vs Unbuffered).

[ ] Sincronização: WaitGroups e Mutexes (Prevenção de Race Conditions).

[ ] Pacote Context: Gerenciamento de prazos (Deadlines) e cancelamentos.

[ ] Padrões de Concorrência: Worker Pools, Fan-in, Fan-out e Pipelines.

🧪 Módulo 6: Testes, Qualidade e Ferramentas

[ ] Testes Nativos (testing): Table-driven Tests, Mocks e Cobertura (Coverage).

[ ] Benchmarks: Medição de performance.

[ ] Toolchain: go fmt, Linters (golangci-lint) e Race Detector.

🌐 Módulo 7: Ecossistema Back-end e Web

[ ] Biblioteca Padrão: Trabalhando direto com net/http e encoding/json.

[ ] Frameworks e Roteadores: Gin / Fiber / Echo (Opcional, foco no nativo primeiro).

[ ] Banco de Dados: Acesso via ORM (GORM) ou pacotes nativos (pgx).

[ ] Criação de CLIs: Ferramentas de terminal (Cobra, bubbletea).

🚀 Módulo 8: Tópicos Avançados e Deploy

[ ] Gerenciamento de Memória: Garbage Collection e Escape Analysis.

[ ] Performance: Profiling com pprof e Tracing.

[ ] Build & Deploy: Cross-compilation para deploy em diferentes sistemas operacionais.

🧠 Teoria e Arquitetura

A teoria não fica separada do código. As decisões de arquitetura e padrões de projeto aplicados nos exercícios deste repositório possuem base teórica fundamentada no meu documento base, o arquivo Engenharia de Software, com foco em Pensamento Sistêmico e Visão de Produto.

🛠️ Padrões de Colaboração (Commits)

Este repositório simula um ambiente profissional, utilizando Commits Semânticos para contar a história do aprendizado:

study: Aplicação de um novo conceito da linguagem.

feat: Construção de uma nova funcionalidade (ex: uma nova rota na API).

docs: Adição de resumos ou atualização deste README.

fix: Correção de bugs encontrados durante o desenvolvimento.

refactor: Melhoria de código (ex: otimizando concorrência).