# Virus-Suave
Essa é pra trolar os amiguinhos que não manjam de TI 

Ok, mas como isso funciona? 

É isso que eu vou te explicar agora.
Pra fazer esses arquivos eu só usei 3 coisas: O bloco de notas, linguagem Batch e alguns comandos do CMD (Prompt de Comando)

Como exemplo, agente vai usar o código do arquivo "GTASanAndreas.exe.bat"

O código é o seguinte:

@echo off

msg * Você não deveria ter aberto este arquivo.

msg * Seu PC será destruído.

shutdown -r -t 10 -c "Destruindo Sistema" 






Começamdo a explicação:

Primeiro comando: @echo off
  Esse comando vai ocultar aquela "telinha preta" do nosso CMD.

Segundo comando: msg 
  Esse é usado para abrir uma "caixinha" com uma mensagem.
 
Terceiro comando: Shutdown -r -t 
  Desliga o computador em um tempo determinado, que no caso do arquivo que estamos usando como exemplo é 10 segundos (10 -c), agora só pra dar um medo no coleguinha
  agente vai colocar uma mensagem antes de que o computador desligar que no caso foi a ("Destruindo Sistema").
  
  Agora pra isso funcionar agente altera a terminação do arquivo de .txt para .bat

Pronto. Agora é só ver o desespero do seu amigo.

