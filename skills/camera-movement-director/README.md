# Camera Movement Director

Reusable scene-planning skill for live action, animation, and AI video.

## Workflow placement

Story beat and rough blocking → camera movement pass → storyboard / shot list / animatic / video prompt → continuity and feasibility review.

Invoke explicitly with `$camera-movement-director`, or allow an agent supporting implicit skill invocation to select it from its description. Metadata expresses the intended trigger; it cannot guarantee invocation in a host that does not load the skill or support implicit invocation.

## Installation

Place the complete `camera-movement-director` directory inside the destination library's supported skills directory. Preserve `SKILL.md` and `agents/openai.yaml`. Follow that library's registration/indexing conventions. Reload skills if the host requires it, then confirm that the skill is listed.

## Suggested checks after installation

- “Design a 15-second suspense scene with three shots.” Should apply after intent/blocking, integrate camera directions, and use durations consistent with the runtime.
- “Change the actor's route to the doorway.” Should revisit affected camera paths and continuity.
- “Write a six-second AI video prompt.” Should specify a clear camera path separately from subject action without unsupported platform controls.
- “Edit this business email.” Should not trigger.

## Classification and attribution

Created skill: an original workflow developed with AI assistance, informed by external references. It is distinct from saved-for-later resources in the repository’s references directory. See SKILL.md for source attribution and access limitations. The repository license applies to this original package, not to external linked sources.

Publishing this package makes it shareable; account-level installation remains a separate step.
