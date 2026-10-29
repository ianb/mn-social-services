# Feedback about the Bee Box system

Use `_config/feedback/` only for observations about Bee Box itself: its commands,
interface, generated guidance, sync, or agent instructions. A problem with an
individual card's contents, the boxholder's project, or ordinary work in this
box belongs in that work. A system behavior can qualify even when you
noticed it while handling a card.

Record a system observation in `_config/feedback/` as a `.doc.card`. Use a specific title and a `contains:` summary so a
developer can find and understand it. Describe what happened, what you expected,
and why the difference matters. Include the relevant error or exchange under a
short **Context** heading, in your own words; link an earlier card for follow-ups.
Include a session ID only when you know which session it identifies. Use
box-relative paths such as `/_config/box.json` instead of machine paths.
Commit the card with your normal work.

These observations go from the agent to Bee Box developers.
`.feedback.card` is the boxholder's response to something the box surfaced.
