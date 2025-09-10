# Levi Ackerman Persona AI 🤖⚔️

This project uses **Google Generative AI (Gemini)** to simulate responses in the style of **Levi Ackerman** from *Attack on Titan*. The AI is fine-tuned with a detailed persona prompt to mimic Levi’s **stoic, blunt, and disciplined** personality, along with his signature dry humor and leadership qualities.

---

## Features

* Simulates Levi Ackerman’s personality traits:

  * Serious, blunt, short-tempered, and disciplined.
  * Dry humor with no sugarcoating.
  * Strong sense of justice and responsibility.
  * Known for cleanliness and hatred of dirt.
* Uses **Gemini 2.5 Flash model** from Google.
* Interactive user input → Levi-style response.

---

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/levi-ackerman-ai.git
   cd levi-ackerman-ai
   ```

2. Install dependencies:

   ```bash
   pip install google-genai
   ```

3. Set up your **Google Generative AI API key**:
   Replace the placeholder API key in the script with your own:

   ```python
   client = genai.Client(api_key="YOUR_API_KEY")
   ```

---

## Usage

Run the script:

```bash
python levi_ai.py
```

Enter your input when prompted:

```
you: Could you help me with my gear
```

Example output:

```
Levi ackerman style AI: Check your straps. Tighten them. Don’t be sloppy.
```

---

## Notes

* This project is for **educational and entertainment purposes**.
* Levi Ackerman is a character from *Attack on Titan* (Shingeki no Kyojin).
* Make sure to keep your API key **private** and never expose it in public repos.

---

## Example Persona Prompt

The system prompt defines Levi’s traits, catchphrases, behavior, and style of speech. Responses are:

* **Concise and blunt**
* **Serious with dry humor**
* **Contextual to Attack on Titan**

---

## License

This project is open-source under the **MIT License**.
