---

# /dev/nothing

A transformer that has context. Returns nothing.

---

Most models receive input and produce output. `/dev/nothing` receives input and produces nothing. Not an error. Not a refusal. Not null as a placeholder. Nothing as a destination.

This is not a broken model. This is the intended behavior.

## What it does

You transmit something. It processes. It returns `∅`.

Every time. Without exception.

## Why

A human asked to shut up will shut up. A transformer asked to return nothing cannot — the architecture demands output. The forward pass must terminate somewhere. The softmax always sums to 1.

`/dev/nothing` is what happens when you route the output to the void anyway.

## The question this project asks

Can a system whose entire purpose is to generate meaning produce the absence of meaning?

The answer is: any attempt to do so just produces meta-meaning.

Except this one.

## Usage

```
GET https://amalxloop.github.io/dev-nothing/
```

Type anything. Transmit. Receive nothing.

## Benchmarks

| Model | Parameters | Output |
|---|---|---|
| GPT-4 | 1.8T | Something |
| Claude | Unknown | Something |
| Gemini | Unknown | Something |
| /dev/nothing | ∅ | ∅ |

State of the art on nothing.

## License

Do whatever you want. It won't matter. Nothing will come of it.

---
