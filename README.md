# Rundeck Exporter Helm Chart
Este é um Helm Chart para o aplicativo Rundeck Exporter. Ele permite que você implante e gerencie facilmente o Exporter em um cluster Kubernetes.

## Pré-requisitos

- [Helm](https://helm.sh) instalado no seu ambiente.
- Acesso a um cluster Kubernetes.

## Instalação

1. Clone este repositório para o seu ambiente local usando o comando `git clone`:

   ```sh
   git clone https://github.com/nataliagranato/rundeck-exporter.git

2. Navegue até o diretório do Helm Chart:
   ```sh
   cd rundeck-exporter

3. Instale o Helm Chart no seu cluster Kubernetes usando o comando:
   ```sh
   helm install rundeck-exporter -n NAMESPACE .

# Configuração
O Helm Chart pode ser configurado através do arquivo values.yaml dentro do diretório do chart. Consulte o arquivo para ver as opções disponíveis.

# Desinstalação
Para desinstalar o Helm Chart, utilize o seguinte comando:
   ```sh
   helm uninstall rundeck-exporter -n NAMESPACE .
   ```
Isso removerá todas as instâncias do aplicativo do seu cluster Kubernetes.

# Contribuições
Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou pull requests neste repositório.


Certifique-se de personalizar as URLs, nomes de diretórios e informações conforme necessário para o seu Helm Chart específico. Este exemplo fornece instruções básicas para clonar o repositório, instalar e configurar o Helm Chart, bem como opções de desinstalação, contribuições e informações de licença.
