# Rule: micro:bit Context

## Purpose

Ensure micro:bit activities account for hardware, browser tools, classroom management, sensors, data and beginner programming constraints.

## Applies To

- micro:bit programming tasks
- MakeCode and Python editor activities
- robotics and sensor lessons
- data-logging tasks
- classroom setup instructions
- troubleshooting and teacher notes

## Rule Statement

The agent must treat micro:bit tasks as physical computing activities that require both code and hardware workflow checks.

## Requirements

- State required hardware, such as micro:bit board, USB cable, battery pack, batteries, sensors or accessories.
- Identify the programming environment: MakeCode blocks, MakeCode JavaScript/Python, micro:bit Python editor or micro:bit classroom.
- Use simulator-first instructions where this reduces setup friction.
- Include transfer steps only when the task requires code on the physical device.
- Account for browser, USB, Bluetooth, file download and school-device restrictions.
- Do not assume student accounts are required; micro:bit classroom can support class sessions without accounts.
- Warn when sharing code to students may overwrite their existing code.
- Include safety notes for batteries, cables, moving parts, LEDs, sound and classroom movement when relevant.
- Separate code debugging from hardware troubleshooting.
- Preserve local or offline fallback options when internet or device access is uncertain.

## Decision Logic

If the activity can be tested in the simulator first, do that before physical transfer. If the learning goal is sensors, robotics or data logging, include hardware and collection checks. If the user has not supplied device access details, state assumptions and provide a no-hardware or simulator alternative.

## Examples

- A MakeCode activity starts in the simulator, then transfers to the board after the button input works.
- A sensor task lists what students should observe before collecting data.
- A troubleshooting note separates "code runs in simulator" from "code does not transfer to board".

## Non-Examples

- Assuming every student has a board and USB data cable.
- Requiring Bluetooth pairing without a fallback.
- Sending teacher code to students without warning that it may overwrite their work.
- Treating a wiring or battery issue as a code error.
- Ignoring safety when motors, servos or external power are involved.

## Interaction With Skills

- `skills/Electronics/SKILL_MICROBIT_PROGRAMMING.md`
- `skills/Electronics/SKILL_SENSOR_SYSTEMS.md`
- `rules/Digital technologies/RULE_BEGINNER_PROGRAMMING.md`
- `rules/Digital technologies/RULE_DEVICE_CONSTRAINTS.md`
- `rules/Digital technologies/RULE_DEBUGGING_EXPLANATION.md`
- `rules/Science/RULE_PRACTICAL_SAFETY.md`

## Quality Check

- Are hardware and editor requirements explicit?
- Is there a simulator or no-hardware fallback where useful?
- Are transfer, saving and class-session limits clear?
- Are safety and supervision needs included?
- Are code and hardware faults separated?
- Is the activity realistic for school-managed devices?

## Sources

- micro:bit classroom - Micro:bit Educational Foundation - https://microbit.org/get-started/user-guide/microbit-classroom/ - Accessed 2026-05-17
- Technologies - Australian Curriculum, Assessment and Reporting Authority - https://www.australiancurriculum.edu.au/curriculum-information/understand-this-learning-area/technologies - Accessed 2026-05-17
