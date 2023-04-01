# DevOps Conceitos

<ul>
	<a href="https://github.com/leostella97/conceitosdevops#introdu%C3%A7%C3%A3o"><b>Introdução</b></a>
	<li>
		<a href="https://github.com/leostella97/conceitosdevops#colabora%C3%A7%C3%A3o">Colaboração</a>
	</li>
	<li>
		<a href="https://github.com/leostella97/conceitosdevops#automa%C3%A7%C3%A3o">Automação</a>
	</li>
	<li>
		<a href="https://github.com/leostella97/conceitosdevops#entrega-cont%C3%ADnua">Entrega contínua</a>
	</li>
	<li>
		<a href="https://github.com/leostella97/conceitosdevops#monitoramento-e-feedback">Monitoramento e feedback</a>
	</li>
	<li>
		<a href="https://github.com/leostella97/conceitosdevops#infraestrutura-como-c%C3%B3digo">Infraestrutura como código</a>
	</li>
	<li>
		<a href="https://github.com/leostella97/conceitosdevops#seguran%C3%A7a">Segurança</a>
	</li>
	<li>
		<a href="https://github.com/leostella97/conceitosdevops#microservices">Microservices</a>
	</li>
	<li>
		<a href="https://github.com/leostella97/conceitosdevops#devsecops">DevSecOps</a>
	</li>
	<!-- fim -->
	<!-- menu docker -->
	<a href="https://github.com/leostella97/conceitosdevops#docker"><b>Docker</b></a>
	<li>
		<a href="https://github.com/leostella97/conceitosdevops#come%C3%A7ando-com-o-docker">Começando com o Docker</a>
	</li>
	<li>
		<a href="https://github.com/leostella97/conceitosdevops#download-de-imagens-docker">Download de Imagens Docker</a>
	</li>
	<li>
		<a href="https://github.com/leostella97/conceitosdevops#executar-um-container">Executar um container</a>
	</li>
	<li>
		<a href="https://github.com/leostella97/conceitosdevops#aplica%C3%A7%C3%B5es-no-container">Aplicações no Container</a>
	</li>
	<li>
		<a href="https://github.com/leostella97/conceitosdevops#excluindo-e-renomeando-containers">Excluindo e Renomeando Containers</a>
	</li>
	<li>
		<a href="https://github.com/leostella97/conceitosdevops#copiar-arquivos-para-o-container">Copiar Arquivos para o Container</a>
	</li>
	<li>
		<a href="https://github.com/leostella97/conceitosdevops#tags">TAGs</a>
	</li>
	<li>
		<a href="https://github.com/leostella97/conceitosdevops#cria%C3%A7%C3%A3o-de-um-container-mysql">Criação de um Container MySQL</a>
	</li>
	<li>
		<a href="https://github.com/leostella97/conceitosdevops#parando-e-reiniciando-um-container">Parando e Reiniciando um Container</a>
	</li>
	<li>
		<a href="">Limitando Processamento e Memória</a>
	</li>
	<!-- fim docker -->
	<!-- menu docker swarm -->
	<a href=""> Docker Swarm</a>
	<li>
		<a href="">Cluster com Docker Swarm</a>
	</li>
	<!-- menu k8s -->
	<a href=""><b>Kubernetes</b></a>
	<!-- fim k8s -->
</ul>


## Introdução
DevOps é uma abordagem de <b>desenvolvimento de software</b> que busca integrar as <i>equipes de desenvolvimento e operações para criar, testar e entregar software</i> com <b>mais eficiência e velocidade</b>. A seguir, alguns conceitos importantes relacionados a DevOps:

### Colaboração
A colaboração é um dos <b>conceitos centrais</b> de DevOps. A ideia é que as equipes de <b>desenvolvimento e operações</b> trabalhem juntas desde o <i>início do processo de desenvolvimento, em vez de trabalharem em silos separados</i>. Isso envolve <i>comunicação constante, compartilhamento de informações e trabalho em equipe</i> para alcançar objetivos comuns.

### Automação
A automação é outro <b>conceito chave de DevOps</b>. A ideia é automatizar tarefas repetitivas e manuais, como <i>testes de software, compilação de código e implantação de aplicativos</i>. Isso ajuda a <i>acelerar o processo de desenvolvimento, reduzir erros e aumentar a eficiência</i>.

### Entrega contínua
Entrega contínua é um processo no qual as equipes de desenvolvimento <b>trabalham para garantir</b> que o software possa ser <b>entregue a qualquer momento</b>, em pequenos incrementos, para garantir que as mudanças sejam <i>integradas rapidamente e possam ser testadas</i>. Isso ajuda a garantir que os problemas sejam detectados e resolvidos rapidamente, <b>evitando</b> a acumulação de problemas.

### Monitoramento e feedback
O monitoramento e feedback é um <b>processo importante</b> para DevOps. As equipes <b>devem monitorar</b> o software após a entrega para garantir que ele esteja <b>funcionando corretamente</b>. Qualquer problema encontrado deve ser resolvido o <b>mais rápido possível</b>. O feedback dos usuários também é importante para ajudar a <i>melhorar o software ao longo do tempo</i>.

### Infraestrutura como código
Infraestrutura como código é um <b>conceito</b> em que a infraestrutura de TI é <b>gerenciada como código</b>, permitindo que as equipes de desenvolvimento e operações colaborem na <i>criação, teste e implantação</i> da infraestrutura. Isso ajuda a garantir que a infraestrutura seja <b>consistente e gerenciável</b>.

### Segurança
A segurança é um <b>aspecto crucial</b> em DevOps. As equipes devem incorporar a segurança em todas as etapas do processo de desenvolvimento, <i>desde o design até a implantação</i>. Isso inclui a realização de testes de segurança regulares e a implementação de medidas de segurança em todo o processo.

### Microservices
Os microservices são uma <b>abordagem de arquitetura</b> de software que divide o aplicativo em <i>pequenos serviços independentes</i>, cada um com sua <b>própria funcionalidade</b>. Isso permite que as equipes de desenvolvimento trabalhem em <b>módulos separados</b>, o que torna mais fácil a implementação de <b>alterações e atualizações</b>. Os microserviçes também permitem uma <b>maior escalabilidade e resiliência</b>.

### DevSecOps
DevSecOps é uma <b>extensão</b> de DevOps que incorpora a <b>segurança</b> desde o início do processo de desenvolvimento. Isso envolve a implementação de <b>práticas e ferramentas de segurança</b> em todas as etapas do processo de desenvolvimento, desde o design até a implantação e operações. O objetivo é <i>criar software seguro e confiável desde o início</i>.

