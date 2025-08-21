# 🤝 Guia de Contribuição

Obrigado por seu interesse em contribuir para a Biblioteca de Segurança de IA! Este guia vai te ajudar a contribuir de forma efetiva.

## 📋 Formas de Contribuir

### 1. 📚 Adicionar Novos Recursos
- Novos cursos, documentários, artigos, ferramentas
- Recursos em português brasileiro (prioridade)
- Atualizações de links ou informações

### 2. 🔧 Melhorar Recursos Existentes
- Corrigir links quebrados
- Melhorar descrições
- Adicionar informações faltantes
- Reorganizar conteúdo

### 3. 🌟 Melhorar a Documentação
- Corrigir erros de português
- Melhorar explicações
- Adicionar exemplos de uso

### 4. 🐛 Reportar Problemas
- Links que não funcionam
- Informações desatualizadas
- Recursos duplicados

## 🎯 Critérios para Inclusão

### ✅ Recursos Aceitos
- **Gratuitos** ou com versão gratuita disponível
- **Relevantes** para segurança em IA/ML
- **Fontes confiáveis** (universidades, empresas reconhecidas, organizações)
- **Conteúdo atual** (preferencialmente dos últimos 3 anos)
- **Qualidade verificada** (sem spam ou conteúdo promocional excessivo)

### ❌ Recursos Não Aceitos
- Links de afiliados ou promocionais
- Recursos não relacionados a IA/segurança
- Conteúdo de baixa qualidade
- Links para downloads suspeitos

## 📁 Estrutura do Projeto

```
village-ai-br/
├── README.md                 # Página principal
├── CONTRIBUTING.md          # Este arquivo
├── LICENSE                  # Licença do projeto
├── docs/                    # Documentação por categoria
│   ├── documentarios/       # Documentários sobre IA
│   ├── cursos/             # Cursos e materiais educacionais
│   ├── red-team/           # Recursos de red teaming
│   ├── leituras/           # Livros, blogs, artigos
│   ├── frameworks/         # Frameworks de segurança
│   ├── ferramentas/        # Software e ferramentas
│   ├── bases-dados/        # Bases de dados de incidentes
│   └── videos-palestras/   # Vídeos e apresentações
└── Biblioteca Segurança de IA.csv  # Dados originais
```

## 🔄 Processo de Contribuição

### 1. Preparação
```bash
# 1. Faça um fork do repositório
# 2. Clone seu fork
git clone https://github.com/SEU_USUARIO/village-ai-br.git
cd village-ai-br

# 3. Crie uma branch para sua contribuição
git checkout -b adicionar-recurso-X
```

### 2. Fazendo as Alterações
1. **Escolha a categoria** apropriada em `/docs/`
2. **Edite o README.md** da categoria
3. **Siga o template** existente
4. **Teste todos os links** antes de submeter

### 3. Submissão
```bash
# 1. Adicione suas alterações
git add .

# 2. Faça um commit descritivo
git commit -m "Adiciona curso de Python para IA Security"

# 3. Envie para seu fork
git push origin adicionar-recurso-X

# 4. Abra um Pull Request no GitHub
```

## 📝 Templates para Contribuição

### Template para Cursos
```markdown
### **Nome do Curso**
- **Instituição/Plataforma**: Nome da instituição
- **Descrição**: Descrição clara e concisa
- **Link**: [Nome do Link](URL)
- **Idioma**: Português/Inglês
- **Nível**: Iniciante/Intermediário/Avançado
- **Duração**: X horas (se disponível)
```

### Template para Artigos/Blogs
```markdown
### **Título do Artigo**
- **Autor/Organização**: Nome do autor
- **Descrição**: Resumo do conteúdo
- **Link**: [Nome do Link](URL)
- **Tipo**: Blog Post/Artigo Acadêmico/Whitepaper
- **Idioma**: Português/Inglês
- **Data**: MM/YYYY (se relevante)
```

### Template para Ferramentas
```markdown
### **Nome da Ferramenta**
- **Desenvolvedor**: Nome/Organização
- **Descrição**: O que a ferramenta faz
- **Link**: [Link oficial](URL)
- **Tipo**: CLI/Web/Desktop/API
- **Licença**: Open Source/Comercial/Freemium
- **Linguagem**: Linguagem principal
```

## 🏷️ Sistema de Tags

Use tags para facilitar a busca:

### Por Nível
- `#iniciante` - Para quem está começando
- `#intermediario` - Conhecimento básico necessário
- `#avancado` - Para especialistas

### Por Idioma
- `#pt-br` - Conteúdo em português brasileiro
- `#en` - Conteúdo em inglês
- `#es` - Conteúdo em espanhol

### Por Tipo de Conteúdo
- `#hands-on` - Conteúdo prático
- `#teorico` - Conteúdo conceitual
- `#academico` - Artigos de pesquisa
- `#industria` - Casos práticos empresariais

### Por Área de Foco
- `#machine-learning` - ML em geral
- `#deep-learning` - Redes neurais profundas
- `#nlp` - Processamento de linguagem natural
- `#computer-vision` - Visão computacional
- `#security` - Segurança específica
- `#red-team` - Testes ofensivos
- `#governance` - Governança e compliance

## ✅ Checklist do Contributor

Antes de submeter sua contribuição:

### Verificação de Qualidade
- [ ] Todos os links estão funcionando
- [ ] As descrições são claras e úteis
- [ ] O conteúdo está na categoria correta
- [ ] Segui o template apropriado
- [ ] Adicionei tags relevantes

### Verificação de Formato
- [ ] Markdown está formatado corretamente
- [ ] Links seguem o padrão `[Texto](URL)`
- [ ] Não há erros de português
- [ ] Respeitei a estrutura existente

### Verificação de Relevância
- [ ] O recurso é relacionado a IA/segurança
- [ ] A fonte é confiável
- [ ] O conteúdo adiciona valor
- [ ] Não é duplicata de recurso existente

## 📞 Suporte

### Precisa de Ajuda?
- **Issues**: Use para reportar bugs ou sugerir melhorias
- **Discussions**: Para perguntas gerais e discussões
- **Email**: Para questões sensíveis

### Reviewers
Os maintainers do projeto vão revisar sua contribuição em até 7 dias. Feedback construtivo é sempre bem-vindo!

## 🏆 Reconhecimento

Todos os contributors são reconhecidos:
- Nome na lista de contributors do GitHub
- Menção em releases importantes
- Badge de contributor para LinkedIn (em breve)

---

**Obrigado por contribuir com a comunidade Village AI BR!** 🇧🇷
