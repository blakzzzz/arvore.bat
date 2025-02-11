# __Guia Completo de Comandos Batch__

Este guia fornece uma explicação detalhada sobre como os comandos Batch funcionam, como escrevê-los e usá-los para automatizar tarefas no sistema operacional Windows. O Batch é uma linguagem simples e poderosa que permite criar scripts para automação de tarefas repetitivas.

![comando](https://windowsteam.com.br/wp-content/uploads/2024/12/Como-ativar-o-Windows-11-pelo-CMD.png)

## O que são Comandos Batch?

Comandos Batch são instruções escritas em arquivos com extensão `.bat` ou `.cmd` e são executadas no Prompt de Comando (CMD) do Windows. São usados para automatizar tarefas, como mover ou copiar arquivos, configurar variáveis de ambiente, executar verificações e muito mais.

Os scripts Batch podem ser usados para:

- Automatizar backups e manutenção de sistema.
- Processar arquivos em massa.
- Configurar ou configurar ambientes de desenvolvimento.
- Criar utilitários personalizados.

## Estrutura Básica de um Script Batch
```Batch
Batch Scripting consiste em uma série de comandos a serem executados pelo interpretador de linha de comando, armazenados em um arquivo de texto simples. Não é comumente usado como uma linguagem de programação e, portanto, não é comumente praticado e não é tendência, mas seu controle e domínio no ambiente Windows nunca podem ser negligenciados. Quase todas as tarefas e todas as ações podem ser realizadas e executadas por uma sequência simples de comandos digitados no Prompt de Comando do Windows. 

Execução de script em lote
Há duas maneiras de executar um script em lote.

Digite o script em lote no prompt de comando.
Escreva o código do script em um arquivo e execute-o através do prompt de comando.
Digitar comandos repetidamente no terminal pode ser uma tarefa muito tediosa de se fazer se tivermos um código muito longo. Então, a opção 2 é geralmente preferida para criar arquivos em lote.

Criando arquivos em lote
As etapas para criar um arquivo em lote são bem simples:

Crie um novo arquivo de texto com extensão ' .txt '.
Agora renomeie este arquivo com a extensão ' .bat ', isso criará um arquivo em lote.
Agora abra este arquivo .bat em qualquer editor de texto e comece a criar scripts.
Para começar a fazer scripts, precisamos estar cientes dos comandos da interface batch. Os comandos do Batch são, às vezes, similares aos comandos do Linux Scripting.
```
Comandos em lote
Os comandos básicos de lote não diferenciam maiúsculas de minúsculas e podem ser usados ​​para executar um conjunto específico de instruções:


- DIR – O comando 'dir' é usado para obter todos os diretórios, subdiretórios e arquivos presentes no diretório de trabalho atual.

- CD – O comando 'cd' é usado para alterar o diretório de trabalho atual.

- VER – O comando 'ver' informa a versão do Windows do usuário.

- CLS – O comando 'cls' é usado para limpar a tela do prompt de comando.

- ECHO – O comando 'echo' é 'on' por padrão, mas se o desativarmos com 'echo off' ele desativará o prompt até que o tempo 'echo on' passe.

- @ – O '@' se usado antes de qualquer comando oculta qual comando está sendo executado.

- @ECHO OFF – Este comando serve como ponto de partida para qualquer script de lote básico, pois oculta o prompt com 'echo off' e oculta o comando 'echo off' com '@'.

- HELP – Este comando nos conta tudo sobre os comandos disponíveis no cmd. Ele roda somente se o cmd for executado como um administrador.


![comando](https://media.geeksforgeeks.org/wp-content/uploads/20200708184130/Cmds.png)


## Comandos Comuns:

- ECHO: Escreve na tela.

- ECHO OFF: Oculta informações e o código executado pelo sistema.

- ECHO ON: Exibe informações e o código executado pelo sistema.

- ECHO.: Salta uma linha.

- @ECHO: Faz com que o prompt fique oculto durante toda execução.

- SET: Cria variável que pode ser referenciada através de %variável%.

- CLS: Limpa o console.

- IF e ELSE: Estruturas condicionais.

- GOTO: Avança até determinado trecho do lote.

- FOR: Estrutura de repetição.

- PAUSE: Faz uma pausa, e exibe: “Pressione qualquer tecla para continuar.”

- REM: Utilizado para fazer comentários.

- START: Inicializa um aplicativo ou programa.

- MOVE: Move (recorta) um arquivo de um diretório para outro.

### Este é um **README.md** completo que cobre os principais comandos Batch, suas explicações detalhadas e exemplos práticos. Ele é ideal para ser usado como uma referência ao aprender ou criar scripts Batch. Se precisar de mais detalhes ou ajustes, estou à disposição!

### __comandos ultilizados:__

- __mkdir:__ O comando mkdir no contexto de scripts batch (ou em qualquer terminal de linha de comando) é utilizado para criar um diretório (ou pasta) no sistema de arquivos.

- __cd:__ O comando cd (que significa "Change Directory", ou "Mudar de Diretório") é utilizado para navegar entre diretórios no sistema de arquivos no terminal ou prompt de comando. Ele permite que você altere o diretório atual em que está trabalhando.

- __echo:__ O comando echo é usado para exibir mensagens ou variáveis no terminal (ou no prompt de comando), ou até mesmo para desativar a exibição de comandos em um script.

- __del:__ O comando del (abreviação de delete, ou excluir) é usado para remover arquivos no sistema. Ele permite apagar um ou mais arquivos especificados.

- __rmdir:__ O comando rmdir (abreviação de remove directory, ou remover diretório) é usado para excluir diretórios (pastas) no sistema de arquivos. Ao contrário do comando del, que exclui arquivos, o rmdir serve para apagar diretórios vazios ou, com a opção certa, diretórios que contenham arquivos.

- __cd .. :__ O comando cd .. é usado para mudar para o diretório pai (ou seja, um nível acima no sistema de arquivos). Em termos simples, ele faz você "subir" um diretório na estrutura de pastas.
