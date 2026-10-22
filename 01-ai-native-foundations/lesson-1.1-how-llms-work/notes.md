# Lesson 1.1 — How an LLM actually works

## It predicts the next token
An LLM reads the text so far and predicts the most likely next piece. Then it adds that piece and repeats.

A **token** is a word fragment, roughly ¾ of an English word. Telugu and Hindi usually take more tokens per word, so they cost more and fill the context window faster.

## It's trained in two stages
1. **Pretraining** on huge amounts of text teaches it language and facts.
2. **Post-training** teaches it to follow instructions and behave like an assistant.

## Its knowledge is like Import mode
What it learned is frozen at the training cutoff, like a semantic model refreshed once and never again.

To give it current or private data, you put that data into the prompt at question time. That's closer to DirectQuery, and it's what RAG does (Module 8).

## It has no memory between calls
Everything it "knows" in a given moment is its training plus whatever is in the current **context window**. Chat apps fake memory by re-sending the conversation each time.

## Why it hallucinates
It produces text that *sounds* plausible, not text it looked up. Its tone is always confident, whether it's right or wrong.

## When to trust it

| Strong | Weak |
|--------|------|
| Transforming information you give it (summarise, extract, reformat) | Recalling exact niche facts |
| Writing code you can run and test | Arithmetic over many numbers |
| | Anything after its training cutoff |

## Key terms
- **Token** — the unit an LLM reads and writes
- **Context window** — everything the model can see in one call
- **Training cutoff** — the date its knowledge stops
- **Hallucination** — plausible-sounding output that isn't true
