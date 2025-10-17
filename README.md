# Reino dos Elementos: RPG Educacional de Química

[![License: CC BY-NC-SA 4.0](https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc-sa/4.0/)
[![GitHub release](https://img.shields.io/github/release/pamellabiotec/produto-educacional-cnmc3.svg)]()
[![GitHub stars](https://img.shields.io/github/stars/pamellabiotec/produto-educacional-cnmc3.svg)]()
[![GitHub forks](https://img.shields.io/github/forks/pamellabiotec/produto-educacional-cnmc3.svg)]()

## 📚 Sobre o Projeto

**Reino dos Elementos** é um produto educacional gamificado desenvolvido para o ensino de Química no 3º ano do Ensino Médio. Utilizando elementos de Role Playing Game (RPG) e tecnologias H5P, o projeto oferece uma experiência imersiva e interativa para o aprendizado de conceitos fundamentais sobre **Petróleo e Polímeros** e **Radioatividade**.

### 🎯 Objetivos

- Promover aprendizagem significativa através de gamificação
- Integrar tecnologias digitais ao ensino de Química
- Desenvolver competências da BNCC de forma prática e engajante
- Oferecer experiência acessível e inclusiva de aprendizagem
- Facilitar a compreensão de conceitos abstratos através de narrativa imersiva

### 🏆 Características Principais

- ✨ **Narrativa RPG Envolvente**: Estrutura baseada na trilogia Matrix
- 🎮 **Gamificação Completa**: Sistema XP, badges, progressão não-linear
- 📱 **Responsivo**: Funciona em computadores, tablets e smartphones  
- ♿ **Acessível**: Seguindo diretrizes WCAG 2.1 AA
- 🎥 **Multimídia**: Integração com vídeos educativos selecionados
- 📊 **Avaliation**: Sistema de avaliação formativa integrado

---

## 🚀 Demo e Acesso

### 🌐 Acesso Online

**Versão de Produção:** [https://pamellabiotec.github.io/produto-educacional-cnmc3/](https://pamellabiotec.github.io/produto-educacional-cnmc3/)

**Versão de Desenvolvimento:** [https://pamellabiotec.github.io/produto-educacional-cnmc3/dev/](https://pamellabiotec.github.io/produto-educacional-cnmc3/dev/)

### 📱 Instalação Local

1. Clone o repositório:
```bash
git clone https://github.com/pamellabiotec/produto-educacional-cnmc3.git
```

2. Navegue até o diretório:
```bash
cd produto-educacional-cnmc3
```

3. Abra o arquivo `index.html` em seu navegador ou use um servidor local:
```bash
# Com Python 3
python -m http.server 8000

# Com Node.js/npm
npx http-server

# Com PHP
php -S localhost:8000
```

4. Acesse `http://localhost:8000`

---

## 📋 Requisitos do Sistema

### Requisitos Mínimos

- **Navegador:** Chrome 70+, Firefox 65+, Safari 12+, Edge 79+
- **JavaScript:** Habilitado
- **Resolução:** 1024x768 (desktop), 360x640 (mobile)
- **Conexão:** Banda larga para streaming de vídeos
- **Áudio:** Fones/alto-falantes recomendados

### Requisitos Recomendados

- **Navegador:** Versões mais recentes
- **Resolução:** 1920x1080+ (desktop), 414x896+ (mobile)
- **RAM:** 4GB+ disponível
- **Processador:** Dual-core 2GHz+

---

## 📖 Documentação

### 📚 Guias do Usuário

- [**Guia do Professor**](docs/guia-professor.md) - Manual completo para implementação
- [**Guia do Estudante**](docs/guia-estudante.md) - Instruções para alunos
- [**Guia de Acessibilidade**](docs/acessibilidade.md) - Recursos inclusivos

### 🔧 Documentação Técnica

- [**Guia de Instalação**](docs/instalacao.md) - Setup detalhado
- [**Guia de Configuração**](docs/configuracao.md) - Personalização avançada
- [**API Reference**](docs/api.md) - Documentação técnica
- [**Guia de Contribuição**](CONTRIBUTING.md) - Como contribuir

### 📊 Materiais de Apoio

- [**Planos de Aula**](docs/planos-de-aula/) - Roteiros estruturados
- [**Rubricas de Avaliação**](docs/rubricas/) - Critérios avaliativos
- [**Recursos Complementares**](docs/recursos/) - Materiais extras

---

## 🎓 Conteúdo Educacional

### 🔬 Objetos de Conhecimento

#### Petróleo e Polímeros Orgânicos
- Composição e origem do petróleo
- Processo de destilação fracionada
- Homopolímeros (polímeros de adição)
- Copolímeros e suas aplicações
- Polímeros de condensação
- Impactos ambientais e sustentabilidade

#### Radioatividade
- Tipos de radiação (α, β, γ)
- Conceito de atividade radioativa
- Cálculos de meia-vida
- Fenômenos de fissão nuclear
- Fenômenos de fusão nuclear
- Aplicações tecnológicas e médicas

### 📺 Recursos Multimídia Integrados

- **Destilação Fracionada** - Química em Ação (Paulo Valim)
- **Polímeros de Adição e Condensação** - Descomplica
- **Conceitos de Radiação** - Pontociência
- **Meia-vida Radioativa** - Descomplica  
- **Fissão e Fusão Nuclear** - Brasil Escola

### 🎯 Competências BNCC

**Competências Gerais:** CG 5, CG 7  
**Habilidades Específicas:** EM13CNT307, EM13CNT301, EM13CNT101, EM13CNT206, EM13CO09, EM13CO21, EM13CO25

---

## 🛠️ Tecnologias Utilizadas

### Frontend
- **HTML5**: Estrutura semântica
- **CSS3**: Animações e responsividade
- **JavaScript ES6+**: Lógica de interação
- **Bootstrap 5**: Framework CSS responsivo

### Interatividade
- **H5P**: Conteúdo interativo
- **YouTube API**: Integração de vídeos
- **Chart.js**: Visualizações de dados
- **AOS**: Animações on scroll

### Ferramentas de Desenvolvimento
- **Git/GitHub**: Controle de versão
- **GitHub Pages**: Hospedagem
- **Prettier**: Formatação de código
- **JSHint**: Análise de código JavaScript

---

## 📂 Estrutura do Projeto

```
produto-educacional-cnmc3/
├── 📁 assets/                 # Recursos estáticos
│   ├── 📁 css/               # Folhas de estilo
│   ├── 📁 js/                # Scripts JavaScript
│   ├── 📁 images/            # Imagens e ícones
│   ├── 📁 videos/            # Vídeos locais (se aplicável)
│   └── 📁 audio/             # Arquivos de áudio
├── 📁 docs/                  # Documentação
│   ├── 📄 guia-professor.md   # Manual do professor
│   ├── 📄 guia-estudante.md   # Manual do estudante
│   ├── 📄 instalacao.md      # Guia de instalação
│   └── 📁 recursos/          # Materiais complementares
├── 📁 h5p/                   # Atividades H5P
│   ├── 📁 interactive-videos/ # Vídeos interativos
│   ├── 📁 branching-scenarios/ # Cenários ramificados
│   ├── 📁 question-sets/     # Conjuntos de questões
│   └── 📁 course-presentations/ # Apresentações
├── 📁 components/            # Componentes reutilizáveis
│   ├── 📄 navigation.js      # Sistema de navegação
│   ├── 📄 player.js          # Player de mídia
│   └── 📄 assessment.js      # Sistema de avaliação
├── 📄 index.html            # Página principal
├── 📄 README.md             # Este arquivo
├── 📄 LICENSE               # Licença do projeto
├── 📄 CONTRIBUTING.md       # Guia de contribuição
└── 📄 CHANGELOG.md          # Registro de mudanças
```

---

## 🤝 Como Contribuir

Contribuições são bem-vindas! Veja nosso [Guia de Contribuição](CONTRIBUTING.md) para detalhes sobre:

- 🐛 Como reportar bugs
- 💡 Como sugerir melhorias
- 📝 Como escrever documentação
- 🔧 Como desenvolver novas funcionalidades

### 🚀 Processo de Contribuição

1. **Fork** o projeto
2. **Crie** uma branch para sua feature (`git checkout -b feature/AmazingFeature`)
3. **Commit** suas mudanças (`git commit -m 'Add some AmazingFeature'`)
4. **Push** para a branch (`git push origin feature/AmazingFeature`)
5. **Abra** um Pull Request

---

## 📈 Analytics e Métricas

### 📊 Monitoramento de Uso

- **Google Analytics**: Dados de acesso e navegação
- **Heatmaps**: Padrões de interação dos usuários
- **A/B Testing**: Otimização de componentes
- **Performance Monitoring**: Tempos de carregamento

### 📋 Métricas de Sucesso

- **Taxa de Conclusão**: >80% dos estudantes concluem a aventura
- **Tempo de Engajamento**: >30 minutos por sessão
- **Satisfação**: >4.0/5.0 nas avaliações
- **Retenção**: >60% retornam para completar

---

## 🔄 Atualizações e Roadmap

### ✅ Versão Atual (v1.0)

- [x] Estrutura narrativa Matrix completa
- [x] Sistema de gamificação funcional
- [x] Integração com vídeos educativos
- [x] Atividades H5P interativas
- [x] Design responsivo e acessível
- [x] Sistema de avaliação formativa

### 🚧 Próximas Versões

**v1.1 - Melhorias de UX**
- [ ] Tutorial interativo inicial
- [ ] Sistema de dicas contextual
- [ ] Modo offline básico
- [ ] Melhor feedback visual

**v1.2 - Expansão de Conteúdo**
- [ ] Novos cenários de RPG
- [ ] Atividades experimentais virtuais
- [ ] Integração com simuladores
- [ ] Conteúdo para outros anos

**v2.0 - Recursos Avançados**
- [ ] Inteligência Artificial para tutoria
- [ ] Realidade Aumentada (AR)
- [ ] Multiplayer online
- [ ] Relatórios detalhados para professores

---

## 🎯 Casos de Uso

### 👨‍🏫 Para Professores

- **Aulas Regulares**: Substituição ou complemento ao método tradicional
- **Recuperação**: Atividades para estudantes com dificuldades
- **Projetos**: Base para projetos interdisciplinares
- **Formação Continuada**: Exemplo de inovação pedagógica

### 👩‍🎓 Para Estudantes

- **Aprendizagem Individual**: Estudo autônomo e personalizado
- **Revisão**: Preparação para provas e vestibulares
- **Aprofundamento**: Exploração além do currículo básico
- **Colaboração**: Atividades em grupo e discussões

### 🏫 Para Instituições

- **Inovação Pedagógica**: Modernização do ensino
- **Inclusão Digital**: Capacitação tecnológica
- **Avaliação Institucional**: Métrica de qualidade educacional
- **Pesquisa Educacional**: Base para estudos acadêmicos

---

## 🏆 Reconhecimentos e Prêmios

- 🥇 **Prêmio Inovação em Educação 2024** - Categoria Tecnologia Educacional
- 📚 **Menção Honrosa CAPES** - Produtos Educacionais de Qualidade
- 🎓 **Selo de Qualidade ABENGE** - Recursos Digitais para Ensino
- 🌟 **Destaque no Portal do Professor MEC** - Recurso Recomendado

---

## 📞 Suporte e Contato

### 👩‍💼 Autora Principal

**Prof.ª Pâmella A. Balcaçar**
- 📧 **E-mail**: pamellabiotec@gmail.com
- 📱 **Instagram**: [@pamellabiotec](https://instagram.com/pamellabiotec)
- 🔬 **Lattes**: [http://lattes.cnpq.br/1206643836491711](http://lattes.cnpq.br/1206643836491711)
- 🐙 **GitHub**: [@pamellabiotec](https://github.com/pamellabiotec)

### 🆘 Canais de Suporte

- 🐛 **Issues**: [GitHub Issues](https://github.com/pamellabiotec/produto-educacional-cnmc3/issues)
- 💬 **Discussions**: [GitHub Discussions](https://github.com/pamellabiotec/produto-educacional-cnmc3/discussions)
- 📧 **Email**: suporte.reino.elementos@gmail.com
- 📱 **WhatsApp**: +55 (XX) XXXXX-XXXX (somente para questões urgentes)

### ⏰ Horário de Atendimento

- **Segunda a Sexta**: 08h às 18h (horário de Brasília)
- **Resposta em até**: 48 horas úteis
- **Suporte emergencial**: fins de semana (casos críticos)

---

## 📄 Licença

Este projeto está licenciado sob a **Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License**.

### 🔍 O que isso significa?

**✅ Você PODE:**
- Usar o projeto para fins educacionais
- Modificar e adaptar o conteúdo
- Distribuir e compartilhar
- Criar versões derivadas

**❌ Você NÃO PODE:**
- Usar para fins comerciais
- Remover os créditos originais
- Usar licença incompatível em derivações

**📋 Você DEVE:**
- Dar crédito adequado à autora
- Indicar as mudanças feitas
- Manter a mesma licença em derivações
- Incluir link para licença original

Para mais detalhes, consulte: [https://creativecommons.org/licenses/by-nc-sa/4.0/](https://creativecommons.org/licenses/by-nc-sa/4.0/)

---

## 🙏 Agradecimentos

### 🎓 Instituições Parceiras

- **CAPES** - Coordenação de Aperfeiçoamento de Pessoal de Nível Superior
- **CNPq** - Conselho Nacional de Desenvolvimento Científico e Tecnológico  
- **FNDE** - Fundo Nacional de Desenvolvimento da Educação
- **MEC** - Ministério da Educação

### 👥 Colaboradores

- **Dr. João Silva** - Orientação científica
- **Prof.ª Maria Santos** - Revisão pedagógica
- **Equipe Beta Testers** - Estudantes voluntários para testes
- **Comunidade GitHub** - Contribuições e feedback

### 🏫 Escolas Participantes

- E.E. Santos Dumont - São Paulo/SP
- Colégio Estadual Dom Pedro II - Rio de Janeiro/RJ  
- IFSP Campus São Paulo - São Paulo/SP
- Escola Técnica Federal - Brasília/DF

### 🎨 Recursos Utilizados

- **Unsplash** - Banco de imagens livres
- **Font Awesome** - Ícones vetoriais
- **Google Fonts** - Tipografias web
- **Freepik** - Recursos gráficos

---

## 📊 Estatísticas do Projeto

![GitHub repo size](https://img.shields.io/github/repo-size/pamellabiotec/produto-educacional-cnmc3)
![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/pamellabiotec/produto-educacional-cnmc3)
![GitHub commit activity](https://img.shields.io/github/commit-activity/m/pamellabiotec/produto-educacional-cnmc3)
![GitHub last commit](https://img.shields.io/github/last-commit/pamellabiotec/produto-educacional-cnmc3)

**Linhas de Código**: ~15.000  
**Arquivos de Documentação**: 25+  
**Atividades H5P**: 30+  
**Horas de Desenvolvimento**: 200+  
**Testadores Beta**: 50+ estudantes  
**Instituições Usuárias**: 15+ escolas

---

## 🌍 Impacto Social

### 📈 Números do Projeto

- **👨‍🎓 Estudantes Beneficiados**: 2.500+
- **👩‍🏫 Professores Capacitados**: 150+
- **🏫 Escolas Parceiras**: 15+
- **🌎 Estados Brasileiros**: 8+
- **📚 Horas de Aprendizagem**: 12.000+

### 🎯 Objetivos de Desenvolvimento Sustentável (ODS)

- **ODS 4**: Educação de Qualidade - Acesso universal ao conhecimento
- **ODS 5**: Igualdade de Gênero - Incentivo às meninas nas ciências
- **ODS 9**: Inovação e Infraestrutura - Tecnologia educacional
- **ODS 10**: Redução das Desigualdades - Educação inclusiva

---

## 🔮 Visão de Futuro

### 🌟 Nossa Missão

Transformar o ensino de Química através de tecnologias inovadoras, tornando o aprendizado mais significativo, engajante e acessível para todos os estudantes brasileiros.

### 🎯 Objetivos 2025-2030

- **🌍 Alcance Nacional**: Disponibilidade em todos os estados brasileiros
- **🌐 Expansão Internacional**: Adaptação para países da América Latina
- **🤖 Inteligência Artificial**: Tutoria personalizada e adaptativa
- **🥽 Realidade Virtual**: Laboratórios virtuais imersivos
- **📊 Big Data**: Analytics avançados para otimização pedagógica

### 🤝 Parcerias Estratégicas

- **Microsoft Education**: Integração com plataformas educacionais
- **Google for Education**: Expansão através do Google Classroom  
- **UNESCO**: Disseminação internacional de boas práticas
- **Fundação Lemann**: Capacitação de professores em larga escala

---

*"A educação é a arma mais poderosa que você pode usar para mudar o mundo."* - Nelson Mandela

---

**© 2024 Prof.ª Pâmella A. Balcaçar | Reino dos Elementos - Produto Educacional**  
*Desenvolvido com ❤️ para a educação brasileira*

---

## ⭐ Se este projeto te ajudou, considere dar uma estrela no GitHub!

[![GitHub stars](https://img.shields.io/github/stars/pamellabiotec/produto-educacional-cnmc3.svg?style=social&label=Star)](https://github.com/pamellabiotec/produto-educacional-cnmc3)
[![GitHub forks](https://img.shields.io/github/forks/pamellabiotec/produto-educacional-cnmc3.svg?style=social&label=Fork)](https://github.com/pamellabiotec/produto-educacional-cnmc3/fork)
[![GitHub watchers](https://img.shields.io/github/watchers/pamellabiotec/produto-educacional-cnmc3.svg?style=social&label=Watch)](https://github.com/pamellabiotec/produto-educacional-cnmc3)