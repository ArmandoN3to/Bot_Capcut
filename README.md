# 📹 Bot de Automação para Upload, Legendagem e Organização de Vídeos

Este projeto implementa um bot utilizando o framework da BotCity para automatizar o processo de upload de vídeos, adição de legendas, download de vídeos legendados e organização em pastas específicas. O bot foi desenvolvido em equipe na **DX ZL Academy** com o objetivo de simplificar o fluxo de trabalho para criadores de conteúdo.

## 🛠 Funcionalidades

1. **Upload Automático de Vídeos para Legendagem**
   - O bot permite a seleção de um ou mais vídeos para upload automático em um software específico de legendagem, eliminando a necessidade de uploads manuais.

2. **Seleção Automática da Opção de Legendagem**
   - Após o upload, o bot seleciona automaticamente a opção de adicionar legendas, agilizando o processo e reduzindo a intervenção manual.

3. **Download Automático de Vídeos Legendados**
   - O bot monitora o progresso da legendagem e realiza o download automático dos vídeos legendados assim que o processo é concluído.

4. **Organização Automática dos Vídeos em Pastas Específicas**
   - Os vídeos legendados são automaticamente movidos para pastas específicas com base em critérios predefinidos, como categoria, facilitando a gestão e localização dos vídeos.

5. **Monitoramento e Notificações do Processo de Automação**
   - O sistema fornece notificações em tempo real sobre o progresso de cada etapa do processo, incluindo upload, legendagem, download e organização, garantindo que o usuário esteja sempre informado sobre o andamento.

## 🎯 História de Usuário & Critérios de Aceitação

### 1. Upload Automático de Vídeos para Legendagem
**Como criador de conteúdo,**
Eu quero que o sistema faça o upload automático dos meus vídeos para o site de legendagem,  
**Para que** eu não precise fazer o upload manualmente e possa economizar tempo no processo de edição.

**Critérios de Aceitação:**
- O sistema deve permitir a seleção de um ou mais vídeos para upload.
- O sistema deve fazer o upload dos vídeos selecionados automaticamente para o software de legendagem específico.

### 2. Seleção Automática da Opção de Legendagem
**Como criador de conteúdo,**
Eu quero que o sistema selecione automaticamente a opção de adicionar legendas após o upload do vídeo,  
**Para que** eu não precise fazer essa escolha manualmente e o processo seja mais rápido.

**Critérios de Aceitação:**
- O sistema deve detectar automaticamente quando o upload foi concluído.
- O sistema deve selecionar a opção de legendagem no site automaticamente.

### 3. Download Automático de Vídeos Legendados
**Como criador de conteúdo,**
Eu quero que o sistema baixe automaticamente os vídeos legendados após a conclusão do processo de legendagem,  
**Para que** eu tenha os vídeos prontos para organizar e publicar sem precisar monitorar constantemente o processo.

**Critérios de Aceitação:**
- O sistema deve monitorar o status da legendagem no site e iniciar o download automaticamente quando a legendagem estiver concluída.
- Os vídeos devem ser baixados para um local predefinido ou configurável.

### 4. Organização Automática dos Vídeos em Pastas Específicas
**Como criador de conteúdo,**
Eu quero que o sistema organize automaticamente os vídeos legendados em pastas específicas com base em critérios que eu definir,  
**Para que** eu possa encontrar e gerenciar meus vídeos de forma mais eficiente.

**Critérios de Aceitação:**
- O sistema deve permitir definir critérios de organização, como categoria.
- Após o download, os vídeos devem ser movidos automaticamente para as pastas corretas com base nos critérios definidos.

### 5. Monitoramento e Notificações do Processo de Automação
**Como criador de conteúdo,**
Eu quero ser notificado em tempo real sobre o progresso de cada etapa do processo de automação (upload, legendagem, download e organização),  
**Para que** eu possa acompanhar o andamento e ser informado imediatamente em caso de erros ou problemas.

**Critérios de Aceitação:**
- O sistema deve fornecer atualizações em tempo real sobre o status de upload, legendagem, download e organização dos vídeos.

## 🚀 Como Executar o Projeto

### Pré-requisitos
- Python 3.x
- Framework BotCity
- Biblioteca OS e Shutil
- Software de legendagem (CapCut ou outro específico)

### Instalação
1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/nome-do-repositorio.git
   ```
2. Instale as dependências:
   ```bash
   pip install -r requirements.txt
   ```
3. Execute o bot:
   ```bash
   python bot.py
   ```
