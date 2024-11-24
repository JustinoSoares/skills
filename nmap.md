## Estudos sobre o comando nmap

- Instalar o nmap
``` bash
sudo dnf install nmap
```
- Comando para fazer o scanner de vários domineos ou IPs ao mesmo tempo
```bash
nmap -iL nome_arquivo
```
Exemplo de arquivo
```
google.com 

facebook.com

instagram.com
```
- Comando para fazer scanner em IPs aleatórios
```bash
nmap -iR `quantidade_de_hosts`
```
- Como fazer o scanner de um ip específico e excluir alguns ips que estão dentro dele
```bash
nmap `IP_alvo` --exclude `IP1`,`IPs`
```
Se quisermos excluir IPs que estão dentro de um arquivo
```bash
nmap `IP_alvo` --excludefile `caminho da imagem`
```
- Como listar todos os IP dentro da rede que estás conectado
```bash
nmap -sL 192.168.1.1/24
```
