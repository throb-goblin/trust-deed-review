# Trust Minute No-Action Review

This repository contains the knowledge and instruction assets for a no-action Custom GPT that reviews Australian trust deeds and company reports, extracts clause-backed trust facts, and prepares a Markdown trust review checklist for practitioner review.

It does not call external endpoints and does not generate final Word minute templates. Matter-specific trust deeds and company reports should be uploaded only in the relevant GPT chat, not committed to this repository or uploaded as GPT Knowledge.

## Files

- `gpt/no_action_trust_review_instructions.md`: Custom GPT instructions.
- `gpt/no_action_knowledge_manifest.md`: Setup checklist for GPT Knowledge.
- `gpt/no_action_conversation_starters.md`: Optional conversation starters.
- `gpt/field_dictionary.md`: Canonical fields and drafting guardrails.
- `Trust Review Checklist.csv`: Clean checklist row list.
- `templates/fieldmaps/checklist_helper_map.json`: Private helper and mapping context.

## GPT Setup

1. Create a Custom GPT with no Actions.
2. Paste `gpt/no_action_trust_review_instructions.md` into the Instructions field.
3. Upload the Knowledge files listed in `gpt/no_action_knowledge_manifest.md`.
4. Enable file upload/data analysis if available.
5. Ask users to upload matter-specific trust deeds and company reports inside the chat only.

## Scope

The GPT prepares extraction summaries, unresolved issue lists and Markdown checklists. It is a drafting aid for review by an Australian legal practitioner and is not legal advice.
