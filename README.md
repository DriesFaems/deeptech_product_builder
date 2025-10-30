# Deeptech Innovation Builder - Fancy Version
## Installation & Setup Guide

### 🚀 Quick Start

1. **Clone or download the project files**
2. **Install Python dependencies**:
   ```bash
   pip install -r requirements.txt
   ```
   
   Or for minimal installation:
   ```bash
   pip install -r requirements_minimal.txt
   ```

3. **Get OpenAI API Key**:
   - Visit [OpenAI Platform](https://platform.openai.com/api-keys)
   - Create a new API key
   - Keep it secure - you'll enter it in the app

4. **Run the application**:
   ```bash
   streamlit run innovation_builder_sdk_fancy.py
   ```

### 🎯 Features

✨ **Enhanced User Experience**:
- Professional gradient design with custom CSS
- Progress bars and step-by-step guidance
- Organized results in beautiful tabs
- Multiple download options (TXT, JSON, Summary)

🤖 **AI-Powered Analysis**:
- Multi-agent system with specialized roles
- Patent document processing and RAG search
- Technical feasibility assessment
- Market opportunity analysis
- Final innovation recommendations

📊 **Professional Output**:
- Structured analysis reports
- Downloadable documentation
- Timestamped results
- JSON export for further processing

### 🔧 Technology Stack

- **Frontend**: Streamlit with custom CSS
- **AI Agents**: OpenAI Agents SDK
- **Document Processing**: LangChain + PyPDF
- **Vector Search**: FAISS
- **LLM**: OpenAI GPT-4o-mini

### 📋 Usage

1. **Enter API Key**: Provide your OpenAI API key
2. **Upload PDF**: Upload patent document(s)
3. **Start Analysis**: Click "Start Innovation Analysis"
4. **Review Results**: Explore the organized tabs
5. **Download Report**: Save complete analysis as text file

### 🛠️ Troubleshooting

**API Key Issues**:
- Ensure key starts with 'sk-'
- Check you have sufficient OpenAI credits
- Verify key has proper permissions

**PDF Processing Issues**:
- Ensure PDF contains readable text (not just images)
- Try smaller PDF files first
- Check file isn't password protected

**Performance**:
- Processing time depends on PDF size and complexity
- Each agent step may take 30-60 seconds
- Monitor progress with the built-in progress bars

### 📄 File Structure

```
├── innovation_builder_sdk_fancy.py    # Main application
├── requirements.txt                   # Full dependencies
├── requirements_minimal.txt           # Essential dependencies only
└── README.md                         # This file
```

### 👨‍💼 Support

Created by **Dries Faems**  
LinkedIn: [https://www.linkedin.com/in/dries-faems-0371569/](https://www.linkedin.com/in/dries-faems-0371569/)

For technical issues, check the error messages in the Streamlit interface - they provide detailed debugging information.