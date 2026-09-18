Quero que você crie um jogo simples para eu aprender coreano, feito preferencialmente em um único arquivo HTML, que eu possa baixar e abrir diretamente no navegador, funcionando offline e sem precisar de servidor.

Objetivo
Meu objetivo inicial é memorizar completamente o Hangul (consoantes, vogais e formas básicas).
Não quero Hanja (chineses) neste projeto. O jogo deve trabalhar apenas com:
- Jamo (consoantes e vogais)
- Romaji
- Português
- Posteriormente, frases simples em coreano

Quero que o jogo seja realmente útil para memorização, usando um sistema que perceba quais caracteres eu mais erro e faça esses caracteres aparecerem novamente com maior frequência (peso adaptativo).

1. Tela inicial
Crie uma interface simples e bonita, sem exagerar.
Na tela inicial, quero poder escolher:
- Jamo (Consoantes e Vogales)
- Frases
(Sem Hanja).

2. Modo Jamo
Quero memorizar as letras do Hangul.
A mecânica principal deve ser invertida em relação ao jogo tradicional de associação.
Em vez de aparecer a letra coreana e eu ter que escolher o romaji, quero que apareça o romaji como pergunta e eu tenha que escolher o Jamo correto.

Exemplo:
No centro da tela:
g
Embaixo aparecem três opções:
ㄱ
ㄴ
ㄷ
Apenas uma é correta. Eu preciso identificar que "g = ㄱ". Isso é importante para aprender a produzir/reconhecer a escrita a partir do som.

3. Controles pelo teclado
Quero conseguir jogar praticamente sem usar o mouse.
As três respostas podem ser selecionadas pelas teclas 1, 2 ou 3.
Ao selecionar uma alternativa, a escolha é confirmada imediatamente.

4. Comportamento após a resposta (Pausar para estudo)
Quando eu selecionar uma opção:
- A tela deve piscar rapidamente em verde (se acertar) ou em vermelho (se errar).
- A cor da borda da alternativa correta/errada deve mudar de destaque.
- O jogo NÃO deve avançar sozinho imediatamente. Deve aparecer um botão centralizado de "Continuar" (ou a possibilidade de apertar Enter/Espaço).
- Isso é fundamental para que eu possa parar, ver o resultado com calma, escrever num caderno, anotar e estudar antes de ir para a próxima questão.

5. Três alternativas e embaralhamento
Sempre devem existir três opções (uma correta e duas incorretas), com as posições embaralhadas aleatoriamente para evitar que eu decore o lugar da resposta.

6. Sistema inteligente de repetição (Pesos)
O jogo deve acompanhar meu desempenho. Cada caractere começa com peso 1. Se eu acerto, o peso diminui um pouco; se eu erro, o peso aumenta bastante, fazendo com que letras difíceis apareçam mais vezes, mas evitando sequências repetitivas excessivas da mesma letra.

7. Modo de Frases
Nesse modo, a pergunta apresenta:
- Primeiro: A frase em romaji.
- Abaixo: A tradução em português como apoio.
E aparecem três alternativas em coreano. Eu escolho a frase coreana correspondente para treinar: som/leitura -> significado -> escrita coreana. As frases devem ser simples e do cotidiano (cumprimentos, comida, verbos básicos, etc.).

8. Estatísticas e Persistência
- Salvar automaticamente todo o progresso no navegador usando localStorage (acertos, erros, pesos e histórico por dias).
- Mostrar contadores de sequência, acertos, erros e porcentagem de precisão.
- Opção para reiniciar o progresso e botão de voltar ao menu.

9. Arquivo único
Tudo deve vir em um único arquivo HTML contendo HTML, CSS, JavaScript e as bases de dados embutidas, para eu poder baixar, dar dois cliques e jogar offline, sem dependências externas.

Faça uma primeira versão funcional, completa e simples, priorizando a estabilidade do código, a clareza visual e o botão de pausa/continuação para estudo.
