# 🧠 Psicologia Estudo - Plataforma de Aprendizado com IA

Uma plataforma inovadora para estudar psicologia utilizando inteligência artificial avançada, gerando resumos, slides, flashcards, mapas mentais e simulados automaticamente.

## ✨ Recursos Principais

✅ **Login Seguro** - Autenticação com armazenamento local
✅ **Editor Inteligente** - Auto-save de seu material de estudo
✅ **Processamento com IA** - Integração com Groq API (Mixtral 8x7b)
✅ **Múltiplos Formatos**:
   - 📝 Resumos estruturados
   - 🎪 Slides interativos
   - 🗺️ Mapas mentais com Mermaid
   - 🔄 Flashcards com rotação 3D
   - ❓ Quiz com feedback automático
✅ **Gamificação** - Sistema de XP e Níveis
✅ **Exportar PDF** - Baixe seu material completo
✅ **Interface Dark Mode** - Design moderno e responsivo

## 🚀 Como Usar

### Acesso Rápido
1. Abra o site
2. Use as credenciais de demo:
   - **Usuário**: `02955185299`
   - **Senha**: `140819Gg@@`

### Fluxo de Uso
1. **Cole seu texto** na área de editor
2. **Clique em "Gerar Material com IA"**
3. **Navegue pelos formatos**:
   - Resumo: Visão geral do conteúdo
   - Slides: Apresentação estruturada
   - Mapa Mental: Visualização hierárquica
   - Flashcards: Estude com cartões flip
   - Quiz: Teste seu conhecimento

### Funcionalidades Extras
- 💾 Auto-save local do seu texto
- 🎯 Ganhe XP ao interagir com o material
- 📊 Acompanhe seu progresso (Nível e XP)
- 📖 Modo Foco para leitura concentrada
- 🔍 Zoom no mapa mental (zoom in/out)
- 📄 Exporte tudo em PDF

## 🔧 Tecnologias

- **Frontend**: HTML5, TailwindCSS, JavaScript vanilla
- **IA**: Groq API (Mixtral 8x7b)
- **Visualização**: Mermaid.js, Marked.js, Lucide Icons
- **Armazenamento**: LocalStorage do navegador
- **PDF**: html2pdf.js

## 📋 Estrutura JSON Gerada

A IA retorna um JSON estruturado com:

```json
{
  "summary": "Resumo em Markdown",
  "slides": [
    {
      "titulo": "Título do Slide",
      "topicos": ["Tópico 1", "Tópico 2"]
    }
  ],
  "cards": [
    {
      "front": "Pergunta?",
      "back": "Resposta"
    }
  ],
  "quiz": [
    {
      "pergunta": "Questão?",
      "opcoes": ["A", "B", "C", "D"],
      "correta": 0,
      "explicacao": "Por que a resposta correta é A..."
    }
  ],
  "mindmap": "graph TD; A[Tema] --> B[Subtema]"
}
```

## 🎮 Sistema de Gamificação

- ✨ **+100 XP**: Por gerar novo material
- ✨ **+15 XP**: Por responder corretamente um quiz
- ✨ **+2 XP**: Por flip em flashcard
- 🆙 **Level Up**: A cada 300 XP × Nível

## 🛡️ Segurança

- Armazenamento local de usuários
- Validação de JSON recebido
- Tratamento de erros robusto
- API key segura (pode ser renovada)

## 📱 Compatibilidade

- ✅ Desktop (Chrome, Firefox, Safari, Edge)
- ✅ Tablet (iPad, Android tablets)
- ✅ Responsivo (adapta-se ao tamanho da tela)

## 🌐 Deploy

Este projeto está hospedado no GitHub Pages e pode ser acessado em:
[https://gabrielartes92-ui.github.io/psicologia-estudo/](https://gabrielartes92-ui.github.io/psicologia-estudo/)

## 📝 Notas

- O material gerado é salvo localmente no localStorage
- A chave da API está configurada no código (pode ser alterada)
- Funciona offline após o primeiro carregamento
- Limpe o cache do navegador para resetar todos os dados

## 👨‍💻 Desenvolvedor

Criado com ❤️ para facilitar o aprendizado em Psicologia

---

**Versão**: 1.0.0  
**Última atualização**: 2026-07-22
