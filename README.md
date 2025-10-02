# FireForce VI Digital Garden 🌱🔥

**Engineering the Future of Wildfire Combat Through Systems Engineering**

[![GitHub Pages](https://img.shields.io/badge/GitHub-Pages-blue?logo=github)](https://fireforce6.github.io)
[![Built with Quartz](https://img.shields.io/badge/Built%20with-Quartz-purple)](https://quartz.jzhao.xyz)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

Welcome to the FireForce VI Digital Garden - a comprehensive knowledge base documenting the design, architecture, and development of a sixth-generation autonomous wildfire fighting system-of-systems.

## 🔥 About FireForce VI

FireForce VI is an ambitious educational project that tackles California's devastating wildfire crisis through advanced systems engineering. With annual losses exceeding $275B and 2.3M+ acres burned, traditional firefighting methods are no longer sufficient. This project explores how:

- **Space-based sensors** detect fires minutes after ignition
- **Autonomous drone fleets** coordinate suppression operations in real-time
- **AI decision systems** optimize resource allocation across multiple fire zones
- **Digital twin technology** enables testing and validation without risk
- **Human-centric interfaces** maintain command authority while leveraging AI capabilities

## 📚 What's Inside

This digital garden contains comprehensive documentation organized into:

### Core Documentation
- **Problem & Inspiration** - Understanding the wildfire crisis and aerospace-inspired solutions
- **System Requirements** - Technical specifications and performance targets
- **Success Criteria** - Stakeholder validation and acceptance requirements
- **Operational Scenario** - Real-world mission execution examples
- **Engineering Competencies** - Skills and learning objectives

### Development Environments (Dev Work Packages)
1. **Project Environment** - Mission-critical project visibility and tracking
2. **Modeling Environment** - Collaborative OML-based system modeling
3. **Development CoPilot** - AI-powered systems engineering assistant
4. **Testing Environment** - Integrated test execution and validation

### System-of-Systems (SoS Work Packages)
1. **Fire Satellite** - Space-based early warning constellation
2. **Scout Drone** - Autonomous reconnaissance platforms
3. **Tanker Drone** - Heavy-lift fire suppression drones
4. **Fire Cloud** - Distributed real-time coordination platform
5. **AI Fire Warden** - Intelligent mission coordination system
6. **Mission Control** - Human-machine command interface
7. **Environment Simulation** - Physics-based digital twin
8. **SoS Architecture** - Formal system architecture models (OML)
9. **SoS Integration** - End-to-end system integration and testing

## 🚀 Getting Started

### Viewing the Digital Garden

Visit the published site: **[https://fireforce6.github.io](https://fireforce6.github.io)**

### Local Development

This digital garden is built with [Quartz 4](https://quartz.jzhao.xyz), a fast, batteries-included static site generator for publishing Obsidian vaults.

#### Prerequisites
- Node.js v22+
- npm v10.9.2+

#### Setup

```bash
# Clone the repository
git clone https://github.com/fireforce6/fireforce6.github.io.git
cd fireforce6.github.io

# Install dependencies
npm install

# Start local development server
npx quartz build --serve

# Or use the convenience script
./start.sh
```

The site will be available at `http://localhost:8080`

#### Building for Production

```bash
# Build the static site
npx quartz build

# Output will be in the /public directory
```

## 📁 Repository Structure

```
fireforce6.github.io/
├── fireforce6/                    # Obsidian vault (source content)
│   ├── *.md                      # Main documentation pages
│   ├── Assets/                   # Images and media
│   ├── Dev Work Packages/        # Development environment docs
│   └── SoS Work Packages/        # System component docs
├── public/                        # Generated static site
├── quartz/                        # Quartz static site generator
├── quartz.config.ts              # Site configuration
├── quartz.layout.tsx             # Layout customization
└── package.json                  # Node.js dependencies
```

## ✨ Features

- **📝 Wiki-style linking** - Seamless navigation between related concepts
- **🔍 Full-text search** - Find information quickly across all documents
- **📊 Interactive diagrams** - Visual system architectures and flows
- **🎨 Syntax highlighting** - Code examples with beautiful formatting
- **📱 Responsive design** - Works on desktop, tablet, and mobile
- **🌙 Dark mode** - Easy on the eyes for extended reading
- **🔗 Backlinks** - Discover connections between topics
- **📈 Graph view** - Visualize the knowledge network

## 🤝 Contributing

This is an educational project documenting a systems engineering approach to autonomous wildfire response. Contributions, suggestions, and improvements are welcome!

### Content Guidelines

- Use Markdown with wiki-style `[[links]]` for cross-references
- Place images in `fireforce6/Assets/` directory
- Follow the established document structure (Overview → Challenge → Capabilities → Architecture → etc.)
- Maintain technical accuracy and include citations where appropriate
- Use appropriate frontmatter metadata for SEO and organization

### Submitting Changes

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-improvement`)
3. Make your changes to files in the `fireforce6/` directory
4. Test locally with `npx quartz build --serve`
5. Commit your changes (`git commit -m 'Add amazing improvement'`)
6. Push to the branch (`git push origin feature/amazing-improvement`)
7. Open a Pull Request

## 🎓 Educational Context

FireForce VI is designed as a systems engineering educational project that:

- Demonstrates **Model-Based Systems Engineering (MBSE)** using OML
- Applies **system-of-systems architecture** principles
- Explores **autonomous systems** coordination and AI decision-making
- Practices **safety-critical systems** design and validation
- Teaches **requirements engineering** and traceability
- Develops **real-time distributed systems** expertise

## 📖 Related Resources

- [Ontological Modeling Language (OML)](https://www.opencaesar.io/)
- [ROS2 Documentation](https://docs.ros.org/)
- [NASA Systems Engineering Handbook](https://www.nasa.gov/reference/systems-engineering-handbook/)
- [INCOSE Systems Engineering Handbook](https://www.incose.org/)
- [NVIDIA Omniverse for Digital Twins](https://www.nvidia.com/en-us/omniverse/)

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Built with [Quartz](https://quartz.jzhao.xyz) by [jackyzha0](https://github.com/jackyzha0)
- Inspired by aerospace systems engineering practices
- Digital twin concept based on [NVIDIA/Lockheed Martin wildfire AI](https://blogs.nvidia.com/blog/lockheed-martin-wildfires-ai/)
- Project structure influenced by modern systems engineering frameworks

## 🤝 Partnerships & Collaboration

We actively encourage partnerships with:
- **Academic institutions** interested in systems engineering education
- **Industry partners** in aerospace, defense, or autonomous systems
- **Research organizations** exploring wildfire response technologies
- **Technology companies** developing relevant hardware or software solutions

For partnership inquiries, please contact:

**Dr. Maged Elaasar**  
*Primary Investigator*  
Modelware Solutions  
📧 [modelwaresolutions@gmail.com](mailto:modelwaresolutions@gmail.com)

## 📬 Contact

For questions, suggestions, or technical discussions:

- **Issues**: [GitHub Issues](https://github.com/fireforce6/fireforce6.github.io/issues)
- **Discussions**: [GitHub Discussions](https://github.com/fireforce6/fireforce6.github.io/discussions)

---

**🔥 FireForce VI** - *Engineering autonomous solutions for wildfire response through rigorous systems engineering*

