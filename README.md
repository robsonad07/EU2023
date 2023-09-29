# EU2023
## Para reproduzir o trabalho do seguinte repositório https://github.com/janael-pinheiro/Adaptive_Packet_Padding_Approach_for_Smart_Home_Networks_A_Tradeoff_Between_Privacy_and_Performance, siga os seguintes passos:
  1. Comece configurando o experimento editando o arquivo "Data/Configuration/experimentConfiguration.json". Defina o tipo de preenchimento (Proposta ou Existente) e escolha a estratégia de preenchimento entre as opções disponíveis.
  2. item Em seguida, prepare os recursos iniciais usando o script "prepare\_features.py". Certifique-se de configurar 'padding' e 'paddingStrategy' como 'None' no arquivo de configuração para gerar recursos relacionados ao tráfego IoT original.
  3. Atualize o arquivo de configuração com os detalhes específicos da estratégia de preenchimento.
  4. Organize os resultados do experimento executando o script ``createsFolderStructure.py" para criar a estrutura de pastas necessárias.
  5. Implemente a estratégia de preenchimento escolhida, seguindo as instruções nos scripts "proposal.py" e "existingStrategies.py", e execute o script correspondente.
  6. Utilize novamente o script "prepare\_features.py" para extrair características relacionadas ao comprimento dos pacotes para cada estratégia.
  7. Por fim, compare os resultados das diferentes estratégias executando o script "padding\_strategies\_evaluation.py"
## Seguindo essas instruções, você poderá reproduzir o trabalho desenvolvido por  [Pinheiro et al. 2021].
