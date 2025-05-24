# resumo-do-lab-microsoft-azure-dio
 Resumo contendo lições aprendidas durante o desenvolvimento do labotatório do curso microsoft azure


Durante a introdução, nos foi apresentado como criar uma conta gratuita no Azure para podermos efetuar as atividades de forma prática e não somente teórica. Logo depois disso, nos foi introduzido o conceito de computação em nuvem.

O conceito de computação na nuvem é fornecer serviços pela internet, fazendo assim, inovações mais rápidas com recursos mais flexíveis.

Existem três tipos de computação em nuvem: As privadas, as públicas e as híbridas. Além desses três existe um quarto tipo de computação em nuvem.

As nuvens privadas são de responsabilidade da empresa ou organização que está utilizando. Elas mesmas criam seu próprio ambiente em nuvem. Elas são responsáveis por manter e atualizar os serviços por ela fornecidos e não permite acesso para usuários fora da empresa.
As nuvens públicas são de responsabilidade da fornecedora, como a Microsoft, por exemplo. Também fornece recursos para várias organizações e usuários e também é acessada via conexão de rede segura.
As nuvens híbridas são o melhor dos dois tipos. Ela combina nuvens públicas e privadas para permitir que os aplicativos sejam executados no local mais adequado.

- Comparação 

A nuvem pública não tem nenhuma despesa de capital para escalar verticalmente, os aplicativos podem ser provisionados e desprovisionados rapidamente e as organizações pagam pelo o tempo e pelo o que utilizam.
Já na nuvem privada, as organizações tem controle total sobre os recursos e a segurança, além de serem responsáveis pela manutenção e pelas atualizações do hardware.
Enquanto na nuvem híbrida, as organizações determinam onde executar seus aplicativos, controlam a segurança e ainda possuem maior flexibilidade.

- Despesas 

Despesa de capital (CapEx):
 É o gasto inical de dinheiro em infraestrutura física.
 As despesas do CapEx têm um valor que se reduz com o tempo.
Despesa operacional (OpEx):
 Gastar com produtos e serviços conforme necessário, pagamento conforme o uso.
 Cobrança imediata.

Além de tudo isso, no laboratório, fomos introduzidos à interface do microsoft azure, aprendemos a personalizar o portal do jeito que preferirmos, fomos apresentados aos recursos e serviços do microsoft azure.


