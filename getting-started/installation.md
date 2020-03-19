---
description: >-
  Requisitos de sistema são 3 etapas simples para instalar com sucesso a
  plataforma
---

# Instalação

* [**Pre-requisito para instalação da plataforma**](installation.md#pc-requirements)\*\*\*\*
* \*\*\*\*[**Etapas da instalação**](installation.md#installation-steps)\*\*\*\*
* \*\*\*\*[**Uninstallation**](installation.md#uninstall)\*\*\*\*

Depois de baixar o aplicativo Quantower no site oficial da Quantower - você estará pronto para iniciar um processo de instalação. A partir deste ponto, devemos esclarecer as principais diferenças entre o "processo de instalação" da Quantower e o processo de instalação padrão do Windows®, aos quais a maioria dos usuários está conhecem..

{% embed url="https://youtu.be/155Ha6Rku0E" caption="" %}

{% hint style="success" %}
A Quantower não copia seus arquivos para as pastas do sistema \(AppData ou Arquivos de Programas\) do sistema operacional, nem grava alterações no registro do sistema
{% endhint %}



O que isso significa? O programa não viola a integridade do sistema operacional e, em caso de remoção, não deixa nenhuma impressão de sua presença no seu computador. O "instalador" da Quantower literalmente extrai arquivos para a pasta especificada pelo usuário.

Essa abordagem permite armazenar \(e iniciar\) a Quantower na unidade removível para uso em qualquer outro computador como aplicativo portátil. Pode ser conveniente quando você precisar mover o Quantower com todas as suas configurações para outro PC; basta copiar a pasta Quantower e colar onde você precisar.

## PC pre-requisitos

{% hint style="info" %}
* Windows 10
* .NET Framework v.4.7.2
* Armanezamento - 1 GB \(depende do volume do histórico carregado\)
{% endhint %}

{% hint style="warning" %}
A Microsoft parou oficialmente de oferecer suporte ao Windows 8 e Windows 7. Portanto, a plataforma pode não iniciar ou pode funcionar incorretamente.. [More information on supported versions, please check on official Microsoft website.](https://support.microsoft.com/en-us/help/13853/windows-lifecycle-fact-sheet)

N's recomendamos o uso do Windows 10.
{% endhint %}

## Etapas da Instalação

![Quantower installer screen](../.gitbook/assets/extract-files-quantower.png)

1. [**Faça o download da plataforma**](https://updates.quantower.com/Quantower/x64/latest/Quantower.exe) onde deseja ser instalado e execute o arquivo _**Quantower\_br.exe**_ 
2. Selecione a pasta para extrair os arquivos do aplicativo
3. Após a conclusão do processo de extração, a plataforma iniciará automaticamente com a conexão da **Binance** no Modo Info e com a área de trabalho padrão

{% hint style="warning" %}
Observe que você pode precisar permitir uma conexão de entrada e saída para o arquivo Starter.exe \(o principal executável da Quantower plataforma\) nas configurações do seu Firewall
{% endhint %}

![](../.gitbook/assets/default-workspace.png)

## Desinstalação 

Se você precisar desinstalar o aplicativo, **basta excluir a pasta com todos os arquivos do aplicativo**. Você também pode manter suas configurações pessoais \(informações de conexão e áreas de trabalho\) copiando a pasta Configurações \(pode ser encontrada diretamente na pasta Quantower\) antes de excluir o aplicativo. Essa pasta Configurações pode ser colada em qualquer outra pasta Quantower posteriormente.

Você também pode consultar [**Backup & Restorador**](backup-and-restore-manager.md)  que permit fazer backup de suas configurações em um arquivo e restaure-as mais tarde.

