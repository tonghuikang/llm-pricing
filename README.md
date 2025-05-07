This is a single page with all the major LLM prices, cited.
All prices are dollars per million tokens.

Pull requests are welcome.

# OpenAI

| Model        | Model Name                 | Input | Output |
| ------------ | -------------------------- | ----- | ------ |
| gpt-4o       | gpt-4o-2024-08-06          | 2.50  | 1.25   |
| gpt-4.1-nano | gpt-4.1-nano-2025-04-14    | 0.10  | 0.40   |
| o4-mini      | o4-mini-2025-04-16         | 1.10  | 4.40   |
| gpt-4.5      | gpt-4.5-preview-2025-02-27 | 75.00 | 150.00 |

For the full list of models, see [here](https://platform.openai.com/docs/pricing).

Sample code for an LLM call is [here](https://platform.openai.com/docs/quickstart).
You can count tokens [here](https://platform.openai.com/tokenizer).

[Batch mode](https://platform.openai.com/docs/guides/batch) provides 50% discount with a 24-hour turnaround time.
[Prompt caching](https://platform.openai.com/docs/guides/prompt-caching) provides 50% ~ 75% discount. Caching is available after 1024 tokens with increments of 128 tokens. You automatically opt in without additional costs. The cache has a 5-10 minute lifetime and refreshes upon use.


# Anthropic

| Model             | Model Name                 | Input | Output |
| ----------------- | -------------------------- | ----- | ------ |
| claude-3.7-sonnet | claude-3-7-sonnet-20250219 | 3.00  | 15.00  |
| claude-3.5-haiku  | claude-3-5-haiku-20241022  | 0.80  | 4.00   |
| claude-3-haiku    | claude-3-haiku-20240307    | 0.25  | 1.25   |

For the full list of models, see [here](https://docs.anthropic.com/en/docs/about-claude/models/all-models).

Sample code for an LLM call is [here](https://docs.anthropic.com/en/api/getting-started).
Instructions to count tokens are [here](https://docs.anthropic.com/en/docs/build-with-claude/token-counting).

[Batch mode](https://www.anthropic.com/news/message-batches-api) provides 50% discount with 24-hour turnaround time.
[Prompt caching](https://docs.anthropic.com/en/docs/build-with-claude/prompt-caching) provides 90% discount. Caching is only available after 1024 or 2048 tokens. Caching requires opt-in and costs 25% more for the input tokens. The cache has a 5 minute lifetime and refreshes upon use.


# Gemini

| Model               | Model Name              | Input  | Output |
| ------------------- | ----------------------- | ------ | ------ |
| gemini-1.5-flash    | gemini-1.5-flash-002    | 0.075  | 0.30   |
| gemini-1.5-flash-8b | gemini-1.5-flash-8b-001 | 0.0375 | 0.15   |
| gemini-1.5-pro      | gemini-1.5-pro-002      | 1.25   | 5.00   |

For the full list of models, see [here](https://ai.google.dev/pricing), [here](https://ai.google.dev/gemini-api/docs/models/gemini), or [here](https://cloud.google.com/vertex-ai/generative-ai/pricing).

Sample code for an LLM call is [here](https://ai.google.dev/gemini-api/docs/quickstart) or [here](https://cloud.google.com/vertex-ai/generative-ai/docs/start/quickstarts/quickstart-multimodal) (not recommended).
Instructions to count tokens are [here](https://ai.google.dev/gemini-api/docs/quickstart).

[Batch mode](https://cloud.google.com/vertex-ai/generative-ai/docs/multimodal/batch-prediction-gemini) provides 50% discount and requires working on Google Cloud Console.
[Prompt caching](https://ai.google.dev/gemini-api/docs/caching) provides more than 90% discount. Caching is only available for prefixes longer than 32k tokens. Caching requires opt-in and charges per lifetime.

