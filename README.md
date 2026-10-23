# StudyMate — Student Voice Assistant

StudyMate is an independent, beginner-built web prototype for helping students break study intentions into small tasks. It demonstrates a conversational, voice-friendly assistant pattern relevant to a simulated Alexa+ experience.

## Current features
- Add, complete, and delete tasks.
- Ask the assistant to create a simple order for open tasks.
- Ask for current priorities.
- Optional browser speech recognition where supported.
- Responsive layout for laptop and phone.

## Important limitations
- This is a local prototype, not a real Alexa+ integration, Alexa Skill, or MCP server.
- The assistant uses simple local rules; it does not call a large language model.
- Tasks are stored only in the current page session and are not synced.
- Voice recognition depends on browser support and permissions.
- This is not an Amazon product and is not affiliated with or endorsed by Amazon.

## Run it
1. Download or clone this repository.
2. Open `index.html` in a modern browser. Typing and task management should work locally.
3. For microphone features, use a browser/environment that supports Web Speech API and grants microphone permission. If voice recognition is unavailable, use text input.

## Demo checklist
1. Open the app.
2. Add “Practice C loops” and “Finish lab record”.
3. Type “Plan my day” and show the generated order.
4. Mark one task complete.
5. If microphone access works, demonstrate one voice command; otherwise say voice input is browser-dependent.
6. Explain that this is a prototype with rule-based responses and no real Alexa+ backend.

## Hackathon submission note
Before submitting, verify the current official rules and confirm that a simulated assistant is acceptable for the Alexa+ track. Do not claim an actual Alexa+ integration, AWS service, or AI model unless you implement and test it.
