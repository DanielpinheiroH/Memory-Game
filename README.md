Um jogo da memória simples e divertido, desenvolvido em React com Hooks (useState, useEffect).
Clique nas cartas para revelar as imagens e encontre todos os pares combinando!

🚀 Tecnologias utilizadas
✅ React (com Hooks)
✅ CSS Grid
✅ JavaScript ES6+
✅ Animações simples

 Estrutura do projeto
bash
Copiar
Editar
/src
 └── App.jsx         # Código completo do jogo
 └── index.js        # Ponto de entrada React
 └── App.css         # Estilo do jogo
/public/img/
 └── helmet.png
 └── potion.png
 └── ring.png
 └── scroll.png
 └── shield.png
 └── sword.png
 └── cover.png       # costas da carta

 1️⃣ Projeto criado com Vite:

bash
Copiar
Editar
npm create vite@latest react-memory-game --template react
cd react-memory-game
npm install
2️⃣ Lógica implementada:

✅ Estado para cartas (cards)
✅ Estado para turnos (turns)
✅ Estado para escolhas (choiceOne, choiceTwo)
✅ Embaralhamento das cartas
✅ Verificação de par
✅ Reset de jogada
✅ Novo jogo

3️⃣ Interface criada com:

✅ Grid responsivo de cartas
✅ Animação de virar carta
✅ Botão "Novo Jogo"
✅ Contador de turnos

🕹️ Como jogar
1️⃣ Clique em uma carta para revelá-la
2️⃣ Clique em outra carta
3️⃣ Se combinarem → permanecem viradas
4️⃣ Se não → voltam a ficar fechadas após um tempo
5️⃣ O jogo termina quando todas as cartas forem combinadas
6️⃣ Use o botão "🔄 Novo Jogo" para reiniciar o jogo

⚙️ Como rodar o projeto
1️⃣ Clone o repositório
bash
Copiar
Editar
git clone https://github.com/seu-usuario/react-memory-game.git
cd react-memory-game
2️⃣ Instale as dependências
bash
Copiar
Editar
npm install
3️⃣ Rode em modo desenvolvimento
bash
Copiar
Editar
npm run dev
Acesse no navegador:

arduino
Copiar
Editar
http://localhost:5173
📋 Melhorias futuras (To Do)
Timer regressivo

Sons de clique e acerto

Animação de vitória quando terminar o jogo

Seleção de nível (fácil, médio, difícil)

Ranking de pontuação (recordes)

Modo multiplayer

📜 Licença
Projeto criado para fins de aprendizado de React + Hooks.
Você pode usar e modificar como quiser. 🚀

