# 🤖 Build Your First AI Agent for FREE (NO CODING Required)

## 📋 Overview

This guide will walk you through creating an intelligent AI automation workflow that responds to chat messages and provides information about AI Automation Testing. No coding experience required!

## ✨ What You'll Build

An AI-powered chatbot workflow that:
- ✅ Receives chat messages automatically
- 🧠 Processes queries using Google Gemini AI
- 💾 Stores conversation history in memory
- 🔍 Performs web searches when needed (via SerpAPI)
- 💬 Provides intelligent, context-aware responses

## 🛠️ Prerequisites

Before starting, you'll need:

1. **Account Creation** (Free)
   - Sign up at the automation platform shown in the screenshots
   - Get free trial access (3 days with 0/1000 executions included)

2. **API Keys** (Free tiers available)
   - Google Gemini API key ([Get it here](https://makersuite.google.com/app/apikey))
   - SerpAPI key for web search ([Get it here](https://serpapi.com/))

## 🎯 Step-by-Step Tutorial

### Step 1: Create Your Workflow

1. Navigate to **"My workflow"** in the platform
2. Click **"+ Add tag"** to organize your project
3. Access the **Editor** tab (shown at the top)

### Step 2: Set Up the Trigger

**When chat message received** trigger:
- 📨 This starts your workflow automatically when a user sends a message
- No configuration needed - it activates on any incoming chat message

### Step 3: Configure the AI Agent

The **AI Agent** is the brain of your workflow:

**Connected Components:**
- **Chat Model**: Google Gemini Chat Model
- **Memory**: Simple Memory (2 instances for conversation tracking)
- **Tool**: SerpAPI (for web search capabilities)

**Flow:**
- 1 item flows from trigger → AI Agent
- 1 item flows from AI Agent → output

### Step 4: Add Google Gemini Chat Model

1. Click on the **Google Gemini Chat Model** node (Google "G" icon)
2. Configure:
   - **Model Selection**: Choose `gemini-pro` or latest available model
   - **API Key**: Paste your Google Gemini API key
   - **Temperature**: Set between 0.7-1.0 for creative responses

**Status Indicator**: ✓ (green checkmark) shows successful connection

### Step 5: Set Up Memory Storage

**Simple Memory** nodes (2 instances):
- 💾 First Memory: Stores user queries
- 💾 Second Memory: Stores AI responses
- **Configuration**: Use default settings (automatically tracks 2 items total)

**Purpose**: Maintains conversation context for more natural interactions

### Step 6: Configure SerpAPI (Optional but Recommended)

**SerpAPI** enables web search:
- Add your SerpAPI key
- Allows the AI to fetch real-time information
- Enhances responses with current data

**Connection**: Links via "Tool" to the AI Agent

### Step 7: Test Your Workflow

#### Test Query 1:
```
Can you Provide me some inputs about AI Automation Testing
```

**Expected Response:**
The AI will provide comprehensive information about Intelligent Test Automation and AI-powered Testing, including key concepts and benefits.

**Execution Results:**
- ✅ Success in 10.866s | 3,786 Tokens
- AI Agent: Success in 9.827s
- Simple Memory: Success in 1ms (×2)
- Google Gemini: Success in 9.803s | 3,786 Tokens

#### Test Query 2:
```
What is the best way to learn Web automation testing
```

**Expected Response:**
Detailed learning path including:
1. **Master a Programming Language**
   - Python (recommended for beginners)
   - JavaScript/TypeScript (for modern frameworks)
2. **Understand Web Technologies** (HTML, CSS, JavaScript)
3. **Learn Automation Frameworks/Tools** (Selenium, Playwright, Cypress)
4. **Practice and Build Projects**

**Execution Results:**
- ✅ Success in 9.094s | 895 Tokens
- AI Agent: Success in 8.146s | 895 Tokens

## 📊 Monitoring Your Workflow

### Executions Tab
Track all workflow runs:
- ⏱️ **Execution Time**: How long each run takes
- 🎯 **Token Usage**: API consumption per execution
- ✅ **Success Rate**: Monitor completion status
- 📅 **Timestamps**: When each execution started

### Logs Section
View detailed execution logs:
- Individual component performance
- Token consumption breakdown
- Error messages (if any)
- Session IDs for debugging

## 💡 Key Features

| Feature | Description | Status |
|---------|-------------|--------|
| **Real-time Chat** | Instant message processing | ✅ Active |
| **AI Processing** | Gemini-powered responses | ✅ Active |
| **Memory** | Context-aware conversations | ✅ Active |
| **Web Search** | Live information retrieval | ✅ Active |
| **No Code** | Visual workflow builder | ✅ Active |

## 🎨 Workflow Visualization

```
📱 Chat Message
    ↓ (1 item)
🤖 AI Agent
    ├─ 💬 Chat Model (Google Gemini)
    ├─ 💾 Memory (Simple Memory ×2)
    └─ 🔍 Tool (SerpAPI)
    ↓ (1 item)
📤 Output Response
```

## 🚀 Advanced Tips

### Optimization
- ⚡ **Token Management**: Monitor usage to stay within free tier
- 🎯 **Prompt Engineering**: Craft better questions for improved responses
- 📝 **Memory Settings**: Adjust to balance context vs. token usage

### Customization
- 🎨 Add custom tags for organization
- 🔄 Create multiple workflows for different use cases
- 📊 Set up evaluations to test different configurations

## 📈 Usage Stats

**Your Current Plan:**
- ⏰ 3 days left in trial
- 📊 0/1000 executions used
- ⭐ 155,656 stars (community popularity)

## 🔧 Troubleshooting

### Common Issues

**Workflow Not Triggering:**
- ✓ Ensure workflow is **Active** (toggle at top)
- ✓ Check "When chat message received" is properly configured

**API Errors:**
- ✓ Verify API keys are correctly entered
- ✓ Check API quota limits
- ✓ Review error messages in Logs tab

**Slow Response Times:**
- ✓ Consider using faster models
- ✓ Reduce memory context size
- ✓ Optimize prompt complexity

## 🎓 What You've Learned

By completing this tutorial, you now know how to:
- ✅ Build no-code AI automation workflows
- ✅ Integrate Google Gemini AI for intelligent responses
- ✅ Implement conversation memory
- ✅ Add web search capabilities
- ✅ Monitor and debug workflow executions
- ✅ Optimize token usage and performance

## 🌟 Next Steps

1. **Enhance Your Agent:**
   - Add more tools (email, calendar, databases)
   - Implement conditional logic
   - Create multi-step workflows

2. **Deploy:**
   - Share your workflow with team members
   - Integrate with external applications
   - Set up production monitoring

3. **Explore:**
   - Try different AI models
   - Experiment with temperature settings
   - Build specialized agents for specific tasks

## 📚 Resources

- [Google Gemini API Documentation](https://ai.google.dev/)
- [SerpAPI Documentation](https://serpapi.com/docs)
- Platform Documentation (check your specific platform's docs)


## 📝 Author

Saran Kumar

---

**Happy Building! 🚀**

*Created with ❤️ for the no-code AI automation community*
