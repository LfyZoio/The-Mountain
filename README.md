
# 🏔️ The Mountain

> Um jogo independente de alpinismo em 3D, no qual cada metro conquistado aproxima você do cume.

**Status:** protótipo em desenvolvimento  
**Plataforma da implementação descrita:** Web  
**Stack principal:** TypeScript e Three.js

---

## 🎮 Sobre o projeto

**The Mountain** é um projeto de jogo de escalada e sobrevivência em terceira pessoa.

O objetivo é alcançar o topo de uma montanha, enfrentando a dificuldade do terreno, os riscos da altitude e os limites físicos do personagem.

A proposta combina exploração, escolha de rotas, gerenciamento de recursos e uso de equipamentos de alpinismo. Mais do que subir, o jogador precisa planejar seus movimentos e avaliar os riscos de continuar a escalada.

O projeto possui identidade própria e não depende do Roblox.

---

## 🧗 Escopo do jogo

O desenvolvimento foi planejado em etapas, começando pela base de movimentação e escalada e avançando para os sistemas de sobrevivência, exploração e progressão.

### Movimentação e escalada

- Personagem controlado em terceira pessoa.
- Câmera para acompanhar a movimentação e observar o ambiente.
- Escalada em superfícies apropriadas.
- Pontos de apoio para mãos e pés.
- Sistema de stamina.
- Mecânicas de aderência, equilíbrio e risco de queda.
- Transição entre caminhada, escalada e passagem por obstáculos.
- Checkpoints e acompanhamento de altitude.

### Exploração e ambiente

- Montanha com diferentes regiões e dificuldades.
- Áreas rochosas, florestas, neve e gelo.
- Penhascos, cavernas e caminhos alternativos.
- Regiões de altitude elevada.
- Vento e mudanças nas condições climáticas.

### Sobrevivência e equipamentos

- Gerenciamento de esforço e energia.
- Temperatura corporal e exposição ao frio.
- Equipamentos adequados para diferentes terrenos.
- Cordas e ferramentas de escalada.
- Recuperação de stamina e momentos de descanso.

### Progressão

- Estatísticas de escalada.
- Registro de tempo.
- Conquistas.
- Equipamentos desbloqueáveis.
- Evolução dos desafios ao longo da subida.

> Os itens desta seção representam o escopo planejado. A disponibilidade de cada sistema depende da versão do projeto e não significa que todos estejam concluídos.

---

## 🛠️ Tecnologias e recursos utilizados

| Tecnologia ou abordagem | Aplicação |
|---|---|
| **TypeScript** | Organização e implementação da lógica do jogo |
| **Three.js** | Construção e renderização da cena 3D no navegador |
| **Geometria procedural** | Construção do personagem low-poly por código |
| **Rig procedural** | Estrutura de articulação e movimentação do personagem descrita no desenvolvimento |
| **Módulos de jogo** | Separação de responsabilidades, como personagem e rig |
| **`package.json`** | Declaração das dependências e dos scripts do projeto |

### Por que essa abordagem?

A combinação de TypeScript e Three.js permite desenvolver uma experiência 3D para navegador com controle direto sobre a cena, a câmera, os objetos e os sistemas do jogo.

A organização em módulos facilita a evolução do protótipo e a manutenção das diferentes mecânicas.

As versões e a lista completa de bibliotecas devem ser consultadas no `package.json` e no arquivo de lock do projeto.

---

## 🧍 Personagem e animações

A base descrita no desenvolvimento utiliza um personagem **low-poly procedural**, construído com formas geométricas no Three.js.

As referências visuais fornecidas em `.webp` são imagens e não substituem um arquivo de modelo 3D com malha, esqueleto e animações.

A evolução do personagem prevê:

- Integração do modelo 3D definitivo.
- Preservação da identidade visual, roupas e equipamentos.
- Preparação de um rig humanoide.
- Animações de idle, caminhada, corrida e escalada.
- Transições entre estados de movimento.
- Apoio de mãos e pés por meio de IK.
- Movimentação dos equipamentos junto ao corpo.

A existência de um modelo original importado, skinning completo e biblioteca definitiva de animações deve ser validada nos arquivos da versão utilizada.

---

## 📥 Como baixar

### Opção 1 — Download pelo GitHub

1. Acesse a página do repositório.
2. Clique em **Code**.
3. Selecione **Download ZIP**.
4. Extraia os arquivos em uma pasta no computador.

### Opção 2 — Clonar com Git

Substitua `SEU_USUARIO` e `SEU_REPOSITORIO` pelos dados corretos:

```bash
git clone https://github.com/SEU_USUARIO/SEU_REPOSITORIO.git
cd SEU_REPOSITORIO
```

> Baixar o código-fonte não equivale a baixar um executável pronto. Para executar o projeto web localmente, siga as instruções abaixo.

---

## 🚀 Como executar localmente

### Pré-requisitos

- Node.js em uma versão compatível com o projeto.
- npm, caso seja o gerenciador utilizado pelo repositório.
- Navegador atualizado com suporte a gráficos 3D.
- Git, caso prefira clonar o repositório.

### 1. Instalar as dependências

Dentro da pasta do projeto:

```bash
npm install
```

Se o repositório utilizar outro gerenciador de pacotes, siga o gerenciador e o arquivo de lock adotados pelo projeto.

### 2. Consultar os comandos disponíveis

```bash
npm run
```

Esse comando lista os scripts definidos no `package.json`.

### 3. Iniciar o ambiente de desenvolvimento

Se houver um script chamado `dev`, execute:

```bash
npm run dev
```

Depois, abra no navegador o endereço informado pelo terminal.

> O comando de inicialização e a porta dependem da configuração real do projeto. Consulte a seção `scripts` do `package.json`.

### Executar no Windows

A implementação descrita é uma aplicação web e pode ser executada pelo navegador, com as dependências instaladas.

Uma versão nativa em `.exe` ou um instalador para Windows não está documentada neste README.

---

## 📦 Gerar uma build

Confira os scripts disponíveis:

```bash
npm run
```

Se o projeto definir um script `build`:

```bash
npm run build
```

A pasta de saída e a forma de publicar a aplicação dependem da ferramenta de build configurada no repositório.

---

## 🗺️ Próximas etapas

- Validar o ciclo principal de movimentação e escalada.
- Refinar câmera, colisões e interação com o terreno.
- Ajustar stamina, aderência e dificuldade das rotas.
- Integrar e validar o personagem definitivo.
- Melhorar animações e transições de movimento.
- Expandir ambiente, clima e sobrevivência.
- Documentar os controles da versão disponível.
- Otimizar o desempenho em diferentes computadores.
- Avaliar uma distribuição própria para Windows.

---

## 🤝 Contribuições

Sugestões, relatos de problemas e melhorias são bem-vindos.

Para relatar um problema, abra uma **issue** informando:

- O comportamento esperado.
- O que aconteceu.
- Como reproduzir o problema.
- Navegador e sistema operacional utilizados.
- Capturas de tela ou mensagens de erro, quando possível.

Para propor alterações:

1. Faça um fork do repositório.
2. Crie uma branch para sua mudança.
3. Implemente e teste a alteração.
4. Abra um Pull Request explicando o que foi modificado.

---

## 📄 Licença e créditos

**Licença:**
