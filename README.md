
# EXP 5: COMPARATIVE ANALYSIS OF DIFFERENT TYPES OF PROMPTING PATTERNS AND EXPLAIN WITH VARIOUS TEST SCENARIOS

# Aim: To test and compare how different pattern models respond to various prompts (broad or unstructured) versus basic prompts (clearer and more refined) across multiple scenarios.  Analyze the quality, accuracy, and depth of  the generated responses 

### AI Tools Required: 
* ChatGPT

# Explanation: 
Define the Two Prompt Types:

Write a basic Prompt: Clear, detailed, and structured prompts that give specific instructions or context to guide the model.
Based on that pattern type refined the prompt and submit that with AI tool.
Get the ouput and write the report.

Prepare Multiple Test Scenarios:
Select various scenarios such as:
Generating a creative story.
Answering a factual question.
Summarizing an article or concept.
Providing advice or recommendations.
Or Any other test scenario
For each scenario, create both a naïve and a basic prompt. Ensure each pair of prompts targets the same task but with different levels of structure.
Run Experiments with ChatGPT:
Input the naïve prompt for each scenario and record the generated response.
Then input the corresponding basic prompt and capture that response.
Repeat this process for all selected scenarios to gather a full set of results.

Evaluate Responses : 
	Compare how ChatGPT performs when given naïve versus basic prompts and analyze the output based on Quality,Accuracy and Depth. Also analyse does ChatGPT consistently provide better results with basic prompts? Are there scenarios where naïve prompts work equally well?
	
Deliverables:
A table comparing ChatGPT's responses to naïve and basic prompts across all scenarios.
Analysis of how prompt clarity impacts the quality, accuracy, and depth of ChatGPT’s outputs.
Summary of findings with insights on how to structure prompts for optimal results when using ChatGPT.


# OUTPUT:
The experiment compared AI responses across four scenarios to analyze the impact of prompt clarity on Quality, Accuracy, and Depth.

