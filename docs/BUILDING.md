# Perspicio OS — Construção da Imagem

## Requisitos

- Debian 13 “Trixie”;
- arquitetura amd64;
- conexão com a internet;
- pelo menos 40 GB de espaço livre;
- acesso administrativo com `sudo`;
- caminho do projeto sem espaços;
- pacote `live-build`.

> O `live-build` não permite construir uma imagem a partir de um diretório cujo caminho contenha espaços. Utilize nomes como `perspicio-os`.

## Instalação das ferramentas

```bash
sudo apt update
sudo apt install live-build
