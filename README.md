\## AI Chat Summary Generator



An AI-powered Node.js application that summarizes chat conversations into short, easy-to-read summaries.  

This project is useful for quickly understanding long chats from support systems, messaging apps, or team discussions.



\### Overview



The AI Chat Summary Generator takes raw chat text (or a chat log) as input and produces a concise summary that captures:

\- The \*\*main topics\*\* discussed

\- \*\*Key decisions\*\* or outcomes

\- Any \*\*important action items\*\*



It is designed to be simple to run and easy to integrate into other tools or workflows.



\### Features



\- \*\*Automatic summarization\*\*: Converts long chat histories into short, meaningful summaries.

\- \*\*Key information focus\*\*: Highlights main points, decisions, and important context.

\- \*\*User-friendly workflow\*\*: Simple input → summarized output.

\- \*\*Extendable\*\*: Can be integrated with front-end UIs, chat apps, or APIs with minimal changes.





\### Tech Stack



\- \*\*Runtime\*\*: Node.js (recommended: 18+)

\- \*\*Package manager\*\*: npm

\- \*\*Backend\*\*: Node.js (JavaScript/TypeScript, depending on your implementation)

\- \*\*AI / NLP\*\*: (e.g. OpenAI API, other LLM APIs, or custom models – update this based on what you actually use)



\### Requirements



\- \*\*Node.js\*\*: Version 18 or higher

\- \*\*npm\*\*: Comes with Node.js

\- \*\*API keys\*\*:   OpenAI( `OPENAI\_API\_KEY` in a `.env` file.)



\### Installation





1\.. Open a terminal in the project directory.

2. Install dependencies:



npm install

\### How to Run



Start the application with:npm startDepending on your implementation, this may:

\- Open your browser and go to `http://localhost:3000`



\*\*Input\*\*:  

&nbsp; - Paste or send a block of chat messages (e.g. from WhatsApp, Slack, support chat logs, etc.).

\- \*\*Processing\*\*:  

&nbsp; - The app sends the text to the AI model (or local logic) to generate a summary.

\- \*\*Output\*\*:  

&nbsp; - A short, readable summary with the most important points.





\### Configuration

OPENAI\_API\_KEY=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

PORT=3000



future scope:\*\*Multiple summary styles\*\* (short, detailed, bullet-point).

\- \*\*Support for different chat formats\*\* (Slack export, WhatsApp, custom logs).

\- \*\*Web UI\*\* for uploading chat files and viewing summaries.

\- \*\*History storage\*\* so users can view past summaries.



