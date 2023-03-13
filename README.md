
# **GymPass style app**
- ## **RFs** (Requisitos Funcionais)
    - [ ] Deve ser possível se cadastrar;
    - [ ] Deve ser possível se autenticar;
    - [ ] Deve ser possível obter o perfil de um usuário logado;
    - [ ] Deve ser possível obter o número de check-ins realizados pelo usuário logado;
    - [ ] Deve ser possível o usuário obter seu histórico de check-ins;
    - [ ] Deve ser possível o usuário buscar academias próximas;
    - [ ] Deve ser possível o usuário buscar academias por nome;
    - [ ] Deve ser possível o usuário realizar check-in em uma academia;
    - [ ] Deve ser possível validar o check-in de um usuário;
    - [ ] Deve ser possível cadastrar uma academia;

- ## **RNs** (Regras de Negocio)
    - [ ] O usuário não pode se cadastrar com um e-mail já existente;
    - [ ] O usuário não pode fazer 2 check-ins no mesmo dia;
    - [ ] O usuário não pode fazer check-in se não estiver perto (100m) da academia;
    - [ ] O check-in só pode ser validado até 20 minutos após criado;
    - [ ] O check-in só pode ser validado por administradores;
    - [ ] A academia só pode ser cadastrada por administradores;

- ## **RNFs** (Requisitos não-funcionais)
    - [ ] A senha do usuário deve ser armazenada criptografada;
    - [ ] Os dados da aplicação devem ser armazenados em um banco de dados PostgreSQL;
    - [ ] Todas listas de dados precisam estar paginadas com 20 itens por página;
    - [ ] O usuário deve ser identificado por um token JWT(JSON Web Token);