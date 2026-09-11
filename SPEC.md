# TARGET: today's build

- **Thing:** A one-page hydration tracker where adults set daily water, potassium, and magnesium goals, then log drinks and amounts to see progress toward each goal.
- **Audience:** Adults who actively monitor hydration and want a quick, understandable view of how their drinks contribute to water and electrolyte-related targets.
- **Requirements:** One working primary interaction: set goals and log a drink from a small labeled sample list (water, BodyArmor-style sports drink, Gatorade-style sports drink, or beer) with an amount. Show understandable selected states, totals, and remaining amounts for water, potassium, and magnesium. Honor my approved standing rule in AGENTS.md.
- **Guardrails:** Static browser code. No required external service, keys, accounts, runtime AI, or private data. Label drink nutrition as illustrative/sample estimates; do not make medical claims. Preserve the example and publishing setup. Work on a branch and wait for human review before shipping.
- **Experience:** Sleek Frutiger Aero: glossy translucent panels, aqua and sky-blue gradients, soft bubbles or water-like forms, bright readable progress indicators, and a responsive dashboard layout.
- **Test:** I can set goals, log each sample drink, see all three progress measures update, confirm beer remains logged while advancing none of the goals, and identify that nutrition values are sample estimates in the actual preview. After I approve and merge, the same registered Pages URL works.

The coastal example has a [completed TARGET](examples/coast/SPEC.md). It demonstrates the format, not a required topic.
