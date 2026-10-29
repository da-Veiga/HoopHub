# HoopHub

**PAP 2027 – TGPSI, Escola Secundária de Vergílio Ferreira**
Aluno: Samuel Cunha · Turma 12.º 13.ª · N.º 23
Professor orientador: Jorge Silva

## Descrição

A HoopHub será uma plataforma web destinada à criação, organização e acompanhamento de torneios de basquetebol. Permitirá que os organizadores criem torneios, definam o formato da competição (1v1, 3v3 ou 5v5), o local, a data, os horários, o número de vagas e, opcionalmente, os prémios. Os utilizadores poderão criar contas, formar equipas e inscrever-se nos torneios disponíveis. A plataforma permitirá também acompanhar os jogos, consultar resultados e classificações, facilitando a comunicação entre organizadores, equipas e jogadores.

## Objetivos

- Desenvolver uma plataforma intuitiva e responsiva para a gestão de torneios de basquetebol.
- Implementar sistemas de registo, autenticação e gestão de permissões dos utilizadores.
- Permitir a criação de torneios, a gestão de equipas e o controlo das inscrições.
- Automatizar a geração de jogos e eliminatórias, bem como a atualização dos resultados e classificações.
- Aplicar conhecimentos de programação, bases de dados e desenvolvimento web adquiridos ao longo do curso.

## Funcionalidades

### Núcleo mínimo (obrigatório)

- [ ] Registo, início de sessão e gestão de perfis de utilizador.
- [ ] Criação, edição e consulta de torneios.
- [ ] Pesquisa de torneios por data, localização e formato.
- [ ] Criação e gestão de equipas e respetivos jogadores.
- [ ] Inscrição de equipas nos torneios, com controlo de vagas e inscrições duplicadas.
- [ ] Gestão de jogos e publicação de resultados pelos organizadores.
- [ ] Base de dados para guardar utilizadores, equipas, torneios, inscrições e resultados.
- [ ] Diferentes permissões para jogadores, organizadores e administradores.

### Extras (se houver tempo)

- [ ] Geração automática de calendários, confrontos e eliminatórias.
- [ ] Atualização automática das classificações e passagem dos vencedores à ronda seguinte.
- [ ] Estatísticas individuais dos jogadores e das equipas.
- [ ] Publicação de fotografias e links para vídeos dos jogos.
- [ ] Sistema de notificações sobre horários, resultados e alterações nos torneios.
- [ ] Listas de espera para torneios com inscrições esgotadas.
- [ ] Painel de controlo com estatísticas e informações para os organizadores.

## Tecnologias

| Camada                         | Tecnologia                                 
| ------------------------------ | ------------------------------------------ 
| Interface                      | HTML5, CSS3, JavaScript e Bootstrap        
| Servidor                       | Java com Spring Boot                       
| Base de dados                  | MySQL                                      
| Controlo de versões            | Git e GitHub                                                                        |
| Ferramentas de desenvolvimento | IntelliJ IDEA ou Eclipse e MySQL Workbench 

## Base de dados (tabelas previstas)

- `Utilizadores` — dados das contas, credenciais e tipo de utilizador.
- `Equipas` — nome, logótipo e capitão de cada equipa.
- `Jogadores_Equipas` — associação entre jogadores e equipas.
- `Torneios` — nome, descrição, formato, local, data, horários e prémios.
- `Inscricoes` — equipas inscritas, torneios associados e estado da inscrição.
- `Jogos` — confrontos, rondas, datas, equipas participantes e resultados.
- `Estatisticas` — estatísticas dos jogadores e das equipas.
- `Multimedia` — links para fotografias e vídeos dos jogos.
