# 🪄 PromptForge - AI Prompt Engineering Studio

A powerful, modern web application for crafting, testing, and managing AI prompts with advanced engineering techniques.

![PromptForge Screenshot](https://via.placeholder.com/800x400/0ea5e9/ffffff?text=PromptForge+Studio)

## ✨ Features

### 🎯 **Dual Mode Interface**
- **Standard Mode**: Flexible prompt building with core components
- **COSTAR Guided Mode**: Structured framework (Context, Objective, Style, Tone, Audience, Response)

### 🧠 **Advanced Prompting Techniques**
- **Foundational**: Front-loading, Role Prompting
- **Reasoning Enhancers**: Chain-of-Thought, Tree of Thoughts
- **Iterative & Adaptive**: Self-Consistency, Self-Refine
- **Security & Safety**: Bias Mitigation, Prompt Leaking Prevention, Content Filtering

### 💾 **Prompt Management**
- Save and organize prompt configurations
- Quick-start templates for common use cases
- Export/Import functionality
- Local storage persistence

### 🎨 **Beautiful Design**
- Modern, responsive interface
- Smooth animations and transitions
- Glass morphism effects
- Intuitive accordion-based organization

## 🚀 Getting Started

### Prerequisites
- Node.js (v14 or higher)
- npm or yarn

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/promptforge.git
   cd promptforge
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start the development server**
   ```bash
   npm start
   ```

4. **Open your browser**
   Navigate to `http://localhost:3000`

## 🏗️ Built With

- **React 18** - Modern React with hooks
- **Tailwind CSS** - Utility-first CSS framework
- **Lucide React** - Beautiful, customizable icons
- **Local Storage API** - Client-side data persistence

## 📖 Usage Guide

### Creating Your First Prompt

1. **Choose Your Mode**
   - Toggle between Standard and COSTAR Guided Mode
   - COSTAR provides structured guidance for beginners

2. **Define Your Objective**
   - Start with a clear, specific task description
   - Be as detailed as possible about what you want to achieve

3. **Add Context & Components**
   - Persona: Define the AI's role and expertise
   - Context: Provide background information
   - Examples: Include few-shot examples for better results
   - Format: Specify desired output structure

4. **Apply Techniques**
   - Select relevant prompting techniques
   - Each technique enhances different aspects of the response
   - Hover over techniques to see detailed descriptions

5. **Review & Save**
   - Your prompt generates automatically as you type
   - Copy the final prompt or save it to your vault
   - Export configurations for sharing or backup

### Template Library

PromptForge includes pre-built templates for common scenarios:
- **Creative Writing Assistant** - For storytelling and creative content
- **Technical Concept Explainer** - For breaking down complex topics
- **Business Strategy Analyst** - For strategic recommendations

## 🔧 Customization

### Adding New Techniques

Edit `src/App.js` and add to the `techniqueCategories` array:

```javascript
{
  id: 'your-technique',
  name: 'Your Technique Name',
  description: 'Description of what this technique does',
  type: 'guardrail' // optional, for safety techniques
}
```

### Creating Custom Templates

Add new templates to the `templatePrompts` array with pre-configured states.

## 🤝 Contributing

We welcome contributions! Please see our [Contributing Guide](CONTRIBUTING.md) for details.

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Inspired by the latest research in prompt engineering
- Built with modern web technologies and best practices
- Icons provided by [Lucide](https://lucide.dev/)

## 📞 Support

- 📧 Email: support@promptforge.dev
- 💬 Discord: [Join our community](https://discord.gg/promptforge)
- 🐛 Issues: [GitHub Issues](https://github.com/yourusername/promptforge/issues)

---

**Made with ❤️ for the AI community**