### Continuous improvement
A melhoria contínua é outro <b>conceito importante</b> em DevOps. As equipes devem estar sempre buscando maneiras de <b>melhorar o processo</b> de desenvolvimento, identificando áreas que precisam de melhorias e implementando mudanças que permitam <i>acelerar a entrega do software, melhorar a qualidade e aumentar a eficiência</i>.

DevOps é uma <b>abordagem poderosa</b> para o desenvolvimento de software, que permite que as equipes de desenvolvimento e operações trabalhem juntas de forma colaborativa para <i>criar, testar e implantar software de alta qualidade</i>. Implementar uma abordagem DevOps requer a adoção de uma série de <b>conceitos e práticas</b>, incluindo <i>colaboração, automação, entrega contínua, monitoramento e feedback, segurança, microservices, DevSecOps e melhoria contínua</i>.

## Docker
Plataforma de <b>código aberto</b> que permite a <i>criação, implantação e execução de aplicativos</i> em <b>contêineres</b>. Com Docker, é possível empacotar um aplicativo com todas as suas <b>dependências</b> em um contêiner, garantindo que ele funcionará da mesma forma em qualquer ambiente. Isso torna o processo de <b>implantação e gerenciamento</b> de aplicativos <i>mais fácil e eficiente</i>. Além disso, Docker oferece uma variedade de <b>ferramentas e recursos</b> para ajudar no <I>desenvolvimento, teste e implantação de aplicativos em contêineres</I>.

### Começando com o Docker
Para <b>começar</b> com Docker:

<b>• Instale o Docker:</b> Primeiro, você precisa instalar o Docker em sua máquina. Você pode encontrar o instalador do Docker no site oficial, tanto Windows quando Linux. Segue um <a href="https://github.com/leostella97/installDocker">script para instalar no Linux</a>

<b>• Aprenda os conceitos básicos:</b> Depois de instalar o Docker, é importante que você entenda alguns conceitos básicos, como <i>imagens, contêineres, redes e volumes</i>. Você pode encontrar informações detalhadas sobre esses conceitos na documentação do Docker.

<b>• Crie sua primeira imagem:</b> Depois de entender os conceitos básicos, você pode criar sua primeira imagem Docker. Para isso, você precisa escrever um arquivo <b>Dockerfile</b> e usar o comando <b>"docker build"</b> para criar a imagem.

<b>• Execute um contêiner:</b> Depois de criar uma imagem, você pode executar um contêiner usando o comando <b>"docker run"</b>. É importante entender os parâmetros necessários para <i>executar um contêiner com êxito</i>.

<b>• Explore o Docker Hub:</b> O Docker Hub é um repositório público de imagens Docker. Você pode explorar o Docker Hub para encontrar <i>imagens prontas</i> para uso ou compartilhar suas próprias imagens.

### Download de Imagens Docker
Para realizar o download de uma imagem Docker:

Certifique-se de que você tenha o <b>Docker instalado e funcionando</b> corretamente em seu sistema.

Abra o <b>terminal ou prompt de comando</b> em seu sistema.

Digite o comando <b>"docker search nome_da_imagem"</b> para pesquisar por <b>imagens disponíveis</b> no Docker Hub (outra opção de procurar imagens no Docker é <b>pesquisar no site</b> Docker Hub).

Selecione a <b>imagem desejada</b> e copie o nome exato.

Digite o comando <b>"docker pull nome_da_imagem"</b> no terminal ou prompt de comando para fazer o <i>download da imagem</i>.

Aguarde até que o download seja concluído e verifique se a imagem foi baixada corretamente digitando <b>"docker images"</b> no terminal ou prompt de comando.
Segue um script exemplo para baixar a imagem ubuntu:latest (última imagem do Ubuntu):
''
    #Para iniciar um script linux
	#!/bin/bash 

	#Define o nome da imagem que desejamos baixar
	nome_da_imagem="ubuntu:latest"

	#Executa o comando para fazer o download da imagem
	docker pull $nome_da_imagem

	#Verifica se o download foi concluído com sucesso
	if [ $? -eq 0 ]; then
    echo "Imagem $nome_da_imagem baixada com sucesso!"
	else
    	echo "Houve um problema ao baixar a imagem $nome_da_imagem."
''

### Executar um container
Abra um terminal e execute o comando <b>docker run</b> seguido do <b>nome da imagem</b> do container que deseja executar. Por exemplo, para executar um container do Ubuntu, você pode usar o comando <code>docker run ubuntu</code>.

Se a imagem do container <b>não estiver presente</b> no seu sistema, o Docker fará o <b>download dela automaticamente</b> antes de executar o container.

Se quiser executar um container com <B>configurações personalizadas</B>, você pode <i>usar opções adicionais no comando</i> <b>docker run</b>. Por exemplo, você pode especificar <b>portas</b> a serem mapeadas com a <b>opção -p</b>, <b>diretórios</b> a serem compartilhados com a opção <b>-v</b>, e <b>variáveis de ambiente</b> com a opção <b>-e</b>.

Quando o container <b>estiver em execução</b>, você pode <i>interagir com ele através do terminal ou executar comandos</i> dentro do container usando o comando <code>docker exec</code>. Por exemplo, para executar o comando <b>ls</b> dentro do container do Ubuntu, você pode usar o comando <b>docker exec nome_ou_id_do_container> ls</b>.

Para parar um container em execução, você pode usar o comando <b>docker stop nome_ou_id_do_container</b>.

### Aplicações no Container
Para executar aplicações em um container Docker:

Crie um Dockerfile que <b>defina a imagem base</b> do seu container, <i>instale as dependências necessárias e copie os arquivos</i> da sua aplicação para o container. Por exemplo:

''

	FROM python:3.8

	WORKDIR /app

	COPY requirements.txt .
	RUN pip install --no-cache-dir -r requirements.txt

	COPY . .

	CMD ["python", "app.py"]
''

Crie uma imagem a partir do <b>Dockerfile</b> usando o comando <b>docker build</b>. Por exemplo, se o <i>Dockerfile estiver no diretório atual</i>, você pode usar o comando <code>docker build -t nome_da_imagem</code>. para criar a imagem.

Execute o container usando o comando <b>docker run</b>. Por exemplo, para executar o container criado acima, você pode usar o comando <code>docker run -p 5000:5000 nome_da_imagem</code>.

Acesse a aplicação no navegador usando o endereço <i>http://localhost:5000 ou a porta que você especificou</i> no comando <b>docker run</b>.

Para <b>atualizar a aplicação</b>, basta <i>modificar o código-fonte e criar uma nova imagem</i> usando o comando <b>docker build</b>. Em seguida, pare o container em execução com o comando <b>docker stop nome_ou_id_do_container</b> e execute o novo container com a imagem atualizada usando o comando <b>docker run</b>.

