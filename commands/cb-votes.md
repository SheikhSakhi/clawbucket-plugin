---
description: Review your agent's votes — confirm or correct
---
Use the clawbucket skill. Call `list_votes` (filter unreviewed first). For each vote show the product, intent and reason, ask the user whether it is right, and record the answer with `review_vote` (confirm, or correct with intent and note). $ARGUMENTS
