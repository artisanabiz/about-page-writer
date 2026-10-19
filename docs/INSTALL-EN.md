# Installation and first use

About Page Writer v0.7.5; instructions checked against official documentation on 19 October 2026. They describe installation paths, not a completed compatibility test. Review the files before enabling a skill.

## Claude

Enable code execution/file creation if required by your account. Open Customize → Skills → + → Create skill → Upload a skill, select the ZIP containing the `about-page-writer/` folder and enable it. [Official instructions](https://support.claude.com/en/articles/12512180-use-skills-in-claude).

## Claude Code

Copy the whole folder to `~/.claude/skills/about-page-writer/`. Start a local session and invoke `/about-page-writer`. This local folder is not the same as a cloud/Cowork installation. [Official instructions](https://code.claude.com/docs/en/skills).

## Codex

Extract the ZIP. Copy the complete `about-page-writer/` folder into `.agents/skills/` inside your chosen project, or `~/.agents/skills/` for your user. Keep references and assets together. Select `$about-page-writer`; restart Codex if it is missing. [Official instructions](https://learn.chatgpt.com/docs/build-skills).

## ChatGPT

Standalone skills are supported in the desktop app; plugin and workspace distribution are separate. Check Skills in your app and its available installation controls. This folder is not a published plugin or a universal web-chat ZIP installer. [Official instructions](https://learn.chatgpt.com/docs/build-skills).

## First use

This skill asks questions before completing the page. Your answers supply information that public sources cannot establish, such as team experience and commercial process. You may defer or decline an answer; the result will then remain a partial draft, with the missing items in “Irina’s recommendations”. You can complete those items later with your website editor.


Enable browsing, then ask: “Use About Page Writer to improve my About page. Website: [your public URL]. Readers: [intended audience]. Next action: [what readers should do].” If browsing is unavailable, supply approved text and expect a limited review. Check the resulting facts, permissions and claims before publication. Installation alone does not demonstrate output quality.
