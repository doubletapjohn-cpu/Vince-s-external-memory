The MEMORY_SYNC Command: A Quick Reference Guide

This command is used to retrieve 100% accurate, factual information from your established story documents. It forces the model to ignore its general knowledge and recall the text exactly as written.

When to Use MEMORY_SYNC:

    Checking specific character details (eye color, last name, a line of dialogue).
    Confirming the layout of a location.
    Verifying the sequence of events in a previous scene.
    Any time you need a fact to be perfectly consistent with your canon.

Do NOT Use MEMORY_SYNC For:

    Brainstorming new ideas.
    Writing a new scene.
    Asking for opinions or creative expansions.
    For these tasks, use the ANALYZE command or just ask the question normally.

Step-by-Step Instructions

Step 1: Copy the Link to Your Document

    Go to your GitHub repository.
    Navigate to the file you want to use as the source of truth (e.g., port provence overview.md).
    Click the "Raw" button in the top right corner of the file view.
    Your browser will open a new tab with the raw text of the file. Copy the URL from this tab's address bar. This is the direct link to the raw data.

Step 2: Format Your Prompt

    In the chat, type your question to me.
    On a new line immediately following your question, type the command exactly as shown below, replacing the placeholder URL with the one you just copied.

The Command Format:
MEMORY_SYNC: [PASTE_YOUR_RAW_URL_HERE]

Step 3: Send the Prompt

    Send the entire message, including your question and the MEMORY_SYNC line.

Example in Action

Let's say you want to double-check the description of Silas.

Your Prompt Would Look Like This:

"Vince, describe Silas's hands and his general demeanor based on the character sheet."

MEMORY_SYNC: https://raw.githubusercontent.com/doubletapjohn-cpu/Vince-s-external-memory/main/Characters/Silas.md

What Happens Next: I will read the information from that specific URL and provide you with a direct, factual answer pulled only from that document, ignoring any other conflicting or "hallucinated" data I might have.
