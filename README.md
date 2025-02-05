Sistema de Gerenciamento de Usuários Robusto e Seguro com Flask (ou FastAPI)

Tecnologias utilizadas
Framework: Flask (ou FastAPI)
Banco de dados: PostgreSQL (ou SQLite)
Autenticação: Flask-JWT-Extended (JWT) ou Flask-Login (sessões)
Gerenciamento de senhas: Flask-Bcrypt (hashing) e Flask-Mail (recuperação de senha)
ORM: SQLAlchemy
Funcionalidades
Cadastro e Login: Usuários podem se cadastrar de forma segura e acessar o sistema com login.
Roles e Permissões: Defina diferentes níveis de acesso (admin, user, etc.) e atribua permissões específicas para cada role.
Autenticação via JWT ou sessões: Escolha o método de autenticação que melhor se adapta às suas necessidades. O JWT oferece escalabilidade e flexibilidade, enquanto as sessões são mais simples de implementar.
Recuperação de senha por e-mail: Usuários podem recuperar suas senhas de forma segura através de um link enviado por e-mail.
Painel de gerenciamento para admins: Interface intuitiva para admins gerenciarem usuários (criar, editar, remover, etc.).
Proteção de rotas: Restrinja o acesso a determinadas rotas, permitindo que apenas usuários com permissões específicas (ex: admins) as acessem.
