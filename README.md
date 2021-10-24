# mibo-k3s

Objetivo aqui é gravar imagens via rede local de cameras da linha Mibo da Intebras. Laboratorio foi montado com foco nas cameras iC3 e iC5, mas caso você possua modelos iM3 e iM5 leia o pdf. 

Para funcionar corretamente você precisa definir algumas variaveis de ambiente:

     - name: CAM
       value: HOSTNAME
     - name: USER
       value: "admin"
     - name: PASSWD
       value: "XXXX"
     - name: DIR
       value: "/mnt/"

O meu laboratio foi monado em cima de um cluster de raspberry, em outras palavras a imagem funciona apenas com arquitetura ARMv7. Se quiser posso buildar em outra arquitetura ou ensinar como fazer. 
