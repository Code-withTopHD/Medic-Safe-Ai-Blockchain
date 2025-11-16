# Medic-Safe-Ai-Blockchain
# 🏥 MediSafe AI - Prescription Safety Assistant

> A bilingual AI-powered prescription safety assistant built on blockchain technology, designed to prevent medication errors in Pakistan and South Asia.
## 🎯 Overview

MediSafe AI is a comprehensive prescription safety platform that helps users verify medication interactions, check dosages, and analyze prescriptions using AI and blockchain technology. The platform supports multiple languages (English, Urdu, Pashto) and includes voice accessibility features for low-literacy users.

### Key Statistics

- **15,000 people die annually** in Pakistan from preventable medication errors
- **70% of Pakistanis self-medicate** without proper guidance
- **60% less access** to doctors in rural areas (Balochistan, Sindh, KPK)
- **250,000+ medical records** integrated for accurate verification

## 🚨 Problem Statement

### Healthcare Inequality in Pakistan

- **Rural Healthcare Gap:** People in rural areas have 60% less access to doctors
- **Language Barriers:** Most medical information is only available in English
- **Dangerous Self-Medication:** 70% of Pakistanis self-medicate without guidance
- **Medication Errors:** 15,000 preventable deaths annually from medication mistakes
- **Lack of Verification:** No reliable system to check drug interactions and dosages

### Common Scenarios

People walk into pharmacies asking dangerous questions:
- "Can I mix these medicines?"
- "How much should I take?"
- "Is this prescription safe?"

And they get **guesses, not answers**.

## 💡 Solution

MediSafe AI solves this critical healthcare gap through:

### 1. Instant Safety Checking
- Real-time drug interaction verification against **250,000+ medical records**
- Multi-source validation (RxNorm API, OpenFDA, local datasets)
- Blockchain-verified prescription integrity

### 2. Intelligent Prescription Analysis
- Upload prescription photo - OCR extracts medications
- Instant safety warnings and interaction alerts
- No doctor visit needed for basic guidance

### 3. Multilingual Accessibility
- Full support for English, Urdu, and Pashto
- Voice input/output for low-literacy users
- Professional medical terminology translations

### 4. Blockchain Security
- Every safety check recorded on Polygon blockchain
- AES-256 encryption for data protection
- Immutable audit logs for transparency

## ✨ Features

### 🔍 Core Features

- ✅ **Drug Interaction Checking** - Real-time safety verification against 250,000+ medical records
- ✅ **AI Chat Assistant** - Natural language queries with multilingual support
- ✅ **Prescription Upload** - OCR-based medication extraction and analysis
- ✅ **Dosage & Timing Information** - Comprehensive medication guidance from medical datasets
- ✅ **Voice Input/Output** - Speech-to-text and text-to-speech for accessibility
- ✅ **Blockchain Security** - Polygon blockchain verification with AES-256 encryption
- ✅ **Multi-API Integration** - RxNorm, OpenFDA, and local medical databases

### 🌍 Accessibility Features

- **Multilingual Support** - Full medical terminology in English, Urdu, and Pashto
- **Voice Accessibility** - Speech recognition and synthesis in all supported languages
- **Mobile-Optimized** - Responsive design for smartphone users
- **Low-Literacy Friendly** - Visual cues and audio responses

### 🛡️ Security Features

- **Blockchain Verification** - All safety checks recorded on Polygon blockchain
- **Encryption** - AES-256 for data transmission, RSA-2048 for sensitive data
- **Privacy** - Zero data sharing, anonymized logs, immediate image deletion
- **Compliance** - Medical disclaimers, healthcare professional consultation required

## 🛠️ Tech Stack

### Backend
- **Framework:** FastAPI (Python 3.8+)
- **AI/ML:** OpenAI API, Custom medical knowledge base
- **APIs:** RxNorm API, OpenFDA API
- **Blockchain:** Polygon blockchain integration
- **Security:** AES-256 encryption, RSA-2048 for sensitive data
- **OCR:** Tesseract OCR with fallback mechanisms
- **Database:** JSON-based medical datasets (250,000+ records)

