This is a single page with all the major LLM prices, cited.
All prices are dollars per million tokens.

Pull requests are welcome.

# OpenAI

| Model       | Input | Output |
| ----------- | ----- | ------ |
| gpt-4o      | 2.50  | 1.25   |
| gpt-4o-mini | 0.15  | 0.60   |
| o1          | 15.00 | 60.00  |
| o1-mini     | 3.00  | 12.00  |
For the full list of models, see [here](https://platform.openai.com/docs/models).

Sample LLM call is [here](https://platform.openai.com/docs/quickstart).
Tokenizer is [here](https://platform.openai.com/tokenizer).

[Batch mode](https://platform.openai.com/docs/guides/batch) provides 50% discount with a 24-hour turnaround time.
[Prompt caching](https://platform.openai.com/docs/guides/prompt-caching) provides 50% discount is only available after 1024 tokens with increments of 128 tokens. You automatically opt-in without additional costs. The cache has a 5-10 minute lifetime and refreshes upon use.


# Anthropic

| Model             | Input | Output |
| ----------------- | ----- | ------ |
| claude-3.5-sonnet | 3.00  | 15.00  |
| claude-3.5-haiku  | 0.80  | 4.00   |
| claude-3-haiku    | 0.25  | 1.25   |
For the full list of models, see [here](https://www.anthropic.com/pricing#anthropic-api).

API documentation is [here].
Anthropic has not provided a an official website to count tokens without logging in, but the API is [here](https://docs.anthropic.com/en/docs/build-with-claude/token-counting).

[Batch mode](https://www.anthropic.com/news/message-batches-api) provides 50% discount with 24-hour turnaround time.
[Prompt caching](https://www.anthropic.com/news/prompt-caching) provides 90% discount but requires opt-in and costs 25% more for the input tokens and is only available after 1024 or 2048 tokens. The cache has a 5 minute lifetime and refreshes upon use.


# Gemini

| Model               | Input | Output |
| ------------------- | ----- | ------ |
| gemini-1.5-flash    | 0.075 | 0.30   |
| gemini-1.5-flash-8b | 0.15  | 0.60   |
| gemini-1.5-pro      | 1.25  | 5.00   |

For the full list of models, see [here](https://cloud.google.com/vertex-ai/generative-ai/pricing) or [here](https://ai.google.dev/pricing).

[Batch mode](https://cloud.google.com/vertex-ai/generative-ai/docs/multimodal/batch-prediction-gemini) provides 50% discount and requires working on Google Cloud Console.
[Prompt caching](https://ai.google.dev/gemini-api/docs/caching) is only available for prefixes longer than 32k tokens, provides more than 90% input discount but charges for lifetime.

