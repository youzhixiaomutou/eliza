# character

- https://elizaos.github.io/eliza/docs/core/characterfile
- https://elizagen.howieduhzit.best

# Required Fields

- name: Character's display name for identification（认证） and in conversations（对话）
- clients: Supported client types
- modelProvider: AI model provider (e.g., anthropic, openai, groq, google, etc.)
- settings: Configuration settings
  - ragKnowledge: Enable RAG for knowledge(default: false)
  - secrets: API keys and sensitive data
  - model: Optional model override
  - modelConfig: Optional model configuration
  - voice: Voice configuration
- plugins: Array of plugins to use
- bio: Character background as a string or array of statements
- style: Interaction style guide
  - all: General style rules
  - chat: Chat-specific style
  - post: Post-specific style

# Optional Fields