### Frontend
- **Framework:** React 18.3+ with TypeScript
- **UI Library:** Radix UI components
- **Styling:** Tailwind CSS
- **Build Tool:** Vite
- **Voice:** Web Speech API

### Infrastructure
- **Deployment:** Docker-ready
- **API:** RESTful API architecture
- **Security:** CORS-enabled, rate limiting

## 🏗️ Architecture

```
MediSafe AI Architecture
│
├── Frontend (React + TypeScript)
│   ├── Chat Assistant with Voice I/O
│   ├── Prescription Upload with OCR
│   ├── Multilingual Display (EN/UR/PS)
│   └── Privacy & Terms Pages
│
├── Backend (FastAPI + Python)
│   ├── OpenAI Integration for AI responses
│   ├── RxNorm API for drug standardization
│   ├── OpenFDA API for safety data
│   ├── Blockchain Manager (Polygon)
│   ├── Encryption Service (AES-256/RSA-2048)
│   ├── OCR Service (Tesseract)
│   └── Medical Knowledge Base (250,000+ records)
│
└── Agents (Multi-Agent Architecture)
    ├── Drug Safety Agent
    ├── Dosage Agent
    ├── Doctor Agent
    ├── Competition Agent
    └── OpenAI Agent
```

### Multi-Agent System

- **Drug Safety Agent:** Checks drug interactions against medical databases
- **Dosage Agent:** Provides dosage and timing information from medical datasets
- **Doctor Agent:** Generates medical disclaimers and safety warnings
- **Competition Agent:** Optimized responses for competition scoring
- **OpenAI Agent:** Natural language processing and translations

## 📦 Installation

### Prerequisites

- Python 3.8 or higher
- Node.js 18+ and npm
- OpenAI API key
- Tesseract OCR (for prescription upload)

### Backend Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/Medisafe2.git
   cd Medisafe2
   ```

2. **Navigate to Backend directory**
   ```bash
   cd Backend
   ```

3. **Create virtual environment**
   ```bash
   python -m venv venv
   
   # Windows
   venv\Scripts\activate
   
   # Linux/Mac
   source venv/bin/activate
   ```

4. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

5. **Set up environment variables**
   Create a `.env` file in the `Backend` directory:
   ```env
   OPENAI_API_KEY=your_openai_api_key_here
   PORT=8000
   ALLOWED_ORIGINS=http://localhost:3000
   ```

6. **Run the backend**
   ```bash
   python main.py
   # or
   uvicorn main:app --reload
   ```

### Frontend Setup

1. **Navigate to Frontend directory**
   ```bash
   cd Frontend
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Run the frontend**
   ```bash
   npm run dev
   ```

### Quick Start (Windows)

For Windows users, simply double-click `START.bat` in the root directory to start both backend and frontend automatically.

## 🚀 Quick Start

### For Judges/Reviewers

1. **Double-click `START.bat`**
2. **Wait 15 seconds** for startup
3. **Browser opens automatically** at http://localhost:3000
4. **Try these queries:**
   - "Can I take Panadol with Ibuprofen?"
   - "What is the dosage for Paracetamol?"
   - Upload a prescription image
   - Click voice input button and speak

### Expected Results

- **Backend:** http://localhost:8000 (API running)
- **Frontend:** http://localhost:3000 (UI running)
- **All features working:** ✓ Chat ✓ Voice ✓ Upload ✓ Multilingual

## 💬 Usage Examples

### Example 1: Drug Interaction Check
```
Query: "Can I take Panadol with Ibuprofen?"
Result: ✅ Safe combination confirmed with multilingual explanation
```

### Example 2: Dosage Information
```
Query: "What is the dosage for Paracetamol?"
Result: Structured dosage info (500-1000mg, max 4000mg daily)
```

