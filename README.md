# 🕯️ The Final Mercy

> *"O mar guarda segredos que a terra não consegue esconder."*

**The Final Mercy** é um jogo narrativo de suspense desenvolvido em **Portugol**, ambientado em **Desterro, 1823** — o nome histórico de Florianópolis. O jogador desperta em uma cidade sombria, sem memória, sob os cuidados de uma misteriosa mulher chamada Alzira. À medida que investiga a casa e seus segredos, descobrirá que algumas dívidas cobram um preço além do compreensível.

---

## 📚 Sobre o Projeto

Este jogo foi desenvolvido como projeto prático do **Programa Jovem Programador do SENAC**, na fase inicial da trilha de desenvolvimento fullstack com python. O objetivo foi colocar em prática os conceitos aprendidos na fase inicial do programa por meio de um projeto criativo e autoral — provando que lógica de programação pode ser muito mais do que exercícios de console.

> 🔭 **Próximos passos:** à medida que o programa avança, o projeto será portado para **Python**, aproveitando os mesmos fundamentos de lógica em uma linguagem profissional.

---

## 🎮 Como Executar

O jogo roda no **Portugol WebStudio**, um ambiente online gratuito — sem instalação necessária.

1. Acesse [portugol.dev](https://portugol.dev) ou o [Portugol WebStudio](https://portugolstudio.sourceforge.io/)
2. Crie um novo arquivo ou abra o editor
3. Copie e cole o conteúdo do arquivo `The_Final_Mercy.por`
4. Clique em **Executar** (▶)

> ⚠️ **Importante:** use o terminal integrado do WebStudio para que os efeitos de digitação e as pausas dramáticas funcionem corretamente. A experiência foi projetada para ser jogada no console, com atenção à atmosfera.

---

## 🧠 Conceitos de Lógica de Programação Aplicados

| Conceito | Como foi usado |
|---|---|
| **Variáveis e tipos** | `inteiro`, `cadeia` para guardar estado do jogo (suspeita, confiança, opções do jogador) |
| **Estruturas condicionais** | `se/senao` e `escolha/caso` para ramificar diálogos e decisões narrativas |
| **Laços de repetição** | `enquanto` para manter o menu ativo até o jogador realizar todas as ações necessárias; `para` para efeitos de animação |
| **Funções** | Código organizado em funções independentes: `introducao()`, `capitulo1()`, `digitar()`, `animarPontos()`, `animarTocToc()`, `animarPassos()` e outras |
| **Variáveis de estado (flags)** | Variáveis como `perguntouOnde`, `perguntouQuem`, `suspeita` e `confiancaAlzira` controlam o que já aconteceu na narrativa e influenciam os caminhos disponíveis |
| **Bibliotecas externas** | `Util` (para pausas com `aguarde()`) e `Texto` (para manipulação de strings no efeito de digitação) |
| **Escopo de variáveis** | Variáveis globais de estado x variáveis locais dentro das funções |
| **Arte ASCII e saída formatada** | Uso criativo de `escreva()` para criar telas de título, cenários e animações frame a frame |

---

## 🗂️ Estrutura do Código

```
programa
├── Variáveis globais de estado
│   ├── suspeita         → acumula pistas estranhas encontradas
│   ├── confiancaAlzira  → registra quando o jogador acredita em Alzira
│   └── opcao            → captura as escolhas do jogador
│
├── Funções utilitárias
│   ├── limpaTela()      → simula scroll para "limpar" o console
│   ├── pausar()         → pausa com tempo customizável
│   ├── digitar()        → efeito de digitação letra a letra
│   ├── animarPontos()   → reticências dramáticas com tempo
│   ├── animarTocToc()   → sequência sonora de batidas na porta
│   └── animarPassos()   → sons de passos se aproximando
│
└── Funções narrativas
    ├── inicio()         → ponto de entrada: chama introdução e capítulo 1
    ├── introducao()     → tela de título com ASCII art e abertura
    └── capitulo1()      → capítulo jogável com diálogos, escolhas e arte ASCII
```

---

## 🎭 Personagens

- **Você** — o jogador. Acorda sem memória em Desterro, 1823.
- **Alzira** — a mulher que o recolheu da rua. Misteriosa, de luto, com um pedido que não pode esperar.
- **Eulélia** — aparece nas profundezas da narrativa. Sua história é o coração sombrio do jogo.

---

## ✨ Destaques Técnicos

- **Efeito de digitação** implementado manualmente percorrendo a string caractere por caractere com a biblioteca `Texto`
- **Animações ASCII frame a frame** para criar cenas cinematográficas sem recursos gráficos
- **Sistema de flags booleanas** simulado com inteiros (`0` e `1`) para rastrear o progresso do jogador dentro do capítulo
- **Atmosfera sonora** construída inteiramente via timing de pausas e texto

---

## 🏆 Reconhecimento

The Final Mercy foi selecionado entre os projetos finalistas da etapa de votação do **Programa Jovem Programador — SENAC**, encerrando a competição em **4º lugar** entre os jogos desenvolvidos pela turma.

---

## 👩‍💻 Desenvolvedoras

Projeto desenvolvido por alunas do **Programa Jovem Programador — SENAC**

- Maria Luiza Dalsasso

- Nahyara Miranda

- Raphaela Samuel


---

## 🔮 Roadmap

- [x] Versão completa em Portugol
- [ ] Port para Python (em andamento conforme avanço do programa)
- [ ] Expansão dos capítulos
- [ ] Sistema de múltiplos finais baseado nas variáveis de estado

---

*Desterro, 1823. Algumas casas envelhecem com o tempo. Outras apodrecem por dentro.*
