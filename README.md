# Biblical Insights AI - Intelligent Bible Assistant

A sophisticated AI-powered chatbot that provides detailed biblical insights, explanations, and interpretations using LangChain, Mistral AI, and Pinecone vector database.

## 🌟 Features

- Interactive chat interface with dynamic responses
- Context-aware biblical explanations
- Real-time verse references and interpretations
- Time-based greetings
- User-friendly interface with clear guidance
- Comprehensive biblical knowledge base
- Historical and contextual insights

## 🛠 Technology Stack

- **Frontend**: Streamlit
- **Language Model**: Mistral AI
- **Vector Database**: Pinecone
- **Embeddings**: HuggingFace
- **Framework**: LangChain
- **Language**: Python 3.9+



## 📁 Project Structure

```
bible-bot/
├── app.py                 # Main application file
├── ui.py                  # UI components and layout
├── system_prompt.txt      # AI system instructions
├── requirements.txt       # Project dependencies
├── .streamlit/           
│   └── secrets.toml      # Local configuration
└── README.md             # Documentation
```

## 🔧 Core Components

1. **UI Layer (`ui.py`)**
   - Chat interface management
   - Session state handling
   - Dynamic greetings
   - User guide integration

2. **Application Core (`app.py`)**
   - LangChain integration
   - Vector store management
   - Query processing
   - Response generation

3. **System Prompt**
   - Response structuring
   - Biblical context handling
   - Tone and style guidelines

## 🎯 Features in Detail

### Chat Interface
- Real-time message updates
- Chat history management
- Clear conversation option
- Contextual responses

### AI Capabilities
- Scripture reference lookup
- Contextual understanding
- Verse interpretation
- Practical applications

### User Experience
- Time-based greetings
- Intuitive interface
- Helpful user guide
- Error handling

## 🔄 Workflow

1. **User Input**
   - Question submission
   - Input validation
   - Context preparation

2. **Processing**
   - Query refinement
   - Vector search
   - Context integration
   - Response generation

3. **Response**
   - Structured output
   - Biblical references
   - Practical insights
   - Additional resources

## 🛡 Security

- API keys stored in Streamlit secrets
- No sensitive data exposure
- Secure dependency versions
- Environment variable protection

## 📈 Performance

- Caching implementation
- Optimized vector searches
- Efficient response generation
- Minimal latency

