# Site de memória do teu gatinho 🐾

Este é um site de uma só página (`index.html`), pronto a publicar no GitHub Pages.

## 1. Substituir as fotos

Cria uma pasta `fotos/` (já vem criada) e coloca lá as tuas imagens **com estes nomes exatos**:

| Ficheiro                 | Onde aparece                          |
|---------------------------|----------------------------------------|
| `fotos/capa.jpg`          | Foto grande do topo (hero)             |
| `fotos/como-era.jpg`      | Secção "Como era"                      |
| `fotos/chegada.jpg`       | Secção "De onde veio"                  |
| `fotos/momento-1.jpg` a `momento-7.jpg` | Galeria "Os nossos momentos" |

Não precisas de editar código — é só guardar a foto com o nome certo dentro da pasta `fotos/`.
Se quiseres mais ou menos fotos na galeria, copia ou apaga blocos `<figure class="ph ...">` dentro do `index.html` (procura por `momento-`).

## 2. Substituir os textos

Abre o `index.html` num editor de texto simples (Bloco de Notas, VS Code, etc.) e procura por tudo o que está entre parênteses retos `[ ]` — são os textos a preencher:

- `[Nome do Gatinho]` — aparece várias vezes, incluindo no `<title>`
- `[dd/mm/aaaa] — [dd/mm/aaaa]` — datas de chegada e de partida
- Os parágrafos de "Como era" e "De onde veio"
- A frase de destaque (`blockquote`)
- As legendas opcionais da galeria (`figcaption`)
- A frase final de despedida

Dica: usa "localizar e substituir" do teu editor para trocar `[Nome do Gatinho]` pelo nome real de uma vez.

## 3. Publicar no GitHub Pages

1. Cria um repositório novo no GitHub (pode ser privado ou público).
2. Carrega estes dois ficheiros e a pasta `fotos/` para o repositório (arrastar e largar na página do GitHub funciona, ou via Git).
3. Vai a **Settings → Pages**.
4. Em "Source", escolhe a branch `main` e a pasta `/ (root)`.
5. Guarda. Ao fim de um ou dois minutos, o GitHub mostra-te o link do site (algo como `https://teu-utilizador.github.io/nome-do-repositorio/`).

Pronto — o site fica online e podes partilhar o link com quem quiseres.

## Notas

- O design usa uma "mancha de luz" que se move lentamente enquanto navegas na página — uma referência ao sítio de sol que todos os gatos procuram.
- Tudo é responsivo (funciona bem em telemóvel).
- Se preferires, também posso ajudar a preencher os textos por ti — basta enviares-me a informação (nome, como era, de onde veio) e eu escrevo o texto final.
