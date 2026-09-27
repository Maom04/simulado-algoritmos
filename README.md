# Simulado de Algoritmos

Site estático de revisão para a prova de Algoritmos: quatro simulados com dez questões inéditas cada, correção explicada, revisão de erros, modo estudo e consulta rápida. Baseado nos três materiais fornecidos para a disciplina. As questões objetivas praticam os mesmos conteúdos; a prova original também contém respostas discursivas e escrita de algoritmos.

## Tecnologias e arquivos

HTML, CSS e JavaScript puro. `index.html` contém a estrutura; `style.css` define o visual responsivo; `questions.js` armazena as questões; `script.js` controla a interface, correção e progresso.

## Executar e editar

Abra `index.html` no navegador ou rode `python3 -m http.server 8000` nesta pasta e acesse `http://localhost:8000/`. Edite as questões em `questions.js`: cada simulado tem dez objetos, com quatro alternativas; `correta` usa índice de 0 (A) a 3 (D). Confira os cálculos e explicações após qualquer edição.

## Publicar no GitHub Pages

No repositório, abra **Settings → Pages → Build and deployment**, escolha **Deploy from a branch**, selecione `main` e `/ (root)` e salve. Aguarde o endereço informado pelo GitHub; será semelhante a `https://maom04.github.io/simulado-algoritmos/`. Todos os caminhos de arquivos são relativos à raiz do projeto.

Não há login, servidor de dados nem coleta pessoal. O melhor resultado de cada simulado fica apenas no `localStorage` do navegador usado.
