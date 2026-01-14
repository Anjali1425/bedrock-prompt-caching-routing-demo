# 🚀 Amazon Bedrock Prompt Caching & Routing Demo

**Save up to 90% on costs and reduce latency by 85%** with Amazon Bedrock's prompt caching! This hands-on demo lets you experience these powerful features in minutes.

## ✨ Why This Demo?

- 🎯 **5-Minute Setup** - Get running with just 3 commands
- 💰 **See Real Savings** - Watch cache hits reduce your costs in real-time
- 🧠 **Smart Routing** - Let AI choose the best model for each task
- 🎨 **Beautiful UI** - Interactive Streamlit apps + CLI tools
- 🌍 **Works Everywhere** - Compatible with all AWS regions
- 📚 **Latest Models** - Claude 4.5 Haiku/Sonnet/Opus + Amazon Nova

## 🎬 What You'll Experience

### Prompt Caching Demo
Upload a document once, ask multiple questions, and watch the magic:
- ⚡ **First query**: ~2 seconds, full cost
- ⚡ **Cached queries**: ~0.3 seconds, 90% cost reduction
- 📊 Live metrics showing cache performance

### Prompt Routing Demo
Ask questions and see intelligent model selection:
- 🤔 Simple questions → Fast, cheap models (Haiku)
- 🧩 Complex analysis → Powerful models (Sonnet/Opus)
- 📈 Real-time routing decisions and cost tracking

## Project Structure

```
BedrockPromptDemo/
├── src/
│   ├── bedrock_prompt_caching.py    # CLI application for prompt caching
│   ├── bedrock_prompt_routing.py    # CLI application for prompt routing
│   ├── prompt_caching_app.py        # Streamlit UI for prompt caching
│   ├── prompt_router_app.py         # Streamlit UI for prompt routing
│   ├── model_manager.py             # Model selection and management
│   ├── bedrock_service.py           # Bedrock API service wrapper
│   └── file_processor.py            # File processing utilities
├── requirements.txt                 # Python dependencies
└── README.md                        # This file
```

## 🤖 Supported Models

| Model | Best For | Speed | Cost |
|-------|----------|-------|------|
| **Claude Haiku 4.5** | Quick tasks, simple Q&A | ⚡⚡⚡ | 💰 |
| **Claude Sonnet 4.5** | Balanced performance | ⚡⚡ | 💰💰 |
| **Claude Opus 4.1** | Complex reasoning | ⚡ | 💰💰💰 |
| **Amazon Nova** | AWS-optimized tasks | ⚡⚡ | 💰 |

## 🎯 Quick Start (5 Minutes!)

### Prerequisites
✅ AWS account with Bedrock access ([enable models here](https://console.aws.amazon.com/bedrock/home#/modelaccess))  
✅ Python 3.8+ installed  
✅ That's it!

### Installation

```bash
# 1. Clone and enter directory
git clone https://github.com/Anjali1425/bedrock-prompt-caching-routing-demo.git
cd bedrock-prompt-caching-routing-demo

# 2. Install dependencies
pip install -r requirements.txt

# 3. Configure AWS (if not already done)
aws configure
```

### 🎨 Launch the Interactive Demo

```bash
# Prompt Caching Demo - See cost savings in action!
cd src
streamlit run prompt_caching_app.py

# Prompt Routing Demo - Watch AI choose the right model!
streamlit run prompt_router_app.py
```

**Or use CLI versions:**
```bash
python bedrock_prompt_caching.py  # Caching demo
python bedrock_prompt_routing.py  # Routing demo
```

## 💡 What You'll Learn

### Prompt Caching Benefits
- 💰 **90% cost reduction** on repeated context
- ⚡ **85% latency reduction** with cache hits
- 📊 Real-time cache performance metrics
- 🔄 Multi-turn conversation optimization

### Intelligent Routing
- 🎯 Automatic model selection based on complexity
- 💵 Cost optimization across model tiers
- 📈 Usage tracking and analytics
- 🔀 Fallback handling for reliability

### Production-Ready Code
- ✅ Best practices for Bedrock API integration
- 🛡️ Error handling and retry logic
- 📁 Multi-format file processing (PDF, DOCX, TXT)
- 🌐 Multi-region compatibility

## 📦 What's Included

```
├── src/
│   ├── prompt_caching_app.py        # 🎨 Streamlit UI for caching
│   ├── prompt_router_app.py         # 🎨 Streamlit UI for routing
│   ├── bedrock_prompt_caching.py    # 💻 CLI caching demo
│   ├── bedrock_prompt_routing.py    # 💻 CLI routing demo
│   ├── bedrock_service.py           # 🔧 Bedrock API wrapper
│   ├── model_manager.py             # 🧠 Model selection logic
│   └── file_processor.py            # 📄 File handling utilities
├── bedrock_prompt_caching_routing.ipynb  # 📓 Jupyter notebook
└── requirements.txt                 # 📋 Dependencies
```

## 🎓 Use Cases

- **Document Q&A**: Upload PDFs/docs, ask unlimited questions with cached context
- **Cost Optimization**: Compare costs with/without caching
- **Model Comparison**: Test different models on the same prompts
- **Production Prototyping**: Reference implementation for your apps

## 🤝 Contributing

Found a bug? Have an idea? PRs and issues welcome!

## 📄 License

MIT License - see LICENSE file for details.

---

⭐ **Star this repo** if you find it useful! | 🍴 **Fork it** to customize for your needs!