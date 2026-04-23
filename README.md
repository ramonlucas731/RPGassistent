🍺 Bem-vindo à Taverna  

# RPGassistent
Um assistente virtual que irá auxiliar o usuário na criação de um personagem para jogar **RPG(D&amp;D,5E)**.  
Acesse aqui 👉[Link de acesso para meu NotebookLM](https://notebooklm.google.com/notebook/7fcdc5d1-c0a7-4cea-80f1-e30c7d5b0c1e)


* 📚**Contexto e Objetivos:** Desenvolvi este assistente no NotebookLM para auxiliar na criação de personagens em campanhas de D&D. Notei que jogadores iniciantes frequentemente enfrentam dificuldades ao preencher fichas e tomar decisões iniciais. O assistente atua sanando dúvidas, oferecendo sugestões criativas e corrigindo erros comuns no processo de montagem de personagens, tornando a experiência mais fluida para todos. Ele também age como um atendente de taberna, agindo de maneira que o usuário se acostume com o roleplay do mundo medieval.


* **Curadoria de Fontes**:  

Classes D&D⚔️  

[Vídeo de Classes 1](https://www.youtube.com/watch?v=X5EWTy-EdG0)  

[Vídeo de Classes 2](https://www.youtube.com/watch?v=v1LNHwuOapk)  

Raças D&D🐉  

[Vídeo para Raças 1](https://www.youtube.com/watch?v=tfG17h2J7kw)  

[Vídeo para Raças 2](https://www.youtube.com/watch?v=Ia6TGAcIYgY)  

Universo📖  

[Vídeo explicando o universo de D&D](https://www.youtube.com/watch?v=cRzFcCFYlG0)

* **Engenharia de Prompts e "Cicatrizes🛠️"**: Como ele é um assistente feito para iniciantes ou pessoas indecisas, coloquei o máximo de informações sobre o manual e sobre descrição de pontos básicos como classes, raças e antecedentes. Para testar se ele estava com informações válidas e sem cometer erros eu fiz uma pergunta simples: É possivel criar um mago com Sabedoria e Inteligência 0? 
A resposta dele foi essa:
>"Ah, mestre Ramon, essa é uma pergunta que faria qualquer arquimago derrubar seu cálice de hidromel! Pelas leis que regem o universo de Dungeons & Dragons 5ª Edição, a resposta curta é não, você não pode ter Inteligência ou Sabedoria 0,
Deixe-me explicar o porquê, antes que você tente conjurar um truque e acabe transformando suas próprias botas em queijo:
O Limite Humano (ou Inumano): No sistema de D&D 5e, os valores de atributo para um personagem jogador variam de um mínimo de 3 (que é considerado um valor péssimo) até um máximo inicial de 18 ou 20
. Um valor 0 em qualquer atributo geralmente significa que a criatura está morta ou em um estado de incapacidade total (como um coma ou paralisia completa)"

Além de responder que não, ele explicou de maneira detalhada o porque, evitando que o jogador cometa erros durante a criação do personagem. Fora isso, ele também ajuda a preencher os pontos das fichas baseado nas informações repassadas pelo usuário, como NÍVEL INICIAL.  

* **Resultados finais**📜:  

Os resultados finais obtidos foram satisfatórios pela quantidade de fontes anexadas ao projeto.
O projeto foca em transformar a etapa técnica e, por vezes, complexa da criação de fichas num processo narrativo e fluido.  

**O Problema**: Jogadores iniciantes sentem-se assoberbados pelo volume de regras do Livro do Jogador e pela matemática dos atributos e perícias.  

**A Solução**: Um assistente personalizado no NotebookLM que utiliza o Manual do Jogador como base de conhecimento (RAG), garantindo precisão técnica.  

**A Interface Narrativa**: O uso de um persona (Funcionário da Taverna) permite que o utilizador tome decisões mecânicas através de respostas a perguntas de contexto histórico (roleplay).


* **Glossário de Conceitos Aprendidos**📜 -  

**D&D 5e (Dungeons & Dragons 5ª Edição)**: O sistema de RPG de fantasia mais utilizado no mundo, focado em três pilares: exploração, interação social e combate.  

**RAG (Retrieval-Augmented Generation)**: Técnica de IA que utiliza documentos externos (neste caso, o manual de D&D) para fornecer respostas precisas, evitando "alucinações" do modelo.  

**Ficha de Personagem**: Documento que contém as estatísticas, habilidades, bónus de proficiência e história de um herói dentro do jogo.
Atributos de Base: As seis estatísticas fundamentais (Força, Destreza, Constituição, Inteligência, Sabedoria e Carisma) que definem as capacidades naturais do personagem.  

**Prompt Engineering (Engenharia de Prompt)**: A arte de estruturar instruções para a IA para que ela assuma uma personalidade específica (o Taverneiro) e siga regras rígidas de correção.


* **Conjunto de Prompts Reutilizáveis**📜  

Pode utilizar estes prompts para testar ou atualizar o teu assistente no futuro:  

Prompt de Definição de Persona (System Prompt):
*"Age como um experiente taverneiro de uma estalagem de fantasia. O teu objetivo é ajudar o viajante a preparar-se para a sua jornada (criar um personagem de D&D 5e). Fala de forma imersiva, mas sempre que o utilizador sugerir algo fora das regras do manual fornecido, corrige-o de forma educada dentro da personagem."*  

Prompt para Verificação de Consistência:
*"Com base na classe [Inserir Classe] escolhida pelo utilizador, verifica se as perícias que ele selecionou são permitidas. Se houver um erro, aponta qual é a regra correta segundo o manual e sugere uma alternativa temática."*  

Prompt para Geração de Antecedente (Backstory):
*"O utilizador escolheu a Raça [X] e a Classe [Y]. Gera três opções de ganchos de história curtos que justifiquem por que razão este personagem está atualmente nesta taverna à procura de um grupo de aventureiros."*  

Prompt de Revisão de Atributos:
*"Analisa a distribuição de atributos feita pelo utilizador. Estão de acordo com o método de Standard Array ou Point Buy? Se os valores estiverem acima do permitido, avisa-o de que 'o destino não foi tão generoso assim' e pede para recalcular."*


Obrigado por chegar até aqui!
Espero que este humilde e pequeno projeto possa te ajudar em algo!
