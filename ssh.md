# gerar chave com

- ssh-keygen

# copia o conteudo da chave pública

# copia dentro do authorized_keys dentro da vps (~/root/.ssh/authorized_keys)

- na máquina que vai acessar a vps criar arquivo config e copiar dentro:

1 - nano config
conteúdo dentro do arquivo

ex:
Host targaryen
HostName 192.168.1.10
User daenerys
Port 7654
IdentityFile ~/.ssh/targaryen.key

como ficou:
Host vps
HostName 3.138.203.27
User root
IdentityFile ~/.ssh/id_rsa
