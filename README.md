📚 Sistema de Gestão de Biblioteca

📖 Sobre o Projeto
Sistema completo de gerenciamento de biblioteca desenvolvido em Python com interface gráfica intuitiva. O projeto utiliza a arquitetura MVC (Model-View-Controller) para garantir código organizado, manutenível e escalável.

🎯 Objetivos

Facilitar o controle de empréstimos e devoluções de livros
Gerenciar cadastro de estudantes e acervo bibliográfico
Fornecer relatórios administrativos detalhados
Proporcionar interface amigável para diferentes tipos de usuários

🛠️ Tecnologias Utilizadas

TecnologiaFinalidadePython 3Linguagem de programação principalTkinterBiblioteca para interface gráficaSQLiteSistema de banco de dados embutidoArquitetura MVCPadrão de organização do código

📁 Estrutura do Projeto
O sistema está organizado seguindo o padrão MVC:

Model: Gerenciamento do banco de dados e persistência de dados
View: Interface gráfica e interação com o usuário
Controller: Lógica de negócio e validações

🚀 Como Executar

Pré-requisitos

Python 3.x instalado no sistema
Bibliotecas padrão do Python (Tkinter e SQLite já incluídos)

Instruções de Execução

Clone ou baixe o repositório do projeto
Navegue até o diretório do projeto
Execute o arquivo principal:

bashpython main.py
👥 Tipos de Acesso
🔑 Administrador
Credenciais de acesso:

Senha: 123

Permissões:

➕ Cadastrar novos livros no acervo

👤 Cadastrar estudantes no sistema

📤 Registrar empréstimos de livros

📥 Registrar devoluções

📊 Gerar relatórios gerenciais completos

🎓 Estudante
Credenciais de acesso:

Matrícula cadastrada no sistema

Permissões:

📤 Solicitar empréstimos de livros (até 3 simultâneos)
📥 Realizar devoluções


⚠️ Nota: Caso a matrícula informada não esteja cadastrada, o sistema exibirá mensagem de erro.

⚙️ Funcionalidades Principais
Gestão de Acervo

✅ Cadastro completo de livros (título, autor, ISBN, ano, quantidade)

✅ Controle de disponibilidade em tempo real

✅ Atualização automática do estoque

Gestão de Estudantes

✅ Cadastro com matrícula, nome e curso

✅ Histórico de empréstimos

✅ Controle de limites (máximo 3 livros)

Sistema de Empréstimos

✅ Registro de data de empréstimo

✅ Prazo de devolução automático

✅ Limite de 3 livros por estudante

✅ Validação de disponibilidade

Sistema de Devoluções

✅ Registro de data de devolução

✅ Detecção automática de atrasos

✅ Atualização do estoque

Relatórios Administrativos

📊 Lista de empréstimos ativos

⏰ Estudantes com devoluções em atraso

📈 Estatísticas do acervo

💾 Dados Pré-cadastrados
Estudantes no Sistema
NomeMatrículaCursoRafael1Análise e Desenvolvimento de SistemasErlano2Análise e Desenvolvimento de SistemasCelso3Análise e Desenvolvimento de SistemasDavi4Análise e Desenvolvimento de Sistemas
Acervo Disponível
TítuloISBNAutorAnoQuantidadeO Pequeno Príncipe1Antoine de Saint-Exupéry19431Divina Comédia2Dante Alighieri13049
Empréstimos Ativos

Estudante: Celso
Livro: Divina Comédia

🔄 Fluxo de Utilização

Inicialização: Execute o sistema através do arquivo main.py
Seleção de Perfil: Escolha entre Administrador ou Estudante
Autenticação: Informe senha (admin) ou matrícula (estudante)
Acesso ao Menu: Utilize as funcionalidades conforme seu nível de acesso
Operações: Realize cadastros, empréstimos, devoluções ou consultas

📋 Regras de Negócio

Cada estudante pode emprestar no máximo 3 livros simultaneamente
O sistema verifica automaticamente a disponibilidade antes de emprestar
Devoluções com atraso são identificadas e sinalizadas
Apenas administradores podem cadastrar livros e estudantes
O estoque é atualizado automaticamente em cada operação

🤝 Contribuições

Este projeto foi desenvolvido como trabalho acadêmico. Sugestões e melhorias são bem-vindas!
📄 Licença
Projeto desenvolvido para fins educacionais.

Desenvolvido com ❤️ para facilitar a gestão de bibliotecas
