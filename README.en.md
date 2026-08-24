<p align="center">
  <img src="./assets/banner.svg" alt="XXD Panel 015 project banner" width="1200">
</p>

<div align="center">

# 🦁 XXD Panel 015

### Distil the photograph into minimal abstract memory and a complete editorial system

[![Codex Skill](https://img.shields.io/badge/Codex-Skill-000000?style=flat-square)](./SKILL.md)
[![Four Modes](https://img.shields.io/badge/Modes-4-d75d32?style=flat-square)](#four-outputs-one-abstract-memory-logic)
[![Raster Output](https://img.shields.io/badge/Output-PNG-3c6f67?style=flat-square)](#boundaries-and-trust)

<a href="README.md">简体中文</a> · <strong>English</strong> · <a href="README.ja.md">日本語</a> · <a href="README.ko.md">한국어</a> · <a href="README.ar.md">العربية</a>

</div>

> DECONSTRUCT–SELECT–DISTIL–RECONSTRUCT · FEW FORMS · STRICT COLOUR ROLES · IVORY SPACE · ART-BOOK MICROTYPE

XXD Panel 015 is an image-generation Skill for Codex and compatible agents. It deconstructs, selects, distils, and reconstructs a photograph, retaining only its most distinctive mass ratios, axes, curves, interlocks, layers, occlusions, negative spaces, scale differences, and asymmetry in a few geometric forms that still correspond at a glance.

Colour comes only from the source and resolves into one main colour, one dark structural colour, one light or neutral colour, and at most a small key accent. One poetic 2–5-word title carries emotion while two to four microtext groups carry order, evidence, material, and reading rhythm: geometry holds visual memory; typography builds the editorial path.

## Why it exists

“Minimal geometry” easily collapses into a generic icon, arbitrary circles and bars, even arrangement, a stock Bauhaus template, or decorative forms that could accompany any photograph.

015 reverses that logic:

```text
lock mass / axes / curves / interlocks / occlusions / negative space / asymmetry → deconstruct source structure → select the few relations essential to recognition → distil them into geometric roles → reconstruct one visual centre with strong scale hierarchy → assign main / dark structural / light-neutral colours → build a reading path with one title and two to four microtext groups
```

If an unrelated photograph could replace the source without materially changing mass ratios, axes, curves, interlocks, negative shapes, colour areas, or type path, the result is not 015.

## The 015 visual contract

- **Source structure:** at least three specific cues come from mass ratio, axis, curve, interlock, layer, occlusion, negative space, scale difference, or asymmetry.
- **Four-stage logic:** deconstruct structural facts, select essential relations, distil geometric roles, and reconstruct abstract memory instead of diagramming every detail.
- **Few forms:** use only source-earned circles, ellipses, rectangles, bars, arcs, wedges, irregular planes, or custom simple contours.
- **One visual memory:** strong scale difference, hierarchy, positive/negative form, occlusion, and generous ivory space create one centre.
- **Strict colour roles:** one main, one dark structural, one light or neutral colour, and at most a small accent; area, value, and local contrast establish hierarchy.
- **Complete type system:** one 2–5-word title plus two to four microtext groups, including deliberate scale contrast, form a reading path along axes, edges, contours, colour blocks, and negative space.
- **No-year original-prompt-generated text:** original-prompt-generated text neither invents nor uses a year; exact user wording stays verbatim even when it contains one.

## Samples · From X

> [Xiaoxiaodong (@xiaoxiaodong01)](https://x.com/xiaoxiaodong01/status/2090123569984679990) · 2026-08-19<br>
> GPT2 x 几何图形 x 留白 x 美学提示词 x VOL.015

<table>
  <tr>
    <td width="50%"><a href="https://x.com/xiaoxiaodong01/status/2090123569984679990"><img src="./assets/examples/sample-01.jpg" alt="XXD Panel 015 sample 1"></a></td>
    <td width="50%"><a href="https://x.com/xiaoxiaodong01/status/2090123569984679990"><img src="./assets/examples/sample-02.jpg" alt="XXD Panel 015 sample 2"></a></td>
  </tr>
  <tr>
    <td width="50%"><a href="https://x.com/xiaoxiaodong01/status/2090123569984679990"><img src="./assets/examples/sample-03.jpg" alt="XXD Panel 015 sample 3"></a></td>
    <td width="50%"><a href="https://x.com/xiaoxiaodong01/status/2090123569984679990"><img src="./assets/examples/sample-04.jpg" alt="XXD Panel 015 sample 4"></a></td>
  </tr>
</table>

<p align="center"><a href="https://x.com/xiaoxiaodong01/status/2090123569984679990">View the original post and full prompt →</a></p>

These samples demonstrate the 015 aesthetic motive. Their subjects, composition, palette, copy, and earlier canvas ratio never become generation references or current defaults.

## The original brief is authoritative

`references/015-source.md` is this project's sole creative and aesthetic authority. The Skill no longer summarizes or expands it, and it does not impose a shared palette, colour plan, aesthetic motive, title, or microcopy package. GPT Image 2 follows that brief's own rules for colour, material, composition, whitespace, wording, and typography.

Mode and size change only the legacy 3:4 top-bottom container. In left-right mode, the brief's upper photo and lower design map to the left and right. In design-only and wallpaper modes, the lower design language expands across the whole canvas. Every other source-brief instruction remains active.

## Four combinable output modes

Select one or more of `top-bottom`, `left-right`, `design-only`, and `wallpaper-pack`. Paired work is generated as one complete canvas by default; deterministic composition is only a fallback after a failed retry, for pixel-identical source preservation, or for lossless size calibration.

Ordinary sizes are also multi-select: auto-fit, source aspect, 1:1, 3:4, 4:3, 4:5, 5:4, 2:3, 3:2, 9:16, 16:9, 21:9, 5:7, 7:5, or custom ratios/exact pixels. There is no silent default. Every distinct aspect is independently recomposed from the same verbatim source brief.

Wallpaper packs may be linked or independent. A linked pack creates one anchor image, then recomposes each remaining device from the original source plus that anchor; it never crops one image into four sizes.

## Text modes

Before generation, resolve one of three choices:

1. **Model generates text from the original prompt**: the user supplies only the language or locale; GPT Image 2 follows the source brief's own wording, amount, tone, and typography logic.
2. **Use my exact text**: pass it verbatim, without rewriting, translating, or adding a title; typography still follows the source brief.
3. **No text**: prohibit visible text and pseudo-text.

The outer Skill no longer pre-writes titles, microcopy, or copy packages. Output language is resolved separately from the interface language and is never guessed from a person, scene, or filename.

## Complete-canvas first, raster-only delivery

The image model owns the aesthetics of the entire finished composition; paired layouts also default to one complete-canvas generation. `scripts/compose_panel.py` remains only for condition-based recovery, lossless pixel calibration, and read-only audit. It is not run pre-emptively and does not judge aesthetic success.

Every deliverable is a raster PNG and every invocation creates a fresh task under `~/Desktop/xxd/`. The configured image route exposes sanitised status only—never providers, endpoints, credentials, headers, prompts, responses, or account details. SVG, HTML, Canvas, diagrams, and programmatic drawing are not substitutes for the final artwork.

## Capability-adaptive questions and inline parameters

The same Skill adapts to the host's real interaction capabilities and never presents decorative symbols as clickable controls:

- **When Claude Code exposes `AskUserQuestion + multiSelect: true`**: modes and sizes use genuine checkboxes; text mode and wallpaper relationship use single-select. Common sizes are grouped into square, portrait, and landscape checkbox questions, selections accumulate across groups, and custom sizes use free input.
- **When Codex exposes only `request_user_input`**: use it only for mutually exclusive fields such as text mode and wallpaper relationship. Do not misrepresent modes or sizes as single-choice; collect them through clear combination input.
- **With no interactive question tool**: use two typed rounds—modes first, then sizes plus text. Never draw fake `- [ ]` boxes or ask the user to switch to Plan mode merely to obtain a form.

The second round initially shows only Smart recommendation, Source aspect, Common ratios, and Custom. Expand the full library only when requested: square `1:1`; portrait `3:4, 4:5, 2:3, 9:16, 5:7`; landscape `4:3, 5:4, 3:2, 16:9, 21:9, 7:5`. Any ratios may be combined, and exact pixels are always accepted.

All settings can also be passed inline:

```text
/xxd-panel-015 photo.jpg --mode top-bottom,design-only --size auto,3:4,9:16 --text prompt --locale ja-JP
```

Supported parameters are `--mode`, repeatable or comma-separated `--size`, `--text prompt|exact|none`, `--locale`, `--copy`, `--wallpaper linked|independent`, `--wallpaper-size`, and `--out`. Complete parameters skip preflight; partial parameters trigger only missing questions.

## Image-model priority

GPT Image 2 is the default first choice. It keeps this project's established workflow: high-fidelity source reference, explicit whole-canvas selection before generation, one complete-canvas generation for paired modes, and scripted composition only as a conditional fallback.

Seedance 5.0 Pro, Nano Banana Pro (Gemini Image Pro), Nano Banana 2 (Gemini Image Flash), or another compatible bitmap model may also be used when it is actually available through the current tools or configured routes and can satisfy source fidelity, whole-canvas ratio, target-language text, and linked-wallpaper multi-reference requirements. An alternative changes only the generation route; it must not change modes, canvas, copy, locale, wallpaper relationship, or the complete-canvas-first strategy.

If no suitable route is available, the Skill asks the user to enable an image-generation tool or provide an API key. User-provided credentials may be used for the current task without being echoed, displayed, logged, or exposed. They are not persisted, and provider, account, billing, or global route configuration is not modified, unless the user explicitly requests that configuration change.

## Get started

```bash
git clone https://github.com/nevertoday/xxd-panel-015.git
mkdir -p ~/.codex/skills
ln -s "$(pwd)/xxd-panel-015" ~/.codex/skills/xxd-panel-015
```

Claude Code users may link the same directory to `~/.claude/skills/xxd-panel-015`. Restart the agent session after installation.

```text
$xxd-panel-015
Turn this photograph into a left-right composition. Derive the copy from the image and write it in natural Korean.
```

You may invoke the Skill with only a photograph. It first asks for one or more modes in a numbered multiline menu, then for copy settings; wallpaper mode also asks for linked/independent continuity and device sizes.

Full specifications:

- [Skill workflow](SKILL.md)
- [Chinese runtime adapter](references/xxd-panel-015-prompt.zh-CN.md)
- [English runtime adapter](references/xxd-panel-015-prompt.en.md)
- [Original style brief](references/015-source.md)

## Boundaries and trust

- Each photograph stays within its own task and never borrows subjects, colours, copy, or composition from other inputs, old results, or samples.
- Every invocation creates a fresh task directory; even identical sources and parameters must generate anew.
- Deliverables are PNG bitmaps, never SVG, HTML, Canvas, or programmatic-drawing substitutes.
- The configured bitmap bridge emits sanitised status only and does not expose providers, endpoints, headers, credentials, prompts, or response bodies.
- Each selected ordinary mode returns one file; selected `wallpaper-pack` adds four separate wallpapers. `all` returns seven PNGs per source across four sibling mode directories, never a contact sheet or overview.

Local composition needs Python 3 and Pillow. The safe bitmap bridge uses Python 3.11+ `tomllib`. Image generation still requires a host agent with built-in raster generation or an already configured compatible raster route.

## Repository

```text
xxd-panel-015/
├── SKILL.md
├── README.md / README.en.md / README.ja.md / README.ko.md / README.ar.md
├── agents/openai.yaml
├── assets/
│   ├── banner.svg
│   └── examples/ (reserved for future local samples)
├── scripts/
│   ├── compose_panel.py
│   └── configured_imagegen.py
└── references/
    ├── xxd-panel-015-prompt.zh-CN.md
    ├── xxd-panel-015-prompt.en.md
    └── 015-source.md
```

## About XXD

XXD is the abbreviated brand name of Xiaoxiaodong. This project is created and maintained by [@xiaoxiaodong01](https://x.com/xiaoxiaodong01).

## Support and Membership

### In-depth Consultation · CNY 299/hour

One-to-one consultation for using the Skills is billed at CNY 299 per hour. Contact Xiaoxiaodong through the WeChat QR code below to book.

### Xiaoxiaodong Skills User Community · CNY 99 to join

A one-time CNY 99 fee joins the community for workflow sharing, work discussion, and peer support. It does not include hourly one-to-one consultation. Include “Skills User Community” in your WeChat message.

### Knowledge Planet + Member Prompt Library · CNY 699/year

[Knowledge Planet](https://wx.zsxq.com/group/15554814142882) and the [XXD Member Prompt Library](https://vip.xiaoxiaodong.ai/) are one membership: **one annual payment unlocks both, with no second purchase required.**

1. Subscribe through [Knowledge Planet](https://wx.zsxq.com/group/15554814142882), then contact Xiaoxiaodong on WeChat for a Prompt Library redemption code.
2. Subscribe through the [Member Prompt Library](https://vip.xiaoxiaodong.ai/), then contact Xiaoxiaodong on WeChat for a Knowledge Planet invitation.

<p align="center">
  <a href="https://xiaoxiaodong.pages.dev/assets/wechat-qr.png"><img src="https://xiaoxiaodong.pages.dev/assets/wechat-qr.png" alt="XXD paid community WeChat QR code" width="320"></a>
</p>

<div align="center">

**Abstraction is not deleting the photograph; it is preserving the relation that cannot be replaced.**

</div>

---

<div align="center">
  <h2>☕ Support this open-source project</h2>
  <p>If this project saved you time, a Star, a share, or a coffee helps keep it moving.</p>
  <table>
    <tr>
      <td align="center" width="240">
        <a href="https://github.com/nevertoday/zhongguo-traditional-colors/blob/main/docs/images/buy-me-a-coffee-qr.png?raw=true"><img src="https://github.com/nevertoday/zhongguo-traditional-colors/blob/main/docs/images/buy-me-a-coffee-qr.png?raw=true" alt="Support Xiaoxiaodong through Buy Me a Coffee" width="180"></a><br>
        <strong>Buy me a coffee</strong><br>
        <sub>Scan or open the QR code to support Xiaoxiaodong</sub>
      </td>
    </tr>
  </table>
  <p><sub>Support is entirely optional and never changes access to this open-source project.</sub></p>
</div>
