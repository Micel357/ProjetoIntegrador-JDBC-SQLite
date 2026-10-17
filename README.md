# Projeto Integrador — JDBC e SQLite

Repositório reservado para um projeto Java com JDBC e SQLite.

**Estado atual:** a estrutura de código e testes está preparada, mas ainda não há classes Java, testes executáveis, arquivo de build ou banco de dados versionados.

## Estrutura

```text
.
├── src/
│   ├── main/java/       # Classes Java futuras
│   └── test/java/       # Testes Java futuros
├── tests/               # Orientação para testes
├── docs/                # Decisões e documentação técnica
├── config/              # Exemplos de configuração futuros
├── data/                # Orientação para dados locais SQLite
├── .gitignore
└── README.md
```

Quando a implementação começar, mantenha o arquivo de dependências na raiz conforme a ferramenta escolhida, como `pom.xml` para Maven ou `build.gradle` para Gradle. Não versione bancos `.db` gerados localmente.