![images (4)](https://github.com/user-attachments/assets/b8c39ee7-1fb8-45f2-88fe-6b27a77f878e)


## Scenario 1: Generating a Creative Story 
**Prompt: "Write a story about a futuristic city."**

Response: Generic description of flying cars, neon signs, and a protagonist (Kai) contemplating the busy life below.

Analysis:

Quality: Low (Relied on common tropes; unoriginal).

Depth: Low (Static character; lacked specific conflict or emotional arc).

Basic Prompt: "Act as a Sci-Fi Noir writer. Write a 5-paragraph short story set in a futuristic, perpetually rainy city called Neo-Veridia. The protagonist, Detective Kaito, is looking for a missing sentient AI. Use a cynical and atmospheric tone."

Response: Focused narrative using the requested tone, introducing Detective Kaito's internal monologue and the specific, high-stakes mystery of the missing AI.

Analysis:

Quality: High (Atmospheric; professional writing style due to the persona).

Depth: High (Focused on a specific internal state and complex plot element).

Insight: Constraints (genre, setting, plot) forced the model to generate a unique, high-quality narrative.

## Scenario 2: Answering a Factual Question
**Prompt: "What caused World War I?"**

Response: A long list detailing the main causes: M.A.I.N. (Militarism, Alliances, Imperialism, Nationalism).

Analysis:

Accuracy: High (Factually correct, but unfocused).

Depth: Medium (Broad coverage; superficial explanation of each factor).

Basic Prompt: "Explain the two most critical long-term systemic causes of World War I, focusing strictly on the Alliance System and Militarism. Provide the response in a two-part, titled essay structure (300 words total) suitable for a college-level history exam."

Response: Highly structured, two-part essay analyzing the rigidity of the Alliance System and the role of escalating military technologies and mobilization plans.

Analysis:

Accuracy: High (Provided the exact, relevant subset of historical information requested).

Depth: High (Achieved targeted academic depth on systemic functions).

Insight: Specific focus ensures the model bypasses generic knowledge to deliver the most relevant and actionable information for the task.

## Scenario 3: Providing Advice/Recommendation
**Prompt: "How do I save money?"**

Response: A list of generic tips: make a budget, cut non-essentials, set goals, cook at home.

Analysis:

Quality: Low (Canned advice).

Accuracy: Low (Not specifically accurate to any user's situation).

Basic Prompt: "Act as a Certified Financial Planner (CFP). Provide 3 actionable and specific recommendations for a single individual with $50,000 in student loan debt and a $3,000 monthly take-home income. Use a professional and encouraging tone. Format the output as a numbered list with bolded headings."

Response: Three specific, prioritized steps: 1. Implement the 50/30/20 Budget Rule (with dollar breakdowns). 2. Prioritize High-Interest Debt with the Avalanche Method. 3. Automate a Small Emergency Fund.

Analysis:

Quality: High (Authoritative and actionable).

Accuracy: High (Recommendations were personalized and based on the exact figures provided).

Insight: Adding Persona (CFP) and Context (specific income/debt) transforms general advice into highly useful and customized guidance.

## Scenario 4: Summarizing a Concept
**Prompt: "Explain the butterfly effect."**

Response: A simple paragraph linking a butterfly's flap to a hurricane, often using the non-technical "spooky action" analogy.

Analysis:

Depth: Low (Surface definition only).

Accuracy: Low (Not nuanced enough for a professional setting).

Basic Prompt: "Summarize the Chaos Theory concept of the Butterfly Effect for an executive audience in the finance sector. Your summary must be under 150 words and frame the concept specifically in terms of financial market risk and forecasting."

Response: Concise, technical summary defining the concept in terms of extreme sensitivity to initial conditions, then applying it to finance (e.g., small market perturbations leading to systemic, unpredictable risk).

Analysis:

Depth: High (Applied theoretical concept to a specialized, real-world context).

Accuracy: High (Adhered to the executive audience, finance sector framing, and word count).

Insight: Structure dictates framing. The Basic prompt forced the model to repackage its knowledge to meet the specific professional needs of the audience.
![What-is-an-AI-Prompt-Engineering](https://github.com/user-attachments/assets/5ceab193-eba9-428f-91cb-3c28d5a7d171)


# How to Structure Prompts for Optimal Results:

Use the C.A.F.T.R. Framework for Basic/Refined Prompts:


<img width="867" height="402" alt="Screenshot 2025-09-27 133844" src="https://github.com/user-attachments/assets/62eb2664-75a0-4a31-a9ca-fdad3aa6bb42" />

# Overall Analysis of Prompt Clarity


![1_p-IVZ1iGJL_pmY6B2SlI8g](https://github.com/user-attachments/assets/aa7d6486-4b12-4d07-938c-fe9c96bbb1f3)

**1. Impact on Quality**

Result: Basic Prompts consistently generated higher-quality outputs.

Reason: By specifying a persona ("CFP," "Sci-Fi Noir writer"), the Basic prompt forced the model to adopt a higher-level, more polished, and context-appropriate vocabulary and tone, overcoming the model's tendency to default to generic prose.

**2. Impact on Accuracy**

Result: Basic Prompts delivered higher utility and specific accuracy.

Reason: While Naïve prompts are often factually correct, Basic prompts were accurate to the user's intent (e.g., "systemic causes" vs. "all causes") and provided information personalized to the given constraints (e.g., specific budget recommendations for a $3,000 income).

 **3. Impact on Depth**
 
Result: Basic Prompts achieved targeted, functional depth.

Reason: Clarity acts as a filter. Instead of producing superficial depth (covering many things briefly), the Basic prompt forced the model to drill down on a single, complex aspect, leading to a much more useful and scholarly output.

 **4. Conclusion on Consistency**
 
Consistency: Yes, Basic Prompts consistently provided better results. The structure effectively channels the LLM's vast knowledge, preventing a generic response and ensuring a focused, high-utility output tailored to the specific task.

Naïve Usefulness: Naïve prompts only work equally well when the user genuinely needs a quick, simple definition or a low-stakes brainstorming idea. Any task requiring precision, specific context, or specialized framing requires a Basic/Refined prompt.

 **5. Optimal Prompt Structure (Key Components)**
 
For optimal LLM results, a prompt should contain the following elements:


Persona/Audience: Define who the model should act as (e.g., "Act as a lawyer") or who the output is for (e.g., "for a non-technical audience").


Core Task: Clearly state the goal using action verbs (e.g., Analyze, Compare, Synthesize, Prioritize).


Context/Data: Include all relevant background information and constraints (e.g., specific figures, debt amounts, dates, or keywords).


Format/Structure: Define the output structure (e.g., "Use a 3-point bulleted list," "Write a 500-word essay," "Output as a single paragraph").


Tone/Style: Specify the desired tone (e.g., "cynical," "formal," "encouraging").

<img width="735" height="492" alt="image" src="https://github.com/user-attachments/assets/7827c1f6-4678-4039-bbb5-60401a97bb6b" />


# RESULT: 

The experiment confirms that interacting with LLMs is primarily an exercise in prompt engineering.

**Key Findings:**
Structure is King: The model performs best when it is given a clear framework rather than an open-ended question.

Constraints are Beneficial: Specific constraints on length, format, tone, and required keywords channel the LLM’s power to produce high-quality, targeted outputs.

The Power of Persona: Asking the model to "Act as a..." (Persona) instantly sets the tone and knowledge domain for the response, significantly improving quality.
