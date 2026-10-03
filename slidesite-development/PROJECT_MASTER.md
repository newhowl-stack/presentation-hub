# SlideSite — Project Master

_Last updated: 3 October 2026_

## Purpose
Canonical living status document for SlideSite / SLS. Structure: **Stages → Steps → Thread References → Living Stage Summary**.

## Cross-runtime source-of-truth rule
GitHub is the cross-runtime canonical checkpoint. ChatGPT Project context remains the fast working environment.

**SYNC SAFETY — mandatory:** “Sync” means reconcile to the newest authoritative state; it never means blindly copy GitHub over a working file. Before replacing canonical material, compare the GitHub version with the current working version and preserve the newer/current work. Never pull an older GitHub file over a newer working copy. Once a material change is finalized, write the resulting current version back to GitHub so other runtimes can use it.

Do not fetch or reread GitHub on every conversational turn. Use GitHub at material checkpoints, when cross-runtime freshness matters, or before handing work to another runtime such as Codex.

## Project Status at a Glance
| Stage | Status | Summary |
|---|---|---|
| **BUILD** | Well advanced / active | Core SLS format/editor exist; productizing, refining, testing and hardening the canonical standalone build. |
| **SHOW** | ~80% complete / active | Lovable site substantially generated; refinement, integration, QA and launch polish remain. |
| **SHARE** | Planned / early groundwork | SlideSite+ concept defined; substantial hosted implementation remains. |
| **LAUNCH** | Strategy developed / execution early | Distribution/adoption strategy exists; public execution is early. |

## BUILD
Goal: canonical standalone SLS format/editor: portable, editable, safe HTML presentations useful without SlideSite.

Steps: SLS format & architecture 95%; core standalone editor 90%; Quiet Studio UX 80%; fonts/Slide Styles/advanced UX 70%; live-browser testing/hardening/canonical release 60%.

Current workflow: **Edit → commit/push GitHub → auto-deploy → stable URL → browser-test.** Use presentation-hub for live HTML testing.

Next: finish UX integration; verify fonts/font preview; browser acceptance testing; resolve experimental vs canonical; declare canonical SLS build.

## SHOW
Goal: explain SLS promise. **Use SLS when generating presentations with AI so the result is editable and standalone. Use SlideSite when you want to share and collaborate.**

Positioning 100%; brand 95%; website architecture/content 95%; Lovable implementation advanced; QA/integrations in progress. Owner estimate: ~80% overall.

Next: refine Lovable pages; ensure correct logo/wordmark/fonts/colors/gradients/example slides; tighten copy; connect Skill/download/converter/demo; responsive QA; launch polish.

## SHARE
Goal: SlideSite+ hosted layer for persistent, shareable, collaborative SLS.

Product/user journey 75%; hosting/accounts/persistence 10%; stable URLs/permissions 5%; comments/review/version history 5%; real-time collaboration 0%.

Next thin loop: **Open/create SLS → persist → reopen → stable shareable URL**, then permissions, comments, history, collaboration, workspaces.

## LAUNCH
Goal: adoption of SLS as an open presentation format for AI-generated presentations, then SlideSite/SlideSite+.

Strategy 70%; public spec/Skill/GitHub distribution 30%; demo/proof assets 25%; social/community rollout 5%; broader LLM/ecosystem campaign 0%.

Next: publish spec/Skill; canonical public distribution; finish site/demos; proof content; community rollout; ecosystem adoption; SlideSite+ launch when hosted layer is ready.

## Maintenance
Update this file for material decisions, completion, reversals, committed future actions, scope/priorities/sequencing, blockers, and percentages. Keep it concise as a fast re-entry map.

When asked **“Project Master: catch me up”**, summarize overall state, stages/completion, recent changes, blockers/unresolved decisions, decided next actions, and relevant source threads/files.
