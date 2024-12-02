# OlimpiaSales
Sistema pensado sobre a rede Salesiana referente a Olimpiadas Salesiana

---

**OlimpiaSales** é um sistema multiplataforma desenvolvido para o gerenciamento e visualização em tempo real das **Olimpíadas Salesianas**, um evento bienal que reúne estudantes de diferentes níveis de ensino em competições esportivas. O projeto é voltado para a organização eficiente e a exibição de dados em tempo real durante o evento, proporcionando uma experiência interativa para atletas, organizadores e espectadores.

## Tecnologias Utilizadas

- **Front-end:** React (para web) / React Native (para dispositivos móveis)
- **Back-end:** Node.js
- **Database:** MySQL + PHPMyAdmin
- **Hospedagem e Deployment:** Vercel

## Funcionalidades

### Para Celulares e Tablets

- **Modo Atleta:** Exibe os jogos do dia, ranking, e notícias.
- **Modo Organizador:** Permite o gerenciamento de dados, como agendamento de jogos, controle de resultados e atualização de rankings.
- **Notificações:** Recebe alertas sobre mudanças nos jogos e outros eventos importantes.

### Para Desktop e Web

- **Interface de Atleta e Organizador:** Exibe todas as informações necessárias, incluindo jogos, ranking, e notícias.
- **Funções Administrativas:** Os organizadores podem acessar dados mais detalhados e realizar o gerenciamento completo da competição.
- **Visualização em Tempo Real:** Atualizações instantâneas de resultados e status dos jogos.

### Para TVs

- **Dashboard em Tempo Real:** 
  - 30% da tela para exibir o ranking dos times.
  - 60% da tela para exibir os jogos atuais e os próximos agendados.

## Estrutura do Projeto

- **Front-end (React/React Native):**
  - Componentes responsivos para exibição de informações sobre os jogos e ranking.
  - Funcionalidade para alternar entre modos "Atleta" e "Organizador".
  
- **Back-end (Node.js):**
  - API RESTful para gerenciar dados de jogos, equipes, resultados e usuários.
  - Comunicação em tempo real com **Socket.IO** para atualizações dinâmicas de resultados e ranking.

- **Database (MySQL + PHPMyAdmin):**
  - Armazenamento de dados estruturados sobre os jogos, equipes, resultados, e usuários.
  - PHPMyAdmin para administração do banco de dados.

## Instalação e Execução Local

### Requisitos

- Node.js (>= 14.x)
- MySQL (ou qualquer serviço compatível com MySQL)
- Conta no Vercel (para deployment)

### Passos para Execução Local

1. **Clonar o repositório:**
   ```bash
   git clone https://github.com/gabsouza-dev/olimpiasales.git
   cd olimpiasales
   ```

2. **Instalar as dependências:**
   - No diretório do **front-end (React)**:
     ```bash
     cd front-end
     npm install
     ```
   - No diretório do **back-end (Node.js)**:
     ```bash
     cd back-end
     npm install
     ```

3. **Configurar o banco de dados MySQL:**
   - Crie um banco de dados no MySQL com o nome `olimpiasales`.
   - Importe o esquema do banco de dados usando o **phpMyAdmin** ou comandos SQL.

4. **Rodar a aplicação localmente:**
   - No diretório do **front-end**, execute:
     ```bash
     npm start
     ```
   - No diretório do **back-end**, execute:
     ```bash
     npm start
     ```

5. Acesse a aplicação no navegador em: [http://localhost:3000](http://localhost:3000)

## Deployment

O projeto está hospedado no **Vercel** para deploy contínuo. Sempre que houver alterações no repositório, o Vercel realizará o deploy automático.

## Contribuindo

1. Faça o fork deste repositório.
2. Crie uma branch para sua modificação (`git checkout -b feature/nova-funcionalidade`).
3. Comite suas mudanças (`git commit -am 'Adiciona nova funcionalidade'`).
4. Push para a branch (`git push origin feature/nova-funcionalidade`).
5. Abra um Pull Request.

## Licença

Distribuído sob a licença MIT. Veja `LICENSE` para mais informações.

## Contato

- Nome: [Gabriel Costa de Souza]
- Email: [dev.gbrlsouza@gmail.com]
- GitHub: [github.com/gabsouza-dev](https://github.com/gabsouza-dev)
