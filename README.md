# [DIO](www.dio.me) - Trilha Java Básico

## POO - Desafio

### Modelagem e Diagramação de um Componente iPhone

Neste desafio, modelei e fiz o diagrama da representação UML do componente iPhone, abrangendo suas funcionalidades como Reprodutor Musical, Aparelho Telefônico e Navegador na Internet.

#### Funcionalidades Modeladas
1. **Reprodutor Musical**
   - Métodos: `tocar()`, `pausar()`, `selecionarMusica(String musica)`
2. **Aparelho Telefônico**
   - Métodos: `ligar(String numero)`, `atender()`, `iniciarCorreioVoz()`
3. **Navegador na Internet**
   - Métodos: `exibirPagina(String url)`, `adicionarNovaAba()`, `atualizarPagina()`

### Objetivo
1. Criar um diagrama UML que represente as funcionalidades descritas acima.
2. Implementar as classes e interfaces correspondentes em Java (Opcional).

### Diagrama UML By Geovanna Capinan (Mermaid)
```mermaid
classDiagram
 class ReprodutorMusical {
    + tocar(): void
    + pausar(): void
    + selecionarMusica(musica: String): void
}

class AparelhoTelefonico {
    + ligar(numero: String): void
    + atender(): void
    + iniciarCorreioVoz(): void
}

class NavegadorInternet {
    + exibirPagina(url: String): void
    + adicionarNovaAba(): void
    + atualizarPagina(): void
}

class iPhone {
    iPhone --> ReprodutorMusical
    iPhone --> AparelhoTelefonico
    iPhone --> NavegadorInternet
   }

```

