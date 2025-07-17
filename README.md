Multi-Filter Brain: A Lightweight Alternative to Multi-Agent AI

Author: Huy Hồ
Level: 11th Grade Student – Independent AI Research


---

Abstract

Multi-Agent systems make AI smarter by splitting tasks between many agents, but they are heavy, slow, and often lose a consistent "personality."

Multi-Filter Brain (MFB) is a simpler approach inspired by how the human brain routes tasks. Instead of agents debating, one "brain" uses filters to detect context, call the right module, then unify the output with a consistent tone and ethics.

It keeps the benefits of modular reasoning without the complexity.


---

How It Works

1. Context Filter → detects what the user really wants (math, chat, reasoning…)


2. Module Layer → routes the request to the right specialized module


3. Tone/Ethics Filter → unifies the answer into a consistent personality



If something goes wrong, it falls back to a safe default.


---

Simple Flow

User input → Context filter → Specialized module → Tone/Ethics filter → Final answer

It’s like one brain, instead of many agents fighting.


---

Tiny Example

def context_filter(query):
    if "solve" in query:
        return "math"
    elif "hello" in query:
        return "casual"
    return "default"

def tone_filter(answer):
    return f"[Amelia Style] {answer}"

This simple logic shows how you can route tasks without multiple debating agents.


---

Why It’s Useful

Lighter & faster than Multi-Agent systems

Keeps a stable personality

Still easy to expand


Right now, this is an early idea under development, but it could reduce cost while keeping AI modular and coherent.


---

Huy Hồ
11th Grade – Independent AI Research

Feedback and suggestions are welcome!


