# yanyan

AI product manager in Hangzhou. I design agent products and ship them end to end, from the PRD to working software, with Claude Code and Codex.

I care about useful developer tools, local-first agents, and the small details that make software behave correctly.

[Open source](#open-source) · [Projects](#projects) · [Now](#now) · [Contact](#contact)

---

## Open source

Small, well-tested fixes merged upstream. Each one starts from a real reproduction.

| Project | What changed | PR |
| --- | --- | --- |
| [mruby](https://github.com/mruby/mruby) | `unpack("m")` keeps the last bytes of base64 input that has no `=` padding | [#7849](https://github.com/mruby/mruby/pull/7849) |
| [mruby](https://github.com/mruby/mruby) | `String#to_f` and `Float()` parse numbers longer than 80 bytes instead of returning `Infinity` | [#7847](https://github.com/mruby/mruby/pull/7847) |
| [Effect](https://github.com/Effect-TS/effect) | String case helpers keep Unicode letters, combining marks, and digits | [#10638](https://github.com/Effect-TS/effect/pull/10638) |
| [HeyForm](https://github.com/heyform/heyform) | Saved dates restore with the field's own date format | [#406](https://github.com/heyform/heyform/pull/406) |
| [HeyForm](https://github.com/heyform/heyform) | Reports no longer count skipped optional answers as zero | [#401](https://github.com/heyform/heyform/pull/401) |
| [HeyForm](https://github.com/heyform/heyform) | Date conditions in logic respect the field's date format | [#393](https://github.com/heyform/heyform/pull/393) |
| [HeyForm](https://github.com/heyform/heyform) | Selects stay readable in dark mode | [#380](https://github.com/heyform/heyform/pull/380) · [#391](https://github.com/heyform/heyform/pull/391) |

[All my pull requests →](https://github.com/pulls?q=is%3Apr+author%3Ayuyongyan29-dev)

## Projects

**[claude-pet](https://github.com/yuyongyan29-dev/claude-pet)**: Clawd, a pixel pet that lives above your Claude Code prompt.  
<sub>TypeScript · Claude Code plugin</sub>

**[agent-town](https://github.com/yuyongyan29-dev/agent-town)**: your local AI coding agents, drawn as a living 3D miniature town.  
<sub>JavaScript · Visualization</sub>

**[Bree](https://github.com/yuyongyan29-dev/Bree)**: a macOS memory inspector with a keyboard-driven TUI that labels AI and developer tools.  
<sub>Rust · macOS · Developer tooling</sub>

**[jd-radar](https://github.com/yuyongyan29-dev/jd-radar)**: a local job-decision agent for Chinese job seekers. It turns job descriptions into decision cards, flags red flags, and drafts follow-up questions.  
<sub>Python · AI agents</sub>

**[ai-agent-roadmap](https://github.com/yuyongyan29-dev/ai-agent-roadmap)**: a 37-week path from zero to production AI agent engineering, with runnable code at every step.  
<sub>Python · Learning path</sub>

## Now

Building AI-enabled products and internal business systems at cenbo:

- AI assistants for enterprise operations and employee self-service
- Retail growth tools for campaign planning and AI-assisted content
- Mobile campaign execution, progress tracking, and reporting for store teams

Company projects are private.

## Contact

[yuyongyan29@gmail.com](mailto:yuyongyan29@gmail.com) · [X @wei_yan77180](https://x.com/wei_yan77180)

Open to AI PM and agent roles.
