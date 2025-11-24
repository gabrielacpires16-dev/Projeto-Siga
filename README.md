

## 📕 Sobre o Projeto
veja mais aqui :https://gabrielacpires16-dev.github.io/apresenta-o-siga-2.0/


O **SIGA** (Sistema de Gerenciamento Acadêmico) é um sistema web interativo desenvolvido para simular um portal acadêmico da FATEC. Ele permite que alunos e professores acessem e gerenciem informações acadêmicas de forma intuitiva e responsiva. O projeto foi criado usando tecnologias puras da web (HTML, CSS e JavaScript), sem frameworks externos, focando em simplicidade, usabilidade e persistência de dados via localStorage.

Este é um trabalho acadêmico mockado, ideal para demonstrações de interfaces de usuário, gestão de dados locais e interações dinâmicas em aplicações web.

## 🚀 Funcionalidades

### Para Alunos:
- **Home e Novidades**: Dashboard inicial com feed de notícias e eventos da FATEC.
- **Notas, Faltas e Horário**: Visualização de desempenho acadêmico, frequência e cronograma semanal.
- **Disciplinas, Histórico e Documentos**: Acesso a ementas, histórico escolar e downloads de documentos.
- **Solicitações**: Revisão de notas/faltas, rematrícula, Atividades Especiais (AE), Regime Domiciliar e Atividades Complementares (AC).
- **Perfil**: Informações pessoais (nome, RA, curso, PP/PR/PPI).

### Para Professores:
- **Turmas e Cadastro**: Gerenciamento de turmas, alunos e horários; criação de novas turmas.
- **Faltas e Chamada**: Registro de justificativas de faltas e realização de listas de presença por disciplina.
- **Lançamento de Notas**: Postagem de notas com métricas detalhadas (testes, trabalhos, participação), incluindo descrições e observações.
- **Solicitações**: Revisão e aprovação/rejeição de pedidos de alunos.
- **Perfil**: Estatísticas pessoais (total de turmas e alunos gerenciados).

### Recursos Gerais:
- Tema claro/escuro alternável.
- Login seguro com credenciais demo (aluno/professor com senha "123").
- Armazenamento local para persistência de dados (notas, faltas, turmas).
- Design responsivo, adaptável a dispositivos móveis.

## 🛠 Tecnologias Utilizadas

- **HTML5**: Estrutura das páginas e formulários.
- **CSS3**: Estilização com variáveis CSS para temas, gradientes, animações (fade-in, slide-up) e responsividade.
- **JavaScript (ES6+)**: Lógica interativa, manipulação de DOM, armazenamento local e validações.

Nenhuma biblioteca externa foi usada para manter o projeto leve e focado em conceitos fundamentais.

## 📋 Diagrama de Uso

O diagrama de casos de uso (use case diagram) simplificado mostra as interações principais:

```
+-------------------+     +-------------------+
|      Aluno        |     |    Professor      |
+-------------------+     +-------------------+
| - Visualizar      |     | - Gerenciar       |
|   notas/faltas    |     |   turmas/alunos   |
+-------------------+     +-------------------+
          |                           |
          v                           v
+---------------------------------------------+
|                SIGA System                  |
+---------------------------------------------+
| Use Cases:                                  |
| - Login (comum)                             |
| - Consultar Novidades (aluno)               |
| - Visualizar Horário/Notas (aluno)          |
| - Enviar Solicitações (aluno)               |
| - Cadastrar Turmas/Alunos (professor)       |
| - Postar Notas com Métricas (professor)     |
| - Aprovar Solicitações (professor)          |
+---------------------------------------------+
```

- **Atores**: Aluno (consulta e solicita) e Professor (gerencia e avalia).
- **Sistema**: Facilita ações como login, consultas e gestão.

## 🎨 Protótipo das Telas

O projeto inclui protótipos de telas principais, baseados no código HTML/CSS:

- **Tela de Login**: Overlay com campos de usuário/senha, botões de entrada e demo. Fundo gradiente rosado, card vermelho.
- **Dashboard do Aluno**: Header com nav em grid (tiles com ícones), seções para home/novidades com cards de eventos.
- **Dashboard do Professor**: Nav para turmas/notas, grids de cards e formulários para lançamento de notas com métricas.

Para visualizar, abra o arquivo `index.html` em um navegador. Screenshots podem ser capturados para demonstrações.

## 🚀 Como Usar

1. **Abra o Arquivo**:
   - Abra `index.html` em qualquer navegador moderno (Chrome, Firefox, etc.).
   - Use credenciais demo: 
     - Aluno: usuário `aluno` ou `aluno123`, senha `123`.
     - Professor: usuário `professor`, senha `123`.

2. **Navegue**:
   - Clique nos tiles para alternar seções.
   - Teste funcionalidades como lançar notas ou enviar solicitações (dados são salvos localmente).

## 📁 Estrutura do Projeto

```
siga/
├── index.html          # Arquivo principal com HTML, CSS e JS inline
├── README.md           # Este arquivo
└── 
```

O código é autocontido em um único arquivo HTML para simplicidade.

## 🤝 Contribuição

Este é um projeto acadêmico. Sugestões são bem-vindas via issues ou pull requests. Para contribuir:
- Faça um fork do repositório.
- Crie uma branch para suas mudanças.
- Teste em navegadores modernos.

## 📄 Licença

Este projeto é para fins educacionais. Não possui licença específica; use e modifique conforme necessário para aprendizado.

---

**Autor**: [Gabriela Pires]
