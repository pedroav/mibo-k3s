# mibo-k3s

Objetivo aqui é gravar imagens via rede local de cameras da linha Mibo da Intebras. Laboratorio foi montado com foco nas cameras iC3, iC5 e iM5. 

Para funcionar corretamente você precisa definir algumas variaveis de ambiente:

     - name: CAM
       value: HOSTNAME
     - name: USER
       value: "admin"
     - name: PASSWD
       value: "XXXX"
     - name: DIR
       value: "/mnt/"

Atenção! Meu ambiente é um cluster de raspberry pi então as imagens funcionam apenas com arquitetura ARMv7. 