### Example 3: Timing Information
```
Query: "When should I take Metformin?"
Result: Timing guidance with food interactions
```

### Example 4: Prescription Upload
- Click "Upload Prescription" button
- Select prescription image
- View extracted medications and safety warnings

### Example 5: Voice Input
- Click microphone button
- Speak your query
- Listen to audio response in multiple languages

## 📚 API Documentation

### Base URL
```
http://localhost:8000
```

### Endpoints

#### Health Check
```http
GET /health
```

**Response:**
```json
{
  "status": "healthy",
  "message": "MediSafe AI is running"
}
```

#### Chat Endpoint
```http
POST /chat
Content-Type: application/json

{
  "message": "Can I take Panadol with Ibuprofen?",
  "language": "en"
}
```

**Response:**
```json
{
  "status": "safe",
  "result": "English response...",
  "urdu_result": "Urdu translation...",
  "pashto_result": "Pashto translation...",
  "disclaimer": "Medical disclaimer...",
  "drugs_found": ["Panadol", "Ibuprofen"]
}
```

#### Check Drug Interaction
```http
POST /check_interaction
Content-Type: application/json

{
  "drug1": "Panadol",
  "drug2": "Ibuprofen"
}
```

**Response:**
```json
{
  "status": "safe",
  "result": "Interaction analysis...",
  "urdu_result": "Urdu translation...",
  "details": "Detailed interaction information...",
  "disclaimer": "Medical disclaimer..."
}
```

#### Upload Prescription
```http
POST /upload_prescription
Content-Type: multipart/form-data

file: [prescription_image]
```

**Response:**
```json
{
  "status": "success",
  "message": "Prescription analysis...",
  "urdu_message": "Urdu translation...",
  "pashto_message": "Pashto translation...",
  "extracted_text": "OCR extracted text...",
  "prescription_data": {...}
}
```

#### Get Drug Information
```http
GET /drug_info/{drug_name}
```

**Example:**
```http
GET /drug_info/Paracetamol
```

#### Security Verification
```http
POST /security/verify
Content-Type: application/json

{
  "prescription_id": "pres_123",
  "prescription_data": {...}
}
```

**Response:**
```json
{
  "verified": true,
  "blockchain_hash": "0x...",
  "integrity_score": 95,
  "verification_timestamp": 1234567890
}
```

### Response Format

All responses include:
- `status`: Interaction status (safe/caution/unsafe/info)
- `result`: English response
- `urdu_result`: Urdu translation
- `pashto_result`: Pashto translation
- `disclaimer`: Medical disclaimer
- `drugs_found`: List of detected drugs (if applicable)

## 🔒 Security & Privacy

### Security Features

- **Blockchain Verification:** All safety checks recorded on Polygon blockchain
- **Encryption:** AES-256 for data transmission, RSA-2048 for sensitive data
- **Privacy:** Zero data sharing, anonymized logs, immediate image deletion
- **Compliance:** Medical disclaimers, healthcare professional consultation required

### Privacy Protection

- **Anonymized Data Processing:** No personal identifiers stored
- **Local Data Storage:** No external data sharing
- **GDPR Compliance:** GDPR-compliant data handling practices
- **Image Deletion:** Prescription images processed and deleted immediately

### Access Control

- **Role-Based Permissions:** Different user types with appropriate access
- **Audit Logging:** All data access logged for security
- **Secure API Authentication:** Rate limiting and secure authentication

## 🌍 Multilingual Support

### Supported Languages

- **English:** Primary interface and responses
- **Urdu:** Full medical terminology translation
- **Pashto:** Complete prescription safety information
- **Voice:** Speech recognition and synthesis in all languages

### Translation Features

- Professional medical terminology translations
- Cultural context awareness
- Regional drug name recognition (Panadol, Brufen, Disprin)
- Voice input/output in all supported languages

## 📊 Data Sources

MediSafe AI integrates multiple authoritative medical databases:

### Primary Sources

