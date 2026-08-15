# Perspicio OS — Roteiro de Desenvolvimento

**Versão do documento:** 0.1  
**Autor:** FB-001  
**Base inicial:** Debian 13 “Trixie”  
**Arquitetura inicial:** amd64

## Objetivo da primeira versão

Produzir uma imagem ISO Live e instalável do Perspicio OS, baseada no Debian 13, com KDE Plasma, interface em português e configurações iniciais de simplicidade e privacidade.

## Fase 1 — Fundação do projeto

- [x] definir o nome Perspicio OS;
- [x] definir propósito e público-alvo;
- [x] registrar os princípios fundamentais;
- [x] criar o repositório Git;
- [x] publicar o projeto no GitHub;
- [x] criar o README;
- [x] definir o KDE Plasma como ambiente gráfico;
- [x] definir a licença do projeto;
- [x] definir a estrutura inicial do repositório.

## Fase 2 — Ambiente de construção

- [x] identificar as ferramentas oficiais do Debian;
- [x] instalar o `live-build`;
- [ ] criar a configuração mínima de construção;
- [ ] documentar os requisitos;
- [ ] testar a geração de uma imagem sem personalizações.

## Fase 3 — Primeira ISO básica

- [ ] gerar uma ISO baseada no Debian 13;
- [ ] incluir o KDE Plasma;
- [ ] configurar português do Brasil;
- [ ] habilitar o modo Live;
- [ ] iniciar a ISO em uma máquina virtual;
- [ ] verificar vídeo, rede, áudio e teclado;
- [ ] registrar os problemas encontrados.

## Fase 4 — Aplicativos e experiência inicial

- [ ] definir os aplicativos essenciais;
- [ ] remover programas desnecessários;
- [ ] configurar navegador, gerenciador de arquivos e suíte de escritório;
- [ ] criar configurações padrão do usuário;
- [ ] preparar uma experiência simples desde o primeiro acesso.

## Fase 5 — Privacidade e segurança

- [ ] revisar serviços iniciados automaticamente;
- [ ] verificar possíveis mecanismos de telemetria;
- [ ] definir configurações de privacidade por padrão;
- [ ] configurar firewall;
- [ ] revisar os aplicativos externos incluídos;
- [ ] documentar claramente os limites de privacidade do sistema.

## Fase 6 — Identidade visual

- [ ] criar logotipo próprio;
- [ ] definir paleta de cores;
- [ ] criar papel de parede;
- [ ] personalizar o KDE Plasma;
- [ ] configurar painel, menu e área de trabalho;
- [ ] definir ícones, tela de login e inicialização;
- [ ] verificar legibilidade e acessibilidade.

## Fase 7 — Instalação e testes

- [ ] incluir e personalizar o instalador gráfico;
- [ ] testar o modo Live;
- [ ] testar a instalação em máquina virtual;
- [ ] testar atualizações;
- [ ] testar instalação em equipamento físico compatível;
- [ ] verificar o funcionamento após reiniciar;
- [ ] produzir e conferir hashes da ISO.

## Fase 8 — Lançamento 0.1.0

- [ ] revisar a documentação;
- [ ] criar instruções de teste e instalação;
- [ ] registrar limitações conhecidas;
- [ ] gerar a ISO candidata;
- [ ] realizar os testes finais;
- [ ] publicar a ISO e os hashes;
- [ ] criar a tag `v0.1.0`.

## Futuro

Depois da primeira versão, poderão ser estudados:

- pacote próprio de configurações do Perspicio OS;
- repositório complementar;
- ferramenta gráfica de boas-vindas;
- processo automatizado de construção;
- versões para outras arquiteturas;
- maior independência técnica do Debian.

Esses itens não fazem parte da primeira versão e somente serão iniciados se forem úteis e sustentáveis.
