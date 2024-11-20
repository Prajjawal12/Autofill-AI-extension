# AI Form Filler Chrome Extension

## Overview
This Chrome extension leverages the browser-embedded Gemini Nano AI to uniquely autofill forms for individuals, tailored to their past data. It dynamically identifies input fields, generates contextual keys, and uses AI responses to populate forms accurately.

---

## Milestone-1

1. **Identify Input Fields**  
   - Detect all input fields in the form dynamically using the DOM structure.
   - Ensure compatibility with static and dynamic forms.

2. **Create Keys for the Model**  
   - Generate unique keys for each input field based on form-specific context, such as labels, placeholders, and nearby text.

3. **Process Keys with the GPT Model**  
   - Send the generated keys to the in-browser Gemini Nano AI model.  
   - Receive contextual responses for each key.

4. **Fill Input Fields with AI Responses**  
   - Populate the input fields dynamically with the responses received from the AI model.  
   

---