# Criando uma máquina virtual

 Para criar uma máquina virtual, é necesssário clicar no ícone escrito "Máquinas virtuais"
 ![image](https://github.com/user-attachments/assets/c9dbb847-5948-46c8-b592-9e1160e491d4)
 depois disso, clicar em "criar"
 ![image](https://github.com/user-attachments/assets/55f30e57-7440-4422-834a-5b4254c19503)

 agora basta preencher os detalhes para criar sua máquina virtual pelo azure! Lembrando que é necessário selecionar quantas zonas de dispoibilidade você irá utilizar. O próprio microsoft Azure nos diz se há uma possibilidade de criar de uma maneira melhor nossas máquinas virtuais, como no caso de ter múltiplas zonas de disponibilidade.



# Configurando uma instância de Banco de Dados no Microsoft Azure

 Para isso, precisamos ir ao portal dos serviços do microsoft azure e clicar no recurso da guia, do lado esquerdo, escrito "Banco de dados SQL" ![image](https://github.com/user-attachments/assets/374d58c7-8a4d-4259-902a-604d1348b1c9)
Clicar em "criar" e preencher os detalhes do banco de dados, como nome e servidor (no caso do servidor, você pode criar um servidor), logo depois clicar em "Revisar + criar" ![image](https://github.com/user-attachments/assets/00a278b4-2222-4de7-bf56-24002360ec65)


# Criando um grupo de recursos

 Para isso, basta pesquisar na barra de pesquisa no topo da página por "grupo de recursos" e selecionar a opção que aparece. Depois disso, preencher as informações e seu grupo de recursos estará criado.

 - Recurso Rede Virtual
    Para criar uma rede virtual basta pesquisar por Rede Virtual na barra de pesquisa, selecionar a opção correspondente e, assim, preencher as informações. Automáticamente o recurso será criado para o grupo de recursos que você acabou de criar.


# Máquinas virtuais

 aqui nós podemos escolher entre um ambiente de teste e um ambiente de produção para nossas máquinas virtuais, além disso, o tipo de carga, como usual, otimizado para memória ou computação otimizada, cada uma com seus beneficios. Depois disso, você deve preencher os detalhes da instância para poder criar sua máquina virtual. Preenchendo os detalhes, você deve preencher o nome, qual região ficará, quais as zonas de disponibilidade e quantas. Logo depois, configurar o tamanho de disco. Depois de configurar o disco, precisamos configurar a rede virtual. Depois o gerenciamento, com a parte de indentidade, o desligamento automático, backup, atualizações. Depois o monitoramento. Depois as opções avançadas, as tags e finalmente podemos criar a máquina.

--

# Análise de Sentimentos com Language Stduio no Azure AI
 IA: sempre lembrar que IA é um repositório de informação.
- Language Studio
 Análise de texto: Através do language studio podemos criar um projeto que detecta a linguagem predominante, o sentimento que há na frase e as frases-chave.
Exemplo:  ![image](https://github.com/user-attachments/assets/e5fcb2a3-cd40-46e2-b7a6-84df300bc3af)
Podemos inserir perguntas e respostas, fornecer um documento com perguntas frequentes e existentes e usando um bate-papo integrado (chat gpt), assim fornecendo dados e conhecimento para nossa IA.

- Serviço de bot do Azure
  É mais eficiente conforme a base de dados. O bot, através da IA, vai fornecer a resposta para o usuário com base nas frases-chave. Lembrar de sempre testar a base de dados da IA.
  É uma plataforma baseada em nuvem, tem integração com AI Language e outros serviços e possui conectividade com vários canais.
  É muito útil para "filtrar" dúvidas comuns e levar apenas casos especificos e não genéricos para atendentes profissionais.

- Compreensão da linguagem coloquial
  Dialogo do dia a dia, sem formalidade. Para a compreensão da IA sobre a linguagem do nosso dia a dia podemos separar em três componentes principais, a declaração do enunciado, a entidade (o item que vai ser reconhecido) e a intenção, sendo a identificação do que queremos que a IA nos responda
- Reconhecimento e síntese da fala
  Usa recursos de fala para texto e transcreve fala audível em texto (Possui esse serviço no Azure como *Fala*). Também para converter texto em fala para gerar fala audível a partir de texto.

# Mineração de conhecimento
-  Encontrar palavras e frases chave no meio dos dados/informações para conseguir otimizar a coleta de dados. A Azure cognitive Search é a plataforma de mineração de conhecimento alimentada por AI do azure.
-  Ingestão de dados: ![image](https://github.com/user-attachments/assets/f226ae58-d5fd-424d-9ce0-9e88c7bcc7a7)
-  Enriquecimento (vetorizar as informações para permitir ser pesquisável mais fácilmente): ![image](https://github.com/user-attachments/assets/71a7d1cc-4849-4343-8efd-45d1f6674426)
-  Explorar: ![image](https://github.com/user-attachments/assets/8bdcbe6d-0744-4db3-a3cd-f14e58990d43)
O enriquecimento de IA torna o conteúdo mais útil para fins de pesquisa.
![image](https://github.com/user-attachments/assets/82792f2e-5b38-4ef0-8918-74dcf934d30f)
![image](https://github.com/user-attachments/assets/01dc3cb2-9f56-4b30-a493-1645950a50f1)


# LAB
 Primeiro criamos um novo AI Azure Search e depois selecionamos a oferta Basica, logo após isso selecionamos o grupo de recursos, damos o nome para o recurso, colocamos a localização e clicamos em review + create. Agora criamos um recurso de machine learn, criando um recurso novo de serviços do Azure AI, com os mesmos passos de sempre, colocando o grupo de recursos, o nome, a região e o tipo de oferta. Também precisamos criar uma conta de armazenamento e preenchemos os dados dela, com nome, grupo de recursos, região, performance e redundância (modelo de réplica dos dados). Após criarmos um novo container na account storage colocamos alguns documentos para sevir como dados para alimentar nossa estrutura. Indo no AI Search nós importamos os dados do nosso account storage, precisamos apontar aonde está esse lugar. E agora podemos fazer uma busca por automação.
 


