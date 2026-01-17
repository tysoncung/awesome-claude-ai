# Awesome Claude AI [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of awesome Claude AI tools, resources, integrations, and applications

Claude is Anthropic's family of large language models known for safety, accuracy, and helpful, harmless, and honest responses. This list covers everything from official APIs to community projects built with Claude.

## What's New (January 2026)

- **Claude Opus 4.5** - Anthropic's most intelligent model, best for coding and agents
- **Hybrid Reasoning** - Adjustable effort levels for balancing speed vs depth
- **Tool Search** - Dynamically discover tools from large libraries
- **Microsoft Foundry** - Claude now available on Azure
- **67% Price Reduction** - Opus pricing significantly reduced

## Contents

- [Official Resources](#official-resources)
- [Models & Capabilities](#models--capabilities)
- [API & SDKs](#api--sdks)
- [Developer Tools](#developer-tools)
  - [CLI Tools](#cli-tools)
  - [IDE Integrations](#ide-integrations)
  - [Browser Extensions](#browser-extensions)
- [Prompt Engineering](#prompt-engineering)
- [Applications & Use Cases](#applications--use-cases)
  - [Coding & Development](#coding--development)
  - [Writing & Content](#writing--content)
  - [Research & Analysis](#research--analysis)
  - [Business & Productivity](#business--productivity)
- [Integrations](#integrations)
  - [Platforms](#platforms)
  - [Frameworks](#frameworks)
  - [Workflows](#workflows)
- [Community Projects](#community-projects)
- [Learning Resources](#learning-resources)
  - [Guides & Tutorials](#guides--tutorials)
  - [Courses](#courses)
  - [Papers & Research](#papers--research)
- [Comparisons & Benchmarks](#comparisons--benchmarks)
- [Best Practices](#best-practices)
- [Community](#community)
- [Related Lists](#related-lists)
- [Contributing](#contributing)

## Official Resources

- [Claude.ai](https://claude.ai/) - Official web interface for Claude
- [Anthropic Console](https://console.anthropic.com/) - API key management and usage dashboard
- [Anthropic Documentation](https://docs.anthropic.com/) - Official API documentation
- [Anthropic Blog](https://www.anthropic.com/news) - Company news and research updates
- [Claude API Status](https://status.anthropic.com/) - API uptime and incident reports
- [Anthropic Research](https://www.anthropic.com/research) - Research papers and findings

## Models & Capabilities

### Current Models (January 2026)

- **Claude Opus 4.5** - Most intelligent model (NEW)
  - Best-in-class for coding, agents, and computer use
  - 80.9% on SWE-bench Verified
  - 66.3% on OSWorld (computer use)
  - Hybrid reasoning with adjustable effort levels
  - 200K context window
  - $5/$25 per 1M tokens (input/output)

- **Claude 3.5 Sonnet** - Best balance model
  - Excellent speed and intelligence
  - 200K context window
  - Vision capabilities
  - Advanced reasoning and coding

- **Claude 3.5 Haiku** - Fast model
  - Improved speed and intelligence
  - Better code generation
  - Vision support
  - Cost-effective for simple tasks

- **Claude 3 Haiku** - Economy model
  - Quick responses
  - Most cost-effective
  - 200K context window
  - Good for simple tasks

### Key Features

- **Long Context**: 200,000 token context window (around 150,000 words)
- **Vision**: Analyze images, charts, diagrams, and screenshots
- **Artifacts**: Generate and iterate on content in separate windows
- **Tool Use**: Function calling, computer use, and tool search capabilities
- **Hybrid Reasoning**: Instant responses or extended thinking (Opus 4.5)
- **Agentic Workflows**: Multi-step planning, autonomous debugging, multi-agent setups
- **Enterprise Features**: Slides, spreadsheets, docs generation with sustained quality
- **Safety**: Constitutional AI for harmless and honest responses
- **Multilingual**: Supports multiple languages with high quality

## API & SDKs

### Official SDKs

- [Python SDK](https://github.com/anthropics/anthropic-sdk-python) - Official Python client
  - Streaming support
  - Async/await
  - Type hints
  - Retry logic

- [TypeScript SDK](https://github.com/anthropics/anthropic-sdk-typescript) - Official TypeScript/JavaScript client
  - Full TypeScript support
  - Streaming responses
  - Edge runtime compatible
  - Deno and Bun support

### Community SDKs

- [anthropic-go](https://github.com/liushuangls/anthropic-sdk-go) - Go client for Claude API
- [anthropic-rs](https://github.com/abdelhamidbakhta/anthropic-rs) - Rust client
- [claude-ruby](https://github.com/alexrudall/ruby-openai) - Ruby client with Claude support
- [ClaudeSharp](https://github.com/tghamm/Anthropic.SDK) - C#/.NET SDK

### API Tools

- [Claude API Playground](https://console.anthropic.com/workbench) - Interactive API testing
- [Anthropic Cookbook](https://github.com/anthropics/anthropic-cookbook) - Code examples and guides
- [Claude Rate Limiter](https://github.com/anthropics/anthropic-sdk-python/tree/main/examples) - Rate limiting examples
- [Token Counter](https://github.com/anthropics/anthropic-tokenizer) - Count tokens for Claude models

## Developer Tools

### CLI Tools

- [Claude Code](https://github.com/anthropics/anthropic-code) - Official terminal-based coding assistant
  - File operations
  - Multi-file editing
  - Bash execution
  - MCP integration

- [claude-cli](https://github.com/amidabuddha/unichat-claude-cli) - Command-line interface for Claude
  - Interactive chat
  - File inputs
  - Streaming responses

- [mods](https://github.com/charmbracelet/mods) - AI on the CLI with Claude support
  - Multiple AI providers
  - Markdown output
  - Pipe support

### IDE Integrations

- [Continue](https://continue.dev/) - Open-source AI coding assistant
  - Claude integration
  - VS Code & JetBrains
  - Autocomplete and chat
  - Custom models

- [Cursor](https://cursor.sh/) - AI-first code editor
  - Built-in Claude support
  - Chat with codebase
  - Multi-file editing
  - Composer mode

- [Cline (formerly Claude Dev)](https://github.com/cline/cline) - VS Code extension
  - Autonomous coding
  - Browser automation
  - File operations
  - Command execution

- [Zed](https://zed.dev/) - Collaborative code editor
  - Claude integration
  - Real-time collaboration
  - Fast performance

### Browser Extensions

- [ChatGPT and Claude Enhancer](https://github.com/josStorer/chatGPTBox) - Enhanced interface
  - Markdown support
  - Export conversations
  - Custom prompts

- [Claude to Markdown](https://github.com/bartolli/claude-to-markdown) - Export Claude conversations
  - Format preservation
  - Code blocks
  - One-click export

## Prompt Engineering

### Guides & Resources

- [Anthropic Prompt Library](https://docs.anthropic.com/claude/prompt-library) - Official prompt examples
- [Prompt Engineering Guide](https://docs.anthropic.com/claude/docs/prompt-engineering) - Best practices from Anthropic
- [Claude Prompting Techniques](https://github.com/anthropics/anthropic-cookbook/tree/main/prompts) - Advanced techniques
- [Constitutional AI Prompts](https://www.anthropic.com/constitutional-ai) - Alignment and safety

### Prompt Patterns

**System Prompts:**
- Role definition and expertise
- Output format specifications
- Tone and style guidelines
- Safety and ethical boundaries

**Chain-of-Thought:**
- Step-by-step reasoning
- Show your work approach
- Verification steps

**Few-Shot Examples:**
- Task demonstrations
- Format examples
- Edge case handling

**XML Tags:**
- Structured inputs
- Clear section separation
- Parsing and extraction

## Applications & Use Cases

### Coding & Development

- [Claude Code](https://claude.ai/claude-code) - Terminal-based coding assistant
- [Aider](https://aider.chat/) - AI pair programming with Claude
  - Git integration
  - Multiple files
  - Undo/redo

- [GPT Engineer](https://github.com/gpt-engineer-org/gpt-engineer) - Build apps from prompts
  - Claude support
  - Full project generation
  - Iterative development

- [Mentat](https://mentat.ai/) - Coding assistant in the terminal
  - Claude integration
  - Context-aware editing
  - Command-line workflow

### Writing & Content

- [Lex](https://lex.page/) - AI-powered writing
  - Claude integration
  - Document collaboration
  - Real-time assistance

- [Notion AI](https://www.notion.so/product/ai) - Workspace AI
  - Claude-powered features
  - Content generation
  - Summarization

- [Jasper](https://www.jasper.ai/) - Marketing content
  - Claude model option
  - Brand voice
  - Multiple formats

### Research & Analysis

- [Perplexity](https://www.perplexity.ai/) - AI search engine
  - Claude-powered mode
  - Source citations
  - Follow-up questions

- [Elicit](https://elicit.org/) - Research assistant
  - Paper analysis
  - Literature review
  - Data extraction

- [Consensus](https://consensus.app/) - Academic search
  - Research paper summaries
  - Evidence synthesis
  - Citations

### Business & Productivity

- [Zapier](https://zapier.com/apps/claude) - Workflow automation
  - Claude actions
  - 5000+ integrations
  - Custom workflows

- [Make](https://www.make.com/) - Automation platform
  - Claude integration
  - Visual workflow builder
  - Complex scenarios

- [Slack Claude App](https://www.anthropic.com/claude-in-slack) - Claude in Slack
  - Direct messages
  - Channel summaries
  - Team collaboration

## Integrations

### Platforms

- **LangChain** - [Python](https://python.langchain.com/docs/integrations/chat/anthropic) | [JS](https://js.langchain.com/docs/integrations/chat/anthropic)
  - Full Claude support
  - Streaming
  - Function calling
  - Agents

- **LlamaIndex** - [Docs](https://docs.llamaindex.ai/en/stable/examples/llm/anthropic/)
  - Claude integration
  - RAG support
  - Multi-modal

- **Haystack** - [Integration](https://haystack.deepset.ai/integrations/anthropic)
  - Claude components
  - NLP pipelines
  - Production-ready

- **Vercel AI SDK** - [Anthropic Provider](https://sdk.vercel.ai/providers/ai-sdk-providers/anthropic)
  - Claude models
  - React hooks
  - Streaming UI

### Frameworks

- [AutoGPT](https://github.com/Significant-Gravitas/AutoGPT) - Autonomous agents
  - Claude support
  - Goal-oriented
  - Plugin system

- [CrewAI](https://github.com/joaomdmoura/crewAI) - Multi-agent orchestration
  - Claude agents
  - Role-based
  - Collaborative

- [LangGraph](https://github.com/langchain-ai/langgraph) - Stateful agents
  - Claude integration
  - Graph-based workflows
  - Cycle support

### Workflows

- [n8n](https://n8n.io/) - Workflow automation
  - Claude node
  - Self-hostable
  - Visual builder

- [Flowise](https://flowiseai.com/) - Build LLM apps
  - Claude chains
  - No-code
  - Drag-and-drop

- [Dify](https://dify.ai/) - LLM app platform
  - Claude support
  - Prompt orchestration
  - API generation

## Community Projects

### Open Source

- [Open Interpreter](https://github.com/OpenInterpreter/open-interpreter) - Code interpreter
  - Claude support
  - Execute code locally
  - Multi-language

- [MemGPT](https://github.com/cpacker/MemGPT) - Long-term memory
  - Claude integration
  - Persistent context
  - Virtual context

- [Claude Engineer](https://github.com/Doriandarko/claude-engineer) - Advanced coding agent
  - Autonomous coding
  - File management
  - Project creation

### Tools

- [Claude API Proxy](https://github.com/anthropics/anthropic-proxy) - API gateway
  - Rate limiting
  - Caching
  - Analytics

- [Claude Cost Calculator](https://anthropic-cost-calculator.vercel.app/) - Estimate API costs
  - Token counting
  - Model comparison
  - Pricing calculator

- [Claude Prompt Manager](https://github.com/anthropic-tools/prompt-manager) - Organize prompts
  - Version control
  - Testing
  - Sharing

### Experiments

- [Claude with Vision](https://github.com/anthropics/anthropic-cookbook/tree/main/vision) - Image analysis examples
- [Claude Function Calling](https://github.com/anthropics/anthropic-cookbook/tree/main/function_calling) - Tool use patterns
- [Claude Computer Use](https://github.com/anthropics/anthropic-quickstarts/tree/main/computer-use-demo) - GUI automation
- [Claude Artifacts](https://github.com/anthropic-labs/claude-artifacts) - Experimental UI

## Learning Resources

### Guides & Tutorials

- [Getting Started with Claude](https://docs.anthropic.com/claude/docs/intro-to-claude) - Official introduction
- [Claude API Quickstart](https://docs.anthropic.com/claude/docs/quickstart-guide) - First API call
- [Prompt Engineering 101](https://docs.anthropic.com/claude/docs/prompt-engineering) - Fundamentals
- [Vision Guide](https://docs.anthropic.com/claude/docs/vision) - Working with images
- [Tool Use Guide](https://docs.anthropic.com/claude/docs/tool-use) - Function calling

### Courses

- [Anthropic's Prompt Engineering Course](https://github.com/anthropics/courses) - Official course materials
- [Building with Claude](https://www.deeplearning.ai/short-courses/prompt-engineering-with-anthropic/) - DeepLearning.AI course
- [Claude for Developers](https://www.udemy.com/topic/claude-ai/) - Udemy courses

### Papers & Research

- [Constitutional AI](https://arxiv.org/abs/2212.08073) - Training helpful and harmless AI
- [Claude 3 Model Card](https://www-cdn.anthropic.com/de8ba9b01c9ab7cbabf5c33b80b7bbc618857627/Model_Card_Claude_3.pdf) - Technical specifications
- [Measuring Massive Multitask Language Understanding](https://arxiv.org/abs/2009.03300) - MMLU benchmark
- [HumanEval Coding Benchmark](https://github.com/openai/human-eval) - Code generation evaluation

## Comparisons & Benchmarks

### Performance

- **MMLU (Graduate-level knowledge)**: Claude 3.5 Sonnet scores 88.7%
- **HumanEval (Coding)**: Claude 3.5 Sonnet scores 92%
- **GPQA (Graduate-level reasoning)**: Leading performance
- **MATH (Mathematical reasoning)**: Strong problem-solving

### Model Comparisons

**Claude vs GPT-4:**
- Longer context (200K vs 128K)
- Strong refusal training
- Better at following complex instructions
- More verbose by default

**Claude vs Gemini:**
- Different safety approaches
- Comparable context lengths
- Similar multimodal capabilities
- Different pricing structures

### Benchmarks

- [Chatbot Arena Leaderboard](https://chat.lmsys.org/) - Community rankings
- [Artificial Analysis](https://artificialanalysis.ai/) - Speed and quality metrics
- [Scale AI Leaderboard](https://scale.com/leaderboard) - Coding benchmarks
- [Berkeley Function Calling](https://gorilla.cs.berkeley.edu/leaderboard.html) - Tool use accuracy

## Best Practices

### API Usage

**Rate Limiting:**
- Implement exponential backoff
- Respect rate limits
- Cache responses when possible
- Use batch processing

**Cost Optimization:**
- Choose appropriate model for task
- Optimize prompt length
- Cache system prompts
- Monitor token usage

**Error Handling:**
- Implement retry logic
- Handle timeouts gracefully
- Log errors properly
- Fallback strategies

### Prompt Design

**Clarity:**
- Be specific and direct
- Provide context
- Use examples
- Define output format

**Structure:**
- Use XML tags for organization
- Separate instructions from data
- Clear section markers
- Consistent formatting

**Safety:**
- Set appropriate guardrails
- Define acceptable behaviors
- Test edge cases
- Monitor outputs

### Production Deployment

**Monitoring:**
- Track API latency
- Monitor error rates
- Log all interactions
- Set up alerts

**Security:**
- Secure API keys
- Validate inputs
- Sanitize outputs
- Implement access controls

**Scaling:**
- Use connection pooling
- Implement caching layers
- Load balancing
- Horizontal scaling

## Community

### Official Channels

- [Anthropic Discord](https://discord.gg/anthropic) - Community chat
- [Twitter/X](https://twitter.com/AnthropicAI) - Official updates
- [LinkedIn](https://www.linkedin.com/company/anthropicai/) - Company news
- [YouTube](https://www.youtube.com/@AnthropicAI) - Demos and talks

### Community Forums

- [r/ClaudeAI](https://www.reddit.com/r/ClaudeAI/) - Reddit community
- [Stack Overflow](https://stackoverflow.com/questions/tagged/claude-ai) - Technical Q&A
- [Hacker News](https://news.ycombinator.com/item?id=claude) - Discussions

### Newsletters

- [Anthropic Newsletter](https://www.anthropic.com/newsletter) - Official updates
- [The Batch](https://www.deeplearning.ai/the-batch/) - AI news (covers Claude)
- [Import AI](https://importai.substack.com/) - AI research digest

## Related Lists

- [awesome-chatgpt](https://github.com/humanloop/awesome-chatgpt) - ChatGPT resources
- [awesome-gpt4](https://github.com/radi-cho/awesome-gpt4) - GPT-4 resources
- [awesome-llm](https://github.com/Hannibal046/Awesome-LLM) - Large Language Models
- [awesome-prompt-engineering](https://github.com/tysoncung/awesome-prompt-engineering) - Prompt engineering
- [awesome-vibe-coding](https://github.com/tysoncung/awesome-vibe-coding) - AI coding tools

## Contributing

Contributions welcome! Please read the [contribution guidelines](CONTRIBUTING.md) first.

**What to contribute:**
- New tools and integrations using Claude
- Tutorials and guides
- Benchmarks and comparisons
- Use cases and success stories
- Open source projects

**Quality standards:**
- Must be Claude-specific or have Claude integration
- Active and maintained
- Well-documented
- Adds genuine value

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Tyson Cung](https://github.com/tysoncung) has waived all copyright and related or neighboring rights to this work.

---

**Star ⭐ this repo to stay updated with the latest Claude AI tools and resources!**
