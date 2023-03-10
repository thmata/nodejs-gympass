# App

GymPass style app.

## RFs (Requisitos funcionais) -> Funcionalidades da aplicação / O que vai ser possível o usuário fazer na aplicação

- [ ] Deve ser possível se cadastrar;
- [ ] Deve ser possível se autenticar;
- [ ] Deve ser possível obter o perfil de um usuário logado;
- [ ] Deve ser possível obter o número de check-ins realizado pelo usuário logado;
- [ ] Deve ser possível o usuário obter seu histórico de check-ins;
- [ ] Deve ser possível o usuário buscar academias próximas;
- [ ] Deve ser possível o usuário buscar academias pelo nome;
- [ ] Deve ser possível o usuário realizar check-in em uma academia;
- [ ] Deve ser possível validar o check-in de um usuário;
- [ ] Deve ser possível cadastrar uma academia;

## RNs ( Regras de Negócio) -> Caminhos que cada requisito pode tomar (Os "IF's" da aplicação)

- [ ] O Usuário não deve poder se cadastrar com um e-mail duplicado;
- [ ] O Usuário não pode fazer 2 checkk-ins no mesmo dia;
- [ ] O Usuário não pode fazer check-in se não tiver perto (100m) da academia;
- [ ] O Check-in só pode ser validade até 20 min após criado;
- [ ] O check-in só pode ser validade por administradores;
- [ ] A Academia só pode ser cadastrada por administradores;

## RNFs (Requisitos não-funcionais) -> Requisitos tecnicos 

- [ ] A senha do usuário precisa estar criptograda;
- [ ] Os dados da aplicação precisam estar persistidos em um banco PostgreSQL;
- [ ] Todas listas de dados precisam estar paginadas por 20 itens de página;
- [ ] O usuário deve ser identificado por um JWT (JSON Web Token);