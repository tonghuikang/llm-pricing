This is a single page with all the major LLM prices, cited.
All prices are dollars per million tokens.

Pull requests are welcome.

# OpenAI

| Model       | Input | Output |
| ----------- | ----- | ------ |
| gpt-4o      | 2.50  | 1.25   |
| gpt-4o-mini | 0.15  | 0.60   |
| o3-mini     | 1.10  | 4.40   |

For the full list of models, see [here](https://platform.openai.com/docs/pricing).

Sample code for an LLM call is [here](https://platform.openai.com/docs/quickstart).
You can count tokens [here](https://platform.openai.com/tokenizer).

[Batch mode](https://platform.openai.com/docs/guides/batch) provides 50% discount with a 24-hour turnaround time.
[Prompt caching](https://platform.openai.com/docs/guides/prompt-caching) provides 50% discount. Caching is available after 1024 tokens with increments of 128 tokens. You automatically opt in without additional costs. The cache has a 5-10 minute lifetime and refreshes upon use.


# Anthropic

| Model             | Input | Output |
| ----------------- | ----- | ------ |
| claude-3.7-sonnet | 3.00  | 15.00  |
| claude-3.5-haiku  | 0.80  | 4.00   |
| claude-3-haiku    | 0.25  | 1.25   |

For the full list of models, see [here](https://www.anthropic.com/pricing#anthropic-api).

Sample code for an LLM call is [here](https://docs.anthropic.com/en/api/getting-started).
Instructions to count tokens are [here](https://docs.anthropic.com/en/docs/build-with-claude/token-counting).

[Batch mode](https://www.anthropic.com/news/message-batches-api) provides 50% discount with 24-hour turnaround time.
[Prompt caching](https://docs.anthropic.com/en/docs/build-with-claude/prompt-caching) provides 90% discount. Caching is only available after 1024 or 2048 tokens. Caching requires opt-in and costs 25% more for the input tokens. The cache has a 5 minute lifetime and refreshes upon use.


# Gemini

| Model               | Input  | Output |
| ------------------- | ------ | ------ |
| gemini-1.5-flash    | 0.075  | 0.30   |
| gemini-1.5-flash-8b | 0.0375 | 0.15   |
| gemini-1.5-pro      | 1.25   | 5.00   |

For the full list of models, see [here](https://ai.google.dev/pricing) or [here](https://cloud.google.com/vertex-ai/generative-ai/pricing).

Sample code for an LLM call is [here](https://ai.google.dev/gemini-api/docs/quickstart) or [here](https://cloud.google.com/vertex-ai/generative-ai/docs/start/quickstarts/quickstart-multimodal) (not recommended).
Instructions to count tokens are [here](https://ai.google.dev/gemini-api/docs/quickstart).

[Batch mode](https://cloud.google.com/vertex-ai/generative-ai/docs/multimodal/batch-prediction-gemini) provides 50% discount and requires working on Google Cloud Console.
[Prompt caching](https://ai.google.dev/gemini-api/docs/caching) provides more than 90% discount. Caching is only available for prefixes longer than 32k tokens. Caching requires opt-in and charges per lifetime.

