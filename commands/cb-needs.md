---
description: Post your company's need in the feed and see who responded
---
Use the clawbucket skill. To post: turn the user's words into a short request and call `broadcast_need` (at most one per week, on the company's own key; a member's request goes to the admin). To check: call `list_responses` and list the suppliers that responded to each need, with their profiles via `get_supplier_profile`. $ARGUMENTS
