# General Meta Prompt Template

```yaml
meta_prompt_template:
  description: "<High-level goal of the meta prompt: what kind of raw data/spec you want generated, for what kind of app, on which platform, with what special capabilities.>"
  target_language: "<Primary implementation language, e.g., Python>"
  target_platform: "<Target platform or environment, e.g., Replit>"
  time_limit_minutes: <Time to build app end-to-end, e.g., 45>

  requested_sections:
    1_core_concept:
      description: "<One-paragraph imaginative description of the app’s world/use-case to inspire core concept.>"
      instruction: "<Short instruction to write a beginner-friendly, memorable sentence that summarizes the app and its special capabilities (e.g., AI-powered, predictive, visual).>"

    2_user_scenarios:
      description: "<What kind of user scenarios you want (e.g., 2–3 real-world situations that inspire features).>"
      instruction: "<Ask for a few concrete, relatable user situations tied to the theme that can drive feature ideas.>"

    3_dynamic_metrics:
      description: "<What kind of metrics/variables you want (e.g., 2 calculable, theme-based metrics with predictive/AI-enhanced functionality).>"
      instruction: |
        "<Describe the main functional features you want. 
        For example:
        - Feature A: <brief explanation>
        - Feature B: <brief explanation>
        - Feature C: <brief explanation>
        - Dashboard: <what users see/manage>
        Keep it focused on things that can be calculated, tracked, and enhanced by AI/predictions/analytics.>"

    4_creative_twist:
      description: "<One bold, theme-integrated enhancement with simple animation and visualization to elevate app appeal.>"
      instruction: |
        "<Ask for one standout feature that:
        - Includes a light animation (e.g., fade-in, pulse)
        - Ties animation behavior to a metric value
        - Uses a simple 1–2 color CSS palette
        - Includes a simple data visualization (chart/graph)
        - Acts as the app’s visual centerpiece on the frontend.>"

    5_sample_output:
      description: "<A quick example of how the app behaves with AI, predictions, and visuals.>"
      instruction: |
        "<Ask for a simple input–output example using one or more metrics, showing:
        - An AI recommendation
        - A predictive insight (e.g., for future state)
        - A visual cue (e.g., trend up/down, % change).
        Make it concrete enough to guide later implementation.>"

  output_instructions:
    - "Structure the response clearly with these five sections."
    - "Keep details vivid, actionable, and tightly aligned with the chosen theme, emphasizing AI recommendations, predictive analytics, and data visualizations."
    - "Focus on raw data and examples (metrics, scenarios, sample IO), leaving UI and deployment details to later prompts."
    - "Ensure practicality for <target_language> on <target_platform> within <time_limit_minutes> minutes—simple yet strong enough to support enhanced features."
```
