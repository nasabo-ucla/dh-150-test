---
title: "Sample: sentiment analysis of a plaque"
task_type: "Sentiment analysis"
artifact: "Sample entry for Frankenstein (all numbers below are invented for demonstration)"
tool: "Name of the tool and its version, for example VADER or a specific chatbot model"
prompt_settings: "Write the exact prompt or settings you used so someone else could repeat the test."
manual_approach: "Two team members each labeled 20 sentences from the plaque as positive, negative, or neutral, then talked through every disagreement."
manual_result: "The two human labelers agreed on 17 of 20 sentences (85 percent)."
ai_result: "The tool matched the reconciled human labels on 13 of 20 sentences (65 percent)."
metric: "Percent agreement with the reconciled human labels."
norm: "Human-to-human agreement (85 percent here) is used as the ceiling. A tool close to that level would count as reliable for this task. Say where your norm comes from."
guardrails: "- Asked the model to label each sentence separately instead of the whole text.\n- Required one of three allowed labels so answers could be counted.\n- Spot-checked every sentence it labeled negative."
verdict: "Ready with guardrails"
---

*This is a sample showing the shape of a good analysis. The numbers are invented. Replace everything.*

Write the qualitative half of the comparison here. Where did the tool and the humans disagree, and why? Did the tool miss irony, period language, or context that a reader would catch? Which errors would matter for an archive, such as a catalog record that confidently mislabels a source, and which would not? End by explaining your verdict: given what you saw, would you trust this tool in an archive, and under what conditions?
