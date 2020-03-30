---
description: >-
  Backup & restore manager plugin allows to keep your settings safe and restore
  them in case of troubles with the application.
---

# Backup & restaurador

## General

O plug-in do gerenciador de backup e restauração permite manter suas configurações seguras e restaurá-las em caso de problemas com o aplicativo. Essa ferramenta inteligente pode fazer backup de suas configurações globais, credenciais de conexões, áreas de trabalho e configurações de layout por painel em um arquivo local, que pode ser usado posteriormente para restaurá-las em vários cliques..

![Backup &amp; restore master starting screen](../.gitbook/assets/backupmanager.png)

## Configurações de backup

O processo de backup é fácil e não requer muitas explicações. Apenas selecione o caminho em que seu arquivo de backup será armazenado \(pasta de backups do Quantower por padrão; recomendado\) e pressione o botão \[**CRIAR BACKUP**\]..

![](../.gitbook/assets/backupsettings1.png)

Uma vez iniciado o processo, você verá a tela de progresso, mostrando o fluxo do processo de backup. Quando o backup estiver concluído, você pode pressionar o botão \[FINISH\] para acessar a tela inicial. Cada backup é criado com o nome automático pelo modelo: “Date Time.zip”.

{% hint style="info" %}
Você pode encontrar alguns arquivos de backup na pasta Quantower Backup, contendo a letra “A” no final - esses são os backups automáticos, feitos periodicamente pelo Quantower \(diariamente, substituídos a cada 5 minutos\).
{% endhint %}

## Restore settings

In case you want to restore some previous settings or wish to apply some custom settings \(got from another Quantower user, that backed up its settings previously\), follow the **\[ RECOVER SETTINGS \]** button.

![Recover your settings in several clicks](../.gitbook/assets/restoresettings.png)

Aqui você encontra duas maneiras de selecionar arquivos de backup::

* Da pasta de backups 
* Do arquivo personalizado

A “pasta Backups” é a pasta padrão do Quantower, onde ele salva todos os arquivos de backup criados automaticamente e propõe que você armazene o seu, criado manualmente. O gerenciador de backup e restauração verifica essa pasta e exibe todos os arquivos encontrados para importar as configurações. Você também pode selecionar um local diferente do seu arquivo de backup, usando a opção “Do arquivo personalizado”..

{% hint style="warning" %}
Verifique se você está especificando o arquivo de backup correto \(criado pelo gerente da B&R anteriormente\) para evitar problemas com a importação e restauração de configurações.
{% endhint %}

Depois de selecionar o arquivo de backup necessário e pressionar o botão \[INICIAR RECUPERAÇÃO\], você verá o processo de recuperação fluir. Quando terminar, você será perguntado sobre a reinicialização do aplicativo. Esta é a ação necessária para aplicar suas configurações importadas recentemente..

{% hint style="success" %}
Em caso de problemas com o arquivo de backup, o gerente da B&R manterá suas configurações atuais do Quantower e o informará sobre isso.
{% endhint %}

