# clip

A Claude Code skill that copies a draft to the macOS clipboard, ready to paste.

## Why I use it

Claude writes in Markdown and wraps lines, and emails and web forms need neither. I type `/clip` after a draft, and the skill strips the Markdown and the line breaks inside paragraphs. I paste the result into a text editor (Sublime Text) for a final check, and only then paste it where it belongs.

## Install

Copy this folder to `~/.claude/skills/clip/`. It needs macOS, because it uses `pbcopy`.

I shared it as my prompt for the AI Retreat prompt library (2026-10-08).
