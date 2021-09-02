## Trabalho II - Reinforcement Learning - Treinamento e Validação de Modelos de RL

FURB - Pós Graduação em Data Science<br/>
Reinforcement Learning<br/>
Aluno: Felipe Eduardo Gomes<br/><br/>

Neste trabalho vamos aplicar Gym, Stable-Baselines3 e RL Baselines Zoo para lidar com o treinamento e validação de problemas de aprendizado por reforço. Sua tarefa é: <br/><br/>

1. Selecionar um cenário da biblioteca `Gym` de sua preferência, desde que este cenário também seja contemplado pelos modelos disponibilizados na `rl baselines zoo`;<br>
R: Para o trabalho, escolhi utilizar o LunarLander-v2.<br><br>

2. Selecionar três algoritmos das biblioteca `Stable-baselines3` para resolver esse problema. Pesquise na documentação da biblioteca quais são os algoritmos mais adequados para o ambiente escolhido e justifique a sua escolha.<br>
R: Foram escolhidos os seguintes algoritmos: POO, A2C e DQN.<br><br>

3. Realize o treinamento de cada um dos três modelos ---você pode ajustar os parâmetros do modelos, se achar necessário--- e salve os modelos em disco.<br>
R: Os três modelos treinados estão na pasta "models".<br><br>

4. De posse dos modelos treinados e salvos, carregue-os e avalie-os por 10 episódios. Apresente os resultados médios e gere a curva de recompensa acumulada disponibilizada pelo `TensorBoard`.<br>
R: Os resultados e os gráficos foram gerados na pasta "tensorboard".<br><br>

5. Compare os resultados dos modelos treinados com os resultados obtidos por modelo(s) existentes no `RL Baselines Zoo` para o cenário escolhido.<br>
R: Os resultados do treinamento foram gerados na pasta "tensorboard".<br><br>

6. Gere um vídeo do melhor modelo que você treinou e do modelo escolhido na `RL Baselines Zoo`. Verifique a documentação de cada biblioteca sobre a criação do vídeo e visualização em Notebooks.<br>
R: Os vídeos foram gerados estão disponíveis na pasta "videos".<br><br>
