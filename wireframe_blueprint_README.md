# Wireframe Builder GPT Assets

This folder provides everything needed to use the Wireframe Builder GPT template inside a project, distribute it to collaborators, and document privacy expectations.

## Files
- `wireframe_blueprint_v1.1.md` - reusable blueprint template that guides product, design, and engineering alignment.
- `wireframe_builder_privacy_policy.md` - privacy policy drafted for the Wireframe Builder GPT experience.

## How to Use the Blueprint
1. Copy `wireframe_blueprint_v1.1.md` into your project (for example under `/templates/`).
2. Search for every bracketed token such as `[AppName]`, `[Feature]`, and `[Service]` and replace them with project-specific values.
3. Update the `_Version_` line with your release tag and the current date.
4. Track edits with comment tags like `<!--SECTION:-->` or `<!--TASK:-->` so AI agents and teammates can follow the context.

## Collaboration Tips
- Commit the template alongside any overlays or brand-specific notes so updates remain synchronized.
- When working with AI agents, keep acceptance criteria and metrics up to date to avoid drift between product and implementation workstreams.

## Privacy Notice
Share the `wireframe_builder_privacy_policy.md` file with anyone consuming the GPT integration so they understand data handling and opt-in choices.
