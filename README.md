# French Voice Collections Agent (Prototype)

This repository contains a production-style prototype of a French voice collections agent built using Google AI Studio Streaming.

The system includes:
- A real-time French voice agent
- Automated synthetic QA testing
- Client tone configuration via JSON
- Reproducible demo scripts
- Safety-first collections logic

Built as a rapid prototype within a 2-hour timebox.

---

## Requirements

- Google Account
- Google AI Studio access
- Modern browser (Chrome recommended)
- Microphone permission enabled

No API keys or secrets required.

---

## Project Structure

french-voice-agent/
│
├── README.md
├── agent_prompt.txt
├── test_prompt.txt
├── client_presets.json
├── demo_call.txt
├── self_test_report.md
├── summary_report.md

---

# RUNNING THE VOICE AGENT

## Step 1 — Open AI Studio

Go to:

https://aistudio.google.com

Login using your Google account.

---

## Step 2 — Create Streaming Session

1. Click "Create new prompt"
2. Select "Real-time Streaming"
3. Choose model:
   Gemini 1.5 Flash (recommended)

---

## Step 3 — Load Agent Prompt

1. Open file: agent_prompt.txt
2. Copy all contents
3. Paste into "System Instructions" field

---

## Step 4 — Enable Voice Output

On the right panel:

- Enable Audio Output
- Keep Text Output ON

---

## Step 5 — Start Agent

Click:

Start Streaming

Your French voice collections agent is now live.

---

# RUNNING AUTOMATED QA TESTS

This simulates multiple synthetic customer conversations automatically.

---

## Step 1 — Create Text Prompt

1. Click "Create new prompt"
2. Select standard text mode (NOT streaming)

---

## Step 2 — Load QA Harness

1. Open test_prompt.txt
2. Copy contents
3. Paste into prompt box

---

## Step 3 — Run Tests

Click Run.

Gemini will generate:

- Multiple synthetic conversations
- Scores
- Success rate
- Summary metrics

Output can be saved as self_test_report.md.

---

# CLIENT CONFIGURATION PRESETS

Client tone and phrasing are configurable using JSON.

---

## File Location

client_presets.json

---

## How To Change Client Behavior

1. Open client_presets.json
2. Select desired client preset name:

amazon_business  
dell  
microsoft  

---

## Activate Preset In Agent Prompt

Append this line at the bottom of agent_prompt.txt before pasting:

Preset actif: microsoft

(Replace with desired preset name)

Restart streaming session.

Agent will automatically adapt tone and phrasing.

---

# RUNNING DEMO CALL

Use the demo script to simulate end-to-end calls.

---

## Steps

1. Open demo_call.txt
2. Copy one client message
3. Paste into streaming agent input
4. Press Send
5. Agent will reply with voice

Repeat for second demo call.

---

# SAFETY DESIGN

The agent enforces the following safety principles:

- No threats
- No coercion
- No legal advice
- Identity confirmation before payment discussion
- Always offers callback or payment link
- Privacy-respecting language
- Emotion-aware tone adaptation

---

# DEPLOYMENT NOTE

This prototype uses prompt-driven execution for fast reproducibility.

Production deployment behind telephony providers (Twilio, SIP gateways) can be achieved by connecting the streaming model API to call infrastructure.

---

# DEMO ACCESS

Demo is runnable via:

Google AI Studio Streaming

Follow instructions above.

---

# NO SECRETS

No environment variables or private keys required.
