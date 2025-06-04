# Resumo do que aprendi no lab – Criando máquina virtual no Azure

Neste lab, avancei no entendimento da plataforma Azure com foco em dois temas fundamentais: **SLA (Service Level Agreement)** e a criação de **máquinas virtuais**. Abaixo estão os principais aprendizados:

##  Entendimento sobre o SLA (Service Level Agreement)
- Compreendi que o SLA representa o compromisso da Microsoft com a **disponibilidade mínima garantida** de um serviço.
- Aprendi que **combinar recursos** (como múltiplas instâncias e zonas de disponibilidade) pode **aumentar o SLA**, garantindo mais confiabilidade para aplicações em produção.
- Também entendi que, para garantir o SLA informado, é preciso seguir **boas práticas de arquitetura** e usar os recursos conforme documentado.

##  Acesso à tela de criação de máquina virtual
- Naveguei até a tela de **criação de uma máquina virtual** no portal do Azure.
- Explorei as opções do painel, incluindo:
  - Grupo de recursos
  - Região
  - Tipo de imagem (sistema operacional)
  - Tamanho da máquina (CPU, RAM)
  - Nome da VM, autenticação (senha ou chave SSH)
- Aprendi que é possível **clicar nos ícones de informação** ao lado dos campos para entender o que cada um faz antes de preencher.

##  Configurações que impactam o custo
- Fui alertado sobre como **determinadas configurações podem aumentar os custos** da infraestrutura:
  - Escolher tamanhos de máquina maiores ou com muitos recursos
  - Adicionar discos premium ou SSDs desnecessários
  - Usar regiões com preços mais altos
  - Manter máquinas ligadas sem necessidade
- Entendi a importância de **planejar bem os recursos** para evitar surpresas na fatura.

