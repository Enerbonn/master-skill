# Master Skill

Master Skill is a Codex skill for learning through real work. Choose what you want to be able to do yourself. Codex asks for a prediction or attempt, gives a clue or explanation when you get stuck, and checks your reasoning with a changed case. You can delegate setup, documentation lookup, and boilerplate while keeping the part you want to learn.

## Install

Clone or download this repository. For a project install, copy `SKILL.md` and the `agents/` directory into `.agents/skills/master-skill/` in that project. For a personal install, put the same files in `~/.agents/skills/master-skill/`. Open Codex in the project and invoke `$master-skill`.

## Use

> Use $master-skill to help me understand why my workflow creates duplicate records. Let me predict what happens and design a test. Give me a hint if I get stuck.

To resume a session, name the topic and point to your progress notes if Codex doesn't already have them. The skill can read available workspace notes to find your latest attempt and pick a next exercise.

> Use $master-skill to resume my linked-list practice from my study notes. Start with the gap I still need to check.

Created by Irvin John J. Parulan. The guided practice approach draws on [Learning Mode](https://github.com/melsayedx/learning-mode) by Muhammad El Sayed. Master Skill's public package is self-contained and includes its own instructions.

[MIT License](LICENSE)
