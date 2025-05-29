# DanHQ - AI-Powered Test Case Management Platform

**A centralized test case management system with intelligent AI integration for modern software testing teams.**

## 🚀 Overview

DanHQ is a next-generation test case management platform that combines the proven reliability of traditional test management tools like TestLink with cutting-edge AI capabilities. Built for Agile teams, it revolutionizes software testing by automating test case generation from Software Requirements Specification (SRS) documents while providing comprehensive test execution tracking and reporting.

## ✨ Key Features

### 🤖 AI-Powered Test Generation
- **Automatic Test Case Creation**: Generate comprehensive test cases from SRS documents using advanced LLM integration (OpenAI GPT, Anthropic Claude)
- **Intelligent Document Processing**: Support for DOCX, PDF, and Markdown formats with smart chunking algorithms
- **Prompt Engineering**: Optimized templates for high-quality test case generation
- **Requirement Traceability**: Automatically link generated test cases to source requirements

### 📊 Hierarchical Test Plan Management
- **Multi-Level Structure**: Organize tests across Sprint Master Plans, Feature Plans, Story Plans, and Release Plans
- **Automatic Status Aggregation**: Real-time status updates propagated across all hierarchy levels
- **Agile Integration**: Perfect fit for Scrum and Kanban methodologies
- **Visual Dashboards**: Comprehensive reporting and analytics for each plan level

### 🎯 Core Test Management
- **Project & Suite Organization**: Hierarchical test suite structure with flexible organization
- **Comprehensive Test Execution**: Track Pass/Fail/Blocked results with detailed notes and screenshots
- **User Role Management**: Granular permissions for Test Managers, Engineers, Developers, and Stakeholders
- **Import/Export**: Seamless data exchange via XML and CSV formats

### 📈 Advanced Reporting & Analytics
- **Real-time Dashboards**: Live progress tracking with interactive charts and metrics
- **Multi-format Exports**: Generate reports in PDF, HTML, and Excel formats
- **Trend Analysis**: Historical data visualization and performance insights
- **Risk Assessment**: Automated alerts and progress forecasting

## 🛠 Technology Stack

### Backend
- **Framework**: .NET 8.0 with ASP.NET Core
- **Architecture**: Clean Architecture
- **Database**: PostgreSQL with Redis caching
- **Real-time Communication**: SignalR
- **Logging**: Structured logging with Serilog

### Frontend
- **Framework**: Angular 19 with TypeScript
- **State Management**: NgRx for predictable state updates
- **UI Components**: Angular Material / PrimeNG
- **Data Visualization**: Chart.js
- **Responsive Design**: Mobile-first approach

### AI Integration
- **LLM Providers**: OpenAI GPT-4+, Anthropic Claude, Llama, Mistral
- **Document Processing**: Advanced chunking algorithms for large documents
- **Security**: Data sanitization and secure API key management
- **Fallback Mechanisms**: Robust error handling and retry logic

### Infrastructure
- **Containerization**: Docker and Kubernetes
- **CI/CD**: GitHub Actions
- **Monitoring**: Application Insights, Grafana, Prometheus
- **Security**: JWT authentication, 2FA, audit logging

## 🎯 Target Users

- **Test Managers/Leaders**: Project oversight, team coordination, and strategic planning
- **Test Engineers**: Test case creation, execution, and maintenance
- **Developers**: Integration with development workflows and bug tracking
- **Product Managers**: Quality metrics and release readiness tracking
- **Stakeholders**: Executive dashboards and progress reporting

## 📋 System Requirements

### Performance Targets
- **Response Time**: < 2 seconds for web interfaces
- **Concurrent Users**: Support for 100+ simultaneous users
- **AI Processing**: < 5 minutes for 50-page SRS analysis
- **Report Generation**: < 3 seconds for 500 test cases

### Security Features
- **Data Encryption**: AES encryption for sensitive data
- **Authentication**: JWT with refresh tokens and 2FA support
- **Audit Trail**: Comprehensive logging of all user activities
- **AI Security**: Data sanitization before LLM processing

## 🚦 Getting Started

### Prerequisites
- .NET 8.0 SDK
- Node.js 18+ and npm
- PostgreSQL 14+
- Redis 7+
- Docker (for containerized deployment)

### Quick Start
```bash
# Clone the repository
git clone git@github.com:cuongtl1992/dan-hq.git
cd dan-hq

# Start infrastructure services
docker-compose up -d postgres redis kafka

# Run backend services
cd backend
dotnet restore
dotnet run --project src/DanHQ.Api

# Run frontend application
cd frontend
npm install
ng serve
```

Visit `http://localhost:4200` to access the application.

## 📖 Documentation

- [📚 User Guide](docs/user-guide.md) - Complete user manual
- [🏗 Architecture Overview](docs/architecture.md) - System design and components
- [🔧 API Documentation](docs/api.md) - REST API reference
- [🤖 AI Integration Guide](docs/ai-integration.md) - LLM setup and configuration
- [⚙️ Deployment Guide](docs/deployment.md) - Production deployment instructions

## 🗺 Roadmap

### MVP (Q2 2025)
- [x] Core test case management
- [x] Hierarchical test plans
- [x] Basic AI integration
- [x] Essential reporting

### Phase 1 (Q3 2025)
- [ ] Advanced AI features
- [ ] External tool integrations (Jira, Azure DevOps)
- [ ] Enhanced reporting and analytics
- [ ] Mobile application

### Phase 2 (Q4 2025)
- [ ] CI/CD pipeline integration
- [ ] Advanced AI agents
- [ ] Automated test script generation
- [ ] Enterprise SSO

## 🤝 Contributing

We welcome contributions! Please see our [Contributing Guide](CONTRIBUTING.md) for details on:
- Development setup
- Code standards and conventions
- Pull request process
- Issue reporting

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🌟 Why DanHQ?

**"Dan"** represents the foundational step in martial arts - the solid foundation upon which advanced techniques are built. Just as a martial artist progresses through dan levels, DanHQ provides the foundational platform that scales with your testing maturity, from basic test management to AI-powered test automation.

**"HQ"** signifies the headquarters - your central command center for all testing operations, bringing together teams, tools, and intelligence in one unified platform.

---

**Built with ❤️ for the testing community**

⭐ **Star this repo if DanHQ helps improve your testing workflow!**