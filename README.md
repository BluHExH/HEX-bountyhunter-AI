# HEX-bountyhunter-AI



# 🔥 HEX-BountyHunter-AI 2036

**Advanced Recon & Attack-Surface Intelligence System**

![HEX-BountyHunter-AI](https://img.shields.io/badge/HEX-BountyHunter-AI-2036-red?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-blue?style=for-the-badge)
![Python](https://img.shields.io/badge/Python-3.8%2B-green?style=for-the-badge)
![Platform](https://img.shields.io/badge/Platform-Termux%20%7C%20Linux%20%7C%20Kali-orange?style=for-the-badge)

## 🎯 Overview

HEX-BountyHunter-AI 2036 is a comprehensive, production-ready cybersecurity reconnaissance platform designed for penetration testers, bug bounty hunters, and security professionals. It combines advanced AI-powered analysis with multi-source intelligence gathering to provide unparalleled visibility into attack surfaces.

## 🚀 Features

### 🛡️ Core Capabilities
- **Automated Subdomain Enumeration** - 10+ sources including passive DNS, certificate transparency
- **AI Asset Discovery Engine** - ML-powered suspicious asset detection
- **Cloud Exposure Analyzer** - AWS, GCP, Azure security assessment
- **Technology Stack Fingerprinting** - Comprehensive version detection
- **JavaScript Deep Scanner** - API key, endpoint, and secret extraction
- **Directory & Endpoint Discovery** - Intelligent crawling with content analysis
- **API Structure Reverse Engineering** - Automated API mapping
- **TLS/SSL Weakness Scanner** - Certificate and configuration analysis
- **DNS Misconfiguration Detector** - Zone transfer, wildcard detection
- **Historical Recon** - Wayback machine and GAU integration
- **Attack Surface Map Visualizer** - NetworkX-based graph analysis
- **AI Risk Scoring** - Explainable vulnerability assessment
- **Token Leakage Detection** - 30+ pattern types with ML enhancement

### 🤖 AI-Powered Features
- **Blind Endpoint Discovery** - AI-driven hidden service detection
- **API Schema Reverse Engineering** - Automated API documentation
- **Token Leakage Pattern AI** - ML-enhanced secret detection
- **Machine-Learning Endpoint Clustering** - Smart asset grouping
- **Smart Duplicate Detection** - Intelligent deduplication
- **Leaked Key Risk Score** - Contextual risk assessment
- **JS Attack Surface Ranker** - Prioritized vulnerability analysis
- **AI Prediction Engine** - Proactive threat intelligence
- **Behavioral Analysis** - Anomaly detection and pattern recognition

### 🔍 Advanced Analysis
- **Third-Party Dependency Attack Surface** - Supply chain security
- **Real-Time Recon Dashboard** - Live monitoring interface
- **JS Execution Sandbox** - Safe JavaScript analysis
- **Automated Parameter Miner** - Dynamic parameter discovery
- **Cloud Exposure Scanner** - Multi-cloud asset detection
- **DNS Zone Transfer Auto-Test** - Automated DNS security checks
- **TLS Misconfig Analyzer** - Certificate vulnerability assessment
- **Subdomain Takeover Detector** - Hijacking vulnerability detection
- **Historical Exposure Analysis** - Timeline-based threat tracking
- **Email & Username Pattern Enumerator** - Target discovery
- **CIDR Block Passive Discovery** - Network intelligence
- **WAF Fingerprint Engine** - Web Application Firewall detection
- **Rate-Limit Evaluation** - Security control testing
- **Scheduler for Recurring Recon** - Automated continuous monitoring

### 📊 Reporting & Integration
- **Auto HTML + PDF Report Generator** - Professional security reports
- **NetworkX Attack Surface Maps** - Visual relationship analysis
- **Telegram & Webhook Notifier** - Real-time alerting
- **Full JSON Logging** - Structured data export
- **SQLite Index for Results** - Fast data retrieval
- **Executive & Technical Reports** - Multi-audience documentation

## 🛠️ Installation

### Quick Start (Termux/Linux/Kali)

```bash
# Clone the repository
git clone https://github.com/your-repo/HEX-BountyHunter-AI.git
cd HEX-BountyHunter-AI

# Run the installation script
chmod +x install.sh
./install.sh

# Activate virtual environment
source venv/bin/activate

# Run your first scan
python src/main.py --domain example.com
```

### Manual Installation

```bash
# Install dependencies
pip install -r requirements.txt

# Setup directories
mkdir -p output/{html_reports,json,logs}
mkdir -p data/{wordlists,sample}

# Copy configuration
cp config/default.yaml config/user.yaml

# Make main executable
chmod +x src/main.py
```

## 🎮 Usage

### Basic Commands

```bash
# Single domain scan
python src/main.py --domain example.com

# Multiple domains from file
python src/main.py --list-domains targets.txt

# Use advanced configuration
python src/main.py --domain example.com --config config/advanced.yaml

# Custom output prefix
python src/main.py --domain example.com --output security_assessment

# Verbose output
python src/main.py --domain example.com --verbose

# Debug mode
python src/main.py --domain example.com --debug

# Specific modules
python src/main.py --domain example.com --modules subdomain dns_enum tech_stack
```

### Configuration Files

#### Default Configuration (config/default.yaml)
- Basic reconnaissance settings
- Essential modules enabled
- Conservative scanning parameters

#### Advanced Configuration (config/advanced.yaml)
- Full feature set enabled
- Aggressive scanning parameters
- Advanced AI analysis
- Extended detection capabilities

### Module Selection

Available modules:
- `subdomain` - Subdomain enumeration
- `dns_enum` - DNS reconnaissance
- `dir_enum` - Directory discovery
- `tech_stack` - Technology fingerprinting
- `asset_mapper` - Asset relationship mapping
- `js_analyzer` - JavaScript security analysis
- `cloud_exposure` - Cloud security assessment
- `token_leak` - Secret detection
- `error_pattern_ai` - AI error analysis
- `vuln_predictor` - ML vulnerability prediction
- `cors_test` - CORS security testing
- `rate_limit` - Rate limiting analysis
- `misconfig` - Misconfiguration scanning

## 📁 Project Structure

```
HEX-BountyHunter-AI/
├── README.md                 # This file
├── LICENSE                   # MIT License
├── requirements.txt          # Python dependencies
├── install.sh               # Installation script
├── config/                  # Configuration files
│   ├── default.yaml        # Default settings
│   └── advanced.yaml       # Advanced settings
├── src/                     # Source code
│   ├── core/               # Core engine
│   ├── recon/              # Reconnaissance modules
│   ├── analysis/           # Analysis modules
│   ├── ai/                 # AI-powered features
│   ├── scanners/           # Security scanners
│   ├── intelligence/       # Intelligence modules
│   ├── utils/              # Utilities
│   └── main.py            # Main entry point
├── src_tests/              # Test suite
├── output/                 # Scan results
├── data/                   # Data files
└── .github/workflows/      # CI/CD pipelines
```

## 🎯 Example Scenarios

### Bug Bounty Reconnaissance
```bash
# Comprehensive bug bounty scan
python src/main.py --domain target.com --config config/advanced.yaml --output bug_bounty_recon
```

### Enterprise Security Assessment
```bash
# Multi-domain enterprise assessment
python src/main.py --list-domains enterprise_targets.txt --modules subdomain dns_enum tech_stack vuln_predictor --output enterprise_assessment
```

### API Security Testing
```bash
# API-focused security analysis
python src/main.py --domain api.example.com --modules js_analyzer cors_test rate_limit misconfig --output api_security
```

### Cloud Security Assessment
```bash
# Cloud exposure analysis
python src/main.py --domain cloud.example.com --modules cloud_exposure asset_mapper --output cloud_security
```

## 🔧 Configuration

### API Keys Setup

Add your API keys to `config/user.yaml`:

```yaml
api_keys:
  shodan: "your_shodan_api_key"
  censys: "your_censys_api_key"
  virustotal: "your_virustotal_api_key"
  github: "your_github_token"
  telegram_bot: "your_telegram_bot_token"
```

### Cloud Configuration

```yaml
cloud:
  aws:
    enabled: true
    access_key: "your_aws_access_key"
    secret_key: "your_aws_secret_key"
    regions: ["us-east-1", "us-west-2"]
  gcp:
    enabled: true
    service_account_key: "path/to/service-account.json"
    project_id: "your-gcp-project"
```

### AI Configuration

```yaml
ai:
  model_type: "openai"  # or "local"
  openai_api_key: "your_openai_api_key"
  model_name: "gpt-3.5-turbo"
  temperature: 0.7
  max_tokens: 2000
```

## 📊 Output Formats

### JSON Reports
Structured data for programmatic access:
```json
{
  "scan_id": "scan_2024_01_15_14_30_00",
  "target": "example.com",
  "timestamp": "2024-01-15T14:30:00Z",
  "findings": [...],
  "risk_score": 7.2,
  "summary": {...}
}
```

### HTML Reports
Professional, interactive reports with:
- Executive summary
- Technical findings
- Risk assessment
- Visual charts and graphs
- Recommendations
- Attack surface maps

### SQLite Database
Persistent storage for:
- Historical scan data
- Trend analysis
- Search functionality
- Integration with other tools

## 🧪 Testing

```bash
# Run all tests
pytest src_tests/ -v

# Run specific test suite
pytest src_tests/test_recon.py -v

# Run with coverage
pytest src_tests/ --cov=src --cov-report=html
```

## 🔄 CI/CD

The project includes GitHub Actions workflows for:
- Automated testing
- Code quality checks
- Security scanning
- Documentation generation

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📋 Requirements

- Python 3.8+
- 4GB RAM minimum (8GB+ recommended)
- 10GB free disk space
- Internet connection for reconnaissance
- (Optional) API keys for enhanced features

## 🔒 Legal Disclaimer

**IMPORTANT**: This tool is for educational and authorized security testing purposes only. Users are responsible for ensuring they have proper authorization before scanning any targets. The authors are not responsible for misuse or illegal activities.

- ✅ **Authorized**: Your own domains, client domains with permission
- ✅ **Educational**: Labs, training environments, CTF challenges
- ❌ **Unauthorized**: Random domains, systems without permission

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- OpenAI for AI capabilities

## 🔮 Roadmap

- [ ] GUI Interface
- [ ] REST API
- [ ] Docker containers
- [ ] Cloud deployment
- [ ] Mobile app
- [ ] Integration frameworks

---

**Built with ❤️ by HEX **

*Hunting vulnerabilities in the digital frontier since 2036*
