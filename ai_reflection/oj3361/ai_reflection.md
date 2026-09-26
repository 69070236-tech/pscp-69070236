# AI Reflection

Use this file only when AI was used on a learning-log-required OJ problem.

Copy this template and rename the file as:

```text
ai_reflection.md
```

Write this reflection in your own words.

Do not paste the full AI conversation.

Do not ask AI to write this reflection for you.

AI may help check grammar, formatting, or clarity after you have already written your own reflection.

---

## 1. OJ Information

| Item | Answer |
|---|---|
| OJ problem number/title | OJ3361 - ขายรถยนต์ |
| OJ submission ID, if submitted | 669150 |
| OJ status | Pass |

---

## 2. AI Tool Used

Write the AI tool or tools that you used.

Examples:

```text
ChatGPT
Claude
Gemini
ChatGPT Codex / OpenAI Codex / Codex CLI
Claude Code
Other: ...
```

My answer:

```text
Claude
```

---

## 3. Required Course AI Policy Check

Answer this section honestly.

This section confirms that you followed the course AI workflow before and while using AI.

| Statement | Yes / No / Not Applicable | Short note |
|---|---|---|
| I read the relevant workflow before using AI. | Yes |  |
| I used `instructions/COURSE_AI_INSTRUCTIONS.md`, `instructions/AGENTS.md`, or manually followed the course AI instructions if the tool did not support custom instructions. | Yes |  |
| I wrote my own problem understanding before asking AI for help. | Yes |  |
| I wrote my own first plan before asking AI for help. | Yes |  |
| I used AI as a coach, reviewer, debugger, or test-case helper, not as a full-answer generator. | Yes |  |

If you answered "No" to any item, explain why:

```text

```

---

## 4. What I Asked AI to Help With

Describe briefly what you asked AI to help with.

Do not paste the full chat log.

Examples:

- I asked AI to explain the problem in simpler words.
- I asked AI to review my first plan.
- I asked AI to help find a bug in my code.
- I asked AI to suggest test cases.
- I asked AI to explain why my output was different from the expected output.

My answer:

```text
I asked Claude how to calculate the in-between car.
```

---

## 5. What AI Helped Me Notice

Write what AI helped you notice.

Examples:

- a misunderstanding in the problem,
- a missing condition,
- a bug in input reading,
- an edge case,
- a Python syntax issue,
- an output formatting problem.

My answer:

```text
I don't need to use a dict. This problem uses the suffix maximum technique, starting from the last input, since the last one will be the cheapest; if the current car has more V than the next one, that means there's an unsellable car. Keep doing this until the end of the list.
```

---

## 6. What I Checked or Changed by Myself

Write what you verified, tested, or changed by yourself after receiving AI help.

Examples:

- I checked the input format again in the OJ problem.
- I tested the code in VS Code.
- I compared expected output and actual output.
- I changed the loop condition by myself.
- I rejected one AI suggestion because it did not match the problem constraints.
- I simplified the AI suggestion into code that I understood.

My answer:

```text
I follow the instructions and try to code it myself before getting the answer.
```

---

## 7. What I Learned

Write 2-4 sentences about what you learned from this problem and from the AI-assisted process.

Focus on your own learning.

Do not write only "I learned coding" or "AI helped me."

My answer:

```text
Using max to compare V. Suffix/prefix max-min.
```

---

## 8. Student Declaration

Answer honestly.

| Statement | Yes / No |
|---|---|
| I wrote this reflection in my own words. | Yes |
| This reflection describes my real AI use. | Yes |
| I checked AI's suggestions before using them. | Yes |
| I can explain my final code. | Yes |
| I did not ask AI to write this reflection for me. | Yes |