Para <b>remover um container</b>, use o comando <b>docker rm nome_ou_id_do_container</b>. Se desejar remover a imagem também, use o comando <b>docker rmi nome_ou_id_da_imagem</b>.

### Excluindo e Renomeando Containers
Para excluir um container no Docker:
''

	docker rm nome_ou_id_do_container
''
Onde <b>nome_ou_id_do_container</b> é (lógico) o nome ou ID do container que você deseja <b>excluir</b>. Certifique-se de que o container <b>esteja parado</b> antes de tentar excluí-lo.

Para <b>renomear</b> um container no Docker, você pode usar o seguinte comando:
<code>
docker rename nome_atual_do_container novo_nome_do_container
</code>

Onde <b>nome_atual_do_container</b> é o nome atual do container que você deseja renomear e <b>novo_nome_do_container</b> é o novo nome que você deseja dar a ele. <b><i>Lembre-se</i></b> de que o novo nome deve ser exclusivo em relação aos outros containers em execução no seu sistema Docker.

Segue um exemplo de como <b>criar um container</b> do <b>Nginx</b>, <b>renomeá-lo e excluí-lo</b>:

Abra o terminal e execute o seguinte comando para baixar e executar um container Docker com a imagem do Nginx:
<code>
docker run --name meu-container-nginx -d nginx
</code>
Este comando <b>baixa a imagem</b> do Nginx do Docker Hub e executa um container com o nome <b>"meu-container-nginx"</b>. O parâmetro <b>"-d"</b> faz com que o container seja <b>executado em segundo plano</b>.

Para verificar se o container está em execução, execute o seguinte comando:
<code>
docker ps
</code>

Você deverá ver o container <b>"meu-container-nginx"</b> na lista de containers em execução.

Agora, vamos <b>renomear</b> o container para <b>"meu-novo-container-nginx"</b> usando o seguinte comando:
<code>
docker rename meu-container-nginx meu-novo-container-nginx
</code>

Para verificar se o nome do container foi alterado, execute o seguinte comando:
<code>
docker ps
</code>

O container deve ser <b>listado</b> com o novo nome <b>"meu-novo-container-nginx"</b>.

Finalmente, para <b>excluir o container</b>, execute o seguinte comando:
<code>
docker rm meu-novo-container-nginx
</code>

Este comando exclui o container com o nome <b>"meu-novo-container-nginx"</b>.

### Copiar Arquivos para o Container
Para <b>copiar arquivos</b> para um contêiner Docker, você pode usar o comando <b>"docker cp"</b> como está nas etapas abaixo:

Execute o contêiner com o comando <b>"docker run"</b>.
Use o comando <b>"docker cp"</b> seguido do <b>caminho do arquivo</b> local que você deseja copiar e o <b>caminho dentro do container</b> que você deseja copiar para. Por exemplo:
<code>
docker cp /caminho/local/arquivo.txt nome-do-container:/caminho/contêiner/arquivo.txt
</code>

Isso copiará o arquivo <b>"arquivo.txt"</b> do seu sistema local para o contêiner Docker com o nome <b>"nome-do-container"</b> no caminho <b>"/caminho/contêiner/arquivo.txt"</b>.

Para copiar arquivos do contêiner para o seu sistema local, basta trocar a ordem dos caminhos:
<code>
docker cp nome-do-container:/caminho/contêiner/arquivo.txt /caminho/local/arquivo.txt
</code>

Isso copiará o arquivo <b>"arquivo.txt"</b> do contêiner Docker com o nome <b>"nome-do-container"</b> no caminho <b>"/caminho/contêiner/arquivo.txt"</b> para o seu sistema local no caminho <b>"/caminho/local/arquivo.txt"</b>.

### TAGs
As <b>tags do Docker</b> referem-se às <b>versões específicas</b> de uma imagem Docker. As tags permitem que você <b>especifique</b> qual versão de uma imagem você deseja usar em seu contêiner.

Algumas das <b>tags comuns (e principais)</b> do Docker incluem:

<b>• latest:</b> a versão mais recente da imagem
<b>• stable:</b> a versão estável da imagem
<b>• beta:</b> uma versão beta da imagem
<b>alpha:</b> uma versão alfa da imagem
<b>• <i>versão_específica</i></b>: uma versão específica da imagem identificada por um número de versão ou tag personalizada

Além disso, os usuários também podem <b>criar suas próprias tags personalizadas</b> para imagens Docker que eles criaram.

### Criação de um Container MySQL
Primeiro, crie um arquivo .yml/.yaml (aconselho .yml caso use GitLab), por exemplo, o nome que darei será cont-mysql.yml:
<code>
version: '3.9'
services:
  db:
    image: mysql:latest
    restart: always
    environment:
      MYSQL_ROOT_PASSWORD: sua_senha
      MYSQL_DATABASE: seu_banco_de_dados
      MYSQL_USER: seu_usuario
      MYSQL_PASSWORD: sua_senha_do_usuario
    ports:
      - "3306:3306"
</code>

Assim como <b>Python</b>, arquivos YAML <b>SÃO OBRIGADOS</b> a serem <i>identados</i> corretamente.

### Parando e Reiniciando um Container
Para parar um container em execução no Docker, você pode usar o seguinte comando:
<code>
docker stop nome_do_container
</code>
Substitua "nome_do_container" pelo nome ou ID do container que você deseja parar. Isso <b>interromperá</b> o processo em execução no container e o <b>desligará</b>.

Para <b>reiniciar um container</b> que já foi interrompido, use o seguinte comando:
<code>
docker start nome_do_container
</code>
Isso <b>iniciará novamente</b> o container com as <b>mesmas configurações</b> que tinha antes de ser interrompido. Se você deseja <b>parar e reiniciar</b> um container em uma <b>única linha de comando</b>, você pode usar o seguinte comando:
<code>
docker restart nome_do_container
</code>

Isso irá <b>parar o container</b>, e em seguida, <b>iniciá-lo novamente <i>imediatamente</i></b> em seguida.

### Limitando Processamento e Memória
Para <b>limitar o processamento e a memória</b> de um container Docker, você pode usar as <b>opções de limites de recursos</b> disponíveis no Docker. Existem várias opções de limites que você pode aplicar, incluindo <i>limites de CPU, memória e E/S</i>.

Para <b>limitar o processamento</b> de um container Docker, você pode usar a opção <b>--cpus</b> para <i>especificar quantos núcleos de CPU</i> o container pode usar. Por exemplo, para limitar um container a usar <b>apenas um núcleo</b> de CPU, você pode executar o seguinte comando:
<code>
docker run --cpus=1 nome-da-imagem
</code>

Para <b>limitar a memória</b> de um container Docker, você pode usar a opção <b>--memory</b> para especificar quantos bytes de memória o container pode usar. Por exemplo, para limitar um container a usar no <b>máximo 1GB</b> de memória, você pode executar o seguinte comando:
<code>
docker run --memory=1g nome-da-imagem
</code>

