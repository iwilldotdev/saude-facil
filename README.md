# 💚 SaúdeFácil - Orientador de Saúde Preventiva

<div align="center">

![License](https://img.shields.io/badge/license-MIT-green)
![HTML](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)
![Health](https://img.shields.io/badge/Health-Preventive-green)

**Seu orientador pessoal de saúde preventiva, gratuito e acessível**

[Demo Online](https://iwilldotdev.github.io/saude-facil/)

</div>

---

## 📋 Sobre o Projeto

**SaúdeFácil** é uma aplicação web educativa desenvolvida como projeto de extensão universitária, alinhada ao **ODS 3 - Saúde e Bem-estar**.

O projeto visa democratizar o acesso a informações de saúde preventiva, oferecendo ferramentas práticas para que qualquer pessoa possa:

- 📊 **Calcular seu IMC** com interpretação personalizada
- ✅ **Acompanhar hábitos saudáveis** diariamente
- 💧 **Monitorar hidratação** de forma visual e gamificada
- 💡 **Aprender sobre saúde** com dicas práticas baseadas em evidências

> **⚠️ Importante:** Este é um app educativo. Sempre consulte profissionais de saúde para orientações médicas específicas.

---

## ✨ Funcionalidades

### 📊 Calculadora de IMC
- Cálculo automático do Índice de Massa Corporal
- Classificação segundo padrões da OMS
- Feedback visual com cores indicativas
- Orientações personalizadas por faixa de IMC
- Explicação educativa sobre o indicador

**Classificações:**
- 🔵 Abaixo do peso (< 18,5)
- 🟢 Peso normal (18,5 - 24,9)
- 🟡 Sobrepeso (25,0 - 29,9)
- 🟠 Obesidade grau I (30,0 - 34,9)
- 🟠 Obesidade grau II (35,0 - 39,9)
- 🔴 Obesidade grau III (≥ 40,0)

### ✅ Checklist de Hábitos Saudáveis
- **6 hábitos essenciais** para acompanhar:
  - 😴 Dormi pelo menos 7 horas
  - 💧 Bebi pelo menos 2 litros de água
  - 🏃 Pratiquei 30 minutos de atividade física
  - 🥗 Comi pelo menos 3 porções de frutas/vegetais
  - 🚫 Evitei alimentos ultraprocessados
  - 🧘 Fiz uma pausa para relaxar/meditar

- **Barra de progresso visual** mostrando compliance diário
- **Interface interativa** com feedback imediato
- **Descrições educativas** dos benefícios de cada hábito

### 💧 Rastreador de Hidratação
- **8 copos virtuais** representando 250ml cada
- **Meta diária:** 2 litros (2000ml)
- **Contador visual** em copos e mililitros
- **Interface gamificada** e intuitiva
- **Função de reset** para novo dia

### 💡 Biblioteca de Dicas de Saúde
**12 categorias de orientações:**
- 🏃 Exercícios regulares
- 🥗 Alimentação balanceada
- 😴 Sono de qualidade
- 🧘 Saúde mental
- ☀️ Exposição solar adequada
- 👨‍⚕️ Check-ups preventivos
- 🚭 Prevenção de vícios
- 👥 Vida social saudável
- 🧼 Higiene pessoal
- 📵 Desconexão digital
- 🧘‍♀️ Postura correta
- 🎯 Metas realistas

---

## 🚀 Como Usar

### Opção 1: Uso Direto (Recomendado)

1. **Baixe o arquivo HTML**
   ```bash
   # Clone o repositório
   git clone https://github.com/iwilldotdev/saude-facil.git
   
   # Ou baixe apenas o index.html
   ```

2. **Abra no navegador**
   - Duplo clique em `index.html`
   - Ou arraste para o navegador
   - **Funciona 100% offline!** ✅

### Opção 2: Hospedagem Online

**GitHub Pages (Gratuito):**
1. Faça fork do repositório
2. Vá em Settings → Pages
3. Selecione branch `main` como source
4. Acesse em: `https://github.com/iwilldotdev/saude-facil.git`

**Alternativas:**
- Netlify
- Vercel
- Surge.sh

### Opção 3: Servidor Local

```bash
# Python 3
python -m http.server 8000

# Node.js
npx serve

# Acesse: http://localhost:8000
```

---

## 🎯 Guia de Uso

### 1️⃣ Calcular IMC

1. Clique na aba **📊 IMC**
2. Insira seu **peso** em kg (ex: 70.5)
3. Insira sua **altura** em metros (ex: 1.75)
4. Clique em **Calcular IMC**
5. Veja seu resultado com orientações personalizadas

### 2️⃣ Acompanhar Hábitos

1. Acesse a aba **✅ Hábitos**
2. Clique nos hábitos que você praticou hoje
3. Veja sua barra de progresso atualizar
4. Meta: completar 100% dos hábitos diariamente!

### 3️⃣ Monitorar Água

1. Entre na aba **💧 Hidratação**
2. Clique em cada copo ao beber água (250ml)
3. Acompanhe seu progresso em tempo real
4. Meta: 8 copos = 2 litros por dia

### 4️⃣ Ler Dicas

1. Visite a aba **💡 Dicas**
2. Explore as 12 categorias de orientações
3. Aplique no seu dia a dia
4. Compartilhe com amigos e família!

---

## 🛠️ Tecnologias

| Tecnologia | Finalidade | Versão |
|------------|-----------|--------|
| **HTML5** | Estrutura semântica | - |
| **CSS3** | Design responsivo e animações | - |
| **JavaScript (Vanilla)** | Lógica e interatividade | ES6+ |
| **Git** | Controle de versão | - |

### Por que Vanilla JavaScript?

✅ **Zero dependências** - sem bibliotecas externas  
✅ **Carregamento instantâneo** - performance máxima  
✅ **Funciona offline** - não precisa de internet  
✅ **Fácil manutenção** - código simples e direto  
✅ **Acessível** - roda em qualquer navegador moderno  

---

## 📊 Base Científica

### Cálculo do IMC

```javascript
IMC = Peso (kg) / Altura² (m)

Exemplo:
Peso: 70 kg
Altura: 1,75 m
IMC = 70 / (1,75 × 1,75) = 22,86
Classificação: Peso Normal
```

### Recomendações de Saúde

Baseadas em diretrizes de:
- 🏥 Organização Mundial da Saúde (OMS)
- 🇧🇷 Ministério da Saúde do Brasil
- 📚 Sociedades médicas especializadas
- 🔬 Estudos científicos revisados por pares

---

## 🎓 Contexto Acadêmico

### Projeto de Extensão II - ADS

- **Disciplina:** Projeto de Extensão II
- **Curso:** Análise e Desenvolvimento de Sistemas
- **Período:** 11/08/2025 a 05/12/2025
- **Carga Horária:** 40 horas
- **Instituição:** Descomplica

### ODS - Objetivos de Desenvolvimento Sustentável

**Principal:**
- 💚 **ODS 3** - Saúde e bem-estar
  - Meta 3.4: Reduzir mortalidade por doenças não transmissíveis
  - Meta 3.d: Fortalecer capacidades de alerta precoce

**Secundários:**
- 🎓 **ODS 4** - Educação de qualidade (educação em saúde)
- 📉 **ODS 10** - Redução das desigualdades (acesso universal)
- 🤝 **ODS 17** - Parcerias (tecnologia para o bem social)

---

## 🤝 Como Contribuir

Contribuições são bem-vindas! Siga os passos:

1. **Fork** o projeto
2. **Crie** uma branch para sua feature
   ```bash
   git checkout -b feature/MinhaNovaFuncionalidade
   ```
3. **Commit** suas mudanças
   ```bash
   git commit -m 'Adiciona funcionalidade X'
   ```
4. **Push** para a branch
   ```bash
   git push origin feature/MinhaNovaFuncionalidade
   ```
5. **Abra** um Pull Request

### Ideias de Melhorias

- [ ] Adicionar histórico de IMC ao longo do tempo
- [ ] Gráfico de evolução de hábitos
- [ ] Sistema de lembretes (notificações)
- [ ] Modo escuro
- [ ] Exportar relatório em PDF
- [ ] Múltiplos perfis de usuários
- [ ] Integração com wearables
- [ ] Gamificação com conquistas e badges
- [ ] Compartilhamento em redes sociais
- [ ] Mais idiomas (i18n)

---

## 📝 Licença

Este projeto está sob a licença MIT. Consulte [LICENSE](LICENSE) para mais detalhes.

```
MIT License

Você pode:
✅ Usar comercialmente
✅ Modificar
✅ Distribuir
✅ Uso privado

Condições:
📄 Incluir aviso de copyright
📄 Incluir cópia da licença
```

---

## 👤 Autor

**William Gonçalves**

- 🌐 GitHub: [@iwilldotdev](https://github.com/iwilldotdev)
- 💼 LinkedIn: [iwilldotdev](https://linkedin.com/in/iwilldotdev)
- 📧 Email: euwilliamgoncalves@gmail.com
- 🎓 Curso: Análise e Desenvolvimento de Sistemas

---

## 🙏 Agradecimentos

- **Organização Mundial da Saúde (OMS)** pelas diretrizes de saúde
- **Ministério da Saúde do Brasil** pelos dados epidemiológicos
- **Comunidade médica** pelas bases científicas
- **Profissionais de saúde** que validaram o conteúdo
- **Usuários beta** que testaram e deram feedback
- **[Sua Instituição]** pelo apoio ao projeto de extensão
- **Comunidade open source** pela inspiração

---

## 📚 Referências

### Científicas
1. [OMS - Obesity and Overweight](https://www.who.int/news-room/fact-sheets/detail/obesity-and-overweight)
2. [Ministério da Saúde - Guia Alimentar](https://bvsms.saude.gov.br/bvs/publicacoes/guia_alimentar_populacao_brasileira_2ed.pdf)
3. [OMS - Physical Activity](https://www.who.int/news-room/fact-sheets/detail/physical-activity)
4. [Vigitel Brasil 2023](https://www.gov.br/saude/pt-br/assuntos/vigitel)

### ODS
- [ONU - ODS 3](https://brasil.un.org/pt-br/sdgs/3)
- [Agenda 2030](https://brasil.un.org/pt-br/91863-agenda-2030-para-o-desenvolvimento-sustentavel)

### Técnicas
- [MDN Web Docs](https://developer.mozilla.org/)
- [W3C - Web Accessibility](https://www.w3.org/WAI/)

---

## 🔗 Links Úteis

- [🏥 Portal da Saúde](https://www.gov.br/saude/)
- [🌍 OMS](https://www.who.int/)
- [💪 Guia de Atividade Física](https://www.gov.br/saude/pt-br/assuntos/saude-brasil/eu-quero-me-exercitar)

---

## ❓ FAQ (Perguntas Frequentes)

### O app funciona offline?
✅ Sim! 100% offline depois de baixado.

### Os cálculos são precisos?
✅ Sim, baseados em fórmulas e classificações da OMS. Mas consulte sempre um médico para avaliações completas.

### É gratuito?
✅ Totalmente gratuito e sempre será!

### Posso usar comercialmente?
✅ Sim, licença MIT permite uso comercial.

### Como reportar bugs?
📝 Abra uma [issue no GitHub](https://github.com/iwilldotdev/saude-facil/issues).

### Meus dados são salvos?
🔒 Atualmente não. Tudo é processado localmente no navegador. Planejamos adicionar salvamento local (localStorage) no futuro.

### Funciona em celular?
📱 Sim! Design totalmente responsivo.

### Preciso de cadastro?
❌ Não! Use livremente sem cadastro.

---

## 📊 Estatísticas do Projeto

- ⏰ **Horas de desenvolvimento:** 40h
- 📝 **Linhas de código:** ~500
- 💻 **Tecnologias:** 3 (HTML, CSS, JS)
- 🎯 **Funcionalidades:** 4 principais
- 📱 **Dispositivos suportados:** Todos
- 🌍 **Idiomas:** Português (BR)
- 📦 **Dependências:** 0
- 🎨 **Telas/Abas:** 4
- 💡 **Dicas de saúde:** 12 categorias

---

## 🎯 Impacto Social

### Problemas que o SaúdeFácil Resolve

❌ **Falta de informação** sobre saúde preventiva  
✅ Educação acessível e gratuita

❌ **Dificuldade** em manter hábitos saudáveis  
✅ Ferramentas de acompanhamento visual

❌ **Desconhecimento** sobre IMC e seu significado  
✅ Calculadora com orientações claras

❌ **Baixa adesão** à hidratação adequada  
✅ Gamificação do consumo de água

❌ **Sobrecarga do sistema de saúde** com problemas evitáveis  
✅ Prevenção através da educação

---

## 🌱 Roadmap Futuro

### Versão 2.0 (Planejado)
- [ ] Histórico pessoal (localStorage)
- [ ] Gráficos de evolução
- [ ] Lembretes programáveis
- [ ] Modo escuro/claro

### Versão 3.0 (Visão)
- [ ] Backend para dados persistentes
- [ ] Autenticação de usuários
- [ ] Comunidade social
- [ ] Gamificação completa
- [ ] App móvel nativo
- [ ] Integração com wearables

---

<div align="center">

### 💚 Juntos por uma vida mais saudável! 🌟

**Se este projeto te ajudou, considere dar uma ⭐ no repositório!**

![Health](https://img.shields.io/badge/Made%20with-❤️%20&%20Health-green)
![Prevention](https://img.shields.io/badge/Prevention-First-blue)

---

**Última atualização:** Dezembro 2025

</div>
