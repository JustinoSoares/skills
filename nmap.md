## Estudos sobre o comando nmap

- Instalar o nmap
``` bash
sudo dnf install nmap
```
- Comando para fazer o scanner de vários domineos ou IPs ao mesmo tempo
```bash
nmap -iL nome_arquivo
```
  - Exemplo de arquivo
  ```
  google.com

  facebook.com

  instagram.com
  ```
