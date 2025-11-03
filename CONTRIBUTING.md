# Guia de Contribuição

## 🎆 Bem-vindo ao Projeto!

Obrigado por seu interesse em contribuir com este projeto! Este guia vai te ajudar a entender como colaborar de forma eficaz.

## 📄 Código de Conduta

Este projeto adere aos mais altos padrões de conduta profissional. Esperamos que todos os colaboradores sejam:

- **Respeitosos** e colaborativos
- **Construtivos** em feedbacks e discussões
- **Inclusivos** e acolhedores a novos colaboradores
- **Profissionais** na comunicação

## 🚀 Como Contribuir

### 1. Preparando o Ambiente

```bash
# 1. Fork o repositório
# 2. Clone seu fork
git clone https://github.com/seu-usuario/projeto-fullstack-estruturado.git
cd projeto-fullstack-estruturado

# 3. Adicione o repositório original como upstream
git remote add upstream https://github.com/AD-Thiago/projeto-fullstack-estruturado.git

# 4. Crie uma branch para sua contribuição
git checkout -b feature/sua-contribuicao
```

### 2. Tipos de Contribuição

#### 🔍 **Melhorias na Documentação**
- Correções de texto e ortografia
- Adição de exemplos práticos
- Traduções
- Melhorias na clareza das instruções

#### 🛠️ **Melhorias na Estrutura**
- Otimizações na organização de pastas
- Adição de arquivos de configuração úteis
- Melhoria no .gitignore
- Inclusão de templates adicionais

#### ✨ **Novas Funcionalidades**
- Adição de novos templates
- Criação de scripts de automação
- Integração com ferramentas úteis
- Exemplos de implementação

### 3. Padrões de Desenvolvimento

#### **Commits Semânticos**
Use a convenção [Conventional Commits](https://www.conventionalcommits.org/):

```bash
# Exemplos de commits válidos
git commit -m "feat: adiciona template para componente React"
git commit -m "docs: atualiza instruções de instalação"
git commit -m "fix: corrige estrutura de pastas do backend"
git commit -m "style: melhora formatação do README"
git commit -m "refactor: reorganiza estrutura de testes"
```

#### **Nomenclatura de Branches**
```bash
# Para novas funcionalidades
feature/nome-da-funcionalidade

# Para correções
fix/descricao-do-bug

# Para documentação
docs/melhoria-documentacao

# Para refatoração
refactor/reorganizacao-estrutura
```

### 4. Processo de Review

#### **Antes de Enviar o PR**
- [ ] Teste suas mudanças localmente
- [ ] Verifique se a documentação está atualizada
- [ ] Certifique-se de que seguiu os padrões do projeto
- [ ] Execute uma revisão própria do código

#### **Criando o Pull Request**
1. **Título claro** descrevendo a mudança
2. **Descrição detalhada** explicando:
   - O que foi alterado
   - Por que foi alterado
   - Como testar as mudanças
3. **Link para issues** relacionadas (se houver)
4. **Screenshots** (se aplicável)

### 5. Template de Pull Request

```markdown
## Descrição
Breve descrição das mudanças realizadas.

## Tipo de Mudança
- [ ] Correção de bug
- [ ] Nova funcionalidade
- [ ] Melhoria na documentação
- [ ] Refatoração
- [ ] Melhoria de performance

## Como Testar
1. Passo a passo para testar as mudanças
2. Comandos necessários
3. Resultados esperados

## Checklist
- [ ] Testei as mudanças localmente
- [ ] Atualizei a documentação
- [ ] Segui os padrões de código
- [ ] Adicionei testes (se aplicável)

## Screenshots (se aplicável)
```

## 📝 Diretrizes de Documentação

### **Padrões de Escrita**
- Use linguagem clara e objetiva
- Prefira frases curtas e diretas
- Inclua exemplos práticos sempre que possível
- Mantenha consistência no tom e estilo

### **Formatação Markdown**
- Use cabeçalhos de forma hierárquica
- Inclua blocos de código com syntax highlighting
- Use listas para organizar informações
- Adicione emojis para melhorar a leitura

### **Estrutura de Documentação**
```
/docs
├── api/              # Documentação da API
├── components/       # Documentação de componentes
├── deployment/       # Guias de deploy
└── tutorials/        # Tutoriais passo-a-passo
```

## 🔍 Reportando Problemas

### **Issues**
Ao reportar problemas, inclua:

1. **Descrição clara** do problema
2. **Passos para reproduzir** o erro
3. **Comportamento esperado** vs **atual**
4. **Ambiente** (OS, Node version, etc.)
5. **Screenshots** ou logs (se possível)

### **Template de Issue**
```markdown
**Descrição do Problema**
Descreva claramente o problema encontrado.

**Passos para Reproduzir**
1. Vá para '...'
2. Clique em '....'
3. Role até '....'
4. Veja o erro

**Comportamento Esperado**
O que deveria acontecer.

**Screenshots**
Se aplicável, adicione screenshots.

**Ambiente**
- OS: [ex: Windows 10]
- Node.js: [ex: 18.17.0]
- npm/yarn: [ex: npm 9.6.7]
```

## 🌟 Reconhecimento

Todos os contribuidores serão reconhecidos no projeto. Contribuições valiosas podem resultar em:

- **Menção no README** principal
- **Badge de contributor** no perfil GitHub
- **Participação** em decisões do projeto
- **Convite** para colaborador oficial

## 📞 Comunicação

### **Canais de Contato**
- **Issues**: Para reportar bugs e sugerir melhorias
- **Discussions**: Para perguntas e discussões gerais
- **Email**: thiago@analisandodados.com

### **Tempo de Resposta**
- Issues: Até 48 horas úteis
- Pull Requests: Até 72 horas úteis
- Emails: Até 24 horas úteis

---

## 🚀 Vamos Construir Juntos!

Sua contribuição, independente do tamanho, é valiosa e ajuda a tornar este projeto melhor para toda a comunidade de desenvolvedores.

**Obrigado por contribuir!** 🙏
