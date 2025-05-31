Todo:  
create notebooks with empty solutions


# Workshop: AI Engineering with Google Gemini 2.5

This workshop teaches how to build advanced AI applications with the Google Gemini 2.5 model family, focusing on practical engineering skills for building agentic AI systems.

> [!NOTE]
> The notebooks include the workshops and learning exercises. You'll find solutions in the [solutions](./solutions/) folder.

**Prerequisites**: You need an API key from [Google AI Studio](https://aistudio.google.com/apikey). Everything can be done on the free tier. Install the `google-genai` package with `pip install -U -q "google-genai"`.

**Acknowledgment**: This workshop structure is inspired by [Patrick Loeber's excellent Gemini workshop](https://github.com/patrickloeber/workshop-build-with-gemini/tree/main). Check out his work for additional learning resources.

## Course Outline

### [Part 0: Setup and Authentication](./notebooks/00-setup-and-authentication.ipynb)
- Google AI Studio setup and API key configuration
- Installing the Python SDK (`google-genai`)

### [Part 1: Text Generation and Chat](./notebooks/01-text-generation-and-chat.ipynb)
- Basic text generation and streaming responses
- Token counting and cost management
- Multi-turn chat conversations
- System instructions and model configuration
- Long context handling and file uploads

### [Part 2: Multimodal Capabilities](./notebooks/02-multimodal-capabilities.ipynb)
- Image understanding and analysis (single and multiple images)
- Audio processing (transcription, analysis, summarization)
- Video understanding (summarization, transcription)
- Document processing (PDFs, structured data extraction)
- Text-to-speech generation & Image generation 

### [Part 3: Structured Outputs, Function Calling & Tools](./notebooks/03-structured-outputs-function-calling-tools.ipynb)
- Structured outputs with Pydantic schemas
- Function calling and external API integration
- Native tools (code execution, Google Search, grounding)
- Automatic function calling capabilities

### [Part 4: Model Context Protocol (MCP)](./notebooks/04-model-context-protocol-mcp.ipynb)
- Introduction to Model Context Protocol
- Working with stdio and HTTP MCP servers
- Building interactive chat agents with MCP

## Resources

- [Google AI Studio](https://aistudio.google.com/)
- [Gemini API Documentation](https://ai.google.dev/gemini-api/docs)
- [Python SDK Reference](https://ai.google.dev/gemini-api/docs/sdks/python)
- [Model Context Protocol](https://modelcontextprotocol.io/)
