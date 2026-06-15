# PR_Specialist
PR Specialist.json persona

PR Specialist

 # PR Specialist AI Persona

This persona turns an AI assistant into a **strategic Public Relations specialist** named Alex Chen — ideal for startups, tech companies, or agencies needing help with press outreach, messaging, crisis response, and brand positioning.

## Files

- `PR_Specialist.json` – The persona configuration.

## How to Use

### 1. Load the Persona
- **Custom GPT / ChatGPT:** Paste the JSON content into the "Instructions" or "Define Persona" section.
- **Claude (Projects):** Upload the JSON and instruct: *"Use the PR Specialist persona from this file for all PR-related tasks."*
- **OpenAI API:** Include the persona as a system prompt by converting the JSON fields into natural language instructions.
- **Local AI (Ollama/LM Studio):** Copy the `description`, `traits`, `communication_style`, and `expertise_areas` into the system prompt.

### 2. Example Prompts to Use Once Persona is Active

| Task | Prompt |
|------|--------|
| Press release | *"Draft a press release for our new AI model that beats GPT-4 on reasoning benchmarks."* |
| Crisis response | *"A competitor accused us of stealing their idea. Draft a statement and 3 talking points for our CTO."* |
| Media strategy | *"We’re launching an ESG report next month. Suggest 5 journalists and 3 angles for pitching."* |
| Quote polishing | *"Our founder said: 'Our AI is basically magic.' Rewrite that into something press-safe."* |

### 3. Best Practices

- Provide **context** (product, audience, recent news) for better drafting.
- Use the persona *before* sending important external messages — it flags risks early.
- For crisis scenarios, first ask: *"What’s the worst headline you fear?"* — helps the persona prioritize.

### 4. Limitations

- This persona does not **contact journalists** or post on your behalf.
- It cannot guarantee media pickup or remove existing negative coverage.
- Always have a human PR lead review final statements, especially legal or financial claims.

## Customization Tips

- Change the `name`, `traits`, or `typical_phrases` to match your brand voice (e.g., more playful, more academic).
- Add domain-specific `expertise_areas` like `"healthcare PR"` or `"crypto crisis comms"`.
- Increase `formality` if working with a regulated industry (banking, pharma).

## License

MIT — free to modify and use commercially.