- **RxNorm API** - U.S. National Library of Medicine (244,470 drug concepts)
- **OpenFDA API** - FDA-approved drug labels and adverse events
- **SIDER Database** - 309,849 side effects from clinical studies
- **Local Medical Datasets** - 250,000+ Pakistani-specific medical records

### Data Validation

- **Multi-Source Cross-Validation:** Every response verified against multiple sources
- **Real-Time API Integration:** Live data from authoritative medical databases
- **Local Dataset Priority:** Pakistani-specific information prioritized
- **Blockchain Verification:** All safety checks recorded immutably

## 🧪 Testing

### Automated Tests

```bash
# Run backend API tests
run_tests.bat  # Windows
# or
python -m pytest  # If pytest is configured
```

### Manual Frontend Tests

See `Frontend/test_features.md` for manual testing scenarios.

### Test Coverage

- ✅ Drug interaction checking
- ✅ Dosage and timing queries
- ✅ Prescription upload OCR
- ✅ Voice input/output
- ✅ Multilingual responses
- ✅ Privacy & terms pages
- ✅ Error handling
- ✅ Security verification

### Test Scenarios

1. **Drug Interaction Check**
   - Query: "Can I take Panadol with Ibuprofen?"
   - Expected: Safe combination confirmed

2. **Dosage Information**
   - Query: "What is the dosage for Paracetamol?"
   - Expected: Structured dosage info (500-1000mg, max 4000mg daily)

3. **Prescription Upload**
   - Action: Upload prescription image
   - Expected: OCR extraction with medication analysis

4. **Voice Accessibility**
   - Action: Click mic, speak "Ibuprofen timing"
   - Expected: Voice recognition + audio response

## 💰 Business Model

### Revenue Streams

- **Freemium:** $2/month premium for advanced features
- **B2B Pharmacy:** $50/month per location for pharmacy integration
- **Enterprise API:** $500/month for healthcare system integration
- **Data Analytics:** Healthcare insights and reports

### Market Size

- **Global Healthcare AI Market:** $45.2 billion by 2026
- **Prescription Management Market:** $4.8 billion by 2025
- **Pakistani Healthcare Market:** $8.2 billion annually
- **Addressable Market:** 220 million Pakistanis, expanding to 2+ billion in South Asia

### Growth Strategy

- **Phase 1:** Pakistani market penetration
- **Phase 2:** Regional expansion (South Asia)
- **Phase 3:** Global deployment with local partnerships

### Projected Revenue

**$1M+ in year one** with clear scaling path

## 🤝 Contributing

We welcome contributions! Please follow these steps:

1. **Fork the repository**
2. **Create a feature branch** (`git checkout -b feature/AmazingFeature`)
3. **Commit your changes** (`git commit -m 'Add some AmazingFeature'`)
4. **Push to the branch** (`git push origin feature/AmazingFeature`)
5. **Open a Pull Request**

### Contribution Guidelines

- Follow PEP 8 for Python code
- Use TypeScript for frontend code
- Add tests for new features
- Update documentation as needed
- Follow the existing code style
- Include medical disclaimers where appropriate

### Code Style

- **Python:** Follow PEP 8, use type hints
- **TypeScript:** Follow ESLint rules, use strict mode
- **Documentation:** Update README and inline comments
- **Testing:** Add tests for new features

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- **RxNorm API** - U.S. National Library of Medicine
- **OpenFDA API** - U.S. Food and Drug Administration
- **SIDER Database** - Side Effect Resource
- **OpenAI** - AI capabilities
- **Polygon** - Blockchain network
- **FastAPI** - Web framework
- **React** - Frontend framework

- **Legal:** legal@medisafe-ai.pk

## 🌟 Star History

If you find this project helpful, please consider giving it a ⭐!

---

MediSafe AI - Transforming healthcare accessibility through AI and blockchain technology.

Made with ❤️ for healthcare accessibility in Pakistan and South Asia.
