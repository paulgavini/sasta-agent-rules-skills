# Rule: GameMaker Context

## Purpose

Ensure GameMaker resources match the GameMaker IDE, project structure and beginner game-development workflow.

## Applies To

- GameMaker tutorials
- GML code examples
- object, room and sprite tasks
- game prototyping activities
- debugging guides
- teacher notes and assessment scaffolds

## Rule Statement

The agent must treat GameMaker as a game-development environment with assets, objects, events, rooms and either GML Code or GML Visual, not as a generic programming language alone.

## Requirements

- Use GameMaker terms accurately, including project, asset browser, workspace, sprite, object, instance, room, event and output window.
- Clarify whether the task uses GML Code or GML Visual.
- Keep beginner tasks focused on one playable mechanic before adding menus, polish or complex systems.
- Explain which object and event owns each code snippet.
- Separate asset setup from code setup.
- Include test steps using the run/build workflow.
- Do not assume the same licensing, export targets or installed SDKs are available on school devices.
- Avoid advanced systems, data structures or object hierarchies unless requested.
- Use small prototypes and incremental changes before full games.
- Preserve GML syntax in fenced code blocks.

## Decision Logic

If students are beginners, start with a room, one player object, one visible goal and one interaction. If the task asks for code, specify the object and event before the snippet. If the task involves export, publishing or platform builds, check licensing, account and SDK requirements first.

## Examples

- "Add this code to the Step event of `obj_player`" before giving movement code.
- A prototype task starts with a room, player sprite, coin object and score variable.
- A debugging task checks the Output window before changing project structure.

## Non-Examples

- Giving GML code without saying which event it belongs in.
- Starting a beginner class with save systems, cameras and inventory management.
- Assuming students can install SDKs or export to every platform.
- Treating sprites and objects as the same thing.
- Rewriting a whole project when one event is misplaced.

## Interaction With Skills

- `skills/Digital Technologies/SKILL_GAMEMAKER_GML.md`
- `rules/Digital technologies/RULE_BEGINNER_PROGRAMMING.md`
- `rules/Digital technologies/RULE_CODE_CLARITY.md`
- `rules/Digital technologies/RULE_DEBUGGING_EXPLANATION.md`
- `rules/Digital technologies/RULE_DEVICE_CONSTRAINTS.md`

## Quality Check

- Are GameMaker terms used correctly?
- Is the object and event context clear for every code snippet?
- Is the task prototype-sized before extension?
- Are licensing, installation and export assumptions avoided?
- Are testing and debugging steps included?
- Is code copyable and GML-specific?

## Sources

- GameMaker Manual Index - GameMaker - https://manual.gamemaker.io/lts/en/Content.htm - Accessed 2026-05-17
- Workspaces - GameMaker Manual - https://manual.gamemaker.io/lts/en/Introduction/Workspaces.htm - Accessed 2026-05-17
