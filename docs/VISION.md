# Perspicio OS — Visão do Projeto

**Versão do documento:** 0.1  
**Autor:** FB-001  
**Base inicial:** Debian 13 “Trixie”  
**Arquitetura inicial:** amd64

## Visão

O Perspicio OS será uma distribuição Linux criada para tornar o computador simples, prático e seguro para o usuário comum, preservando sua privacidade, sua liberdade de escolha e seu controle sobre o próprio equipamento.

O sistema deverá funcionar bem desde a instalação, sem exigir conhecimentos técnicos, contas on-line obrigatórias ou configurações complicadas de privacidade.

## Propósito

Simplificar a vida do usuário final por meio de um sistema operacional fácil de instalar e usar, que respeite seus dados e não transforme sua atividade em produto.

## Público-alvo

Pessoas que desejam um sistema fácil e prático para as tarefas diárias, sem precisar conhecer profundamente Linux ou realizar diversas configurações depois da instalação.

O usuário deverá ter confiança de que o Perspicio OS não coleta nem transmite seus dados para o projeto. Aplicativos e serviços externos serão escolhidos e apresentados com critérios claros de privacidade.

## Princípios fundamentais

### 1. Privacidade por padrão

As configurações iniciais deverão proteger o usuário sem exigir que ele procure opções escondidas ou compreenda detalhes técnicos.

### 2. Simplicidade

O sistema deverá ser fácil de instalar, compreender e utilizar nas atividades cotidianas.

### 3. Liberdade de escolha

Nenhuma conta on-line será obrigatória. O usuário poderá instalar, remover e substituir programas livremente.

### 4. Transparência

Os componentes, as configurações e as decisões do projeto deverão ser documentados e explicáveis.

### 5. Controle local

Sempre que possível, arquivos, configurações e processamento permanecerão no computador do usuário.

### 6. Sem telemetria própria

O Perspicio OS não coletará dados de utilização para o projeto.

### 7. Segurança sem aprisionamento

A segurança deverá proteger o usuário sem retirar seu controle sobre o sistema ou limitar artificialmente suas escolhas.

## Escopo inicial

A primeira versão será uma distribuição para computadores de 64 bits, baseada no Debian 13 “Trixie”. Inicialmente, o projeto utilizará os pacotes, repositórios e atualizações de segurança do Debian.

A primeira versão deverá oferecer:

- imagem ISO inicializável;
- modo Live para teste sem instalação;
- instalação em português;
- instalador gráfico;
- ambiente gráfico simples e organizado;
- conjunto reduzido de aplicativos essenciais;
- ausência de conta on-line obrigatória;
- configurações de privacidade aplicadas por padrão;
- atualizações de segurança provenientes do Debian;
- documentação simples para o usuário final.

## Fora do escopo inicial

Não fazem parte da primeira etapa:

- desenvolvimento de um kernel próprio;
- criação de um gerenciador de pacotes próprio;
- manutenção independente de todos os pacotes;
- versões para celulares;
- suporte simultâneo a várias arquiteturas;
- serviços on-line próprios do ecossistema Perspicio.

Essas possibilidades poderão ser estudadas no futuro, depois que a versão para computadores estiver estável e utilizável.

## Identidade

**Nome do sistema:** Perspicio OS  
**Frase provisória:** *Simples para usar, privado por princípio.*

Perspicio será a identidade principal do ecossistema. O nome poderá ser utilizado em outros produtos, mantendo uma relação clara entre o sistema operacional e as demais ferramentas do projeto.

## Direção de desenvolvimento

O projeto será desenvolvido em etapas pequenas, documentadas e testáveis. Cada parte deverá ser validada antes da inclusão de novas funções.

A evolução prevista é:

1. edição personalizada do Debian 13;
2. primeira ISO Live e instalável;
3. configurações e identidade próprias;
4. pacotes próprios para configurações do Perspicio OS;
5. repositório próprio complementar;
6. aumento gradual da independência técnica, caso isso continue sendo útil e sustentável.

## Compromisso central

O Perspicio OS deverá tornar a privacidade uma característica normal do sistema, e não uma tarefa adicional imposta ao usuário.
