## Nos
- 94230 Samuel Barata
- Fabio Sousa
- Pedro Godinho

## o q n funciona:

- VLANS/DHCP AS10 apenas funcionam nos PCs de alguns elementos do grupo (v 2.2.17)
- PCS do AS10 nao conseguem ligar a nada fora da rede
    - Os endereços sao convertidos pela nat mas nao recebem resposta
- Tentamos configurar eBGP com ipv6 entre os routers R1 e R2 mas nao conseguimos sem estragar o ipv4
- IPV6 tem endereços atribuidos nas redes AS 20/30/40 mas nºao ha inter doamin routing com ipv6
- Nao conseguimos remover a rota 7.0.0.0 partilhada pelo rip do AS 10/20 para dentro do ospf/bgp
- Nao removemos VLAN1 routing no SwR9