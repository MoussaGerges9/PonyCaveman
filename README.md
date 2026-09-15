# PonyCaveman Skill 👱‍♀️🪨

A combined GitHub Copilot custom skill for VS Code that fuses two powerful developer personas: **Ponytail** (the efficient, lazy senior dev) and **Caveman** (the ultra-terse, fluff-free communicator).

## The Philosophy
Modern AI coding assistants often have two annoying habits: they write too much boilerplate, and they talk too much. **PonyCaveman** fixes both by combining:

1. **The Ponytail Logic (Code Design):** Enforces strict YAGNI (You Aren't Gonna Need It). It checks standard libraries, native features, and existing codebase utilities before writing new code. It favors deletion over addition and shortest working diffs.
2. **The Caveman Style (Communication):** Drops all pleasantries, hedging, and filler words. You get the cause, the fix, and the code. No "Sure! I'd be happy to help!" or long-winded explanations.

## Credits & Original Repositories
This skill is a direct mashup of two brilliant prompt projects. Full credit goes to their original creators:

* 👱‍♀️ **[Ponytail](https://github.com/dietrichgebert/ponytail) by dietrichgebert:** *Lazy senior dev mode. The best code is the code never written.*
* 🪨 **[Caveman](https://github.com/juliusbrussee/caveman) by JuliusBrussee:** *Talk like smart caveman. Same brain, fewer tokens.*

Please consider starring the original repositories if you find this combination useful!

## Installation (VS Code)

1. Open VS Code.
2. Open the Command Palette (`Ctrl + Shift + P` or `Cmd + Shift + P`).
3. Run **`Chat: New Instructions File`**.
4. Select **`User Data`** (Global, roams with Settings Sync).
5. Name the file `ponycaveman.prompt.md`.
6. Copy the contents of [`SKILL.md`](./SKILL.md) into this new file and save.
7. Reload VS Code (`Developer: Reload Window`).

## Usage
In your GitHub Copilot Chat, simply use the slash command:

```text
/ponycaveman Refactor this method to remove unnecessary loops.