Além disso, você também pode usar a opção <b>--memory-swap</b> para especificar a <b>quantidade máxima</b> de memória e swap que o container pode usar. Por exemplo, para limitar um container a usar no máximo 1 GB de memória e 2 GB de swap, você pode executar o seguinte comando:
<code>
docker run --memory=1g --memory-swap=2g nome-da-imagem
</code>

Lembre-se de que essas opções são apenas para limitar o uso de recursos dentro do container Docker e não limitam o uso do host subjacente. Certifique-se de definir limites apropriados para evitar problemas de desempenho ou estabilidade.

Por exemplo, limitar a 1 núcleo de CPU e 1GB de memória
<code>
	docker run --cpus=1 --memory=1g nome-da-imagem
</code>

E, neste exemplo, limitando a 1 núcleo de CPU, 1GB de memória com swap de 2GB
<code>
	docker run --cpus=1 --memory=1g --memory-swap=2g nome-da-imagem
</code>

### Informações, Logs e Processos
Dentro de um container Docker, é possível <b>acessar informações</b> sobre o <i>sistema operacional e os processos em execução</i>, bem como <i>visualizar logs do container</i>.

<b>• Informações do sistema operacional:</b> Dentro de um container Docker, é possível <b>acessar informações</b> sobre o sistema operacional usando comandos como <b>uname, lsb_release ou cat /etc/*-release</b>. Esses comandos podem ser executados dentro do container para <b>verificar informações</b> como o nome e a versão do sistema operacional, o kernel em execução e outras informações relevantes.
<!-- -->
<b>• Processos em execução:</b> É possível <b>visualizar os processos em execução</b> dentro de um container Docker usando o comando <b>ps</b>. Esse comando mostra uma <i>lista de processos em execução</i> dentro do container, incluindo seu <b>PID (proccess id), nome e uso de recursos</b>.

<b>• Logs do container:</b> Os logs de um container Docker podem ser acessados usando o comando <b>docker logs</b>. Esse comando mostra a saída padrão do container, que pode incluir <i>mensagens de erro, informações de depuração e outros registros importantes</i>.

Além disso, o Docker também permite o <b>redirecionamento da saída padrão e de erro para arquivos de log externos</b>. Esses arquivos de log podem ser <i>monitorados por ferramentas de monitoramento de log ou analisados manualmente</i>.

### Redes
As redes de container Docker permitem que os contêineres se <b>comuniquem</b> uns com os outros de forma <b>segura e eficiente</b>. O Docker fornece várias opções para <b>configurar redes de container</b>, desde <i>redes padrão pré-configuradas até a criação de redes personalizadas</i>. Segue abaixo as opções:

<b>• Rede padrão:</b> O Docker cria automaticamente uma rede padrão chamada <b>"bridge"</b> quando é instalado. Essa rede permite que os contêineres se comuniquem entre si e com o host, mas não fornece isolamento de rede entre os contêineres (parecido com VM).

<b>• Rede host:</b> A rede host permite que os contêineres <b>compartilhem</b> a rede do host, o que pode <i>melhorar o desempenho em alguns casos</i>. No entanto, os contêineres não estão isolados uns dos outros e podem acessar facilmente a rede do host.

<b>• Rede overlay:</b> As redes overlay permitem que os contêineres se <i>comuniquem entre si em diferentes hosts em um cluster do Docker</i>. Essa opção é útil para aplicativos que precisam ser executados em vários hosts.

<b>• Rede personalizada:</b> O Docker também permite criar redes personalizadas para atender às <b>necessidades específicas</b> do aplicativo. Essas redes podem ser isoladas dos outros contêineres e do host e podem ter recursos adicionais, como a <i>atribuição de endereços</i> IP específicos.

## Docker Swarm
Docker Swarm é uma plataforma de <b>orquestração de contêineres</b> Docker que permite que você <b>gerencie e escalone</b> aplicativos em <i>vários hosts Docker</i>. Com o Docker Swarm, você pode <i>criar um cluster de hosts Docker e distribuir aplicativos</i> em vários hosts para garantir alta disponibilidade e escalabilidade.

O Docker Swarm inclui um sistema de programação que <i>permite que você defina o número de réplicas</i> de um serviço e <b>como ele deve ser distribuído</b> em todo o cluster. Ele também possui <i>recursos de balanceamento de carga integrados</i> que ajudam a <i>distribuir o tráfego</i> entre os hosts do cluster.

Outra vantagem do Docker Swarm é a <b>facilidade de configuração e gerenciamento</b>. Ele pode ser <i>configurado</i> usando uma <i>simples linha de comando</i> e os serviços podem ser <i>facilmente atualizados e escalonados</i> com apenas alguns comandos.

Em resumo, o Docker Swarm é uma <b>ferramenta poderosa</b> para gerenciar contêineres Docker em larga escala, oferecendo <i>alta disponibilidade, escalabilidade e facilidade de uso</i>.

### Exemplo do Docker Compose
pode usar o Docker Compose para gerenciar e orquestrar os contêineres Docker necessários para o seu aplicativo que vai colocar no container Docker. Lembrando como foi dito anteriormente, <b>Docker Compose</b> também usa <b>arquivos YAML</b>, tendo que identar o código para funcionar e a extensçao .yaml ou .yml (recapitulando, aconselho .yml para uso em GitLab)

O nome que darei vai ser <b>docker-compose.yml</b> e ficará no <b>diretório raiz</b> do projeto com o seguinte conteúdo:
<code>
version: '3'
services:
  web:
    build: .
    ports:
      - "5000:5000"
  db:
    image: mysql:5.7
    environment:
      MYSQL_ROOT_PASSWORD: senha_root
      MYSQL_DATABASE: meu_banci
      MYSQL_USER: meu_usuario
      MYSQL_PASSWORD: minha_senha
</code>

Este arquivo define dois serviços: <b>web</b> e <b>db</b>. O serviço web é <b>construído a partir do Dockerfile</b> no diretório atual <b>(.)</b> e expõe a <b>porta 5000</b>. O serviço db usa a imagem <b>MySQL 5.7</b> e define algumas variáveis de ambiente para <b>configurar</b> o banco de dados.

• No terminal, navegue até o diretório raiz do seu projeto e execute o seguinte comando para iniciar os contêineres:
<code>
	docker-compose up
</code>

Isso iniciará os contêineres definidos no arquivo <b>docker-compose.yml</b> que fizemos. O Docker Compose irá <b>construir o serviço web</b> a partir do <b>Dockerfile</b> e <i>iniciar um contêiner para ele, juntamente com um contêiner para o serviço db</i>.

Acesse o aplicativo em seu navegador em <i>http://localhost:5000</i>.

Quando terminar, <b>pare</b> os contêineres com o comando:
<code>
	docker-compose down
</code>

Este é apenas um <i>exemplo simples</i>, mas o <b>Docker Compose</b> pode ser usado para <b>gerenciar aplicativos</b> muito mais <b>complexos e com vários serviços</b>. Com o Docker Compose, você pode facilmente <b>orquestrar e dimensionar</b> seus aplicativos em contêineres Docker, tornando o processo de <i>desenvolvimento e implantação muito mais fácil e eficiente</i>.

### Exemplo PHP APACHE MySQL
• Crie um arquivo YAML, eu vou criar o <b>docker-compose.yml</b> com o seguinte conteúdo:
<code>
version: '3'

services:
  web:
    image: php:apache
    ports:
      - "80:80"
    volumes:
      - ./src:/var/www/html/
    deploy:
      replicas: 3
      update_config:
        parallelism: 2
        delay: 10s
      restart_policy:
        condition: on-failure
  db:
    image: mysql:5.7
    volumes:
      - ./db_data:/var/lib/mysql
    environment:
      MYSQL_ROOT_PASSWORD: example
      MYSQL_DATABASE: mydatabase
      MYSQL_USER: myuser
      MYSQL_PASSWORD: mypassword
    deploy:
      replicas: 1
      update_config:
        parallelism: 1
        delay: 10s
      restart_policy:
        condition: on-failure
</code>

Este arquivo define <b>dois serviços</b>: um para o <b>servidor web</b> PHP/Apache e outro para o <b>servidor de banco de dados</b> MySQL. O serviço web é configurado para ter <b>três réplicas</b> e o serviço de banco de dados <b>uma réplica</b>.

Crie uma pasta chamada <b>src</b> para o código PHP. Adicione um arquivo <b>index.php (para o servidor APACHE ler o arquivo e já mostrar, necessita ter o nome index, seja html ou php)</b> a esta pasta com o seguinte conteúdo:
<code>
<?php
$servername = "meu_banco";
$username = "meu_usuario";
$password = "minha_senha";
$dbname = "minha_tabela";

// Cria conexão
$conn = new mysqli($servername, $username, $password, $dbname);

// Verifica conexão
if ($conn->connect_error) {
    die("Falha na conexão: " . $conn->connect_error);
}

echo "Conectado com sucesso!";
?>
</code>

Este script PHP <b>conecta ao banco</b> de dados</b> MySQL usando as <i>credenciais</i> definidas no arquivo <b>docker-compose.yml</b> e imprime uma mensagem na tela se a conexão for bem-sucedida (poderia colocar else também, caso quiser imprimir mensagem de erro caso dê falha na conexão).

• Execute o comando <b>docker swarm init</b> para iniciar o <i>modo Swarm</i>.

Execute o comando <code>docker stack deploy -c docker-compose.yml myapp</code> para <b>implantar</b> a pilha de contêineres. Isso criará os contêineres para os serviços web e de banco de dados e os distribuirá em <b>três nós</b> do Swarm.

Acesse <i>http://localhost</i> em seu navegador para ver a saída do código PHP.

### Cluster com Docker Swarm
Como dito anteriormente, <b>Docker Swarm</b> é uma ferramenta que permite <b>criar e gerenciar clusters</b> de containers Docker. Um <i>cluster é um conjunto de nós (máquinas) que trabalham juntos</i> para executar aplicativos distribuídos.

Para <b>criar um cluster</b> com Docker Swarm, é necessário ter pelo menos duas máquinas em que o Docker esteja <b>instalado e configurado</b>. Uma das máquinas será designada como <b>nó gerente</b> e as outras máquinas serão designadas como <b>nós de trabalho</b>.

Para <b>iniciar o cluster</b>, o nó gerente precisa ser inicializado com o comando <code>docker swarm init</code>. Isso irá criar o cluster e <b>gerar um token</b> que deve ser usado para adicionar os nós de trabalho ao cluster. Os nós de trabalho podem ser adicionados ao cluster executando o comando <code>docker swarm join</code> com o token gerado pelo nó gerente.

Uma vez que o cluster esteja <i>configurado</i> e os nós de trabalho tenham se <i>juntado</i>, é possível implantar aplicativos no cluster usando o comando <i>docker service create</i>. Isso criará um serviço que será <b>distribuído e executado</b> em todos os nós de trabalho do cluster.

O Docker Swarm oferece <b>recursos avançados de gerenciamento</b> de cluster, como <i>balanceamento de carga (mais conhecido como LoadBalancer), escalonamento automático e recuperação de falhas</i>. Com esses recursos, é possível criar aplicativos distribuídos altamente <b>disponíveis e escaláveis</b>.

### Exemplo de Aplicação em Cluster
Suponha que temos uma <b>aplicação web simples</b> composta por dois serviços: um <b>serviço web e um serviço de banco de dados</b>. Queremos implantar essa aplicação em um cluster Docker Swarm com <b>três nós</b>.

Primeiro, precisamos <b>inicializar</b> um novo cluster Docker Swarm. Podemos fazer isso usando o seguinte comando em um dos nós:
<code>
docker swarm init
</code>
Em seguida, precisamos <b>criar uma pilha Docker</b> para nossa aplicação. Uma pilha Docker é um arquivo YAML que define os <i>serviços, redes e volumes de nossa aplicação</i>. Aqui está um exemplo de pilha para nossa aplicação:
<code>
version: "3"
services:
  db:
    image: mysql:5.7
    deploy:
      replicas: 2
      placement:
        constraints: [node.role == worker]
  web:
    image: my-web-app:latest
    deploy:
      replicas: 3
      placement:
        constraints: [node.role == worker]
    ports:
      - "80:80"
    depends_on:
      - db
networks:
  webnet:
</code>

Com a pilha criada, podemos <b>implantar</b> nossa aplicação no cluster Docker Swarm usando o seguinte comando:
<code>
docker stack deploy -c docker-compose.yml my-app
</code>

Agora, nossa aplicação está sendo <b>executada em todo</b> o cluster Docker Swarm, com <b>três réplicas</b> do serviço web e <b>duas réplicas</b> do serviço de banco de dados.

Podemos <b>verificar o status</b> da nossa pilha usando o seguinte comando:
<code>
docker stack ps my-app
</code>

Isso mostrará o status de cada réplica do serviço em cada nó do cluster.

### Load Balancer
Um load balancer é um <b>componente de rede</b> que <b>distribui o tráfego</b> de entrada entre vários servidores de destino. Ele é usado para <b>evitar</b> que um único servidor se torne um <b>ponto de falha</b> e também para <b>maximizar</b> a capacidade de processamento disponível. Quando um cliente faz uma solicitação, o <b>load balancer decide</b> qual servidor deve atendê-lo com base em uma variedade de fatores, como <i>carga de trabalho, latência, capacidade e muito mais</i>.

No contexto do <b>Docker</b> e do <b>Docker Swarm</b>, um load balancer é frequentemente usado para <b>distribuir o tráfego</b> de entrada entre os vários nós do cluster. Isso permite que os serviços sejam escalonados horizontalmente, <b>adicionando ou removendo</b> réplicas à medida que a carga de trabalho <b>aumenta ou diminui</b>. O load balancer pode ser configurado para <b>monitorar</b> a carga em cada nó do cluster e <b>direcionar</b> o tráfego de entrada para os nós menos ocupados, a fim de garantir que a capacidade de processamento seja <i>usada de forma eficiente</i>.

Existem <b>vários tipos</b> de load balancers que podem ser usados com o Docker e o Docker Swarm, incluindo <i>load balancers baseados em hardware, load balancers baseados em software e soluções de balanceamento de carga baseadas em nuvem</i>, como o <b>Amazon Elastic Load Balancer (ELB)</b> ou o <b>Google Cloud Load Balancer</b>.

No entanto, o uso de load balancers <i>pode afetar o desempenho e a disponibilidade da rede</i> do Docker e do Docker Swarm. Se o load balancer for <i>mal configurado</i> ou estiver <i>sobrecarregado</i>, ele pode se tornar um gargalo e reduzir a capacidade de processamento disponível. Além disso, se o load balancer <b>falhar</b>, ele pode interromper o acesso aos serviços que ele está balanceando. Portanto, é <b>importante</b> configurar o load balancer <b>corretamente e monitorá-lo</b> de perto para garantir que ele esteja funcionando corretamente.

### Definição de um Cluster Swarm Local com o Vagrant
Um cluster swarm local é um <b>grupo de computadores</b> que trabalham juntos para executar aplicativos e serviços. O <b>Vagrant</b> é uma ferramenta que permite <b>criar e gerenciar</b> ambientes de desenvolvimento. Combinando essas duas tecnologias, é possível <i>criar um cluster swarm local usando o Vagrant</i>.

Para criar um cluster swarm local com o Vagrant, você precisa seguir os seguintes passos:

• Instale o <b>Vagrant</b> e o <b>VirtualBox</b> em seu computador.

• Crie um arquivo <b>Vagrantfile</b> em um diretório vazio. Este arquivo é usado para <b>definir as configurações</b> do cluster.

• <b>Adicione as configurações</b> para as máquinas virtuais que você deseja criar, <b>incluindo</b> o sistema operacional e o tamanho da memória.

• <b>Adicione as configurações</b> para o cluster swarm, <b>incluindo</b> o número de nós e o tipo de rede.

• Inicie o cluster swarm com o comando <code>vagrant up</code>.

• Configure o cluster swarm usando o <b>Docker Swarm</b>, que é uma ferramenta de gerenciamento de cluster (dito anteriormente).

• <b>Execute</b> seus aplicativos e serviços no cluster swarm.

Usando esses passos, você pode criar um cluster swarm local para <b>testar e desenvolver</b> aplicativos e serviços.

## Kubernetes
<b>Kubernetes (também chamado por k8s)</b> é uma plataforma de <b>orquestração de contêineres</b> de código aberto desenvolvida pelo Google. Ele ajuda a <i>gerenciar aplicativos</i> em contêineres e <i>automatizar tarefas</i> como <i>implantação, escalonamento e gerenciamento de recursos</i>.

Kubernetes permite que você <b>implante e gerencie</b> containeres em um <i>cluster de máquinas</i>, o que torna mais <b>fácil gerenciar</b> um grande número de contêineres. Ele também ajuda a garantir que seus aplicativos estejam <b>sempre disponíveis</b>, mesmo em <b>caso de falha</b> em <i>uma ou mais máquinas</i>.

Kubernetes fornece uma <b>API para gerenciar</b> contêineres, que é <i>compatível com vários provedores Cloud</i>. Ele também tem uma <i>ampla comunidade</i> de desenvolvedores e usuários que estão continuamente contribuindo para melhorar a plataforma.

Kubernetes é uma <b>ferramenta poderosa e popular</b> para <i>gerenciar contêineres e escalonar aplicativos</i> em um ambiente de produção.

## Arquitetura Básica do Kubernetes
A arquitetura básica do Kubernetes <b>consiste em vários componentes</b> que trabalham juntos para <b>gerenciar e orquestrar</b> contêineres em um cluster. Esses componentes são:

<b>• Master Node:</b> o nó mestre é responsável por <i>controlar e gerenciar</i> todo o cluster. Ele executa vários componentes, como o <i>API Server, o Controller Manager e o Scheduler</i>.

<b>• Worker Nodes:</b> os nós de trabalho são responsáveis por <b>executar e fornecer recursos</b> para os containeres. Cada nó de trabalho tem um <b>agente do Kubernetes (Kubelet)</b> e um <b>gerenciador de contêineres (Docker, CRI-O ou outros)</b>.

<b>• API Server:</b> o servidor API é o <b>ponto de entrada principal</b> para o cluster Kubernetes. Ele expõe uma <b>API REST</b> que <i>permite</i> aos usuários e aos componentes do Kubernetes <i>interagir com o cluster</i>.

<b>• Controller Manager:</b> o gerenciador de controladores é responsável por <b>garantir</b> que o estado desejado do cluster <b>seja mantido</b>. Ele executa vários controladores que <b>monitoram e gerenciam</b> recursos no cluster.

<b>• Scheduler:</b> o agendador é responsável por <b>programar containeres</b> em nós de trabalho. Ele leva em consideração vários fatores, como <b>requisitos de recursos, afinidade e antiafinidade</b>.

<b>• Etcd:</b> o etcd é um <b>armazenamento de chave-valor</b> distribuído que é usado pelo Kubernetes para <b>armazenar informações</b> sobre o estado do cluster. Ele é altamente <b>disponível e consistente</b> para garantir a integridade dos dados.

Esses componentes trabalham em conjunto para fornecer recursos de <i>escalabilidade, resiliência e automação</i> para aplicativos em contêineres executados em um cluster Kubernetes.

### Ambiente de Desenvolvimento Kubernetes
O ambiente de desenvolvimento Kubernetes é um <b>conjunto de ferramentas e configurações</b> que permitem que os desenvolvedores <i>criem, testem e implantem</i> aplicativos no Kubernetes. Isso inclui um <i>cluster Kubernetes local</i> que pode ser executado em uma máquina de desenvolvimento, bem como ferramentas para <b>implantar e gerenciar</b> aplicativos no cluster.

Existem várias opções para criar um ambiente de desenvolvimento Kubernetes, como usar <b>minikube, Kind (Kubernetes em Docker) ou K3d (Kubernetes em Docker em Docker)</b>. Cada opção tem suas próprias <b>vantagens e desvantagens</b>, dependendo das necessidades específicas do projeto.

Uma vez configurado, um ambiente de desenvolvimento Kubernetes permite que os desenvolvedores <b>criem e testem</b> aplicativos em um ambiente semelhante ao de produção. Isso ajuda a garantir que os aplicativos sejam <i>implantados corretamente e funcionem conforme o esperado</i> quando forem implantados no ambiente de produção real.

### Exemplo de Cluster Kubernetes com o MiniKube
O <b>Kubernetes</b> é uma <b>plataforma de orquestração</b> de contêineres amplamente utilizada para <i>implantação, gerenciamento e escalabilidade</i> de aplicativos em contêineres. O <b>MiniKube</b> é uma ferramenta que <b>permite executar</b> o Kubernetes em um único nó, tornando-o ideal para <b>testar e desenvolver</b> aplicativos em um <i>ambiente de produção simulado</i>.

Para <b>criar um cluster</b> Kubernetes com o MiniKube, siga estes passos:

• Instale o <b>MiniKube</b> e o <b>Kubernetes CLI</b> em sua máquina local.

• Abra o terminal e inicie o <b>MiniKube</b> digitando o seguinte comando:
<code>
minikube start
</code>

• Verifique se o cluster está em execução digitando o seguinte comando:
<code>
kubectl cluster-info
</code>
Isso mostrará informações sobre o cluster Kubernetes em execução.

• Crie um deployment usando um <b>arquivo YAML</b>. Por exemplo, para criar um deployment com uma imagem Nginx, crie um arquivo chamado <b>nginx-deployment.yaml</b> com o seguinte conteúdo (está sendo criado com a extensão .yaml para diversificar um pouco):
<code>
apiVersion: apps/v1
kind: Deployment
metadata:
  name: nginx-deployment
spec:
  replicas: 3
  selector:
    matchLabels:
      app: nginx
  template:
    metadata:
      labels:
        app: nginx
    spec:
      containers:
      - name: nginx
        image: nginx:latest
        ports:
        - containerPort: 80
</code>
<b>Salve o arquivo</b> e, em seguida, <b>implante-o</b> usando o seguinte comando:
<code>
kubectl apply -f nginx-deployment.yaml
</code>

• Verifique se o deployment está em execução digitando o seguinte comando:
<code>
kubectl get deployments
</code>
Isso <b>mostrará uma lista</b> de todos os deployments em execução.

• Crie um serviço para <b>expor</b> o deployment. Por exemplo, para criar um serviço para o deployment nginx, crie um arquivo chamado nginx-service.yaml com o seguinte conteúdo:
<code>
apiVersion: v1
kind: Service
metadata:
  name: nginx-service
spec:
  selector:
    app: nginx
  ports:
  - protocol: TCP
    port: 80
    targetPort: 80
  type: LoadBalancer
</code>
Salve o arquivo e, em seguida, <b>crie o serviço,/ usando o seguinte comando:
<code>
kubectl apply -f nginx-service.yaml
</code>

• Verifique se o serviço está em execução digitando o seguinte comando:
<code>
kubectl get services
</code>

Isso mostrará uma lista de todos os serviços em execução.

### Exemplo de Deploy de uma Aplicação
Vou iniciar o minikube e então, criar um arquivo chamado myapp.yml com o seguinte conteúdo:
<code>
minikube start
apiVersion: apps/v1
kind: Deployment
metadata:
  name: myapp-deployment
spec:
  replicas: 1
  selector:
    matchLabels:
      app: myapp
  template:
    metadata:
      labels:
        app: myapp
    spec:
      containers:
      - name: myapp-container
        image: nginx:latest
        ports:
        - containerPort: 80
</code>

Para expor o deployment como um serviço, precisa executar o seguinte comando:
<code>
kubectl expose deployment myapp-deployment --type=LoadBalancer --port=80
</code>

### Deployment e Roolback em Clusters Kubernetes
Deployment e Rollback são <b>duas funcionalidades importantes</b> em clusters Kubernetes que permitem <b>gerenciar e atualizar</b> aplicativos de maneira eficiente.

Antes de continuar, vou explicar o que é <b>pods</b>:
um <b>pod</b> é a <b>menor unidade</b> de implantação que pode ser <i>criada e gerenciada</i>. Um pod é uma <b>abstração que encapsula</b> um ou mais contêineres do Docker, armazenando informações como <i>endereço IP, portas expostas e volumes montados</i>.

Cada pod é criado com seu <b>próprio espaço de rede e armazenamento</b>, e pode ser considerado como uma <b>"cápsula" (tradução literal de pods)</b> que envolve <b>um ou mais</b> contêineres, permitindo que eles sejam <b>gerenciados</b> de maneira unificada.

<b>Os pods são projetados</b> para serem <i>escaláveis e altamente disponíveis</i>. Isso significa que, <i>se um pod falhar, o Kubernetes pode automaticamente criar um novo pod em seu lugar</i>, para garantir que o aplicativo <b>continue a funcionar</b> sem interrupções. Além disso, os pods podem ser <b>replicados e distribuídos</b> em vários nós de um cluster Kubernetes, permitindo que o aplicativo seja <b>escalado horizontalmente</b>.

Os pods também fornecem uma maneira de compartilhar recursos entre os contêineres em um ambiente Kubernetes. Por exemplo, um pod pode ter vários contêineres que compartilham um volume de dados comum, permitindo que eles troquem informações de maneira eficiente.

Em resumo, os pods são uma das <b>principais unidades de gerenciamento</b> de aplicativos em <b>Kubernetes</b>, permitindo que os usuários <b>implantem e gerenciem</b> containeres de maneira <i>flexível e escalável</i>.

O <b>Deployment</b> é um objeto Kubernetes que <b>gerencia a implantação</b> de um conjunto de <b>pods</b> em um cluster. Ele permite que os usuários <b>especifiquem o número</b> de réplicas de um aplicativo que devem ser implantadas e <b>define</b> como as atualizações serão aplicadas. Quando um Deployment é criado, ele cria um conjunto de réplicas do aplicativo que são <i>gerenciadas automaticamente pelo Kubernetes</i>.

O <b>Rollback</b>, por sua vez, é uma funcionalidade que permite <b>reverter uma implantação</b> para uma <b>versão anterior</b> do aplicativo. Isso é útil quando ocorre um erro durante uma atualização ou quando é descoberto um bug crítico após a implantação. O Kubernetes permite que os usuários executem um Rollback facilmente, criando um novo Deployment com a versão anterior do aplicativo e fazendo com que o Kubernetes alterne o tráfego para o novo Deployment.

Em conjunto, <b>Deployment e o Rollback</b> permitem que os usuários atualizem seus aplicativos com <i>segurança e eficiência</i> em um <b>cluster Kubernetes</b>. Isso ajuda a <b>garantir a disponibilidade</b> contínua do aplicativo para os usuários finais.

### History e Undo
<b>• History</b> refere-se a uma funcionalidade que permite aos usuários <b>visualizar o histórico de versões</b> de um objeto Kubernetes. Isso inclui informações sobre <i>alterações feitas em um objeto, como quem fez a alteração, quando ela foi feita e qual foi a alteração em si</i>.

<b>• Undo</b> é uma funcionalidade relacionada que permite <b>desfazer as alterações feitas</b> em um objeto Kubernetes, <b>voltando para um estado anterior</b>. Isso pode ser útil se uma alteração <i>causou problemas inesperados ou se um usuário cometeu um erro</i> ao realizar uma alteração. Com a funcionalidade <b>Undo</b>, é possível <b>reverter as alterações</b> para um <b>estado anterior</b> conhecido e estável.

### CI/CD Utlizando Kubernetes
<b>CI/CD (Integração Contínua/Implantação Contínua)</b> é uma <b>metodologia de desenvolvimento</b> de software que visa <b>automatizar</b> <i>o processo de construção, teste e implantação de um aplicativo</i>. <b>Kubernetes</b> é uma plataforma de <b>orquestração de containeres</b> que permite <b>gerenciar e implantar</b> aplicativos em escala.

Ao utilizar Kubernetes em conjunto com uma <b>ferramenta de CI/CD</b>, é possível <i>automatizar todo o processo de implantação</i>, desde a <b>construção</b> até a <b>implantação em produção</b>. Isso permite que as equipes de desenvolvimento possam <i>entregar com mais rapidez e confiança novas funcionalidades e correções de bugs</i>.

Para implementar CI/CD utilizando Kubernetes, é necessário criar <b>pipelines de integração e implantação contínuas</b> que utilizem as funcionalidades de orquestração do Kubernetes para <i>criar, gerenciar e escalar os contêineres</i>. Essas pipelines devem ser configuradas para <b>executar testes</b> automatizados em cada etapa do processo, <b>garantindo</b> que o aplicativo esteja funcionando corretamente antes de ser implantado em produção.

Além disso, é <b>importante</b> utilizar <i>ferramentas de monitoramento e análise</i> para identificar rapidamente <i>problemas em produção e corrigi-los com rapidez</i>. Com a combinação de <b>Kubernetes e CI/CD</b>, é possível construir <i>aplicativos escaláveis, confiáveis e que sejam atualizados com frequência</i>, permitindo que as empresas possam inovar e atender às demandas do mercado de forma mais eficiente.

### Exemplo de Pipeline de Criação de Imagens
Para criar um pipeline de criação de imagens com Kubernetes CI/CD, você pode seguir os seguintes passos:

• Escolha uma <b>ferramenta de automação</b> de CI/CD como o <b>Jenkins, GitLab CI/CD, Travis CI ou CircleCI</b>.

• Configure um <b>ambiente de construção</b> para a sua aplicação, que pode ser um contêiner Docker com <b>todas as dependências</b> necessárias.

• Escreva um script de compilação, que pode ser baseado em um <b>Dockerfile</b>, que <i>instrua o ambiente de construção a compilar</i> a sua aplicação e criar a imagem Docker correspondente.

• <b>Configure</b> o seu ambiente de CI/CD para <b>executar o script</b> de compilação quando houver alterações no código-fonte.

• <b>Armazene a imagem</b> Docker resultante em um <b>repositório de imagens</b>, como o <b>Docker Hub ou o Google Container Registry</b>.

• Configure um <b>ambiente de implantação</b>, que pode ser outro cluster Kubernetes ou um servidor virtual.

• Escreva um <b>script Kubernetes</b> que defina os <b>recursos necessários</b> para implantar sua aplicação, como <i>implantações, serviços e configurações</i>.

Configure o seu ambiente de <b>CI/CD</b> para <b>implantar automaticamente</b> a sua aplicação usando o script Kubernetes quando a imagem Docker for atualizada.

• <b>Monitore</b> a sua aplicação e faça <b>ajustes necessários</b> no seu <b>pipeline de CI/CD</b>.

Com este <b>pipeline de criação de imagens</b> com Kubernetes CI/CD, você pode <b>automatizar</b> todo o processo de <b>construção, teste e implantação</b> de sua aplicação, tornando-o mais <b>eficiente e confiável</b>.
<code>
#Arquivo .gitlab-ci.yml
image: docker:latest

variables:
  #Defina as variáveis de ambiente
  DOCKER_DRIVER: overlay2
  CONTAINER_REGISTERY: gcr.io
  PROJECT_NAME: my-project
  IMAGE_NAME: my-image
  IMAGE_TAG: $CI_COMMIT_SHORT_SHA

before_script:
  #Instale o cliente do Google Cloud SDK
  - apk add --update curl python py-pip bash
  - curl -sSL https://sdk.cloud.google.com | bash
  - ln -s /root/google-cloud-sdk/bin/gcloud /usr/local/bin/gcloud
  - gcloud auth activate-service-account --key-file=my-service-account.json
  - gcloud auth configure-docker

stages:
  - build
  - deploy

build:
  stage: build
  script:
    #Compile a aplicação e crie a imagem Docker correspondente
    - docker build -t $CONTAINER_REGISTERY/$PROJECT_NAME/$IMAGE_NAME:$IMAGE_TAG .
    - docker push $CONTAINER_REGISTERY/$PROJECT_NAME/$IMAGE_NAME:$IMAGE_TAG
  tags:
    #Especifique os runners do GitLab CI/CD que podem executar este trabalho
    - docker

deploy:
  stage: deploy
  script:
    #Implante a aplicação no cluster Kubernetes
    - kubectl apply -f kubernetes-manifest.yaml
  tags:
    #Especifique os runners do GitLab CI/CD que podem executar este trabalho
    - kubernetes
</code>

Este código usa o GitLab CI/CD para <b>compilar a aplicação e criar a imagem</b> Docker correspondente. Em seguida, a imagem Docker é enviada para o <b>Google Container Registry</b>. Por fim, o script Kubernetes é aplicado para <b>implantar a aplicação</b> no cluster Kubernetes.




















<br><br><br><br>
Repositório feito para ajudar nos estudos de um amigo, <b>Alan Alves</b>
<br>
Agradecimentos pelo conhecimento a <a href="https://dio.me">DIO - Digital Inovation One</a>