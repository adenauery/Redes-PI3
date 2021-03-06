## Projeto Integrador III-A - Redes de Computadores

### Equipe

**Grupo 1:**
* Guilherme de Souza Dias
* Pablo de Souza Lopes

**Grupo 2:**
* Bruno Lemke dos Santos
* Emerson Barbosa de Medeiros

**Grupo 3:**
* Hendrio Buttow Pereira
* Marcelo Souza da Rosa

**Grupo 4:**
* Paulo Armando da Silva Alves
* Rodrigo Valadão
  
### Primeiro Encontro Presencial - 27/03/2021

#### Visão Geral da IoT
  * [Slides Introdutórios](http://olaria.ucpel.edu.br/materiais/lib/exe/fetch.php?media=internet_das_coisas_iot.pdf)

#### História do Unix
* [Site 1](https://www.levenez.com/unix/), [Site 2](https://en.wikipedia.org/wiki/Timeline_of_operating_systems), [Site 3](https://lcomlinux.wordpress.com/a-historia-do-linux/), [Site 4](https://distrowatch.com/)
* [Padrão POSIX](https://pt.wikipedia.org/wiki/POSIX)

#### Explorando Máquinas Virtuais para Instalação de uma Distribuição Linux
* Virtualizador sugerido: [Virtual Box](https://www.virtualbox.org/) instalar também o Extension Pack
* Distribuição sugerida: [Linux Mint](https://linuxmint.com/)

#### Atualizando o sistema operacional (Sistemas com base no Debian)
* sudo su
* apt-get update
* apt-get upgrade
* apt-get dist-upgrade (se necessário)
* apt-get autoremove (se necessário)

#### Instalando um software por apt-get
* Atualizar o sistema operacional (vide item acima)
* Como root:
  * apt-cache search \<parte do nome ou funcionalidade do possível pacote\>
  * apt-get install \<nome do pacote\>

#### Protocolo Git
  * Site de referência - [Fast Version Control ...](https://git-scm.com/)
  * Criar conta no GitHub: https://github.com/
  * [Alternativas ao GitHub](https://pt.wikiversity.org/wiki/Github_x_Gitlab_x_Bitbucket)
  * Utilizando o GitHub - [Tutorial 1](https://rogerdudler.github.io/git-guide/index.pt_BR.html), [Tutorial 2](https://www.hostinger.com.br/tutoriais/comandos-basicos-de-git/), [Tutorial 3](https://gist.github.com/leocomelli/2545add34e4fec21ec16)
  * Exercitar a sintaxe do Markdown: [Tutorial 1](https://docs.pipz.com/central-de-ajuda/learning-center/guia-basico-de-markdown)

  * Comandos selcionados:
    * git help
    * git clone \<URL provida pelo GitHub\>
    * git config --global user.name "Leonardo Comelli"
    * git config --global user.email leonardo@software-ltda.com.br
    * git add meu_arquivo.txt (para adicionar todos os arquivos git add .)
    * git rm meu_arquivo.txt
    * git commit meuarquivo.txt -m "minha mensagem de commit"
    * git push (para enviar arquivos ao diretório remoto)
      * a primeira vez utilizar git push -u origin master
    * git pull (para buscar arquivos diretório remoto)

  * Explorando Scripts no Linux
    * Guia Foca Linux - [Site](https://guiafoca.org/)
    * Livros sobre Bash Scripts - [Diretório](https://drive.google.com/open?id=0B2INSZz1E5TlVWdkVFM0OUxKXzA)
    * Exemplos de Scripts:
      * [Filtro CPU e Memória](http://olaria.ucpel.edu.br/materiais/doku.php?id=script-filtro-informacoes)
      * [Captura Informações Dinâmicas](http://olaria.ucpel.edu.br/materiais/lib/exe/fetch.php?media=script-cpu-dinamico.sh.zip)
 
  * A linguagem Python
    * [Aprendendo Python](https://wiki.python.org.br/AprendaProgramar)
    * [Integrando Bash e Python](http://olaria.ucpel.edu.br/materiais/doku.php?id=integrando-bash-python)

  * Exemplos de Dahsboard
    * [Dashboards para IoT](http://olaria.ucpel.edu.br/materiais/doku.php?id=plataformas_nuvem_iot)
    * [Dahsboards para Linux](https://homelaber.com.br/linux-dashboards-ferramentas-simples-para-monitorar-o-seu-servidor-linux/)
    
 ### Avaliação
 
  * **Cada grupo irá ficar responsável por um dashboard, conforme a seguir:**

      * Grupo 1: [Konker](http://www.konkerlabs.com) - Pablo e Guilherme
      * Grupo 2: [ThingSpeak](https://thingspeak.com/) - Bruno - [Como postar por MQTT](https://nothans.com/thingspeak-tutorials/update-a-thingspeak-channel-using-mqtt-on-a-raspberry-pi)
      * Grupo 3: [Tago IO](https://tago.io/)
      * Grupo 4: [Ubidots](https://ubidots.com/stem/) - Paulo e Rodrigo
     
  * **Ferramentas para Análise Estatística de Grandes Volumes de Dados:**     
      * https://pt.wikipedia.org/wiki/Scilab (Open Source)
      * https://pt.wikipedia.org/wiki/MATLAB (Proprietária)
     
 
  * **Entrega Relatório Parcial:**
    * A data da Entrega Parcial é de **05/04 até 11/04** via a Plataforma Blackboard
    * Relatório descrevendo as características do Dashboard selecionado, podendo ser incluídas figuras, tabelas, etc. A natureza deste relatório é conceitual, focado no entendimento de como opera o Dashboard e quais funcionalidades são disponibilizadas.
    * O arquivo a ser submetido pode estar em formato do MS-Word ou PDF
    
    
  * **Entrega Relatório Final** 
    * O período para a Entrega Final é de **26/04 até 27/04** às 23:59h

  * Para monitorar a ocupação de CPU utilizar um programa para gerar carga sintética, como o abaixo escrito em Bash:

~~~
while [ 1 ]
do
a=7.11/6.79
done
~~~

  * Para tornar executável utilizar no terminal o comando **chmod 755 nome-do-programa.sh**
  * Para executar utilizar **./nome-do-programa.sh**

   
  * **Apresentação do Relatório Final:**
    * Apresentação do Relatório Final será dia **08/05/2021 a partir das 14:00 h** 
    * Avaliar utilizar o Google Docs para produzir de forma colaborativa a apresentação. Vide exemplo neste [link](https://docs.google.com/presentation/d/1CaY3PK5XJZ73Zojp6r_omlfoj-3kg-suxOLtwOEI6rg/edit?usp=sharing) (mesmo disponível abaixo)
    * Entrega Final incluindo diferentes aspectos da operação do Dahsboard 
      * O Relatório correspondente a Entrega Final, no seu início **deverá incluir a parte conceitual, já contemplada no Entrega Parcial**
      * A coleta de informações a serem publicadas no Dashboard poderá ser feita a partir de qualquer equipamento
      * Se necessário podem ser utilizados os equipamentos da Sala 202D. A sala 202D é o local aonde acontecerá o Segundo Encontro Presencial
      * Como exemplo de informações a serem coletadas teríamos: ocupação de CPU, de memória, de disco, volume instântaneo de tráfego, etc.
      * Serão realizadas discussões de procedimentos de captura de informações nas encontros por web conferência, bem como no Segundo Encontro presencial
      * Como exemplo de informações a serem coletadas teríamos: ocupação de CPU, de memória, de disco, volume instântaneo de tráfego, etc.
    * Apresentação 
      * Deverá ser elaborada uma apresentação com duração entre 15 e 30 minutos discorrendo sobre o Dashboard trabalhado 

  * **Exemplo de Uso do LaTeX**
    * [Exemplo de Texto](https://www.overleaf.com/read/cqtvqphcvnyd)
    * [Exemplo de Apresentação](https://www.overleaf.com/read/dwthrxtnchbb)
    * [Dicas sobre o uso de LaTeX](http://olaria.ucpel.edu.br/latex/)

  * **Exemplo de Apresentação explorando o Google Docs**
    * [Exemplo de Apresentação](https://docs.google.com/presentation/d/1CaY3PK5XJZ73Zojp6r_omlfoj-3kg-suxOLtwOEI6rg/edit?usp=sharing)


### Segundo Encontro Presencial - 24/04/2021
 
#### Gravando Dados Coletados em uma Plataforma de Nuvem
  * Registro histórico dos dados: [Exemplo 1](https://fazerlab.wordpress.com/2017/10/24/dados-em-tempo-real-com-planilha-do-google-docs/)
~~~
var planilha = SpreadsheetApp.openById("1cXSm1inxurfARCu9JN12rCpxIAPVEd5KJ1p_P2MxKs0");
var sheet = planilha.getActiveSheet();

function doGet(e)
{
var linhas = sheet.getLastRow();
var rec_cargacpu = e.parameter.cargacpu;
sheet.appendRow([linhas, rec_cargacpu]);
return ContentService.createTextOutput("Ocupação CPU recebida"); 
}
~~~
  * Visualizando os dados: [Exemplo 1](https://fazerlab.wordpress.com/2017/10/30/grafico-dinamico-com-google-script-e-planilha/)
~~~
var planilha = SpreadsheetApp.openById("1uw3kIEHct32iNtlecpOtddExPNEQ6b4A38MZp5HWfLk"); 
var sheet = planilha.getActiveSheet();

function doGet(e)
{
  var linhas = sheet.getLastRow();
  var rec_cpu = e.parameter.cpu;
  sheet.appendRow([linhas, rec_cpu]); 
  //atualizacao: grafico
  var range = sheet.getRange("A1:B120")
  var chart = sheet.getCharts()[0];
  chart = chart.modify()
     .addRange(range)
     .setOption('title', 'Updated!')
     .setOption('animation.duration', 500)
     .setPosition(5,5,0,0)
     .build();
   sheet.updateChart(chart);
  
  //retorna msg para cliente
  return ContentService.createTextOutput("Carga CPU Recebida");
}
~~~
#### Coletando Informações do Meio
  * Empregando Shell Script
~~~
#!/bin/bash
while :
do
CPU_USAGE=$(top -b -n2 -p 1 | fgrep "Cpu(s)" | tail -1 | awk -F'id,' -v prefix="$prefix" '{ split($1, vs, ","); v=vs[length(vs)]; sub("%", "", v); printf "%s%.4f\n", prefix, 100 - v }')

cpu=`(echo $CPU_USAGE | tr . ,)`

echo "Enviando a carga atual da CPU para o Google";
wget https://script.google.com/macros/s/AKfycbyqNdmcL8fv3elwt77DrcBYt3VPykl5rmZ9QsK4nLZRbBZcbkgm/exec?cpu=$cpu 2> /dev/null -O /dev/null;

sleep 10;
done
~~~
  * Empregando uma linguagem de programação
  
#### Transmitindo Informações Sensoriadas do Meio para um Servidor
  * Conceitos
    * [Protocolo MQTT - Material IBM](https://www.ibm.com/developerworks/br/library/iot-mqtt-why-good-for-iot/index.html)
    * [Protocolo MQTT - Material Curto Circuito](https://www.curtocircuito.com.br/blog/introducao-ao-mqtt/)
    * [Slides sobre MQTT - Material UFC](https://pt.slideshare.net/MaurcioMoreiraNeto/protocolo-mqtt-redes-de-computadores)
  * Plataformas de Software
    * [Mosquitto da Eclipse Foundation](https://mosquitto.org)
    * [Brokers MQTT gratuitos e pagos para utilizar em projetos da IoT](https://mntolia.com/10-free-public-private-mqtt-brokers-for-testing-prototyping/)
    * [Explorando o uso de MQTT em Programas Python](https://fazbe.github.io/Usando-o-paho-mqtt-para-Python/)

#### Comunicando com um Broker MQTT utilizando Python

No link a seguir, dicas de como instalar e utilizar o Python: **[Python Brasil](https://python.org.br/)**

##### Procedimento de Subscrição
~~~
# Cliente Python para subscrever em um Broker MQTT
#
# Para instalar o paho-mqtt use o comando pip install paho-mqtt
import paho.mqtt.client as mqtt

# Retorno quando um cliente recebe um  CONNACK do Broker, confirmando a subscricao
def on_connect(client, userdata, flags, rc):
    print("Conectado, com o seguinte retorno do Broker: "+str(rc))

    # O subscribe fica no on_connect pois, caso perca a conexão ele a renova
    # Lembrando que quando usado o #, você está falando que tudo que chegar após a barra do topico, será recebido
    client.subscribe("PI-3A/#")

# Callback responsavel por receber uma mensagem publicada no tópico acima
def on_message(client, userdata, msg):
    print(msg.topic+" "+str(msg.payload))

client = mqtt.Client()
client.on_connect = on_connect
client.on_message = on_message

# Define um usuário e senha para o Broker, se não tem, não use esta linha
# client.username_pw_set("USUARIO", password="SENHA")

# Conecta no MQTT Broker
client.connect("mqtt.eclipse.org", 1883, 60)

# Blocking call that processes network traffic, dispatches callbacks and
# handles reconnecting.
# Other loop*() functions are available that give a threaded interface and a
# manual interface.
# Inicia o loop
client.loop_forever()
~~~
##### Procedimento de Publicação
~~~
# Ensures paho is in PYTHONPATH
import context
# Importa o publish do paho-mqtt
import paho.mqtt.publish as publish

# Publica
publish.single("PI-3A", "Olá Mundo!", hostname="mqtt.eclipse.org")
~~~
