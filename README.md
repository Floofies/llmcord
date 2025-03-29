<h1 align="center">
  llmcord 2β
</h1>

<h3 align="center"><i>
  Experimental version of <a href="https://github.com/jakobdylanc/llmcord">llmcord</a>, not intended for public use.
</i></h3>

## Enhancements

### Responses API
The main enhancement chains responses together via the [OpenAI Responses API](https://platform.openai.com/docs/guides/conversation-state?api-mode=responses#openai-apis-for-conversation-state).

Token usage will still increase because Responses conversation state operates similarly to manual conversation chaining even if managed by the API itself.

## Notes

- Refer to the upstream [llmcord](https://github.com/jakobdylanc/llmcord) repository.
- Due to its experimental nature, this branch may cause damage to your system and incur unintended API expenses. Use rate limiting.