<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
<meta name="theme-color" content="#060914" />
<title>Cognitive Comparison Atlas | Human-centred capability map</title>
<link rel="preconnect" href="https://fonts.googleapis.com" />
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
<link href="https://fonts.googleapis.com/css2?family=Manrope:wght@400;500;600;700;800&family=Space+Grotesk:wght@400;500;600;700&display=swap" rel="stylesheet" />
<style>
:root {
  color-scheme: light dark;
  --site-primary: #8c7bff;
  --site-secondary: #39e6c0;
  --site-background: #080b19;
  --site-on-primary: #090b1b;
  --site-on-secondary: #061b19;
  --site-on-background: #eef0ff;
  --site-font-body: Manrope, ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", sans-serif;
  --site-font-heading: Manrope, ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", sans-serif;
  --site-heading-scale: 1;
  --site-spacing-scale: 1;
  --site-radius-scale: 1;
  --site-decoration-opacity: 1;
  --ink: light-dark(#151832, #eef0ff);
  --muted: light-dark(#6c728b, #929ab8);
  --surface: light-dark(#ffffff, #11152a);
  --surface-2: light-dark(#f3f5fc, #171c34);
  --line: light-dark(#dfe3f1, #2a3150);
  --canvas-bg: #080b19;
  --human: #ffcc70;
  --ai: #6debd1;
  --close: #a79bff;
}
* { box-sizing: border-box; }
html { scroll-behavior: smooth; }
body { margin: 0; font-family: var(--site-font-body); color: var(--ink); background: light-dark(color-mix(in srgb, var(--site-background) 5%, white), var(--site-background)); }
button, input { font: inherit; }
button { cursor: pointer; }
#app { min-height: 100vh; width: 100%; border-radius: 0; background-color: light-dark(color-mix(in srgb, var(--site-background) 5%, white), var(--site-background)); overflow: hidden; }
.shell { width: min(1510px, 100%); margin: 0 auto; padding: calc(26px * var(--site-spacing-scale)) clamp(16px, 3.5vw, 54px) 42px; }
.topbar { display: flex; align-items: center; justify-content: space-between; gap: 18px; padding: 5px 0 25px; border-bottom: 1px solid var(--line); }
.brand { display: flex; align-items: center; gap: 12px; min-width: 0; }
.brand-mark { width: 37px; height: 37px; position: relative; border: 1px solid color-mix(in srgb, var(--site-primary) 70%, transparent); border-radius: 50%; display: grid; place-items: center; background: color-mix(in srgb, var(--site-primary) 13%, transparent); flex: 0 0 auto; }
.brand-mark::before, .brand-mark::after { content: ""; position: absolute; border: 1px solid var(--site-secondary); border-radius: 50%; width: 23px; height: 11px; transform: rotate(-42deg); opacity: .9; }
.brand-mark::after { transform: rotate(42deg); border-color: var(--site-primary); }
.brand-mark span { width: 5px; height: 5px; border-radius: 50%; background: #fff; box-shadow: 0 0 12px var(--site-secondary); z-index: 1; }
.brand-name { font-weight: 760; letter-spacing: .14em; font-size: 12px; line-height: 1.1; }
.brand-sub { color: var(--muted); font-size: 10px; letter-spacing: .1em; margin-top: 4px; text-transform: uppercase; }
.topmeta { display: flex; align-items: center; justify-content: flex-end; gap: 10px; flex-wrap: wrap; }
.live-tag, .source-tag { border: 1px solid var(--line); color: var(--muted); padding: 8px 11px; font-size: 10px; font-weight: 650; text-transform: uppercase; letter-spacing: .12em; border-radius: 99px; white-space: nowrap; }
.live-dot { display: inline-block; width: 6px; height: 6px; background: var(--site-secondary); border-radius: 50%; margin-right: 7px; box-shadow: 0 0 9px var(--site-secondary); }
.source-tag { color: var(--site-secondary); border-color: color-mix(in srgb, var(--site-secondary) 35%, var(--line)); }
.hero { display: grid; grid-template-columns: minmax(0, 1.1fr) minmax(250px, .9fr); gap: clamp(20px, 4vw, 60px); align-items: end; padding: 42px 0 26px; }
.eyebrow { text-transform: uppercase; letter-spacing: .19em; font-size: 10px; font-weight: 760; color: var(--site-secondary); display: flex; align-items: center; gap: 9px; }
.eyebrow:before { content: ""; display: inline-block; width: 22px; height: 1px; background: currentColor; }
h1 { margin: 15px 0 13px; font-family: var(--site-font-heading); font-size: clamp(36px, 5vw, 70px); letter-spacing: -.065em; line-height: .98; font-weight: 740; max-width: 820px; }
h1 .gradient { color: var(--site-primary); background: linear-gradient(105deg, #a89cff 10%, #6debd1 95%); background-clip: text; -webkit-background-clip: text; -webkit-text-fill-color: transparent; }
.hero-copy { font-size: 14px; line-height: 1.7; max-width: 650px; color: var(--muted); margin: 0; }
.hero-note { border-left: 2px solid var(--site-primary); padding: 4px 0 4px 18px; color: var(--muted); font-size: 12px; line-height: 1.65; max-width: 410px; justify-self: end; }
.hero-note strong { color: var(--ink); font-weight: 680; }
.metrics { display: grid; grid-template-columns: repeat(4, minmax(0, 1fr)); gap: 9px; margin: 8px 0 22px; }
.metric { padding: 15px 17px 13px; background: var(--surface); border: 1px solid var(--line); border-radius: calc(12px * var(--site-radius-scale)); min-width: 0; }
.metric-label { color: var(--muted); font-size: 9px; letter-spacing: .14em; text-transform: uppercase; font-weight: 750; }
.metric-value { margin-top: 8px; font-size: clamp(23px, 3vw, 31px); letter-spacing: -.05em; font-weight: 730; line-height: 1; }
.metric-foot { margin-top: 7px; font-size: 10px; color: var(--muted); line-height: 1.4; }
.metric:nth-child(1) .metric-value { color: var(--human); }
.metric:nth-child(2) .metric-value { color: var(--ai); }
.metric:nth-child(3) .metric-value { color: var(--close); }
.explorer { display: grid; grid-template-columns: minmax(0, 1fr) 315px; gap: 12px; align-items: stretch; }
.galaxy-panel { background: var(--canvas-bg); border: 1px solid #202747; border-radius: calc(18px * var(--site-radius-scale)); overflow: hidden; position: relative; color: #edf1ff; min-width: 0; }
.galaxy-head { display: flex; justify-content: space-between; align-items: flex-start; gap: 15px; padding: 22px 24px 0; position: relative; z-index: 2; }
.galaxy-title { font-size: 13px; font-weight: 740; letter-spacing: .015em; }
.galaxy-subtitle { font-size: 10px; color: #858eaf; margin-top: 5px; line-height: 1.5; }
.mode-pill { color: #79eed8; border: 1px solid #27574e; background: #0f2528; padding: 7px 10px; text-transform: uppercase; font-size: 9px; font-weight: 740; letter-spacing: .13em; border-radius: 99px; white-space: nowrap; }
.canvas-wrap { height: clamp(330px, 46vw, 570px); min-height: 320px; position: relative; margin-top: -1px; }
#cosmos { width: 100%; height: 100%; display: block; touch-action: pan-y; cursor: grab; }
#cosmos.dragging { cursor: grabbing; }
.canvas-guide { position: absolute; left: 24px; bottom: 18px; font-size: 9px; line-height: 1.55; color: #717c9e; letter-spacing: .04em; pointer-events: none; }
.canvas-guide b { color: #d5dcf8; font-weight: 600; }
.legend { position: absolute; right: 21px; bottom: 18px; display: flex; gap: 13px; flex-wrap: wrap; justify-content: flex-end; font-size: 9px; color: #959dbb; pointer-events: none; }
.legend span { display: inline-flex; align-items: center; gap: 6px; }
.legend i { display: inline-block; width: 6px; height: 6px; border-radius: 50%; }
.legend .hum { background: var(--human); }
.legend .machine { background: var(--ai); box-shadow: 0 0 8px #6debd177; }
.legend .parity { background: var(--close); }
.sidepanel { display: flex; flex-direction: column; min-width: 0; gap: 12px; }
.inspector { background: var(--surface); border: 1px solid var(--line); border-radius: calc(18px * var(--site-radius-scale)); padding: 20px; flex: 1; }
.panel-topline { display: flex; justify-content: space-between; align-items: center; color: var(--muted); text-transform: uppercase; letter-spacing: .13em; font-size: 9px; font-weight: 760; }
.selected-index { color: var(--site-primary); }
.faculty-name { font-size: 23px; letter-spacing: -.045em; margin: 19px 0 6px; font-weight: 730; line-height: 1.1; }
.faculty-desc { color: var(--muted); font-size: 11px; line-height: 1.6; min-height: 36px; }
.status-row { margin: 17px 0 18px; display: flex; justify-content: space-between; align-items: center; gap: 10px; }
.status-chip { display: inline-flex; align-items: center; padding: 6px 9px; border-radius: 99px; font-size: 9px; font-weight: 760; letter-spacing: .07em; text-transform: uppercase; white-space: nowrap; }
.status-chip.human { color: #94610a; background: #fff2d2; }
.status-chip.ai { color: #076b5d; background: #d5fbf2; }
.status-chip.close { color: #6651bb; background: #e8e3ff; }
.gap-label { color: var(--muted); font-size: 10px; }
.compare { display: grid; gap: 13px; padding: 15px 0; border-top: 1px solid var(--line); border-bottom: 1px solid var(--line); }
.compare-line { display: grid; grid-template-columns: 62px minmax(0,1fr) 42px; align-items: center; gap: 9px; font-size: 10px; }
.compare-line .who { color: var(--muted); }
.track { height: 6px; background: light-dark(#e9ecf6, #262d49); border-radius: 99px; overflow: hidden; }
.fill { height: 100%; border-radius: 99px; transition: width .22s ease; }
.fill.human { background: var(--human); }
.fill.ai { background: var(--ai); }
.score { text-align: right; font-variant-numeric: tabular-nums; font-weight: 700; }
.model-block { padding-top: 16px; }
.small-label { color: var(--muted); text-transform: uppercase; letter-spacing: .12em; font-size: 9px; font-weight: 760; }
.model-name { font-size: 12px; font-weight: 720; line-height: 1.5; margin-top: 6px; }
.model-source { font-size: 10px; line-height: 1.55; color: var(--muted); margin-top: 4px; }
.projection-card { background: var(--surface-2); border: 1px solid var(--line); border-radius: calc(18px * var(--site-radius-scale)); padding: 19px 20px 18px; }
.projection-title { display: flex; align-items: center; justify-content: space-between; gap: 10px; font-size: 12px; font-weight: 750; }
.projection-title .spark { color: var(--site-primary); font-size: 16px; }
.projection-explain { color: var(--muted); font-size: 10px; line-height: 1.6; margin: 7px 0 13px; }
.scenario-tabs { display: grid; grid-template-columns: repeat(3, 1fr); gap: 5px; }
.scenario { border: 1px solid var(--line); background: transparent; color: var(--muted); border-radius: 8px; padding: 8px 5px; font-size: 9px; font-weight: 700; transition: .15s ease; }
.scenario[aria-pressed="true"] { border-color: var(--site-primary); color: var(--ink); background: color-mix(in srgb, var(--site-primary) 14%, transparent); }
.horizon-line { margin-top: 15px; display: flex; justify-content: space-between; font-size: 10px; gap: 10px; }
.horizon-line strong { color: var(--site-primary); font-variant-numeric: tabular-nums; }
input[type="range"] { width: 100%; accent-color: var(--site-primary); margin: 13px 0 0; cursor: pointer; }
.range-labels { display: flex; justify-content: space-between; color: var(--muted); font-size: 9px; margin-top: 3px; }
.scenario-result { border-top: 1px solid var(--line); margin-top: 15px; padding-top: 13px; }
.result-main { font-size: 13px; letter-spacing: -.015em; font-weight: 730; }
.result-sub { font-size: 10px; color: var(--muted); margin-top: 5px; line-height: 1.5; }
.impact-section { margin-top: 22px; }
.section-heading { display: flex; align-items: end; justify-content: space-between; gap: 20px; margin-bottom: 11px; }
.section-heading h2 { font-size: 17px; letter-spacing: -.03em; margin: 0; font-weight: 740; }
.section-heading p { margin: 0; color: var(--muted); font-size: 10px; text-align: right; }
.impact-grid { display: grid; grid-template-columns: repeat(3, minmax(0,1fr)); gap: 9px; }
.impact { background: var(--surface); border: 1px solid var(--line); border-radius: calc(12px * var(--site-radius-scale)); padding: 16px 17px; min-width: 0; }
.impact-kicker { color: var(--muted); font-size: 9px; letter-spacing: .13em; font-weight: 760; text-transform: uppercase; }
.impact h3 { margin: 10px 0 7px; font-size: 14px; letter-spacing: -.02em; line-height: 1.25; }
.impact p { color: var(--muted); font-size: 11px; line-height: 1.65; margin: 0; }
.impact .accent { color: var(--ai); }
.impact .human-accent { color: #ce951c; }
.data-note { margin: 20px 0 0; padding: 16px 18px; border: 1px dashed var(--line); border-radius: 11px; display: grid; grid-template-columns: 20px 1fr auto; gap: 12px; align-items: start; }
.note-icon { color: var(--site-primary); font-size: 16px; line-height: 1.2; }
.data-note p { margin: 0; color: var(--muted); font-size: 10px; line-height: 1.7; }
.data-note strong { color: var(--ink); }
.data-links { display: flex; flex-direction: column; gap: 7px; white-space: nowrap; }
a { color: var(--site-primary); text-decoration: none; font-size: 10px; font-weight: 700; }
a:hover { text-decoration: underline; }
.footer { display: flex; gap: 20px; justify-content: space-between; align-items: center; padding-top: 25px; color: var(--muted); font-size: 9px; line-height: 1.6; }
.footer-brand { letter-spacing: .13em; text-transform: uppercase; font-weight: 750; }
.tooltip { position: absolute; z-index: 5; pointer-events: none; border: 1px solid #394164; background: #12172b; color: #f3f5ff; padding: 9px 11px; font-size: 10px; border-radius: 9px; max-width: 190px; box-shadow: 0 8px 30px #0006; display: none; }
.tooltip strong { display: block; font-size: 11px; margin-bottom: 3px; }
@media (max-width: 1000px) { .explorer { grid-template-columns: minmax(0,1fr) 295px; } .hero { grid-template-columns: 1fr; gap: 18px; } .hero-note { justify-self: start; max-width: 600px; } }
@media (max-width: 760px) { .shell { padding-top: 16px; } .topbar { align-items: flex-start; } .topmeta { gap: 6px; } .live-tag, .source-tag { font-size: 8px; padding: 7px 8px; } .brand-sub { font-size: 8px; } .hero { padding-top: 32px; } .metrics { grid-template-columns: repeat(2, minmax(0,1fr)); } .explorer { grid-template-columns: 1fr; } .canvas-wrap { height: 430px; } .sidepanel { display: grid; grid-template-columns: minmax(0,1fr); } .impact-grid { grid-template-columns: 1fr; } .impact { padding: 15px 17px; } .data-note { grid-template-columns: 20px 1fr; } .data-links { grid-column: 2; flex-direction: row; flex-wrap: wrap; } .section-heading { align-items: flex-start; flex-direction: column; gap: 6px; } .section-heading p { text-align: left; } }
@media (max-width: 430px) { .topmeta { align-items: flex-end; flex-direction: column; } .hero h1 { font-size: 39px; } .canvas-wrap { height: 365px; min-height: 365px; } .galaxy-head { padding: 18px 16px 0; } .canvas-guide { left: 15px; bottom: 44px; max-width: 160px; } .legend { left: 15px; right: 15px; bottom: 15px; justify-content: flex-start; } .inspector, .projection-card { padding: 17px; } }
@media (prefers-reduced-motion: reduce) { *, *::before, *::after { scroll-behavior: auto !important; transition: none !important; } }
/* A field atlas, not a generic SaaS dashboard. */
:root {
  --site-primary: #e45e42;
  --site-secondary: #d8f45a;
  --site-background: #f3f0e5;
  --site-on-primary: #fffaf0;
  --site-on-secondary: #25251f;
  --site-on-background: #25251f;
  --ink: light-dark(#25251f, #25251f);
  --muted: light-dark(#707064, #707064);
  --surface: #faf8f0;
  --surface-2: #e9e7dc;
  --line: #d5d2c6;
  --canvas-bg: #171914;
  --human: #ffbd55;
  --ai: #d8f45a;
  --close: #d2b7f7;
}
body, #app { background: #f3f0e5; color: #25251f; }
.shell { display: flex; flex-direction: column; width: min(1680px, 100%); padding: 16px clamp(14px, 2.7vw, 42px) 32px; }
.topbar { order: 0; padding: 2px 0 13px; border-bottom: 1px solid #cfcbbd; }
.brand { gap: 10px; }
.brand-mark { width: 31px; height: 31px; border: 0; border-radius: 9px; background: var(--site-primary); }
.brand-mark::before, .brand-mark::after { display: none; }
.brand-mark span { width: 10px; height: 10px; border-radius: 2px; background: var(--site-secondary); box-shadow: none; transform: rotate(45deg); }
.brand-name { font-size: 11px; letter-spacing: .16em; color: #25251f; }
.brand-sub { font-size: 10px; letter-spacing: .015em; text-transform: none; margin-top: 4px; color: #77776b; }
.topmeta { gap: 8px; }
.source-tag { color: #55584a; border-color: #cfccbf; background: #eae7dc; border-radius: 3px; font-size: 10px; letter-spacing: .035em; text-transform: none; }
.language-toggle { border: 1px solid #25251f; background: #25251f; color: #f3f0e5; border-radius: 3px; padding: 8px 12px; font-size: 11px; font-weight: 750; }
.language-toggle:hover { background: var(--site-primary); border-color: var(--site-primary); }
.hero { display: none; }
.explorer { order: 1; display: grid; grid-template-columns: minmax(0, 1fr); gap: 0; margin-top: 13px; }
.galaxy-panel { background: var(--canvas-bg); border: 1px solid #373b2e; border-radius: 4px; }
.galaxy-head { padding: 17px 20px 14px; align-items: center; border-bottom: 1px solid #34382b; }
.galaxy-title { font-size: clamp(18px, 2vw, 27px); letter-spacing: -.055em; font-weight: 760; color: #f4f0e5; }
.galaxy-subtitle { font-size: 11px; color: #b5b7a4; letter-spacing: .005em; margin-top: 6px; }
.stage-actions { display: flex; align-items: center; justify-content: flex-end; flex-wrap: wrap; gap: 5px; }
.mode-pill { background: var(--site-secondary); border: 1px solid var(--site-secondary); color: #25251f; border-radius: 3px; font-size: 10px; letter-spacing: .035em; text-transform: none; padding: 8px 10px; }
.map-button { border: 1px solid #494d3e; background: #26291f; color: #f3f0e5; border-radius: 3px; padding: 7px 10px; font-size: 11px; line-height: 1; min-height: 30px; }
.map-button:hover { border-color: var(--site-secondary); color: var(--site-secondary); }
.map-button:focus-visible, .faculty-switcher button:focus-visible, .faculty-switcher select:focus-visible, .scenario:focus-visible, .watch-item:focus-visible, .language-toggle:focus-visible, a:focus-visible { outline: 2px solid #e45e42; outline-offset: 3px; }
.map-button.zoom { min-width: 31px; padding: 6px; font-size: 17px; }
.zoom-level { color: #d5d4c6; min-width: 39px; text-align: center; font-size: 10px; font-variant-numeric: tabular-nums; }
.canvas-wrap { height: clamp(470px, 61vw, 790px); min-height: 470px; margin-top: 0; }
#cosmos { touch-action: none; outline-offset: -5px; }
#cosmos:focus-visible { outline: 2px solid var(--site-secondary); }
.canvas-guide { left: 20px; bottom: 18px; max-width: 245px; color: #cacbbb; font-size: 10px; line-height: 1.65; letter-spacing: .005em; background: #171914d9; padding: 10px 12px; border-left: 2px solid var(--site-secondary); }
.canvas-guide b { color: var(--site-secondary); letter-spacing: .11em; font-size: 9px; }
.legend { right: 16px; bottom: 17px; gap: 12px; background: #171914d9; padding: 10px 12px; border: 1px solid #414434; color: #e0dfd2; }
.legend i { width: 8px; height: 8px; }
.legend .machine { border-radius: 1px; transform: rotate(45deg); box-shadow: none; }
.legend .parity { background: transparent; border: 2px solid var(--close); }
.legend .orbit-key { width: 12px; height: 0; border-top: 1px dashed #ffbd55; border-radius: 0; background: transparent; }
.tooltip { background: #f3f0e5; border: 1px solid #d7d4c7; border-radius: 3px; color: #25251f; box-shadow: 0 9px 25px #0003; }
.tooltip strong { color: #25251f; }
.sidepanel { display: grid; grid-template-columns: minmax(0, 1.1fr) minmax(300px, .9fr); gap: 10px; margin-top: 11px; }
.inspector, .projection-card { background: #faf8f0; border: 1px solid #d5d2c6; border-radius: 4px; padding: 18px 20px; }
.panel-topline, .small-label, .metric-label, .impact-kicker { letter-spacing: .12em; }
.faculty-name { font-size: clamp(24px, 3vw, 34px); margin: 14px 0 7px; letter-spacing: -.06em; }
.faculty-desc { font-size: 13px; line-height: 1.55; min-height: 0; max-width: 650px; }
.faculty-switcher { display: flex; align-items: center; gap: 6px; margin-top: 12px; }
.faculty-switcher select { min-width: 0; flex: 1; width: 100%; background: #f3f0e5; border: 1px solid #d5d2c6; color: #25251f; border-radius: 3px; padding: 8px 9px; font-size: 11px; }
.faculty-switcher button { border: 1px solid #d5d2c6; background: transparent; color: #25251f; border-radius: 3px; padding: 8px 10px; font-size: 11px; }
.faculty-switcher button:hover { border-color: var(--site-primary); color: var(--site-primary); }
.status-chip { border-radius: 3px; text-transform: none; letter-spacing: 0; font-size: 10px; padding: 7px 9px; }
.gap-label { font-size: 11px; }
.compare { gap: 14px; padding: 16px 0; }
.compare-line { grid-template-columns: 92px minmax(0,1fr) 43px; font-size: 11px; }
.track { height: 7px; background: #e7e4d8; }
.fill.human { background: #e9a83f; }
.fill.ai { background: #87a82f; }
.model-name { font-size: 13px; }
.model-source { font-size: 11px; line-height: 1.6; }
.projection-title { font-size: 13px; letter-spacing: .03em; }
.projection-explain { font-size: 11px; line-height: 1.6; margin: 9px 0 14px; }
.scenario-tabs { gap: 6px; }
.scenario { background: #f3f0e5; border-radius: 3px; padding: 9px 6px; font-size: 10px; }
.scenario[aria-pressed="true"] { background: var(--site-secondary); color: #25251f; border-color: #25251f; }
input[type="range"] { accent-color: var(--site-primary); }
.horizon-line { font-size: 11px; }
.horizon-line strong { color: #a6412b; }
.result-main { font-size: 14px; }
.result-sub { font-size: 11px; line-height: 1.6; }
.metrics { order: 2; grid-template-columns: repeat(4, minmax(0,1fr)); gap: 0; margin: 0; border-bottom: 1px solid #d5d2c6; }
.metric { background: transparent; border: 0; border-right: 1px solid #d5d2c6; border-radius: 0; padding: 15px 15px 13px; }
.metric:first-child { padding-left: 0; }
.metric:last-child { border-right: 0; }
.metric-value { font-size: clamp(22px, 2.4vw, 29px); margin-top: 7px; }
.metric-foot { font-size: 10px; line-height: 1.45; }
.metric:nth-child(1) .metric-value { color: #a16a17; }
.metric:nth-child(2) .metric-value { color: #5f7d19; }
.metric:nth-child(3) .metric-value { color: #8261b4; }
.impact-section { order: 3; margin-top: 30px; }
.section-heading { align-items: end; margin-bottom: 13px; }
.section-heading h2 { font-size: clamp(19px, 2.4vw, 27px); letter-spacing: -.055em; }
.section-heading p { font-size: 11px; max-width: 320px; line-height: 1.5; }
.impact-grid { grid-template-columns: repeat(3, minmax(0,1fr)); gap: 0; border-top: 1px solid #cfcbbd; border-bottom: 1px solid #cfcbbd; }
.impact { background: transparent; border: 0; border-right: 1px solid #cfcbbd; border-radius: 0; padding: 17px 20px 18px; }
.impact:first-child { padding-left: 0; }
.impact:last-child { border-right: 0; }
.impact h3 { font-size: 16px; line-height: 1.3; margin: 9px 0 7px; letter-spacing: -.03em; }
.impact p { font-size: 12px; line-height: 1.65; max-width: 460px; }
.impact .accent { color: #617a17; }
.impact .human-accent { color: #a16a17; }
.watch-section { order: 4; display: grid; grid-template-columns: minmax(190px, .72fr) minmax(0, 1.8fr); gap: 24px; align-items: start; padding: 24px 0; border-bottom: 1px solid #d5d2c6; }
.watch-intro h2 { font-size: 20px; line-height: 1.15; letter-spacing: -.05em; margin: 8px 0; }
.watch-intro p { font-size: 11px; line-height: 1.6; color: var(--muted); margin: 0; }
.watch-list { display: grid; grid-template-columns: repeat(3, minmax(0,1fr)); gap: 8px; }
.watch-item { text-align: left; min-width: 0; border: 1px solid #d5d2c6; background: #faf8f0; color: #25251f; padding: 13px; border-radius: 3px; cursor: pointer; }
.watch-item:hover, .watch-item:focus-visible { border-color: var(--site-primary); outline: none; }
.watch-name { display: block; font-size: 13px; line-height: 1.25; font-weight: 750; }
.watch-gap { display: block; margin-top: 7px; color: #77776b; font-size: 10px; line-height: 1.4; }
.watch-score { display: block; margin-top: 10px; font-size: 18px; letter-spacing: -.04em; font-weight: 760; color: #617a17; }
.data-note { order: 5; grid-template-columns: 20px minmax(0,1fr) auto; gap: 11px; margin-top: 18px; padding: 13px 14px; border: 1px solid #d5d2c6; border-radius: 3px; }
.note-icon { color: var(--site-primary); }
.data-note p { font-size: 11px; line-height: 1.65; }
.data-links { gap: 8px; }
.data-links a { color: #9a3d29; font-size: 10px; }
.footer { order: 6; border-top: 0; border-bottom: 0; padding-top: 18px; color: #77776b; }
.footer-brand { color: #25251f; }
@media (max-width: 900px) {
  .sidepanel { grid-template-columns: 1fr 1fr; }
  .watch-section { grid-template-columns: 1fr; gap: 14px; }
}
@media (max-width: 680px) {
  .shell { padding: 12px 12px 25px; }
  .topbar { align-items: center; gap: 8px; }
  .brand-name { font-size: 10px; }
  .brand-sub { font-size: 9px; }
  .topmeta { align-items: flex-end; gap: 5px; }
  .source-tag { white-space: normal; text-align: right; max-width: 130px; font-size: 9px; padding: 6px 7px; }
  .language-toggle { padding: 7px 9px; }
  .galaxy-head { align-items: flex-start; flex-direction: column; padding: 15px 14px 12px; }
  .stage-actions { justify-content: flex-start; width: 100%; }
  .canvas-wrap { height: 57vh; min-height: 390px; max-height: 570px; }
  .canvas-guide { left: 10px; bottom: 50px; max-width: 185px; padding: 7px 9px; font-size: 9px; }
  .legend { left: 10px; right: 10px; bottom: 9px; justify-content: flex-start; gap: 9px; padding: 7px 8px; font-size: 9px; }
  .sidepanel { grid-template-columns: 1fr; }
  .inspector, .projection-card { padding: 15px; }
  .metrics { grid-template-columns: repeat(2, minmax(0,1fr)); }
  .metric, .metric:first-child { padding: 12px 10px; border-right: 1px solid #d5d2c6; border-bottom: 1px solid #d5d2c6; }
  .metric:nth-child(2n) { border-right: 0; }
  .metric-value { font-size: 24px; }
  .impact-grid { grid-template-columns: 1fr; }
  .impact, .impact:first-child { border-right: 0; border-bottom: 1px solid #cfcbbd; padding: 15px 0; }
  .impact:last-child { border-bottom: 0; }
  .watch-list { grid-template-columns: 1fr; }
  .watch-item { display: grid; grid-template-columns: 1fr auto; gap: 4px 12px; align-items: center; }
  .watch-gap { margin-top: 0; }
  .watch-score { grid-column: 2; grid-row: 1 / span 2; margin: 0; }
  .data-note { grid-template-columns: 18px minmax(0,1fr); }
  .data-links { grid-column: 2; flex-direction: row; flex-wrap: wrap; white-space: normal; }
  .footer { align-items: flex-start; flex-direction: column; gap: 7px; }
}
.calibration-strip { order: 2; display: grid; grid-template-columns: 24px minmax(0,1fr) auto; align-items: center; gap: 12px; padding: 12px 0; border-bottom: 1px solid #d5d2c6; color: #5e6055; }
.calibration-mark { display: grid; place-items: center; width: 22px; height: 22px; background: #d8f45a; color: #25251f; border-radius: 50%; font-size: 12px; font-weight: 800; }
.calibration-strip p { margin: 0; font-size: 11px; line-height: 1.6; }
.calibration-strip a, .source-inline { color: #9a3d29; font-size: 10px; font-weight: 750; white-space: nowrap; }
.calibration-links { display: flex; flex-direction: column; align-items: flex-end; gap: 7px; }
.metrics { order: 3; }
.impact-section { order: 4; }
.watch-section { order: 5; }
.data-note { order: 6; }
.footer { order: 7; }
.faculty-switcher { flex-wrap: wrap; }
.faculty-switcher label { width: 100%; }
.reference-caveat { margin-top: 10px; padding: 10px 11px; background: #f0eee3; border-left: 2px solid #e45e42; color: #626257; font-size: 10px; line-height: 1.6; }
.everyday-meaning { margin-top: 12px; padding-top: 11px; border-top: 1px solid #d5d2c6; }
.everyday-meaning strong { display: block; color: #617a17; font-size: 9px; letter-spacing: .1em; text-transform: uppercase; }
.everyday-meaning p { margin: 6px 0 0; font-size: 11px; color: #55584e; line-height: 1.6; }
.source-inline { display: inline-block; margin-top: 10px; white-space: normal; }
#cosmos { touch-action: pan-y; }
.galaxy-title { font-size: clamp(19px, 2.3vw, 29px); }
.galaxy-subtitle { max-width: 620px; }
.topmeta .source-tag { background: #eae7dc; color: #55584a; }
.status-chip { max-width: 58%; white-space: normal; line-height: 1.35; }
.faculty-desc { max-width: 680px; }
@media (max-width: 680px) {
  .calibration-strip { grid-template-columns: 22px minmax(0,1fr); align-items: start; gap: 9px; }
  .calibration-strip a { grid-column: 2; white-space: normal; }
  .calibration-links { grid-column: 2; align-items: flex-start; flex-direction: row; flex-wrap: wrap; }
  .reference-caveat { font-size: 11px; }
  .everyday-meaning p { font-size: 12px; }
  .stage-actions { gap: 6px; }
  .map-button { min-height: 36px; }
}
/* Observatory-grade visual system: the galaxy is the instrument, not a card. */
:root { --canvas-bg:#111713; --site-primary:#d8f45a; --site-secondary:#ffbd55; }
body { background:#eeece3; color:#20251f; }
.shell { max-width:1600px; padding:22px clamp(14px,3vw,44px) 52px; }
.topbar { border-bottom:1px solid #d1d0c4; padding-bottom:14px; }
.brand-mark { background:#20251f; border-radius:50%; box-shadow:0 0 0 5px #20251f0c; }
.brand-mark span { background:#d8f45a; }
.brand-name { letter-spacing:.19em; font-size:11px; }
.brand-sub { color:#76796e; }
.source-tag { background:#e4e4d9; border-color:#d1d0c4; color:#555b4c; }
.hero { display:none; }
.explorer { margin-top:20px; }
.galaxy-panel { background:#111713; border:1px solid #343b31; border-radius:8px; box-shadow:0 18px 55px #1d25160e; }
.galaxy-head { padding:18px 22px; border-bottom:1px solid #30372d; }
.galaxy-title { font-size:clamp(20px,2.2vw,30px); letter-spacing:-.045em; font-weight:620; }
.galaxy-subtitle { color:#a6ad9c; font-size:11px; }
.canvas-wrap { height:clamp(520px,66vw,880px); min-height:520px; }
#cosmos { display:block; }
.canvas-guide { background:#1b211be8; border:1px solid #3b4435; border-left:2px solid #d8f45a; border-radius:5px; color:#d7dccd; max-width:250px; font-size:11px; }
.canvas-guide b { color:#d8f45a; }
.legend { background:#1b211be8; border:1px solid #3b4435; border-radius:5px; }
.map-button { background:#1d241d; border-color:#414a3c; color:#e8eadf; border-radius:5px; padding:8px 11px; }
.map-button:hover { border-color:#d8f45a; color:#d8f45a; }
.map-button.zoom { font-size:16px; }
.mode-switch { display:flex; gap:4px; align-items:center; padding:4px; background:#1a201a; border:1px solid #343d31; border-radius:6px; margin-right:6px; }
.mode-switch button { background:transparent; color:#aab09f; border:0; border-radius:4px; padding:7px 9px; font-size:10px; cursor:pointer; white-space:nowrap; }
.mode-switch button[aria-pressed="true"] { background:#d8f45a; color:#20251f; font-weight:750; }
.sidepanel { grid-template-columns:minmax(0,1.15fr) minmax(300px,.85fr); gap:12px; margin-top:14px; }
.inspector,.projection-card { border-radius:7px; border-color:#d6d5c9; padding:22px; }
.faculty-switcher select,.faculty-switcher button,.scenario { border-radius:5px; }
.impact-section { margin-top:38px; }
.impact-grid { border-color:#d4d3c7; }
.impact h3 { font-size:18px; }
.watch-item { border-radius:6px; }
.calibration-strip { border-radius:6px; }
@media (min-width:1000px) {
  .explorer { display:flex; flex-direction:column; }
  .galaxy-panel { width:100%; }
  .sidepanel { width:100%; grid-template-columns:minmax(0,1.15fr) minmax(300px,.85fr); }
}
@media (max-width:760px) {
  .mode-switch { order:-1; width:100%; margin:0 0 3px; justify-content:space-between; }
  .mode-switch button { flex:1; padding:8px 5px; }
  .canvas-wrap { height:60vh; min-height:430px; max-height:680px; }
  .galaxy-head { padding:15px; }
  .sidepanel { grid-template-columns:1fr; }
}
/* Immersive observatory: the galaxy is the environment, not a card. */
:root { color-scheme:dark; --site-primary:#9a91ff; --site-secondary:#72e9df; --site-background:#060914; --ink:#f1f4ff; --muted:#9ca8c4; --surface:rgba(12,18,36,.82); --surface-2:rgba(17,24,46,.78); --line:rgba(159,177,229,.18); --canvas-bg:#070b17; --human:#ffc17d; --ai:#72e9df; --close:#c1adff; --site-font-body:'Manrope',Manrope,ui-sans-serif,system-ui,-apple-system,BlinkMacSystemFont,'Segoe UI',sans-serif; --site-font-heading:'Space Grotesk',Manrope,ui-sans-serif,system-ui,sans-serif; }
html { background:#060914; scroll-padding-top:24px; }
body { position:relative; isolation:isolate; overflow-x:hidden; min-height:100vh; background:#060914; color:#f1f4ff; font-family:var(--site-font-body); }
body::before { content:""; position:fixed; inset:0; z-index:-2; pointer-events:none; background:radial-gradient(ellipse at 17% 18%,rgba(68,55,156,.33),transparent 35%),radial-gradient(ellipse at 83% 28%,rgba(18,113,146,.18),transparent 31%),radial-gradient(ellipse at 67% 82%,rgba(91,42,131,.21),transparent 36%),radial-gradient(ellipse at 8% 88%,rgba(20,72,115,.14),transparent 30%),radial-gradient(1px 1px at 12% 27%,rgba(236,242,255,.8) 0,transparent 1.6px),radial-gradient(1px 1px at 72% 15%,rgba(236,242,255,.66) 0,transparent 1.6px),radial-gradient(1px 1px at 43% 76%,rgba(236,242,255,.62) 0,transparent 1.6px),radial-gradient(1px 1px at 91% 69%,rgba(236,242,255,.7) 0,transparent 1.6px),linear-gradient(145deg,#050711 0%,#080d1d 48%,#060914 100%); background-size:auto,auto,auto,auto,187px 211px,239px 263px,283px 307px,331px 359px,auto; animation:deepDrift 42s ease-in-out infinite alternate; }
body::after { content:""; position:fixed; inset:0; z-index:-1; pointer-events:none; opacity:.12; background-image:radial-gradient(rgba(255,255,255,.12) .55px,transparent .65px); background-size:4px 4px; mask-image:linear-gradient(transparent,#000 18%,#000 85%,transparent); }
@keyframes deepDrift { from { background-position:0 0,0 0,0 0,0 0,0 0,0 0,0 0,0 0,0 0; } to { background-position:0 0,0 0,0 0,0 0,33px -19px,-27px 22px,19px 31px,-17px -23px,0 0; } }
#app { position:relative; isolation:isolate; background:transparent; color:#f1f4ff; min-height:100vh; }
.shell { width:100%; max-width:1920px; padding:18px clamp(16px,3.1vw,58px) 72px; }
.topbar { border-bottom:1px solid rgba(164,180,228,.16); padding:4px 0 16px; }
.brand-mark { width:35px; height:35px; background:linear-gradient(145deg,#8d82ff,#2ca9b7); border:1px solid rgba(222,228,255,.36); border-radius:11px; box-shadow:0 0 26px rgba(119,112,255,.22),inset 0 1px 0 rgba(255,255,255,.32); }
.brand-mark span { background:#f4f5ff; width:8px; height:8px; border-radius:50%; box-shadow:0 0 13px #72e9df; transform:none; }
.brand-name { color:#f3f5ff; font-size:11px; letter-spacing:.2em; }
.brand-sub { color:#9ca8c4; font-size:10px; letter-spacing:.025em; }
.source-tag { display:inline-flex; align-items:center; gap:8px; color:#bfcae3; background:rgba(17,24,46,.7); border:1px solid rgba(159,177,229,.22); border-radius:5px; padding:8px 11px; letter-spacing:.035em; }
.source-tag::before { content:""; width:6px; height:6px; display:inline-block; border-radius:50%; background:#ffbd7a; box-shadow:0 0 10px rgba(255,189,122,.52); }
.language-toggle { color:#dfe7ff; background:rgba(18,25,48,.75); border:1px solid rgba(159,177,229,.28); border-radius:5px; transition:background .18s,border-color .18s,transform .18s; }
.language-toggle:hover { color:#06101b; background:#72e9df; border-color:#72e9df; transform:translateY(-1px); }
.explorer { margin-top:18px; }
.galaxy-panel { background:rgba(4,8,19,.63); border:1px solid rgba(153,174,231,.2); border-radius:13px; box-shadow:0 28px 100px rgba(0,0,0,.22),inset 0 1px 0 rgba(255,255,255,.035); backdrop-filter:blur(14px); }
.galaxy-head { padding:20px clamp(16px,2.1vw,32px); align-items:center; gap:18px; border-bottom:1px solid rgba(150,170,228,.14); background:linear-gradient(90deg,rgba(21,28,53,.46),rgba(6,10,22,.1)); }
.galaxy-title { color:#f1f4ff; font-family:var(--site-font-heading); font-weight:600; font-size:clamp(22px,2.25vw,34px); letter-spacing:-.055em; }
.galaxy-subtitle { color:#aab6d1; font-size:11px; max-width:650px; line-height:1.65; }
.stage-actions { gap:7px; }
.mode-pill { color:#b8fcf5; background:rgba(26,84,91,.26); border-color:rgba(114,233,223,.32); border-radius:5px; font-family:'Manrope',Manrope, sans-serif; letter-spacing:.045em; font-size:9px; }
.mode-switch { background:rgba(8,13,29,.78); border-color:rgba(159,177,229,.2); border-radius:7px; padding:3px; }
.mode-switch button { color:#a4b0cb; font-family:var(--site-font-body); border-radius:5px; padding:8px 10px; transition:color .18s,background .18s,box-shadow .18s; }
.mode-switch button:hover { color:#f3f6ff; background:rgba(133,143,255,.14); }
.mode-switch button[aria-pressed="true"] { color:#07131b; background:linear-gradient(115deg,#82eee2,#a2d9ff); box-shadow:0 0 22px rgba(114,233,223,.16); }
.map-button { background:rgba(18,25,48,.8); color:#e4eaff; border-color:rgba(159,177,229,.24); border-radius:6px; min-height:34px; transition:all .18s ease; }
.map-button:hover { background:rgba(109,126,196,.18); border-color:#72e9df; color:#aaf7f0; transform:translateY(-1px); }
.map-button.zoom { font-size:18px; min-width:35px; }
.zoom-level { color:#aebadc; font-family:'Manrope',Manrope, sans-serif; font-size:10px; }
.canvas-wrap { height:clamp(560px,73svh,1020px); min-height:560px; overflow:hidden; background:#050916; }
#cosmos { touch-action:none; cursor:grab; }
.canvas-guide { left:clamp(12px,2vw,30px); bottom:clamp(12px,2vw,24px); max-width:255px; border:1px solid rgba(167,184,236,.19); border-left:2px solid #72e9df; border-radius:7px; background:rgba(7,12,28,.76); color:#c2cbe1; box-shadow:0 8px 34px rgba(0,0,0,.2); backdrop-filter:blur(10px); font-size:10px; }
.canvas-guide b { color:#9ef7ee; }
.legend { right:clamp(12px,2vw,30px); bottom:clamp(12px,2vw,24px); gap:14px; border:1px solid rgba(167,184,236,.2); border-radius:7px; background:rgba(7,12,28,.76); color:#d1daef; box-shadow:0 8px 34px rgba(0,0,0,.2); backdrop-filter:blur(10px); }
.legend .hum { background:#ffc17d; box-shadow:0 0 9px rgba(255,193,125,.4); }
.legend .machine { background:#72e9df; box-shadow:0 0 11px rgba(114,233,223,.5); }
.legend .parity { border-color:#c1adff; background:transparent; }
.legend .orbit-key { border-top-color:#ffc17d; }
.sidepanel { grid-template-columns:minmax(0,1.08fr) minmax(320px,.92fr); gap:13px; margin-top:14px; }
.inspector,.projection-card { color:#eff3ff; background:rgba(11,17,35,.79); border:1px solid rgba(159,177,229,.2); border-radius:9px; padding:clamp(18px,2.2vw,29px); box-shadow:0 15px 46px rgba(0,0,0,.13),inset 0 1px 0 rgba(255,255,255,.03); backdrop-filter:blur(15px); }
.panel-topline,.small-label,.metric-label,.impact-kicker { color:#9ca9c7; letter-spacing:.13em; }
.selected-index { color:#a7a0ff; font-family:'Manrope',Manrope, sans-serif; }
.faculty-name { font-family:var(--site-font-heading); color:#f2f5ff; font-size:clamp(27px,3.3vw,42px); letter-spacing:-.065em; }
.faculty-desc { color:#acb8d2; font-size:12px; line-height:1.7; }
.faculty-switcher select { color:#e8eeff; background:#10172d; border-color:rgba(159,177,229,.24); border-radius:6px; padding:10px 12px; }
.faculty-switcher select option { color:#edf2ff; background:#10172d; }
.faculty-switcher button { color:#d5e0fb; background:rgba(36,46,80,.44); border-color:rgba(159,177,229,.24); border-radius:6px; min-width:38px; }
.faculty-switcher button:hover { color:#72e9df; border-color:#72e9df; background:rgba(114,233,223,.08); }
.status-chip { border:1px solid transparent; border-radius:4px; font-size:10px; letter-spacing:.015em; }
.status-chip.human { color:#ffd9a7; background:rgba(149,92,35,.19); border-color:rgba(255,193,125,.25); }
.status-chip.ai { color:#a7faf1; background:rgba(25,123,121,.17); border-color:rgba(114,233,223,.25); }
.status-chip.close { color:#d7c9ff; background:rgba(121,94,191,.18); border-color:rgba(193,173,255,.25); }
.gap-label { color:#c0cae1; font-family:'Manrope',Manrope, sans-serif; font-size:10px; }
.compare { border-color:rgba(159,177,229,.16); }
.compare-line { font-family:'Manrope',Manrope, sans-serif; font-size:10px; }
.compare-line .who { color:#9ca9c7; font-family:var(--site-font-body); }
.track { background:rgba(139,156,200,.16); border-radius:99px; height:7px; }
.fill { transition:width .35s cubic-bezier(.2,.8,.2,1); }
.fill.human { background:linear-gradient(90deg,#c88a50,#ffd59c); box-shadow:0 0 12px rgba(255,193,125,.13); }
.fill.ai { background:linear-gradient(90deg,#428fbc,#72e9df); box-shadow:0 0 12px rgba(114,233,223,.13); }
.score { color:#eef3ff; }
.model-name { color:#eaf0ff; font-size:13px; }
.model-source { color:#aab7d1; font-family:'Manrope',Manrope, sans-serif; font-size:10px; }
.reference-caveat { color:#bdc9e2; background:rgba(31,40,73,.56); border-left-color:#a098ff; border-radius:0 5px 5px 0; font-size:10px; }
.everyday-meaning { border-top-color:rgba(159,177,229,.17); }
.everyday-meaning strong { color:#9ef7ee; }
.everyday-meaning p { color:#c1cbe1; font-size:11px; }
.source-inline,.data-links a,.calibration-strip a { color:#9ddff3; text-decoration:none; }
.source-inline:hover,.data-links a:hover,.calibration-strip a:hover { color:#d2fbff; text-decoration:underline; }
.projection-title { color:#eef3ff; font-family:var(--site-font-heading); font-size:14px; letter-spacing:-.02em; }
.projection-title .spark { color:#9a91ff; text-shadow:0 0 14px rgba(154,145,255,.4); }
.projection-explain,.result-sub { color:#a6b3ce; }
.scenario { color:#b9c5df; background:rgba(6,12,28,.55); border-color:rgba(159,177,229,.22); border-radius:5px; font-size:10px; padding:10px 6px; transition:all .18s; }
.scenario:hover { color:#eef4ff; border-color:#72e9df; background:rgba(114,233,223,.08); }
.scenario[aria-pressed="true"] { color:#07131b; background:linear-gradient(110deg,#84eee2,#acdfff); border-color:transparent; box-shadow:0 0 20px rgba(114,233,223,.12); }
input[type="range"] { accent-color:#72e9df; }
.horizon-line strong { color:#a9a1ff; font-family:'Manrope',Manrope, sans-serif; }
.scenario-result { border-color:rgba(159,177,229,.18); }
.result-main { color:#f0f4ff; font-family:var(--site-font-heading); font-size:16px; }
.calibration-strip { margin-top:16px; padding:16px 18px; background:rgba(16,23,45,.7); border:1px solid rgba(159,177,229,.18); border-radius:8px; color:#bdc9e2; }
.calibration-mark { background:rgba(154,145,255,.2); border:1px solid rgba(154,145,255,.38); color:#c5beff; }
.calibration-strip p { color:#aebbd5; line-height:1.75; }
.metrics { margin-top:20px; border-bottom-color:rgba(159,177,229,.17); }
.metric { border-right-color:rgba(159,177,229,.15); }
.metric-label { color:#8796b5; font-size:9px; }
.metric-value { color:#eff3ff !important; font-family:var(--site-font-heading); font-variant-numeric:tabular-nums; }
.metric:nth-child(1) .metric-value { color:#ffd09a !important; }
.metric:nth-child(2) .metric-value { color:#8df4e8 !important; }
.metric:nth-child(3) .metric-value { color:#c8baff !important; }
.metric-foot { color:#91a0bf; font-size:10px; }
.impact-section { margin-top:42px; }
.section-heading h2,.watch-intro h2 { color:#f1f4ff; font-family:var(--site-font-heading); font-size:clamp(23px,2.5vw,34px); font-weight:600; letter-spacing:-.06em; }
.section-heading p { color:#94a3c1; }
.impact-grid { border-color:rgba(159,177,229,.18); }
.impact { background:transparent; border-right-color:rgba(159,177,229,.16); }
.impact-kicker { color:#90a0c0; }
.impact h3 { color:#edf2ff; font-size:17px; font-weight:650; }
.impact p { color:#aebbd4; font-size:12px; line-height:1.8; }
.impact .accent { color:#8cf3e9; }
.impact .human-accent { color:#ffd09a; }
.watch-section { border-bottom-color:rgba(159,177,229,.18); }
.watch-intro p { color:#9eacc9; font-size:12px; line-height:1.7; }
.watch-item { color:#eaf0ff; background:rgba(14,21,42,.75); border-color:rgba(159,177,229,.19); border-radius:7px; transition:transform .2s,border-color .2s,background .2s,box-shadow .2s; }
.watch-item:hover { transform:translateY(-3px); background:rgba(29,41,75,.86); border-color:rgba(114,233,223,.55); box-shadow:0 12px 35px rgba(0,0,0,.2); }
.watch-name { color:#edf3ff; }
.watch-gap { color:#a3b0cb; }
.watch-score { color:#8df4e8; font-family:'Manrope',Manrope, sans-serif; }
.data-note { background:rgba(10,16,32,.68); border-color:rgba(159,177,229,.22); border-radius:7px; }
.data-note p { color:#a6b4ce; font-size:11px; line-height:1.8; }
.data-note strong { color:#edf3ff; }
.note-icon { color:#a39aff; }
.footer { color:#7f8eae; border-top:1px solid rgba(159,177,229,.1); }
.footer-brand { color:#dce6ff; }
.tooltip { background:rgba(8,14,31,.95); color:#edf4ff; border-color:rgba(145,174,234,.38); border-radius:7px; box-shadow:0 12px 44px rgba(0,0,0,.4); backdrop-filter:blur(16px); }
.tooltip strong { color:#a7f7ef; font-family:var(--site-font-heading); }
.tooltip span { display:block; margin-top:4px; color:#b7c4de; line-height:1.45; }
.map-button:focus-visible,.faculty-switcher button:focus-visible,.faculty-switcher select:focus-visible,.scenario:focus-visible,.watch-item:focus-visible,.language-toggle:focus-visible,a:focus-visible,.mode-switch button:focus-visible { outline:2px solid #a69dff; outline-offset:3px; }
@media (min-width:1000px) { .explorer { display:flex; flex-direction:column; } .galaxy-panel { width:100%; } .sidepanel { width:100%; grid-template-columns:minmax(0,1.08fr) minmax(320px,.92fr); } }
@media (max-width:760px) { .shell { padding:12px 12px 48px; } .topbar { padding-bottom:12px; } .brand-name { font-size:10px; } .brand-sub { font-size:9px; } .source-tag { max-width:150px; white-space:normal; line-height:1.4; font-size:9px; } .galaxy-panel { border-radius:9px; } .galaxy-head { align-items:flex-start; padding:16px 14px; } .galaxy-title { font-size:23px; } .stage-actions { justify-content:flex-start; width:100%; } .mode-switch { width:100%; order:-1; margin:0 0 4px; justify-content:stretch; } .mode-switch button { flex:1; padding:9px 3px; font-size:9px; } .canvas-wrap { height:66svh; min-height:450px; max-height:710px; } .canvas-guide { left:9px; bottom:62px; max-width:178px; padding:8px; font-size:9px; } .legend { left:9px; right:9px; bottom:9px; justify-content:flex-start; gap:9px; padding:8px; font-size:8px; } .sidepanel { grid-template-columns:1fr; } .inspector,.projection-card { padding:17px; } .metrics { grid-template-columns:repeat(2,minmax(0,1fr)); } .metric,.metric:first-child { padding:13px 10px; border-right:1px solid rgba(159,177,229,.15); border-bottom:1px solid rgba(159,177,229,.15); } .metric:nth-child(2n) { border-right:0; } .impact-grid { grid-template-columns:1fr; } .impact,.impact:first-child { border-right:0; border-bottom:1px solid rgba(159,177,229,.16); padding:16px 0; } .impact:last-child { border-bottom:0; } .watch-list { grid-template-columns:1fr; } .watch-item { display:grid; grid-template-columns:1fr auto; gap:4px 12px; } .watch-score { grid-column:2; grid-row:1/span 2; } .calibration-strip { grid-template-columns:22px minmax(0,1fr); } .calibration-links { grid-column:2; align-items:flex-start; flex-direction:row; flex-wrap:wrap; } .data-note { grid-template-columns:18px minmax(0,1fr); } .data-links { grid-column:2; flex-direction:row; flex-wrap:wrap; white-space:normal; } }
@media (max-width:420px) { .source-tag { max-width:125px; } .canvas-wrap { min-height:415px; } .canvas-guide { bottom:71px; max-width:160px; } .legend { flex-wrap:wrap; } .map-button { padding:8px; } .zoom-level { min-width:32px; } }
@media (prefers-reduced-motion:reduce) { *,*::before,*::after { animation:none !important; scroll-behavior:auto !important; transition:none !important; } body::before { animation:none !important; } }
/* New art direction: an editorial, geodesic capability instrument on warm paper. */
:root { color-scheme:light; --site-primary:#e30613; --site-secondary:#e30613; --site-background:#f7f6f2; --site-on-primary:#fff; --site-on-secondary:#fff; --site-on-background:#171717; --ink:#171717; --muted:#767676; --surface:#fff; --surface-2:#f0efeb; --line:#d8d7d1; --canvas-bg:#f7f6f2; --human:#171717; --ai:#e30613; --close:#777; --site-font-body:'Manrope',Arial,sans-serif; --site-font-heading:'Space Grotesk',Arial,sans-serif; }
html,body,#app { background:#f7f6f2 !important; color:#171717 !important; }
body { font-family:var(--site-font-body); }
body::before,body::after { display:none !important; }
.shell { width:100%; max-width:1720px; padding:14px clamp(16px,3.6vw,56px) 48px; }
.topbar { border-bottom:1px solid #d8d7d1; padding:5px 0 13px; }
.brand-mark { width:25px; height:25px; border:1px solid #171717; border-radius:50%; background:transparent; box-shadow:none; }
.brand-mark::before,.brand-mark::after { display:none; }
.brand-mark span { width:7px; height:7px; background:#e30613; border-radius:50%; box-shadow:none; transform:none; }
.brand-name { color:#171717; letter-spacing:.12em; font-size:10px; font-weight:700; }
.brand-sub { color:#777; font-family:'Manrope', sans-serif; text-transform:uppercase; font-size:9px; letter-spacing:.035em; }
.topmeta { gap:8px; }
.source-tag { background:transparent !important; border:0 !important; color:#e30613 !important; border-radius:0 !important; font-family:'Manrope', sans-serif; letter-spacing:.015em; font-size:9px; text-transform:uppercase; padding:6px 0; }
.source-tag::before { width:5px; height:5px; background:#e30613; box-shadow:none; }
.language-toggle { background:transparent; color:#171717; border:1px solid #d8d7d1; border-radius:2px; padding:7px 10px; font-family:'Manrope', sans-serif; font-size:10px; }
.language-toggle:hover { color:#fff; background:#e30613; border-color:#e30613; }
.hero { display:none !important; }
.explorer { display:block; position:relative; margin-top:0; }
.galaxy-panel { position:relative; overflow:visible; border:0; border-radius:0; background:transparent; box-shadow:none; color:#171717; backdrop-filter:none; }
.galaxy-head { position:absolute; z-index:4; top:27px; left:0; right:0; display:grid; grid-template-columns:minmax(250px, .42fr) minmax(420px,.58fr); align-items:start; gap:24px; padding:0; border:0; background:transparent; pointer-events:none; }
.galaxy-head > div:first-child { max-width:410px; pointer-events:auto; }
.galaxy-title { font-family:var(--site-font-heading); color:#171717; font-size:clamp(27px,3.3vw,49px); line-height:.98; letter-spacing:-.065em; font-weight:600; text-transform:uppercase; max-width:390px; }
.galaxy-subtitle { color:#666; font-family:'Manrope', sans-serif; font-size:10px; line-height:1.7; letter-spacing:0; max-width:360px; margin-top:14px; }
.stage-actions { justify-content:flex-end; align-items:flex-start; flex-wrap:wrap; gap:5px; pointer-events:auto; }
.mode-pill { background:transparent; color:#e30613; border:1px solid #e30613; border-radius:0; font-family:'Manrope', sans-serif; font-weight:500; font-size:9px; letter-spacing:.02em; text-transform:uppercase; padding:7px 8px; }
.mode-switch { display:flex; gap:0; padding:0; margin:0 0 0 4px; background:transparent; border:1px solid #d8d7d1; border-radius:0; }
.mode-switch button { padding:7px 8px; border-radius:0; background:transparent; color:#666; border:0; border-right:1px solid #d8d7d1; font:9px 'Manrope', sans-serif; text-transform:uppercase; letter-spacing:.02em; }
.mode-switch button:last-child { border-right:0; }
.mode-switch button:hover { color:#e30613; background:#edebe5; }
.mode-switch button[aria-pressed="true"] { background:#e30613; color:#fff; box-shadow:none; font-weight:500; }
.map-button { background:transparent; color:#171717; border:1px solid #d8d7d1; border-radius:0; font:9px 'Manrope', sans-serif; min-height:29px; padding:6px 8px; }
.map-button:hover { color:#fff; background:#e30613; border-color:#e30613; transform:none; }
.map-button.zoom { font-size:14px; min-width:28px; }
.zoom-level { color:#777; font:9px 'Manrope', sans-serif; min-width:34px; text-align:center; padding-top:8px; }
.canvas-wrap { position:relative; height:clamp(590px,68vw,820px); min-height:590px; margin-top:0; overflow:hidden; background:#f7f6f2; }
#cosmos { display:block; touch-action:none; cursor:crosshair; }
#cosmos.dragging { cursor:grabbing; }
.activity-log { position:absolute; z-index:3; top:180px; left:0; width:min(330px,34%); max-height:340px; pointer-events:auto; color:#171717; }
.activity-log-head { display:flex; justify-content:space-between; align-items:baseline; border-bottom:1px solid #171717; padding:0 0 8px; font:10px 'Manrope', sans-serif; letter-spacing:.06em; text-transform:uppercase; }
.activity-log-head span { color:#777; font-size:9px; }
.activity-entries { display:flex; flex-direction:column; padding-top:4px; }
.activity-entry { display:grid; grid-template-columns:24px minmax(0,1fr) auto; gap:7px; align-items:baseline; border:0; border-bottom:1px solid #e0dfd9; text-align:left; padding:7px 0; background:transparent; color:#777; font:9px 'Manrope', sans-serif; cursor:pointer; transition:color .16s ease,padding .16s ease; }
.activity-entry:hover { color:#171717; padding-left:3px; }
.activity-entry[aria-current="true"] { color:#171717; }
.activity-entry[aria-current="true"] .activity-num { color:#e30613; }
.activity-entry[aria-current="true"] .activity-name { font-weight:700; }
.activity-entry[aria-current="true"] .activity-gap { color:#e30613; }
.activity-num { color:#aaa; }
.activity-name { overflow:hidden; text-overflow:ellipsis; white-space:nowrap; text-transform:uppercase; }
.activity-gap { color:#171717; text-align:right; font-variant-numeric:tabular-nums; }
.activity-gap.ai-leading { color:#e30613; }
.canvas-guide { display:none; }
.legend { z-index:3; right:95px; bottom:32px; display:flex; gap:12px; background:transparent; padding:5px 0; border:0; border-radius:0; color:#666; font:9px 'Manrope', sans-serif; }
.legend span { gap:6px; }
.legend i { width:6px; height:6px; }
.legend .hum { background:#171717; }
.legend .machine { background:#626262; border-radius:0; transform:rotate(45deg); box-shadow:none; }
.legend .selected-key { width:7px; height:7px; background:#e30613; border-radius:50%; box-shadow:0 0 0 3px rgba(227,6,19,.1); }
.legend .orbit-key { border-top:1px solid #888; width:13px; height:0; border-radius:0; background:transparent; }
.journey-trigger { position:absolute; z-index:4; right:8px; bottom:19px; width:54px; height:54px; display:grid; place-items:center; border:0; border-radius:50%; color:#fff; background:#e30613; box-shadow:0 0 0 1px #e30613,0 0 0 7px rgba(227,6,19,.08); cursor:pointer; transition:transform .18s ease,box-shadow .18s ease; }
.journey-trigger:hover { transform:scale(1.06); box-shadow:0 0 0 1px #e30613,0 0 0 10px rgba(227,6,19,.1); }
.journey-trigger:active { transform:scale(.96); }
.journey-trigger svg { width:18px; height:18px; }
.journey-trigger .journey-hint { position:absolute; right:0; bottom:66px; width:max-content; max-width:180px; padding:8px 10px; color:#171717; background:#fff; border:1px solid #d8d7d1; font:9px 'Manrope', sans-serif; opacity:0; transform:translateY(4px); pointer-events:none; transition:opacity .16s,transform .16s; }
.journey-trigger:hover .journey-hint,.journey-trigger:focus-visible .journey-hint { opacity:1; transform:translateY(0); }
.sidepanel { display:grid; grid-template-columns:minmax(0,1.1fr) minmax(300px,.9fr); gap:16px; margin-top:0; }
.inspector,.projection-card { background:transparent; border:0; border-top:1px solid #171717; border-bottom:1px solid #d8d7d1; border-radius:0; box-shadow:none; padding:18px 0 20px; backdrop-filter:none; color:#171717; }
.panel-topline,.small-label,.metric-label,.impact-kicker { color:#777; letter-spacing:.06em; font:9px 'Manrope', sans-serif; }
.selected-index { color:#e30613; }
.faculty-name { color:#171717; font-family:var(--site-font-heading); font-size:clamp(28px,3vw,39px); letter-spacing:-.06em; font-weight:600; margin:17px 0 7px; }
.faculty-desc { color:#666; font-size:12px; line-height:1.65; }
.faculty-switcher select,.faculty-switcher button { background:transparent; color:#171717; border:1px solid #d8d7d1; border-radius:0; }
.faculty-switcher select { font:10px 'Manrope', sans-serif; }
.faculty-switcher button:hover { color:#fff; background:#e30613; border-color:#e30613; }
.status-chip { border-radius:0; text-transform:uppercase; letter-spacing:.035em; font:9px 'Manrope', sans-serif; border:1px solid #d8d7d1; }
.status-chip.human { color:#171717; background:#ecebe6; border-color:#d8d7d1; }
.status-chip.ai { color:#fff; background:#e30613; border-color:#e30613; }
.status-chip.close { color:#171717; background:transparent; border-color:#777; }
.gap-label { color:#777; font:9px 'Manrope', sans-serif; }
.compare { border-color:#d8d7d1; }
.compare-line { grid-template-columns:100px minmax(0,1fr) 42px; font:10px 'Manrope', sans-serif; }
.compare-line .who { color:#777; }
.track { height:5px; background:#e5e4de; border-radius:0; }
.fill { border-radius:0; }
.fill.human { background:#171717; }
.fill.ai { background:#e30613; }
.model-name { color:#171717; font-size:13px; font-weight:650; }
.model-source { color:#777; font:10px/1.6 'Manrope', sans-serif; }
.reference-caveat { background:#f0efeb; border-left:2px solid #e30613; color:#666; border-radius:0; }
.everyday-meaning { border-top-color:#d8d7d1; }
.everyday-meaning strong { color:#e30613; }
.everyday-meaning p { color:#555; }
.source-inline,.data-links a,.calibration-strip a { color:#e30613; }
.source-inline:hover,.data-links a:hover,.calibration-strip a:hover { color:#171717; }
.projection-title { color:#171717; font:10px 'Manrope', sans-serif; }
.projection-title .spark { color:#e30613; text-shadow:none; }
.projection-explain,.result-sub { color:#666; }
.scenario { color:#666; background:transparent; border-color:#d8d7d1; border-radius:0; font:9px 'Manrope', sans-serif; }
.scenario:hover { color:#e30613; background:#edebe5; border-color:#e30613; }
.scenario[aria-pressed="true"] { color:#fff; background:#e30613; border-color:#e30613; box-shadow:none; }
input[type="range"] { accent-color:#e30613; }
.horizon-line strong { color:#e30613; font-family:'Manrope', sans-serif; }
.result-main { color:#171717; font:15px var(--site-font-heading); }
.calibration-strip { background:transparent; border:0; border-bottom:1px solid #d8d7d1; border-radius:0; grid-template-columns:22px minmax(0,1fr) auto; padding:17px 0; margin-top:12px; color:#666; }
.calibration-mark { width:20px; height:20px; border-radius:50%; color:#fff; background:#e30613; }
.calibration-strip p,.data-note p { color:#666; font-size:11px; line-height:1.75; }
.metrics { border-top:1px solid #171717; border-bottom:1px solid #d8d7d1; margin:4px 0 0; }
.metric { border-color:#d8d7d1; padding:15px 15px 13px; }
.metric:first-child { padding-left:0; }
.metric-value,.metric:nth-child(1) .metric-value,.metric:nth-child(2) .metric-value,.metric:nth-child(3) .metric-value { color:#171717 !important; font:clamp(24px,3vw,35px) var(--site-font-heading); letter-spacing:-.06em; }
.metric:nth-child(4) .metric-value { color:#e30613 !important; }
.metric-label { color:#777; }
.metric-foot { color:#777; font:9px/1.5 'Manrope', sans-serif; }
.impact-section { margin-top:32px; }
.section-heading h2,.watch-intro h2 { color:#171717; font:clamp(22px,2.5vw,31px) var(--site-font-heading); letter-spacing:-.06em; }
.section-heading p { color:#777; font:10px 'Manrope', sans-serif; }
.impact-grid { border-color:#d8d7d1; }
.impact { border-color:#d8d7d1; }
.impact-kicker { color:#e30613; }
.impact h3 { color:#171717; font:16px/1.3 var(--site-font-heading); }
.impact p { color:#666; }
.impact .accent,.impact .human-accent { color:#e30613; }
.watch-section { border-color:#d8d7d1; }
.watch-intro h2 { font-size:22px; }
.watch-intro p { color:#666; }
.watch-item { background:transparent; color:#171717; border-color:#d8d7d1; border-radius:0; transition:border-color .16s,padding .16s; }
.watch-item:hover { background:transparent; border-color:#e30613; box-shadow:none; transform:none; }
.watch-name { color:#171717; }
.watch-gap { color:#777; }
.watch-score { color:#e30613; font:18px 'Manrope', sans-serif; }
.data-note { background:transparent; border-color:#d8d7d1; border-radius:0; }
.data-note strong { color:#171717; }
.note-icon { color:#e30613; }
.footer { color:#777; border-color:#d8d7d1; }
.footer-brand { color:#171717; }
.tooltip { background:#fff; border:1px solid #d8d7d1; color:#171717; border-radius:0; box-shadow:0 5px 20px #00000010; }
.tooltip strong { color:#e30613; }
.tooltip span { color:#666; }
.map-button:focus-visible,.faculty-switcher button:focus-visible,.faculty-switcher select:focus-visible,.scenario:focus-visible,.watch-item:focus-visible,.language-toggle:focus-visible,a:focus-visible,.mode-switch button:focus-visible,.journey-trigger:focus-visible { outline:2px solid #e30613; outline-offset:3px; }
@media (max-width:850px) { .galaxy-head { grid-template-columns:minmax(200px,.6fr) minmax(260px,.4fr); gap:10px; } .stage-actions { max-width:100%; } .stage-actions .mode-pill { display:none; } .mode-switch { order:2; flex-wrap:wrap; } .map-button#resetView { display:none; } .activity-log { width:min(300px,40%); } .canvas-wrap { height:650px; } }
@media (max-width:620px) { .shell { padding:12px 14px 32px; } .topbar { align-items:center; } .brand-sub { font-size:8px; } .source-tag { max-width:145px; white-space:normal; text-align:right; font-size:8px; } .galaxy-head { top:19px; display:block; right:0; } .galaxy-head > div:first-child { max-width:240px; } .galaxy-title { font-size:clamp(25px,8vw,34px); max-width:260px; } .galaxy-subtitle { max-width:230px; font-size:9px; margin-top:10px; }
  .stage-actions { position:absolute; top:2px; right:0; max-width:54%; justify-content:flex-end; gap:4px; }
  .mode-switch { display:grid; grid-template-columns:repeat(2,auto); order:0; margin:0; }
  .mode-switch button { font-size:8px; padding:6px 7px; }
  .stage-actions .map-button#zoomOut,.stage-actions .map-button#zoomIn,.stage-actions #zoomLevel { display:none; }
  .canvas-wrap { height:630px; min-height:630px; }
  .activity-log { top:169px; left:0; width:min(260px,61%); max-height:315px; }
  .activity-entry { grid-template-columns:20px minmax(0,1fr) auto; gap:5px; font-size:8px; padding:7px 0; }
  .legend { right:58px; left:auto; bottom:26px; gap:7px; font-size:8px; max-width:calc(100% - 124px); }
  .journey-trigger { width:43px; height:43px; right:2px; bottom:19px; }
  .journey-trigger .journey-hint { bottom:53px; }
  .sidepanel { grid-template-columns:1fr; }
  .metrics { grid-template-columns:repeat(2,minmax(0,1fr)); }
  .metric,.metric:first-child { padding:13px 9px; border-right:1px solid #d8d7d1; border-bottom:1px solid #d8d7d1; }
  .metric:nth-child(2n) { border-right:0; }
  .metric-value { font-size:27px; }
  .impact-grid { grid-template-columns:1fr; }
  .impact,.impact:first-child { border-right:0; border-bottom:1px solid #d8d7d1; padding:15px 0; }
  .impact:last-child { border-bottom:0; }
  .watch-section { grid-template-columns:1fr; gap:12px; }
  .watch-list { grid-template-columns:1fr; }
  .watch-item { display:grid; grid-template-columns:1fr auto; gap:4px 12px; }
  .watch-score { grid-column:2; grid-row:1/span 2; }
  .calibration-strip,.data-note { grid-template-columns:20px minmax(0,1fr); }
  .calibration-links,.data-links { grid-column:2; align-items:flex-start; flex-direction:row; flex-wrap:wrap; white-space:normal; }
  .footer { align-items:flex-start; flex-direction:column; gap:7px; }
}
@media (prefers-reduced-motion:reduce) { .journey-trigger,.activity-entry { transition:none; } }
/* Single-screen observatory: evidence rail + instrument stage. */
html, body { width:100%; height:100%; overflow:hidden !important; }
body { min-height:0; }
#app { width:100%; height:100%; min-height:0; overflow:hidden; }
.shell { display:block; width:100%; max-width:none; height:100svh; min-height:0; overflow:hidden; padding:12px clamp(14px,2.2vw,34px); }
.cosmos-layout { display:grid; grid-template-columns:minmax(0,1.55fr) minmax(360px,.72fr); gap:clamp(18px,2.4vw,38px); width:100%; height:100%; min-height:0; }
.stage-column { display:flex; flex-direction:column; min-width:0; min-height:0; overflow:hidden; }
.right-rail { display:flex; flex-direction:column; min-width:0; min-height:0; overflow:hidden; border-left:1px solid #d8d7d1; padding-left:clamp(14px,1.8vw,28px); }
.right-rail .topbar { flex:0 0 auto; padding:1px 0 9px; gap:8px; align-items:center; }
.right-rail .brand { gap:8px; }
.right-rail .brand-mark { width:21px; height:21px; }
.right-rail .brand-mark span { width:6px; height:6px; }
.right-rail .brand-name { font-size:9px; letter-spacing:.1em; }
.right-rail .brand-sub { margin-top:2px; font-size:8px; }
.right-rail .topmeta { gap:8px; }
.right-rail .source-tag { max-width:155px; white-space:normal; text-align:right; line-height:1.35; font-size:8px; }
.right-rail .language-toggle { padding:6px 8px; font-size:9px; flex:0 0 auto; }
.explorer { display:contents; }
.galaxy-panel { display:flex; flex-direction:column; flex:1 1 auto; min-height:0; overflow:hidden; border:0; background:transparent; box-shadow:none; }
.galaxy-head { position:static; display:grid; grid-template-columns:minmax(0,1fr) minmax(250px,.9fr); align-items:end; gap:15px; padding:10px 0 12px; border:0; background:transparent; }
.galaxy-head > div:first-child { max-width:none; }
.galaxy-title { max-width:620px; font-size:clamp(31px,3.35vw,53px); line-height:.88; letter-spacing:-.072em; text-transform:none; }
.galaxy-subtitle { margin-top:8px; max-width:590px; color:#74746b; font:9px/1.5 'Manrope', sans-serif; letter-spacing:.015em; }
.stage-actions { gap:4px; align-content:end; }
.stage-actions .mode-pill { flex:0 0 auto; padding:6px 7px; font-size:8px; }
.mode-switch { margin:0; flex-wrap:wrap; }
.mode-switch button { padding:6px 7px; font-size:8px; }
.map-button { min-height:27px; padding:5px 7px; font-size:8px; }
.map-button.zoom { min-width:25px; font-size:13px; }
.zoom-level { min-width:28px; padding-top:6px; font-size:8px; }
.activity-log { position:static; width:100%; max-height:none; flex:0 0 auto; margin:0 0 8px; }
.activity-log-head { padding-bottom:5px; font-size:9px; }
.activity-entries { display:grid; grid-template-columns:repeat(5,minmax(0,1fr)); gap:0 12px; padding-top:0; }
.activity-entry { min-width:0; grid-template-columns:17px minmax(0,1fr) auto; gap:4px; padding:5px 0; font-size:8px; }
.activity-name { font-size:8px; }
.canvas-wrap { position:relative; flex:1 1 auto; height:auto; min-height:0; max-height:none; margin:0; overflow:hidden; background:#f7f6f2; }
#cosmos { width:100%; height:100%; }
.canvas-guide { display:none; }
.legend { right:70px; bottom:13px; font-size:8px; gap:8px; }
.journey-trigger { width:42px; height:42px; right:6px; bottom:7px; }
.sidepanel { display:flex; flex-direction:column; gap:0; margin:0; }
.inspector,.projection-card { flex:0 0 auto; padding:10px 0 11px; }
.panel-topline,.small-label,.metric-label,.impact-kicker { font-size:8px; }
.faculty-switcher { margin-top:7px; gap:4px; }
.faculty-switcher label { width:auto; }
.faculty-switcher select { padding:5px 6px; font-size:9px; }
.faculty-switcher button { padding:5px 7px; min-width:28px; font-size:10px; }
.faculty-name { margin:8px 0 3px; font-size:clamp(22px,1.8vw,29px); line-height:.98; }
.faculty-desc { max-width:none; font-size:10px; line-height:1.4; display:-webkit-box; -webkit-line-clamp:2; -webkit-box-orient:vertical; overflow:hidden; }
.status-row { margin:7px 0; gap:6px; }
.status-chip { max-width:65%; font-size:8px; padding:4px 6px; }
.gap-label { font-size:8px; }
.compare { gap:6px; padding:8px 0; }
.compare-line { grid-template-columns:83px minmax(0,1fr) 32px; gap:6px; font-size:8px; }
.track { height:4px; }
.model-block { padding-top:7px; }
.model-name { margin-top:3px; font-size:10px; line-height:1.3; }
.model-source { margin-top:2px; font-size:8px; line-height:1.35; }
.reference-caveat { margin-top:5px; padding:5px 7px; font-size:8px; line-height:1.4; display:-webkit-box; -webkit-line-clamp:3; -webkit-box-orient:vertical; overflow:hidden; }
.everyday-meaning { margin-top:6px; padding-top:5px; }
.everyday-meaning strong { font-size:8px; }
.everyday-meaning p { margin-top:3px; font-size:9px; line-height:1.4; display:-webkit-box; -webkit-line-clamp:2; -webkit-box-orient:vertical; overflow:hidden; }
.source-inline { margin-top:5px; font-size:8px; }
.projection-title { font-size:9px; }
.projection-explain { margin:4px 0 6px; font-size:9px; line-height:1.4; }
.scenario-tabs { gap:4px; }
.scenario { padding:5px 4px; font-size:8px; }
.horizon-line { margin-top:7px; font-size:9px; }
input[type="range"] { margin-top:5px; }
.range-labels { margin-top:0; font-size:8px; }
.scenario-result { margin-top:6px; padding-top:6px; }
.result-main { font-size:11px; }
.result-sub { margin-top:2px; font-size:8px; line-height:1.35; }
.right-rail .metrics { flex:0 0 auto; grid-template-columns:repeat(4,minmax(0,1fr)); gap:0; margin:8px 0 0; border-top:1px solid #171717; border-bottom:1px solid #d8d7d1; }
.right-rail .metric,.right-rail .metric:first-child { padding:8px 6px 7px; min-width:0; border-right:1px solid #d8d7d1; border-bottom:0; }
.right-rail .metric:first-child { padding-left:0; }
.right-rail .metric:last-child { border-right:0; padding-right:0; }
.right-rail .metric-label { font-size:7px; letter-spacing:.02em; line-height:1.25; }
.right-rail .metric-value,.right-rail .metric:nth-child(1) .metric-value,.right-rail .metric:nth-child(2) .metric-value,.right-rail .metric:nth-child(3) .metric-value,.right-rail .metric:nth-child(4) .metric-value { margin-top:4px; font-size:clamp(16px,1.55vw,22px); line-height:1; }
.right-rail .metric-foot { margin-top:3px; font-size:7px; line-height:1.25; }
.calibration-strip { flex:0 0 auto; grid-template-columns:18px minmax(0,1fr) auto; gap:7px; margin:0; padding:7px 0; border:0; border-bottom:1px solid #d8d7d1; }
.calibration-mark { width:16px; height:16px; font-size:9px; }
.calibration-strip p { font-size:8px; line-height:1.4; }
.calibration-links { gap:4px; }
.calibration-strip a { font-size:8px; }
.impact-section { flex:0 0 auto; margin:7px 0 0; }
.section-heading { align-items:baseline; gap:8px; margin-bottom:5px; }
.section-heading h2,.watch-intro h2 { font-size:14px; line-height:1.1; letter-spacing:-.045em; }
.section-heading p { max-width:52%; font-size:7px; line-height:1.3; }
.impact-grid { grid-template-columns:repeat(3,minmax(0,1fr)); gap:8px; border-top:1px solid #d8d7d1; border-bottom:1px solid #d8d7d1; }
.impact,.impact:first-child { min-width:0; padding:6px 6px 6px 0; border-right:1px solid #d8d7d1; border-bottom:0; }
.impact:last-child { padding-right:0; border-right:0; }
.impact-kicker { font-size:7px; line-height:1.3; letter-spacing:0; }
.impact h3 { margin:4px 0 3px; font-size:9px; line-height:1.2; }
.impact p { font-size:8px; line-height:1.35; display:-webkit-box; -webkit-line-clamp:3; -webkit-box-orient:vertical; overflow:hidden; }
.watch-section { flex:0 0 auto; grid-template-columns:1fr; gap:5px; padding:7px 0; border-bottom:1px solid #d8d7d1; }
.watch-intro { display:flex; align-items:baseline; gap:7px; flex-wrap:wrap; }
.watch-intro h2 { font-size:12px; }
.watch-intro p { display:none; }
.watch-list { grid-template-columns:repeat(3,minmax(0,1fr)); gap:5px; }
.watch-item { min-width:0; padding:5px 6px; }
.watch-name { font-size:8px; white-space:nowrap; overflow:hidden; text-overflow:ellipsis; }
.watch-gap { font-size:7px; margin-top:2px; line-height:1.2; }
.watch-score { margin-top:3px; font-size:11px; }
.data-note { flex:0 0 auto; grid-template-columns:14px minmax(0,1fr) auto; gap:6px; margin:0; padding:6px 0; border:0; border-bottom:1px solid #d8d7d1; }
.note-icon { font-size:11px; }
.data-note p { font-size:7px; line-height:1.35; display:-webkit-box; -webkit-line-clamp:3; -webkit-box-orient:vertical; overflow:hidden; }
.data-links { gap:4px; white-space:normal; }
.data-links a { font-size:7px; }
.right-rail .footer { flex:0 0 auto; align-items:center; flex-direction:row; gap:6px; padding-top:5px; font-size:7px; }
.right-rail .footer-brand { font-size:7px; }
.tooltip { font-size:8px; max-width:165px; }
@media (max-width:1050px) and (min-width:761px) {
  .cosmos-layout { grid-template-columns:minmax(0,1.25fr) minmax(320px,.85fr); gap:14px; }
  .right-rail { padding-left:12px; }
  .galaxy-head { grid-template-columns:minmax(0,1fr); gap:8px; }
  .stage-actions { justify-content:flex-start; }
  .activity-entries { gap:0 7px; }
  .activity-entry { grid-template-columns:14px minmax(0,1fr) auto; font-size:7px; }
  .activity-name { font-size:7px; }
  .calibration-links { display:none; }
}
@media (max-width:760px) {
  .shell { padding:8px; }
  .cosmos-layout { grid-template-columns:minmax(0,1fr); grid-template-rows:minmax(0,1.15fr) minmax(0,.85fr); gap:6px; height:100%; }
  .stage-column { min-height:0; }
  .right-rail { border-left:0; border-top:1px solid #d8d7d1; padding:5px 0 0; overflow:hidden; }
  .right-rail .topbar { padding:0 0 5px; }
  .right-rail .brand-sub { display:none; }
  .right-rail .topmeta { gap:6px; }
  .right-rail .source-tag { max-width:none; font-size:7px; }
  .right-rail .metrics { margin-top:5px; }
  .right-rail .metric,.right-rail .metric:first-child { padding:4px 5px; }
  .right-rail .metric-foot { display:none; }
  .galaxy-head { grid-template-columns:minmax(0,1fr); gap:6px; padding:5px 0 7px; }
  .galaxy-title { max-width:none; font-size:clamp(25px,6vw,38px); line-height:.9; }
  .galaxy-subtitle { margin-top:4px; font-size:7px; }
  .stage-actions { justify-content:flex-start; }
  .stage-actions .mode-pill { display:none; }
  .mode-switch button { padding:5px 5px; font-size:7px; }
  .activity-log { margin-bottom:4px; }
  .activity-log-head { font-size:7px; padding-bottom:3px; }
  .activity-entries { grid-template-columns:repeat(5,minmax(0,1fr)); gap:0 5px; }
  .activity-entry { grid-template-columns:11px minmax(0,1fr); gap:2px; padding:3px 0; }
  .activity-gap { display:none; }
  .activity-num,.activity-name { font-size:6px; }
  .canvas-wrap { min-height:0; }
  .legend { right:48px; bottom:7px; max-width:calc(100% - 58px); flex-wrap:wrap; gap:5px; font-size:6px; }
  .legend i { width:5px; height:5px; }
  .journey-trigger { width:32px; height:32px; right:4px; bottom:4px; }
  .journey-trigger svg { width:13px; height:13px; }
  .right-rail .sidepanel { display:grid; grid-template-columns:minmax(0,1fr) minmax(0,.9fr); gap:10px; }
  .inspector,.projection-card { padding:5px 0; min-width:0; }
  .faculty-switcher { flex-wrap:nowrap; }
  .faculty-switcher label { display:none; }
  .faculty-switcher select { padding:4px; font-size:8px; }
  .faculty-name { font-size:18px; }
  .faculty-desc { font-size:8px; }
  .reference-caveat,.everyday-meaning,.model-source { display:none; }
  .model-block { padding-top:4px; }
  .model-name { font-size:8px; }
  .source-inline { font-size:7px; }
  .projection-title { font-size:8px; }
  .projection-explain { display:none; }
  .scenario { padding:4px 2px; font-size:7px; }
  .horizon-line { margin-top:4px; font-size:7px; }
  .scenario-result { margin-top:4px; padding-top:4px; }
  .result-main { font-size:9px; }
  .result-sub { font-size:7px; }
  .calibration-strip { padding:4px 0; }
  .calibration-strip p { font-size:7px; -webkit-line-clamp:2; }
  .calibration-links { display:none; }
  .impact-section { display:none; }
  .watch-section { padding:4px 0; }
  .watch-kicker { display:none; }
  .watch-intro h2 { font-size:9px; }
  .watch-list { grid-template-columns:repeat(3,minmax(0,1fr)); }
  .watch-item { padding:3px; }
  .watch-name { font-size:7px; }
  .watch-gap { display:none; }
  .watch-score { font-size:8px; }
  .data-note { padding:4px 0; }
  .data-note p { font-size:6px; -webkit-line-clamp:2; }
  .data-links { display:none; }
  .right-rail .footer { display:none; }
}
/* Geodesic atlas v2: larger type, a consistent surface, and deliberate motion. */
html,body { overflow:hidden !important; height:100%; overscroll-behavior:none; }
body,#app { min-height:0; height:100%; }
.shell { height:100svh; min-height:0; padding:14px clamp(14px,2.2vw,32px); }
.cosmos-layout { grid-template-columns:minmax(0,1.6fr) minmax(380px,.8fr); gap:clamp(17px,2vw,30px); }
.stage-column,.right-rail,.galaxy-panel { min-height:0; }
.galaxy-head { padding:13px 0 10px; grid-template-columns:minmax(0,.95fr) minmax(300px,1.05fr); gap:17px; }
.galaxy-title { max-width:600px; font-size:clamp(31px,3.3vw,49px); line-height:.97; letter-spacing:-.065em; }
.galaxy-subtitle { max-width:650px; margin-top:7px; font-size:11px; line-height:1.55; }
.stage-actions { gap:5px; }
.mode-switch button { padding:8px 10px; font-size:10px; }
.mode-pill,.map-button,.zoom-level { font-size:10px; }
.map-button { min-height:31px; padding:7px 9px; }
.map-button.zoom { min-width:30px; font-size:16px; }
.activity-log { margin:0 0 10px; }
.activity-log-head { padding-bottom:7px; font-size:10px; }
.activity-entries { grid-template-columns:repeat(5,minmax(0,1fr)); gap:0 14px; }
.activity-entry { grid-template-columns:22px minmax(0,1fr) auto; gap:6px; padding:7px 0; font-size:10px; }
.activity-num { font-size:10px; }
.activity-name { font-size:10px; }
.activity-gap { font-size:10px; }
.canvas-wrap { flex:1 1 auto; height:auto; min-height:0; max-height:none; }
.legend { right:66px; bottom:14px; font-size:10px; gap:11px; }
.journey-trigger { width:45px; height:45px; right:5px; bottom:6px; }
.right-rail .topbar { padding-bottom:10px; }
.right-rail .brand-name { font-size:10px; }
.right-rail .brand-sub { font-size:9px; }
.right-rail .source-tag { font-size:9px; max-width:180px; }
.right-rail .metrics { margin-top:9px; }
.right-rail .metric-label { font-size:9px; line-height:1.3; }
.right-rail .metric-value,.right-rail .metric:nth-child(1) .metric-value,.right-rail .metric:nth-child(2) .metric-value,.right-rail .metric:nth-child(3) .metric-value,.right-rail .metric:nth-child(4) .metric-value { font-size:clamp(19px,1.8vw,26px); }
.right-rail .metric-foot { font-size:8px; line-height:1.35; }
.inspector,.projection-card { padding:12px 0 13px; }
.panel-topline,.small-label,.metric-label,.impact-kicker { font-size:9px; }
.faculty-switcher { margin-top:9px; gap:5px; }
.faculty-switcher select { padding:7px 8px; font-size:11px; }
.faculty-switcher button { padding:7px 9px; min-width:31px; font-size:13px; }
.faculty-name { margin:10px 0 5px; font-size:clamp(26px,2.25vw,34px); line-height:1; }
.faculty-desc { font-size:12px; line-height:1.5; }
.status-row { margin:9px 0; }
.status-chip,.gap-label { font-size:10px; }
.compare { gap:9px; padding:10px 0; }
.compare-line { grid-template-columns:90px minmax(0,1fr) 38px; gap:7px; font-size:10px; }
.track { height:6px; }
.model-block { padding-top:9px; }
.model-name { margin-top:5px; font-size:12px; line-height:1.4; }
.model-source { font-size:10px; line-height:1.45; }
.reference-caveat { font-size:10px; line-height:1.45; padding:7px 8px; }
.everyday-meaning { margin-top:8px; padding-top:7px; }
.everyday-meaning strong { font-size:9px; }
.everyday-meaning p { margin-top:4px; font-size:10px; line-height:1.45; }
.source-inline { margin-top:7px; font-size:10px; }
.projection-title { font-size:11px; }
.projection-explain { margin:5px 0 8px; font-size:10px; line-height:1.45; }
.scenario { padding:7px 5px; font-size:9px; }
.horizon-line { margin-top:9px; font-size:10px; }
input[type="range"] { margin-top:7px; }
.scenario-result { margin-top:8px; padding-top:8px; }
.result-main { font-size:13px; }
.result-sub { font-size:9px; line-height:1.45; }
.calibration-strip { padding:8px 0; }
.calibration-strip p { font-size:9px; line-height:1.5; }
.calibration-links { gap:5px; }
.calibration-strip a { font-size:9px; }
.impact-section { margin-top:9px; }
.section-heading { margin-bottom:6px; }
.section-heading h2,.watch-intro h2 { font-size:clamp(15px,1.5vw,20px); line-height:1.1; }
.section-heading p { font-size:9px; line-height:1.35; }
.impact-grid { gap:8px; }
.impact,.impact:first-child { padding:8px 7px 8px 0; }
.impact-kicker { font-size:8px; line-height:1.3; }
.impact h3 { font-size:11px; line-height:1.25; margin:5px 0 4px; }
.impact p { font-size:9px; line-height:1.45; display:-webkit-box; -webkit-line-clamp:4; -webkit-box-orient:vertical; overflow:hidden; }
.watch-section { padding:8px 0; gap:7px; }
.watch-intro h2 { font-size:15px; margin:2px 0; }
.watch-intro p { font-size:9px; line-height:1.4; }
.watch-list { gap:5px; }
.watch-item { padding:7px; }
.watch-name { font-size:10px; }
.watch-gap { font-size:8px; margin-top:4px; }
.watch-score { font-size:12px; margin-top:5px; }
.data-note { padding:7px 0; }
.data-note p { font-size:9px; line-height:1.45; }
.data-links a { font-size:9px; }
.right-rail .footer { padding-top:5px; font-size:8px; }
.right-rail .footer-brand { font-size:8px; }
.tooltip { font-size:11px; max-width:220px; }
.tooltip strong { font-size:12px; }
@media (max-height:850px) and (min-width:761px) {
  .shell { padding-top:9px; padding-bottom:9px; }
  .right-rail .brand-sub { display:none; }
  .right-rail .topbar { padding-bottom:5px; }
  .galaxy-head { padding-top:7px; padding-bottom:7px; }
  .galaxy-title { font-size:clamp(27px,2.8vw,40px); }
  .activity-log { margin-bottom:6px; }
  .activity-entry { padding:5px 0; }
  .inspector,.projection-card { padding:7px 0 8px; }
  .faculty-name { margin-top:6px; font-size:26px; }
  .faculty-desc { font-size:10px; }
  .model-block { padding-top:5px; }
  .reference-caveat,.everyday-meaning { margin-top:5px; }
  .everyday-meaning p { font-size:9px; }
  .impact-section { margin-top:5px; }
  .impact p { -webkit-line-clamp:3; }
  .calibration-strip p,.data-note p { -webkit-line-clamp:2; display:-webkit-box; -webkit-box-orient:vertical; overflow:hidden; }
}
@media (max-width:1050px) and (min-width:761px) {
  .cosmos-layout { grid-template-columns:minmax(0,1.35fr) minmax(335px,.9fr); gap:13px; }
  .galaxy-head { grid-template-columns:1fr; gap:8px; }
  .stage-actions { justify-content:flex-start; }
  .activity-entries { gap:0 8px; }
  .activity-entry { grid-template-columns:17px minmax(0,1fr) auto; font-size:9px; }
  .activity-name { font-size:9px; }
}
@media (max-width:760px) {
  .shell { padding:8px; }
  .cosmos-layout { grid-template-columns:minmax(0,1fr); grid-template-rows:minmax(0,1.13fr) minmax(0,.87fr); gap:5px; }
  .right-rail { padding:5px 0 0; overflow:hidden; }
  .galaxy-head { padding:4px 0 6px; gap:5px; }
  .galaxy-title { font-size:clamp(24px,6vw,34px); line-height:.95; }
  .galaxy-subtitle { margin-top:4px; font-size:9px; line-height:1.35; }
  .stage-actions { gap:4px; }
  .mode-switch button { padding:6px 6px; font-size:9px; }
  .map-button { min-height:27px; padding:5px 6px; font-size:9px; }
  .activity-log { margin-bottom:5px; }
  .activity-log-head { font-size:8px; padding-bottom:4px; }
  .activity-entries { gap:0 5px; }
  .activity-entry { grid-template-columns:13px minmax(0,1fr); padding:4px 0; }
  .activity-num,.activity-name { font-size:8px; }
  .activity-gap { display:none; }
  .legend { right:43px; bottom:6px; max-width:calc(100% - 50px); flex-wrap:wrap; gap:6px; font-size:8px; }
  .journey-trigger { width:32px; height:32px; right:4px; bottom:3px; }
  .right-rail .topbar { padding-bottom:4px; }
  .right-rail .brand-sub { display:none; }
  .right-rail .brand-name { font-size:9px; }
  .right-rail .source-tag { font-size:7px; max-width:140px; }
  .right-rail .metrics { margin-top:3px; }
  .right-rail .metric,.right-rail .metric:first-child { padding:4px; }
  .right-rail .metric-label { font-size:7px; }
  .right-rail .metric-value,.right-rail .metric:nth-child(1) .metric-value,.right-rail .metric:nth-child(2) .metric-value,.right-rail .metric:nth-child(3) .metric-value,.right-rail .metric:nth-child(4) .metric-value { font-size:16px; }
  .right-rail .metric-foot { display:none; }
  .right-rail .sidepanel { grid-template-columns:minmax(0,1fr) minmax(0,.9fr); gap:8px; }
  .inspector,.projection-card { padding:4px 0; }
  .faculty-name { font-size:18px; margin:5px 0 3px; }
  .faculty-desc { font-size:9px; line-height:1.3; }
  .status-row { margin:4px 0; }
  .status-chip,.gap-label { font-size:7px; }
  .compare { padding:4px 0; gap:4px; }
  .compare-line { grid-template-columns:53px minmax(0,1fr) 24px; gap:4px; font-size:7px; }
  .track { height:4px; }
  .panel-topline,.small-label { font-size:7px; }
  .faculty-switcher { margin-top:4px; gap:3px; }
  .faculty-switcher label { display:none; }
  .faculty-switcher select { padding:3px; font-size:8px; }
  .faculty-switcher button { min-width:22px; padding:3px; font-size:9px; }
  .model-block { padding-top:4px; }
  .model-name { font-size:8px; }
  .model-source,.reference-caveat,.everyday-meaning,.source-inline { display:none; }
  .projection-title { font-size:8px; }
  .projection-explain { display:none; }
  .scenario { padding:4px 2px; font-size:7px; }
  .horizon-line { margin-top:4px; font-size:7px; }
  .range-labels { font-size:7px; }
  .scenario-result { margin-top:4px; padding-top:4px; }
  .result-main { font-size:9px; }
  .result-sub { font-size:7px; }
  .calibration-strip { padding:4px 0; grid-template-columns:14px minmax(0,1fr); gap:4px; }
  .calibration-mark { width:13px; height:13px; font-size:7px; }
  .calibration-strip p { font-size:7px; line-height:1.3; -webkit-line-clamp:2; }
  .calibration-links { display:none; }
  .impact-section { display:none; }
  .watch-section { padding:4px 0; }
  .watch-kicker,.watch-intro p { display:none; }
  .watch-intro h2 { font-size:9px; }
  .watch-list { grid-template-columns:repeat(3,minmax(0,1fr)); gap:3px; }
  .watch-item { padding:3px; }
  .watch-name { font-size:7px; }
  .watch-gap { display:none; }
  .watch-score { font-size:8px; }
  .data-note { padding:4px 0; grid-template-columns:12px minmax(0,1fr); gap:4px; }
  .data-note p { font-size:6px; line-height:1.25; -webkit-line-clamp:2; }
  .note-icon { font-size:8px; }
  .data-links,.right-rail .footer { display:none; }
}
/* Bright white observatory; the selected faculty owns the accent colour. */
:root { color-scheme:light; --faculty-accent:#E30613; --faculty-accent-soft:color-mix(in srgb,var(--faculty-accent) 10%,#fff); --site-primary:var(--faculty-accent); --site-secondary:var(--faculty-accent); --site-background:#fff; --ink:#17191f; --muted:#68707d; --surface:#fff; --surface-2:#fbfcfe; --line:#e3e7ee; --canvas-bg:#fff; }
html,body,#app { color-scheme:light !important; background:#fff !important; color:#17191f !important; }
body { background:radial-gradient(ellipse at 58% 0%,rgba(231,237,246,.30),transparent 38%),linear-gradient(145deg,#fff 0%,#fff 57%,#fcfdff 100%) !important; }
body::before,body::after { display:none !important; } #app { background:transparent !important; }
.right-rail,.topbar { border-color:#e3e7ee; }
.brand-name,.faculty-name,.galaxy-title,.section-heading h2,.watch-intro h2,.model-name,.result-main,.projection-title { color:#17191f; }
.brand-sub,.galaxy-subtitle,.faculty-desc,.model-source,.projection-explain,.result-sub,.impact p,.watch-intro p,.data-note p,.footer { color:#5f6877; }
.brand-mark { background:linear-gradient(145deg,#fff,#f5f7fb); border-color:color-mix(in srgb,var(--faculty-accent) 38%,#fff); box-shadow:0 2px 9px rgba(27,38,58,.06),inset 0 1px 0 #fff; }
.brand-mark span,.source-tag::before,.calibration-mark { background:var(--faculty-accent) !important; box-shadow:none !important; }
.source-tag { color:var(--faculty-accent) !important; background:#fff !important; border:1px solid color-mix(in srgb,var(--faculty-accent) 22%,#e3e7ee) !important; border-radius:3px !important; }
.language-toggle { background:#fff; color:#17191f; border-color:#dfe4ec; border-radius:3px; }
.language-toggle:hover,.map-button:hover,.faculty-switcher button:hover { color:#fff !important; background:var(--faculty-accent) !important; border-color:var(--faculty-accent) !important; }
.galaxy-panel { color:#17191f; background:rgba(255,255,255,.6); border:1px solid #e8ebf1; border-radius:10px; box-shadow:0 12px 38px rgba(28,43,68,.035),inset 0 1px 0 #fff; backdrop-filter:blur(7px); }
.galaxy-head { border-bottom:1px solid #edf0f5; background:linear-gradient(110deg,rgba(255,255,255,.95),rgba(250,251,254,.7)); }
.canvas-wrap { background:radial-gradient(ellipse at 22% 5%,#fff 0%,transparent 55%),linear-gradient(145deg,#fff,#fbfcff 72%,#fff); border:1px solid #edf0f5; border-radius:7px; box-shadow:inset 0 1px 0 #fff,0 8px 25px rgba(28,43,68,.025); }
.canvas-wrap::after { content:""; position:absolute; inset:0; pointer-events:none; border-radius:inherit; background:linear-gradient(112deg,rgba(255,255,255,.18),transparent 28%,transparent 72%,rgba(255,255,255,.24)); }
.activity-log-head { color:#454d5b; border-bottom-color:#cfd5df; } .activity-log-head span { color:#777f8b; }
.activity-entry { color:#69717e; border-bottom-color:#e8ebf1; } .activity-entry:hover { color:#17191f; }
.activity-entry[aria-current="true"] .activity-num,.activity-entry[aria-current="true"] .activity-gap,.activity-gap.ai-leading { color:var(--faculty-accent); }
.activity-entry[aria-current="true"] .activity-name { color:#17191f; text-decoration:underline; text-decoration-color:color-mix(in srgb,var(--faculty-accent) 48%,transparent); text-underline-offset:3px; }
.mode-pill { color:var(--faculty-accent); background:var(--faculty-accent-soft); border-color:color-mix(in srgb,var(--faculty-accent) 34%,#fff); border-radius:3px; }
.mode-switch,.map-button,.faculty-switcher select,.faculty-switcher button,.scenario { background:#fff; border-color:#dfe4ec; }
.mode-switch button { color:#677080; } .mode-switch button:hover { background:#f4f6fa; color:var(--faculty-accent); }
.mode-switch button[aria-pressed="true"],.scenario[aria-pressed="true"] { color:#fff !important; background:var(--faculty-accent) !important; border-color:var(--faculty-accent) !important; box-shadow:0 4px 12px color-mix(in srgb,var(--faculty-accent) 17%,transparent) !important; }
.map-button:focus-visible,.faculty-switcher button:focus-visible,.faculty-switcher select:focus-visible,.scenario:focus-visible,.watch-item:focus-visible,.language-toggle:focus-visible,a:focus-visible,.mode-switch button:focus-visible,.journey-trigger:focus-visible { outline:2px solid var(--faculty-accent) !important; outline-offset:3px; }
.zoom-level { color:#657080; }
.legend { color:#5c6573; background:rgba(255,255,255,.9); border:1px solid #e4e8ef; border-radius:4px; box-shadow:0 3px 12px rgba(27,38,58,.035); }
.legend .hum { background:#20242d; box-shadow:none; } .legend .machine { background:var(--faculty-accent); border-radius:1px; transform:rotate(45deg); box-shadow:none; }
.legend .selected-key { background:var(--faculty-accent); box-shadow:0 0 0 3px var(--faculty-accent-soft); }
.journey-trigger { background:var(--faculty-accent); box-shadow:0 0 0 1px var(--faculty-accent),0 0 0 6px var(--faculty-accent-soft); }
.journey-trigger:hover { box-shadow:0 0 0 1px var(--faculty-accent),0 0 0 9px var(--faculty-accent-soft); }
.sidepanel .inspector,.sidepanel .projection-card { color:#17191f; background:rgba(255,255,255,.96); border-color:#e3e7ee; box-shadow:0 5px 20px rgba(28,43,68,.025),inset 0 1px 0 #fff; }
.panel-topline,.small-label,.metric-label,.impact-kicker { color:#69717e; }
.selected-index,.horizon-line strong,.everyday-meaning strong,.note-icon,.watch-score,.metric:nth-child(4) .metric-value,.source-inline,.data-links a,.calibration-strip a,.impact .accent,.impact .human-accent { color:var(--faculty-accent) !important; }
.status-chip.human { color:#333b48; background:#f2f4f7; border-color:#dce2ea; }
.status-chip.ai { color:var(--faculty-accent) !important; background:var(--faculty-accent-soft) !important; border:1px solid color-mix(in srgb,var(--faculty-accent) 26%,#fff); }
.status-chip.close { color:#5f6877; background:#f5f6f9; border-color:#e1e5ed; }
.compare { border-color:#e4e8ef; } .track { background:#edf0f5; } .fill.human { background:#20242d; }
.fill.ai { background:linear-gradient(90deg,color-mix(in srgb,var(--faculty-accent) 64%,#fff),var(--faculty-accent)) !important; }
.reference-caveat { background:#f8f9fc; border-left-color:var(--faculty-accent) !important; color:#576171; }
.everyday-meaning { border-top-color:#e4e8ef; } .everyday-meaning p { color:#535d6b; }
.source-inline,.data-links a,.calibration-strip a { color:var(--faculty-accent) !important; }
.projection-title .spark { color:var(--faculty-accent); text-shadow:none; } .scenario:hover { color:var(--faculty-accent); border-color:var(--faculty-accent); background:var(--faculty-accent-soft); }
input[type="range"] { accent-color:var(--faculty-accent); } .scenario-result { border-color:#e3e7ee; }
.calibration-strip { background:rgba(255,255,255,.58); border-color:#e3e7ee; } .calibration-strip p { color:#5f6877; }
.metric { background:transparent; border-color:#e3e7ee; } .metric-value,.metric:nth-child(1) .metric-value,.metric:nth-child(2) .metric-value,.metric:nth-child(3) .metric-value { color:#20242d !important; }
.metric:nth-child(4) .metric-value { color:var(--faculty-accent) !important; } .metric-label,.metric-foot { color:#6a7380; }
.impact-grid,.impact,.watch-section { border-color:#e3e7ee; } .impact h3 { color:#20242d; } .impact p { color:#5f6877; }
.watch-item { color:#20242d; background:rgba(255,255,255,.86); border-color:#e1e6ee; box-shadow:0 2px 8px rgba(25,37,58,.025); }
.watch-item:hover { border-color:color-mix(in srgb,var(--faculty-accent) 46%,#fff); background:#fff; box-shadow:0 8px 24px rgba(25,37,58,.06); }
.watch-name { color:#20242d; } .watch-gap { color:#68717e; } .data-note { background:rgba(255,255,255,.7); border-color:#e1e6ee; }
.data-note p { color:#5f6877; } .data-note strong { color:#20242d; } .footer { border-color:#e4e8ef; color:#68717e; } .footer-brand { color:#20242d; }
.tooltip { color:#17191f; background:rgba(255,255,255,.97); border-color:#dfe4ec; box-shadow:0 9px 28px rgba(23,32,49,.12); }
.tooltip strong { color:var(--faculty-accent) !important; } .tooltip span { color:#535d6b; }
@media (max-width:760px) { .canvas-wrap { background:#fff; } .galaxy-panel { border-radius:7px; } .legend { background:rgba(255,255,255,.95); } }
/* Final cohesion pass: precise controls, high-contrast editorial type, and aligned micro-UI. */
:root { --site-font-body:'Manrope',Arial,sans-serif; --ink:#111216; --muted:#454954; --line:#d7dbe2; }
body,button,input,select,textarea,.faculty-name,.faculty-desc,.model-name,.result-main,.result-sub,.projection-explain,.impact h3,.impact p,.watch-name,.watch-gap,.data-note p,.hero-copy,.hero-note { font-family:'Manrope',Arial,sans-serif; }
.brand-sub,.source-tag,.mode-pill,.mode-switch button,.map-button,.zoom-level,.activity-log-head,.activity-entry,.panel-topline,.small-label,.metric-label,.metric-foot,.compare-line,.model-source,.calibration-strip a,.data-links a { font-family:'Manrope', sans-serif; }
.galaxy-title,.faculty-name,.model-name,.result-main,.section-heading h2,.watch-intro h2,.impact h3,.metric-value,.brand-name { color:#101114; }
.galaxy-subtitle,.faculty-desc,.model-source,.projection-explain,.result-sub,.impact p,.watch-intro p,.data-note p,.metric-foot,.watch-gap { color:#353943; }
.stage-actions { display:flex; align-items:center; justify-content:flex-end; }
.stage-actions > *, .mode-switch, .mode-switch button, .map-button, .mode-pill, .scenario, .language-toggle { box-sizing:border-box; align-items:center; justify-content:center; text-align:center; line-height:1.25; }
.mode-switch { display:inline-flex; flex-wrap:nowrap; align-self:center; }
.mode-switch button { display:inline-flex; min-height:30px; white-space:nowrap; vertical-align:middle; }
.stage-actions .mode-pill { display:inline-flex; min-height:29px; }
.map-button { display:inline-flex; min-height:29px; white-space:nowrap; }
.scenario-tabs { align-items:stretch; }
.scenario { display:flex; min-height:34px; align-items:center; justify-content:center; text-align:center; line-height:1.2; }
.language-toggle { display:inline-flex; align-items:center; justify-content:center; text-align:center; white-space:nowrap; }
.comparator-switcher { display:grid; grid-template-columns:minmax(106px,.42fr) minmax(0,1fr); align-items:center; gap:10px; margin:9px 0 4px; padding:9px 0; border-top:1px solid #e1e4e9; border-bottom:1px solid #e1e4e9; }
.comparator-switcher label { color:#242832; font:9px/1.3 'Manrope', sans-serif; text-transform:uppercase; letter-spacing:.055em; }
.comparator-switcher select { min-width:0; width:100%; min-height:34px; padding:7px 9px; border:1px solid #c6cbd4; border-radius:3px; background:#fff; color:#111216; font:600 11px/1.3 'Manrope',Arial,sans-serif; text-align:left; }
.comparator-switcher select:focus-visible { outline:2px solid var(--faculty-accent); outline-offset:2px; }
.comparison-kind { display:inline-flex; align-items:center; gap:6px; margin-top:6px; color:#30343d; font:9px/1.45 'Manrope', sans-serif; }
.comparison-kind::before { content:""; width:6px; height:6px; flex:0 0 auto; border-radius:50%; background:var(--faculty-accent); }
.reference-caveat { color:#252a33; background:#f3f5f8; }
.everyday-meaning p { color:#30343d; }
.impact-kicker { color:#4b505c; }
.data-note p,.calibration-strip p { color:#30343d; }
.mode-switch button:disabled,.scenario:disabled,input:disabled { cursor:not-allowed; opacity:.42; }
#cosmos { touch-action:none; }
@media (max-width:1050px) { .mode-switch button { padding-left:6px; padding-right:6px; } }
@media (max-width:760px) {
  .comparator-switcher { grid-template-columns:1fr; gap:5px; margin:5px 0 3px; padding:5px 0; }
  .comparator-switcher label { font-size:7px; }
  .comparator-switcher select { min-height:28px; padding:4px 6px; font-size:9px; }
  .mode-switch button { min-height:27px; }
  .scenario { min-height:27px; }
}
/* Final readability and control-alignment pass. */
.canvas-wrap { background:#f1f3f7 !important; }
.galaxy-subtitle,.faculty-desc,.model-source,.projection-explain,.result-sub,.impact p,.watch-intro p,.data-note p,.calibration-strip p,.metric-foot { color:#424a57 !important; }
.comparator-switcher label { color:#242a34; }
.comparator-switcher select { border-color:#aab2c0; }
.stage-actions { align-items:center; }
.mode-switch button,.scenario,.stage-actions .map-button,.stage-actions .mode-pill { display:inline-flex; align-items:center; justify-content:center; text-align:center; line-height:1.2; }
.mode-switch button { min-height:32px; }
.scenario { min-height:34px; }
.reference-caveat { display:block !important; }
@media (max-width:760px) { .mode-switch button,.scenario { min-height:27px; } }
/* Desktop fit pass: give the evidence rail more usable vertical space without clipping its copy. */
@media (min-width:1100px) and (min-height:900px) {
  .cosmos-layout { grid-template-columns:minmax(0,1.52fr) minmax(390px,.86fr); gap:clamp(12px,1.4vw,22px); }
  .right-rail { overflow:visible; padding-left:14px; }
  .right-rail .sidepanel { display:grid; grid-template-columns:minmax(0,1.12fr) minmax(0,.88fr); gap:12px; align-items:start; }
  .right-rail .inspector,.right-rail .projection-card { min-width:0; padding:7px 0 8px; }
  .right-rail .faculty-desc,.right-rail .reference-caveat,.right-rail .everyday-meaning p,.right-rail .impact p,.right-rail .calibration-strip p,.right-rail .data-note p { display:block; overflow:visible; -webkit-line-clamp:unset; }
  .right-rail .faculty-desc { font-size:10px; line-height:1.35; }
  .right-rail .reference-caveat,.right-rail .everyday-meaning p { font-size:9px; line-height:1.35; }
  .right-rail .model-source,.right-rail .projection-explain,.right-rail .result-sub { font-size:8px; line-height:1.3; }
  .right-rail .projection-explain { display:block; }
  .right-rail .impact-grid { gap:6px; }
  .right-rail .impact,.right-rail .impact:first-child { padding:6px 5px 6px 0; }
  .right-rail .impact h3 { font-size:10px; }
  .right-rail .impact p { font-size:8px; line-height:1.3; }
  .right-rail .watch-section { padding:5px 0; gap:4px; }
  .right-rail .watch-intro p { display:block; font-size:8px; line-height:1.3; }
  .right-rail .data-note p,.right-rail .calibration-strip p { font-size:8px; line-height:1.3; }
}
/* Keep the comparator control proportionate to the inspector, while preserving mobile width. */
.comparator-switcher { width:min(84%,380px); grid-template-columns:minmax(90px,.42fr) minmax(0,1fr); gap:8px; }
@media (max-width:760px) { .comparator-switcher { width:100%; } }
/* Give the future-horizon control a soft white track; keep its active thumb on-brand. */
#horizon { appearance:none; -webkit-appearance:none; height:16px; background:transparent; accent-color:var(--faculty-accent); }
#horizon::-webkit-slider-runnable-track { height:5px; border:1px solid #e1e5ec; border-radius:99px; background:#f5f6f8; }
#horizon::-moz-range-track { height:5px; border:1px solid #e1e5ec; border-radius:99px; background:#f5f6f8; }
#horizon::-webkit-slider-thumb { -webkit-appearance:none; appearance:none; width:13px; height:13px; margin-top:-5px; border:2px solid #fff; border-radius:50%; background:var(--faculty-accent); box-shadow:0 0 0 1px color-mix(in srgb,var(--faculty-accent) 26%,#d5dae2); cursor:grab; }
#horizon::-moz-range-thumb { width:11px; height:11px; border:2px solid #fff; border-radius:50%; background:var(--faculty-accent); box-shadow:0 0 0 1px color-mix(in srgb,var(--faculty-accent) 26%,#d5dae2); cursor:grab; }
/* Restore five faculties per row, keeping the two-row log within the stage width. */
.activity-log,.activity-entries { min-width:0; width:100%; max-width:100%; }
.activity-log { width:100%; max-width:100%; }
.activity-entries { display:grid; grid-template-columns:repeat(5,minmax(0,1fr)); gap:0 12px; }
.activity-entry { min-width:0; grid-template-columns:14px minmax(0,1fr) auto; gap:6px; }
.activity-name { min-width:0; overflow:hidden; text-overflow:ellipsis; white-space:nowrap; }
@media (max-width:760px) {
  .activity-log { width:100%; max-width:100%; }
  .activity-entries { grid-template-columns:repeat(5,minmax(0,1fr)); gap:0 7px; }
  .activity-entry { grid-template-columns:11px minmax(0,1fr) auto; gap:3px; padding:4px 0; font-size:7px; }
  .activity-name,.activity-num,.activity-gap { font-size:6px; }
  .activity-gap { display:block; }
}
/* The inspector starts directly with its comparator control after removing the topline. */
.inspector > .comparator-switcher { margin-top:0; }
/* Headline sizing follows its own available column, preventing wraps across layouts. */
.galaxy-head > div:first-child,.inspector,.projection-card,.section-heading,.impact,.watch-intro,.watch-item { container-type:inline-size; }
h1,h2,h3,.galaxy-title,.faculty-name,.projection-title,.model-name,.result-main,.watch-name { white-space:nowrap; }
.galaxy-title { font-size:clamp(10px,4.4cqw,49px); }
.faculty-name { font-size:clamp(8px,4.8cqw,39px); }
.projection-title { font-size:clamp(7px,3.6cqw,14px); }
.model-name { font-size:clamp(7px,3.4cqw,13px); }
.section-heading h2 { font-size:clamp(8px,3.3cqw,31px); }
.impact h3 { font-size:clamp(7px,3.5cqw,18px); }
.watch-intro h2 { font-size:clamp(8px,7cqw,22px); }
.watch-name { font-size:clamp(7px,4.5cqw,13px); }
@media (max-width:760px) {
  .galaxy-title { font-size:clamp(10px,4.4cqw,23px); }
  .faculty-name { font-size:clamp(8px,5cqw,18px); }
  .projection-title { font-size:clamp(7px,4cqw,10px); }
  .section-heading h2 { font-size:clamp(8px,3.3cqw,14px); }
  .impact h3 { font-size:clamp(7px,3.5cqw,9px); }
  .watch-intro h2 { font-size:clamp(8px,7cqw,12px); }
}
/* Desktop evidence rail: preserve the information hierarchy while reclaiming vertical space. */
@media (min-width:1100px) {
  .cosmos-layout { gap:clamp(12px,1.4vw,22px); }
  .right-rail { gap:0; padding-left:14px; overflow:hidden; }
  .right-rail .topbar { padding:1px 0 5px; }
  .right-rail .brand-mark { width:19px; height:19px; }
  .right-rail .brand-name { font-size:8px; }
  .right-rail .brand-sub { font-size:7px; }
  .right-rail .topmeta { gap:5px; }
  .right-rail .source-tag { max-width:140px; padding:4px 0; font-size:7px; }
  .right-rail .language-toggle { padding:4px 6px; font-size:8px; }
  .right-rail .metrics { margin:3px 0 0; }
  .right-rail .metric,.right-rail .metric:first-child { padding:5px 4px; }
  .right-rail .metric-label { font-size:7px; letter-spacing:0; line-height:1.15; }
  .right-rail .metric-value,.right-rail .metric:nth-child(1) .metric-value,.right-rail .metric:nth-child(2) .metric-value,.right-rail .metric:nth-child(3) .metric-value,.right-rail .metric:nth-child(4) .metric-value { margin-top:3px; font-size:clamp(15px,1.25vw,20px); }
  .right-rail .metric-foot { margin-top:2px; font-size:7px; line-height:1.15; }
  .right-rail .sidepanel { display:grid; grid-template-columns:minmax(0,1.08fr) minmax(0,.92fr); gap:12px; margin:0; align-items:start; }
  .right-rail .inspector,.right-rail .projection-card { min-width:0; padding:5px 0 6px; }
  .right-rail .comparator-switcher { grid-template-columns:1fr; gap:3px; margin:2px 0; padding:4px 0; }
  .right-rail .comparator-switcher label { font-size:7px; }
  .right-rail .comparator-switcher select { min-height:25px; padding:4px 5px; font-size:8px; }
  .right-rail .faculty-switcher { margin-top:3px; gap:3px; }
  .right-rail .faculty-switcher label { font-size:7px; }
  .right-rail .faculty-switcher select,.right-rail .faculty-switcher button { padding:4px; font-size:8px; }
  .right-rail .faculty-name { margin:5px 0 2px; font-size:clamp(15px,1.35vw,21px); line-height:1; }
  .right-rail .faculty-desc { font-size:8px; line-height:1.25; min-height:0; }
  .right-rail .status-row { margin:4px 0; gap:4px; }
  .right-rail .status-chip { padding:3px 4px; font-size:7px; }
  .right-rail .gap-label { font-size:7px; }
  .right-rail .compare { gap:5px; padding:5px 0; }
  .right-rail .compare-line { grid-template-columns:minmax(48px,.8fr) minmax(0,1fr) 27px; gap:4px; font-size:7px; }
  .right-rail .track { height:4px; }
  .right-rail .model-block { padding-top:4px; }
  .right-rail .small-label { font-size:7px; }
  .right-rail .model-name { margin-top:2px; font-size:9px; }
  .right-rail .model-source { margin-top:2px; font-size:7px; line-height:1.2; }
  .right-rail .reference-caveat { margin-top:4px; padding:4px 5px; font-size:7px; line-height:1.25; }
  .right-rail .everyday-meaning { margin-top:4px; padding-top:4px; }
  .right-rail .everyday-meaning strong { font-size:7px; }
  .right-rail .everyday-meaning p { margin-top:2px; font-size:7px; line-height:1.25; }
  .right-rail .source-inline { margin-top:3px; font-size:7px; }
  .right-rail .projection-title { font-size:9px; gap:3px; }
  .right-rail .projection-title .spark { font-size:11px; }
  .right-rail .projection-explain { margin:3px 0 5px; font-size:7px; line-height:1.25; }
  .right-rail .scenario-tabs { gap:3px; }
  .right-rail .scenario { min-height:25px; padding:4px 2px; font-size:7px; }
  .right-rail .horizon-line { margin-top:4px; font-size:7px; gap:4px; }
  .right-rail #horizon { margin:3px 0 0; height:12px; }
  .right-rail .range-labels { margin-top:0; font-size:7px; }
  .right-rail .scenario-result { margin-top:4px; padding-top:4px; }
  .right-rail .result-main { font-size:9px; }
  .right-rail .result-sub { margin-top:2px; font-size:7px; line-height:1.2; }
  .right-rail .calibration-strip { grid-template-columns:14px minmax(0,1fr) auto; gap:5px; margin:0; padding:5px 0; }
  .right-rail .calibration-mark { width:13px; height:13px; font-size:8px; }
  .right-rail .calibration-strip p { font-size:7px; line-height:1.25; }
  .right-rail .calibration-links { gap:3px; }
  .right-rail .calibration-strip a { font-size:7px; }
  .right-rail .impact-section { margin:2px 0 0; }
  .right-rail .section-heading { margin-bottom:2px; gap:4px; }
  .right-rail .section-heading h2,.right-rail .watch-intro h2 { font-size:11px; line-height:1.05; }
  .right-rail .section-heading p { max-width:48%; font-size:7px; line-height:1.2; }
  .right-rail .impact-grid { gap:4px; }
  .right-rail .impact,.right-rail .impact:first-child { padding:3px 4px 3px 0; }
  .right-rail .impact-kicker { font-size:6px; line-height:1.15; }
  .right-rail .impact h3 { margin:2px 0; font-size:8px; line-height:1.15; }
  .right-rail .impact p { font-size:7px; line-height:1.2; }
  .right-rail .watch-section { grid-template-columns:minmax(100px,.55fr) minmax(0,1.45fr); gap:8px; padding:5px 0; }
  .right-rail .watch-kicker { font-size:6px; }
  .right-rail .watch-intro h2 { margin:3px 0; font-size:10px; }
  .right-rail .watch-intro p { font-size:7px; line-height:1.2; }
  .right-rail .watch-list { gap:3px; }
  .right-rail .watch-item { padding:4px; }
  .right-rail .watch-name { font-size:7px; }
  .right-rail .watch-gap { margin-top:2px; font-size:6px; line-height:1.15; }
  .right-rail .watch-score { margin-top:3px; font-size:9px; }
  .right-rail .data-note { grid-template-columns:12px minmax(0,1fr) auto; gap:5px; margin:0; padding:4px 0; }
  .right-rail .note-icon { font-size:10px; }
  .right-rail .data-note p { font-size:7px; line-height:1.2; }
  .right-rail .data-links { gap:3px; }
  .right-rail .data-links a { font-size:7px; }
  .right-rail .footer { padding-top:4px; font-size:7px; line-height:1.2; }
}
@media (min-width:1100px) and (max-height:780px) {
  .shell { padding-top:3px; padding-bottom:3px; }
  .right-rail .topbar { padding-bottom:2px; }
  .right-rail .brand-sub { display:block; margin-top:1px; font-size:6px; }
  .right-rail .metric-foot { display:block; font-size:6px; line-height:1.05; }
  .right-rail .sidepanel { gap:4px; }
  .right-rail .faculty-desc { font-size:6px; line-height:1.1; }
  .right-rail .reference-caveat,.right-rail .everyday-meaning p { font-size:6px; line-height:1.1; }
  .right-rail .impact p { font-size:6px; line-height:1.1; }
  .right-rail .calibration-links { display:flex; flex-direction:row; flex-wrap:wrap; gap:2px 4px; }
  .right-rail .calibration-strip a { font-size:6px; }
  .right-rail .watch-intro p { display:block; font-size:6px; line-height:1.1; }
  .right-rail .data-note p { font-size:6px; line-height:1.1; }
  .right-rail .footer { display:flex; padding-top:2px; font-size:6px; line-height:1.1; }
}
/* Desktop rail rhythm: use the full height, move methodology ahead of detail, and make microcopy readable. */
@media (min-width:1100px) {
  .right-rail {
    display:grid;
    grid-template-columns:minmax(0,1fr);
    grid-template-rows:auto minmax(0,2.1fr) minmax(0,.55fr) minmax(0,.68fr) minmax(0,.42fr);
    grid-template-areas:"metrics" "detail" "impact" "watch" "data";
    align-content:stretch;
    justify-content:stretch;
    gap:0;
    padding-left:14px;
    overflow:hidden;
  }
  .right-rail > .metrics { grid-area:metrics; margin:0; }
  .right-rail > .sidepanel { grid-area:detail; display:grid; grid-template-columns:minmax(0,1.06fr) minmax(0,.94fr); gap:14px; margin:0; align-items:stretch; min-height:0; }
  .right-rail > .impact-section { grid-area:impact; margin:0; min-height:0; }
  .right-rail > .watch-section { grid-area:watch; min-height:0; }
  .right-rail > .data-note { grid-area:data; min-height:0; }
  .right-rail .topbar { padding:1px 0 6px; }
  .right-rail .brand-mark { width:20px; height:20px; }
  .right-rail .brand-name { font-size:9px; }
  .right-rail .brand-sub { font-size:7.5px; }
  .right-rail .source-tag { max-width:150px; padding:4px 0; font-size:8px; }
  .right-rail .language-toggle { padding:5px 7px; font-size:8.5px; }
  .right-rail .metrics { border-top:0; }
  .right-rail .metric,.right-rail .metric:first-child { padding:7px 5px; }
  .right-rail .metric-label { font-size:8px; line-height:1.2; }
  .right-rail .metric-value,.right-rail .metric:nth-child(1) .metric-value,.right-rail .metric:nth-child(2) .metric-value,.right-rail .metric:nth-child(3) .metric-value,.right-rail .metric:nth-child(4) .metric-value { margin-top:4px; font-size:clamp(18px,1.45vw,23px); }
  .right-rail .metric-foot { margin-top:3px; font-size:7.5px; line-height:1.25; }
  .right-rail .calibration-strip { height:100%; grid-template-columns:15px minmax(0,1fr) auto; align-content:center; gap:6px; margin:0; padding:6px 0; }
  .right-rail .calibration-mark { width:14px; height:14px; font-size:8px; }
  .right-rail .calibration-strip p { font-size:8.5px; line-height:1.3; }
  .right-rail .calibration-links { gap:4px; }
  .right-rail .calibration-strip a { font-size:7.5px; }
  .right-rail .inspector,.right-rail .projection-card { display:flex; flex-direction:column; justify-content:space-between; gap:4px; height:100%; min-height:0; padding:7px 0 9px; overflow:hidden; }
  .right-rail .comparator-switcher { width:100%; grid-template-columns:1fr; gap:4px; margin:0; padding:5px 0; }
  .right-rail .comparator-switcher label { font-size:8px; }
  .right-rail .comparator-switcher select { min-height:28px; padding:5px 6px; font-size:9px; }
  .right-rail .faculty-switcher { margin-top:4px; gap:4px; }
  .right-rail .faculty-switcher label { font-size:8px; }
  .right-rail .faculty-switcher select,.right-rail .faculty-switcher button { padding:5px; font-size:9px; }
  .right-rail .faculty-name { margin:5px 0 3px; font-size:clamp(16px,1.2vw,20px); line-height:1.05; }
  .right-rail .faculty-desc { font-size:9px; line-height:1.35; }
  .right-rail .status-row { margin:5px 0; gap:5px; }
  .right-rail .status-chip { padding:4px 5px; font-size:8px; }
  .right-rail .gap-label { font-size:8px; }
  .right-rail .compare { gap:7px; padding:7px 0; }
  .right-rail .compare-line { grid-template-columns:minmax(54px,.8fr) minmax(0,1fr) 30px; gap:5px; font-size:8px; }
  .right-rail .track { height:5px; }
  .right-rail .model-block { padding-top:5px; }
  .right-rail .small-label { font-size:8px; }
  .right-rail .model-name { margin-top:3px; font-size:10px; line-height:1.3; white-space:normal; }
  .right-rail .model-source { margin-top:3px; font-size:8px; line-height:1.3; }
  .right-rail .reference-caveat { margin-top:5px; padding:5px 6px; font-size:8px; line-height:1.3; }
  .right-rail .everyday-meaning { margin-top:5px; padding-top:5px; }
  .right-rail .everyday-meaning strong { font-size:8px; }
  .right-rail .everyday-meaning p { margin-top:3px; font-size:8px; line-height:1.3; }
  .right-rail .source-inline { margin-top:4px; font-size:7.5px; }
  .right-rail .projection-title { font-size:10px; gap:4px; }
  .right-rail .projection-title .spark { font-size:12px; }
  .right-rail .projection-explain { margin:4px 0 6px; font-size:8.5px; line-height:1.35; }
  .right-rail .scenario-tabs { gap:4px; }
  .right-rail .scenario { min-height:28px; padding:5px 3px; font-size:8px; }
  .right-rail .horizon-line { margin-top:5px; font-size:8.5px; gap:5px; }
  .right-rail #horizon { margin:4px 0 0; }
  .right-rail .range-labels { margin-top:1px; font-size:8px; }
  .right-rail .scenario-result { margin-top:6px; padding-top:6px; }
  .right-rail .result-main { font-size:11px; line-height:1.25; white-space:normal; }
  .right-rail .result-sub { margin-top:3px; font-size:8px; line-height:1.3; }
  .right-rail .impact-section { display:flex; flex-direction:column; justify-content:center; }
  .right-rail .section-heading { margin-bottom:4px; gap:6px; }
  .right-rail .section-heading h2 { font-size:13px; line-height:1.1; white-space:normal; }
  .right-rail .section-heading p { max-width:48%; font-size:8px; line-height:1.25; }
  .right-rail .impact-grid { flex:1; grid-template-columns:repeat(3,minmax(0,1fr)); align-content:center; gap:7px; }
  .right-rail .impact,.right-rail .impact:first-child { padding:6px 5px 6px 0; }
  .right-rail .impact-kicker { font-size:7px; line-height:1.2; }
  .right-rail .impact h3 { margin:4px 0 3px; font-size:9px; line-height:1.2; white-space:normal; }
  .right-rail .impact p { font-size:8px; line-height:1.3; display:block; overflow:visible; }
  .right-rail .watch-section { grid-template-columns:minmax(95px,.56fr) minmax(0,1.44fr); gap:9px; align-items:center; padding:6px 0; }
  .right-rail .watch-kicker { font-size:7px; }
  .right-rail .watch-intro h2 { margin:3px 0; font-size:12px; line-height:1.1; white-space:normal; }
  .right-rail .watch-intro p { display:block; font-size:8px; line-height:1.25; }
  .right-rail .watch-list { gap:4px; }
  .right-rail .watch-item { padding:5px; }
  .right-rail .watch-name { font-size:8px; white-space:normal; line-height:1.2; }
  .right-rail .watch-gap { margin-top:3px; font-size:7px; line-height:1.2; }
  .right-rail .watch-score { margin-top:4px; font-size:10px; }
  .right-rail .data-note { height:100%; grid-template-columns:13px minmax(0,1fr) auto; align-content:center; gap:5px; margin:0; padding:5px 0; }
  .right-rail .data-note p { font-size:8px; line-height:1.3; display:block; overflow:visible; }
  .right-rail .data-links { gap:4px; }
  .right-rail .data-links a { font-size:7.5px; }
  .right-rail .footer { padding-top:4px; font-size:7.5px; line-height:1.2; }
}
@media (min-width:1100px) and (max-height:780px) {
  .right-rail { grid-template-rows:auto minmax(0,2.05fr) minmax(0,.5fr) minmax(0,.58fr) minmax(0,.32fr); }
  .right-rail .brand-sub { display:block; font-size:7px; }
  .right-rail .metric-foot { display:block; font-size:7px; }
  .right-rail .faculty-desc,.right-rail .reference-caveat,.right-rail .everyday-meaning p,.right-rail .impact p,.right-rail .calibration-strip p,.right-rail .data-note p { font-size:7.5px; line-height:1.2; }
  .right-rail .inspector,.right-rail .projection-card { padding-top:4px; padding-bottom:5px; }
  .right-rail .compare { gap:5px; padding:5px 0; }
  .right-rail .scenario { min-height:25px; padding:4px 2px; }
  .right-rail .impact h3 { font-size:8px; }
  .right-rail .watch-section { padding:4px 0; }
  .right-rail .watch-intro p { font-size:7px; }
  .right-rail .data-note { padding:3px 0; }
}
/* Give each faculty score a clearer lane from its name. */
@media (min-width:761px) {
  .activity-entry { column-gap:8px; }
  .activity-gap { padding-left:6px; }
}
@media (max-width:760px) {
  .activity-entry { column-gap:3px; }
  .activity-gap { padding-left:2px; }
}
/* Give the active faculty control a clear, deliberate focal point. */
.right-rail .faculty-switcher {
  position:relative;
  gap:6px;
  margin-top:8px;
  padding:9px 9px 10px;
  border:1px solid color-mix(in srgb,var(--faculty-accent) 24%,#e3e7ee);
  border-left:3px solid var(--faculty-accent);
  background:linear-gradient(110deg,var(--faculty-accent-soft),rgba(255,255,255,.88));
  box-shadow:0 3px 12px rgba(23,33,52,.035);
}
.right-rail .faculty-switcher label {
  width:100%;
  color:var(--faculty-accent);
  font:700 8px/1.25 'Manrope', sans-serif;
  letter-spacing:.09em;
}
.right-rail .faculty-switcher select {
  min-height:31px;
  padding:6px 8px;
  border-color:color-mix(in srgb,var(--faculty-accent) 34%,#dfe4ec);
  background:#fff;
  color:#17191f;
  font:600 10px/1.25 'Manrope',Arial,sans-serif;
  box-shadow:inset 0 1px 0 rgba(255,255,255,.95);
}
.right-rail .faculty-switcher button {
  min-width:31px;
  min-height:31px;
  padding:5px 8px;
  border-color:color-mix(in srgb,var(--faculty-accent) 30%,#dfe4ec);
  background:var(--faculty-accent-soft);
  color:var(--faculty-accent);
  font-size:13px;
  font-weight:700;
  transition:background .16s ease,color .16s ease,border-color .16s ease,transform .16s ease;
}
.right-rail .faculty-switcher button:hover {
  background:var(--faculty-accent);
  color:#fff;
  border-color:var(--faculty-accent);
  transform:translateY(-1px);
}
.right-rail .faculty-switcher select:focus-visible,
.right-rail .faculty-switcher button:focus-visible {
  outline:2px solid var(--faculty-accent);
  outline-offset:2px;
}
@media (max-width:760px) {
  .right-rail .faculty-switcher { gap:4px; margin-top:5px; padding:5px 6px 6px; }
  .right-rail .faculty-switcher label { font-size:7px; }
  .right-rail .faculty-switcher select,.right-rail .faculty-switcher button { min-height:26px; padding:4px; font-size:8px; }
  .right-rail .faculty-switcher button { min-width:23px; }
}
/* Remove the galaxy strapline and reclaim its vertical space. */
.galaxy-head .galaxy-subtitle { display:none !important; }
@media (min-width:761px) {
  .galaxy-head { padding-top:8px; padding-bottom:6px; gap:12px; }
}
@media (max-width:760px) {
  .galaxy-head { padding-top:3px; padding-bottom:4px; gap:4px; }
}
/* Editorial headline: polished black ink, scaled without crowding the controls. */
.galaxy-title {
  color:#050608 !important;
  background:linear-gradient(180deg,#050506 0%,#252831 43%,#08090b 72%,#30333a 100%);
  background-clip:text;
  -webkit-background-clip:text;
  -webkit-text-fill-color:transparent;
  text-shadow:0 1px 0 rgba(255,255,255,.78),0 3px 9px rgba(14,18,27,.14);
  filter:drop-shadow(0 1px 1px rgba(12,15,22,.08));
  font-weight:700;
  letter-spacing:-.07em;
  line-height:1;
  white-space:normal;
  text-wrap:balance;
}
@media (min-width:761px) {
  .galaxy-head {
    grid-template-columns:minmax(0,1.08fr) minmax(0,.92fr);
    align-items:center;
    gap:18px;
  }
  .galaxy-title { font-size:clamp(29px,3.1vw,46px) !important; max-width:680px; }
}
@media (max-width:760px) {
  .galaxy-head { grid-template-columns:minmax(0,1fr); gap:7px; }
  .galaxy-title { font-size:clamp(24px,7vw,34px) !important; max-width:100%; line-height:.98; }
}
/* Use solid black ink for the headline while preserving its current scale. */
.galaxy-title {
  color:#000000 !important;
  background:none !important;
  -webkit-text-fill-color:#000000 !important;
  text-shadow:none !important;
  filter:none !important;
}
/* Make the comparison choice a clear, high-salience control in the evidence rail. */
.right-rail .comparator-switcher {
  position:relative;
  width:100%;
  gap:5px;
  margin:5px 0 7px;
  padding:8px 9px 9px;
  border:1px solid color-mix(in srgb,var(--faculty-accent) 25%,#e3e7ee);
  border-left:3px solid var(--faculty-accent);
  background:linear-gradient(105deg,var(--faculty-accent-soft),rgba(255,255,255,.98) 82%);
  box-shadow:0 3px 12px rgba(23,33,52,.045);
}
.right-rail .comparator-switcher label {
  display:flex;
  align-items:center;
  gap:7px;
  width:100%;
  color:var(--faculty-accent);
  font:700 8px/1.35 'Manrope', sans-serif;
  letter-spacing:.08em;
}
.right-rail .comparator-switcher label::before {
  content:"";
  width:6px;
  height:6px;
  flex:0 0 auto;
  border-radius:50%;
  background:var(--faculty-accent);
  box-shadow:0 0 0 3px var(--faculty-accent-soft);
}
.right-rail .comparator-switcher select {
  min-height:32px;
  padding:6px 8px;
  border:1px solid color-mix(in srgb,var(--faculty-accent) 32%,#d5dae3);
  border-radius:3px;
  background:#fff;
  color:#111216;
  font:700 10px/1.3 'Manrope',Arial,sans-serif;
  box-shadow:inset 0 1px 0 #fff,0 1px 3px rgba(23,33,52,.04);
  transition:border-color .16s ease,box-shadow .16s ease;
}
.right-rail .comparator-switcher select:hover {
  border-color:var(--faculty-accent);
}
.right-rail .comparator-switcher select:focus-visible {
  outline:2px solid var(--faculty-accent);
  outline-offset:2px;
  box-shadow:0 0 0 4px var(--faculty-accent-soft);
}
.right-rail .comparator-switcher select option {
  color:#111216;
  background:#fff;
}
@media (max-width:760px) {
  .right-rail .comparator-switcher {
    gap:4px;
    margin:4px 0 5px;
    padding:5px 6px 6px;
  }
  .right-rail .comparator-switcher label { font-size:7px; }
  .right-rail .comparator-switcher select { min-height:27px; padding:4px 6px; font-size:8px; }
}
/* Increase text contrast across the evidence rail without changing typography or layout. */
.right-rail { color:#111216; }
.right-rail :is(.brand-name,.faculty-name,.model-name,.result-main,.projection-title,.section-heading h2,.watch-intro h2,.impact h3,.data-note strong,.footer-brand,.score,.watch-name,.metric-value,.comparator-switcher select,.faculty-switcher select) {
  color:#111216 !important;
  opacity:1 !important;
}
.right-rail :is(.brand-sub,.metric-label,.metric-foot,.panel-topline,.small-label,.faculty-desc,.gap-label,.compare-line .who,.model-source,.reference-caveat,.everyday-meaning p,.projection-explain,.result-sub,.calibration-strip p,.section-heading p,.impact-kicker,.impact p,.watch-intro p,.watch-gap,.data-note p,.footer) {
  color:#292d35 !important;
  opacity:1 !important;
}
.right-rail :is(.comparator-switcher label,.faculty-switcher label) { opacity:1 !important; }
/* Keep orbit status immediately above-left of the zoom controls. */
@media (min-width:761px) {
  .stage-actions {
    display:grid;
    grid-template-columns:minmax(0,1fr) auto;
    grid-template-areas:"views views" "zoom zoom";
    align-items:center;
    justify-content:stretch;
    gap:3px 8px;
    width:100%;
  }
  .view-controls {
    grid-area:views;
    display:flex;
    align-items:center;
    justify-content:flex-end;
    flex-wrap:wrap;
    gap:5px;
    min-width:0;
  }
  .zoom-controls {
    grid-area:zoom;
    display:flex;
    min-width:0;
    align-items:center;
    justify-content:flex-end;
    flex-wrap:wrap;
    gap:4px;
  }
  .galaxy-head { padding-top:5px; padding-bottom:3px; gap:12px; }
  .activity-log { margin-bottom:5px; }
}
@media (max-width:760px) {
  .stage-actions { display:flex; flex-direction:column; align-items:flex-end; gap:4px; }
  .view-controls { display:flex; flex-direction:column; align-items:flex-end; gap:4px; min-width:0; max-width:100%; }
  .zoom-controls { display:flex; align-items:center; justify-content:flex-end; flex-wrap:wrap; gap:3px; max-width:100%; }
}
/* Keep the source note available to the script, but remove it from the visible layout. */
.right-rail .model-source { display:none !important; }
.right-rail .reference-caveat { margin-top:3px; }
/* One shared faculty-control panel with two clearly separated solid-tint sections. */
.right-rail .selection-switchers {
  display:flex;
  flex-direction:column;
  gap:7px;
  width:100%;
  margin:2px 0 6px;
  padding:8px 9px;
  border:1px solid color-mix(in srgb,var(--faculty-accent) 24%,#e3e7ee);
  border-left:3px solid color-mix(in srgb,var(--faculty-accent) 58%,#fff);
  border-radius:4px;
  background:var(--faculty-accent-soft);
  box-shadow:none;
}
.right-rail .selection-switchers .comparator-switcher,
.right-rail .selection-switchers .faculty-switcher {
  display:flex;
  flex-direction:column;
  align-items:stretch;
  gap:4px;
  width:100%;
  margin:0;
  padding:0;
  border:0;
  border-radius:0;
  background:transparent;
  box-shadow:none;
}
.right-rail .selection-switchers .comparator-switcher {
  padding-bottom:7px;
  border-bottom:1px solid color-mix(in srgb,var(--faculty-accent) 22%,#fff);
}
.right-rail .selection-switchers :is(.comparator-switcher label,.faculty-switcher label) {
  display:flex;
  align-items:center;
  gap:6px;
  width:100%;
  margin:0;
  color:color-mix(in srgb,var(--faculty-accent) 82%,#17191f);
  font:700 8px/1.3 'Manrope', sans-serif;
  letter-spacing:.055em;
}
.right-rail .selection-switchers .faculty-switcher label::before {
  content:"";
  width:6px;
  height:6px;
  flex:0 0 auto;
  border-radius:50%;
  background:var(--faculty-accent);
}
.right-rail .selection-switchers :is(.comparator-switcher select,.faculty-switcher select) {
  width:100%;
  min-width:0;
  min-height:28px;
  padding:5px 7px;
  border:1px solid color-mix(in srgb,var(--faculty-accent) 25%,#dfe4ec);
  border-radius:3px;
  background:#fff;
  color:#17191f;
  font:600 9px/1.25 'Manrope',Arial,sans-serif;
  text-align:left;
  box-shadow:none;
}
.right-rail .selection-switchers .faculty-switcher {
  display:grid;
  grid-template-columns:minmax(0,1fr) auto auto;
  gap:4px;
}
.right-rail .selection-switchers .faculty-switcher label { grid-column:1/-1; }
.right-rail .selection-switchers .faculty-switcher select { grid-column:1; }
.right-rail .selection-switchers .faculty-switcher button {
  min-width:27px;
  min-height:28px;
  padding:4px 6px;
  border:1px solid color-mix(in srgb,var(--faculty-accent) 26%,#dfe4ec);
  border-radius:3px;
  background:#fff;
  color:var(--faculty-accent);
  font-size:12px;
  box-shadow:none;
}
.right-rail .selection-switchers .faculty-switcher button:hover {
  color:#fff;
  background:var(--faculty-accent);
  border-color:var(--faculty-accent);
  transform:none;
}
.right-rail .selection-switchers select:focus-visible,
.right-rail .selection-switchers button:focus-visible {
  outline:2px solid var(--faculty-accent);
  outline-offset:2px;
}
@media (min-width:1100px) {
  .right-rail .selection-switchers { gap:6px; margin:1px 0 5px; padding:7px 8px; }
  .right-rail .selection-switchers .comparator-switcher { padding-bottom:6px; }
  .right-rail .selection-switchers :is(.comparator-switcher label,.faculty-switcher label) { font-size:7.5px; }
  .right-rail .selection-switchers :is(.comparator-switcher select,.faculty-switcher select) { min-height:26px; padding:4px 6px; font-size:8.5px; }
  .right-rail .selection-switchers .faculty-switcher button { min-width:25px; min-height:26px; padding:3px 5px; font-size:11px; }
}
@media (max-width:760px) {
  .right-rail .selection-switchers { gap:5px; margin:1px 0 4px; padding:5px 6px; }
  .right-rail .selection-switchers .comparator-switcher { padding-bottom:5px; }
  .right-rail .selection-switchers :is(.comparator-switcher label,.faculty-switcher label) { font-size:6.5px; }
  .right-rail .selection-switchers :is(.comparator-switcher select,.faculty-switcher select) { min-height:24px; padding:3px 4px; font-size:7.5px; }
  .right-rail .selection-switchers .faculty-switcher button { min-width:20px; min-height:24px; padding:3px; font-size:9px; }
}
/* Method note sits inside the future panel, with links beside its copy and a consistent rhythm. */
@media (min-width:761px) {
  .right-rail .projection-card { justify-content:flex-start; gap:0; }
  .right-rail .projection-card > .calibration-strip {
    display:grid;
    grid-template-columns:13px minmax(0,1fr) auto;
    align-items:start;
    gap:6px;
    flex:0 0 auto;
    height:auto;
    margin:0 0 9px;
    padding:0 0 8px;
    border:0;
    border-bottom:1px solid #e3e7ee;
    border-radius:0;
    background:transparent;
  }
  .right-rail .projection-card > .calibration-strip .calibration-mark { width:13px; height:13px; margin-top:1px; font-size:8px; }
  .right-rail .projection-card > .calibration-strip p { min-width:0; margin:0; color:#454954; font-size:8px; line-height:1.3; }
  .right-rail .projection-card > .calibration-strip .calibration-links { display:flex; flex-direction:column; align-items:flex-end; gap:4px; min-width:0; white-space:nowrap; }
  .right-rail .projection-card > .calibration-strip .calibration-links a { font-size:7px; line-height:1.25; }
  .right-rail .projection-title { margin-top:0; }
  .right-rail .projection-explain { margin:4px 0 7px; }
  .right-rail .scenario-tabs { margin-top:0; }
  .right-rail .horizon-line { margin-top:8px; }
  .right-rail .scenario-result { margin-top:7px; padding-top:7px; }
}
@media (min-width:1100px) {
  .right-rail .projection-card > .calibration-strip { grid-template-columns:12px minmax(0,1fr) auto; gap:5px; margin-bottom:7px; padding-bottom:6px; }
  .right-rail .projection-card > .calibration-strip p { font-size:7.5px; line-height:1.25; }
  .right-rail .projection-card > .calibration-strip .calibration-links { gap:3px; }
  .right-rail .projection-card > .calibration-strip .calibration-links a { font-size:6.5px; }
}
@media (max-width:760px) {
  .right-rail .projection-card { gap:3px; }
  .right-rail .projection-card > .calibration-strip { display:none; }
}
/* Pair the practical takeaway with its caveat, using a shared two-column row. */
@media (min-width:1100px) {
  .right-rail .model-block {
    display:grid;
    grid-template-columns:minmax(0,1fr) minmax(0,1fr);
    column-gap:12px;
    row-gap:3px;
    align-items:start;
  }
  .right-rail .model-block > .small-label,
  .right-rail .model-block > .model-name,
  .right-rail .model-block > .model-source,
  .right-rail .model-block > .source-inline { grid-column:1 / -1; }
  .right-rail .model-block > .reference-caveat { grid-column:1; align-self:stretch; margin-top:4px; }
  .right-rail .model-block > .everyday-meaning {
    grid-column:2;
    align-self:stretch;
    min-width:0;
    margin-top:4px;
    padding:4px 0 0 10px;
    border-top:0;
    border-left:1px solid #e4e8ef;
  }
  .right-rail .model-block > .everyday-meaning p { margin-top:3px; }
}
@media (min-width:1100px) and (max-height:780px) {
  .right-rail .model-block { column-gap:8px; row-gap:2px; }
  .right-rail .model-block > .everyday-meaning { padding-left:7px; }
}
/* Keep the winning result beside its comparison; place both selectors below today's scenario readout. */
.right-rail .projection-card > .selection-switchers {
  flex:0 0 auto;
  width:100%;
  max-width:none;
  margin:7px 0 0;
  padding:6px 7px;
  gap:5px;
}
.right-rail .projection-card > .selection-switchers .comparator-switcher {
  display:flex;
  flex-direction:column;
  align-items:stretch;
  gap:3px;
  padding-bottom:5px;
}
.right-rail .projection-card > .selection-switchers .faculty-switcher {
  display:grid;
  grid-template-columns:minmax(0,1fr) auto auto;
  align-items:center;
  gap:4px;
  margin:0;
}
.right-rail .projection-card > .selection-switchers .faculty-switcher label { grid-column:1/-1; }
.right-rail .projection-card > .selection-switchers :is(.comparator-switcher select,.faculty-switcher select) { min-height:26px; padding:4px 6px; font-size:8.5px; }
.right-rail .projection-card > .selection-switchers .faculty-switcher button { min-width:25px; min-height:26px; padding:3px 5px; font-size:11px; }
@media (min-width:1100px) and (max-height:780px) {
  .right-rail .projection-card > .selection-switchers { margin-top:4px; padding:4px 5px; gap:3px; }
  .right-rail .projection-card > .selection-switchers .comparator-switcher { padding-bottom:3px; }
  .right-rail .projection-card > .selection-switchers :is(.comparator-switcher label,.faculty-switcher label) { font-size:6.5px; }
  .right-rail .projection-card > .selection-switchers :is(.comparator-switcher select,.faculty-switcher select) { min-height:22px; padding:3px 4px; font-size:7px; }
  .right-rail .projection-card > .selection-switchers .faculty-switcher button { min-width:21px; min-height:22px; padding:2px; font-size:9px; }
}
/* Slightly larger rail typography, with tighter rhythms between related controls. */
@media (min-width:761px) {
  .right-rail .brand-name { font-size:9.5px; }
  .right-rail .source-tag { font-size:8.5px; }
  .right-rail .language-toggle { font-size:9px; }
  .right-rail .metric-label { font-size:8.5px; line-height:1.2; }
  .right-rail .metric-value,.right-rail .metric:nth-child(1) .metric-value,.right-rail .metric:nth-child(2) .metric-value,.right-rail .metric:nth-child(3) .metric-value,.right-rail .metric:nth-child(4) .metric-value { font-size:clamp(19px,1.5vw,24px); }
  .right-rail .metric-foot { font-size:8px; line-height:1.3; }
  .right-rail .sidepanel { column-gap:12px; }
  .right-rail .inspector,.right-rail .projection-card { gap:5px; justify-content:flex-start; }
  .right-rail .panel-topline,.right-rail .small-label { font-size:8.5px; }
  .right-rail .selection-switchers { gap:5px; padding:7px 8px; }
  .right-rail .selection-switchers .comparator-switcher { padding-bottom:5px; }
  .right-rail .selection-switchers :is(.comparator-switcher label,.faculty-switcher label) { font-size:8px; }
  .right-rail .selection-switchers :is(.comparator-switcher select,.faculty-switcher select) { min-height:27px; padding:4px 6px; font-size:9px; }
  .right-rail .selection-switchers .faculty-switcher button { min-width:26px; min-height:27px; font-size:11.5px; }
  .right-rail .faculty-name { font-size:clamp(17px,1.3vw,22px); margin:5px 0 3px; }
  .right-rail .faculty-desc { font-size:9.5px; line-height:1.35; }
  .right-rail .status-row { margin:4px 0; gap:5px; }
  .right-rail .status-chip { font-size:8.5px; }
  .right-rail .gap-label { font-size:8.5px; }
  .right-rail .compare { gap:6px; padding:6px 0; }
  .right-rail .compare-line { grid-template-columns:minmax(56px,.8fr) minmax(0,1fr) 29px; gap:5px; font-size:8.5px; }
  .right-rail .model-block { padding-top:4px; }
  .right-rail .model-block > .small-label { font-size:8px; }
  .right-rail .model-name { font-size:10.5px; line-height:1.3; }
  .right-rail .reference-caveat { margin-top:3px; padding:5px 6px; font-size:8px; line-height:1.3; }
  .right-rail .everyday-meaning { margin-top:3px; padding-top:4px; }
  .right-rail .everyday-meaning strong { font-size:8px; }
  .right-rail .everyday-meaning p { margin-top:3px; font-size:8px; line-height:1.3; }
  .right-rail .source-inline { margin-top:3px; font-size:8px; }
  .right-rail .projection-card > .calibration-strip { gap:5px; margin-bottom:5px; padding-bottom:5px; }
  .right-rail .projection-card > .calibration-strip p { font-size:8px; line-height:1.3; }
  .right-rail .projection-card > .calibration-strip .calibration-links a { font-size:7px; }
  .right-rail .projection-title { font-size:10.5px; }
  .right-rail .projection-explain { margin:3px 0 5px; font-size:8.5px; line-height:1.35; }
  .right-rail .scenario { min-height:26px; padding:5px 3px; font-size:8.5px; }
  .right-rail .horizon-line { margin-top:5px; font-size:9px; }
  .right-rail .range-labels { font-size:8px; }
  .right-rail .scenario-result { margin-top:5px; padding-top:5px; }
  .right-rail .result-main { font-size:11px; }
  .right-rail .result-sub { margin-top:2px; font-size:8px; line-height:1.3; }
  .right-rail .calibration-strip p { font-size:8px; line-height:1.3; }
  .right-rail .calibration-strip a { font-size:7.5px; }
  .right-rail .impact-section { margin-top:3px; }
  .right-rail .section-heading { gap:5px; margin-bottom:4px; }
  .right-rail .section-heading h2 { font-size:13.5px; }
  .right-rail .section-heading p { font-size:8px; line-height:1.3; }
  .right-rail .impact-grid { gap:5px; }
  .right-rail .impact,.right-rail .impact:first-child { padding:5px 5px 5px 0; }
  .right-rail .impact-kicker { font-size:7px; }
  .right-rail .impact h3 { margin:3px 0; font-size:9px; line-height:1.25; }
  .right-rail .impact p { font-size:8px; line-height:1.3; }
  .right-rail .watch-section { gap:7px; padding:5px 0; }
  .right-rail .watch-kicker { font-size:7px; }
  .right-rail .watch-intro h2 { margin:3px 0; font-size:12px; }
  .right-rail .watch-intro p { font-size:8px; line-height:1.3; }
  .right-rail .watch-list { gap:4px; }
  .right-rail .watch-item { padding:5px; }
  .right-rail .watch-name { font-size:8px; line-height:1.25; }
  .right-rail .watch-gap { margin-top:3px; font-size:7px; line-height:1.25; }
  .right-rail .watch-score { margin-top:4px; font-size:10px; }
  .right-rail .data-note { gap:5px; padding:5px 0; }
  .right-rail .note-icon { font-size:11px; }
  .right-rail .data-note p { font-size:8px; line-height:1.3; }
  .right-rail .data-links { gap:4px; }
  .right-rail .data-links a { font-size:7.5px; }
}
@media (min-width:1100px) and (max-height:780px) {
  .right-rail .inspector,.right-rail .projection-card { gap:3px; }
  .right-rail .metric-label { font-size:8px; }
  .right-rail .metric-value,.right-rail .metric:nth-child(1) .metric-value,.right-rail .metric:nth-child(2) .metric-value,.right-rail .metric:nth-child(3) .metric-value,.right-rail .metric:nth-child(4) .metric-value { font-size:clamp(17px,1.35vw,21px); }
  .right-rail .faculty-desc,.right-rail .reference-caveat,.right-rail .everyday-meaning p,.right-rail .impact p,.right-rail .calibration-strip p,.right-rail .data-note p { font-size:7.5px; line-height:1.2; }
  .right-rail .impact h3 { font-size:8.5px; }
  .right-rail .watch-intro p { font-size:7.5px; }
}
/* Reduce the desktop gap below the selected-faculty content without clipping its copy. */
@media (min-width:761px) {
  .right-rail .sidepanel { column-gap:10px; margin-bottom:0; }
  .right-rail .inspector,.right-rail .projection-card {
    min-height:0;
    height:auto;
    padding-top:5px;
    padding-bottom:3px;
    gap:3px;
    overflow:visible;
  }
  .right-rail .faculty-name { margin-top:4px; margin-bottom:2px; }
  .right-rail .status-row { margin-top:3px; margin-bottom:3px; }
  .right-rail .compare { padding-top:5px; padding-bottom:5px; gap:5px; }
  .right-rail .model-block { padding-top:3px; row-gap:2px; }
  .right-rail .reference-caveat { margin-top:2px; padding-top:4px; padding-bottom:4px; }
  .right-rail .everyday-meaning { margin-top:2px; padding-top:3px; }
  .right-rail .projection-card > .calibration-strip { margin-bottom:4px; padding-bottom:4px; }
  .right-rail .projection-explain { margin-top:2px; margin-bottom:4px; }
  .right-rail .horizon-line { margin-top:4px; }
  .right-rail .scenario-result { margin-top:4px; padding-top:4px; }
}
/* Slightly open the desktop inspector rhythm and scale its type as one system. */
@media (min-width:761px) {
  .right-rail .sidepanel { column-gap:12px; }
  .right-rail .inspector,.right-rail .projection-card { gap:4px; }
  .right-rail .panel-topline,.right-rail .small-label { font-size:9px; }
  .right-rail .selection-switchers { gap:6px; padding:7px 8px; }
  .right-rail .selection-switchers .comparator-switcher { padding-bottom:6px; }
  .right-rail .selection-switchers :is(.comparator-switcher label,.faculty-switcher label) { font-size:8.5px; }
  .right-rail .selection-switchers :is(.comparator-switcher select,.faculty-switcher select) { min-height:28px; padding:4px 6px; font-size:9.5px; }
  .right-rail .selection-switchers .faculty-switcher button { min-width:27px; min-height:28px; font-size:12px; }
  .right-rail .faculty-name { font-size:clamp(18px,1.35vw,23px); margin:6px 0 3px; }
  .right-rail .faculty-desc { font-size:10px; line-height:1.4; }
  .right-rail .status-row { margin:5px 0; gap:6px; }
  .right-rail .status-chip,.right-rail .gap-label { font-size:9px; }
  .right-rail .compare { gap:7px; padding:7px 0; }
  .right-rail .compare-line { grid-template-columns:minmax(58px,.8fr) minmax(0,1fr) 30px; gap:5px; font-size:9px; }
  .right-rail .model-block { padding-top:5px; row-gap:3px; }
  .right-rail .model-block > .small-label { font-size:8.5px; }
  .right-rail .model-name { font-size:11px; line-height:1.35; }
  .right-rail .reference-caveat { margin-top:4px; padding:5px 6px; font-size:8.5px; line-height:1.35; }
  .right-rail .everyday-meaning { margin-top:4px; padding-top:5px; }
  .right-rail .everyday-meaning strong { font-size:8.5px; }
  .right-rail .everyday-meaning p { margin-top:3px; font-size:8.5px; line-height:1.35; }
  .right-rail .source-inline { margin-top:4px; font-size:8.5px; }
  .right-rail .projection-title { font-size:11px; }
  .right-rail .projection-explain { margin:4px 0 6px; font-size:9px; line-height:1.4; }
  .right-rail .scenario { min-height:27px; padding:5px 3px; font-size:9px; }
  .right-rail .horizon-line { margin-top:6px; font-size:9.5px; }
  .right-rail .range-labels { font-size:8.5px; }
  .right-rail .scenario-result { margin-top:6px; padding-top:6px; }
  .right-rail .result-main { font-size:11.5px; }
  .right-rail .result-sub { margin-top:3px; font-size:8.5px; line-height:1.35; }
  .right-rail .projection-card > .calibration-strip { gap:6px; margin-bottom:6px; padding-bottom:6px; }
  .right-rail .projection-card > .calibration-strip p { font-size:8.5px; line-height:1.35; }
  .right-rail .projection-card > .calibration-strip .calibration-links a { font-size:7.5px; }
}
@media (min-width:1100px) and (max-height:780px) {
  .right-rail .inspector,.right-rail .projection-card { gap:3px; }
  .right-rail .faculty-name { font-size:clamp(17px,1.3vw,22px); }
  .right-rail .faculty-desc { font-size:8px; line-height:1.25; }
  .right-rail .compare { gap:5px; padding:5px 0; }
  .right-rail .compare-line { font-size:8px; }
  .right-rail .model-block { row-gap:2px; }
  .right-rail .model-name { font-size:10px; }
  .right-rail .reference-caveat,.right-rail .everyday-meaning p { font-size:7.5px; line-height:1.2; }
  .right-rail .projection-title { font-size:9.5px; }
  .right-rail .projection-explain,.right-rail .result-sub { font-size:7.5px; line-height:1.2; }
  .right-rail .scenario { min-height:25px; padding:4px 2px; font-size:8px; }
  .right-rail .scenario-result { margin-top:4px; padding-top:4px; }
}
/* Keep the five-by-two observation log legible; highlight only the chosen faculty with its own solid tint. */
@media (min-width:761px) {
  .activity-entries { grid-template-columns:repeat(5,minmax(0,1fr)); column-gap:8px; }
  .activity-entry { grid-template-columns:18px minmax(0,1fr) auto; gap:4px; padding:6px 4px; font-size:10px; }
  .activity-name,.activity-num,.activity-gap { font-size:10px; }
  .activity-entry[aria-current="true"] { padding-left:8px; padding-right:6px; color:#17191f; background:var(--faculty-accent-soft); box-shadow:inset 2px 0 0 var(--faculty-accent); }
  .activity-entry[aria-current="true"] .activity-name { color:#17191f; text-decoration-color:var(--faculty-accent); }
  .activity-entry[aria-current="true"] .activity-num,.activity-entry[aria-current="true"] .activity-gap { color:var(--faculty-accent); }
}
/* Slightly enlarge every rail level while reclaiming spacing to keep desktop content on-screen. */
@media (min-width:1100px) {
  .right-rail { gap:0; }
  .right-rail .metric-label { font-size:9px; line-height:1.2; }
  .right-rail .metric-value,.right-rail .metric:nth-child(1) .metric-value,.right-rail .metric:nth-child(2) .metric-value,.right-rail .metric:nth-child(3) .metric-value,.right-rail .metric:nth-child(4) .metric-value { font-size:clamp(19px,1.5vw,24px); }
  .right-rail .metric-foot { font-size:8.5px; line-height:1.25; }
  .right-rail .sidepanel { column-gap:10px; }
  .right-rail .inspector,.right-rail .projection-card { gap:3px; padding-top:4px; padding-bottom:4px; }
  .right-rail .selection-switchers { gap:5px; padding:6px 7px; }
  .right-rail .selection-switchers .comparator-switcher { padding-bottom:5px; }
  .right-rail .selection-switchers :is(.comparator-switcher label,.faculty-switcher label) { font-size:8.5px; }
  .right-rail .selection-switchers :is(.comparator-switcher select,.faculty-switcher select) { min-height:27px; padding:4px 6px; font-size:9.5px; }
  .right-rail .selection-switchers .faculty-switcher button { min-width:26px; min-height:27px; padding:3px 5px; font-size:12px; }
  .right-rail .faculty-name { font-size:clamp(18px,1.4vw,24px); margin:5px 0 3px; }
  .right-rail .faculty-desc { font-size:10px; line-height:1.3; }
  .right-rail .status-row { margin:4px 0; }
  .right-rail .status-chip,.right-rail .gap-label { font-size:9px; }
  .right-rail .compare { gap:6px; padding:6px 0; }
  .right-rail .compare-line { font-size:9px; }
  .right-rail .model-block { padding-top:4px; row-gap:2px; }
  .right-rail .model-block > .small-label { font-size:8.5px; }
  .right-rail .model-name { font-size:11px; line-height:1.3; }
  .right-rail .reference-caveat { margin-top:3px; padding:4px 5px; font-size:8.5px; line-height:1.3; }
  .right-rail .everyday-meaning { margin-top:3px; padding-top:4px; }
  .right-rail .everyday-meaning strong { font-size:8.5px; }
  .right-rail .everyday-meaning p { margin-top:3px; font-size:8.5px; line-height:1.3; }
  .right-rail .projection-card > .calibration-strip { margin-bottom:4px; padding-bottom:4px; }
  .right-rail .projection-card > .calibration-strip p { font-size:8.5px; line-height:1.3; }
  .right-rail .projection-card > .calibration-strip .calibration-links a { font-size:7.5px; }
  .right-rail .projection-title { font-size:11px; }
  .right-rail .projection-explain { margin:3px 0 5px; font-size:9px; line-height:1.3; }
  .right-rail .scenario { min-height:26px; padding:4px 3px; font-size:8.5px; }
  .right-rail .horizon-line { margin-top:4px; font-size:9px; }
  .right-rail .range-labels { font-size:8px; }
  .right-rail .scenario-result { margin-top:4px; padding-top:4px; }
  .right-rail .result-main { font-size:11.5px; line-height:1.2; }
  .right-rail .result-sub { font-size:8.5px; line-height:1.25; }
  .right-rail .calibration-strip p { font-size:8.5px; line-height:1.3; }
  .right-rail .impact-section { margin-top:2px; }
  .right-rail .section-heading { margin-bottom:3px; gap:5px; }
  .right-rail .section-heading h2 { font-size:14px; }
  .right-rail .section-heading p { font-size:8.5px; line-height:1.25; }
  .right-rail .impact-grid { gap:4px; }
  .right-rail .impact,.right-rail .impact:first-child { padding:4px 4px 4px 0; }
  .right-rail .impact-kicker { font-size:7.5px; line-height:1.2; }
  .right-rail .impact h3 { margin:3px 0; font-size:9.5px; line-height:1.2; }
  .right-rail .impact p { font-size:8.5px; line-height:1.25; }
  .right-rail .watch-section { padding:4px 0; gap:5px; }
  .right-rail .watch-kicker { font-size:7.5px; }
  .right-rail .watch-intro h2 { margin:2px 0; font-size:12.5px; }
  .right-rail .watch-intro p { font-size:8.5px; line-height:1.25; }
  .right-rail .watch-list { gap:3px; }
  .right-rail .watch-item { padding:4px; }
  .right-rail .watch-name { font-size:8.5px; line-height:1.2; }
  .right-rail .watch-gap { font-size:7.5px; line-height:1.2; }
  .right-rail .watch-score { margin-top:3px; font-size:10.5px; }
  .right-rail .data-note { padding:4px 0; gap:4px; }
  .right-rail .note-icon { font-size:11px; }
  .right-rail .data-note p { font-size:8.5px; line-height:1.25; }
  .right-rail .data-links a { font-size:8px; }
}
@media (min-width:1100px) and (max-height:780px) {
  .right-rail .metric-label { font-size:8.5px; }
  .right-rail .metric-value,.right-rail .metric:nth-child(1) .metric-value,.right-rail .metric:nth-child(2) .metric-value,.right-rail .metric:nth-child(3) .metric-value,.right-rail .metric:nth-child(4) .metric-value { font-size:clamp(18px,1.4vw,22px); }
  .right-rail .metric-foot { font-size:7.5px; }
  .right-rail .inspector,.right-rail .projection-card { gap:2px; padding-top:3px; padding-bottom:3px; }
  .right-rail .faculty-name { font-size:clamp(17px,1.3vw,22px); }
  .right-rail .faculty-desc,.right-rail .reference-caveat,.right-rail .everyday-meaning p,.right-rail .projection-explain,.right-rail .result-sub,.right-rail .impact p,.right-rail .watch-intro p,.right-rail .data-note p,.right-rail .calibration-strip p { font-size:8px; line-height:1.2; }
  .right-rail .selection-switchers { gap:3px; padding:4px 5px; }
  .right-rail .selection-switchers .comparator-switcher { padding-bottom:3px; }
  .right-rail .selection-switchers :is(.comparator-switcher select,.faculty-switcher select) { min-height:23px; padding:3px 4px; font-size:8px; }
  .right-rail .selection-switchers .faculty-switcher button { min-height:23px; min-width:22px; padding:2px; font-size:10px; }
  .right-rail .compare { gap:4px; padding:4px 0; }
  .right-rail .scenario { min-height:24px; padding:3px 2px; font-size:8px; }
  .right-rail .impact-section { margin-top:1px; }
  .right-rail .impact h3 { font-size:8.5px; }
  .right-rail .watch-section { padding:3px 0; gap:3px; }
  .right-rail .watch-intro h2 { font-size:11.5px; }
  .right-rail .watch-name { font-size:8px; }
  .right-rail .watch-score { font-size:10px; }
  .right-rail .data-note { padding:3px 0; }
}
/* Full-height desktop: add deliberate breathing room between each inspector section. */
@media (min-width:1100px) and (min-height:900px) {
  .right-rail .inspector,
  .right-rail .projection-card {
    gap:6px;
    padding-top:6px;
    padding-bottom:6px;
  }
  .right-rail .faculty-name { margin-top:7px; margin-bottom:4px; }
  .right-rail .status-row { margin-top:6px; margin-bottom:6px; }
  .right-rail .compare { gap:8px; padding-top:8px; padding-bottom:8px; }
  .right-rail .model-block { padding-top:6px; row-gap:4px; }
  .right-rail .model-block > .reference-caveat,
  .right-rail .model-block > .everyday-meaning { margin-top:5px; }
  .right-rail .projection-card > .calibration-strip { margin-bottom:7px; padding-bottom:7px; }
  .right-rail .projection-explain { margin-top:5px; margin-bottom:7px; }
  .right-rail .horizon-line { margin-top:7px; }
  .right-rail .scenario-result { margin-top:7px; padding-top:7px; }
  .right-rail .projection-card > .selection-switchers { margin-top:8px; }
}
/* Give the methodology note more vertical breathing room while preserving the full future controls. */
@media (min-width:761px) {
  .right-rail .projection-card > .calibration-strip { margin-bottom:9px; padding-top:2px; padding-bottom:8px; }
  .right-rail .projection-explain { margin:2px 0 4px; }
  .right-rail .scenario-result { margin-top:4px; padding-top:4px; }
}
@media (min-width:1100px) and (max-height:780px) {
  .right-rail .projection-card > .calibration-strip { margin-bottom:6px; padding-top:1px; padding-bottom:6px; }
  .right-rail .projection-explain { margin:2px 0 4px; }
  .right-rail .scenario-result { margin-top:2px; padding-top:2px; }
}
/* User-adjustable desktop evidence rail. Grips preserve the overall rail size. */
.right-rail .rail-layout-tools { display:none; }
@media (min-width:1100px) {
  .right-rail { position:relative; padding-top:30px; }
  .right-rail .rail-layout-tools {
    position:absolute; z-index:60; top:0; right:0; left:14px;
    display:flex; align-items:center; justify-content:flex-end; gap:6px;
    min-height:25px; padding:0 0 4px;
  }
  .rail-layout-toggle,.rail-layout-reset {
    display:inline-flex; align-items:center; justify-content:center;
    min-height:23px; padding:4px 7px; border:1px solid #d7dbe2; border-radius:3px;
    background:#fff; color:#252a33; font:8px/1.2 'Manrope', sans-serif;
    white-space:nowrap; cursor:pointer;
  }
  .rail-layout-toggle[aria-pressed="true"] { color:#fff; background:var(--faculty-accent); border-color:var(--faculty-accent); }
  .rail-layout-reset { display:none; }
  .rail-layout-hint { display:none; margin-right:auto; color:#606979; font:7.5px/1.25 'Manrope', sans-serif; }
  .right-rail.layout-editing .rail-layout-reset,.right-rail.layout-editing .rail-layout-hint { display:inline-flex; }
  .right-rail :is(.metrics,.sidepanel,.impact-section,.watch-section,.data-note) { position:relative; min-height:0; }
  .right-rail .rail-row-resize {
    display:none; position:absolute; z-index:55; right:0; bottom:0; left:0;
    width:100%; height:9px; padding:0; border:0; background:transparent;
    cursor:row-resize; touch-action:none; align-items:center; justify-content:center;
  }
  .right-rail .rail-row-resize::after { content:""; display:block; width:42px; height:3px; border-radius:3px; background:#e30613; box-shadow:0 0 0 3px rgba(227,6,19,.09); opacity:0; transition:opacity .12s ease; }
  .right-rail.layout-editing .rail-row-resize { display:flex; }
  .right-rail.layout-editing .rail-row-resize::after { opacity:.82; }
  .right-rail.layout-editing .rail-row-resize:hover::after,.right-rail.layout-editing .rail-row-resize:focus-visible::after { width:58px; opacity:1; }
  .right-rail.layout-editing > .metrics,
  .right-rail.layout-editing > .impact-section,
  .right-rail.layout-editing > .watch-section,
  .right-rail.layout-editing > .data-note { overflow:auto; overscroll-behavior:contain; }
  .right-rail.layout-editing > .sidepanel { overflow:visible; }
  .right-rail.layout-editing .sidepanel > .inspector,
  .right-rail.layout-editing .sidepanel > .projection-card { overflow:auto !important; overscroll-behavior:contain; scrollbar-width:thin; }
  .right-rail .rail-column-resize {
    display:none; position:absolute; z-index:56; top:0; bottom:0; width:11px;
    padding:0; border:0; background:transparent; cursor:col-resize; touch-action:none;
    transform:translateX(-50%); align-items:center; justify-content:center;
  }
  .right-rail .rail-column-resize::after { content:""; height:42px; width:3px; border-radius:3px; background:#e30613; box-shadow:0 0 0 3px rgba(227,6,19,.09); opacity:0; transition:opacity .12s ease; }
  .right-rail.layout-editing .rail-column-resize { display:flex; }
  .right-rail.layout-editing .rail-column-resize::after { opacity:.82; }
  .right-rail.layout-editing .rail-column-resize:hover::after,.right-rail.layout-editing .rail-column-resize:focus-visible::after { height:58px; opacity:1; }
}
/* Place the desktop editing tools beside the methodology annotation. */
@media (min-width:1100px) {
  .right-rail { padding-top:0; }
  .right-rail .projection-card > .calibration-strip {
    position:relative;
    grid-template-columns:12px minmax(0,1fr) auto auto;
    align-items:start;
  }
  .right-rail .rail-layout-tools {
    position:static;
    grid-column:4;
    grid-row:1;
    display:flex;
    align-items:flex-start;
    justify-content:flex-end;
    gap:4px;
    min-height:0;
    padding:0;
  }
  .right-rail .rail-layout-toggle,.right-rail .rail-layout-reset {
    min-height:22px;
    padding:4px 5px;
    font-size:7px;
  }
  .right-rail .rail-layout-hint { display:none !important; }
  .right-rail.layout-editing .rail-layout-reset { display:inline-flex; }
}

/* Final interaction fixes: keep the method note tucked behind the info mark. */
.right-rail .projection-card > .calibration-strip { position:relative; }
.right-rail .projection-card > .calibration-strip .calibration-mark {
  cursor:help;
  outline-offset:3px;
}
.right-rail .projection-card > .calibration-strip .calibration-tooltip {
  display:none !important;
  position:absolute;
  z-index:140;
  top:100%;
  left:0;
  width:min(215px, calc(100vw - 32px));
  max-width:215px;
  box-sizing:border-box;
  padding:7px 8px;
  border:1px solid #dfe3e9;
  border-radius:4px;
  background:#ffffff;
  color:#30343b;
  box-shadow:0 6px 18px rgba(20,24,18,.12);
  font-size:9px;
  line-height:1.35;
  white-space:normal;
  pointer-events:auto;
}
.right-rail .projection-card > .calibration-strip .calibration-mark:hover + .calibration-tooltip,
.right-rail .projection-card > .calibration-strip .calibration-mark:focus-visible + .calibration-tooltip,
.right-rail .projection-card > .calibration-strip .calibration-tooltip:hover {
  display:block !important;
}
.right-rail .projection-card > .calibration-strip #calibrationText { margin:0; }
.right-rail .data-links {
  flex-direction:column !important;
  flex-wrap:nowrap !important;
  align-items:flex-end !important;
  white-space:normal !important;
}
.right-rail .data-links a {
  max-width:100%;
  white-space:normal;
  text-align:right;
}
.right-rail .data-links .comparison-method-link { display:block; text-align:right; }
.right-rail .model-block > .test-inline {
  display:block;
  grid-column:1 / -1;
  margin-top:2px;
  white-space:normal;
}
#everydayText,
.right-rail .everyday-meaning,
.right-rail .model-block {
  height:auto !important;
  max-height:none !important;
  overflow:visible !important;
}
#everydayText {
  display:block !important;
  min-height:0 !important;
  max-height:none !important;
  height:auto !important;
  overflow:visible !important;
  white-space:normal !important;
  text-overflow:clip !important;
  -webkit-line-clamp:unset !important;
  line-clamp:unset !important;
}
@media (min-width:1100px) {
  .right-rail .sidepanel,
  .right-rail .inspector {
    height:auto !important;
    min-height:max-content !important;
    overflow:visible !important;
  }
  .right-rail .model-block > .everyday-meaning {
    grid-column:1 / -1 !important;
    align-self:start;
    padding:6px 0 0 !important;
    border-left:0 !important;
    border-top:1px solid #e4e8ef !important;
    min-height:max-content !important;
    overflow:visible !important;
  }
  .right-rail .everyday-meaning p {
    display:block !important;
    max-height:none !important;
    overflow:visible !important;
    white-space:normal !important;
    -webkit-line-clamp:unset !important;
    line-clamp:unset !important;
  }
}
</style>
</head>
<body>
<div id="app">
  <main class="shell">
    <section class="hero">
      <div>
        <div class="eyebrow" id="heroEyebrow">Human × machine intelligence</div>
        <h1 id="heroTitle">Where does AI sit<br>in the <span class="gradient" id="heroTitleAccent">human universe?</span></h1>
        <p class="hero-copy" id="heroCopy">Explore the frontier across ten cognitive faculties. Each model marker is positioned against a human reference, so you can see where AI leads, where people lead, and where the gap is still small.</p>
      </div>
      <div class="hero-note"><strong id="heroNoteTitle">One map. Two kinds of intelligence.</strong><br><span id="heroNoteText">Drag the cosmos, select a star, then change the future scenario to see how today's gaps could move. Past the present, the display is a transparent what-if, not a prediction.</span></div>
    </section>

    <section class="metrics" aria-label="Current comparison summary">
      <div class="metric"><div class="metric-label">Human leads</div><div class="metric-value" id="humanCount">4 / 10</div><div class="metric-foot">faculties in the source snapshot</div></div>
      <div class="metric"><div class="metric-label">AI leads</div><div class="metric-value" id="aiCount">3 / 10</div><div class="metric-foot">best published result per faculty</div></div>
      <div class="metric"><div class="metric-label">Near parity</div><div class="metric-value" id="closeCount">3 / 10</div><div class="metric-foot">within five score points</div></div>
      <div class="metric"><div class="metric-label">Largest current gap</div><div class="metric-value" id="largestGap">55 pts</div><div class="metric-foot" id="largestGapFoot">AI leads in metacognition</div></div>
    </section>

    <section class="explorer" aria-label="Interactive capability galaxy">
      <div class="galaxy-panel">
        <div class="galaxy-head">
          <div><div class="galaxy-title" id="galaxyTitle">The human vs other intelligence frontier</div><div class="galaxy-subtitle" id="galaxySubtitle">TEN FACULTIES · TWO REFERENCE POINTS · A FIELD OF COMPARISONS</div></div>
          <div class="stage-actions">
            <div class="view-controls">
              <span class="mode-pill" id="projectionMode">CC Atlas · Human</span>
              <div class="mode-switch" role="group" aria-label="Galaxy visualization mode">
              <button type="button" data-view="cosmos" aria-pressed="true">Cosmos</button>
              <button type="button" data-view="frontier" aria-pressed="false">Frontier</button>
              <button type="button" data-view="trajectory" aria-pressed="false">Trajectory</button>
              <button type="button" data-view="evidence" aria-pressed="false">Evidence</button>
              <button type="button" data-view="impact" aria-pressed="false">Impact</button>
              </div>
            </div>
            <div class="zoom-controls" aria-label="Zoom and view controls">
              <button class="map-button zoom" id="zoomOut" type="button" aria-label="Zoom out" >−</button>
              <span class="zoom-level" id="zoomLevel" aria-live="polite">100%</span>
              <button class="map-button zoom" id="zoomIn" type="button" aria-label="Zoom in" >+</button>
              <a class="map-button feedback-button" id="feedbackIdea" href="https://tally.so/r/rDjRGv" target="_blank" rel="noreferrer">Feedback · Idea</a><button class="map-button" id="resetView" type="button">Reset view</button>
              <button class="map-button" id="howToUse" type="button" aria-haspopup="dialog" aria-controls="howToUseModal">How to use</button>
              <button class="language-toggle" id="languageToggle" type="button" aria-label="Switch language to Bangla" aria-pressed="false">বাংলা</button>
            </div>
          </div>
        </div>
        <div class="canvas-wrap" id="canvasWrap">
          <aside class="activity-log" aria-label="Capability observation log">
            <div class="activity-log-head"><span id="activityLogTitle">OBSERVATION LOG</span><span id="activityLogCount">10 RECORDS</span></div>
            <div class="activity-entries" id="activityEntries"></div>
          </aside>
          <canvas id="cosmos" tabindex="0" aria-label="Interactive galaxy. Use arrow keys to change faculty, plus and minus to zoom. Select a marker for details." role="img"></canvas>
          <div class="tooltip" id="tooltip"></div>
          <div class="canvas-guide" id="canvasGuide"><b>READ THE GALAXY</b><br>Circle = human reference + selected comparison · diamonds = other comparison points<br>AI outside the orbit = higher score<br>AI inside = human reference scores higher<br>Separation cues this test’s gap; it is not a shared intelligence scale.</div>
          <div class="legend"><span><i class="hum"></i><span id="legendHuman">Human reference</span></span><span><i class="machine"></i><span id="legendAI">AI result</span></span><span class="territory-legend-item"><i class="territory-key"></i><span class="territory-legend-copy"><strong id="legendTerritory">Perception</strong><small id="legendTerritoryDesc">Taking in information from the world and making sense of it.</small></span></span><span><i class="gap-key"></i><span id="legendGap">Pair gap</span></span><span><i class="orbit-key"></i><span id="legendOrbit">Mesh links</span></span><span><i class="selected-key"></i><span id="legendSelected">Selected faculty</span></span></div>
          <button class="journey-trigger" id="journeyTrigger" type="button" aria-label="Explore next capability" title="Explore next capability"><svg viewBox="0 0 24 24" fill="none" aria-hidden="true"><path d="M5 12h13M12 5l7 7-7 7" stroke="currentColor" stroke-width="1.8" stroke-linecap="round" stroke-linejoin="round"/></svg><span class="journey-hint" id="journeyHint">EXPLORE NEXT CAPABILITY ↗</span></button>
        </div>
      </div>

      <aside class="sidepanel">
        <div class="inspector" aria-live="polite">
          <h2 class="faculty-name" id="facultyName">Perception</h2>
          <div class="faculty-desc" id="facultyDesc">Taking in information from the world and making sense of it.</div>
          <div class="status-row"><span class="status-chip human" id="statusChip">Human leads</span><span class="gap-label" id="gapLabel">+13.0 point gap</span></div>
          <div class="compare" id="scoreComparison">
            <div class="compare-line"><span class="who" id="humanCompareLabel">Human reference</span><div class="track"><div class="fill human" id="humanBar" style="width:91.4%"></div></div><span class="score" id="humanScore">91.4</span></div>
            <div class="compare-line"><span class="who" id="aiCompareLabel">Reported AI result</span><div class="track"><div class="fill ai" id="aiBar" style="width:78.4%"></div></div><span class="score" id="aiScore">78.4</span></div>
          </div>
          <div class="animal-estimate" id="animalEstimate" aria-label="Animal faculty estimate"><div class="animal-estimate-line"><span class="who" id="animalEstimateLabel">Faculty estimate</span><div class="track"><div class="fill animal-estimate-fill" id="animalEstimateBar" style="width:82%"></div></div><span class="score" id="animalEstimateScore">82</span></div></div>
          <div class="model-block"><div class="small-label" id="topResultLabel">Winning AI Model or Result</div><div class="model-name" id="modelName">Gemini 2.5 Pro</div><div class="model-source" id="modelSource">Published benchmark snapshot · source details pending</div><div class="reference-caveat" id="referenceCaveat">A reference score is a comparison point, not the full range of human ability.</div><div class="everyday-meaning"><strong id="everydayLabel">WHY THIS MATTERS</strong><p id="everydayText">This task is a signal about one type of performance, not a verdict on every real-world situation.</p></div><a class="source-inline" id="facultySourceLink" href="https://epoch.ai/benchmarks" target="_blank" rel="noreferrer">Explore independent benchmark research ↗</a></div>
        </div>

        <div class="projection-card">
          <aside class="calibration-strip" aria-label="How to interpret the comparison">
            <span class="calibration-mark" aria-hidden="true">i</span>
            <p id="calibrationText">Each faculty uses a different benchmark. The 0–100 scores are not one shared intelligence scale, and the human reference may be an estimate, a small sample or an expert group, not the average or best human.</p>
            <div class="calibration-links"><a id="calibrationLink" href="https://epoch.ai/benchmarks" target="_blank" rel="noreferrer">How these comparisons work ↗</a><a id="takeTestLink" href="https://artificialanalysis.ai/models/recommend" target="_blank" rel="noreferrer">Find out the right model for you ↗</a></div>
          </aside>
          <div class="projection-title"><span id="projectionTitle">TRY A POSSIBLE FUTURE</span><span class="spark">✳</span></div>
          <p class="projection-explain" id="projectionExplain">Imagine slower, steady, or faster AI progress.</p>
          <div class="scenario-tabs" role="group" aria-label="Choose AI progress scenario">
            <button class="scenario" data-rate="1" aria-pressed="false">Slower +1</button>
            <button class="scenario" data-rate="3" aria-pressed="true">Steady +3</button>
            <button class="scenario" data-rate="6" aria-pressed="false">Faster +6</button>
          </div>
          <div class="horizon-line"><label for="horizon" id="horizonLabel">Look ahead</label><strong id="horizonValue">Today</strong></div>
          <input id="horizon" type="range" min="0" max="5" step="1" value="0" aria-label="Future time horizon in years" />
          <div class="range-labels"><span id="todayLabel">Today</span><span id="maxHorizonLabel">+5 years</span></div>
          <div class="scenario-result"><div class="result-main" id="scenarioMain">7 of 10 faculties AI-led</div><div class="result-sub" id="scenarioSub">Scenario: +3 score points per year, capped at 100. It is a what-if, not a forecast.</div></div>
          <div class="selection-switchers" aria-label="Comparison and faculty controls">
            <div class="comparator-switcher"><label for="comparatorSelect" id="comparatorLabel">COMPARE WITH</label><div class="comparator-controls"><select id="comparatorSelect" aria-label="Choose a comparator"><option value="ai">Artificial Intelligence (AI)</option><option value="chimpanzee">Chimpanzee</option><option value="dog">Dog</option><option value="honeybee">Honeybee</option></select><button id="prevComparator" type="button" aria-label="Previous comparison" title="Previous comparison">←</button><button id="nextComparator" type="button" aria-label="Next comparison" title="Next comparison">→</button></div></div>
            <div class="faculty-switcher"><label for="facultySelect" id="chooseFacultyLabel" class="small-label">CHOOSE A FACULTY</label><select id="facultySelect" aria-label="Choose a cognitive faculty"></select><button id="prevFaculty" type="button" aria-label="Previous faculty">←</button><button id="nextFaculty" type="button" aria-label="Next faculty">→</button></div>
          </div>
        </div>
      </aside>
    </section>

    <section class="impact-section">
      <div class="impact-grid">
        <article class="impact"><div class="impact-kicker" id="impactKicker1">01 / AI leads in these tests</div><h3 id="impactHead1">Reasoning & making things</h3><p id="impactText1">AI leads on selected reasoning and generation tests. The animal modes add task-specific estimates for chimpanzees, dogs and honeybees.</p></article>
        <article class="impact"><div class="impact-kicker" id="impactKicker2">02 / Human reference leads</div><h3 id="impactHead2">Attention, memory & control</h3><p id="impactText2">Human references score higher on several selected tasks. The gap does not prove people always perform better in real life.</p></article>
        <article class="impact"><div class="impact-kicker" id="impactKicker3">03 / Closest comparisons</div><h3 id="impactHead3">Close scores need careful reading</h3><p id="impactText3">Learning, problem solving, and social cognition sit close to the reference here. Different tests can make a small gap misleading.</p></article>
      </div>
    </section>

    <section class="watch-section" aria-live="polite">
      <div class="watch-intro"><div class="impact-kicker" id="watchKicker">FRONTIER WATCHLIST</div><h2 id="watchTitle">The closest calls</h2><p id="watchSub">These comparisons sit nearest to parity. Select one to inspect the test and the evidence.</p></div>
      <div class="watch-list" id="watchList"></div>
    </section>

    <aside class="data-note">
      <div class="note-icon" aria-hidden="true">ⓘ</div>
      <p id="dataNoteText">Evidence integrity: These are task-specific benchmark snapshots, not a shared intelligence scale or live ranking. Check the test, sample, setup and date to interpret differences fairly.</p>
      <div class="data-links"><a id="sourceLink" href="https://epoch.ai/benchmarks" target="_blank" rel="noreferrer">Explore benchmark data ↗</a><a id="methodLink" href="https://artificialanalysis.ai/data-api" target="_blank" rel="noreferrer">Explore evaluation APIs ↗</a><a id="modelRecommendLink" href="https://artificialanalysis.ai/models/recommend" target="_blank" rel="noreferrer">Find your match AI Model ↗</a></div>
    </aside>

  </main>
</div>
<script>
(() => {
  'use strict';
  const data = [
    {name:'Perception',desc:'Taking in information from the world and making sense of it.',human:91.4,ai:78.4,model:'Gemini 2.5 Pro',source:'Perception Test · untrained adults vs. published model result',ref:'Perception Test, untrained adults',aiRef:'Perception Test, Gemini 2.5 Pro',confidence:'Published reference'},
    {name:'Generation',desc:'Producing words, images, sounds, or actions and executing them under constraints.',human:50.0,ai:84.9,model:'GPT-5.5',source:'GDPval · vendor-reported wins or ties',ref:'GDPval, expert vs. expert (parity by design)',aiRef:'GDPval wins or ties, GPT-5.5',confidence:'Vendor-reported AI result'},
    {name:'Attention',desc:'Focusing on what matters and filtering distractors that look relevant.',human:95.0,ai:51.0,model:'RIAC · pooled frontier models',source:'One planted lure · human reference is a source estimate',ref:'Estimated human reference · untimed reading task',aiRef:'RIAC, one planted lure, pooled',confidence:'Estimated human reference'},
    {name:'Learning',desc:'Picking up new rules or skills from examples or feedback, then applying them.',human:100.0,ai:99.9,model:'GPT-6 Astra · custom harness',source:'ARC-AGI-3 · members of the public vs. published model result',ref:'ARC-AGI-3, members of the public',aiRef:'ARC-AGI-3, GPT-6 Astra with custom harness',confidence:'Published AI result; harness matters'},
    {name:'Memory',desc:'Holding information over time and retrieving it when needed.',human:87.9,ai:66.5,model:'Claude Sonnet + memory system',source:'LoCoMo F1 · Maharana et al. (2024)',ref:'LoCoMo F1, human reference',aiRef:'LoCoMo F1, Claude Sonnet + memory system',confidence:'Published reference'},
    {name:'Reasoning',desc:'Drawing valid conclusions through deduction, induction, analogy, and mathematics.',human:69.7,ai:96.4,model:'Gemini 4 Argon',source:'GPQA Diamond · PhD expert human reference',ref:'GPQA Diamond, PhD experts',aiRef:'GPQA Diamond, Gemini 4 Argon (Epoch AI)',confidence:'Published AI result; benchmark-specific'},
    {name:'Metacognition',desc:'Knowing what you know, spotting flawed questions, and judging confidence.',human:45.0,ai:100.0,model:'MetaBound · best reported model',source:'Human reference is a source estimate; other models scored 0% on this benchmark',ref:'Estimated human reference · Moses illusion + invented names',aiRef:'MetaBound, best model',confidence:'Estimated human reference'},
    {name:'Executive functions',desc:'Planning, switching strategy when rules change, and inhibiting old habits.',human:92.0,ai:74.5,model:'Claude Sonnet 4.5 (HAL)',source:'GAIA · university-educated testers',ref:'GAIA, university-educated testers',aiRef:'GAIA, Claude Sonnet 4.5 (HAL)',confidence:'Published reference'},
    {name:'Problem solving',desc:'Combining faculties to solve problems, from novel puzzles to everyday common sense.',human:83.7,ai:81.9,model:'Claude Fable 5',source:'SimpleBench · nine non-specialists; composite faculty',ref:'SimpleBench, nine non-specialists',aiRef:'SimpleBench, Claude Fable 5',confidence:'Small human sample'},
    {name:'Social cognition',desc:'Understanding what people think, feel, and mean without saying it directly.',human:84.4,ai:80.0,model:'GPT-5.1',source:'Human and AI results come from different tests',ref:'Social IQa (Sap et al., 2019)',aiRef:'CogToM, GPT-5.1',confidence:'Different tests; interpret cautiously'}
  ];
  // Evidence ledger: these links explain the benchmark or original paper. They do NOT automatically
  // validate the exact score/run in this snapshot. Where an exact run, sample, or matched human
  // baseline is not traceable, the passport says so explicitly rather than silently upgrading it.
  const evidenceLedger = {
    'Perception': {
      sourceName:'Perception Test · original benchmark paper', sourceUrl:'https://arxiv.org/abs/2305.13786', scoreTrailUrl:'https://www.humanbaseline.org/benchmarks/perception-test/',
      sourceLabel:'Open the benchmark paper ↗',
      status:'BENCHMARK IDENTIFIED · EXACT AI RUN NEEDS VERIFICATION',
      method:'The Perception Test evaluates multimodal video understanding across audio, video and text tasks. The linked paper documents the benchmark and a human baseline, but it does not by itself verify this exact Gemini 2.5 Pro value or that the two displayed values use the same split and evaluation setup.',
      comparability:'Provisional. Match the exact model run, test split, metric, prompt/tool setup and date before treating this as a head-to-head gap.'
    },
    'Generation': {
      sourceName:'OpenAI · GPT-5.5 and GDPval results', sourceUrl:'https://openai.com/index/introducing-gpt-5-5/', scoreTrailUrl:'https://www.humanbaseline.org/benchmarks/gdpval/',
      sourceLabel:'Explore GDPval tasks and method ↗',
      status:'VENDOR-REPORTED RESULT · HUMAN VALUE IS A PARITY REFERENCE',
      method:'GDPval grades model deliverables against work products from professionals. The 50.0 human figure is an expert-versus-expert parity reference by design, not the average person’s score. The 84.9 figure is described in this snapshot as vendor-reported wins or ties; retain the run details when quoting it.',
      comparability:'Not a comparison with an average human. Read 84.9 as a task/benchmark-specific reported result, not a universal generation or creativity score.'
    },
    'Attention': {
      sourceName:'RIAC · benchmark and measurement notes', sourceUrl:'https://www.humanbaseline.org/benchmarks/riac/', scoreTrailUrl:'https://www.humanbaseline.org/faculties/attention/',
      sourceLabel:'Inspect RIAC methodology ↗',
      status:'HUMAN REFERENCE IS AN ATLAS ESTIMATE',
      method:'RIAC reports the model result for a deliberately planted-lure attention task. The ~95 human value is an estimate, not a matched human-population result from this benchmark. The source page describes the task; it is not a peer-reviewed population baseline.',
      comparability:'Unmatched. Do not present the 44-point difference as a measured gap between AI and the average human.'
    },
    'Learning': {
      sourceName:'ARC Prize · verified GPT-6 Astra results', sourceUrl:'https://arcprize.org/results/openai-gpt-6-astra', scoreTrailUrl:'https://www.humanbaseline.org/faculties/learning/',
      sourceLabel:'Inspect ARC-AGI-3 results and harness ↗',
      status:'HARNESS-SENSITIVE · MATCHED HUMAN COMPARISON UNRESOLVED',
      method:'ARC-AGI-3 is an interactive agent benchmark. The cited 99.9% result is tied to a Provider Adapter harness; the same model has a materially different result with the Standard harness. A score from a different human procedure is not automatically an equivalent learning score.',
      comparability:'High caution. Keep the harness, reasoning effort, cost and exact leaderboard variant attached to the model result. Do not read 100 vs 99.9 as proof of equal general learning.'
    },
    'Memory': {
      sourceName:'LoCoMo · original ACL paper', sourceUrl:'https://aclanthology.org/2024.acl-long.747/', scoreTrailUrl:'https://www.humanbaseline.org/benchmarks/locomo/',
      sourceLabel:'Read the LoCoMo paper ↗',
      status:'TASK-SPECIFIC · EXACT HUMAN BASELINE NEEDS PROVENANCE',
      method:'LoCoMo measures long-term conversational memory using questions about extended conversations. The shown model uses an added memory system, and the displayed human-reference value needs its sample and scoring procedure linked before it can be treated as a matched baseline.',
      comparability:'Task-specific only. This does not measure all forms of human memory or compare an unaided person with an unassisted model.'
    },
    'Reasoning': {
      sourceName:'GPQA Diamond · official benchmark and method', sourceUrl:'https://epoch.ai/benchmarks/gpqa-diamond', scoreTrailUrl:'https://llmbenchmark.ai/benchmarks/epoch-gpqa-diamond',
      sourceLabel:'Inspect the GPQA Diamond snapshot ↗',
      status:'BENCHMARK-SPECIFIC · HUMAN REFERENCE METHOD NEEDS VERIFICATION',
      method:'GPQA Diamond tests graduate-level science questions in biology, physics and chemistry. The displayed 96.4 model result comes from a dated third-party mirror of Epoch AI’s GPQA Diamond run; the official benchmark page describes the test and the 69.7 PhD-expert reference. Keep the model-run date, evaluation prompt and reference setup together before interpreting the gap.',
      comparability:'Narrow domain. Strong performance on graduate science QA is not a universal measure of deduction, everyday judgement, or intelligence.'
    },
    'Metacognition': {
      sourceName:'MetaBound · benchmark/method notes', sourceUrl:'https://www.humanbaseline.org/benchmarks/metabound/', scoreTrailUrl:'https://www.humanbaseline.org/faculties/metacognition/',
      sourceLabel:'Inspect MetaBound method notes ↗',
      status:'ESTIMATED HUMAN REFERENCE · PRIMARY VALIDATION NEEDED',
      method:'The 45.0 human value is an Atlas estimate based on false-premise examples, not a score published by MetaBound. The HumanBaseline context page reports roughly 20% for a narrower false-premise task; that number is not the same measurement as this composite estimate. The 100.0 AI value is the best reported result in this snapshot.',
      comparability:'High caution. The human number is an Atlas estimate and is not validated as a matched MetaBound baseline. Treat the two values as evidence prompts, not a measured head-to-head gap.'
    },
    'Executive functions': {
      sourceName:'HAL · Holistic Agent Leaderboard', sourceUrl:'https://hal.cs.princeton.edu/', scoreTrailUrl:'https://www.humanbaseline.org/benchmarks/gaia/',
      sourceLabel:'Inspect the HAL leaderboard and tasks ↗',
      status:'CONSTRUCT-VALIDITY WARNING · GAIA IS NOT A PURE EXECUTIVE-FUNCTION TEST',
      method:'GAIA evaluates multi-step real-world assistant tasks such as reasoning, reading files, browsing and tool use. That can involve planning, but its score is not a validated, isolated composite measure of executive functions. The faculty label is an interpretive mapping.',
      comparability:'Weak construct match. Rename or relabel this faculty-to-benchmark mapping before presenting the 92.0 vs 74.5 figures as executive-function evidence.'
    },
    'Problem solving': {
      sourceName:'SimpleBench · official benchmark and leaderboard', sourceUrl:'https://epoch.ai/benchmarks/simplebench', scoreTrailUrl:'https://llmbenchmark.ai/benchmarks/epoch-simplebench',
      secondaryName:'SimpleBench · benchmark context and human-reference notes', secondaryUrl:'https://www.humanbaseline.org/benchmarks/simplebench/', secondaryLabelEn:'Human-sample note ↗', secondaryLabelBn:'মানব-নমুনার নোট ↗',
      sourceLabel:'Inspect SimpleBench results ↗',
      status:'SMALL HUMAN SAMPLE · RUN/LEADERBOARD ALIGNMENT SHOULD BE CHECKED',
      method:'The human reference is nine non-specialists, so it is highly sensitive to who was tested. The 81.9 Claude Fable 5 value is from a dated leaderboard snapshot; the original benchmark page documents the standard prompt and five-run average, and the human reference uses nine people. Keep the date, model configuration and small-sample caveat beside the score.',
      comparability:'Provisional. Keep the nine-person sample visible and do not generalize the result to all people or every kind of problem solving.'
    },
    'Social cognition': {
      sourceName:'Social IQa · original ACL paper', sourceUrl:'https://aclanthology.org/D19-1454/', scoreTrailUrl:'https://www.humanbaseline.org/benchmarks/cogtom/',
      secondaryName:'CogToM · ACL Anthology paper', secondaryUrl:'https://aclanthology.org/2026.acl-long.1448/', secondaryLabelEn:'CogToM paper ↗', secondaryLabelBn:'CogToM গবেষণাপত্র ↗',
      sourceLabel:'Open Social IQa source ↗',
      status:'NOT HEAD-TO-HEAD · HUMAN AND AI RESULTS USE DIFFERENT TESTS',
      method:'The human reference comes from Social IQa, while the AI result is listed from CogToM. The tests have different items and designs; source details for the exact GPT-5.1 CogToM run still require confirmation. The displayed 84.4 and 80.0 values must not be interpreted as a directly measured 4.4-point human advantage.',
      comparability:'No direct numeric comparison. Present both as separate task indicators until a matched protocol and shared scoring method are available.'
    }
  };
  // Animal comparisons use transparent 0–100 faculty estimates; the basis of each rating is labelled in the inspector and visual map.
  // Faculty indices follow the site's existing ten-faculty order: Perception, Generation,
  // Attention, Learning, Memory, Reasoning, Metacognition, Executive functions,
  // Problem solving, Social cognition.
  const comparativeProfiles = {
    chimpanzee: {
      labelEn:'Chimpanzee', labelBn:'শিম্পাঞ্জি', sourceUrl:'https://pubmed.ncbi.nlm.nih.gov/20424030/',
      groupEn:'Primary study: 106 chimpanzees and 105 two-year-old children completed 15 tasks covering the physical and social worlds.',
      groupBn:'মূল গবেষণা: ১০৬টি শিম্পাঞ্জি ও ১০৫ জন দুই বছর বয়সী শিশু দৈহিক ও সামাজিক জগত নিয়ে ১৫টি কাজ সম্পন্ন করে।',
      limitEn:'The paper compares the structure of individual cognitive differences; it does not publish species-wide 0–100 faculty scores. Atlas values synthesize the reported task pattern and are deliberately labelled by their basis.',
      limitBn:'গবেষণাপত্রটি ব্যক্তিভেদে জ্ঞানীয় সক্ষমতার গঠন তুলনা করে; প্রজাতির জন্য ০–১০০ সক্ষমতা-স্কোর প্রকাশ করে না। অ্যাটলাসের মানগুলো প্রকাশিত কাজের ধরন থেকে সংশ্লেষ করা এবং ভিত্তি দিয়ে স্পষ্টভাবে চিহ্নিত।',
      faculties:[
        {score:82,basis:'Evidence Based',en:'The linked study found a spatial-cognition factor shared by chimpanzees and two-year-old children. The score is an atlas estimate of this directly studied faculty, not a raw study score.',bn:'লিংক করা গবেষণায় শিম্পাঞ্জি ও দুই বছর বয়সী শিশুদের মধ্যে স্থানিক বোধের একটি মিলযুক্ত ফ্যাক্টর পাওয়া যায়। এটি সরাসরি আলোচিত সক্ষমতার অ্যাটলাসের অনুমান, গবেষণার কাঁচা স্কোর নয়।'},
        {score:56,basis:'Reasoning Based',en:'Creative output is estimated conservatively from the distinction between producing an action or signal and solving a task. The linked battery did not score generative output as a separate faculty.',bn:'কাজ বা সংকেত তৈরি করা এবং কোনো কাজ সমাধানের পার্থক্য বিবেচনায় সৃজনশীল আউটপুটের মান সতর্কভাবে অনুমান করা হয়েছে। লিংক করা পরীক্ষামালায় সৃজনশীল আউটপুট আলাদা সক্ষমতা হিসেবে স্কোর করা হয়নি।'},
        {score:71,basis:'Reasoning Based',en:'Attention is estimated from the demands of selecting relevant cues across multi-task testing. The score is an interpretation of task demands, not a direct attention measure.',bn:'বহু-ধরনের পরীক্ষায় প্রাসঙ্গিক সংকেত বেছে নেওয়ার প্রয়োজন থেকে মনোযোগের মান অনুমান করা হয়েছে। এটি কাজের চাহিদার ব্যাখ্যা, সরাসরি মনোযোগের মাপ নয়।'},
        {score:76,basis:'Reasoning Based',en:'Performance across a 15-task battery suggests substantial task learning and adaptation capacity, while the paper did not isolate learning speed as a separate score.',bn:'১৫টি কাজের পরীক্ষামালায় অংশগ্রহণ কাজ শেখা ও মানিয়ে নেওয়ার উল্লেখযোগ্য সক্ষমতার ইঙ্গিত দেয়, যদিও গবেষণায় শেখার গতি আলাদা স্কোর ছিল না।'},
        {score:75,basis:'Reasoning Based',en:'The estimate reflects the need to retain task-relevant information across a varied cognitive battery. The linked paper focused on factor structure rather than a dedicated memory test.',bn:'বিভিন্ন জ্ঞানীয় কাজে প্রাসঙ্গিক তথ্য ধরে রাখার প্রয়োজন বিবেচনায় এই মান অনুমান করা হয়েছে। লিংক করা গবেষণা নির্দিষ্ট স্মৃতি-পরীক্ষার বদলে ফ্যাক্টর-গঠনে মনোযোগ দিয়েছে।'},
        {score:78,basis:'Evidence Based',en:'The linked battery included physical-world tasks, and the analysis identified a distinct pattern of physical cognition in chimpanzees. The score is a synthesis estimate, not a published reasoning percentage.',bn:'লিংক করা পরীক্ষামালায় দৈহিক জগতের কাজ ছিল এবং বিশ্লেষণে শিম্পাঞ্জিদের দৈহিক বোধের স্বতন্ত্র ধরন পাওয়া যায়। স্কোরটি সংশ্লেষভিত্তিক অনুমান, প্রকাশিত যুক্তি-দক্ষতার শতাংশ নয়।'},
        {score:55,basis:'Reasoning Based',en:'The estimate is cautious because the linked study was not designed to measure confidence calibration or explicit self-monitoring.',bn:'লিংক করা গবেষণাটি আত্মবিশ্বাসের যথার্থতা বা নিজের চিন্তা স্পষ্টভাবে পর্যবেক্ষণ করার সক্ষমতা মাপার জন্য তৈরি হয়নি, তাই এই মান সতর্কভাবে নির্ধারণ করা হয়েছে।'},
        {score:68,basis:'Reasoning Based',en:'The estimate reflects flexible engagement across tasks while remaining cautious about planning, inhibition and switching, which were not isolated as a composite score.',bn:'বিভিন্ন কাজে নমনীয় অংশগ্রহণ বিবেচনায় এই মান অনুমান করা হয়েছে; পরিকল্পনা, বাধা দেওয়া ও কৌশল বদলের সম্মিলিত স্কোর আলাদা করে মাপা হয়নি বলে সতর্কতা রাখা হয়েছে।'},
        {score:78,basis:'Reasoning Based',en:'The physical-world task set informs this problem-solving estimate, but the paper does not give a single composite puzzle-solving percentage.',bn:'দৈহিক জগতের কাজগুলো সমস্যা-সমাধানের এই অনুমানকে সমর্থন করে, তবে গবেষণাপত্রে ধাঁধা সমাধানের একক সম্মিলিত শতাংশ নেই।'},
        {score:68,basis:'Evidence Based',en:'The study found a distinct social-cognition factor in children and a different task pattern in chimpanzees. That difference concerns how abilities cluster, not the absence of social capacity.',bn:'গবেষণায় শিশুদের সামাজিক বোধের স্বতন্ত্র ফ্যাক্টর এবং শিম্পাঞ্জিদের ভিন্ন কাজভিত্তিক ধরন পাওয়া যায়। এই পার্থক্য সক্ষমতাগুলো কীভাবে গুচ্ছবদ্ধ হয় তা নিয়ে, সামাজিক সক্ষমতার অনুপস্থিতি নিয়ে নয়।'}
      ]
    },
    dog: {
      labelEn:'Dog', labelBn:'কুকুর', sourceUrl:'https://pubmed.ncbi.nlm.nih.gov/19343382/',
      groupEn:'Primary study: dogs were compared with children aged two and three on their use and generalization of several human pointing gestures to find a hidden object.',
      groupBn:'মূল গবেষণা: লুকানো বস্তু খুঁজতে মানুষের বিভিন্ন নির্দেশক অঙ্গভঙ্গি ব্যবহার ও সাধারণীকরণের ক্ষেত্রে কুকুরদের দুই ও তিন বছর বয়সী শিশুদের সঙ্গে তুলনা করা হয়।',
      limitEn:'The paper reports success and failure by gesture type, not an overall dog-intelligence score. Atlas values summarize faculty strength cautiously and label the basis for each estimate.',
      limitBn:'গবেষণাপত্রে অঙ্গভঙ্গির ধরন অনুযায়ী সাফল্য ও ব্যর্থতা জানানো হয়েছে, সামগ্রিক কুকুর-বুদ্ধিমত্তার স্কোর নয়। অ্যাটলাসের মানগুলো সক্ষমতার শক্তি সতর্কভাবে সংশ্লেষ করে এবং প্রতিটি অনুমানের ভিত্তি চিহ্নিত করে।',
      faculties:[
        {score:75,basis:'Reasoning Based',en:'Finding a hidden object from a human gesture depends on visual cue processing. The score is a bounded estimate from the task demands, rather than a standalone perception test.',bn:'মানুষের অঙ্গভঙ্গি থেকে লুকানো বস্তু খুঁজতে দৃশ্যমান সংকেত প্রক্রিয়াকরণ দরকার। এটি কাজের চাহিদা থেকে করা সীমিত অনুমান, স্বতন্ত্র অনুধাবন-পরীক্ষার স্কোর নয়।'},
        {score:38,basis:'Reasoning Based',en:'The linked study tests comprehension of cues, not the production of language, images or novel symbols; this faculty is therefore estimated conservatively.',bn:'লিংক করা গবেষণায় সংকেত বোঝা পরীক্ষা করা হয়েছে, ভাষা, ছবি বা নতুন প্রতীক তৈরি নয়; তাই এই সক্ষমতার মান সতর্কভাবে অনুমান করা হয়েছে।'},
        {score:70,basis:'Reasoning Based',en:'Success depends on attending to the human cue and distinguishing it from other possible directions. Attention is inferred from task demands, not directly isolated.',bn:'সফলতার জন্য মানুষের সংকেতে মনোযোগ দেওয়া এবং অন্য সম্ভাব্য দিক থেকে সেটিকে আলাদা করা প্রয়োজন। কাজের চাহিদা থেকে মনোযোগ অনুমান করা হয়েছে, সরাসরি আলাদা করে মাপা হয়নি।'},
        {score:76,basis:'Evidence Based',en:'Dogs generalized some unfamiliar leg-pointing cues, but performance depended on gesture type. The score summarizes that demonstrated flexibility as a faculty estimate.',bn:'কুকুরেরা কিছু অপরিচিত পা-দিয়ে নির্দেশের সংকেত সাধারণীকরণ করতে পেরেছে, তবে ফল অঙ্গভঙ্গির ধরনের ওপর নির্ভর করেছে। স্কোরটি প্রদর্শিত নমনীয়তার সক্ষমতা-অনুমান।'},
        {score:55,basis:'Reasoning Based',en:'The task required retaining a cue long enough to choose an object, but it did not measure delayed recall or memory duration. The score stays conservative.',bn:'বস্তু বেছে নেওয়া পর্যন্ত সংকেত ধরে রাখা প্রয়োজন ছিল, তবে বিলম্বিত স্মরণ বা স্মৃতির স্থায়িত্ব মাপা হয়নি। তাই স্কোরটি সতর্ক রাখা হয়েছে।'},
        {score:55,basis:'Reasoning Based',en:'Using a gesture to select a hidden-object location requires bounded cue-to-outcome inference. The study does not test abstract or scientific reasoning.',bn:'লুকানো বস্তুর অবস্থান বেছে নিতে অঙ্গভঙ্গি থেকে ফলের সীমিত অনুমান করতে হয়। গবেষণাটি বিমূর্ত বা বৈজ্ঞানিক যুক্তি পরীক্ষা করে না।'},
        {score:35,basis:'Reasoning Based',en:'Confidence calibration and explicit awareness of uncertainty were not the target of this task, so the estimate is intentionally cautious.',bn:'আত্মবিশ্বাসের যথার্থতা ও অনিশ্চয়তা সম্পর্কে স্পষ্ট সচেতনতা এই কাজের লক্ষ্য ছিল না, তাই অনুমানটি ইচ্ছাকৃতভাবে সতর্ক।'},
        {score:48,basis:'Reasoning Based',en:'The task involved a single cue-guided choice rather than multi-step planning or inhibition. The score reflects that narrow task scope.',bn:'কাজটিতে বহু-ধাপের পরিকল্পনা বা বাধা দেওয়ার বদলে একটি সংকেত-নির্দেশিত বাছাই ছিল। স্কোরটি সেই সীমিত কাজের পরিসরকে প্রতিফলিত করে।'},
        {score:58,basis:'Reasoning Based',en:'Locating a hidden object from a directional signal is a bounded everyday problem-solving task. The score estimates that narrow competence, not general problem solving.',bn:'দিকনির্দেশক সংকেত থেকে লুকানো বস্তু খুঁজে পাওয়া দৈনন্দিন জীবনের সীমিত সমস্যা-সমাধানের কাজ। স্কোরটি সেই নির্দিষ্ট সক্ষমতার অনুমান, সাধারণ সমস্যা-সমাধানের নয়।'},
        {score:82,basis:'Evidence Based',en:'Dogs used several human pointing gestures successfully, but failed on some cross-pointing forms that three-year-old children understood. This is a direct, gesture-specific social-communication result.',bn:'কুকুরেরা মানুষের কয়েক ধরনের নির্দেশক অঙ্গভঙ্গি সফলভাবে ব্যবহার করেছে, তবে এমন কিছু ক্রস-পয়েন্টিং বুঝতে পারেনি যা তিন বছর বয়সী শিশুরা বুঝেছিল। এটি অঙ্গভঙ্গি-নির্দিষ্ট সামাজিক যোগাযোগের সরাসরি ফল।'}
      ]
    },
    honeybee: {
      labelEn:'Honeybee', labelBn:'মৌমাছি', sourceUrl:'https://pmc.ncbi.nlm.nih.gov/articles/PMC7568273/',
      groupEn:'Primary study: honeybees and adult humans were tested in related visual statistical-learning tasks involving element frequencies, co-occurrence patterns and conditional prediction.',
      groupBn:'মূল গবেষণা: দৃশ্যের উপাদানের পুনরাবৃত্তি, সহ-উপস্থিতির ধরন ও শর্তাধীন পূর্বাভাস নিয়ে সম্পর্কিত দৃশ্য-পরিসংখ্যানগত শেখার কাজে মৌমাছি ও প্রাপ্তবয়স্ক মানুষকে পরীক্ষা করা হয়।',
      limitEn:'The linked paper measures specific visual-learning mechanisms, not a universal intelligence score. Atlas values are evidence-informed faculty estimates; use them as a structured guide rather than a standardized cross-species test result.',
      limitBn:'লিংক করা গবেষণাপত্র নির্দিষ্ট দৃশ্য-শেখার প্রক্রিয়া মাপে, সার্বজনীন বুদ্ধিমত্তার স্কোর নয়। অ্যাটলাসের মানগুলো প্রমাণ-সমর্থিত সক্ষমতা-অনুমান; এগুলোকে মানসম্মত আন্তঃপ্রজাতি পরীক্ষার ফল নয়, বরং কাঠামোবদ্ধ নির্দেশক হিসেবে দেখুন।',
      faculties:[
        {score:78,basis:'Evidence Based',en:'Honeybees extracted visual element and co-occurrence statistics from scenes. The study also notes other work on object recognition, spatial configuration and visual categorization.',bn:'মৌমাছি দৃশ্য থেকে উপাদান ও সহ-উপস্থিতির পরিসংখ্যান শিখেছে। গবেষণাপত্রে বস্তু শনাক্তকরণ, স্থানিক বিন্যাস ও দৃশ্যভিত্তিক শ্রেণিবিন্যাস নিয়ে অন্য কাজেরও উল্লেখ আছে।'},
        {score:18,basis:'Reasoning Based',en:'This visual statistical-learning study did not assess creative output. The conservative estimate reflects the narrow scope of the selected test, not an absolute limit on bee behaviour.',bn:'এই দৃশ্য-পরিসংখ্যানগত শেখার গবেষণায় সৃজনশীল আউটপুট মাপা হয়নি। সতর্ক অনুমানটি নির্বাচিত পরীক্ষার সীমিত পরিসরকে প্রতিফলিত করে, মৌমাছির আচরণের চূড়ান্ত সীমা নয়।'},
        {score:65,basis:'Reasoning Based',en:'Choosing a target among visual scenes requires selective processing over repeated trials. Attention is inferred from the design rather than measured as a separate faculty.',bn:'বারবার পরীক্ষায় বিভিন্ন দৃশ্যের মধ্যে লক্ষ্য বেছে নিতে নির্বাচিত প্রক্রিয়াকরণ প্রয়োজন। পরীক্ষার নকশা থেকে মনোযোগ অনুমান করা হয়েছে, আলাদা সক্ষমতা হিসেবে মাপা হয়নি।'},
        {score:79,basis:'Evidence Based',en:'With increased exposure, bees shifted from relying on individual-element frequencies toward co-occurrence statistics. The experiment directly measures this learning pattern.',bn:'আরও দৃশ্য দেখার সঙ্গে মৌমাছি পৃথক উপাদানের পুনরাবৃত্তির ওপর নির্ভরতা থেকে সহ-উপস্থিতির পরিসংখ্যানের দিকে সরে গেছে। পরীক্ষাটি সরাসরি এই শেখার ধরন মাপে।'},
        {score:60,basis:'Reasoning Based',en:'The developing internal representation retained statistical structure across exposure, supporting a cautious estimate for task-specific memory. This was not a dedicated delayed-recall test.',bn:'দৃশ্যের সংস্পর্শে গড়ে ওঠা অভ্যন্তরীণ উপস্থাপনায় পরিসংখ্যানগত গঠন বজায় ছিল, যা নির্দিষ্ট কাজের স্মৃতির জন্য সতর্ক অনুমানকে সমর্থন করে। এটি বিলম্বিত স্মরণের আলাদা পরীক্ষা ছিল না।'},
        {score:62,basis:'Reasoning Based',en:'Other bee studies report learned number operations and abstract relations. Together with this paper, those findings support a bounded estimate for simple rule-based inference, not human-like general reasoning.',bn:'মৌমাছির অন্য গবেষণায় শেখানো সংখ্যাগত যোগ-বিয়োগ ও বিমূর্ত সম্পর্ক শেখার ফল রয়েছে। এই গবেষণার সঙ্গে মিলিয়ে এগুলো সরল নিয়মভিত্তিক অনুমানের সীমিত মান সমর্থন করে, মানুষের মতো সাধারণ যুক্তির নয়।'},
        {score:30,basis:'Reasoning Based',en:'The selected paper did not measure confidence or explicit self-monitoring. The estimate is kept low and should be read as a working hypothesis.',bn:'নির্বাচিত গবেষণাপত্রে আত্মবিশ্বাস বা স্পষ্ট আত্ম-পর্যবেক্ষণ মাপা হয়নি। অনুমানটি কম রাখা হয়েছে এবং প্রাথমিক ধারণা হিসেবে পড়া উচিত।'},
        {score:42,basis:'Reasoning Based',en:'The experiments required choosing and adapting a response across trials, but did not directly test multi-step planning or inhibition. The score is a cautious synthesis.',bn:'পরীক্ষায় একাধিক ধাপে সাড়া বেছে নেওয়া ও বদলানো দরকার ছিল, তবে বহু-ধাপের পরিকল্পনা বা বাধা দেওয়ার সরাসরি পরীক্ষা ছিল না। স্কোরটি সতর্ক সংশ্লেষ।'},
        {score:55,basis:'Reasoning Based',en:'Bees generalized visual-pattern learning to novel test displays. That supports a bounded problem-solving estimate within structured visual tasks rather than a general puzzle score.',bn:'মৌমাছি নতুন পরীক্ষামূলক দৃশ্যেও দৃশ্য-প্যাটার্ন শেখা সাধারণীকরণ করেছে। এটি কাঠামোবদ্ধ দৃশ্যভিত্তিক কাজের মধ্যে সীমিত সমস্যা-সমাধান অনুমানকে সমর্থন করে, সাধারণ ধাঁধার স্কোর নয়।'},
        {score:48,basis:'Reasoning Based',en:'Colony communication and cooperative foraging are important aspects of bee life, but this linked experiment measured visual learning rather than individual understanding of others. The estimate stays moderate.',bn:'উপনিবেশের যোগাযোগ ও সহযোগিতামূলক খাদ্যসংগ্রহ মৌমাছির জীবনের গুরুত্বপূর্ণ দিক, তবে এই গবেষণায় অন্যকে বোঝার বদলে দৃশ্য-শেখা মাপা হয়েছে। তাই মানটি মাঝামাঝি রাখা হয়েছে।'}
      ]
    }
  };
  function animalLabel(key) {
    const p = comparativeProfiles[key];
    return p ? (lang === 'bn' ? p.labelBn : p.labelEn) : key;
  }
  function animalFinding(key,index) {
    const p = comparativeProfiles[key];
    return p && p.faculties ? p.faculties[index] || null : null;
  }
  function animalFindingText(key,index) {
    const rating = animalFinding(key,index);
    if (rating) return `${basisLabel(rating.basis)} · ${lang === 'bn' ? rating.bn : rating.en}`;
    return lang === 'bn' ? 'যুক্তিনির্ভর অনুমান · এই সক্ষমতার জন্য সতর্ক অ্যাটলাস-অনুমান দেখানো হয়েছে।' : 'Reasoning-based estimate · A cautious estimate is used for this faculty.';
  }
  const facultyBn = {'Perception':'অনুধাবন','Generation':'সৃজন','Attention':'মনোযোগ','Learning':'শেখা','Memory':'স্মৃতি','Reasoning':'যুক্তি','Metacognition':'আত্মমূল্যায়ন','Executive functions':'পরিকল্পনা ও নিয়ন্ত্রণ','Problem solving':'সমস্যা সমাধান','Social cognition':'সামাজিক বোধ'};
  const descriptionsBn = {'Perception':'বাইরের তথ্য গ্রহণ করে তার অর্থ বোঝা।','Generation':'শব্দ, ছবি বা অন্য কিছু তৈরি করা এবং নির্দিষ্ট শর্ত মেনে কাজ সম্পন্ন করা।','Attention':'প্রাসঙ্গিক বিষয়ে মনোযোগ রাখা এবং বিভ্রান্তি এড়িয়ে চলা।','Learning':'উদাহরণ বা প্রতিক্রিয়া থেকে নতুন নিয়ম শেখা ও কাজে লাগানো।','Memory':'তথ্য ধরে রাখা এবং প্রয়োজনে তা মনে করা।','Reasoning':'যুক্তি, তুলনা, গণিত বা প্রমাণ দিয়ে সিদ্ধান্তে পৌঁছানো।','Metacognition':'নিজের জ্ঞানের সীমা বোঝা, ভুল প্রশ্ন শনাক্ত করা এবং আত্মবিশ্বাস বিচার করা।','Executive functions':'পরিকল্পনা করা, কৌশল বদলানো এবং পুরোনো অভ্যাস থামানো।','Problem solving':'নতুন ধাঁধা থেকে বাস্তব সমস্যা সমাধানে একাধিক দক্ষতা কাজে লাগানো।','Social cognition':'মানুষ কী ভাবছে বা অনুভব করছে, তা বুঝতে চেষ্টা করা।'};
  const confidenceBn = {'Published reference':'প্রকাশিত তুলনা','Vendor-reported AI result':'এআই প্রতিষ্ঠানের জানানো ফল','Estimated human reference':'মানব-স্কোর অনুমানভিত্তিক','Published AI result; harness matters':'প্রকাশিত এআই ফল; ব্যবহৃত সরঞ্জামও প্রভাব ফেলে','Published AI result; benchmark-specific':'প্রকাশিত এআই ফল; এই পরীক্ষার জন্য প্রযোজ্য','Small human sample':'মানব-নমুনা খুব ছোট','Different tests; interpret cautiously':'দুই পক্ষের পরীক্ষা আলাদা; সতর্কভাবে তুলনা করুন'};
  const comparisonNotes = {
    'Perception':'The reference is from untrained adults. The AI result has its own published setup; this is not a full distribution of human perceptual ability.',
    'Generation':'Important: the 50.0 human figure is expert-versus-expert parity by design; the 84.9 AI figure is vendor-reported wins or ties. Do not read the difference as AI beating an average person by 34.9 points.',
    'Attention':'The ~95 human figure is an estimate, not a measured population result. Treat this large gap as a useful hypothesis, not a settled human-capability boundary.',
    'Learning':'The human reference uses members of the public; the AI result used a custom harness. Near-ceiling scores can hide meaningful differences in the underlying task.',
    'Memory':'This is a task-specific long-conversation memory result, and the AI result includes a memory system. It is not a direct test of unaided human memory.',
    'Reasoning':'The human reference is PhD experts on GPQA Diamond. This tests difficult science questions, not every form of reasoning or everyday judgement.',
    'Metacognition':'The ~45 human figure is an estimate. The AI score is the best MetaBound result, while two other models scored 0%; one perfect score hides model variation.',
    'Executive functions':'The human group is university-educated testers, and the AI result involves the HAL setup. Tools, timing and task conditions affect the comparison.',
    'Problem solving':'The human reference is only nine non-specialists. A sample this small can move substantially and should not stand in for all people.',
    'Social cognition':'The human result is from Social IQa and the AI result from CogToM, which are different tests. The 4.4-point gap is not a direct head-to-head result.'
  };
  const comparisonNotesBn = {
    'Perception':'মানব-তুলনার স্কোরটি প্রশিক্ষণ না-দেওয়া প্রাপ্তবয়স্কদের কাছ থেকে নেওয়া। এআই-এর ফল নির্দিষ্ট পরীক্ষার সেটআপের ওপর নির্ভরশীল; এটি মানুষের উপলব্ধি-দক্ষতার পূর্ণ চিত্র নয়।',
    'Generation':'গুরুত্বপূর্ণ: ৫০.০ মানব-স্কোরটি বিশেষজ্ঞ বনাম বিশেষজ্ঞ সমতায় নির্ধারিত; ৮৪.৯ এআই-স্কোরটি প্রতিষ্ঠানের জানানো জয় বা সমতার ফল। এর অর্থ এআই গড় মানুষের চেয়ে ৩৪.৯ পয়েন্ট ভালো, এমন নয়।',
    'Attention':'প্রায় ৯৫ মানব-স্কোরটি অনুমান, জনসংখ্যার মাপা ফল নয়। বড় ব্যবধানটিকে চূড়ান্ত সিদ্ধান্ত নয়, যাচাইযোগ্য ধারণা হিসেবে দেখুন।',
    'Learning':'মানব-রেফারেন্সটি সাধারণ অংশগ্রহণকারীদের ফল; এআই-কে একটি কাস্টম সরঞ্জাম-সেটআপে পরীক্ষা করা হয়েছে। খুব বেশি স্কোর হলে পরীক্ষার সীমা বাস্তব পার্থক্য আড়াল করতে পারে।',
    'Memory':'এটি দীর্ঘ কথোপকথনে তথ্য মনে রাখার নির্দিষ্ট পরীক্ষা। এআই-এর ফলটি অতিরিক্ত স্মৃতি-ব্যবস্থাসহ পাওয়া; তাই এটি মানুষের কোনো সহায়তা ছাড়া মনে রাখার ক্ষমতার সরাসরি তুলনা নয়।',
    'Reasoning':'মানব-তুলনাটি GPQA Diamond পরীক্ষার পিএইচডি বিশেষজ্ঞদের। এটি কঠিন বিজ্ঞান-প্রশ্ন মাপে, সব ধরনের যুক্তি বা দৈনন্দিন বিচার নয়।',
    'Metacognition':'প্রায় ৪৫-এর মানব-স্কোরটি অনুমান। MetaBound-এ প্রকাশিত এআই ফল ১০০, কিন্তু আরও দুটি মডেল ০ পেয়েছে। শুধু সর্বোচ্চ স্কোর দেখলে মডেলগুলোর পার্থক্য বোঝা যায় না।',
    'Executive functions':'মানব-দলটি বিশ্ববিদ্যালয়-শিক্ষিত পরীক্ষার্থী; এআই ফলটি HAL সেটআপ ব্যবহার করেছে। টুল, সময় ও পরীক্ষার শর্ত ফলকে প্রভাবিত করে।',
    'Problem solving':'মানব-তুলনায় মাত্র নয়জন সাধারণ অংশগ্রহণকারী আছেন। এত ছোট নমুনায় ফল অনেকটা ওঠানামা করতে পারে; তাই এটিকে সবার প্রতিনিধিত্বকারী ধরা উচিত নয়.',
    'Social cognition':'মানব-ফল Social IQa থেকে, এআই ফল CogToM থেকে, অর্থাৎ পরীক্ষা দুটি আলাদা। ৪.৪ পয়েন্টের ব্যবধান সরাসরি মুখোমুখি তুলনা নয়।'
  };
  const everydayMeaning = {
    'Perception':'Perception turns sights, sounds and other signals into information you can use. It matters whenever the right detail must stand out in a busy world.',
    'Generation':'Generation turns ideas into words, images, code and other useful outputs. It matters because creation is often the first step in communication, design and problem execution.',
    'Attention':'Attention keeps the relevant signal in focus while distractions compete for it. It matters whenever one overlooked detail can change the outcome.',
    'Learning':'Learning turns examples and feedback into better performance on new situations. It matters because useful intelligence must adapt beyond the exact task it has seen.',
    'Memory':'Memory keeps past information available when a new decision depends on it. It matters across conversations, planning, expertise and continuity over time.',
    'Reasoning':'Reasoning connects evidence and rules to conclusions that can be checked. It matters when choices require more than recall, including analysis, diagnosis and planning.',
    'Metacognition':'Metacognition helps a thinker judge what it knows and when it may be wrong. It matters because calibrated confidence and knowing when to pause can prevent avoidable errors.',
    'Executive functions':'Executive functions organize steps, manage competing goals and change course when conditions shift. They matter when work needs sustained planning rather than one correct answer.',
    'Problem solving':'Problem solving combines knowledge and strategies to handle unfamiliar situations. It matters because real challenges rarely arrive in the same form as a practice example.',
    'Social cognition':'Social cognition helps interpret other people’s intentions, emotions and unspoken cues. It matters wherever collaboration, trust, negotiation or care depends on understanding people.'
  };
  const everydayMeaningBn = {
    'Perception':'অনুধাবন দৃষ্টি, শব্দ ও অন্যান্য সংকেতকে ব্যবহারযোগ্য তথ্যে রূপ দেয়। ব্যস্ত পরিবেশে সঠিক বিষয়টি চিনে নেওয়া জরুরি হলে এটি গুরুত্বপূর্ণ।',
    'Generation':'সৃজনশীলতা ভাবনাকে লেখা, ছবি, কোড ও অন্যান্য কাজে লাগার মতো ফলে রূপ দেয়। যোগাযোগ, নকশা ও সমস্যা সমাধানের শুরুতেই এটি গুরুত্বপূর্ণ।',
    'Attention':'মনোযোগ প্রাসঙ্গিক সংকেতকে সামনে রাখে, যখন নানা বিভ্রান্তি প্রতিযোগিতা করে। একটি বাদ পড়া তথ্য ফল বদলে দিতে পারে, এমন কাজে এটি গুরুত্বপূর্ণ।',
    'Learning':'শেখা উদাহরণ ও প্রতিক্রিয়া থেকে নতুন পরিস্থিতিতে ভালোভাবে কাজ করতে সাহায্য করে। আগে দেখা কাজের বাইরে মানিয়ে নেওয়ার প্রয়োজন হলেই এটি গুরুত্বপূর্ণ।',
    'Memory':'স্মৃতি আগের তথ্যকে ধরে রাখে, যাতে নতুন সিদ্ধান্তে তা কাজে লাগে। কথোপকথন, পরিকল্পনা, অভিজ্ঞতা ও ধারাবাহিকতার জন্য এটি গুরুত্বপূর্ণ।',
    'Reasoning':'যুক্তি প্রমাণ ও নিয়মকে যাচাইযোগ্য সিদ্ধান্তের সঙ্গে যুক্ত করে। শুধু তথ্য মনে রাখলেই চলে না, এমন বিশ্লেষণ, নির্ণয় ও পরিকল্পনায় এটি গুরুত্বপূর্ণ।',
    'Metacognition':'আত্মমূল্যায়ন কী জানা আছে এবং কোথায় ভুল হতে পারে, তা বিচার করতে সাহায্য করে। আত্মবিশ্বাস মেপে নেওয়া ও প্রয়োজন হলে থামা ভুল কমাতে গুরুত্বপূর্ণ।',
    'Executive functions':'পরিকল্পনা ও নিয়ন্ত্রণ কাজের ধাপ সাজায়, একাধিক লক্ষ্য সামলায় এবং পরিস্থিতি বদলালে পথ বদলায়। দীর্ঘমেয়াদি পরিকল্পনা দরকার এমন কাজে এগুলো গুরুত্বপূর্ণ।',
    'Problem solving':'সমস্যা সমাধান অচেনা পরিস্থিতিতে জ্ঞান ও কৌশল একসঙ্গে কাজে লাগায়। বাস্তব সমস্যা অনুশীলনের উদাহরণের হুবহু পুনরাবৃত্তি হয় না, তাই এটি গুরুত্বপূর্ণ।',
    'Social cognition':'সামাজিক বোধ অন্যের উদ্দেশ্য, অনুভূতি ও না-বলা ইঙ্গিত বুঝতে সাহায্য করে। সহযোগিতা, আস্থা, আলোচনা ও যত্নে মানুষকে বোঝা জরুরি বলে এটি গুরুত্বপূর্ণ।'
  };
  const workImplications = {
    'Perception':'Use AI for first-pass visual checks only after testing it on messy images and real edge cases. Keep a person responsible for consequential decisions.',
    'Generation':'Let AI draft or remix work where a reviewer can check facts, tone, rights and quality before anything reaches a customer.',
    'Attention':'Test whether the system spots the right signal when instructions conflict or distractors are deliberately introduced. The human baseline here is estimated.',
    'Learning':'Test adaptation on new rules and unseen examples, not just a familiar benchmark. Near-ceiling scores can hide brittleness.',
    'Memory':'For long workflows, measure what is recalled, what is forgotten and whether stale information is treated as current. This AI result uses a memory system.',
    'Reasoning':'Use model assistance for bounded analytical work, then verify sources, assumptions and calculations. Expert-level test performance is not universal judgement.',
    'Metacognition':'Ask the system to flag uncertainty and abstain when evidence is weak. Verify calibration on real cases; one benchmark result cannot prove general self-knowledge.',
    'Executive functions':'Trial AI on bounded plans with reversible actions, explicit checkpoints and a human escalation path when the situation changes.',
    'Problem solving':'Pilot on unfamiliar cases from the actual workflow. This human reference has only nine participants, so it is not a stable workforce benchmark.',
    'Social cognition':'Use extra review for sensitive conversations. These human and AI results come from different tests, so they do not establish real-world equivalence.'
  };
  const workImplicationsBn = {
    'Perception':'এআই-কে দৃশ্য-যাচাইয়ে ব্যবহার করার আগে জটিল ছবি ও বাস্তব ব্যতিক্রমে পরীক্ষা করুন। গুরুত্বপূর্ণ সিদ্ধান্তের দায় মানুষের কাছে রাখুন।',
    'Generation':'এআই-কে খসড়া তৈরিতে ব্যবহার করুন, তবে গ্রাহকের কাছে পাঠানোর আগে তথ্য, ভাষা, অধিকার ও মান যাচাই করান।',
    'Attention':'নির্দেশনায় দ্বন্দ্ব বা বিভ্রান্তিকর সংকেত থাকলে সিস্টেম সঠিক বিষয়টি ধরতে পারে কি না পরীক্ষা করুন। মানব-তুলনাটি অনুমানভিত্তিক।',
    'Learning':'নতুন নিয়ম ও অচেনা উদাহরণে মানিয়ে নেওয়া যাচাই করুন। প্রায় পূর্ণ নম্বরও ভঙ্গুরতা আড়াল করতে পারে।',
    'Memory':'দীর্ঘ কাজে কী মনে থাকে, কী ভুলে যায় এবং পুরোনো তথ্যকে বর্তমান ধরে কি না মাপুন। এআই ফলের সঙ্গে স্মৃতি-ব্যবস্থা যুক্ত আছে।',
    'Reasoning':'সীমিত বিশ্লেষণী কাজে এআই সহায়তা নিন, তারপর উৎস, অনুমান ও হিসাব যাচাই করুন। বিশেষজ্ঞ-পরীক্ষার ফল সব পরিস্থিতির বিচারবুদ্ধি নয়।',
    'Metacognition':'প্রমাণ দুর্বল হলে অনিশ্চয়তা জানাতে ও উত্তর না দিতে সিস্টেমকে পরীক্ষা করুন। একটি ফল সাধারণ আত্মজ্ঞান প্রমাণ করে না।',
    'Executive functions':'সীমিত পরিকল্পনায় এআই পরীক্ষা করুন; কাজগুলো প্রত্যাবর্তনযোগ্য রাখুন এবং পরিস্থিতি বদলালে মানুষের কাছে পাঠানোর ধাপ রাখুন।',
    'Problem solving':'নিজের কাজের অচেনা বাস্তব কেসে পরীক্ষা চালান। নয়জনের মানব-নমুনা কর্মশক্তির নির্ভরযোগ্য মানদণ্ড নয়।',
    'Social cognition':'সংবেদনশীল কথোপকথনে মানব-পর্যালোচনা রাখুন। দুই ফল আলাদা পরীক্ষা থেকে এসেছে, তাই বাস্তব সমতা প্রমাণিত নয়।'
  };
  let lang = 'en';
  const $ = (s) => document.querySelector(s);
  // Recompose the existing modules into one instrument stage and one evidence rail.
  const shell = $('.shell');
  const explorer = $('.explorer');
  const stagePanel = $('.galaxy-panel');
  const stageLog = $('.activity-log');
  const stageCanvas = $('#canvasWrap');
  const metricPanel = $('.metrics');
  const inspectorPanel = $('.sidepanel');
  const calibrationPanel = $('.calibration-strip');
  const impactPanel = $('.impact-section');
  const watchPanel = $('.watch-section');
  const dataPanel = $('.data-note');
  // Put reference links beside the content they explain, not beside layout controls.
  const calibrationInfo = $('.calibration-mark');
  const calibrationText = $('#calibrationText');
  const calibrationLink = $('#calibrationLink');
  const takeTestLink = $('#takeTestLink');
  const facultySourceLink = $('#facultySourceLink');
  const methodLink = $('#methodLink');
  const sourceFooterLink = $('#sourceLink');
  if (sourceFooterLink) sourceFooterLink.remove();
  if (methodLink && calibrationLink) {
    methodLink.insertAdjacentElement('afterend', calibrationLink);
    calibrationLink.classList.add('comparison-method-link');
  }
  if (facultySourceLink && takeTestLink) {
    facultySourceLink.insertAdjacentElement('afterend', takeTestLink);
    takeTestLink.classList.add('test-inline');
  }
  const calibrationLinks = $('.calibration-links');
  if (calibrationLinks) calibrationLinks.remove();
  // Add the evidence passport and export controls inside the existing inspector, preserving its layout.
  const modelBlockForEvidence = $('.model-block');
  const atlasActionRow = document.createElement('div');
  atlasActionRow.className = 'atlas-action-row';
  atlasActionRow.innerHTML = '<button type="button" class="atlas-action primary" id="atlasDownloadCard">Save a copy for you</button><span class="evidence-hover-wrap"><button type="button" class="atlas-action" id="atlasEvidencePassport" aria-describedby="evidencePassport" aria-label="See evidence passport">See evidence passport</button><span class="evidence-passport" id="evidencePassport" role="tooltip"><strong class="evidence-passport-heading" id="evidencePassportSummary">Evidence passport</strong><ul class="evidence-passport-content" id="evidencePassportContent"></ul></span></span>';
  const evidencePassport = atlasActionRow.querySelector('#evidencePassport');
  const evidencePassportSummary = atlasActionRow.querySelector('#evidencePassportSummary');
  const evidencePassportContent = atlasActionRow.querySelector('#evidencePassportContent');
  const atlasActionStatus = document.createElement('div');
  atlasActionStatus.className = 'atlas-action-status';
  atlasActionStatus.id = 'atlasActionStatus';
  atlasActionStatus.setAttribute('role','status');
  atlasActionStatus.setAttribute('aria-live','polite');
  if (modelBlockForEvidence) modelBlockForEvidence.append(atlasActionRow, atlasActionStatus);
  const scenarioResultForStamp = $('.scenario-result');
  const scenarioStamp = document.createElement('div');
  scenarioStamp.className = 'scenario-stamp';
  scenarioStamp.id = 'scenarioStamp';
  scenarioStamp.setAttribute('aria-live','polite');
  if (scenarioResultForStamp) scenarioResultForStamp.appendChild(scenarioStamp);
  if (calibrationInfo && calibrationText) {
    calibrationInfo.setAttribute('tabindex', '0');
    calibrationInfo.setAttribute('role', 'button');
    calibrationInfo.setAttribute('aria-label', 'Show comparison notes');
    calibrationInfo.setAttribute('aria-describedby', 'calibrationText');
    calibrationText.setAttribute('role', 'tooltip');
    calibrationText.classList.add('calibration-tooltip');
  }
  const layout = document.createElement('div');
  layout.className = 'cosmos-layout';
  const stageColumn = document.createElement('section');
  stageColumn.className = 'stage-column';
  stageColumn.setAttribute('aria-label', 'Interactive capability instrument');
  const rightRail = document.createElement('aside');
  rightRail.className = 'right-rail';
  rightRail.setAttribute('aria-label', 'Capability evidence, comparison and implications');
  shell.insertBefore(layout, metricPanel);
  layout.append(stageColumn, rightRail);
  stageColumn.appendChild(stagePanel);
  stagePanel.insertBefore(stageLog, stageCanvas);
  rightRail.append(metricPanel, inspectorPanel, impactPanel, watchPanel, dataPanel);
  // Let the viewer resize rail rows and the two detail columns without changing the overall page frame.
  const railRowElements = [metricPanel, inspectorPanel, impactPanel, watchPanel, dataPanel];
  const railRowMinimums = [58, 300, 70, 66, 42];
  let layoutEditing = false, customRailRowRatios = null, customSidepanelRatio = null, resizeDrag = null;
  const railLayoutTools = document.createElement('div');
  railLayoutTools.className = 'rail-layout-tools';
  railLayoutTools.innerHTML = '<span class="rail-layout-hint">Drag red grips to resize</span><button class="rail-layout-reset" type="button">Reset sizes</button><button class="rail-layout-toggle" type="button" aria-pressed="false">Adjust layout</button>';
  const railLayoutToggle = railLayoutTools.querySelector('.rail-layout-toggle');
  const railLayoutReset = railLayoutTools.querySelector('.rail-layout-reset');
  calibrationPanel.appendChild(railLayoutTools);
  const rowResizeHandles = [];
  function readRailRows() {
    const tracks = getComputedStyle(rightRail).gridTemplateRows.split(/\s+/).map(parseFloat).filter(Number.isFinite);
    return tracks.length === railRowElements.length ? tracks : null;
  }
  function applyRailRows(sizes) {
    const safe = sizes.map((size, i) => Math.max(railRowMinimums[i], size));
    const total = safe.reduce((sum, size) => sum + size, 0) || 1;
    rightRail.style.gridTemplateRows = safe.map(size => `${size.toFixed(1)}px`).join(' ');
    customRailRowRatios = safe.map(size => size / total);
  }
  function railContentHeight() {
    const style = getComputedStyle(rightRail);
    return Math.max(1, rightRail.clientHeight - (parseFloat(style.paddingTop) || 0) - (parseFloat(style.paddingBottom) || 0));
  }
  function restoreRailRatiosForViewport() {
    if (!layoutEditing || !customRailRowRatios || window.innerWidth < 1100) return;
    const height = railContentHeight();
    rightRail.style.gridTemplateRows = customRailRowRatios.map(ratio => `${(height * ratio).toFixed(1)}px`).join(' ');
  }
  function updateColumnHandle() {
    const first = inspectorPanel.querySelector('.inspector');
    const second = inspectorPanel.querySelector('.projection-card');
    if (!first || !second || !inspectorPanel.contains(columnResizeHandle)) return;
    const outer = inspectorPanel.getBoundingClientRect(), a = first.getBoundingClientRect(), b = second.getBoundingClientRect();
    columnResizeHandle.style.left = `${((a.right + b.left) / 2) - outer.left}px`;
  }
  function availableSidepanelWidth() {
    const style = getComputedStyle(inspectorPanel);
    return Math.max(1, inspectorPanel.clientWidth - (parseFloat(style.columnGap) || 0));
  }
  function applySidepanelRatio(ratio) {
    const available = availableSidepanelWidth();
    const min = Math.min(140, available * .34);
    const max = Math.max(min, available - Math.min(150, available * .34));
    const left = Math.max(min, Math.min(max, available * ratio));
    inspectorPanel.style.gridTemplateColumns = `${left.toFixed(1)}px minmax(0,1fr)`;
    customSidepanelRatio = left / available;
    updateColumnHandle();
  }
  function setLayoutEditing(active) {
    layoutEditing = active;
    rightRail.classList.toggle('layout-editing', active);
    const isBn = document.documentElement.lang === 'bn';
    railLayoutToggle.textContent = isBn ? (active ? 'বিন্যাস সম্পন্ন' : 'বিন্যাস বদলান') : (active ? 'Done adjusting' : 'Adjust layout');
    railLayoutToggle.setAttribute('aria-pressed', String(active));
    if (active) {
      updateColumnHandle();
      if (customRailRowRatios) restoreRailRatiosForViewport();
      if (customSidepanelRatio !== null) applySidepanelRatio(customSidepanelRatio);
    } else {
      resizeDrag = null;
    }
  }
  railLayoutToggle.addEventListener('click', () => setLayoutEditing(!layoutEditing));
  railLayoutReset.addEventListener('click', () => {
    customRailRowRatios = null;
    customSidepanelRatio = null;
    rightRail.style.removeProperty('grid-template-rows');
    inspectorPanel.style.removeProperty('grid-template-columns');
    updateColumnHandle();
  });
  railRowElements.forEach((element, index) => {
    if (index === railRowElements.length - 1) return;
    const handle = document.createElement('button');
    handle.type = 'button';
    handle.className = 'rail-row-resize';
    handle.setAttribute('aria-label', document.documentElement.lang === 'bn'
      ? ['সারাংশ','তুলনার বিবরণ','প্রভাব','ওয়াচলিস্ট'][index] + ' অংশের উচ্চতা বদলান'
      : `Resize ${['summary','comparison details','impact','watchlist'][index]} section height`);
    handle.title = document.documentElement.lang === 'bn' ? 'টেনে পাশের অংশগুলোর মাপ বদলান' : 'Drag to resize adjoining sections';
    element.appendChild(handle);
    rowResizeHandles.push({handle, index});
    handle.addEventListener('pointerdown', event => {
      if (!layoutEditing || window.innerWidth < 1100 || event.button !== 0) return;
      const sizes = readRailRows();
      if (!sizes || sizes.length !== railRowElements.length) return;
      resizeDrag = {type:'row', index, startY:event.clientY, sizes, pointerId:event.pointerId};
      handle.setPointerCapture(event.pointerId);
      event.preventDefault();
    });
    handle.addEventListener('pointermove', event => {
      if (!resizeDrag || resizeDrag.type !== 'row' || resizeDrag.index !== index || resizeDrag.pointerId !== event.pointerId) return;
      const next = [...resizeDrag.sizes], before = index, after = index + 1;
      const combined = next[before] + next[after], minBefore = railRowMinimums[before], minAfter = railRowMinimums[after];
      next[before] = Math.max(minBefore, Math.min(combined - minAfter, resizeDrag.sizes[before] + event.clientY - resizeDrag.startY));
      next[after] = combined - next[before];
      applyRailRows(next);
      event.preventDefault();
    });
    const finishRowDrag = event => { if (resizeDrag?.type === 'row' && resizeDrag.index === index && resizeDrag.pointerId === event.pointerId) resizeDrag = null; };
    handle.addEventListener('pointerup', finishRowDrag);
    handle.addEventListener('pointercancel', finishRowDrag);
    handle.addEventListener('keydown', event => {
      if (!layoutEditing || !['ArrowUp','ArrowDown'].includes(event.key)) return;
      const sizes = readRailRows(); if (!sizes) return;
      const next = [...sizes], before = index, after = index + 1, combined = next[before] + next[after];
      next[before] = Math.max(railRowMinimums[before], Math.min(combined - railRowMinimums[after], next[before] + (event.key === 'ArrowDown' ? 10 : -10)));
      next[after] = combined - next[before]; applyRailRows(next); event.preventDefault();
    });
  });
  const columnResizeHandle = document.createElement('button');
  columnResizeHandle.type = 'button';
  columnResizeHandle.className = 'rail-column-resize';
  columnResizeHandle.setAttribute('aria-label', 'Resize comparison and future panels');
  columnResizeHandle.title = 'Drag to resize the two detail columns';
  inspectorPanel.appendChild(columnResizeHandle);
  columnResizeHandle.addEventListener('pointerdown', event => {
    if (!layoutEditing || window.innerWidth < 1100 || event.button !== 0) return;
    const first = inspectorPanel.querySelector('.inspector');
    const available = availableSidepanelWidth();
    if (!first || !available) return;
    resizeDrag = {type:'column', startX:event.clientX, startWidth:first.getBoundingClientRect().width, available, pointerId:event.pointerId};
    columnResizeHandle.setPointerCapture(event.pointerId);
    event.preventDefault();
  });
  columnResizeHandle.addEventListener('pointermove', event => {
    if (!resizeDrag || resizeDrag.type !== 'column' || resizeDrag.pointerId !== event.pointerId) return;
    applySidepanelRatio((resizeDrag.startWidth + event.clientX - resizeDrag.startX) / resizeDrag.available);
    event.preventDefault();
  });
  const finishColumnDrag = event => { if (resizeDrag?.type === 'column' && resizeDrag.pointerId === event.pointerId) resizeDrag = null; };
  columnResizeHandle.addEventListener('pointerup', finishColumnDrag);
  columnResizeHandle.addEventListener('pointercancel', finishColumnDrag);
  columnResizeHandle.addEventListener('keydown', event => {
    if (!layoutEditing || !['ArrowLeft','ArrowRight'].includes(event.key)) return;
    const current = inspectorPanel.querySelector('.inspector')?.getBoundingClientRect().width || availableSidepanelWidth() * .52;
    applySidepanelRatio((current + (event.key === 'ArrowRight' ? 12 : -12)) / availableSidepanelWidth());
    event.preventDefault();
  });
  window.addEventListener('resize', () => {
    restoreRailRatiosForViewport();
    if (layoutEditing && customSidepanelRatio !== null && window.innerWidth >= 1100) applySidepanelRatio(customSidepanelRatio);
    else updateColumnHandle();
  }, {passive:true});
  explorer.remove();
  const canvas = $('#cosmos');
  const ctx = canvas.getContext('2d');
  const wrap = $('#canvasWrap');
  const tooltip = $('#tooltip');
  let selected = 0, comparator = 'ai', rate = 3, years = 0, yaw = -0.35, pitch = 0.9, zoom = 1, drag = null, hover = null, points = [], links = [], raf = null, last = 0, focusMotion = null;
  // Shared links restore the same faculty, comparator, lens, language and scenario inputs.
  const allowedViews = new Set(['cosmos','frontier','trajectory','evidence','impact']);
  const allowedComparators = new Set(['ai','chimpanzee','dog','honeybee']);
  try {
    const sharedState = new URLSearchParams(window.location.search);
    const facultyParam = Number(sharedState.get('faculty'));
    const viewParam = sharedState.get('view');
    const comparatorParam = sharedState.get('compare');
    const yearParam = Number(sharedState.get('year'));
    const rateParam = Number(sharedState.get('rate'));
    const langParam = sharedState.get('lang');
    if (Number.isInteger(facultyParam) && facultyParam >= 0 && facultyParam < data.length) selected = facultyParam;
    if (allowedComparators.has(comparatorParam)) comparator = comparatorParam;
    if (allowedViews.has(viewParam)) {
      wrap.dataset.view = viewParam;
      document.querySelectorAll('.mode-switch button').forEach(button => button.setAttribute('aria-pressed', String(button.dataset.view === viewParam)));
    }
    if ([1,3,6].includes(rateParam)) rate = rateParam;
    if (Number.isInteger(yearParam) && yearParam >= 0 && yearParam <= 5 && comparator === 'ai') years = yearParam;
    if (langParam === 'en' || langParam === 'bn') lang = langParam;
    if (lang === 'bn') document.documentElement.lang = 'bn';
    $('#comparatorSelect').value = comparator;
    $('#facultySelect').value = String(selected);
    $('#horizon').value = String(years);
  } catch (error) {
    // A malformed query string must never stop the atlas from opening.
  }
  const prefersReduced = window.matchMedia('(prefers-reduced-motion: reduce)').matches;
  let autoSpin = true;
  const clamp = (v,a,b) => Math.max(a,Math.min(b,v));
  const fmt = v => Number(v).toFixed(1);
  const toBanglaNumber = value => String(value).replace(/[0-9]/g, digit => '০১২৩৪৫৬৭৮৯'[Number(digit)]);
  const gap = d => isAnimalComparator() ? 0 : d.human - comparisonScore(d, data.indexOf(d), false);
  function comparatorName() {
    if (comparator === 'ai') return lang==='bn' ? 'এআই' : 'AI';
    return animalLabel(comparator);
  }
  function comparatorLabel() {
    if(comparator==='ai') return lang==='bn'?'এআই-এর প্রকাশিত ফল':'AI published result';
    return comparatorName();
  }
  function isAnimalComparator() { return comparator !== 'ai'; }
  function comparisonScore(d,index,projected=false) {
    if(isAnimalComparator()) return null;
    return projected ? futureAI(d) : d.ai;
  }
  function displayName(name) { return lang === 'bn' ? (facultyBn[name] || name) : name; }
  function setText(id, value) { const el = document.getElementById(id); if (el) el.textContent = value; }
  function normalize3(v) { const m=Math.hypot(v.x,v.y,v.z)||1; return {x:v.x/m,y:v.y/m,z:v.z/m}; }
  function cross3(a,b) { return {x:a.y*b.z-a.z*b.y,y:a.z*b.x-a.x*b.z,z:a.x*b.y-a.y*b.x}; }
  function buildFacultySelect() {
    const select = $('#facultySelect');
    if (!select) return;
    select.innerHTML = '';
    data.forEach((d, i) => { const option = document.createElement('option'); option.value = String(i); option.textContent = displayName(d.name); select.appendChild(option); });
    select.value = String(selected);
  }
  function updateActivityLog() {
    const list=$('#activityEntries');
    if(!list)return;
    setText('activityLogTitle',lang==='bn'?'সক্ষমতার প্রমাণ':'FACULTY EVIDENCE');
    setText('activityLogCount',lang==='bn'?'১০টি সক্ষমতা':'10 FACULTIES');
    setText('journeyHint',lang==='bn'?'পরের সক্ষমতা দেখুন ↗':'EXPLORE NEXT CAPABILITY ↗');
    list.innerHTML='';
    data.forEach((d,i)=>{
      const button=document.createElement('button');button.type='button';button.className='activity-entry';button.setAttribute('aria-current',String(i===selected));
      if(isAnimalComparator()) {
        const finding=animalFinding(comparator,i);
        button.setAttribute('aria-label',lang==='bn'?`${displayName(d.name)}। ${toBanglaNumber(finding.score)} / ১০০। ${basisLabel(finding.basis,true)}। সক্ষমতা নির্বাচন করুন।`:`${displayName(d.name)}. ${finding.score} / 100. ${basisLabel(finding.basis,false)}. Select faculty.`);
        button.title=animalFindingText(comparator,i);
        const number=document.createElement('span');number.className='activity-num';number.textContent=String(i+1).padStart(2,'0');
        const name=document.createElement('span');name.className='activity-name';name.textContent=displayName(d.name);
        const mark=document.createElement('span');mark.className='activity-gap '+(finding.basis==='Evidence Based'?'ai-leading':'');mark.textContent=String(finding.score);
        button.append(number,name,mark);
      } else {
        button.setAttribute('aria-label', lang === 'bn'
          ? `${displayName(d.name)}। মানব-রেফারেন্স ${fmt(d.human)}। ${comparatorLabel()} ${fmt(comparisonScore(d,i,years>0))}। এই সক্ষমতা বেছে নিন।`
          : `${displayName(d.name)}. Human reference ${fmt(d.human)}. ${comparatorLabel()} ${fmt(comparisonScore(d,i,years>0))}. Select capability.`);
        button.title = lang === 'bn' ? descriptionsBn[d.name] : d.desc;
        const number=document.createElement('span');number.className='activity-num';number.textContent=String(i+1).padStart(2,'0');
        const name=document.createElement('span');name.className='activity-name';name.textContent=displayName(d.name);
        const delta=comparisonScore(d,i,years>0)-d.human,gapText=document.createElement('span');gapText.className='activity-gap'+(delta>5?' ai-leading':'');gapText.textContent=(delta>0?'+':delta<0?'−':'')+Math.abs(delta).toFixed(1);
        button.append(number,name,gapText);
      }
      button.addEventListener('click',()=>selectFaculty(i));list.appendChild(button);
    });
  }
  function focusFaculty(index, immediate=false) {
    const a=facultyAnchors[index];
    const target={yaw:Math.atan2(a.x,a.z),pitch:Math.atan2(a.y,Math.hypot(a.x,a.z))};
    if(immediate||prefersReduced){yaw=target.yaw;pitch=target.pitch;focusMotion=null;}
    else focusMotion=target;
  }
  function selectFaculty(index) { selected = (index + data.length) % data.length; focusFaculty(selected); $('#facultySelect').value = String(selected); updateInspector(); applyDynamicLanguage(); draw(); }
  function evidenceRisk(d) { const c=d.confidence.toLowerCase(); return (c.includes('estimated')||c.includes('different tests')||c.includes('vendor-reported'))?3:(c.includes('small')||c.includes('harness'))?2:1; }
  function updateWatchlist() {
    const list = $('#watchList');
    if (!list) return;
    list.innerHTML = '';
    const mode=wrap.dataset.view||'cosmos';
    if(isAnimalComparator()) {
      const rows=data.map((d,i)=>({d,i,finding:animalFinding(comparator,i)}));
      rows.sort((a,b)=>b.finding.score-a.finding.score);
      rows.slice(0,3).forEach(item=>{
        const button=document.createElement('button');button.type='button';button.className='watch-item';button.dataset.index=String(item.i);
        const name=document.createElement('span');name.className='watch-name';name.textContent=displayName(item.d.name);
        const note=document.createElement('span');note.className='watch-gap';note.textContent=basisLabel(item.finding.basis,lang==='bn');
        const score=document.createElement('span');score.className='watch-score';score.textContent=lang==='bn'?toBanglaNumber(item.finding.score)+' / ১০০':item.finding.score+' / 100';
        button.title=animalFindingText(comparator,item.i);
        button.append(name,note,score);button.addEventListener('click',()=>selectFaculty(item.i));list.appendChild(button);
      });
      return;
    }
    const rows=data.map((d,i)=>({d,i,gap:Math.abs(d.human-comparisonScore(d,i,mode==='trajectory'&&years>0)),risk:evidenceRisk(d),advantage:comparisonScore(d,i,mode==='trajectory'&&years>0)-d.human}));
    rows.sort((a,b)=>mode==='frontier'?b.gap-a.gap:mode==='evidence'?(b.risk-a.risk||b.gap-a.gap):mode==='impact'?b.advantage-a.advantage:mode==='trajectory'?a.gap-b.gap:a.gap-b.gap);
    rows.slice(0,3).forEach(item => {
      const button = document.createElement('button'); button.type = 'button'; button.className = 'watch-item'; button.dataset.index = String(item.i);
      const name = document.createElement('span'); name.className = 'watch-name'; name.textContent = displayName(item.d.name);
      const note = document.createElement('span'); note.className = 'watch-gap'; note.textContent = lang === 'bn' ? (mode==='evidence'?'প্রমাণ-সতর্কতা: '+item.risk+'/৩':mode==='trajectory'?'দৃশ্যপটের ব্যবধান':'দুই স্কোরের ব্যবধান') : (mode==='evidence'?'Evidence risk: '+item.risk+'/3':mode==='trajectory'?'Scenario gap':'Reported score gap');
      const score = document.createElement('span'); score.className = 'watch-score'; score.textContent = item.gap.toFixed(1) + (lang === 'bn' ? ' পয়েন্ট' : ' pts');
      button.append(name, note, score); button.addEventListener('click', () => selectFaculty(item.i)); list.appendChild(button);
    });
  }
  const modeCopy = {
    cosmos:{
      en:{title:'The human vs other intelligence frontier',subtitle:'GEODESIC ATLAS · TEN FACULTIES · SELECT A NODE TO BRING IT FORWARD',heading:'How to read the field',summary:'Three cues tie the visual map to the comparison.',items:[['01 / THE SYSTEM','Ten mapped faculties','Every named point is anchored to a vertex in the same geodesic mesh.'],['02 / THE PAIR','Two results, one task family','Black marks the human reference; signal red marks the AI result.'],['03 / THE INTERACTION','Select, rotate, inspect','The camera follows your selection; details update with the point.']],watch:'Explore a faculty',watchSub:'Choose a point to bring it to the front and inspect its source notes.'},
      bn:{title:'মানুষ বনাম অন্যান্য বুদ্ধিমত্তার সীমারেখা',subtitle:'জ্যামিতিক গোলক · দশটি সক্ষমতা · কোনো বিন্দু বাছলে সামনে আসবে',heading:'মানচিত্রটি কীভাবে পড়বেন',summary:'দৃশ্য ও তুলনার সম্পর্ক বোঝার তিনটি সূত্র।',items:[['০১ / কাঠামো','দশটি নির্দিষ্ট সক্ষমতা','প্রতিটি নাম গোলকের একই জ্যামিতিক জালের একটি নির্দিষ্ট বিন্দুতে বাঁধা।'],['০২ / জোড়া ফল','দুটি ফল, একটি সক্ষমতা-পরিবার','কালো চিহ্ন মানব-তুলনা; লাল চিহ্ন এআই ফল।'],['০৩ / ইন্টার‌্যাকশন','বাছুন, ঘোরান, পরীক্ষা করুন','ক্যামেরা নির্বাচিত বিন্দু অনুসরণ করে; তথ্যও তার সঙ্গে বদলায়।']],watch:'একটি সক্ষমতা দেখুন',watchSub:'বিন্দু বাছলে গোলকটি সামনে ঘুরবে এবং উৎসের নোট দেখাবে।'}
    },
    frontier:{
      en:{title:'Where do reported scores separate?',subtitle:'GAP MAP · MARKER SEPARATION CUES ABSOLUTE GAP · STATUS SHOWS WHO LEADS',heading:'Read the distance carefully',summary:'A visible gap is a prompt to investigate, not a universal ranking.',items:[['01 / DISTANCE','Larger arc, wider gap','Pair separation grows with the absolute score difference in this snapshot.'],['02 / DIRECTION','Check who leads','The inspector gives the signed comparison; distance alone does not show direction.'],['03 / LIMIT','Not one shared test','Different benchmarks and reference groups can make gaps misleading.']],watch:'Largest reported gaps',watchSub:'Ranked by absolute score difference. Select a pair to examine its caveat.'},
      bn:{title:'কোথায় স্কোরের ব্যবধান?',subtitle:'ব্যবধান মানচিত্র · চিহ্নের দূরত্বে পার্থক্য · অবস্থায় কে এগিয়ে',heading:'ব্যবধান বুঝে পড়ুন',summary:'দৃশ্যমান পার্থক্য যাচাইয়ের সংকেত, সর্বজনীন র‌্যাঙ্কিং নয়।',items:[['০১ / দূরত্ব','বড় দূরত্ব, বড় ব্যবধান','এই স্ন্যাপশটে দুই স্কোরের ব্যবধান বাড়লে চিহ্নের দূরত্বও বাড়ে।'],['০২ / দিক','কে এগিয়ে দেখুন','বিশ্লেষণ দিকটি জানায়; দূরত্ব একা তা বলে না।'],['০৩ / সীমা','একই পরীক্ষা নয়','ভিন্ন বেঞ্চমার্ক ও মানব-তুলনায় ব্যবধান বিভ্রান্তিকর হতে পারে।']],watch:'সবচেয়ে বড় প্রকাশিত ব্যবধান',watchSub:'সংখ্যাগত ব্যবধান অনুযায়ী সাজানো। সীমাবদ্ধতা দেখতে জোড়া বাছুন।'}
    },
    trajectory:{
      en:{title:'What changes under a scenario?',subtitle:'PATH MODE · CHANGE THE HORIZON AND ASSUMED AI UPLIFT · NOT A FORECAST',heading:'Change the assumption, watch the field',summary:'A deliberately simple scenario keeps each assumption visible.',items:[['01 / ASSUMPTION','Choose a growth rate','The slider applies a fixed annual uplift to the reported AI score.'],['02 / COMPARISON','Human reference stays fixed','Only the AI score moves; the view isolates one assumption at a time.'],['03 / BOUNDARY','No probability implied','This is not a fitted trend, confidence interval or job prediction.']],watch:'Where the scenario narrows the gap',watchSub:'Sorted by the remaining score difference under the selected scenario.'},
      bn:{title:'দৃশ্যপট বদলালে কী বদলায়?',subtitle:'সম্ভাব্য পথ · সময় ও এআই বৃদ্ধির অনুমান বদলান · পূর্বাভাস নয়',heading:'অনুমান বদলান, মানচিত্র দেখুন',summary:'সহজ দৃশ্যপটের প্রতিটি অনুমান স্পষ্ট রাখা হয়েছে।',items:[['০১ / অনুমান','বৃদ্ধির হার বাছুন','স্লাইডার প্রকাশিত এআই স্কোরে প্রতি বছরের নির্দিষ্ট বৃদ্ধি যোগ করে।'],['০২ / তুলনা','মানব-স্কোর স্থির থাকে','একটি অনুমানের প্রভাব দেখতে শুধু এআই ফল নড়ে।'],['০৩ / সীমা','সম্ভাব্যতা বোঝায় না','এটি ইতিহাসভিত্তিক প্রবণতা বা চাকরির পূর্বাভাস নয়।']],watch:'দৃশ্যপটে ব্যবধান যেখানে কমে',watchSub:'নির্বাচিত দৃশ্যপটে অবশিষ্ট স্কোরের ব্যবধান অনুযায়ী সাজানো।'}
    },
    evidence:{
      en:{title:'How strong is each comparison?',subtitle:'EVIDENCE LENS · RINGS FLAG CAVEATS · READ THE TASK, BASELINE AND SETUP',heading:'Audit before comparing',summary:'Treat the method as part of the result, not fine print.',items:[['01 / SOURCE','Trace the exact task','Confirm the original source, test version and date before citing a score.'],['02 / BASELINE','Know who was tested','An estimate, expert group or tiny sample is not “the average human.”'],['03 / COMPARABILITY','Match like with like','Different tests, tools and scoring rules weaken direct comparisons.']],watch:'Comparisons needing scrutiny',watchSub:'Evidence-risk ranking is a review aid, not a statistical confidence score.'},
      bn:{title:'এই তুলনায় প্রমাণ কতটা শক্ত?',subtitle:'প্রমাণের লেন্স · বলয় সতর্কতা দেখায় · পরীক্ষা, নমুনা ও সেটআপ পড়ুন',heading:'তুলনার আগে যাচাই করুন',summary:'পদ্ধতিও ফলের অংশ, ছোট অক্ষরের শর্ত নয়।',items:[['০১ / উৎস','মূল পরীক্ষাটি খুঁজুন','স্কোর উদ্ধৃতির আগে মূল উৎস, সংস্করণ ও তারিখ নিশ্চিত করুন।'],['০২ / মানব-তুলনা','কারা পরীক্ষায় ছিলেন?','অনুমান, বিশেষজ্ঞ বা ক্ষুদ্র নমুনা মানেই “গড় মানুষ” নয়।'],['০৩ / তুলনাযোগ্যতা','একই ধরনের ফল মিলান','ভিন্ন পরীক্ষা, টুল ও স্কোরিং সরাসরি তুলনাকে দুর্বল করে।']],watch:'যেসব তুলনা যাচাই করা দরকার',watchSub:'প্রমাণ-ঝুঁকি পর্যালোচনার সহায়ক, পরিসংখ্যানগত নিশ্চয়তা নয়।'}
    },
    impact:{
      en:{title:'What might this mean for real work?',subtitle:'WORK IMPACT · TASK RESULTS ARE NOT JOB PREDICTIONS · TEST IN CONTEXT',heading:'Translate scores into workflow questions',summary:'The useful unit is a task with clear outcomes, limits and review.',items:[['01 / ASSIST','Automate what can be checked','Trial repeatable drafting or classification against clear acceptance criteria.'],['02 / ACCOUNTABILITY','Keep judgement visible','A benchmark score cannot take responsibility or resolve every exception.'],['03 / VALIDATION','Measure the real workflow','Track errors, review time, edge cases and user outcomes before scaling.']],watch:'Largest AI-leading gaps',watchSub:'Investigation targets, not proof that a role can be automated.'},
      bn:{title:'বাস্তব কাজে এর অর্থ কী হতে পারে?',subtitle:'কাজের প্রভাব · পরীক্ষার ফল চাকরির পূর্বাভাস নয় · বাস্তবে যাচাই করুন',heading:'স্কোর থেকে কাজের প্রশ্নে যান',summary:'কার্যকর একক হলো স্পষ্ট ফল, সীমা ও পর্যালোচনাসহ একটি কাজ।',items:[['০১ / সহায়তা','যা যাচাই করা যায় তা পরীক্ষা করুন','স্পষ্ট মানদণ্ডে খসড়া বা শ্রেণিবিন্যাসের কাজ পরীক্ষা করুন।'],['০২ / দায়বদ্ধতা','মানবিক বিচার দৃশ্যমান রাখুন','বেঞ্চমার্কের স্কোর দায় নেয় না বা সব ব্যতিক্রম সমাধান করে না।'],['০৩ / যাচাই','বাস্তব কাজের ফল মাপুন','বড় পরিসরে ব্যবহারের আগে ভুল, পর্যালোচনার সময় ও ব্যবহারকারীর ফল মাপুন।']],watch:'এআই এগিয়ে থাকা বড় ব্যবধান',watchSub:'আরও পরীক্ষা করার ক্ষেত্র, কোনো কাজ স্বয়ংক্রিয় হওয়ার প্রমাণ নয়।'}
    }
  };
  function applyModeCopy() {
    const mode=wrap.dataset.view||'cosmos';
    if(isAnimalComparator()) {
      const animalCopy={
        cosmos:{en:{title:'Human and animal cognition, faculty by faculty',subtitle:'TEN FACULTIES · 0–100 ESTIMATES · SELECT A MARKER',heading:'Read the capability map',summary:'Each faculty shows a structured estimate and the basis behind it.',items:[['01 / SCORE','A bounded estimate','The selected panel gives a faculty value and explains how it was assigned.'],['02 / BASIS','Evidence or reasoning','Evidence Based marks a faculty directly addressed by the selected primary study; Reasoning Based marks an indirect or inferred estimate.'],['03 / SCALE','Compare with care','Animal values are a transparent synthesis, not raw scores reported by the study.']],watch:'Highest faculty estimates',watchSub:'Select an entry to inspect its estimate, explanation and primary research source.'},bn:{title:'সক্ষমতাভিত্তিক মানুষ ও প্রাণীর তুলনা',subtitle:'দশটি সক্ষমতা · ০–১০০ অনুমান · একটি চিহ্ন বেছে নিন',heading:'সক্ষমতার মানচিত্র পড়ুন',summary:'প্রতিটি সক্ষমতায় একটি কাঠামোবদ্ধ অনুমান ও তার ভিত্তি দেখানো হয়।',items:[['০১ / স্কোর','সীমিত অনুমান','নির্বাচিত প্যানেলে সক্ষমতার মান ও সেটি কীভাবে নির্ধারিত হয়েছে দেখুন।'],['০২ / ভিত্তি','প্রমাণ বা যুক্তি','প্রত্যক্ষ প্রমাণভিত্তিক মানে নির্বাচিত মূল গবেষণায় সক্ষমতাটি সরাসরি আলোচিত; যুক্তিনির্ভর অনুমান মানে পরোক্ষ তথ্য বা অনুমাননির্ভর মান।'],['০৩ / স্কেল','সতর্কভাবে তুলনা করুন','প্রাণীর মানগুলো স্বচ্ছ সংশ্লেষ, গবেষণাপত্রে প্রকাশিত কাঁচা স্কোর নয়।']],watch:'উচ্চ সক্ষমতা-অনুমান',watchSub:'স্কোর, ব্যাখ্যা ও মূল গবেষণার উৎস দেখতে একটি সক্ষমতা নির্বাচন করুন।'}},
        frontier:{en:{title:'Explore the ten faculty estimates',subtitle:'SCORE RINGS · BASIS LABELS · SELECT A FACULTY',heading:'What the estimates capture',summary:'Scores summarize task-relevant capability; the written basis tells you how direct the support is.',items:[['01 / RANGE','0 to 100','Higher scores are shown with larger faculty rings.'],['02 / SOLID RING','Evidence Based','The linked primary study directly addresses the faculty or closely related task.'],['03 / DASHED RING','Reasoning Based','The value uses indirect cognitive research or a cautious explicit inference.']],watch:'Faculty estimate leaders',watchSub:'The list is ordered by the estimate within the selected species.'},bn:{title:'দশটি সক্ষমতা-অনুমান দেখুন',subtitle:'স্কোরের বলয় · ভিত্তির লেবেল · সক্ষমতা নির্বাচন করুন',heading:'অনুমানগুলো কী বোঝায়',summary:'স্কোর কাজ-সম্পর্কিত সক্ষমতা সংক্ষেপে দেখায়; লিখিত ভিত্তি তথ্য কতটা সরাসরি তা জানায়।',items:[['০১ / পরিসর','০ থেকে ১০০','উচ্চ স্কোর বড় সক্ষমতা-বলয়ে দেখানো হয়।'],['০২ / পূর্ণ বলয়','প্রত্যক্ষ প্রমাণভিত্তিক','লিংক করা মূল গবেষণায় সক্ষমতা বা খুব কাছের কাজ সরাসরি আলোচিত।'],['০৩ / ড্যাশ বলয়','যুক্তিনির্ভর অনুমান','মানটি পরোক্ষ জ্ঞানীয় গবেষণা বা সতর্ক স্পষ্ট অনুমান ব্যবহার করে।']],watch:'উচ্চ সক্ষমতা-অনুমান',watchSub:'নির্বাচিত প্রাণীর মধ্যে অনুমানের উচ্চতা অনুযায়ী তালিকা সাজানো।'}},
        trajectory:{en:{title:'Inspect the rating basis',subtitle:'CURRENT FACULTY ESTIMATES · SOURCE-LINKED EXPLANATIONS',heading:'Separate the finding from the estimate',summary:'The source describes a tested behaviour; the atlas score is a synthesis used to make faculties inspectable.',items:[['01 / FINDING','What the study reports','Read the primary-study summary for the behaviour or task that was examined.'],['02 / SCORE','How the map encodes it','The 0–100 value is a faculty estimate rather than a percentage published by the study.'],['03 / CONTEXT','Keep the conditions in view','Sample, task design and species context matter when interpreting a finding.']],watch:'Inspect faculty estimates',watchSub:'Future-score controls are paused while an animal is selected.'},bn:{title:'স্কোরের ভিত্তি পরীক্ষা করুন',subtitle:'বর্তমান সক্ষমতা-অনুমান · উৎস-সংযুক্ত ব্যাখ্যা',heading:'গবেষণার ফল ও অনুমান আলাদা রাখুন',summary:'উৎসে পরীক্ষিত আচরণ বর্ণিত; অ্যাটলাসের স্কোরটি সক্ষমতাগুলো পরিদর্শনযোগ্য করার জন্য সংশ্লেষ করা।',items:[['০১ / ফল','গবেষণাপত্রে যা আছে','পরীক্ষিত আচরণ বা কাজের সারাংশ পড়ুন।'],['০২ / স্কোর','মানচিত্রে কীভাবে দেখানো','০–১০০ মানটি সক্ষমতা-অনুমান, গবেষণায় প্রকাশিত শতাংশ নয়।'],['০৩ / প্রেক্ষিত','শর্ত মনে রাখুন','ফল ব্যাখ্যায় নমুনা, পরীক্ষার নকশা ও প্রজাতির প্রেক্ষিত গুরুত্বপূর্ণ।']],watch:'সক্ষমতা-অনুমান পরীক্ষা করুন',watchSub:'প্রাণী নির্বাচন করলে ভবিষ্যৎ-স্কোরের নিয়ন্ত্রণ স্থগিত থাকে।'}},
        evidence:{en:{title:'Inspect the support behind a score',subtitle:'PRIMARY PAPER · FACULTY ESTIMATE · BASIS LABEL',heading:'What each label means',summary:'The basis label distinguishes direct task evidence from a cautious inference.',items:[['01 / SOURCE','Primary research','Open the animal cognition research link in the selected faculty panel.'],['02 / EVIDENCE BASED','Directly addressed','The linked primary research measures or directly discusses the faculty or a closely related task.'],['03 / REASONING BASED','Inference made explicit','Indirect findings or a cautious inference support the estimate where the primary paper does not directly measure that faculty.']],watch:'Faculty estimates',watchSub:'Choose a faculty to read the score rationale and open the selected species source.'},bn:{title:'স্কোরের ভিত্তি যাচাই করুন',subtitle:'মূল গবেষণা · সক্ষমতা-অনুমান · ভিত্তির লেবেল',heading:'প্রতিটি লেবেলের অর্থ',summary:'ভিত্তির লেবেল সরাসরি কাজের ফল ও সতর্ক অনুমান আলাদা করে।',items:[['০১ / উৎস','মূল গবেষণা','নির্বাচিত সক্ষমতার প্যানেলে প্রাণী-জ্ঞান গবেষণার লিংক খুলুন।'],['০২ / প্রত্যক্ষ প্রমাণ','সরাসরি আলোচিত','লিংক করা মূল গবেষণায় সক্ষমতা বা খুব কাছের কাজ মাপা বা সরাসরি আলোচনা করা হয়েছে।'],['০৩ / যুক্তিনির্ভর অনুমান','স্পষ্ট অনুমান','মূল গবেষণা সরাসরি সক্ষমতাটি না মাপলে পরোক্ষ ফল বা সতর্ক অনুমান স্কোরকে সমর্থন করে।']],watch:'সক্ষমতা-অনুমান',watchSub:'স্কোরের যুক্তি পড়তে ও নির্বাচিত প্রাণীর উৎস খুলতে একটি সক্ষমতা বাছুন।'}},
        impact:{en:{title:'What the selected species is suited to',subtitle:'FACULTY ESTIMATES · DOMAIN AND TASK MATTER',heading:'Interpret capability in context',summary:'A faculty score points to task-relevant strengths, not a single ladder of intelligence.',items:[['01 / CHIMPANZEE','Physical and spatial cognition','The linked battery found a shared spatial-cognition factor and different physical/social patterns across species.'],['02 / DOG','Human-directed social cues','Dogs used several pointing gestures, with success varying by gesture type.'],['03 / HONEYBEE','Visual statistical learning','Honeybees extracted co-occurrence patterns but did not automatically encode conditional predictions in the selected paradigm.']],watch:'Faculty estimates',watchSub:'Select an animal and faculty to inspect the source-linked explanation.'},bn:{title:'নির্বাচিত প্রজাতির সক্ষমতার ক্ষেত্র',subtitle:'সক্ষমতা-অনুমান · ক্ষেত্র ও কাজ গুরুত্বপূর্ণ',heading:'প্রেক্ষাপটে সক্ষমতা বুঝুন',summary:'একটি সক্ষমতার স্কোর নির্দিষ্ট কাজের শক্তি বোঝায়, বুদ্ধিমত্তার একক সিঁড়ি নয়।',items:[['০১ / শিম্পাঞ্জি','দৈহিক ও স্থানিক বোধ','লিংক করা পরীক্ষামালায় মিলযুক্ত স্থানিক বোধের ফ্যাক্টর এবং দৈহিক/সামাজিক সক্ষমতায় ভিন্ন ধরন পাওয়া যায়।'],['০২ / কুকুর','মানুষ-নির্দেশিত সামাজিক সংকেত','কুকুর মানুষের কয়েক ধরনের নির্দেশক অঙ্গভঙ্গি বুঝেছে; সাফল্য অঙ্গভঙ্গির ধরনভেদে বদলেছে।'],['০৩ / মৌমাছি','দৃশ্য-পরিসংখ্যানগত শেখা','মৌমাছি সহ-উপস্থিতির প্যাটার্ন শিখেছে, কিন্তু নির্বাচিত পরীক্ষায় শর্তাধীন পূর্বাভাস স্বয়ংক্রিয়ভাবে ধরেনি।']],watch:'সক্ষমতা-অনুমান',watchSub:'উৎস-সংযুক্ত ব্যাখ্যা দেখতে প্রাণী ও সক্ষমতা নির্বাচন করুন.'}}
      };
      const c=animalCopy[mode][lang==='bn'?'bn':'en'];
      setText('galaxyTitle',c.title);setText('galaxySubtitle',c.subtitle);
      setText('impactTitle',c.heading);setText('impactSub',c.summary);
      c.items.forEach((item,i)=>{setText('impactKicker'+(i+1),item[0]);setText('impactHead'+(i+1),item[1]);setText('impactText'+(i+1),item[2]);});
      setText('watchTitle',c.watch);setText('watchSub',c.watchSub);
      updateWatchlist();return;
    }
    const c=modeCopy[mode][lang==='bn'?'bn':'en'];
    setText('galaxyTitle',c.title);setText('galaxySubtitle',c.subtitle);
    setText('impactTitle',c.heading);setText('impactSub',c.summary);
    c.items.forEach((item,i)=>{setText('impactKicker'+(i+1),item[0]);setText('impactHead'+(i+1),item[1]);setText('impactText'+(i+1),item[2]);});
    setText('watchTitle',c.watch);setText('watchSub',c.watchSub);
    updateWatchlist();
  }
  function applyDynamicLanguage() {
    const d=data[selected];
    if(isAnimalComparator()) {
      applyAnimalInspector();
      const sourceLink=$('#facultySourceLink');
      if(sourceLink){sourceLink.href=comparativeProfiles[comparator].sourceUrl;sourceLink.textContent=lang==='bn'?'প্রাণীর জ্ঞানীয় সক্ষমতা নিয়ে গবেষণা দেখুন':'Explore animal cognition research';}
      const currentView=wrap.dataset.view||'cosmos';
      const modeLabels=lang==='bn'?{cosmos:'প্রমাণ · মানচিত্র',frontier:'সক্ষমতা · অনুসন্ধান',trajectory:'গবেষণা · স্ন্যাপশট',evidence:'প্রমাণ · সীমা',impact:'কাজ · প্রয়োগ'}:{cosmos:'Evidence · map',frontier:'Faculty · explore',trajectory:'Research · snapshot',evidence:'Evidence · limits',impact:'Impact · context'};
      setText('projectionMode',modeLabels[currentView]||modeLabels.cosmos);
      setText('zoomLevel',Math.round(zoom*100)+'%');
      $('#facultySelect').value=String(selected);
      updateActivityLog();applyModeCopy();
      $('#cosmos').setAttribute('aria-label',lang==='bn'?'ইন্টার‌্যাকটিভ প্রমাণ-মানচিত্র। একটি সক্ষমতার চিহ্ন বেছে নিয়ে নির্দিষ্ট ফল দেখুন।':'Interactive evidence map. Select a faculty marker to inspect its task-specific finding.');
      updateStats();
      return;
    }
    const dScore = comparisonScore(d,selected,years>0); const state = classify(d.human,dScore); const g=d.human-dScore;
    setText('facultyName',displayName(d.name));
    setText('facultyDesc',lang==='bn'?descriptionsBn[d.name]:d.desc);
    setText('statusChip',state==='close'?(lang==='bn'?'প্রায় সমান':'Near parity'):state==='human'?(lang==='bn'?'মানব-রেফারেন্স এগিয়ে':'Human leads'):(lang==='bn'?'এআই এগিয়ে':'AI leads'));
    setText('gapLabel',g>0?(lang==='bn'?'মানব-রেফারেন্স '+toBanglaNumber(fmt(g))+' পয়েন্ট এগিয়ে':'Human reference ahead by '+fmt(g)+' points'):g<0?(lang==='bn'?'এআই '+toBanglaNumber(fmt(Math.abs(g)))+' পয়েন্ট এগিয়ে':comparatorName()+' ahead by '+fmt(Math.abs(g))+' points'):(lang==='bn'?'স্কোর সমান':'Scores are equal'));
    setText('aiCompareLabel',comparatorLabel());setText('legendAI',comparatorLabel());
    const liveGuide=$('#canvasGuide');if(liveGuide)liveGuide.innerHTML=lang==='bn'
      ? '<b>গ্যালাক্সি বুঝুন</b><br>বৃত্ত = মানব-রেফারেন্স ও নির্বাচিত এআই ফল · রম্বস = অন্য ফল<br>চিহ্নের দূরত্ব এই পরীক্ষার ব্যবধানের দৃশ্য-সংকেত; এটি অভিন্ন বুদ্ধিমত্তার স্কেল নয়।'
      : '<b>READ THE GALAXY</b><br>Circles = human reference and selected AI result · diamonds = other results<br>Separation cues this test’s gap; it is not a shared intelligence scale.';
    setText('topResultLabel',lang==='bn'?'সেরা এআই মডেল বা ফল':'WINNING AI MODEL OR RESULT');
    setText('modelName',lang==='bn' && d.name==='Metacognition' ? 'MetaBound · সর্বোচ্চ প্রকাশিত মডেল' : d.model);
    setText('modelSource',(years>0?(lang==='bn'?'আজকের প্রকাশিত এআই ফল: '+fmt(d.ai):'Published AI score today: '+fmt(d.ai)):'')+(years>0?' · ':'')+(lang==='bn'?(aiRefBn[d.name]||d.aiRef):d.aiRef)+' · '+(lang==='bn'?(confidenceBn[d.confidence]||d.confidence):d.confidence));
    setText('referenceCaveat',referenceCaveats[d.name][lang==='bn'?'bn':'en']);
    setText('calibrationText',lang==='bn'?'প্রতিটি সক্ষমতায় আলাদা পরীক্ষা ব্যবহৃত হয়, তাই স্কোরগুলো অভিন্ন বুদ্ধিমত্তার স্কেল নয়। মানব-তুলনা অনুমান, ছোট নমুনা বা বিশেষজ্ঞ-দলের ফল হতে পারে।':'Each faculty uses a different test, so scores are not on one shared intelligence scale. Human results may come from estimates, small samples or expert groups.');
    setText('everydayText',(wrap.dataset.view||'cosmos')==='impact'?(lang==='bn'?workImplicationsBn[d.name]:workImplications[d.name]):(lang==='bn'?everydayMeaningBn[d.name]:everydayMeaning[d.name]));
    const sourceLink=$('#facultySourceLink');if(sourceLink){const evidence=evidenceLedger[d.name]||{sourceUrl:'https://epoch.ai/benchmarks',sourceLabel:'Open benchmark source ↗'};sourceLink.href=evidence.sourceUrl;sourceLink.textContent=lang==='bn'?'এই সক্ষমতার উৎস দেখুন ↗':evidence.sourceLabel;sourceLink.setAttribute('aria-label',lang==='bn'?'নির্বাচিত সক্ষমতার উৎস খুলুন':evidence.sourceLabel);}
    const currentView=wrap.dataset.view||'cosmos';
    const modeLabels=lang==='bn'?{cosmos:'ক্ষেত্র · মানচিত্র',frontier:'ব্যবধান · তুলনা',trajectory:'পথ · +'+years+' বছর',evidence:'প্রমাণ · সীমাবদ্ধতা',impact:'কাজ · প্রয়োগ'}:{cosmos:'Field · atlas',frontier:'Gaps · comparison',trajectory:'Path · +'+years+' years',evidence:'Evidence · method',impact:'Impact · workflow'};
    setText('projectionMode',currentView==='trajectory'&&years>0?(lang==='bn'?'দৃশ্যপট · +'+rate+' পয়েন্ট/বছর':'Scenario · +'+rate+' pts/year'):modeLabels[currentView]);
    setText('galaxySubtitle',lang==='bn'?'১০টি সক্ষমতা · ০–১০০ অনুমান · প্রতিটি বলয়ের ভিত্তি দেখুন':'TEN FACULTIES · 0–100 ESTIMATES · INSPECT EACH RATING BASIS');
    setText('zoomLevel',Math.round(zoom*100)+'%');$('#facultySelect').value=String(selected);
    updateActivityLog();applyModeCopy();$('#cosmos').setAttribute('aria-label',lang==='bn'?'ইন্টার‌্যাকটিভ গ্যালাক্সি। তীর চিহ্ন দিয়ে বিভাগ বদলান, প্লাস ও মাইনাস দিয়ে জুম করুন। বিস্তারিত দেখতে একটি চিহ্ন নির্বাচন করুন।':'Interactive galaxy. Use arrow keys to change faculty, plus and minus to zoom. Select a marker for details.');
  }
  function applyScenarioLanguage() {
    const animal=isAnimalComparator();
    $('#horizon').disabled=animal;
    document.querySelectorAll('.scenario').forEach(button=>{button.disabled=animal;});
    const scenarioLabels=lang==='bn'?['ধীর +১','স্থির +৩','দ্রুত +৬']:['Slower +1','Steady +3','Faster +6'];
    document.querySelectorAll('.scenario').forEach((button,i)=>{button.textContent=scenarioLabels[i];button.setAttribute('aria-pressed',String(Number(button.dataset.rate)===rate));});
    const modeNames=lang==='bn'?['ক্ষেত্র','ব্যবধান','পথ','প্রমাণ','প্রভাব']:['Field','Gaps','Path','Evidence','Impact'];
    document.querySelectorAll('.mode-switch button').forEach((button,i)=>{button.textContent=modeNames[i];});
    setText('spinToggle',lang==='bn'?'ড্র্যাগ ছাড়া অবিরাম ঘূর্ণন':'Continuous rotation · pauses during drag');
    if(animal){
      const ratings=data.map((d,i)=>animalFinding(comparator,i));
      const avg=Math.round(ratings.reduce((sum,r)=>sum+r.score,0)/ratings.length);
      setText('horizonValue',lang==='bn'?'গবেষণার স্ন্যাপশট':'Research snapshot');
      setText('scenarioMain',lang==='bn'?'গড় সক্ষমতা-অনুমান · '+toBanglaNumber(avg)+' / ১০০':'Mean faculty estimate · '+avg+' / 100');
      setText('scenarioSub',lang==='bn'?'পূর্ণ বলয় = প্রত্যক্ষ প্রমাণভিত্তিক · ড্যাশযুক্ত বলয় = যুক্তিনির্ভর অনুমান · বড় বলয় = বেশি অনুমান।':'Solid ring = evidence-based · dashed ring = reasoning-based estimate · larger ring = higher estimate.');
      return;
    }
    const c=counts(years>0);
    setText('horizonValue',years===0?(lang==='bn'?'আজ':'Today'):(lang==='bn'?'+'+toBanglaNumber(years)+' বছর':'+'+years+' year'+(years===1?'':'s')));
    setText('scenarioMain',years===0?(lang==='bn'?'আজকের তুলনা · প্রকাশিত তথ্য':'Today’s comparison · source snapshot'):(lang==='bn'?'১০টির মধ্যে '+toBanglaNumber(c.a)+'টি সক্ষমতায় এআই এগিয়ে':c.a+' of 10 faculties AI-led'));
    setText('scenarioSub',years===0?(lang==='bn'?'এখানে কোনো ভবিষ্যৎ অনুমান যোগ করা হয়নি।':'Observed source scores; current snapshot.'):(lang==='bn'?'উদাহরণ: বছরে '+toBanglaNumber(rate)+' স্কোর-পয়েন্ট বৃদ্ধি, সর্বোচ্চ ১০০। এটি পূর্বাভাস নয়।':'Scenario: +'+rate+' score points/year, capped at 100. This is a what-if, not a forecast.'));
  }
  function applyStaticLanguage() {
    const bn = lang === 'bn';
    document.documentElement.lang = bn ? 'bn' : 'en';
    const retainedStatus = $('#atlasActionStatus');
    if (retainedStatus) {
      const saved = ['তুলনার পিডিএফ কপি তৈরি হয়েছে।','Your comparison snapshot PDF is ready.'];
      const unavailable = ['এই ব্রাউজারে পিডিএফ তৈরি করা যায়নি।','This browser could not create the PDF.'];
      const legacySaved = ['প্রসঙ্গ ও সতর্কতাসহ কপি সংরক্ষিত হয়েছে।','A copy was saved with its caveat and source context.'];
      const legacyUnavailable = ['এই ব্রাউজারে কার্ড তৈরি করা যায়নি।','This browser could not create the result card.'];
      const pngFailure = ['PNG তৈরি করা যায়নি।','Could not generate the PNG.'];
      const current = retainedStatus.textContent.trim();
      if (saved.includes(current) || legacySaved.includes(current)) retainedStatus.textContent = saved[bn ? 0 : 1];
      else if (unavailable.includes(current) || legacyUnavailable.includes(current)) retainedStatus.textContent = unavailable[bn ? 0 : 1];
      else if (pngFailure.includes(current)) retainedStatus.textContent = unavailable[bn ? 0 : 1];
    }
    $('#languageToggle').textContent = bn ? 'English' : 'বাংলা';
    $('#languageToggle').setAttribute('aria-label', bn ? 'ভাষা ইংরেজিতে বদলান' : 'Switch language to Bangla');
    $('#languageToggle').title = bn ? 'ভাষা ইংরেজিতে বদলান' : 'Switch language to Bangla';
    $('#languageToggle').setAttribute('aria-pressed', String(bn));
    const labels = bn ? {
      brandSub:'মানুষ ও যন্ত্রের সক্ষমতার মানচিত্র', snapshotTag:'বেঞ্চমার্ক স্ন্যাপশট · লাইভ নয়',
      galaxyTitle:'মানুষ ও অন্যান্য বুদ্ধিমত্তার সক্ষমতার তুলনামূলক মানচিত্র', galaxySubtitle:'দশটি সক্ষমতা · প্রকাশিত ফল · তুলনার একটি ক্ষেত্র',
      canvasGuide:'<b>গ্যালাক্সি পড়ুন</b><br>বৃত্ত = মানব-রেফারেন্স ও নির্বাচিত তুলনা · রম্বস = অন্য তুলনা-বিন্দু<br>এআই কক্ষপথের বাইরে = এআই স্কোর বেশি<br>ভেতরে = মানব-রেফারেন্স বেশি<br>চিহ্নের দূরত্ব এই পরীক্ষার ব্যবধানের দৃশ্য-সংকেত; এটি অভিন্ন বুদ্ধিমত্তার স্কেল নয়।',
      legendHuman:'মানব-রেফারেন্স', legendAI:'এআই ফল', legendGap:'দুই স্কোরের ব্যবধান', legendSelected:'নির্বাচিত সক্ষমতা', legendOrbit:'গোলকের জালিকা',
      facultyInspectorLabel:'আরও কাছ থেকে দেখুন', chooseFacultyLabel:'সক্ষমতা বাছুন', humanCompareLabel:'মানব-রেফারেন্স', aiCompareLabel:'প্রকাশিত এআই ফল', topResultLabel:'সেরা এআই মডেল বা ফল', everydayLabel:'কেন এটি গুরুত্বপূর্ণ',
      projectionTitle:'সম্ভাব্য ভবিষ্যৎ দেখুন', projectionExplain:'এআই ধীরে, স্থির গতিতে বা দ্রুত এগোলে কী হতে পারে, তা কল্পনা করুন। মানব-রেফারেন্স অপরিবর্তিত থাকে। এটি একটি দৃশ্যপট, পূর্বাভাস নয়।',
      horizonLabel:'কত বছর সামনে', todayLabel:'আজ', maxHorizonLabel:'+৫ বছর',
      impactTitle:'বেঞ্চমার্কের ব্যবধান কী বলে, কী বলে না', impactSub:'বাস্তব কাজে কোন সক্ষমতা কেন গুরুত্বপূর্ণ, তা বুঝতে পরীক্ষার ফল ব্যবহার করুন।',
      impactKicker1:'০১ / যাচাইযোগ্য আউটপুট', impactHead1:'কাজ তৈরির গতি বদলাতে পারে', impactText1:'ফল বারবার তৈরি করা যায় এবং সহজে যাচাই করা যায়, সেখানে এআই খসড়া, সংশ্লেষণ ও নিয়মিত বিশ্লেষণ দ্রুত করতে পারে। মান ও দায়বদ্ধতার জন্য মানুষের পর্যালোচনা জরুরি।',
      impactKicker2:'০২ / মানবিক বিচার', impactHead2:'প্রেক্ষাপট স্কোরের বাইরে', impactText2:'প্রেক্ষাপট, বাস্তব জগৎ, দায়বদ্ধতা ও অস্পষ্ট লক্ষ্য প্রায়ই পরীক্ষার বাইরে থাকে। উচ্চ স্কোর নির্ভরযোগ্য এন্ড-টু-এন্ড কাজ প্রমাণ করে না।',
      impactKicker3:'০৩ / প্রমাণের সীমা', impactHead3:'পদ্ধতি না মিললে তুলনা ভঙ্গুর', impactText3:'ভিন্ন পরীক্ষা, কাস্টম টুল, ছোট নমুনা ও অনুমানভিত্তিক মানব-স্কোর সংখ্যার ব্যবধানকে প্রভাবিত করতে পারে। আগে পদ্ধতি যাচাই করুন।',
      watchKicker:'প্রমাণের সীমারেখা', watchTitle:'প্রকাশিত স্কোরে সবচেয়ে কম ব্যবধান', watchSub:'স্কোর কাছাকাছি হলেই ফলগুলো সরাসরি তুলনাযোগ্য হয় না। পরীক্ষার পদ্ধতি ও সীমাবদ্ধতা দেখতে একটি সক্ষমতা বেছে নিন।',
      dataNoteText:'প্রমাণের অখণ্ডতা: স্কোরগুলো নির্দিষ্ট পরীক্ষার স্ন্যাপশট, অভিন্ন বুদ্ধিমত্তার স্কেল বা লাইভ র‍্যাঙ্কিং নয়। পার্থক্য বুঝতে পরীক্ষার ধরন, নমুনা, সেটআপ ও তারিখ মিলিয়ে দেখুন।',
      calibrationText:'প্রতিটি সক্ষমতায় আলাদা পরীক্ষা ব্যবহৃত হয়, তাই স্কোরগুলো অভিন্ন বুদ্ধিমত্তার স্কেল নয়। মানব-তুলনা অনুমান, ছোট নমুনা বা বিশেষজ্ঞ-দলের ফল হতে পারে।',
      calibrationLink:'তুলনা কীভাবে কাজ করে', takeTestLink:'স্কোরের উৎস ও সীমাবদ্ধতা ↗', modelRecommendLink:'নিজের জন্য উপযুক্ত এআই মডেল খুঁজুন ↗',
      sourceLink:'মূল উৎস খুলুন ↗', methodLink:'পরিমাপের পদ্ধতি ↗', footerSub:'মানুষ ও যন্ত্রের সক্ষমতার একটি নির্দেশিকা।', footerStatus:'প্রোটোটাইপ · নির্দিষ্ট ডেটা-স্ন্যাপশট · লাইভ ফিড নয়',
      metricLabels:['মানব-রেফারেন্স এগিয়ে','এআই এগিয়ে','প্রায় সমান','সবচেয়ে বড় ব্যবধান'], metricFoots:['১০টির মধ্যে সক্ষমতা','প্রকাশিত ফলের ভিত্তিতে','৫ পয়েন্টের মধ্যে','ভিন্ন পরীক্ষার সংখ্যাগত ব্যবধান']
    } : {
      brandSub:'A field guide to human + machine ability', snapshotTag:'Benchmark snapshot · not live',
      galaxyTitle:'A comparative map of human and other intelligence', galaxySubtitle:'Ten faculties · reported results · one field of comparison',
      canvasGuide:'<b>READ THE GALAXY</b><br>Circle = human reference + selected comparison · diamonds = other comparison points<br>AI outside orbit = higher score<br>AI inside = human reference scores higher<br>Separation cues this test’s gap; it is not a shared intelligence scale.',
      legendHuman:'Human reference', legendAI:'AI result', legendGap:'Pair gap', legendSelected:'Selected capability', legendOrbit:'Geodesic mesh',
      facultyInspectorLabel:'Look closer', chooseFacultyLabel:'CHOOSE A FACULTY', humanCompareLabel:'Human reference', aiCompareLabel:'Reported AI result', topResultLabel:'WINNING AI MODEL OR RESULT', everydayLabel:'WHY THIS MATTERS',
      projectionTitle:'TRY A POSSIBLE FUTURE', projectionExplain:'Imagine slower, steady, or faster AI progress. The human reference stays fixed. This is a what-if, not a forecast.',
      horizonLabel:'Look ahead', todayLabel:'Today', maxHorizonLabel:'+5 years',
      impactTitle:'What benchmark gaps can and cannot tell us', impactSub:'Use task-level evidence to explore where capabilities may matter in real work.',
      impactKicker1:'01 / Verifiable outputs', impactHead1:'Where work may change first', impactText1:'When outputs are repeatable and easy to check, AI can accelerate drafting, synthesis and routine analysis. Human review still anchors quality and accountability.',
      impactKicker2:'02 / Human judgement', impactHead2:'Context sits beyond a score', impactText2:'Context, physical reality, responsibility and ambiguous goals often sit outside a benchmark. A high score does not establish reliable end-to-end work.',
      impactKicker3:'03 / Evidence boundary', impactHead3:'Method before leaderboard', impactText3:'Unequal tests, custom tools, small samples and estimated human baselines can dominate a score gap. Check the method before comparing the numbers.',
      watchKicker:'EVIDENCE WATCHLIST', watchTitle:'Smallest reported gaps', watchSub:'Close scores do not automatically make results comparable. Select a faculty to inspect the test method and its limits.',
      dataNoteText:'Evidence integrity: These are task-specific benchmark snapshots, not a shared intelligence scale or live ranking. Check the test, sample, setup and date to interpret differences fairly.',
      calibrationText:'Each faculty uses a different test, so scores are not on one shared intelligence scale. Human results may come from estimates, small samples or expert groups.',
      calibrationLink:'How comparisons work', takeTestLink:'Score trail & caveats ↗', modelRecommendLink:'Find your match AI Model ↗',
      sourceLink:'Open source ↗', methodLink:'How it is measured ↗', footerSub:'A field guide to human and machine capability.', footerStatus:'Prototype · Snapshot data · Not a live feed',
      metricLabels:['Human leads','AI leads','Near parity','Largest reported gap'], metricFoots:['faculties out of 10','best published result per faculty','within five score points','numeric gap across unlike tests']
    };
    Object.keys(labels).forEach(key => {
      if (key === 'canvasGuide') $('#canvasGuide').innerHTML = labels[key];
      else if (key === 'metricLabels' || key === 'metricFoots') { const selector = key === 'metricLabels' ? '.metric-label' : '.metric-foot'; document.querySelectorAll(selector).forEach((el, i) => { el.textContent = labels[key][i]; }); }
      else setText(key, labels[key]);
    });
    // Hero copy, brand, feedback and all control labels are switched as one locale unit.
    const hero = bn ? {
      eyebrow:'মানুষ ও যন্ত্রের বুদ্ধিমত্তা', title:'মানুষের মহাবিশ্বে এআই কোথায়?', accent:'মানবজগতের মধ্যে?',
      copy:'দশটি জ্ঞানীয় সক্ষমতা জুড়ে তুলনা ঘুরে দেখুন। প্রতিটি মডেল-চিহ্ন মানব-তুলনার পাশে দেখানো হয়েছে, যাতে বোঝা যায় কোন কাজে এআই এগিয়ে, কোথায় মানুষ এগিয়ে এবং কোথায় ব্যবধান কম।',
      noteTitle:'একটি মানচিত্র। বুদ্ধিমত্তার দুই রূপ।', noteText:'গ্যালাক্সি ঘোরান, একটি বিন্দু বেছে নিন, তারপর ভবিষ্যৎ-দৃশ্য বদলে দেখুন আজকের ব্যবধান কীভাবে বদলাতে পারে। বর্তমানের পরের অংশটি কেবল একটি সম্ভাব্য দৃশ্য, পূর্বাভাস নয়.'
    } : {
      eyebrow:'Human × machine intelligence', title:'Where does AI sit', accent:'human universe?',
      copy:'Explore the frontier across ten cognitive faculties. Each model marker is positioned against a human reference, so you can see where AI leads, where people lead, and where the gap is still small.',
      noteTitle:'One map. Two kinds of intelligence.', noteText:'Drag the cosmos, select a star, then change the future scenario to see how today’s gaps could move. Past the present, the display is a transparent what-if, not a prediction.'
    };
    setText('heroEyebrow', hero.eyebrow);
    const heroTitle = $('#heroTitle');
    if (heroTitle) heroTitle.innerHTML = bn ? 'মানুষের মহাবিশ্বে <span class="gradient" id="heroTitleAccent">এআই কোথায়?</span>' : 'Where does AI sit<br>in the <span class="gradient" id="heroTitleAccent">human universe?</span>';
    setText('heroCopy', hero.copy); setText('heroNoteTitle', hero.noteTitle); setText('heroNoteText', hero.noteText);
    setText('feedbackIdea', bn ? 'মতামত · ধারণা' : 'Feedback · Idea');
    document.title = bn ? 'কগনিটিভ তুলনা অ্যাটলাস | মানুষকেন্দ্রিক সক্ষমতার মানচিত্র' : 'Cognitive Comparison Atlas | Human-centred capability map';
    setText('projectionMode', bn ? 'CC ATLAS · মানুষকেন্দ্রিক' : 'CC ATLAS · Human-centered');
    const prevC = $('#prevComparator'), nextC = $('#nextComparator');
    if (prevC) { prevC.setAttribute('aria-label', bn ? 'আগের তুলনা' : 'Previous comparison'); prevC.title = bn ? 'আগের তুলনা' : 'Previous comparison'; }
    if (nextC) { nextC.setAttribute('aria-label', bn ? 'পরের তুলনা' : 'Next comparison'); nextC.title = bn ? 'পরের তুলনা' : 'Next comparison'; }
    const prevF = $('#prevFaculty'), nextF = $('#nextFaculty');
    if (prevF) { prevF.setAttribute('aria-label', bn ? 'আগের সক্ষমতা' : 'Previous faculty'); prevF.title = bn ? 'আগের সক্ষমতা' : 'Previous faculty'; }
    if (nextF) { nextF.setAttribute('aria-label', bn ? 'পরের সক্ষমতা' : 'Next faculty'); nextF.title = bn ? 'পরের সক্ষমতা' : 'Next faculty'; }
    const credit = $('#siteCredit');
    if (credit) { credit.textContent = bn ? 'নির্মাণ: Wasi Uz Zaman · সংস্করণ ১.০' : 'Built by Wasi Uz Zaman · V1.0'; credit.setAttribute('aria-label', bn ? 'নির্মাণ করেছেন Wasi Uz Zaman, সংস্করণ ১.০' : 'Built by Wasi Uz Zaman, version 1.0'); }

    setText('galaxySubtitle', bn ? '১০টি সক্ষমতা · নির্দিষ্ট পরীক্ষার স্কোর · অভিন্ন বুদ্ধিমত্তার স্কেল নয়' : 'TEN FACULTIES · TASK-SPECIFIC SCORES · NOT A SHARED INTELLIGENCE SCALE');
    $('#zoomIn').setAttribute('aria-label', bn ? 'জুম বাড়ান' : 'Zoom in');
    $('#zoomIn').removeAttribute('title');
    $('#zoomOut').setAttribute('aria-label', bn ? 'জুম কমান' : 'Zoom out');
    $('#zoomOut').removeAttribute('title');
    setText('resetView', bn ? 'দৃশ্য রিসেট' : 'Reset view');
    $('#resetView').setAttribute('aria-label', bn ? 'গ্যালাক্সির দৃশ্য আগের অবস্থায় ফেরান' : 'Reset galaxy view');
    $('#howToUse').setAttribute('aria-label', bn ? 'ব্যবহারবিধি দেখুন' : 'Open the guide');
    $('#howToUse').title = bn ? 'ব্যবহারবিধি দেখুন' : 'Open the guide';
    setText('comparatorLabel', bn ? 'তুলনার ধরন বেছে নিন' : 'COMPARE WITH');
    $('#comparatorSelect').setAttribute('aria-label', bn ? 'তুলনার জন্য এআই বা প্রাণী বেছে নিন' : 'Choose a comparator');
    const comparatorOptions = bn
      ? ['কৃত্রিম বুদ্ধিমত্তা (এআই)','শিম্পাঞ্জি','কুকুর','মৌমাছি']
      : ['Artificial Intelligence (AI)','Chimpanzee','Dog','Honeybee'];
    Array.from($('#comparatorSelect').options).forEach((option, i) => { option.textContent = comparatorOptions[i]; });
    $('.mode-switch').setAttribute('aria-label', bn ? 'গ্যালাক্সি দেখার ধরন বাছুন' : 'Choose a galaxy view');
    const layoutHint = $('.rail-layout-hint');
    if (layoutHint) layoutHint.textContent = bn ? 'লাল হ্যান্ডেল টেনে আকার বদলান' : 'Drag red grips to resize';
    const layoutReset = $('.rail-layout-reset');
    if (layoutReset) layoutReset.textContent = bn ? 'মাপ আগের অবস্থায় ফেরান' : 'Reset sizes';
    const layoutToggle = $('.rail-layout-toggle');
    if (layoutToggle) layoutToggle.textContent = bn ? (layoutToggle.getAttribute('aria-pressed') === 'true' ? 'বিন্যাস সম্পন্ন' : 'বিন্যাস বদলান') : (layoutToggle.getAttribute('aria-pressed') === 'true' ? 'Finish layout' : 'Adjust layout');
    $('#cosmos').setAttribute('aria-label', bn ? 'ইন্টার‌্যাকটিভ গ্যালাক্সি। সক্ষমতা বদলাতে তীরচিহ্ন, জুম করতে প্লাস বা মাইনাস চাপুন। বিস্তারিত দেখতে একটি চিহ্ন বেছে নিন।' : 'Interactive galaxy. Use arrow keys to change faculty, plus and minus to zoom. Select a marker for details.');
    $('#facultySelect').setAttribute('aria-label', bn ? 'সক্ষমতা বাছুন' : 'Choose a cognitive faculty');
    $('#prevFaculty').setAttribute('aria-label', bn ? 'আগের সক্ষমতা' : 'Previous faculty');
    $('#nextFaculty').setAttribute('aria-label', bn ? 'পরের সক্ষমতা' : 'Next faculty');
    $('#journeyTrigger').setAttribute('aria-label', bn ? 'পরের সক্ষমতা দেখুন' : 'Explore next capability');
    $('#journeyTrigger').title = bn ? 'পরের সক্ষমতা দেখুন' : 'Explore next capability';
    $('.activity-log').setAttribute('aria-label', bn ? 'সক্ষমতা তুলনার লগ' : 'Capability observation log');
    $('.stage-column').setAttribute('aria-label', bn ? 'ইন্টার‌্যাকটিভ সক্ষমতা মানচিত্র' : 'Interactive capability instrument');
    $('.right-rail').setAttribute('aria-label', bn ? 'সক্ষমতার প্রমাণ, তুলনা ও প্রয়োগ' : 'Capability evidence, comparison and implications');
    $('#horizon').setAttribute('aria-label', bn ? 'ভবিষ্যতের সময়সীমা, বছর' : 'Future time horizon in years');
    $('.scenario-tabs').setAttribute('aria-label', bn ? 'এআই কত দ্রুত এগোবে তার দৃশ্য বাছুন' : 'Choose AI progress scenario');
    buildFacultySelect(); updateStats(); updateWatchlist();
    const activeTerritory = data[selected];
    setText('legendTerritory', displayName(activeTerritory.name));
    setText('legendTerritoryDesc', bn ? descriptionsBn[activeTerritory.name] : activeTerritory.desc);
    const territoryLabel = $('#legendTerritory');
    if (territoryLabel) territoryLabel.style.color = facultyColors[selected] || facultyColors[0];
    const biggest = data.reduce((best, d) => Math.abs(gap(d)) > Math.abs(gap(best)) ? d : best, data[0]);
    setText('largestGapFoot', bn ? (gap(biggest)<0 ? 'আত্মমূল্যায়নে এআই এগিয়ে' : displayName(biggest.name) + ' ক্ষেত্রে মানুষ এগিয়ে') : (gap(biggest)<0 ? 'AI leads in ' : 'Human leads in ') + biggest.name.toLowerCase());
    applyDynamicLanguage(); applyScenarioLanguage(); draw();
  }
  function classify(h, a) { const g = h - a; return Math.abs(g) <= 5 ? 'close' : (g > 0 ? 'human' : 'ai'); }
  function futureAI(d) { return clamp(d.ai + rate * years, 0, 100); }
  function counts(projected = false) {
    if(isAnimalComparator()) return {h:0,a:0,c:0};
    let h=0,a=0,c=0;
    data.forEach((d,i) => { const s=classify(d.human, comparisonScore(d,i,projected)); if(s==='human')h++; else if(s==='ai')a++; else c++; });
    return {h,a,c};
  }
  function updateStats() {
    const labels=Array.from(document.querySelectorAll('.metric-label'));
    const foots=Array.from(document.querySelectorAll('.metric-foot'));
    if(isAnimalComparator()) {
      const ratings=data.map((d,i)=>animalFinding(comparator,i));
      const evidenceCount=ratings.filter(r=>r.basis==='Evidence Based').length;
      const reasoningCount=ratings.length-evidenceCount;
      const average=Math.round(ratings.reduce((sum,r)=>sum+r.score,0)/ratings.length);
      const strongest=ratings.reduce((best,r,i)=>r.score>best.score?{...r,i}:best,{...ratings[0],i:0});
      const names=lang==='bn'?['প্রত্যক্ষ প্রমাণভিত্তিক','যুক্তিনির্ভর অনুমান','গড় সক্ষমতা-অনুমান','সর্বোচ্চ সক্ষমতা']:['Evidence-based','Reasoning-based estimate','Mean faculty estimate','Highest faculty estimate'];
      const values=[`${evidenceCount} / 10`,`${reasoningCount} / 10`,`${average} / 100`,`${displayName(data[strongest.i].name)} · ${strongest.score}`];
      const footValues=lang==='bn'?['সরাসরি আলোচিত সক্ষমতা','পরোক্ষ তথ্য বা সতর্ক অনুমান','স্বচ্ছ সংশ্লেষভিত্তিক মান','নির্বাচিত প্রাণীর মধ্যে']:['faculties directly addressed by the primary paper','faculties informed by indirect research or inference','synthesized estimate across ten faculties','within the selected species'];
      labels.forEach((el,i)=>{if(el)el.textContent=names[i]||'';});
      document.querySelectorAll('.metric-value').forEach((el,i)=>{el.textContent=values[i]||'';});
      foots.forEach((el,i)=>{if(el)el.textContent=footValues[i]||'';});
      setText('largestGapFoot',lang==='bn'?'দশটি সক্ষমতার মধ্যে সর্বোচ্চ অনুমান':'Highest estimate among ten faculties');
      return;
    }
    const c = counts(false);
    $('#humanCount').textContent = `${c.h} / 10`;
    $('#aiCount').textContent = `${c.a} / 10`;
    $('#closeCount').textContent = `${c.c} / 10`;
    const metricLabels=lang==='bn'?['মানব-রেফারেন্স এগিয়ে','এআই এগিয়ে','প্রায় সমান','সবচেয়ে বড় ব্যবধান']:['Human leads','AI leads','Near parity','Largest current gap'];
    const metricFoots=lang==='bn'?['১০টির মধ্যে সক্ষমতা','প্রকাশিত ফলের ভিত্তিতে','৫ পয়েন্টের মধ্যে','ভিন্ন পরীক্ষার সংখ্যাগত ব্যবধান']:['faculties out of 10','best published result per faculty','within five score points','numeric gap across unlike tests'];
    labels.forEach((el,i)=>{if(el)el.textContent=metricLabels[i]||'';});
    foots.forEach((el,i)=>{if(el)el.textContent=metricFoots[i]||'';});
    let biggest = data.reduce((best,d) => Math.abs(gap(d)) > Math.abs(gap(best)) ? d : best, data[0]);
    $('#largestGap').textContent = lang==='bn' ? `${toBanglaNumber(Math.abs(gap(biggest)).toFixed(0))} পয়েন্ট` : `${Math.abs(gap(biggest)).toFixed(0)} pts`;
    $('#largestGapFoot').textContent = gap(biggest)<0 ? (lang==='bn'?comparatorName()+' এগিয়ে: '+displayName(biggest.name):comparatorName()+' leads in '+biggest.name.toLowerCase()) : (lang==='bn'?displayName(biggest.name)+' ক্ষেত্রে মানুষ এগিয়ে':'Human leads in '+biggest.name.toLowerCase());
  }
  function applyAnimalInspector() {
    const d=data[selected], profile=comparativeProfiles[comparator], rating=animalFinding(comparator,selected);
    const inspector=$('.inspector');
    if(inspector) inspector.classList.add('animal-mode');
    const accent=facultyColors[selected]||facultyColors[0];
    document.documentElement.style.setProperty('--faculty-accent',accent);
    document.documentElement.style.setProperty('--faculty-accent-soft','color-mix(in srgb,'+accent+' 10%,#fff)');
    setText('facultyName',displayName(d.name));
    setText('facultyDesc',lang==='bn'?descriptionsBn[d.name]:d.desc);
    const selectedIndex=$('#selectedIndex');if(selectedIndex)selectedIndex.textContent=`${String(selected+1).padStart(2,'0')} / 10`;
    const chip=$('#statusChip');chip.className='status-chip '+(rating.basis==='Evidence Based'?'evidence':'reasoning');
    chip.textContent=basisLabel(rating.basis);
    setText('gapLabel',lang==='bn'?toBanglaNumber(rating.score)+' / ১০০ সক্ষমতা-অনুমান':rating.score+' / 100 faculty estimate');
    setText('humanCompareLabel',lang==='bn'?'মানব-তুলনার দল':'Human reference');
    setText('aiCompareLabel',animalLabel(comparator));
    setText('legendHuman',lang==='bn'?'সক্ষমতার অনুমান':'Faculty estimate / 100');
    setText('legendAI',lang==='bn'?'পূর্ণ বলয় = প্রত্যক্ষ প্রমাণভিত্তিক · ড্যাশযুক্ত বলয় = যুক্তিনির্ভর অনুমান':'Solid ring = evidence-based · dashed ring = reasoning-based estimate');
    setText('legendGap',lang==='bn'?'বড় বলয় = বেশি অনুমান':'Larger ring = higher estimate');
    setText('legendOrbit',lang==='bn'?'সক্ষমতার জালিকা':'Faculty mesh');
    setText('legendSelected',lang==='bn'?'নির্বাচিত সক্ষমতা':'Selected faculty');
    const legend=$('.legend');if(legend)legend.classList.add('animal-mode');
    setText('topResultLabel',lang==='bn'?'সক্ষমতার ভিত্তি':'FACULTY RATING BASIS');
    setText('modelName',animalLabel(comparator));
    setText('modelSource',animalFindingText(comparator,selected));
    setText('referenceCaveat',(lang==='bn'?profile.groupBn:profile.groupEn)+' '+(lang==='bn'?profile.limitBn:profile.limitEn));
    const est=$('#animalEstimate');
    if(est){est.style.setProperty('--estimate-value',rating.score);}
    setText('animalEstimateLabel',lang==='bn'?'সক্ষমতা-অনুমান':'Faculty estimate');
    setText('animalEstimateScore',String(rating.score));
    const estimateBar=$('#animalEstimateBar');if(estimateBar)estimateBar.style.width=rating.score+'%';
    setText('calibrationText',lang==='bn'
      ? 'প্রাণীর ০–১০০ মানগুলো নির্দিষ্ট কাজ ও জ্ঞানীয় গবেষণা থেকে তৈরি সক্ষমতা-অনুমান। প্রত্যক্ষ প্রমাণভিত্তিক মানে নির্বাচিত মূল গবেষণায় সক্ষমতাটি সরাসরি আলোচিত; যুক্তিনির্ভর অনুমান মানে পরোক্ষ তথ্য বা সতর্ক অনুমান ব্যবহৃত।'
      : 'Animal values are 0–100 faculty estimates synthesized from task findings and cognition research. Evidence Based means the selected primary study directly addresses the faculty; Reasoning Based means indirect findings or a cautious inference inform the estimate.');
    setText('everydayText',(wrap.dataset.view||'cosmos')==='impact'?(lang==='bn'?workImplicationsBn[d.name]:workImplications[d.name]):(lang==='bn'?everydayMeaningBn[d.name]:everydayMeaning[d.name]));
    const sourceLink=$('#facultySourceLink');
    if(sourceLink){sourceLink.href=profile.sourceUrl;sourceLink.textContent=lang==='bn'?'প্রাণীর জ্ঞানীয় সক্ষমতা নিয়ে গবেষণা দেখুন':'Explore animal cognition research';sourceLink.setAttribute('aria-label',lang==='bn'?'প্রাণীর জ্ঞানীয় সক্ষমতা নিয়ে গবেষণা দেখুন':'Explore animal cognition research');}
    setText('projectionMode',lang==='bn'?'CC ATLAS · মানুষকেন্দ্রিক':'CC ATLAS · Human-centered');
    setText('horizonValue',lang==='bn'?'গবেষণার স্ন্যাপশট':'Research snapshot');
    setText('scenarioMain',lang==='bn'?'সক্ষমতা-অনুমান · '+toBanglaNumber(rating.score)+' / ১০০':'Faculty estimate · '+rating.score+' / 100');
    setText('scenarioSub',lang==='bn'?'পূর্ণ বলয় = প্রত্যক্ষ প্রমাণভিত্তিক · ড্যাশযুক্ত বলয় = যুক্তিনির্ভর অনুমান · বড় বলয় = বেশি অনুমান।':'Solid ring = evidence-based · dashed ring = reasoning-based estimate · larger ring = higher estimate.');
    setText('galaxySubtitle',lang==='bn'?'দশটি সক্ষমতা · ০–১০০ অনুমান · প্রতিটি বলয়ের ভিত্তি দেখুন':'TEN FACULTIES · 0–100 ESTIMATES · INSPECT EACH RATING BASIS');
    const liveGuide=$('#canvasGuide');if(liveGuide)liveGuide.innerHTML=lang==='bn'
      ? '<b>সক্ষমতার মানচিত্র</b><br>বলয়ের আকার = সক্ষমতা-অনুমান<br>পূর্ণ বলয় = প্রত্যক্ষ প্রমাণভিত্তিক<br>ড্যাশ বলয় = যুক্তিনির্ভর অনুমান<br>নির্বাচিত বিন্দুতে স্কোর ও ব্যাখ্যা দেখুন।'
      : '<b>READ THE FACULTY MAP</b><br>Ring size = faculty estimate<br>Solid ring = Evidence Based<br>Dashed ring = Reasoning Based<br>Select a marker for its score and rationale.';
    setText('aiCompareLabel',animalLabel(comparator));
  }

  function updateInspector() {
    if(isAnimalComparator()) { applyAnimalInspector(); return; }
    const inspector=$('.inspector');if(inspector)inspector.classList.remove('animal-mode');
    const legend=$('.legend');if(legend)legend.classList.remove('animal-mode');
    const d = data[selected], a = comparisonScore(d,selected,years>0), projected = years > 0 && comparator==='ai';
    const accent = facultyColors[selected] || facultyColors[0];
    document.documentElement.style.setProperty('--faculty-accent',accent);
    document.documentElement.style.setProperty('--faculty-accent-soft','color-mix(in srgb,'+accent+' 10%,#fff)');
    const state = classify(d.human, a);
    const selectedIndex=$('#selectedIndex');if(selectedIndex)selectedIndex.textContent=`${String(selected+1).padStart(2,'0')} / 10`;
    $('#facultyName').textContent = d.name;
    $('#facultyDesc').textContent = d.desc;
    const territoryName = $('#legendTerritory');
    const territoryDesc = $('#legendTerritoryDesc');
    if (territoryName) { territoryName.textContent = displayName(d.name); territoryName.style.color = accent; }
    if (territoryDesc) territoryDesc.textContent = lang === 'bn' ? descriptionsBn[d.name] : d.desc;
    const chip=$('#statusChip'); chip.className=`status-chip ${state}`;
    chip.textContent = lang==='bn' ? (state==='close'?'প্রায় সমান':state==='human'?'মানব-রেফারেন্স এগিয়ে':'এআই এগিয়ে') : (state==='close'?'Near parity':state==='human'?'Human leads':'AI leads');
    const g = d.human-a;
    $('#gapLabel').textContent = lang==='bn' ? `${g>=0?'+':''}${toBanglaNumber(g.toFixed(1))} পয়েন্টের ব্যবধান${projected?' · দৃশ্যপট':''}` : `${g>=0?'+':''}${g.toFixed(1)} point gap${projected?' · scenario':''}`;
    $('#humanBar').style.width=`${d.human}%`;
    $('#aiBar').style.width=`${a}%`;
    $('#humanScore').textContent=fmt(d.human);
    $('#aiScore').textContent=fmt(a)+(projected?'*':'');
    $('#modelName').textContent=lang==='bn' && d.name==='Metacognition' ? 'MetaBound · সর্বোচ্চ প্রকাশিত মডেল' : d.model;
    $('#modelSource').textContent=projected ? (lang === 'bn' ? 'আজকের ফল '+toBanglaNumber(fmt(d.ai))+' → দৃশ্যপট '+toBanglaNumber(fmt(a))+' · এটি পূর্বাভাস নয়' : `Today ${fmt(d.ai)} → scenario ${fmt(a)} · ${d.source}`) : `${lang==='bn' ? (aiRefBn[d.name] || d.aiRef) : d.aiRef} · ${lang==='bn' ? (confidenceBn[d.confidence] || d.confidence) : d.confidence}`;
    $('#projectionMode').textContent = projected ? (lang === 'bn' ? 'দৃশ্যপট · +' + toBanglaNumber(rate) + ' পয়েন্ট/বছর' : `Scenario · +${rate} pts/yr`) : (lang === 'bn' ? 'আজ · প্রকাশিত ফল' : 'Today · observed');
  }

  function updateInspector() {
    if(isAnimalComparator()) { applyAnimalInspector(); return; }
    const inspector=$('.inspector');if(inspector)inspector.classList.remove('animal-mode');
    const legend=$('.legend');if(legend)legend.classList.remove('animal-mode');
    const d = data[selected], a = comparisonScore(d,selected,years>0), projected = years > 0 && comparator==='ai';
    const accent = facultyColors[selected] || facultyColors[0];
    document.documentElement.style.setProperty('--faculty-accent',accent);
    document.documentElement.style.setProperty('--faculty-accent-soft','color-mix(in srgb,'+accent+' 10%,#fff)');
    const state = classify(d.human, a);
    const selectedIndex=$('#selectedIndex');if(selectedIndex)selectedIndex.textContent=`${String(selected+1).padStart(2,'0')} / 10`;
    $('#facultyName').textContent = d.name;
    $('#facultyDesc').textContent = d.desc;
    const territoryName = $('#legendTerritory');
    const territoryDesc = $('#legendTerritoryDesc');
    if (territoryName) { territoryName.textContent = displayName(d.name); territoryName.style.color = accent; }
    if (territoryDesc) territoryDesc.textContent = lang === 'bn' ? descriptionsBn[d.name] : d.desc;
    const chip=$('#statusChip'); chip.className=`status-chip ${state}`;
    chip.textContent = lang==='bn' ? (state==='close'?'প্রায় সমান':state==='human'?'মানব-রেফারেন্স এগিয়ে':'এআই এগিয়ে') : (state==='close'?'Near parity':state==='human'?'Human leads':'AI leads');
    const g = d.human-a;
    $('#gapLabel').textContent = lang==='bn' ? `${g>=0?'+':''}${toBanglaNumber(g.toFixed(1))} পয়েন্টের ব্যবধান${projected?' · দৃশ্যপট':''}` : `${g>=0?'+':''}${g.toFixed(1)} point gap${projected?' · scenario':''}`;
    $('#humanBar').style.width=`${d.human}%`;
    $('#aiBar').style.width=`${a}%`;
    $('#humanScore').textContent=fmt(d.human);
    $('#aiScore').textContent=fmt(a)+(projected?'*':'');
    $('#modelName').textContent=lang==='bn' && d.name==='Metacognition' ? 'MetaBound · সর্বোচ্চ প্রকাশিত মডেল' : d.model;
    $('#modelSource').textContent=projected ? (lang === 'bn' ? 'আজকের ফল '+toBanglaNumber(fmt(d.ai))+' → দৃশ্যপট '+toBanglaNumber(fmt(a))+' · এটি পূর্বাভাস নয়' : `Today ${fmt(d.ai)} → scenario ${fmt(a)} · ${d.source}`) : `${lang==='bn' ? (aiRefBn[d.name] || d.aiRef) : d.aiRef} · ${lang==='bn' ? (confidenceBn[d.confidence] || d.confidence) : d.confidence}`;
    $('#projectionMode').textContent = projected ? (lang === 'bn' ? 'দৃশ্যপট · +' + toBanglaNumber(rate) + ' পয়েন্ট/বছর' : `Scenario · +${rate} pts/yr`) : (lang === 'bn' ? 'আজ · প্রকাশিত ফল' : 'Today · observed');
  }
  function updateScenario() {
    if(isAnimalComparator()) {
      years=0;$('#horizon').value='0';applyAnimalInspector();applyDynamicLanguage();draw();return;
    }
    years=Number($('#horizon').value);
    const bn=lang==='bn';
    $('#horizonValue').textContent=years===0?(bn?'আজ':'Today'):(bn?'+'+years+' বছর':`+${years} year${years===1?'':'s'}`);
    const c=counts(years>0);
    $('#scenarioMain').textContent=years===0?(bn?'আজকের তুলনা · প্রকাশিত তথ্য':'Today’s comparison · source snapshot'):(bn?'১০টির মধ্যে '+toBanglaNumber(c.a)+'টি সক্ষমতায় এআই এগিয়ে':`${c.a} of 10 faculties AI-led`);
    $('#scenarioSub').textContent=years===0?(bn?'প্রকাশিত স্কোর দেখানো হচ্ছে; ভবিষ্যৎ অনুমান যোগ করা হয়নি।':'Observed source scores; current snapshot.'):(bn?'উদাহরণ: বছরে '+toBanglaNumber(rate)+' স্কোর-পয়েন্ট বৃদ্ধি, সর্বোচ্চ ১০০। এটি পূর্বাভাস নয়।':'Scenario: +'+rate+' score points/year for '+years+' year'+(years===1?'':'s')+', capped at 100. This is a what-if, not a forecast.');
    document.querySelectorAll('.scenario').forEach(b=>b.setAttribute('aria-pressed',String(Number(b.dataset.rate)===rate)));
    updateInspector();applyDynamicLanguage();applyScenarioLanguage();draw();
  }
  function vecRotate(p) {
    const cy=Math.cos(yaw), sy=Math.sin(yaw), cx=Math.cos(pitch), sx=Math.sin(pitch);
    const x=p.x*cy-p.z*sy, z=p.x*sy+p.z*cy;
    return {x, y:p.y*cx-z*sx, z:p.y*sx+z*cx};
  }
  function project(p, w, h, scale) {
    const r=vecRotate(p), focal=5.3, k=focal/(focal-r.z);
    const centerX = w*.52;
    const centerY = h*.51;
    return {x:centerX+r.x*k*scale, y:centerY+r.y*k*scale, z:r.z, k};
  }
  function makeIcosphere(level=2) {
    const t=(1+Math.sqrt(5))/2;
    const vertices=[[-1,t,0],[1,t,0],[-1,-t,0],[1,-t,0],[0,-1,t],[0,1,t],[0,-1,-t],[0,1,-t],[t,0,-1],[t,0,1],[-t,0,-1],[-t,0,1]];
    const faces=[[0,11,5],[0,5,1],[0,1,7],[0,7,10],[0,10,11],[1,5,9],[5,11,4],[11,10,2],[10,7,6],[7,1,8],[3,9,4],[3,4,2],[3,2,6],[3,6,8],[3,8,9],[4,9,5],[2,4,11],[6,2,10],[8,6,7],[9,8,1]];
    const normalize=v=>{const m=Math.hypot(v[0],v[1],v[2])||1;return [v[0]/m,v[1]/m,v[2]/m];};
    for(let i=0;i<vertices.length;i++)vertices[i]=normalize(vertices[i]);
    let triangles=faces;
    for(let n=0;n<level;n++){
      const cache=new Map(),next=[];
      const mid=(a,b)=>{const key=a<b?`${a}:${b}`:`${b}:${a}`;if(cache.has(key))return cache.get(key);const v=normalize([(vertices[a][0]+vertices[b][0])/2,(vertices[a][1]+vertices[b][1])/2,(vertices[a][2]+vertices[b][2])/2]);const index=vertices.push(v)-1;cache.set(key,index);return index;};
      triangles.forEach(([a,b,c])=>{const ab=mid(a,b),bc=mid(b,c),ca=mid(c,a);next.push([a,ab,ca],[b,bc,ab],[c,ca,bc],[ab,bc,ca]);});
      triangles=next;
    }
    const seen=new Set(),edges=[];
    triangles.forEach(face=>{for(let j=0;j<3;j++){const a=face[j],b=face[(j+1)%3],key=a<b?`${a}:${b}`:`${b}:${a}`;if(!seen.has(key)){seen.add(key);edges.push([a,b]);}}});
    return {vertices,edges};
  }
  const sphereMesh=makeIcosphere(3);
  const facultyColors=['#E30613','#E85D3F','#D98218','#A6A822','#1D9856','#009D91','#198CB6','#3268D4','#7956CC','#C5448C'];
  // Deterministic farthest-point sampling assigns every faculty to a real vertex in the same geodesic mesh.
  function chooseGeodesicAnchors(mesh,count) {
    const v=mesh.vertices;
    let seed=0;
    for(let i=1;i<v.length;i++) if(v[i][1]>v[seed][1]) seed=i;
    const chosen=[seed];
    while(chosen.length<count) {
      let winner=-1,winnerDistance=-Infinity;
      for(let i=0;i<v.length;i++) {
        if(chosen.includes(i)) continue;
        let nearest=Infinity;
        for(const j of chosen) {
          const dot=v[i][0]*v[j][0]+v[i][1]*v[j][1]+v[i][2]*v[j][2];
          nearest=Math.min(nearest,1-dot);
        }
        if(nearest>winnerDistance){winnerDistance=nearest;winner=i;}
      }
      if(winner<0) break;
      chosen.push(winner);
    }
    return chosen.map(i=>({x:v[i][0],y:v[i][1],z:v[i][2]}));
  }
  const facultyAnchors=chooseGeodesicAnchors(sphereMesh,data.length);
  const meshFacultyIndex=sphereMesh.vertices.map(v=>{
    let bestIndex=0,bestDot=-Infinity;
    facultyAnchors.forEach((a,i)=>{const dot=v[0]*a.x+v[1]*a.y+v[2]*a.z;if(dot>bestDot){bestDot=dot;bestIndex=i;}});
    return bestIndex;
  });
  function facultySurfacePositions(d,i,aiScore) {
    const anchor=facultyAnchors[i];
    const reference=Math.abs(anchor.y)<.88?{x:0,y:1,z:0}:{x:1,y:0,z:0};
    const tangent=normalize3(cross3(anchor,reference));
    const radius=1.075;
    const human=normalize3({x:anchor.x-tangent.x*.03,y:anchor.y-tangent.y*.03,z:anchor.z-tangent.z*.03});
    const spread=.11+Math.min(Math.abs(d.human-aiScore),100)/100*.95;
    const ai=normalize3({x:anchor.x+tangent.x*spread,y:anchor.y+tangent.y*spread,z:anchor.z+tangent.z*spread});
    return {anchor:{x:anchor.x*radius,y:anchor.y*radius,z:anchor.z*radius},human:{x:human.x*radius,y:human.y*radius,z:human.z*radius},ai:{x:ai.x*radius,y:ai.y*radius,z:ai.z*radius}};
  }
  function resize() {
    const box=wrap.getBoundingClientRect(), dpr=Math.min(window.devicePixelRatio||1,2);
    canvas.width=Math.max(1,Math.floor(box.width*dpr)); canvas.height=Math.max(1,Math.floor(box.height*dpr));
    canvas.style.width=box.width+'px'; canvas.style.height=box.height+'px';
    ctx.setTransform(dpr,0,0,dpr,0,0); draw();
  }
  function rgbForStatus(d, aiScoreValue) { const s=classify(d.human, aiScoreValue); return s==='human'?'#ffbd55':s==='ai'?'#d8f45a':'#d2b7f7'; }
  function draw() {
    if(!ctx) return;
    const w=wrap.clientWidth, h=wrap.clientHeight; if(!w||!h)return;
    const view=wrap.dataset.view||'cosmos';
    const dpr=Math.min(window.devicePixelRatio||1,2); ctx.setTransform(dpr,0,0,dpr,0,0);
    ctx.clearRect(0,0,w,h);
    const backdrop=ctx.createLinearGradient(0,0,w,h);backdrop.addColorStop(0,'#f2f4f8');backdrop.addColorStop(.54,'#f8f9fc');backdrop.addColorStop(1,'#edf0f5');ctx.fillStyle=backdrop;ctx.fillRect(0,0,w,h);
    const reflection=ctx.createRadialGradient(w*.18,h*.04,0,w*.18,h*.04,Math.max(w,h)*.8);reflection.addColorStop(0,'rgba(255,255,255,.78)');reflection.addColorStop(.38,'rgba(255,255,255,.18)');reflection.addColorStop(1,'rgba(229,235,245,0)');ctx.fillStyle=reflection;ctx.fillRect(0,0,w,h);
    const scale=Math.min(w*(w<620?.46:.35),h*.43,340)*zoom;
    const center=project({x:0,y:0,z:0},w,h,scale);
    const sphereRadius=scale*1.055;
    const surface=ctx.createRadialGradient(center.x-scale*.34,center.y-scale*.39,scale*.025,center.x,center.y,scale*1.08);
    surface.addColorStop(0,'rgba(255,255,255,1)');surface.addColorStop(.42,'rgba(255,255,255,.98)');surface.addColorStop(.77,'rgba(244,247,252,.92)');surface.addColorStop(1,'rgba(225,232,241,.48)');
    ctx.beginPath();ctx.arc(center.x,center.y,sphereRadius,0,Math.PI*2);ctx.fillStyle=surface;ctx.fill();ctx.strokeStyle='rgba(91,104,125,.2)';ctx.lineWidth=1;ctx.stroke();
    ctx.beginPath();ctx.arc(center.x,center.y,sphereRadius-2,Math.PI*1.08,Math.PI*1.88);ctx.strokeStyle='rgba(255,255,255,.98)';ctx.lineWidth=2;ctx.stroke();
    ctx.save();ctx.beginPath();ctx.arc(center.x,center.y,sphereRadius-1,0,Math.PI*2);ctx.clip();const sheen=ctx.createLinearGradient(center.x-scale,center.y-scale,center.x+scale*.8,center.y+scale*.8);sheen.addColorStop(0,'rgba(255,255,255,.28)');sheen.addColorStop(.32,'rgba(255,255,255,0)');sheen.addColorStop(.77,'rgba(255,255,255,0)');sheen.addColorStop(1,'rgba(211,221,236,.12)');ctx.fillStyle=sheen;ctx.fillRect(center.x-sphereRadius,center.y-sphereRadius,sphereRadius*2,sphereRadius*2);ctx.restore();
    const meshPoints=sphereMesh.vertices.map(v=>project({x:v[0]*1.055,y:v[1]*1.055,z:v[2]*1.055},w,h,scale));
    sphereMesh.edges.forEach(([a,b])=>{
      const p=meshPoints[a],q=meshPoints[b],depth=(p.z+q.z)/2;
      ctx.beginPath();ctx.moveTo(p.x,p.y);ctx.lineTo(q.x,q.y);
      const selectedEdge=meshFacultyIndex[a]===selected&&meshFacultyIndex[b]===selected;
      ctx.strokeStyle=facultyColors[meshFacultyIndex[a]]+(depth<-.12?(selectedEdge?'38':'20'):(selectedEdge?'f0':'5e'));ctx.lineWidth=selectedEdge?(depth<-.12?.7:1.15):(depth<-.12?.45:.8);ctx.stroke();
    });
    const waveTime=prefersReduced?0:performance.now()/1900;
    meshPoints.forEach((p,i)=>{
      const v=sphereMesh.vertices[i];
      const ripple=(Math.sin(waveTime+v[0]*2.7+v[1]*1.9+v[2]*2.4)+1)/2;
      const selectedRegion=meshFacultyIndex[i]===selected;
      const nodeRadius=p.z<-.12?.55:selectedRegion?(ripple>.91?4.2:2.7):ripple>.91?2.0:1.05;
      ctx.beginPath();ctx.arc(p.x,p.y,nodeRadius,0,Math.PI*2);
      const nodeColor=facultyColors[meshFacultyIndex[i]];
      ctx.fillStyle=p.z<-.12?nodeColor+(selectedRegion?'38':'22'):selectedRegion?(ripple>.91?nodeColor+'ff':nodeColor+'e5'):ripple>.91?nodeColor+'b0':nodeColor+(ripple>.65?'8a':'62');ctx.fill();
    });
    // Faculty points and edges.
    points=[];links=[];meshPoints.forEach((p,vertexIndex)=>{if(p.z>-.12){const facultyIndex=meshFacultyIndex[vertexIndex];points.push({x:p.x,y:p.y,kind:'mesh',i:facultyIndex,z:p.z,score:comparisonScore(data[facultyIndex],facultyIndex,years>0)});}});
    if(isAnimalComparator()) {
      data.forEach((d,i)=>{
        const anchor=facultyAnchors[i], anchorP=project({x:anchor.x*1.075,y:anchor.y*1.075,z:anchor.z*1.075},w,h,scale), front=anchorP.z>-.02;
        const rating=animalFinding(comparator,i), color=facultyColors[i];
        const pulse=prefersReduced?.5:(Math.sin(performance.now()/380)+1)/2;
        const scoreRadius=6+rating.score*.065;
        const basisIsEvidence=rating.basis==='Evidence Based';
        if(i===selected){ctx.beginPath();ctx.arc(anchorP.x,anchorP.y,scoreRadius+8+pulse*2,0,Math.PI*2);ctx.strokeStyle=color;ctx.lineWidth=2;ctx.stroke();ctx.beginPath();ctx.arc(anchorP.x,anchorP.y,scoreRadius+15+pulse*3,0,Math.PI*2);ctx.strokeStyle=color;ctx.globalAlpha=.14+pulse*.14;ctx.stroke();ctx.globalAlpha=1;}
        if(front){
          const glow=ctx.createRadialGradient(anchorP.x,anchorP.y,0,anchorP.x,anchorP.y,scoreRadius*3.2);glow.addColorStop(0,color+(i===selected?'45':'18'));glow.addColorStop(1,color+'00');ctx.fillStyle=glow;ctx.fillRect(anchorP.x-scoreRadius*3.2,anchorP.y-scoreRadius*3.2,scoreRadius*6.4,scoreRadius*6.4);
          ctx.beginPath();ctx.arc(anchorP.x,anchorP.y,scoreRadius,0,Math.PI*2);ctx.fillStyle=color;ctx.fill();ctx.strokeStyle='#fff';ctx.lineWidth=1.25;ctx.stroke();
          ctx.beginPath();ctx.arc(anchorP.x,anchorP.y,scoreRadius+4.5,0,Math.PI*2);ctx.strokeStyle=color;ctx.globalAlpha=i===selected?.95:.78;ctx.lineWidth=i===selected?1.8:1.15;ctx.setLineDash(basisIsEvidence?[]:[3,2.5]);ctx.stroke();ctx.setLineDash([]);ctx.globalAlpha=1;
          if(i===selected||w>520||view==='evidence'&&w>850){
            const label=displayName(d.name),lx=anchorP.x+(anchorP.x>w*.5?-14:14),ly=anchorP.y+(anchorP.y>h*.55?-14:15);
            ctx.font=i===selected?'400 14px Manrope, sans-serif':'600 10px '+getComputedStyle(document.body).fontFamily;ctx.textAlign=anchorP.x>w*.5?'right':'left';ctx.textBaseline='middle';ctx.fillStyle=i===selected?color:'#4f4f4f';ctx.fillText(label,lx,ly);
            if(i===selected||view==='frontier'){ctx.font='700 9px '+getComputedStyle(document.body).fontFamily;ctx.fillStyle='#4f4f4f';ctx.fillText(lang==='bn'?toBanglaNumber(String(rating.score)):String(rating.score),lx,ly+(anchorP.y>h*.55?12:-12));}
          }
          points.push({x:anchorP.x,y:anchorP.y,kind:'animal-evidence',i,z:anchorP.z,score:rating.score,basis:rating.basis,note:lang==='bn'?rating.bn:rating.en});
        }
      });
    } else {
      const largestGaps=new Set(data.map((d,i)=>({d,gap:Math.abs(d.human-comparisonScore(d,i,false))})).sort((a,b)=>b.gap-a.gap).slice(0,3).map(item=>item.d.name));
      data.forEach((d,i)=>{
        const aScore=comparisonScore(d,i,years>0);
        const position=facultySurfacePositions(d,i,aScore);
        const currentPosition=facultySurfacePositions(d,i,comparisonScore(d,i,false));
        const hp=project(position.human,w,h,scale), ap=project(position.ai,w,h,scale), anchorP=project(position.anchor,w,h,scale), currentAp=project(currentPosition.ai,w,h,scale);
        const front=anchorP.z>-.02;
        const gapSize=Math.abs(d.human-aScore);
        ctx.beginPath();ctx.moveTo(hp.x,hp.y);ctx.lineTo(ap.x,ap.y);
        ctx.strokeStyle=facultyColors[i]+(i===selected?'ff':view==='frontier'?'82':'52');
        if(view==='frontier'){ctx.strokeStyle=facultyColors[i]+(i===selected?'ff':'88');ctx.lineWidth=i===selected?1.8:.75+Math.min(1.5,gapSize/35);}
        else ctx.lineWidth=i===selected?1.65:1.0;
        ctx.stroke();
        if(front) links.push({x1:hp.x,y1:hp.y,x2:ap.x,y2:ap.y,i,gap:gapSize,score:aScore});
        if(view==='trajectory' && years>0){const bp=currentAp;if(front){ctx.save();ctx.setLineDash([4,4]);ctx.beginPath();ctx.moveTo(bp.x,bp.y);ctx.lineTo(ap.x,ap.y);ctx.strokeStyle=facultyColors[i]+'d0';ctx.lineWidth=1.8;ctx.stroke();ctx.setLineDash([]);ctx.beginPath();ctx.arc(bp.x,bp.y,4,0,Math.PI*2);ctx.strokeStyle='#777';ctx.lineWidth=1;ctx.stroke();ctx.restore();}}
        if(i===selected){const pulse=prefersReduced?.5:(Math.sin(performance.now()/380)+1)/2;ctx.beginPath();ctx.arc(anchorP.x,anchorP.y,14+pulse*4,0,Math.PI*2);ctx.strokeStyle=facultyColors[i];ctx.lineWidth=2;ctx.stroke();ctx.beginPath();ctx.arc(anchorP.x,anchorP.y,25+pulse*8,0,Math.PI*2);ctx.strokeStyle=facultyColors[i];ctx.globalAlpha=.16+pulse*.19;ctx.stroke();ctx.globalAlpha=1;ctx.beginPath();ctx.arc(anchorP.x,anchorP.y,4.5+pulse*1.5,0,Math.PI*2);ctx.fillStyle=facultyColors[i];ctx.fill();}
        if(view==='evidence'){const confidence=d.confidence.toLowerCase(),level=(confidence.includes('estimated')||confidence.includes('different tests')||confidence.includes('vendor-reported'))?3:(confidence.includes('small')||confidence.includes('harness'))?2:1;const ringColor=level===3?facultyColors[i]:level===2?'rgba(70,70,70,.8)':'rgba(150,150,150,.7)';if(front){ctx.save();ctx.beginPath();ctx.arc(anchorP.x,anchorP.y,13+level*4.5,0,Math.PI*2);ctx.strokeStyle=ringColor;ctx.lineWidth=level===1?1:1.5;ctx.setLineDash(level===1?[]:[3,4]);ctx.stroke();ctx.setLineDash([]);if(i===selected||(w>1100&&level===3)){ctx.font='700 9px '+getComputedStyle(document.body).fontFamily;ctx.textAlign=anchorP.x>w*.5?'right':'left';ctx.fillStyle=ringColor;ctx.fillText((lang==='bn'?(level===3?'উচ্চ সতর্কতা':level===2?'প্রমাণ মিশ্র':'উৎস শনাক্ত'):(level===3?'HIGH CAVEAT':level===2?'MIXED':'TRACEABLE')),anchorP.x+(anchorP.x>w*.5?-23:23),anchorP.y-18);}ctx.restore();}}
        const aiColor=facultyColors[i],selectedMarkerRadius=5.8;
        ctx.beginPath();ctx.arc(hp.x,hp.y,i===selected?selectedMarkerRadius:3.6,0,Math.PI*2);ctx.fillStyle=front?'#171717':'#c9c8c0';ctx.fill();ctx.strokeStyle='#f7f6f2';ctx.lineWidth=i===selected?1.3:.65;ctx.stroke();
        ctx.beginPath();ctx.arc(hp.x,hp.y,i===selected?12:6.8,0,Math.PI*2);ctx.strokeStyle=facultyColors[i];ctx.globalAlpha=front?(i===selected?.92:.43):.1;ctx.lineWidth=i===selected?1.5:.75;ctx.stroke();ctx.globalAlpha=1;
        const glowRadius=i===selected?23:16,glow=ctx.createRadialGradient(ap.x,ap.y,0,ap.x,ap.y,glowRadius);glow.addColorStop(0,aiColor+(i===selected?'48':'00'));glow.addColorStop(1,aiColor+'00');ctx.fillStyle=glow;ctx.fillRect(ap.x-glowRadius,ap.y-glowRadius,glowRadius*2,glowRadius*2);
        if(i===selected){ctx.beginPath();ctx.arc(ap.x,ap.y,selectedMarkerRadius,0,Math.PI*2);ctx.fillStyle=front?aiColor:aiColor+'55';ctx.fill();ctx.strokeStyle='#fff';ctx.globalAlpha=front?1:.55;ctx.lineWidth=1.3;ctx.stroke();ctx.strokeStyle='#252a34';ctx.lineWidth=.6;ctx.stroke();ctx.globalAlpha=1;}else{const markerSize=6.3;ctx.beginPath();ctx.moveTo(ap.x,ap.y-markerSize);ctx.lineTo(ap.x+markerSize,ap.y);ctx.lineTo(ap.x,ap.y+markerSize);ctx.lineTo(ap.x-markerSize,ap.y);ctx.closePath();ctx.fillStyle=front?aiColor+'c5':aiColor+'55';ctx.fill();ctx.strokeStyle='#fff';ctx.globalAlpha=front?.74:.45;ctx.lineWidth=1.05;ctx.stroke();ctx.strokeStyle='#252a34';ctx.lineWidth=.8;ctx.stroke();ctx.globalAlpha=1;}
        if(front){ctx.beginPath();ctx.arc(anchorP.x,anchorP.y,2.2,0,Math.PI*2);ctx.fillStyle=i===selected?facultyColors[i]:'#777';ctx.fill();}
        if(front&&(i===selected||w>520||(view==='frontier'&&largestGaps.has(d.name))||(view==='trajectory'&&years>0)||(view==='impact'&&w>850)||(view==='evidence'&&w>850&&evidenceRisk(d)>=2)||(view==='cosmos'&&w>850))){const label=displayName(d.name),lx=anchorP.x+(anchorP.x>w*.5?-12:12),ly=anchorP.y+(anchorP.y>h*.55?-13:15);ctx.font=i===selected?'400 14px Manrope, sans-serif':'600 10px '+getComputedStyle(document.body).fontFamily;ctx.textAlign=anchorP.x>w*.5?'right':'left';ctx.textBaseline='middle';ctx.fillStyle=i===selected?facultyColors[i]:'#4f4f4f';ctx.fillText(label,lx,ly);if(view==='frontier'){ctx.font='700 9px '+getComputedStyle(document.body).fontFamily;ctx.fillStyle=gapSize>25?'#e30613':'#666';ctx.fillText((aScore>=d.human?'+':'−')+(lang==='bn'?toBanglaNumber(gapSize.toFixed(1)):gapSize.toFixed(1)),lx,ly+(ap.y>h*.55?12:-12));}}
        if(view==='impact'&&i===selected){ctx.beginPath();ctx.arc(ap.x,ap.y,23,0,Math.PI*2);ctx.strokeStyle=facultyColors[i]+'e6';ctx.lineWidth=1.1;ctx.stroke();ctx.beginPath();ctx.arc(ap.x,ap.y,31,0,Math.PI*2);ctx.strokeStyle=facultyColors[i]+'59';ctx.setLineDash([2,5]);ctx.stroke();ctx.setLineDash([]);}
        if(front){points.push({x:ap.x,y:ap.y,kind:'ai',i,z:ap.z,score:aScore});points.push({x:hp.x,y:hp.y,kind:'human',i,z:hp.z,score:d.human});}
      });
    }
  }
  function animate(t){
    if(!last)last=t;
    if(t-last>20){
      if(focusMotion){
        const deltaYaw=Math.atan2(Math.sin(focusMotion.yaw-yaw),Math.cos(focusMotion.yaw-yaw));
        yaw+=deltaYaw*.13;
        pitch+=(focusMotion.pitch-pitch)*.13;
        if(Math.abs(deltaYaw)<.001&&Math.abs(focusMotion.pitch-pitch)<.001){yaw=focusMotion.yaw;pitch=focusMotion.pitch;focusMotion=null;}
      } else if(autoSpin&&!drag) yaw+=.001;
      draw();last=t;
    }
    raf=requestAnimationFrame(animate);
  }
  function hit(e){
    const r=canvas.getBoundingClientRect(),x=e.clientX-r.left,y=e.clientY-r.top;
    let best=null,dist=Infinity;
    for(const p of points){if(p.kind!=='human'&&p.kind!=='ai'&&p.kind!=='animal-evidence')continue;const d=Math.hypot(x-p.x,y-p.y);if(d<dist){best=p;dist=d;}}
    if(best&&dist<18)return best;
    best=null;dist=Infinity;
    for(const p of points){if(p.kind!=='mesh')continue;const d=Math.hypot(x-p.x,y-p.y);if(d<dist){best=p;dist=d;}}
    if(best&&dist<9)return best;
    let target=null,lineDist=Infinity;
    for(const link of links){const vx=link.x2-link.x1,vy=link.y2-link.y1,len=vx*vx+vy*vy||1,t=clamp(((x-link.x1)*vx+(y-link.y1)*vy)/len,0,1),d=Math.hypot(x-(link.x1+t*vx),y-(link.y1+t*vy));if(d<lineDist){target=link;lineDist=d;}}
    return target&&lineDist<7?{x:(target.x1+target.x2)/2,y:(target.y1+target.y2)/2,kind:'link',i:target.i,score:target.score}:null;
  }
  canvas.addEventListener('pointerdown',e=>{drag={x:e.clientX,y:e.clientY,downX:e.clientX,downY:e.clientY,moved:false};focusMotion=null;canvas.setPointerCapture(e.pointerId);canvas.classList.add('dragging');autoSpin=false;applyScenarioLanguage();});
  canvas.addEventListener('pointermove',e=>{
    if(drag){const dx=e.clientX-drag.x,dy=e.clientY-drag.y;if(Math.abs(e.clientX-drag.downX)+Math.abs(e.clientY-drag.downY)>3)drag.moved=true;yaw+=dx*.009;pitch=clamp(pitch+dy*.006,.28,1.35);drag.x=e.clientX;drag.y=e.clientY;draw();tooltip.style.display='none';return;}
    const found=hit(e);hover=found;canvas.style.cursor=found?'pointer':'grab';
    const territoryIndex=found&&found.kind==='mesh'&&Number.isInteger(found.i)&&data[found.i]?found.i:selected;
    const territoryData=data[territoryIndex],territoryLabel=$('#legendTerritory'),territoryDescription=$('#legendTerritoryDesc');
    if(territoryLabel&&territoryData){territoryLabel.textContent=displayName(territoryData.name);territoryLabel.style.color=facultyColors[territoryIndex]||facultyColors[0];}
    if(territoryDescription&&territoryData)territoryDescription.textContent=lang==='bn'?descriptionsBn[territoryData.name]:territoryData.desc;
    if(!found){tooltip.style.display='none';return;}
    const d=data[found.i];let content='';
    if(isAnimalComparator()){
      const rating=animalFinding(comparator,found.i);
      const basis=rating.basis;
      const detail=lang==='bn'?rating.bn:rating.en;
      content=`<strong>${displayName(d.name)}</strong><span>${rating.score} / 100 · ${basis}</span><span>${detail}</span>`;
    } else {
      const role=found.kind==='human'?(lang==='bn'?'মানব-তুলনা':'Human reference'):(lang==='bn'?'এআই ফল':'AI result');
      const gapText=(lang==='bn'?'দুই স্কোরের ব্যবধান: ':'Reported score gap: ')+Math.abs(d.human-d.ai).toFixed(1)+(lang==='bn'?' পয়েন্ট':' pts');
      const detail=wrap.dataset.view==='evidence'?(lang==='bn'?'তুলনার সতর্কতা: ':'Evidence caveat: ')+(lang==='bn'?(confidenceBn[d.confidence]||d.confidence):d.confidence):wrap.dataset.view==='frontier'?gapText:wrap.dataset.view==='trajectory'&&years>0?(lang==='bn'?'দৃশ্যপটের বৃদ্ধি: ':'Scenario uplift: ')+(rate*years)+(lang==='bn'?' পয়েন্ট, পূর্বাভাস নয়':' pts, not a forecast'):(lang==='bn'?(evidenceLedger[d.name]?.sourceName||'নির্দিষ্ট পরীক্ষার ফল'):d.source);
      content=`<strong>${displayName(d.name)}</strong><span>${role} · ${fmt(found.score)} / 100</span><span>${detail}</span>`;
    }
    tooltip.innerHTML=content;tooltip.style.display='block';
    const rect=wrap.getBoundingClientRect(),box=tooltip.getBoundingClientRect();
    tooltip.style.left=clamp(e.clientX-rect.left+14,10,rect.width-box.width-10)+'px';tooltip.style.top=clamp(e.clientY-rect.top+10,10,rect.height-box.height-10)+'px';
  });
  canvas.addEventListener('pointerup',e=>{if(!drag)return;const wasMoved=drag.moved;drag=null;canvas.classList.remove('dragging');autoSpin=true;applyScenarioLanguage();if(!wasMoved){const p=hit(e);if(p)selectFaculty(p.i);}});
  canvas.addEventListener('pointercancel',()=>{drag=null;canvas.classList.remove('dragging');autoSpin=true;applyScenarioLanguage();});
  canvas.addEventListener('click',e=>{if(drag)return;const p=hit(e);if(p)selectFaculty(p.i);});
  canvas.addEventListener('keydown',e=>{if(e.key==='ArrowRight'||e.key==='ArrowDown'){e.preventDefault();selectFaculty(selected+1);}else if(e.key==='ArrowLeft'||e.key==='ArrowUp'){e.preventDefault();selectFaculty(selected-1);}else if(e.key==='+'||e.key==='='){e.preventDefault();zoom=Math.min(1.8,zoom+.1);draw();applyDynamicLanguage();}else if(e.key==='-'){e.preventDefault();zoom=Math.max(.65,zoom-.1);draw();applyDynamicLanguage();}});
  function makeEvidenceField(label, value) {
    const row = document.createElement('div'); row.className = 'evidence-field';
    const key = document.createElement('span'); key.className = 'evidence-field-label'; key.textContent = label;
    const text = document.createElement('p'); text.className = 'evidence-field-value'; text.textContent = value;
    row.append(key, text); return row;
  }
  function makeEvidenceLink(label, url) {
    if (!url) return null;
    const anchor = document.createElement('a'); anchor.className = 'evidence-source-link';
    anchor.href = url; anchor.target = '_blank'; anchor.rel = 'noopener noreferrer'; anchor.textContent = label;
    return anchor;
  }
  function basisLabel(basis, bn = (lang === 'bn')) {
    if (basis === 'Evidence Based') return bn ? 'প্রত্যক্ষ প্রমাণভিত্তিক' : 'Evidence-based';
    if (basis === 'Reasoning Based') return bn ? 'যুক্তিনির্ভর অনুমান' : 'Reasoning-based estimate';
    return basis || (bn ? 'সতর্ক অনুমান' : 'Cautious estimate');
  }
  const passportBenchmarkNamesBn = {
    'Perception':'Perception Test', 'Generation':'GDPval', 'Attention':'RIAC',
    'Learning':'ARC-AGI-3', 'Memory':'LoCoMo', 'Reasoning':'GPQA Diamond',
    'Metacognition':'MetaBound', 'Executive functions':'GAIA / HAL',
    'Problem solving':'SimpleBench', 'Social cognition':'Social IQa / CogToM'
  };
  const passportEvidenceBn = {
    'Perception': {status:'বেঞ্চমার্ক শনাক্ত; নির্দিষ্ট এআই রান যাচাই বাকি',method:'Perception Test অডিও, ভিডিও ও লেখা মিলিয়ে দৃশ্য বোঝার কাজ মাপে।',limit:'দুই স্কোরের পরীক্ষার সংস্করণ, বিভাজন, পরিমাপ ও সেটআপ মিলেছে কি না যাচাই প্রয়োজন।'},
    'Generation': {status:'প্রতিষ্ঠানের জানানো ফল; মানব-মানটি বিশেষজ্ঞ-সমতার রেফারেন্স',method:'GDPval পেশাজীবীদের কাজের ফলের সঙ্গে মডেলের আউটপুট তুলনা করে।',limit:'৫০.০ গড় মানুষের স্কোর নয়; ৮৪.৯-ও সৃজনশীলতার সার্বজনীন মাপ নয়।'},
    'Attention': {status:'মানব-তুলনাটি অ্যাটলাসের অনুমান',method:'RIAC-এ ইচ্ছাকৃত বিভ্রান্তিকর সংকেতসহ মনোযোগের কাজ পরীক্ষা করা হয়।',limit:'৯৫.০ মানব-মানটি একই পরীক্ষায় মাপা জনসংখ্যাগত ফল নয়; ব্যবধানটি অস্থায়ী।'},
    'Learning': {status:'কাস্টম সেটআপ-সংবেদনশীল; সমমানের মানব-তুলনা অনিষ্পন্ন',method:'ARC-AGI-3 একটি ইন্টার‌্যাকটিভ এজেন্ট বেঞ্চমার্ক; ফল নির্দিষ্ট পরীক্ষার সেটআপের ওপর নির্ভর করে।',limit:'পরীক্ষার সেটআপ, চিন্তার সময়, খরচ ও সংস্করণ না মিলিয়ে ১০০ বনাম ৯৯.৯-কে সমতা বলা যাবে না।'},
    'Memory': {status:'নির্দিষ্ট কাজভিত্তিক; মানব-তুলনার উৎস যাচাই প্রয়োজন',method:'LoCoMo দীর্ঘ কথোপকথনের স্মৃতি-সম্পর্কিত প্রশ্ন মাপে; এআই মডেলের সঙ্গে অতিরিক্ত স্মৃতি-ব্যবস্থা যুক্ত।',limit:'মানব-নমুনা ও স্কোরিং-পদ্ধতির উৎস ছাড়া এটি সহায়তাহীন মানুষের সঙ্গে সরাসরি তুলনা নয়।'},
    'Reasoning': {status:'নির্দিষ্ট বেঞ্চমার্কভিত্তিক; মানব-তুলনার পদ্ধতি যাচাই প্রয়োজন',method:'GPQA Diamond জীববিজ্ঞান, পদার্থবিদ্যা ও রসায়নের কঠিন প্রশ্ন ব্যবহার করে।',limit:'মানব-রেফারেন্সের উৎস যাচাই প্রয়োজন; ফলটি দৈনন্দিন বিচার বা সব ধরনের যুক্তির মাপ নয়।'},
    'Metacognition': {status:'মানব-তুলনা অনুমানভিত্তিক; মূল উৎস যাচাই প্রয়োজন',method:'MetaBound ভুল পূর্বধারণা ও উদ্ভাবিত নামের মতো উদাহরণ দিয়ে নির্দিষ্ট আত্ম-পর্যবেক্ষণ পরীক্ষা করে।',limit:'একটি পরীক্ষায় সর্বোচ্চ ফল সাধারণ আত্মজ্ঞান বা আত্মবিশ্বাসের যথার্থতা প্রমাণ করে না।'},
    'Executive functions': {status:'সক্ষমতা ও পরীক্ষার মিল সীমিত',method:'GAIA বহু-ধাপের বাস্তব সহকারী-কাজ, ব্রাউজিং ও সরঞ্জাম ব্যবহারের মূল্যায়ন করে।',limit:'GAIA নির্বাহী-কার্যের স্বতন্ত্র স্কেল নয়; এ-সম্পর্কটি ব্যাখ্যামূলক।'},
    'Problem solving': {status:'মানব-নমুনা ছোট',method:'SimpleBench-এ মানব-তুলনার নমুনা মাত্র নয়জন অ-বিশেষজ্ঞের।',limit:'ছোট নমুনা ও যৌগিক সক্ষমতার কারণে এই মান সাধারণ মানব-ক্ষমতার নির্ভরযোগ্য প্রতিনিধিত্ব নয়।'},
    'Social cognition': {status:'দুই পক্ষের ফল আলাদা পরীক্ষা থেকে এসেছে',method:'মানব-তুলনা Social IQa থেকে, আর এআই-ফল CogToM থেকে নেওয়া।',limit:'একই প্রশ্ন ও স্কোরিং-পদ্ধতি ছাড়া সংখ্যাগুলোকে সরাসরি মানব-এআই ব্যবধান বলা যায় না।'}
  };
  const referenceCaveats = {
    'Perception': {
      en:'Human reference: untrained adults on the Perception Test. The displayed Gemini 2.5 Pro result still needs exact-run, split, metric and setup matching; treat the gap as provisional.',
      bn:'মানব-তথ্যসূত্র: Perception Test-এ প্রশিক্ষণ না-দেওয়া প্রাপ্তবয়স্কদের ফল। প্রদর্শিত Gemini 2.5 Pro ফলের নির্দিষ্ট রান, পরীক্ষা-বিভাজন, পরিমাপ ও সেটআপ এখনো মিলিয়ে দেখা প্রয়োজন; তাই ব্যবধানটি অস্থায়ী।'
    },
    'Generation': {
      en:'GDPval’s 50.0 is expert-versus-expert parity by design, not the average person’s score. The 84.9 GPT-5.5 figure is described as vendor-reported wins or ties, not a universal measure of creativity.',
      bn:'GDPval-এ ৫০.০ হলো বিশেষজ্ঞ বনাম বিশেষজ্ঞ সমতার রেফারেন্স, গড় মানুষের স্কোর নয়। GPT-5.5-এর ৮৪.৯ হলো প্রতিষ্ঠানের জানানো জয় বা সমতার ফল; একে সৃজনশীলতার সার্বজনীন মাপ হিসেবে পড়বেন না।'
    },
    'Attention': {
      en:'The ~95.0 human value is an Atlas estimate, not a matched population result. The RIAC score is task-specific to a planted-lure attention test, so the 44-point difference is not a measured general human–AI gap.',
      bn:'প্রায় ৯৫.০ মানব-মানটি অ্যাটলাসের অনুমান, একই পরীক্ষায় মাপা মানব-নমুনার ফল নয়। RIAC-এর এআই-ফল একটি বিভ্রান্তিকর সংকেতযুক্ত নির্দিষ্ট মনোযোগ-পরীক্ষার; ৪৪ পয়েন্টের ব্যবধানকে সাধারণ মানব-এআই পার্থক্য হিসেবে ধরা যাবে না.'
    },
    'Learning': {
      en:'The 99.9 GPT-6 Astra result on ARC-AGI-3 uses a custom Provider Adapter harness. The 100.0 human reference has not been shown to use an equivalent procedure; near-equal numbers do not establish equal general learning ability.',
      bn:'ARC-AGI-3-এ GPT-6 Astra-এর ৯৯.৯ ফলটি কাস্টম Provider Adapter সেটআপে পাওয়া। ১০০.০ মানব-রেফারেন্স সমমানের পদ্ধতিতে মাপা হয়েছে কি না যাচাই হয়নি; কাছাকাছি সংখ্যা সাধারণ শেখার ক্ষমতার সমতা প্রমাণ করে না।'
    },
    'Memory': {
      en:'LoCoMo measures long-conversation memory questions. The Claude Sonnet result includes an added memory system; the sample and scoring provenance for the 87.9 human reference still need verification.',
      bn:'LoCoMo দীর্ঘ কথোপকথন থেকে তথ্য মনে রাখার প্রশ্ন মাপে। Claude Sonnet-এর ফলে অতিরিক্ত স্মৃতি-ব্যবস্থা আছে; ৮৭.৯ মানব-রেফারেন্সের নমুনা ও স্কোরিং-পদ্ধতির উৎস এখনো যাচাই প্রয়োজন।'
    },
    'Reasoning': {
      en:'GPQA Diamond tests graduate-level biology, physics and chemistry questions. The source and method for the 69.7 human reference need verification; 96.4 is not a universal reasoning or everyday-judgement score.',
      bn:'GPQA Diamond জীববিজ্ঞান, পদার্থবিদ্যা ও রসায়নের স্নাতকোত্তর পর্যায়ের প্রশ্ন পরীক্ষা করে। ৬৯.৭ মানব-রেফারেন্সের উৎস ও পদ্ধতি যাচাই প্রয়োজন; ৯৬.৪ সর্বজনীন যুক্তি বা দৈনন্দিন বিচারের স্কোর নয়।'
    },
    'Metacognition': {
      en:'The 45.0 human value is an estimate, while 100.0 is the best reported MetaBound model result in this snapshot. A perfect score on this task does not prove general self-knowledge or reliable confidence calibration.',
      bn:'৪৫.০ মানব-মানটি অনুমানভিত্তিক, আর ১০০.০ এই স্ন্যাপশটে MetaBound-এর সর্বোচ্চ প্রকাশিত মডেল-ফল। একটি পরীক্ষায় পূর্ণ স্কোর সাধারণ আত্মজ্ঞান বা আত্মবিশ্বাসের নির্ভরযোগ্য যথার্থতা প্রমাণ করে না।'
    },
    'Executive functions': {
      en:'GAIA covers multi-step real-world assistant tasks and tool use; it is not a validated, isolated executive-function test. Treat this as an interpretive mapping until a matched construct-specific human baseline is available.',
      bn:'GAIA-তে বহু-ধাপের বাস্তব সহকারী-কাজ ও সরঞ্জাম ব্যবহার থাকে; এটি নির্বাহী-কার্যের স্বতন্ত্রভাবে যাচাইকৃত পরীক্ষা নয়। একই সক্ষমতা ও পদ্ধতিতে মাপা মানব-তুলনা না পাওয়া পর্যন্ত এটিকে ব্যাখ্যামূলক সংযোগ হিসেবে দেখুন।'
    },
    'Problem solving': {
      en:'The SimpleBench human reference uses only nine non-specialists. The small sample and composite faculty mean 83.7 versus 81.9 should not be read as a robust general human–AI comparison.',
      bn:'SimpleBench-এর মানব-রেফারেন্স মাত্র নয়জন অ-বিশেষজ্ঞের নমুনা থেকে এসেছে। ছোট নমুনা ও যৌগিক সক্ষমতার কারণে ৮৩.৭ বনাম ৮১.৯-কে নির্ভরযোগ্য সাধারণ মানব-এআই তুলনা হিসেবে পড়া উচিত নয়.'
    },
    'Social cognition': {
      en:'The 84.4 human reference comes from Social IQa and the 80.0 AI result from CogToM. Because the tests differ, this is not a direct 4.4-point head-to-head comparison.',
      bn:'৮৪.৪ মানব-রেফারেন্স Social IQa থেকে, আর ৮০.০ এআই-ফল CogToM থেকে এসেছে। পরীক্ষা দুটি আলাদা হওয়ায় এটিকে সরাসরি ৪.৪ পয়েন্টের মুখোমুখি তুলনা হিসেবে ব্যাখ্যা করা যাবে না।'
    }
  };
  const humanRefBn = {
    'Perception':'Perception Test · প্রশিক্ষণ না-দেওয়া প্রাপ্তবয়স্কদের ফল','Generation':'GDPval · বিশেষজ্ঞ বনাম বিশেষজ্ঞ সমতা-রেফারেন্স','Attention':'অনুমানভিত্তিক মানব-তুলনা · সময়সীমাহীন পাঠ-কাজ','Learning':'ARC-AGI-3 · সাধারণ অংশগ্রহণকারীদের ফল','Memory':'LoCoMo · মানব-তুলনার উৎস যাচাই প্রয়োজন','Reasoning':'GPQA Diamond · পিএইচডি পর্যায়ের বিশেষজ্ঞ-রেফারেন্স','Metacognition':'অনুমানভিত্তিক মানব-তুলনা · ভুল পূর্বধারণা ও উদ্ভাবিত নাম','Executive functions':'GAIA · বিশ্ববিদ্যালয়-শিক্ষিত পরীক্ষার্থী','Problem solving':'SimpleBench · নয়জন অ-বিশেষজ্ঞের নমুনা','Social cognition':'Social IQa · মানব-ফল'
  };
  const aiRefBn = {
    'Perception':'Perception Test · Gemini 2.5 Pro-এর ফল','Generation':'GDPval · GPT-5.5-এর জয় বা সমতার ফল','Attention':'RIAC · বিভ্রান্তিকর সংকেতসহ মনোযোগ-পরীক্ষা','Learning':'ARC-AGI-3 · কাস্টম Provider Adapter সেটআপসহ GPT-6 Astra','Memory':'LoCoMo · অতিরিক্ত স্মৃতি-ব্যবস্থাসহ Claude Sonnet','Reasoning':'GPQA Diamond · Gemini 4 Argon-এর প্রকাশিত ফল','Metacognition':'MetaBound · সর্বোচ্চ প্রকাশিত মডেল-ফল','Executive functions':'HAL · Claude Sonnet 4.5','Problem solving':'SimpleBench · Claude Fable 5','Social cognition':'CogToM · GPT-5.1'
  };
  const humanRefEn = {
    'Perception':'Perception Test · untrained adult participants',
    'Generation':'GDPval · expert-versus-expert parity reference',
    'Attention':'Estimated human reference · untimed reading task',
    'Learning':'ARC-AGI-3 · public participants',
    'Memory':'LoCoMo · human-reference provenance needs verification',
    'Reasoning':'GPQA Diamond · PhD-expert reference',
    'Metacognition':'Estimated human reference · false premises and invented names',
    'Executive functions':'GAIA · university-educated testers',
    'Problem solving':'SimpleBench · nine non-specialist participants',
    'Social cognition':'Social IQa · human result'
  };
  function refreshEvidencePassport() {
    if (!evidencePassport || !evidencePassportContent) return;
    const d = data[selected];
    const bn = lang === 'bn';
    evidencePassportSummary.textContent = bn ? 'প্রমাণের পরিচয়' : 'Evidence passport';
    evidencePassportContent.replaceChildren();
    const addBullet = value => {
      const li = document.createElement('li');
      li.textContent = value;
      evidencePassportContent.appendChild(li);
    };
    if (isAnimalComparator()) {
      const profile = comparativeProfiles[comparator];
      const rating = animalFinding(comparator, selected);
      const metaName = bn ? (rating?.bn || profile?.groupBn || 'নির্বাচিত প্রাণীর গবেষণা') : (rating?.en || profile?.groupEn || 'Selected animal research');
      addBullet(bn
        ? `ধরন: ${displayName(d.name)}-এর ${rating ? toBanglaNumber(rating.score) : '—'} / ১০০ সক্ষমতা-অনুমান।`
        : `Type: ${displayName(d.name)} faculty estimate, ${rating ? rating.score : '—'} / 100.`);
      addBullet(bn ? `ভিত্তি: ${basisLabel(rating?.basis, true)}।` : `Basis: ${basisLabel(rating?.basis, false)}.`);
      addBullet(bn
        ? `গবেষণার প্রেক্ষাপট: ${String(metaName).replace(/\bAtlas\b/g,'অ্যাটলাস')}`
        : `Study context: ${String(metaName)}`);
      addBullet(bn ? `সীমা: এটি প্রজাতির সব সদস্যের সরাসরি মাপা স্কোর নয়।` : `Limit: this is not a directly measured species-wide score.`);
    } else {
      const meta = evidenceLedger[d.name] || {};
      const bnMeta = passportEvidenceBn[d.name] || {};
      addBullet(bn
        ? `পরীক্ষা: ${passportBenchmarkNamesBn[d.name] || 'নির্দিষ্ট পরীক্ষা'}।`
        : `Benchmark: ${meta.sourceName || d.source}`);
      addBullet(bn
        ? `যাচাই: ${bnMeta.status || 'উৎস যাচাই প্রয়োজন'}।`
        : `Review status: ${meta.status || 'Source check required'}.`);
      addBullet(bn
        ? `পরীক্ষার ধরন: ${bnMeta.method || 'মূল পদ্ধতি যাচাই প্রয়োজন'}`
        : `Method: ${meta.method || 'Review the primary method before citing the score.'}`);
      addBullet(bn
        ? `তুলনার সীমা: ${bnMeta.limit || 'সরাসরি তুলনার আগে পদ্ধতি যাচাই করুন।'}`
        : `Comparability: ${meta.comparability || comparisonNotes[d.name] || 'Check methods before comparing.'}`);
      if (years > 0 && comparator === 'ai') addBullet(bn
        ? `দৃশ্যপট: বছরে +${toBanglaNumber(rate)} স্কোর-পয়েন্ট, ${toBanglaNumber(years)} বছর; এটি পূর্বাভাস নয়।`
        : `Scenario: +${rate} score points/year for ${years} years; not a forecast.`);
    }
    if (atlasActionRow) {
      $('#atlasDownloadCard').textContent = bn ? 'নিজের জন্য কপি সংরক্ষণ করুন' : 'Save a copy for you';
      $('#atlasEvidencePassport').textContent = bn ? 'প্রমাণের বিবরণ দেখুন' : 'See evidence passport';
      $('#atlasEvidencePassport').setAttribute('aria-label', bn ? 'প্রমাণের বিবরণ দেখুন' : 'See evidence passport');
    }
    updateScenarioStamp();
  }
  function updateScenarioStamp() {
    if (!scenarioStamp) return;
    scenarioStamp.classList.remove('is-scenario','is-estimate');
    // Reset the previous state before evaluating the newly selected faculty/comparator.
    scenarioStamp.hidden = false;
    scenarioStamp.style.display = '';
    scenarioStamp.removeAttribute('aria-hidden');

    if (isAnimalComparator()) {
      const rating = animalFinding(comparator, selected);
      // The species-wide caution badge is reserved for reasoning-based faculty estimates.
      // Evidence Based means the primary study directly addresses the faculty, so keep the
      // visual field clean rather than showing the generic estimate warning badge.
      if (!rating || rating.basis !== 'Reasoning Based') {
        scenarioStamp.textContent = '';
        scenarioStamp.hidden = true;
        scenarioStamp.style.display = 'none';
        scenarioStamp.setAttribute('aria-hidden', 'true');
        return;
      }
      scenarioStamp.classList.add('is-estimate');
      scenarioStamp.textContent = lang === 'bn'
        ? 'অ্যাটলাসের অনুমান · প্রজাতির জন্য প্রকাশিত ০–১০০ স্কোর নয়'
        : 'ATLAS ESTIMATE · NOT A PUBLISHED SPECIES-WIDE 0–100 SCORE';
    } else if (years > 0) {
      scenarioStamp.classList.add('is-scenario');
      scenarioStamp.textContent = lang === 'bn'
        ? `দৃশ্যপট · বছরে +${toBanglaNumber(rate)} স্কোর-পয়েন্ট · পর্যবেক্ষিত ফল নয়, পূর্বাভাসও নয়`
        : `SCENARIO · +${rate} SCORE POINTS/YEAR · NOT OBSERVED DATA OR A FORECAST`;
    } else {
      scenarioStamp.textContent = lang === 'bn'
        ? 'প্রকাশিত / সংকলিত স্ন্যাপশট · লাইভ ফিড নয় · ভবিষ্যৎ অনুমান বন্ধ'
        : 'REPORTED / COMPILED SNAPSHOT · NOT LIVE · NO FUTURE UPLIFT APPLIED';
    }
  }
  function showAtlasStatus(message) {
    if (atlasActionStatus) atlasActionStatus.textContent = message;
  }
  function drawResultCard() {
    // Export the single-page landscape PDF in the supplied reference layout, with localized and distinct fact paragraphs.
    createAtlasEvidencePDF().catch(error => {
      console.error('Atlas PDF export failed:', error);
      showAtlasStatus(lang === 'bn' ? 'এই ব্রাউজারে পিডিএফ তৈরি করা যায়নি।' : 'This browser could not create the PDF.');
    });
  }
  async function createAtlasEvidencePDF() {
    const d = data[selected];
    const bn = lang === 'bn';
    const locale = bn ? 'bn' : 'en';
    const animal = isAnimalComparator();
    const rating = animal ? animalFinding(comparator, selected) : null;
    const aiScore = years > 0 ? futureAI(d) : d.ai;
    const otherScore = animal ? (rating && Number.isFinite(Number(rating.score)) ? Number(rating.score) : null) : Number(aiScore);
    const accent = facultyColors[selected] || facultyColors[0] || '#E30613';
    const facultyDeep = atlasPdfDarken(accent, 0.24);
    const facultyLight = atlasPdfMix(accent, '#FFFFFF', 0.84);
    const humanAccent = '#3F78F6';
    const humanLight = '#DDEEFF';
    const humanName = bn ? 'মানুষ' : 'Human';
    const otherName = animal ? animalLabel(comparator) : (bn ? 'এআই' : 'AI');
    const facultyName = displayName(d.name);
    const facultyMeaning = bn ? (descriptionsBn[d.name] || d.desc) : d.desc;
    const snapshotDate = new Date();
    const dateEn = new Intl.DateTimeFormat('en-GB', {day:'2-digit', month:'short', year:'numeric', timeZone:'Asia/Dhaka'}).format(snapshotDate);
    const scenarioSuffixEn = years > 0 && !animal ? ` · Scenario +${rate}/year` : '';
    const headerOtherName = animal ? (comparativeProfiles[comparator]?.labelEn || comparator) : 'AI';
    const matchup = `Human vs ${headerOtherName}${scenarioSuffixEn} - ${dateEn}`;

    const W = 1714, H = 898, scale = 2;
    const canvas = document.createElement('canvas');
    canvas.width = W * scale; canvas.height = H * scale;
    const g = canvas.getContext('2d');
    if (!g) throw new Error('Canvas context is unavailable');
    g.scale(scale, scale);
    await Promise.race([document.fonts.ready, new Promise(resolve => setTimeout(resolve, 650))]);
    const fontLoads = [
      document.fonts.load('500 48px Georgia'),
      document.fonts.load('700 22px Manrope'),
      document.fonts.load('400 18px Manrope'),
      document.fonts.load('700 76px Manrope'),
      document.fonts.load('500 18px "Noto Sans Bengali"')
    ];
    await Promise.race([Promise.allSettled(fontLoads), new Promise(resolve => setTimeout(resolve, 850))]);

    // Wide one-page composition matched to the supplied reference image.
    g.fillStyle = '#FFFFFF'; g.fillRect(0, 0, W, H);
    g.textBaseline = 'alphabetic';
    g.fillStyle = accent; g.fillRect(92, 44, 4, 88);
    const title = 'COGNITIVE COMPARISON ATLAS';
    g.textAlign = 'left'; g.fillStyle = '#151515';
    const titleFont = '500 49px Georgia, "Times New Roman", serif';
    g.font = titleFont;
    // Canvas letter spacing is supported by current Chromium; preserve a graceful fallback.
    try { g.letterSpacing = bn ? '0px' : '0.5px'; } catch (_) {}
    g.fillText(title, 104, 92);
    try { g.letterSpacing = '0px'; } catch (_) {}
    g.fillStyle = '#545454'; g.font = '700 19px "Manrope", "Noto Sans Bengali", sans-serif';
    g.fillText(matchup, 105, 120, 1085);

    // Compact brand lock-up redrawn to match the globe + CC + spaced ATLAS mark in the reference.
    const logoLeft = W - 410;
    const globeCx = logoLeft + 20, globeCy = 83, globeR = 17;
    g.save();
    g.fillStyle = '#2E8CF0'; g.beginPath(); g.arc(globeCx, globeCy, globeR, 0, Math.PI * 2); g.fill();
    g.save(); g.beginPath(); g.arc(globeCx, globeCy, globeR - 0.5, 0, Math.PI * 2); g.clip();
    g.fillStyle = '#9ADFFF';
    g.beginPath(); g.moveTo(globeCx-12,globeCy-12); g.lineTo(globeCx-4,globeCy-14); g.lineTo(globeCx,globeCy-8); g.lineTo(globeCx-3,globeCy-3); g.lineTo(globeCx-10,globeCy-4); g.closePath(); g.fill();
    g.beginPath(); g.moveTo(globeCx+1,globeCy-14); g.lineTo(globeCx+12,globeCy-9); g.lineTo(globeCx+8,globeCy-3); g.lineTo(globeCx+13,globeCy+2); g.lineTo(globeCx+7,globeCy+11); g.lineTo(globeCx+1,globeCy+7); g.lineTo(globeCx+3,globeCy+1); g.lineTo(globeCx-1,globeCy-4); g.closePath(); g.fill();
    g.strokeStyle = 'rgba(255,255,255,.5)'; g.lineWidth = 0.8;
    g.beginPath(); g.ellipse(globeCx,globeCy,8,17,0,0,Math.PI*2); g.stroke();
    g.beginPath(); g.ellipse(globeCx,globeCy,17,6,0,0,Math.PI*2); g.stroke();
    g.restore();
    g.strokeStyle = '#78BDF4'; g.lineWidth = 1;
    g.beginPath(); g.ellipse(globeCx,globeCy+22,23,4,-0.07,0,Math.PI*2); g.stroke();
    g.fillStyle = '#3978F7'; g.font = '700 39px "Manrope", Arial, sans-serif'; g.textAlign = 'left';
    g.fillText('CC', logoLeft + 48, 96);
    g.fillStyle = '#7E9ABF'; g.font = '500 5.5px "Manrope", Arial, sans-serif';
    g.fillText('COGNITIVE', logoLeft + 49, 104); g.fillText('COMPARISON', logoLeft + 49, 110);
    g.fillStyle = '#151515'; g.font = '300 43px "Manrope", Arial, sans-serif';
    try { g.letterSpacing = '8px'; } catch (_) {}
    g.fillText('ATLAS', logoLeft + 128, 104, 204);
    try { g.letterSpacing = '0px'; } catch (_) {}
    g.restore();
    g.strokeStyle = '#D9DDE1'; g.lineWidth = 1.25;
    g.beginPath(); g.moveTo(142, 143); g.lineTo(W - 139, 143); g.stroke();

    // Faculty ribbon: the selected faculty is centered and emphasized, with its neighbours muted.
    const ribbonOrder = ['Reasoning','Executive functions','Perception','Attention','Metacognition','Social cognition','Generation','Learning','Memory','Problem solving'];
    const selectedRibbonIndex = Math.max(0, ribbonOrder.indexOf(d.name));
    const ribbonItems = [-2,-1,0,1,2,3].map(offset => ribbonOrder[(selectedRibbonIndex + offset + ribbonOrder.length) % ribbonOrder.length]);
    const positions = [118, 424, W/2, 1188, 1435, 1654];
    const maxWidths = [210, 352, 550, 204, 274, 180];
    ribbonItems.forEach((item, idx) => {
      const isCurrent = idx === 2;
      let text = item === 'Executive functions' && !bn ? 'Executive Function' : (bn ? (facultyBn[item] || item) : item);
      let size = isCurrent ? (bn ? 71 : 82) : (bn ? 29 : 36);
      const fontFamily = bn ? '"Manrope", "Noto Sans Bengali", sans-serif' : '"Manrope", Arial, sans-serif';
      g.font = `${isCurrent ? 500 : 400} ${size}px ${fontFamily}`;
      while (size > (isCurrent ? 42 : 18) && g.measureText(text).width > maxWidths[idx]) {
        size -= 1; g.font = `${isCurrent ? 500 : 400} ${size}px ${fontFamily}`;
      }
      g.textAlign = 'center';
      g.fillStyle = isCurrent ? facultyDeep : '#B7B7B7';
      g.fillText(text, positions[idx], 231, maxWidths[idx]);
    });
    g.textAlign = 'center'; g.fillStyle = atlasPdfMix(accent, '#FFFFFF', 0.38);
    g.font = '400 19px "Manrope", "Noto Sans Bengali", sans-serif';
    const meaningText = facultyMeaning;
    atlasPdfDrawWrapped(g, meaningText, 155, 287, W - 310, 23, '400 19px "Manrope", "Noto Sans Bengali", sans-serif', atlasPdfMix(accent, '#FFFFFF', 0.38), 'center', 1);

    // This is the single badge retained in the reference layout, with localized copy.
    const badgeText = bn ? 'তুলনামূলক দৃশ্যগত সিমুলেশনে নির্মিত' : 'Made by Comparative Visual Simulation';
    g.font = '600 13px "Manrope", "Noto Sans Bengali", sans-serif';
    const badgeW = g.measureText(badgeText).width + 32, badgeH = 31, badgeX = (W - badgeW)/2, badgeY = 325;
    g.fillStyle = '#FAFBFC'; g.strokeStyle = '#DEE3E8'; g.lineWidth = 1.2;
    atlasPdfRoundRect(g, badgeX, badgeY, badgeW, badgeH, 16); g.fill(); g.stroke();
    g.fillStyle = '#5E6268'; g.textAlign = 'center'; g.fillText(badgeText, W/2, badgeY + 20);

    const cardY = 409, cardW = 492, cardH = 257, cardX1 = 298, cardX2 = 941;
    const cardFacts = {"en":{"humanCard":{"Perception":"Your brain combines what the eyes detect with context to build a scene. That is why one ambiguous picture can look different to different people.","Generation":"Creativity often links familiar ideas in a new way. A fresh relationship between known ingredients can make an idea feel original.","Attention":"People can miss a visible event when their attention is tightly occupied elsewhere. What attention is set to notice can shape what reaches awareness.","Learning":"Practice can make an effortful action feel almost automatic. Spaced practice often helps information last longer than packing all the learning into one sitting.","Memory":"Remembering is reconstructive rather than a perfect replay of a recording. The cues and context present during recall can change which details come back.","Reasoning":"A hard puzzle can become simple once its hidden rule is spotted. Sometimes the breakthrough is a better representation of the problem, not faster calculation.","Metacognition":"People can sense uncertainty before they can fully explain its source. Metacognition asks whether confidence tracks the chance of being right.","Executive functions":"Executive functions help you hold a goal while resisting distractions. Planning, switching tasks, and stopping an automatic response use this control system.","Problem solving":"When people get stuck, changing how a problem is represented can unlock a solution. Insight can be a shift in viewpoint, not a sudden gift of extra information.","Social cognition":"We read more than words: gaze, timing, facial movement, and context all add meaning. The same gesture can mean different things in different settings."},"aiCard":{"Perception":"Vision-language models connect image details with words, so they can answer questions about pictures. Some can also analyse sequences of video frames.","Generation":"Generative models create text, images, or audio from learned patterns and prompts. Small prompt changes can reshape the style and structure.","Attention":"Transformers use attention weights so each token can draw information from others. This mechanism is central to how many language models process context.","Learning":"An AI model can sometimes learn a pattern from examples in its prompt without changing its trained weights. This is known as in-context learning.","Memory":"AI can draw on a current chat, saved notes, or a retrieval system. These components can help it bring information back across sessions.","Reasoning":"A language model may split a problem into steps and use tools or calculations. The problem’s structure often shapes which approach works best.","Metacognition":"AI can express uncertainty, compare answers, or critique a first draft. Researchers can test how well its confidence matches its accuracy.","Executive functions":"AI agents can combine planning, browser or code tools, and checks into a workflow. These actions can link separate steps into one task.","Problem solving":"Some AI systems propose a solution, test it, then revise using feedback. This loop helps when a first answer needs improvement.","Social cognition":"Language models can reason about beliefs and intentions described in stories. These tests explore how they interpret social situations through language."},"animalCard":{"chimpanzee":{"Perception":"Chimpanzees can learn visual patterns in touchscreen tasks. Researchers use these tasks to study how they recognise and remember visual information.","Generation":"Wild chimpanzee communities have different tool-use traditions. Young chimpanzees can learn local techniques by watching experienced group members.","Attention":"Chimpanzees monitor food, nearby individuals, and changing social cues in their group. Gaze and choice tasks let researchers study which signals capture their attention.","Learning":"Some chimpanzee communities use distinct ways of cracking nuts or fishing for termites. These traditions can pass between generations through social learning.","Memory":"Some chimpanzees recall where numerals appeared after a brief look at a screen. This striking visual-memory skill is studied in primate research.","Reasoning":"Chimpanzees select sticks and other tools to reach food in challenging settings. The choice can depend on matching a tool’s properties to the task.","Metacognition":"Some chimpanzees seek extra information before choosing when a reward is hidden. Researchers use this choice to study responses to uncertainty.","Executive functions":"Chimpanzees may choose a tool, carry it to a target, and change tactics after failure. Such sequences help researchers study planning and self-control.","Problem solving":"Some wild chimpanzees crack hard nuts with stone hammers and anvils. Choosing and positioning the pieces turns a food search into a multi-part physical problem.","Social cognition":"Chimpanzees groom partners, form alliances, and track changing relationships. Their social lives offer a window into cooperation and competition."},"dog":{"Perception":"Dogs build a rich picture of the world through smell, not just sight and sound. Odours help them detect, distinguish, and track people, animals, and objects.","Generation":"Dogs use play bows and other body signals to invite interaction. These flexible signals help shape the next move during social play.","Attention":"Dogs can follow human pointing gestures to find hidden food. The gesture acts as a clue about a place they cannot directly see.","Learning":"Dogs have shown that they can generalise some pointing cues to unfamiliar forms. The learned meaning can sometimes transfer beyond one exact gesture.","Memory":"Dogs can learn associations among odours, places, and outcomes. Their scent-rich world gives memory a different set of clues from the visual cues humans often rely on.","Reasoning":"A dog can use a human gesture to choose which location to search for food. Researchers change the cue to test whether the learned relation transfers to a new case.","Metacognition":"Researchers test whether dogs seek information before choosing when a target is hidden. These choices make uncertainty observable through behaviour.","Executive functions":"Waiting for a cue or delaying access to a reward lets researchers study impulse control in dogs. The behavior must be guided by an outcome that comes later.","Problem solving":"Dogs can search around barriers and use cues to locate hidden objects. Their approach can vary with experience, motivation, and how the problem is presented.","Social cognition":"Dogs often follow human pointing to find hidden objects. This response helps researchers study how animals read human communication."},"honeybee":{"Perception":"Honeybees can see ultraviolet wavelengths that humans cannot see. Some flower patterns therefore look different to bees and help guide them while foraging.","Generation":"A honeybee’s waggle dance is a movement sequence that carries information about a food source. The dance turns a location into a message other bees can use.","Attention":"Honeybees learn which colours or patterns predict a reward and choose among competing cues. Their small brains still support measurable selective attention.","Learning":"Honeybees can learn visual relationships such as same-versus-different and above-versus-below. These tasks go beyond memorising one picture.","Memory":"Honeybees remember landmarks along a route and use visual cues to navigate home. They can combine landmarks with the sun’s position.","Reasoning":"In experiments, honeybees learned to add or subtract one item when colour signalled the rule. It is a striking numerical skill in a tiny brain.","Metacognition":"Honeybees can apply learned visual relationships to new displays. Researchers use this transfer to study flexible learning in a very small brain.","Executive functions":"A foraging bee coordinates searching, navigation, and returning to the hive. Its route reflects several behaviours working together in a compact nervous system.","Problem solving":"Honeybees can apply visual rules to unfamiliar arrangements of shapes. This shows a learned rule used beyond the original training picture.","Social cognition":"A honeybee’s waggle dance tells nestmates the direction and distance of food. The dance turns a discovery into movements other bees can read."}},"humanExtra":{"Perception":"Each eye has a blind spot, yet your brain fills the gap so you rarely notice it. The blind spot sits where the optic nerve exits the retina.","Generation":"A useful constraint can sometimes boost creativity by giving the mind a boundary to work against. A smaller search space can make a new connection easier to find.","Attention":"Inattentional blindness shows that an obvious object can go unnoticed when attention is occupied by another task. A famous demonstration had viewers miss a gorilla-suited person while counting passes.","Learning":"The spacing effect is one reason short revisits over several days can outperform one long study session. A short self-test reveals what you can retrieve, not merely what feels familiar.","Memory":"Sleep helps stabilise some memories, so the brain continues processing experiences after a study session ends. A vivid memory can still omit or rearrange small details.","Reasoning":"A small change in how a puzzle is worded can change which rule a person considers first. Spotting which detail matters is often half the solution.","Metacognition":"A confidence judgment is most informative when it predicts which answers will survive checking. It is measured across many answers, not by one impressive response.","Executive functions":"Working memory acts like a small mental workbench for temporarily holding and manipulating information. Task-switching can cost time when goals compete.","Problem solving":"Changing the representation of a problem can turn a seemingly impossible task into an approachable one. A sketch can reveal a relationship hidden in a paragraph.","Social cognition":"People learn by watching others, and social learning helps useful habits spread through a community. People often mirror expressions without consciously deciding to."},"aiExtra":{"Perception":"AI perception can connect pixels with language, producing a scene description rather than only a list of image labels. Different questions can make a model describe different details in the same picture.","Generation":"One prompt can yield many valid outputs because generative AI learns patterns, not one fixed answer. The prompt steers the result, while multiple continuations may remain plausible.","Attention":"In transformer models, “attention” names a mathematical operation, not a conscious feeling of focus. Its weights help connect information across words in the current context.","Learning":"In-context learning lets prompt examples change a model’s answer without retraining its weights. Those examples guide one answer but do not retrain the model.","Memory":"Retrieval-augmented systems can bring external notes into a model’s working context when those notes are relevant. This lets a system refer to material that is not stored in its model weights.","Reasoning":"Extra computation at answer time can let some models explore or verify more than one path to a solution. Extra computation can help, but it does not guarantee correctness.","Metacognition":"Calibration measures whether stated confidence aligns with how often answers turn out to be correct. A model can also review an answer after a second check reveals new evidence.","Executive functions":"An AI agent’s results depend on its control loop and available tools as well as on its core model. One faulty tool result can affect every later step.","Problem solving":"A plan-test-revise loop can turn an initial failed attempt into useful feedback for the next one. Testing against feedback can expose a weak first solution.","Social cognition":"Language-only tests probe social reasoning through words; people also use faces, voices, and context. Reading about emotions is not the same as experiencing them."},"animalExtra":{"chimpanzee":{"Perception":"One famous visual task uses numerals that appear on a screen only briefly, challenging rapid visual memory as well as recognition. The brief display tests how quickly locations are registered and retained.","Generation":"Researchers describe some community-specific tool behaviours as cultural traditions that can persist across generations. A tradition spreads through a group, not just one successful act.","Attention":"Researchers can compare where a chimpanzee looks and what it chooses after a cue changes. A changed cue can reveal which signal influenced the choice.","Learning":"Different wild populations can develop different ways to use tools for similar goals. Social learning lets techniques travel between younger and older chimps.","Memory":"Some of the best-known examples involve immediate recall of briefly presented number locations. Remembering a location is different from simply recognising a numeral.","Reasoning":"A tool’s shape, length, and reach can change which choice successfully solves the task. Tool choice depends on matching shape and reach to the goal.","Metacognition":"Information-seeking decisions let scientists study uncertainty without asking an animal to describe its thoughts. Researchers can compare the choice made before and after the hidden item is revealed.","Executive functions":"Changing tactics after an attempt fails reveals more than simply repeating a practised movement. Flexible tactic changes reveal more than repetition alone.","Problem solving":"Stone-tool nut cracking is one of the classic examples of technical problem solving in wild chimpanzees. The task links tool selection, placement, and controlled force.","Social cognition":"Grooming and alliance patterns can influence who cooperates with whom in a group. Alliances can change who receives support and cooperates with whom."},"dog":{"Perception":"Current research also examines how odours affect dogs’ emotions and social responses. Scent can reveal what passed through a place even when it is out of sight.","Generation":"The play bow is a recognisable signal that marks an action as play. Play signals help other dogs interpret a movement as an invitation.","Attention":"A dog’s response can depend on the kind of pointing gesture and the setting in which it appears. Researchers vary gestures to test what guides a dog’s choice.","Learning":"Generalisation is what makes a learned cue useful beyond the exact training example. That flexibility matters when different people give slightly different signals.","Memory":"Smell can carry information even after the object that produced the odour has moved away. An odour can remain informative after the scene itself has changed.","Reasoning":"Researchers can test transfer by changing the location or form of the cue. Changing the cue tests whether learning transfers to a new case.","Metacognition":"Animal-uncertainty research examines what an animal chooses when it has incomplete information. Researchers can vary the situation to see whether the same information-seeking pattern returns.","Executive functions":"Self-control tasks can compare an immediate reward with waiting for a later outcome. Waiting is especially demanding when the reward is visible.","Problem solving":"A barrier task can reveal whether a dog changes its route when the direct path is blocked. A detour shows whether a dog can adapt to an obstacle.","Social cognition":"Dogs are particularly responsive to several kinds of human communicative gesture. A simple gesture can bridge two species with different sensory worlds."},"honeybee":{"Perception":"Some flowers have ultraviolet patterns that humans cannot see but honeybees can. This gives bees a visual channel humans cannot directly inspect.","Generation":"The angle of a waggle dance relative to vertical communicates a direction relative to the sun. The dance lets a scout share location information without sound.","Attention":"Honeybee visual discrimination can use colour, shapes, and repeated patterns. Small changes in colour or pattern can guide a trained choice.","Learning":"Researchers have reported honeybees learning relations such as same-versus-different and above-versus-below. A learned relation may transfer to arrangements never seen before.","Memory":"A bee can combine remembered landmarks with celestial cues while navigating. Recognised landmarks help turn a route into a repeatable journey.","Reasoning":"In one experiment, a colour told the bee whether to add or subtract one item. Researchers can change the display while keeping the rule constant.","Metacognition":"Transfer to a new display helps researchers distinguish learning a relation from memorising one picture. Such transfer offers a window into flexible learning in a very small nervous system.","Executive functions":"Foraging combines search, navigation, and return decisions within one small nervous system. Search, navigation, and return all need coordination during a trip.","Problem solving":"Applying a learned rule to a new display is a key sign that the bee has carried the pattern beyond one example. These tests ask whether a learned rule can guide choices beyond the original example.","Social cognition":"A waggle dance can recruit nestmates to a food patch that the dancer has visited. It is a striking example of information passed between insects."}}},"bn":{"humanCard":{"Perception":"আপনার মস্তিষ্ক শুধু চোখ থেকে পাওয়া ছবি পড়ে না; প্রেক্ষাপট মিলিয়ে দৃশ্যের অর্থ তৈরি করে। তাই একই অস্পষ্ট ছবিকে দুইজন মানুষ ভিন্নভাবে দেখতে পারেন।","Generation":"সৃজনশীলতা অনেক সময় পরিচিত ধারণাকে নতুনভাবে যুক্ত করার মধ্যে থাকে। উপাদান পরিচিত হলেও তাদের সম্পর্ক বদলালে ফল নতুন মনে হতে পারে।","Attention":"অন্য কাজে মনোযোগ গভীর হলে চোখের সামনে থাকা ঘটনাও মানুষ মিস করতে পারে। মনোযোগ কোথায় ছিল, তা অনেক সময় দেখা আর না-দেখার পার্থক্য গড়ে দেয়।","Learning":"বারবার অনুশীলনে একসময় কঠিন কাজ স্বয়ংক্রিয় মনে হতে পারে। কয়েক দিনে ভাগ করে শেখা প্রায়ই এক বসায় সব গুঁজে নেওয়ার চেয়ে স্মৃতিকে দীর্ঘস্থায়ী করে।","Memory":"স্মৃতি কোনো রেকর্ডিংয়ের নিখুঁত পুনরাবৃত্তি নয়; মনে করার সময় মস্তিষ্ক তথ্য পুনর্গঠন করে। সংকেত ও প্রেক্ষাপট মনে পড়া বিবরণ বদলে দিতে পারে।","Reasoning":"একটি কঠিন ধাঁধা সহজ হয়ে যেতে পারে, যখন তার নিয়মটি ঠিকভাবে বোঝা যায়। কখনও দ্রুত হিসাবের চেয়ে সমস্যাটিকে নতুনভাবে উপস্থাপন করাই বড় অগ্রগতি।","Metacognition":"মানুষ কখনও অনিশ্চয়তা অনুভব করতে পারে, যদিও তার কারণ সঙ্গে সঙ্গে ব্যাখ্যা করতে পারে না। আত্মমূল্যায়ন দেখে, এই আত্মবিশ্বাস সঠিক উত্তরের সম্ভাবনার সঙ্গে মেলে কি না।","Executive functions":"লক্ষ্য মাথায় ধরে রেখে আকর্ষণীয় বিভ্রান্তি সামলাতে মস্তিষ্কের নিয়ন্ত্রণব্যবস্থা সাহায্য করে। পরিকল্পনা, কাজ বদলানো এবং স্বয়ংক্রিয় প্রতিক্রিয়া থামানো এর অংশ।","Problem solving":"সমস্যায় আটকে গেলে সেটিকে নতুনভাবে উপস্থাপন করলে সমাধান বেরিয়ে আসতে পারে। অন্তর্দৃষ্টি অনেক সময় নতুন তথ্য নয়, দেখার দৃষ্টিভঙ্গি বদল।","Social cognition":"মানুষ শুধু কথার শব্দ নয়, সময়, দৃষ্টি, মুখের ভঙ্গি ও ভাগ করা প্রেক্ষাপট থেকেও উদ্দেশ্য বোঝে। একই অঙ্গভঙ্গি ভিন্ন পরিস্থিতিতে ভিন্ন অর্থ দিতে পারে।"},"aiCard":{"Perception":"ভিশন-ল্যাঙ্গুয়েজ মডেল ছবির দৃশ্যমান তথ্যকে ভাষার সঙ্গে যুক্ত করে ছবি নিয়ে প্রশ্নের উত্তর দিতে পারে। কিছু ব্যবস্থা স্থির ছবির পাশাপাশি ভিডিওর ধারাবাহিক ফ্রেমও বিশ্লেষণ করে।","Generation":"জেনারেটিভ মডেল প্রশিক্ষণে শেখা ধরন ও ব্যবহারকারীর নির্দেশ থেকে লেখা, ছবি বা অডিও তৈরি করতে পারে। নির্দেশের সামান্য পরিবর্তনও আউটপুটের ভঙ্গি ও গঠন বদলে দিতে পারে।","Attention":"ট্রান্সফরমার মডেলে attention হিসাব করে কোন টোকেন অন্য টোকেন থেকে কত তথ্য নেবে। নামটি মানব-মনোযোগের কথা মনে করালেও এটি সচেতনভাবে মনোযোগ দেওয়ার সমান নয়।","Learning":"কখনও AI মডেল প্রম্পটে দেওয়া উদাহরণ থেকে নতুন ধরন কাজে লাগায়, অথচ প্রশিক্ষিত ওজন বদলায় না। এই প্রক্রিয়াকে in-context learning বলা হয়।","Memory":"একটি মডেল বর্তমান কথোপকথন, সংরক্ষিত নোট বা তথ্য-অনুসন্ধান ব্যবস্থার সাহায্যে তথ্য ব্যবহার করতে পারে। এসব যোগ হলে একই মূল মডেলের মনে রাখার মতো আচরণ বদলে যায়।","Reasoning":"AI কোনো সমস্যাকে কয়েকটি ধাপে ভেঙে হিসাব বা টুলের সাহায্যে সমাধানে পৌঁছাতে পারে। সমস্যার গঠন অনুযায়ী কোন পদ্ধতি কাজ করবে, তা বদলাতে পারে।","Metacognition":"AI-কে অনিশ্চয়তা জানাতে, একাধিক উত্তর তুলনা করতে বা নিজের উত্তর পর্যালোচনা করতে শেখানো যায়। সেই আত্মবিশ্বাস সঠিকতার সঙ্গে কতটা মেলে, সেটি আলাদা করে মাপা যায়।","Executive functions":"AI agent পরিকল্পনা, ব্রাউজার বা কোড টুল এবং যাচাইয়ের ধাপ মিলিয়ে বহু-ধাপের কাজ করতে পারে। তাই ফল মডেলের পাশাপাশি তার টুল ও নিয়ন্ত্রণ-ব্যবস্থার ওপরও নির্ভর করে।","Problem solving":"কিছু AI ব্যবস্থা প্রস্তাবিত সমাধান পরীক্ষা করে ভুল থেকে প্রতিক্রিয়া নিয়ে আবার চেষ্টা করতে পারে। একবারে উত্তর দেওয়ার বদলে পরীক্ষা ও সংশোধনের চক্র জটিল কাজে কাজে লাগে।","Social cognition":"ভাষার মডেল গল্পে মানুষের বিশ্বাস ও উদ্দেশ্য নিয়ে প্রশ্নের উত্তর দিতে পারে। এভাবে ভাষার মাধ্যমে সামাজিক পরিস্থিতি বোঝার ক্ষমতা পরীক্ষা করা হয়।"},"animalCard":{"chimpanzee":{"Perception":"শিম্পাঞ্জি টাচস্ক্রিন পরীক্ষায় দৃশ্য-প্যাটার্ন শিখতে পারে। গবেষকেরা এসব কাজে তাদের দৃশ্যমান তথ্য শনাক্ত ও মনে রাখার ধরন পরীক্ষা করেন।","Generation":"বুনো শিম্পাঞ্জিদের বিভিন্ন গোষ্ঠীতে সরঞ্জাম ব্যবহারের আলাদা ঐতিহ্য দেখা যায়। অল্পবয়সীরা অভিজ্ঞ সদস্যদের দেখে স্থানীয় কৌশল শিখতে পারে।","Attention":"শিম্পাঞ্জিরা খাদ্য, কাছের সঙ্গী এবং দলের বদলে যাওয়া সামাজিক সংকেতের দিকে নজর রাখে। দৃষ্টি ও বাছাইভিত্তিক পরীক্ষা দেখায় কোন সংকেত তাদের মনোযোগ টানে।","Learning":"কিছু শিম্পাঞ্জি-গোষ্ঠী বাদাম ভাঙা বা উইপোকা ধরার আলাদা কৌশল ব্যবহার করে। সামাজিক শেখার মাধ্যমে এসব রীতি প্রজন্ম থেকে প্রজন্মে ছড়াতে পারে।","Memory":"কিছু শিম্পাঞ্জি পর্দায় খুব অল্প সময়ের জন্য দেখা সংখ্যার অবস্থান মনে রাখতে পেরেছে। এই দ্রুত দৃশ্য-স্মৃতি প্রাইমেট গবেষণার একটি উল্লেখযোগ্য বিষয়।","Reasoning":"কঠিন পরিস্থিতিতে খাবার পেতে শিম্পাঞ্জি কাঠি ও অন্য সরঞ্জাম বেছে নেয়। কোন সরঞ্জাম কাজে লাগবে, তা তার বৈশিষ্ট্য ও সমস্যার সঙ্গে মেলানোর ওপর নির্ভর করতে পারে।","Metacognition":"পরীক্ষায় পুরস্কারের অবস্থান দেখা না গেলে কিছু শিম্পাঞ্জি সিদ্ধান্তের আগে অতিরিক্ত তথ্য খোঁজে। অনিশ্চয়তায় তারা কী করে, গবেষকেরা এসব বাছাই থেকে তা বোঝার চেষ্টা করেন।","Executive functions":"সরঞ্জাম ব্যবহার করতে বস্তু বাছাই, লক্ষ্যে নিয়ে যাওয়া এবং ব্যর্থ হলে পদ্ধতি বদলানো লাগতে পারে। এ ধরনের ধারাবাহিক কাজ পরিকল্পনা ও নিয়ন্ত্রণ নিয়ে গবেষণায় সাহায্য করে।","Problem solving":"কিছু বুনো শিম্পাঞ্জি পাথরের হাতুড়ি ও নেহাই দিয়ে শক্ত বাদাম ভাঙে। পাথর নির্বাচন ও ঠিকভাবে বসানো খাবার খোঁজাকে বহু-ধাপের শারীরিক সমস্যায় পরিণত করে।","Social cognition":"শিম্পাঞ্জিরা সঙ্গীকে পরিচর্যা করে, জোট গড়ে এবং দলের সম্পর্কের পরিবর্তন অনুসরণ করে। সহযোগিতা ও প্রতিযোগিতা নিয়ে গবেষণায় তাদের সামাজিক জীবন গুরুত্বপূর্ণ।"},"dog":{"Perception":"কুকুর শুধু দেখা বা শোনার মাধ্যমে নয়, ঘ্রাণের মাধ্যমেও চারপাশের সমৃদ্ধ চিত্র তৈরি করে। গন্ধ মানুষ, প্রাণী ও বস্তু শনাক্ত করা এবং অনুসরণ করতে সাহায্য করে।","Generation":"কুকুর খেলার আমন্ত্রণ জানাতে শরীর নিচু করে খেলার ভঙ্গি ও অন্য সংকেত ব্যবহার করে। এসব নমনীয় সংকেত সামাজিক খেলায় পরের আচরণ নির্ধারণে ভূমিকা রাখে।","Attention":"কুকুর মানুষের আঙুলের ইশারা অনুসরণ করে লুকানো খাবার খুঁজে পেতে পারে। ইশারাটি এমন জায়গা সম্পর্কে সংকেত দেয়, যা তারা সরাসরি দেখতে পায় না।","Learning":"কুকুর কিছু অপরিচিত ধরনের নির্দেশক অঙ্গভঙ্গিও সাধারণীকরণ করতে পারে। অর্থাৎ শেখা সংকেতের অর্থ কখনও একটি নির্দিষ্ট অঙ্গভঙ্গির বাইরেও কাজে লাগে।","Memory":"কুকুর গন্ধ, স্থান ও ফলাফলের মধ্যে সম্পর্ক শিখতে পারে। ঘ্রাণসমৃদ্ধ জগৎ তাদের স্মৃতিকে এমন সূত্র দেয়, যা মানুষের প্রধানত দৃশ্যনির্ভর সূত্র থেকে আলাদা।","Reasoning":"মানুষের ইশারা দেখে কুকুর খাবার খোঁজার জায়গা বেছে নিতে পারে। গবেষকেরা সংকেত বদলে দেখেন, শেখা সম্পর্কটি নতুন পরিস্থিতিতেও কাজে লাগে কি না।","Metacognition":"লক্ষ্য দেখা না গেলে সিদ্ধান্তের আগে কুকুর অতিরিক্ত তথ্য খোঁজে কি না, তা গবেষকেরা পরীক্ষা করেছেন। এতে অনিশ্চয়তার ধারণাকে পর্যবেক্ষণযোগ্য বাছাইয়ে দেখা যায়।","Executive functions":"সংকেতের অপেক্ষা করা বা পুরস্কার পেতে দেরি করা কুকুরের আত্মনিয়ন্ত্রণ বোঝার সুযোগ দেয়। এখানে আচরণকে তাৎক্ষণিক তাড়নার বদলে পরের ফলাফলের সঙ্গে মানাতে হয়।","Problem solving":"কুকুর বাধার চারপাশ দিয়ে খুঁজে এবং সংকেত ব্যবহার করে লুকানো বস্তু পেতে পারে। অভিজ্ঞতা, আগ্রহ এবং সমস্যাটি কীভাবে উপস্থাপন করা হয়েছে, তার ওপর কৌশল বদলাতে পারে।","Social cognition":"মানুষের আঙুলের ইশারা অনুসরণ করে কুকুর লুকানো বস্তু খুঁজে পেতে পারে, যদিও ইশারাটির অর্থ স্বাভাবিকভাবে নির্দিষ্ট নয়। এ ক্ষমতা মানুষ-প্রাণীর সামাজিক যোগাযোগ বুঝতে সাহায্য করে।"},"honeybee":{"Perception":"মৌমাছি এমন অতিবেগুনি আলো দেখতে পারে, যা মানুষ দেখতে পায় না। তাই কিছু ফুলের নকশা মৌমাছির কাছে আলাদা দেখায় এবং খাদ্য সংগ্রহে পথ দেখায়।","Generation":"মৌমাছির waggle dance হলো নড়াচড়ার এমন একটি ধারাবাহিকতা, যা খাদ্যের অবস্থান সম্পর্কে তথ্য বহন করে। নাচের মাধ্যমে একটি জায়গা অন্য মৌমাছির ব্যবহারযোগ্য বার্তায় পরিণত হয়।","Attention":"মৌমাছি কোন রং বা দৃশ্য-প্যাটার্ন পুরস্কারের সংকেত দেয় তা শিখে প্রতিদ্বন্দ্বী সংকেতের মধ্যে বেছে নিতে পারে। তাদের ছোট স্নায়ুতন্ত্রও গবেষণাযোগ্য নির্বাচনী আচরণ সমর্থন করে।","Learning":"দৃশ্যভিত্তিক পরীক্ষায় মৌমাছি একই-ভিন্ন এবং ওপর-নিচের মতো সম্পর্ক শিখতে পারে। এসব ফল দেখায় যে শেখা একটি নির্দিষ্ট ছবি মুখস্থ করার বাইরে যেতে পারে।","Memory":"মৌমাছি পথের চিহ্ন মনে রাখে এবং খাদ্য ও চাকের মধ্যে চলাচলে দৃশ্যমান তথ্য ব্যবহার করে। উড়ার পথে শেখা চিহ্নের সঙ্গে সূর্যের অবস্থানও মিলতে পারে।","Reasoning":"নিয়ন্ত্রিত পরীক্ষায় রং দিয়ে নিয়ম জানালে মৌমাছি একটি বস্তু যোগ বা বিয়োগ করতে শিখেছে। ক্ষুদ্র মস্তিষ্কের একটি কীটের সংখ্যাগত নিয়ম শেখার এটি বিস্ময়কর উদাহরণ।","Metacognition":"পরীক্ষায় মৌমাছি শেখা কিছু দৃশ্যগত সম্পর্ক নতুন বিন্যাসেও প্রয়োগ করতে পারে। খুব ছোট স্নায়ুতন্ত্র কীভাবে নমনীয় শেখা সমর্থন করে, গবেষকেরা তা অনুসন্ধান করেন।","Executive functions":"খাদ্য সংগ্রহের সময় একটি মৌমাছি অনুসন্ধান, পথ চিনে চলা এবং চাকের দিকে ফেরার কাজ সমন্বয় করে। ছোট স্নায়ুতন্ত্রে একাধিক আচরণ একসঙ্গে কাজ করে পথ তৈরি করে।","Problem solving":"পরীক্ষায় মৌমাছি নতুন বিন্যাসের আকারেও শেখা দৃশ্যগত নিয়ম প্রয়োগ করতে পারে। এতে একটি প্রশিক্ষিত ছবি চিনে নেওয়ার বদলে নিয়মটিকে নতুন দৃশ্যে কাজে লাগাতে হয়।","Social cognition":"মৌমাছির waggle dance অন্য মৌমাছিকে খাদ্যের দিক ও দূরত্ব জানায়। নাচটি বাইরের জগতের তথ্যকে অন্য মৌমাছির বোঝার মতো নড়াচড়ায় রূপ দেয়।"}},"humanExtra":{"Perception":"প্রতিটি চোখে আলো-সংবেদী কোষহীন একটি ছোট অন্ধস্থান আছে, কিন্তু মস্তিষ্ক আশপাশের দৃশ্য দিয়ে সেটি পূরণ করায় সাধারণত তা চোখে পড়ে না। অন্ধস্থানটি রেটিনায় অপটিক নার্ভ বের হওয়ার জায়গায় থাকে।","Generation":"কখনও একটি কার্যকর সীমাবদ্ধতা সৃজনশীলতা বাড়ায়, কারণ মস্তিষ্ক তখন কাজ করার মতো একটি স্পষ্ট সীমানা পায়। বিকল্প কমলে নতুন সংযোগ খুঁজে পাওয়া সহজ হতে পারে।","Attention":"মনোযোগ অন্য কাজে ব্যস্ত থাকলে চোখের সামনে থাকা বস্তু নজর এড়িয়ে যেতে পারে; এই ঘটনাকে inattentional blindness বলা হয়। একটি বিখ্যাত পরীক্ষায় বল পাস গোনার সময় অনেকেই গরিলা-পোশাকের মানুষটিকে খেয়াল করেননি।","Learning":"কয়েক দিনে অল্প অল্প করে পুনরাবৃত্তি করলে এক বসায় দীর্ঘ সময় পড়ার চেয়ে শেখা বেশি স্থায়ী হতে পারে; একে spacing effect বলা হয়। নিজেকে ছোট পরীক্ষায় যাচাই করলে শুধু পরিচিত লাগছে কি না, তার বদলে কী মনে আছে তা বোঝা যায়।","Memory":"ঘুম কিছু স্মৃতি স্থিতিশীল করতে সাহায্য করে, তাই পড়া শেষ হওয়ার পরও মস্তিষ্ক অভিজ্ঞতা প্রক্রিয়াকরণ চালিয়ে যায়। স্মৃতি স্পষ্ট লাগলেও ছোট বিবরণ বাদ পড়তে বা বদলাতে পারে।","Reasoning":"ধাঁধার ভাষায় সামান্য পরিবর্তনও মানুষ প্রথমে কোন নিয়মটি বিবেচনা করবে, তা বদলে দিতে পারে। কোন তথ্যটি গুরুত্বপূর্ণ, তা চিনে নেওয়াই অনেক সময় সমাধানের অর্ধেক।","Metacognition":"আত্মবিশ্বাসের মূল্য তখনই বেশি, যখন তা বলে দিতে পারে কোন উত্তর যাচাইয়ের পরও সঠিক থাকবে। একটি চমৎকার উত্তর নয়, অনেক উত্তরের ধারাবাহিক ফলেই এটি ভালোভাবে বোঝা যায়।","Executive functions":"কর্মস্মৃতি একটি ছোট মানসিক কাজের টেবিলের মতো, যেখানে তথ্য সাময়িকভাবে ধরে রেখে নাড়াচাড়া করা যায়। এক কাজ থেকে অন্য কাজে যেতে সময় ও মনোযোগ খরচ হয়।","Problem solving":"সমস্যাকে নতুনভাবে উপস্থাপন করলে অসম্ভব মনে হওয়া কাজও সমাধানযোগ্য হয়ে উঠতে পারে। ছোট একটি চিত্র দীর্ঘ বর্ণনায় লুকানো সম্পর্ক দেখাতে পারে।","Social cognition":"মানুষ অন্যকে দেখে শেখে, আর সামাজিক শেখার মাধ্যমে কার্যকর অভ্যাস একটি গোষ্ঠীতে ছড়িয়ে পড়তে পারে। মানুষ অনেক সময় না বুঝেই অন্যের ভঙ্গি বা অভিব্যক্তি অনুসরণ করে।"},"aiExtra":{"Perception":"AI-এর অনুধাবন ছবির পিক্সেলকে ভাষার সঙ্গে যুক্ত করে, ফলে এটি শুধু লেবেলের তালিকা নয়, দৃশ্যের বর্ণনাও দিতে পারে। প্রশ্ন বদলালে একই ছবির ভিন্ন বিবরণও সামনে আসতে পারে।","Generation":"একই নির্দেশ থেকেও নানা ফল আসে, কারণ জেনারেটিভ ব্যবস্থা শেখা ধরন নতুনভাবে সাজায়। প্রম্পট ফলের দিক নির্ধারণ করে, তবে একাধিক সম্ভাব্য উত্তর তৈরি হতে পারে।","Attention":"ট্রান্সফরমার মডেলে “attention” একটি গাণিতিক প্রক্রিয়ার নাম, সচেতনভাবে মনোযোগ অনুভব করার নাম নয়। এটি প্রসঙ্গের বিভিন্ন শব্দের মধ্যে তথ্যের সম্পর্ক গড়ে তুলতে সাহায্য করে।","Learning":"in-context learning-এ প্রম্পটের উদাহরণ মডেলের প্রশিক্ষিত ওজন না বদলিয়েই তার উত্তর পাল্টাতে পারে। উদাহরণগুলো ওই উত্তরে প্রভাব ফেলে, মডেলকে নতুন করে প্রশিক্ষণ দেয় না।","Memory":"প্রাসঙ্গিক হলে retrieval-ভিত্তিক ব্যবস্থা বাইরের নোটকে মডেলের বর্তমান কাজের প্রেক্ষাপটে এনে দিতে পারে। এতে মডেলের ওজনের ভেতরে না থাকা তথ্যও প্রয়োজনে ব্যবহার করা যায়।","Reasoning":"উত্তর তৈরির সময় অতিরিক্ত গণনা কিছু মডেলকে সমাধানের একাধিক পথ যাচাই করার সুযোগ দেয়। অতিরিক্ত গণনা সহায়ক হতে পারে, তবে সঠিক উত্তর নিশ্চিত করে না।","Metacognition":"calibration মাপে মডেলের জানানো আত্মবিশ্বাস বাস্তবে তার সঠিক উত্তরের হারের সঙ্গে মেলে কি না। নতুন প্রমাণ পেলে মডেলকে দ্বিতীয়বার উত্তর যাচাই করতেও বলা যায়।","Executive functions":"AI agent-এর ফল তার মূল মডেলের পাশাপাশি নিয়ন্ত্রণ-ব্যবস্থা ও হাতে থাকা টুলের ওপরও নির্ভর করে। একটি ভুল টুল-ফল পরের ধাপগুলোকেও প্রভাবিত করতে পারে।","Problem solving":"পরিকল্পনা, পরীক্ষা ও সংশোধনের চক্র প্রথম ব্যর্থ চেষ্টাকেও পরের চেষ্টার জন্য কার্যকর প্রতিক্রিয়ায় বদলে দিতে পারে। প্রতিক্রিয়া দিয়ে পরীক্ষা করলেই প্রথম সমাধানের দুর্বলতা ধরা পড়ে।","Social cognition":"ভাষাভিত্তিক সামাজিক যুক্তির পরীক্ষায় শব্দের ভূমিকা বড়, অথচ মানুষ মুখভঙ্গি, কণ্ঠ ও পরিস্থিতির তথ্যও ব্যবহার করে। আবেগ নিয়ে লেখা বোঝা আর আবেগ অনুভব করা এক বিষয় নয়।"},"animalExtra":{"chimpanzee":{"Perception":"একটি বিখ্যাত দৃশ্য-পরীক্ষায় পর্দায় সংখ্যা খুব অল্প সময়ের জন্য দেখা যায়, যা দ্রুত শনাক্তকরণ ও দৃশ্য-স্মৃতি দুটিকেই চ্যালেঞ্জ করে। এতে বোঝা যায়, অবস্থান কত দ্রুত মনে রাখা যায়।","Generation":"গবেষকেরা কিছু গোষ্ঠী-নির্দিষ্ট সরঞ্জাম-ব্যবহারকে সাংস্কৃতিক রীতি বলেন, যা প্রজন্ম ধরে টিকে থাকতে পারে। একটি আচরণ সফল হওয়া আর গোষ্ঠীতে ঐতিহ্য হয়ে ওঠা আলাদা বিষয়।","Attention":"সংকেত বদলালে শিম্পাঞ্জি কোথায় তাকায় এবং কী বেছে নেয়, গবেষকেরা তা তুলনা করতে পারেন। সংকেত বদলালে কোন তথ্য সিদ্ধান্তে প্রভাব ফেলে, তা বোঝা যায়।","Learning":"বুনো শিম্পাঞ্জিদের ভিন্ন গোষ্ঠী একই ধরনের লক্ষ্য পূরণে ভিন্ন সরঞ্জাম-কৌশল গড়ে তুলতে পারে। বয়স্ক সদস্যকে দেখে শেখা কৌশল তরুণ শিম্পাঞ্জির কাছে ছড়াতে পারে।","Memory":"সবচেয়ে পরিচিত উদাহরণগুলোর মধ্যে আছে খুব অল্প সময়ের জন্য দেখা সংখ্যার অবস্থান সঙ্গে সঙ্গে মনে রাখা। অবস্থান মনে রাখা শুধু সংখ্যাটি চিনে নেওয়ার চেয়ে আলাদা কাজ।","Reasoning":"সরঞ্জামের আকার, দৈর্ঘ্য ও নাগাল বদলালে কোনটি কাজে লাগবে, সেটিও বদলে যেতে পারে। সরঞ্জামের গঠন ও নাগালকে লক্ষ্যের সঙ্গে মেলাতে হয়।","Metacognition":"তথ্য খোঁজার সিদ্ধান্ত প্রাণীকে নিজের চিন্তা ভাষায় বোঝাতে না বলেও অনিশ্চয়তা নিয়ে গবেষণার সুযোগ দেয়। লুকানো বস্তু দেখার আগে ও পরে নেওয়া সিদ্ধান্ত তুলনা করা যায়।","Executive functions":"একটি চেষ্টা ব্যর্থ হওয়ার পর কৌশল বদলানো শুধু অভ্যাসের নড়াচড়া পুনরাবৃত্তি করার চেয়ে বেশি তথ্য দেয়। কৌশল বদলানোর ক্ষমতা শুধু একই কাজ পুনরাবৃত্তির চেয়ে বেশি তথ্য দেয়।","Problem solving":"বুনো শিম্পাঞ্জির পাথরের সরঞ্জাম দিয়ে বাদাম ভাঙা প্রযুক্তিগত সমস্যা সমাধানের একটি পরিচিত উদাহরণ। এখানে সরঞ্জাম বাছাই, বসানো ও নিয়ন্ত্রিত আঘাত একসঙ্গে লাগে।","Social cognition":"দলটির মধ্যে কে কার সঙ্গে সহযোগিতা করে, তা পরিচর্যা ও জোটের ধরন দ্বারা প্রভাবিত হতে পারে। জোটের সম্পর্ক বদলালে সহযোগিতা ও সহায়তা পাওয়ার ধরনও বদলায়।"},"dog":{"Perception":"বর্তমান গবেষণায় গন্ধ কীভাবে কুকুরের আবেগ ও সামাজিক প্রতিক্রিয়ায় প্রভাব ফেলে, তাও দেখা হয়। কোনো প্রাণী বা বস্তু চোখে না পড়লেও তার গন্ধ থেকে তথ্য মিলতে পারে।","Generation":"খেলার সময় কুকুরের শরীর নিচু করার ভঙ্গি একটি পরিচিত সংকেত, যা আচরণটিকে খেলা হিসেবে চিহ্নিত করে। খেলার সংকেত অন্য কুকুরকে আচরণটি আমন্ত্রণ হিসেবে বুঝতে সাহায্য করে।","Attention":"কুকুর কীভাবে সাড়া দেয়, তা আঙুলের ইশারার ধরন এবং পরিস্থিতির ওপর নির্ভর করতে পারে। ইশারা বদলে গবেষকেরা দেখেন, কুকুর কোন সংকেত অনুসরণ করে।","Learning":"সাধারণীকরণের কারণে শেখা সংকেতটি ঠিক একই প্রশিক্ষণ-উদাহরণের বাইরেও কাজে লাগে। ভিন্ন মানুষ সামান্য ভিন্নভাবে ইশারা করলেও এই নমনীয়তা কাজে লাগে।","Memory":"গন্ধের উৎস বস্তুটি সরে যাওয়ার পরও সেই গন্ধ তথ্য বহন করতে পারে। দৃশ্য পাল্টে গেলেও গন্ধ আগের ঘটনার তথ্য ধরে রাখতে পারে।","Reasoning":"সংকেতের অবস্থান বা ধরন বদলে গবেষকেরা শেখা সম্পর্ক নতুন পরিস্থিতিতে কাজে লাগে কি না পরীক্ষা করেন। সংকেত বদলালে শেখা সম্পর্কটি নতুন অবস্থায় কাজে লাগে কি না বোঝা যায়।","Metacognition":"প্রাণীর অনিশ্চয়তা নিয়ে গবেষণা অসম্পূর্ণ তথ্য থাকলে প্রাণী কী বেছে নেয়, তা অনুসন্ধান করে। পরিস্থিতি বদলে গবেষকেরা দেখেন একই তথ্য-খোঁজার ধরন আবার দেখা যায় কি না।","Executive functions":"আত্মনিয়ন্ত্রণের পরীক্ষায় তাৎক্ষণিক পুরস্কার ও পরে পাওয়া পুরস্কারের জন্য অপেক্ষা করার তুলনা করা যায়। পুরস্কার চোখের সামনে থাকলে অপেক্ষা করা আরও কঠিন হতে পারে।","Problem solving":"সামনের পথ বন্ধ হলে কুকুর অন্য পথ নেয় কি না, বাধা-ভিত্তিক পরীক্ষা তা প্রকাশ করতে পারে। বিকল্প পথে যাওয়া বাধা অনুযায়ী কৌশল বদলানোর ইঙ্গিত দেয়।","Social cognition":"মানুষের বিভিন্ন যোগাযোগমূলক অঙ্গভঙ্গিতে কুকুর বিশেষভাবে সাড়া দেয়। একটি সাধারণ ইশারা দুই ভিন্ন প্রজাতির মধ্যে যোগাযোগের সেতু হতে পারে।"},"honeybee":{"Perception":"কিছু ফুলের অতিবেগুনি নকশা মানুষ দেখতে পায় না, কিন্তু মৌমাছি দেখতে পারে। ফলে মৌমাছি এমন দৃশ্যগত তথ্য পায়, যা মানুষ সরাসরি দেখতে পারে না।","Generation":"waggle dance-এ উল্লম্ব দিকের তুলনায় নাচের কোণ সূর্যের তুলনায় খাদ্যের দিক জানায়। শব্দ ছাড়াই নাচের মাধ্যমে খাদ্যের অবস্থান জানানো যায়।","Attention":"মৌমাছির দৃশ্যগত পার্থক্যকরণে রং, আকার ও পুনরাবৃত্ত প্যাটার্ন কাজে লাগে। রং বা নকশার ছোট বদলও শেখা বাছাইকে প্রভাবিত করতে পারে।","Learning":"মৌমাছি একই-ভিন্ন এবং ওপর-নিচের মতো সম্পর্ক শিখতে পারে বলে গবেষণায় দেখা গেছে। শেখা সম্পর্ক নতুন বিন্যাসেও প্রয়োগ করা যেতে পারে।","Memory":"পথ চলার সময় মৌমাছি মনে রাখা স্থলচিহ্নের সঙ্গে আকাশের সংকেত মিলিয়ে নিতে পারে। চেনা স্থলচিহ্ন পথকে আবার অনুসরণ করার উপযোগী করে তোলে।","Reasoning":"একটি পরীক্ষায় রং মৌমাছিকে জানাত কোন ক্ষেত্রে একটি বস্তু যোগ করতে হবে আর কোন ক্ষেত্রে বিয়োগ। নিয়ম একই রেখে গবেষকেরা দৃশ্যের বিন্যাস বদলে পরীক্ষা করেন।","Metacognition":"নতুন দৃশ্যে শেখা নিয়ম প্রয়োগ করা একটি সম্পর্ক শেখা আর শুধু একটি ছবি মুখস্থ করার পার্থক্য বুঝতে সাহায্য করে। এ ধরনের স্থানান্তর ক্ষুদ্র স্নায়ুতন্ত্রেও নমনীয় শেখার ধারণা দেয়।","Executive functions":"খাদ্য সংগ্রহে অনুসন্ধান, নেভিগেশন এবং ফিরে আসার সিদ্ধান্ত একটি ছোট স্নায়ুতন্ত্রের মধ্যে সমন্বিত হয়। একটি যাত্রায় খোঁজা, পথ চেনা ও ফিরে আসা সমন্বয় করতে হয়।","Problem solving":"নতুন দৃশ্যে শেখা নিয়ম প্রয়োগ করা দেখায় মৌমাছি প্যাটার্নটিকে একটি উদাহরণের বাইরেও কাজে লাগাতে পেরেছে। এ পরীক্ষায় দেখা হয় শেখা নিয়মটি মূল উদাহরণের বাইরেও সিদ্ধান্তে সাহায্য করে কি না।","Social cognition":"মৌমাছির waggle dance নাচ করা মৌমাছির দেখা খাদ্যস্থলে অন্য মৌমাছিদের যেতে উৎসাহিত করতে পারে। এটি কীটের মধ্যে তথ্য পৌঁছে দেওয়ার পরিচিত বিস্ময়কর উদাহরণ।"}}}};
    const localeFacts = cardFacts[locale];
    const humanCardFact = localeFacts.humanCard[d.name];
    const otherCardFact = animal
      ? ((localeFacts.animalCard[comparator] || {})[d.name] || (bn ? 'নির্বাচিত সক্ষমতায় প্রাণীর আচরণ নিয়ে গবেষণা চলমান।' : 'Researchers study how this animal uses the selected faculty in everyday behaviour.'))
      : (localeFacts.aiCard[d.name] || (bn ? 'AI বিভিন্ন ধাপের তথ্য একত্র করে নতুন কাজ সম্পন্ন করতে পারে।' : 'AI can combine information across steps to complete a new task.'));
    const humanExtra = localeFacts.humanExtra[d.name] || '';
    const otherExtra = animal
      ? ((localeFacts.animalExtra[comparator] || {})[d.name] || '')
      : (localeFacts.aiExtra[d.name] || '');
    const humanBelow = humanExtra;
    const otherBelow = otherExtra;

    atlasPdfDrawReferenceCard(g, {
      x:cardX1, y:cardY, w:cardW, h:cardH,
      title:humanName, score:Number(d.human), accent:humanAccent, light:humanLight,
      track:'#E9EDF3', fact:humanCardFact,
      scoreFont:'800 76px "Manrope", "Noto Sans Bengali", sans-serif',
      labelFont:'500 28px "Manrope", "Noto Sans Bengali", sans-serif', isHuman:true, bn
    });
    atlasPdfDrawReferenceCard(g, {
      x:cardX2, y:cardY, w:cardW, h:cardH,
      title:otherName, score:otherScore, accent:accent, light:facultyLight,
      track:'#E9EDF3', fact:otherCardFact,
      scoreFont:'800 76px "Manrope", "Noto Sans Bengali", sans-serif',
      labelFont:'500 28px "Manrope", "Noto Sans Bengali", sans-serif', isHuman:false, bn
    });

    // Untitled paragraphs are part of the reference layout; they now carry faculty-relevant facts.
    g.textAlign = 'center';
    atlasPdfDrawWrapped(g, humanBelow, cardX1 - 18, 704, cardW + 36, 22,
      '400 17px "Manrope", "Noto Sans Bengali", sans-serif', '#5B5D60', 'center', 3);
    atlasPdfDrawWrapped(g, otherBelow, cardX2 - 18, 704, cardW + 36, 22,
      '400 17px "Manrope", "Noto Sans Bengali", sans-serif', '#5B5D60', 'center', 3);

    g.strokeStyle = '#D9DDE1'; g.lineWidth = 1.25;
    g.beginPath(); g.moveTo(142, 841); g.lineTo(W - 139, 841); g.stroke();

    const jpegBlob = await new Promise(resolve => canvas.toBlob(resolve, 'image/jpeg', 0.97));
    if (!jpegBlob) throw new Error('Could not encode page image');
    const jpegBytes = new Uint8Array(await jpegBlob.arrayBuffer());
    const pdfBlob = atlasPdfBuildImagePDF(jpegBytes, canvas.width, canvas.height, W, H, []);
    const safeFaculty = String(d.name).normalize('NFD').replace(/[\u0300-\u036f]/g,'').replace(/[^a-z0-9]+/gi,'-').replace(/^-|-$/g,'');
    const animalFile = animal ? comparator : (years > 0 ? `AI-Scenario-${rate}perYear-${years}years` : 'AI');
    const safeComparator = String(animalFile).normalize('NFD').replace(/[\u0300-\u036f]/g,'').replace(/[^a-z0-9]+/gi,'').replace(/^-|-$/g,'');
    const dateParts = Object.fromEntries(new Intl.DateTimeFormat('en-CA', {year:'numeric', month:'2-digit', day:'2-digit', timeZone:'Asia/Dhaka'}).formatToParts(snapshotDate).map(part => [part.type, part.value]));
    const fileDate = `${dateParts.year}-${dateParts.month}-${dateParts.day}`;
    const pdfUrl = URL.createObjectURL(pdfBlob);
    const a = document.createElement('a');
    const isIOS = /iPad|iPhone|iPod/.test(navigator.userAgent) || (navigator.platform === 'MacIntel' && navigator.maxTouchPoints > 1);
    a.href = pdfUrl;
    a.download = `Cognitive-Comparison-Atlas-${safeFaculty}-${safeComparator}-${fileDate}.pdf`;
    a.target = isIOS ? '_blank' : '_self';
    if (isIOS) a.rel = 'noopener';
    a.style.position = 'fixed'; a.style.left = '-9999px'; a.style.top = '0';
    document.body.appendChild(a);
    a.click();
    a.remove();
    // iOS Safari commonly previews Blob PDFs instead of honoring the download attribute.
    // Keep the Blob URL alive long enough for the native preview/download sheet to consume it.
    setTimeout(() => URL.revokeObjectURL(pdfUrl), isIOS ? 120000 : 30000);
    showAtlasStatus(isIOS
      ? (bn ? 'পিডিএফ খুললে শেয়ার বোতাম থেকে “Save to Files” বেছে নিন।' : 'If the PDF opens, use Share → Save to Files to keep it on your iPhone or iPad.')
      : (bn ? 'তুলনার পিডিএফ কপি তৈরি হয়েছে।' : 'Your comparison snapshot PDF is ready.'));
  }
  function atlasPdfDrawReferenceCard(g, opt) {
    const {x,y,w,h,title,score,accent,light,track,fact,scoreFont,labelFont,isHuman,bn} = opt;
    g.save();
    const bg = g.createLinearGradient(x, y, x + w, y + h);
    bg.addColorStop(0, atlasPdfMix(light, '#FFFFFF', 0.04));
    bg.addColorStop(1, atlasPdfMix(light, '#FFFFFF', 0.20));
    g.fillStyle = bg; g.fillRect(x, y, w, h);
    g.fillStyle = accent; g.fillRect(x, y, w, 5);
    g.strokeStyle = atlasPdfMix(accent, '#FFFFFF', 0.52); g.lineWidth = 1;
    g.beginPath(); g.moveTo(x, y + h - 1); g.lineTo(x + w, y + h - 1); g.stroke();

    g.textAlign = 'center'; g.textBaseline = 'alphabetic';
    g.fillStyle = accent; g.font = labelFont;
    g.fillText(title, x + w/2, y + 42, w - 24);
    const numeric = score == null || !Number.isFinite(Number(score)) ? null : Math.max(0, Math.min(100, Number(score)));
    const value = numeric == null ? '—' : numeric.toFixed(1);
    g.fillStyle = atlasPdfDarken(accent, 0.08); g.font = scoreFont;
    g.fillText(bn ? toBanglaNumber(value) : value, x + w/2, y + 126, w - 30);

    const barW = 372, barH = 13, barX = x + (w - barW)/2, barY = y + 146;
    g.fillStyle = track; atlasPdfRoundRect(g, barX, barY, barW, barH, 7); g.fill();
    if (numeric != null && numeric > 0) {
      const fillW = Math.max(7, barW * numeric / 100);
      g.fillStyle = atlasPdfMix(accent, '#FFFFFF', 0.30);
      atlasPdfRoundRect(g, barX, barY, Math.min(barW, fillW), barH, 7); g.fill();
    }
    g.fillStyle = '#111820';
    atlasPdfDrawWrapped(g, fact, x + 34, y + 192, w - 68, 18,
      '400 15px "Manrope", "Noto Sans Bengali", sans-serif', '#111820', 'center', 3);
    g.restore();
  }
  function atlasPdfDrawAnalysis(g,text,x,y,w,maxHeight,font,color) {
    g.save(); g.fillStyle=color; g.font=font; g.textAlign='center'; g.textBaseline='alphabetic';
    const lineH=27, maxLines=Math.floor(maxHeight/lineH);
    atlasPdfDrawWrapped(g,text,x+24,y,w-48,lineH,font,color,'center',maxLines);
    g.restore();
  }
  function atlasPdfDrawWrapped(g,text,x,y,maxW,lineH,font,color,align='left',maxLines=Infinity) {
    g.save(); g.font=font; g.fillStyle=color; g.textAlign=align; g.textBaseline='alphabetic';
    const words=String(text??'').split(/\s+/).filter(Boolean); const lines=[]; let line='';
    for (const word of words) {
      const candidate=line?`${line} ${word}`:word;
      if(g.measureText(candidate).width>maxW && line){lines.push(line);line=word;}else line=candidate;
    }
    if(line) lines.push(line);
    let visible=lines.slice(0,maxLines);
    if(lines.length>maxLines && visible.length){
      let last=visible[visible.length-1]; while(last.length && g.measureText(last+'…').width>maxW) last=last.slice(0,-1);
      visible[visible.length-1]=last+'…';
    }
    const baseX=align==='center'?x+maxW/2:(align==='right'?x+maxW:x);
    visible.forEach((t,i)=>g.fillText(t,baseX,y+i*lineH));
    g.restore(); return y+(Math.max(visible.length,1)-1)*lineH;
  }
  function atlasPdfRoundRect(g,x,y,w,h,r) {
    const rr=Math.min(r,w/2,h/2);
    g.beginPath(); g.moveTo(x+rr,y); g.arcTo(x+w,y,x+w,y+h,rr); g.arcTo(x+w,y+h,x,y+h,rr); g.arcTo(x,y+h,x,y,rr); g.arcTo(x,y,x+w,y,rr); g.closePath();
  }
  function atlasPdfMix(hex1,hex2,whiteRatio) {
    const a=atlasPdfHex(hex1),b=atlasPdfHex(hex2); const r=Math.round(a[0]*(1-whiteRatio)+b[0]*whiteRatio),g=Math.round(a[1]*(1-whiteRatio)+b[1]*whiteRatio),bl=Math.round(a[2]*(1-whiteRatio)+b[2]*whiteRatio);
    return '#'+[r,g,bl].map(n=>n.toString(16).padStart(2,'0')).join('').toUpperCase();
  }
  function atlasPdfDarken(hex,ratio) { const [r,g,b]=atlasPdfHex(hex).map(v=>Math.round(v*(1-ratio))); return '#'+[r,g,b].map(n=>n.toString(16).padStart(2,'0')).join('').toUpperCase(); }
  function atlasPdfHex(hex) { const c=String(hex||'#E30613').replace('#',''); const full=c.length===3?c.split('').map(v=>v+v).join(''):c; return [parseInt(full.slice(0,2),16),parseInt(full.slice(2,4),16),parseInt(full.slice(4,6),16)]; }
  function atlasPdfLoadImage(src) { return new Promise((resolve,reject)=>{const im=new Image();im.onload=()=>resolve(im);im.onerror=reject;im.src=src;}); }
  function atlasPdfBuildImagePDF(jpegBytes,pixelW,pixelH,logicalW,logicalH,links) {
    const enc=new TextEncoder(), parts=[]; let total=0; const offsets=[];
    const push=chunk=>{parts.push(chunk);total+=chunk.length;};
    const ascii=s=>enc.encode(s);
    push(ascii('%PDF-1.4\n%\xE2\xE3\xCF\xD3\n'));
    function obj(id,bodyParts){offsets[id]=total;push(ascii(`${id} 0 obj\n`));bodyParts.forEach(p=>push(typeof p==='string'?ascii(p):p));push(ascii('\nendobj\n'));}
    const annotationIds=links.map((_,i)=>6+i);
    obj(1,['<< /Type /Catalog /Pages 2 0 R >>']);
    obj(2,[`<< /Type /Pages /Kids [3 0 R] /Count 1 >>`]);
    const pageW=792, pageH=pageW*logicalH/logicalW;
    obj(3,[`<< /Type /Page /Parent 2 0 R /MediaBox [0 0 ${pageW.toFixed(4)} ${pageH.toFixed(4)}] /Resources << /XObject << /Im0 5 0 R >> >> /Contents 4 0 R /Annots [${annotationIds.map(id=>id+' 0 R').join(' ')}] >>`]);
    const stream=`q\n${pageW} 0 0 ${pageH.toFixed(4)} 0 0 cm\n/Im0 Do\nQ`;
    obj(4,[`<< /Length ${enc.encode(stream).length} >>\nstream\n${stream}\nendstream`]);
    offsets[5]=total; push(ascii(`5 0 obj\n<< /Type /XObject /Subtype /Image /Width ${pixelW} /Height ${pixelH} /ColorSpace /DeviceRGB /BitsPerComponent 8 /Filter /DCTDecode /Length ${jpegBytes.length} >>\nstream\n`)); push(jpegBytes); push(ascii('\nendstream\nendobj\n'));
    links.forEach((link,i)=>{
      const id=annotationIds[i];
      const sx=pageW/logicalW, sy=pageH/logicalH;
      const x1=Math.max(0,link.x*sx), x2=Math.min(pageW,(link.x+link.w)*sx);
      const y1=Math.max(0,pageH-(link.y+link.h)*sy), y2=Math.min(pageH,pageH-link.y*sy);
      const safeUrl=String(link.url).replace(/[()\\]/g,'');
      obj(id,[`<< /Type /Annot /Subtype /Link /Rect [${x1.toFixed(2)} ${y1.toFixed(2)} ${x2.toFixed(2)} ${y2.toFixed(2)}] /Border [0 0 0] /A << /Type /Action /S /URI /URI (${safeUrl}) >> >>`]);
    });
    const xrefOffset=total, size=6+links.length;
    let xref=`xref\n0 ${size}\n0000000000 65535 f \n`;
    for(let id=1;id<size;id++) xref+=`${String(offsets[id]).padStart(10,'0')} 00000 n \n`;
    push(ascii(xref+`trailer\n<< /Size ${size} /Root 1 0 R >>\nstartxref\n${xrefOffset}\n%%EOF`));
    return new Blob(parts,{type:'application/pdf'});
  }
  // Canvas text wrapping keeps the two fact blocks aligned with the reference composition.
  function wrapCanvasText(ctx, text, x, y, maxWidth, lineHeight, fontSize, color) {
    ctx.font = `500 ${fontSize}px Arial, sans-serif`; ctx.fillStyle = color;
    const words = String(text).split(/\s+/); let line = '', lineCount = 0;
    for (const word of words) {
      const test = line ? line + ' ' + word : word;
      if (ctx.measureText(test).width > maxWidth && line) { ctx.fillText(line,x,y+lineCount*lineHeight); line = word; lineCount++; }
      else line = test;
    }
    if (line) ctx.fillText(line,x,y+lineCount*lineHeight);
    return y + lineCount*lineHeight;
  }
  // Keep the evidence summary fresh whenever existing update logic refreshes the selected comparison.
  const baseUpdateInspector = updateInspector;
  updateInspector = function() { baseUpdateInspector(); refreshEvidencePassport(); };
  $('#atlasDownloadCard').addEventListener('click', drawResultCard);
  $('#atlasEvidencePassport').addEventListener('click', event => { event.preventDefault(); event.stopPropagation(); });
  $('#atlasEvidencePassport').addEventListener('keydown', event => { if (event.key === 'Enter' || event.key === ' ') { event.preventDefault(); } });
  document.querySelectorAll('.mode-switch button').forEach(button => button.addEventListener('click', () => { refreshEvidencePassport(); }));
  $('#languageToggle').addEventListener('click', () => { setTimeout(() => { refreshEvidencePassport(); updateScenarioStamp(); }, 0); });
  $('#facultySelect').addEventListener('change',e=>selectFaculty(Number(e.target.value)));
  $('#comparatorSelect').addEventListener('change',e=>{comparator=e.target.value;years=0;$('#horizon').value='0';updateStats();updateInspector();applyDynamicLanguage();applyScenarioLanguage();draw();});
  function stepComparator(direction) {
    const select = $('#comparatorSelect');
    const options = Array.from(select.options);
    const current = Math.max(0, options.findIndex(option => option.value === comparator));
    const next = (current + direction + options.length) % options.length;
    comparator = options[next].value;
    select.value = comparator;
    years = 0; $('#horizon').value = '0';
    updateStats(); updateInspector(); applyDynamicLanguage(); applyScenarioLanguage(); draw(); refreshEvidencePassport();
  }
  $('#prevComparator').addEventListener('click', () => stepComparator(-1));
  $('#nextComparator').addEventListener('click', () => stepComparator(1));
  $('#prevFaculty').addEventListener('click',()=>selectFaculty(selected-1));
  $('#nextFaculty').addEventListener('click',()=>selectFaculty(selected+1));
  $('#journeyTrigger').addEventListener('click',()=>{yaw-=Math.PI*2/data.length;zoom=1;autoSpin=true;selectFaculty(selected+1);applyScenarioLanguage();});
  $('#zoomIn').addEventListener('click',()=>{zoom=Math.min(1.8,zoom+.15);draw();applyDynamicLanguage();});
  $('#zoomOut').addEventListener('click',()=>{zoom=Math.max(.65,zoom-.15);draw();applyDynamicLanguage();});
  $('#resetView').addEventListener('click',()=>{yaw=-0.35;pitch=0.9;zoom=1;draw();applyDynamicLanguage();});
  $('#languageToggle').addEventListener('click',()=>{lang=lang==='en'?'bn':'en';applyStaticLanguage();});
  $('#watchList').addEventListener('click',e=>{const button=e.target.closest('button[data-index]');if(button)selectFaculty(Number(button.dataset.index));});
  document.querySelectorAll('.mode-switch button').forEach(button=>button.addEventListener('click',()=>{
    const mode=button.dataset.view;
    document.querySelectorAll('.mode-switch button').forEach(b=>b.setAttribute('aria-pressed',String(b===button)));
    const wrap=$('#canvasWrap');
    wrap.dataset.view=mode;
    if(isAnimalComparator()){
      years=0;$('#horizon').value='0';rate=mode==='trajectory'?6:3;
      if(mode==='cosmos'){yaw=-0.35;pitch=0.9;zoom=1;}
      else if(mode==='frontier') zoom=1.18;
      else if(mode==='evidence') zoom=1.12;
      else if(mode==='impact') zoom=1.08;
      applyScenarioLanguage();draw();applyDynamicLanguage();return;
    }
    if(mode!=='trajectory'){years=0;rate=3;$('#horizon').value='0';}
    if(mode==='cosmos'){yaw=-0.35;pitch=0.9;zoom=1;setText('galaxySubtitle',lang==='bn'?'ঘুরিয়ে দেখুন · যেকোনো চিহ্ন বাছুন · জুম করে দেখুন':'Rotate the field · select a marker · zoom to inspect');setText('projectionMode',lang==='bn'?'মহাবিশ্ব · সারসংক্ষেপ':'Cosmos · overview');}
    if(mode==='frontier'){const gaps=data.map((d,i)=>({i,g:Math.abs(d.human-comparisonScore(d,i,false))})).sort((a,b)=>b.g-a.g);selectFaculty(gaps[0].i);zoom=1.38;setText('galaxySubtitle',lang==='bn'?'সবচেয়ে বড় ব্যবধানের দিকে ফোকাস করা হয়েছে':'Focused on the largest reported gap');setText('projectionMode',lang==='bn'?'ফ্রন্টিয়ার · ব্যবধান':'Frontier · gap view');}
    if(mode==='trajectory'){rate=6;$('#horizon').value='5';updateScenario();setText('galaxySubtitle',lang==='bn'?'ভবিষ্যৎ দৃশ্য · অনুমান, পূর্বাভাস নয়':'Future scenario · what-if, not a forecast');setText('projectionMode',lang==='bn'?'সম্ভাব্য পথ · +৫ বছর':'Trajectory · +5 years');}
    if(mode==='evidence'){const caution=d=>{const c=d.confidence.toLowerCase();return(c.includes('estimated')||c.includes('different tests')||c.includes('vendor-reported'))?3:(c.includes('small')||c.includes('harness'))?2:1;};const weakest=data.map((d,i)=>({i,level:caution(d)})).sort((a,b)=>b.level-a.level);selectFaculty(weakest[0].i);zoom=1.2;setText('galaxySubtitle',lang==='bn'?'ড্যাশযুক্ত বড় বলয় তুলনার সতর্কতা দেখায়, পরিসংখ্যানগত ত্রুটি নয়':'Dashed rings flag comparison caveats, not statistical error bars');setText('projectionMode',lang==='bn'?'প্রমাণ · সতর্কতার মানচিত্র':'Evidence · caveat lens');}
    if(mode==='impact'){const candidates=data.map((d,i)=>({i,g:comparisonScore(d,i,false)-d.human})).sort((a,b)=>b.g-a.g);selectFaculty(candidates[0].i);zoom=1.25;setText('galaxySubtitle',lang==='bn'?'তুলনাকারীর সবচেয়ে বড় ব্যবধান পরীক্ষা করুন':'Inspect the largest comparator-leading gap');setText('projectionMode',lang==='bn'?'প্রভাব · নির্বাচিত সক্ষমতা':'Impact · selected capability');}
    applyScenarioLanguage();draw();applyDynamicLanguage();
  }));
  document.querySelectorAll('.scenario').forEach(b=>b.addEventListener('click',()=>{rate=Number(b.dataset.rate);updateScenario();}));
  $('#horizon').addEventListener('input',updateScenario);
  $('#horizon').addEventListener('change',updateScenario);
  window.addEventListener('resize',resize,{passive:true});
  focusFaculty(selected,true); buildFacultySelect(); updateStats(); updateInspector(); updateScenario(); applyStaticLanguage(); resize();
  raf=requestAnimationFrame(animate);
})();
</script>

<!--sites-preview-theme:start-->
<style data-sites-preview-theme>:root{--site-font-body:system-ui,sans-serif !important;--site-font-heading:system-ui,sans-serif !important}</style>
<script type="application/json" data-sites-preview-theme>{"appearance":"custom","primary":null,"secondary":null,"background":"#ffffff","typography":"modern","spacing":1,"roundness":1,"headingScale":null,"decorationOpacity":null}</script>
<!--sites-preview-theme:end-->
<style id="capability-cosmos-refinements">
  /* Preserve the existing interface while tightening selected elements. */
  .zoom-controls #howToUse { white-space: nowrap; }
  .right-rail .data-links { gap: 2px !important; row-gap: 2px !important; }
  .right-rail .calibration-links { gap: 2px !important; row-gap: 2px !important; }
  .right-rail .model-block > #facultySourceLink { margin-top: 2px !important; }
  .right-rail .model-block > #facultySourceLink,
  .right-rail .model-block > #takeTestLink {
    display: block !important;
    margin-top: 3px !important;
    line-height: 1.35 !important;
    white-space: normal !important;
  }
  .right-rail .projection-card .projection-title {
    font-size: 11.5px !important;
    line-height: 1.2 !important;
  }
  .right-rail .projection-card .projection-explain {
    font-size: 9.5px !important;
    line-height: 1.4 !important;
    margin: 6px 0 9px !important;
  }
  .right-rail .projection-card .scenario-tabs { gap: 4px !important; }
  .right-rail .projection-card .scenario {
    height: 26px !important;
    min-height: 26px !important;
    max-height: 26px !important;
    padding: 5px 4px !important;
    font-size: 8.5px !important;
    line-height: 1.1 !important;
    white-space: nowrap !important;
    resize: none !important;
  }

  .howto-backdrop {
    position: fixed; inset: 0; z-index: 10000;
    display: none; align-items: center; justify-content: center;
    padding: 18px;
    background: rgba(9, 13, 21, .64);
    backdrop-filter: blur(8px);
    -webkit-backdrop-filter: blur(8px);
  }
  .howto-backdrop[data-open="true"] { display: flex; }
  .howto-dialog {
    position: relative;
    width: min(690px, calc(100vw - 28px));
    max-height: min(84vh, 760px);
    overflow: auto;
    overscroll-behavior: contain;
    padding: clamp(24px, 4.2vw, 42px);
    border: 1px solid color-mix(in srgb, var(--faculty-accent, var(--site-primary)) 40%, #d9deeb);
    border-radius: 14px;
    background: #f8f7f1;
    color: #20251f;
    box-shadow: 0 26px 100px rgba(0, 0, 0, .38);
    font-family: var(--site-font-body), system-ui, sans-serif;
  }
  .howto-close {
    position: absolute; top: 14px; right: 14px;
    display: grid; place-items: center;
    width: 34px; height: 34px; padding: 0;
    border: 0; border-radius: 50%;
    background: var(--faculty-accent, var(--site-primary));
    color: #fff;
    font-size: 22px; line-height: 1; font-weight: 600;
    cursor: pointer;
    box-shadow: 0 0 0 3px color-mix(in srgb, var(--faculty-accent, var(--site-primary)) 15%, transparent);
  }
  .howto-close:focus-visible, .howto-nav button:focus-visible {
    outline: 3px solid color-mix(in srgb, var(--faculty-accent, var(--site-primary)) 75%, white);
    outline-offset: 3px;
  }
  .howto-eyebrow {
    margin: 0 44px 13px 0;
    color: #586254; font-family: Manrope, Arial, Arial, sans-serif;
    font-size: 10px; font-weight: 800; letter-spacing: .14em; text-transform: uppercase;
  }
  .howto-title {
    max-width: 540px; margin: 0 42px 10px 0;
    font-size: clamp(25px, 4vw, 36px); line-height: 1.13; letter-spacing: -.045em;
    font-weight: 780;
  }
  .howto-intro {
    max-width: 545px; margin: 0 0 27px;
    color: #555d52; font-size: 13px; line-height: 1.65;
  }
  .howto-progress { display:flex; gap:5px; margin: 0 0 24px; }
  .howto-progress span {
    flex: 1; height: 3px; border-radius: 9px; background: #d9ddd2;
  }
  .howto-progress span[aria-current="step"] { background: var(--faculty-accent, var(--site-primary)); }
  .howto-step {
    min-height: 178px; padding: 22px 22px 20px;
    background: #eeeee5; border: 1px solid #dedfd4; border-left: 3px solid var(--faculty-accent, var(--site-primary));
    border-radius: 8px;
  }
  .howto-step h3 { margin: 0 0 12px; font-size: 20px; line-height: 1.3; letter-spacing: -.02em; }
  .howto-step p { margin: 0; color: #41483e; font-size: 14px; line-height: 1.75; }
  .howto-nav { display:flex; align-items:center; justify-content:space-between; gap:10px; margin-top: 22px; }
  .howto-nav button {
    min-height: 38px; padding: 9px 14px; border-radius: 6px;
    font: inherit; font-size: 12px; font-weight: 750; cursor:pointer;
  }
  .howto-prev { border: 1px solid #ccd0c3; background: transparent; color:#333a30; }
  .howto-next { border: 1px solid var(--faculty-accent, var(--site-primary)); background: var(--faculty-accent, var(--site-primary)); color:#fff; }
  .howto-prev:disabled { opacity:.35; cursor:default; }
  .howto-count { color:#697064; font: 10px Manrope, Arial, Arial, sans-serif; text-align:center; white-space:nowrap; }
  html[lang="bn"] .howto-dialog { line-height: 1.7; }
  html[lang="bn"] .howto-step h3 { line-height: 1.42; }
  html[lang="bn"] .howto-step p { line-height: 1.85; }
  @media (max-width: 540px) {
    .howto-backdrop { padding: 10px; }
    .howto-dialog { width: calc(100vw - 20px); max-height: 88vh; padding: 24px 18px 19px; border-radius: 10px; }
    .howto-close { top: 10px; right: 10px; width: 32px; height: 32px; }
    .howto-title { font-size: 25px; margin-right: 32px; }
    .howto-intro { font-size: 12px; margin-bottom: 20px; }
    .howto-step { min-height: 0; padding: 17px 15px; }
    .howto-step h3 { font-size: 18px; }
    .howto-step p { font-size: 13px; }
    .howto-nav button { padding: 8px 10px; }
  }
</style>

<div class="howto-backdrop" id="howToUseModal" data-open="false" aria-hidden="true">
  <section class="howto-dialog" role="dialog" aria-modal="true" aria-labelledby="howToUseTitle" aria-describedby="howToUseIntro" tabindex="-1">
    <button class="howto-close" id="howToUseClose" type="button" aria-label="Close guide" title="Close guide">×</button>
    <p class="howto-eyebrow" id="howToUseEyebrow">CAPABILITY COSMOS · FIELD GUIDE</p>
    <h2 class="howto-title" id="howToUseTitle">Read the field. Question the score.</h2>
    <p class="howto-intro" id="howToUseIntro">A short guided tour of the map, comparisons and evidence. You choose what to inspect; every score has a boundary.</p>
    <div class="howto-progress" id="howToUseProgress" aria-hidden="true"></div>
    <article class="howto-step" aria-live="polite">
      <h3 id="howToUseStepTitle">Choose a lens</h3>
      <p id="howToUseStepText">Switch between the five views to change what the galaxy emphasizes.</p>
    </article>
    <div class="howto-nav">
      <button class="howto-prev" id="howToUsePrev" type="button" disabled>← Back</button>
      <span class="howto-count" id="howToUseCount" aria-live="polite">01 / 07</span>
      <button class="howto-next" id="howToUseNext" type="button">Next stop →</button>
    </div>
  </section>
</div>

<!-- Right-column text is 0.4px smaller than the preceding +1px pass, i.e. +0.6px over the stylesheet baseline. -->
<script>
(function () {
  'use strict';
  const rail = document.querySelector('.right-rail');
  if (!rail) return;

  const originals = new Map();
  let scheduled = false;

  function hasDirectText(el) {
    if (el.matches('input, select, textarea, button')) return true;
    return Array.from(el.childNodes).some(node =>
      node.nodeType === Node.TEXT_NODE && node.textContent.trim().length > 0
    );
  }
  function restoreInlineFontSize(el, original) {
    if (original.value) el.style.setProperty('font-size', original.value, original.priority);
    else el.style.removeProperty('font-size');
  }
  function applyTypography() {
    scheduled = false;
    const elements = [rail, ...rail.querySelectorAll('*')];
    for (const el of elements) {
      if (!originals.has(el)) {
        originals.set(el, { value: el.style.getPropertyValue('font-size'), priority: el.style.getPropertyPriority('font-size') });
      } else restoreInlineFontSize(el, originals.get(el));
    }

    // Keep the scenario-control section at its explicitly locked dimensions.
    const isLockedScenarioText = el => Boolean(el.closest('.projection-card'));
    const isAtlasEnhancement = el => Boolean(el.closest('.atlas-action-row, .evidence-passport, .atlas-action-status, .scenario-stamp'));
    const targets = elements.filter(el => hasDirectText(el) && !isLockedScenarioText(el) && !isAtlasEnhancement(el));
    const sizes = targets.map(el => parseFloat(getComputedStyle(el).fontSize));
    targets.forEach((el, i) => {
      if (Number.isFinite(sizes[i])) {
        // Faculty titles get an extra 0.5px beyond the common +0.6px adjustment.
        const add = el.id === 'facultyName' ? 1.1 : 0.6;
        el.style.setProperty('font-size', (sizes[i] + add) + 'px', 'important');
      }
    });

    // These two actions are intended as a matched pair, so use one baseline size for both.
    const facultyEvidence = rail.querySelector('#facultySourceLink');
    const modelFinder = rail.querySelector('#takeTestLink');
    if (facultyEvidence && modelFinder) {
      const base = parseFloat(getComputedStyle(facultyEvidence).fontSize);
      if (Number.isFinite(base)) {
        const matchedSize = (base - 0.6) + 0.6;
        facultyEvidence.style.setProperty('font-size', matchedSize + 'px', 'important');
        modelFinder.style.setProperty('font-size', matchedSize + 'px', 'important');
      }
    }
  }
  function scheduleUpdate() {
    if (scheduled) return;
    scheduled = true;
    requestAnimationFrame(applyTypography);
  }
  applyTypography();
  window.addEventListener('resize', scheduleUpdate, { passive: true });
  new MutationObserver(scheduleUpdate).observe(rail, { subtree: true, childList: true, characterData: true });
})();
</script>

<script>
(function () {
  'use strict';
  const modal = document.getElementById('howToUseModal');
  const dialog = modal?.querySelector('.howto-dialog');
  const opener = document.getElementById('howToUse');
  const closeButton = document.getElementById('howToUseClose');
  const prevButton = document.getElementById('howToUsePrev');
  const nextButton = document.getElementById('howToUseNext');
  if (!modal || !dialog || !opener || !closeButton || !prevButton || !nextButton) return;

  const guide = {
    en: {
      button: 'How to use', close: 'Close guide', eyebrow: 'COGNITIVE COMPARISON ATLAS · FIELD GUIDE',
      title: 'Explore the field. Examine the evidence.',
      intro: 'A short tour of the map, comparisons and evidence. Every score has a boundary.',
      back: '← Back', next: 'Next stop →', restart: 'Start again ↻',
      steps: [
        ['Choose a lens', 'Use Field, Gaps, Path, Evidence and Impact to change the view. Each lens brings a different question forward while leaving the rest of the field available to explore.'],
        ['Explore the galaxy', 'Select a point in the galaxy or a row in the observation log. The selected human and comparison markers are equal-sized circles; other comparison points remain diamonds. Their distance shows the score gap on that test only.'],
        ['Read one capability closely', 'The right-hand panel gives the selected faculty, the human reference, the selected model or profile, the test, and a short interpretation. Treat each result as task-specific evidence, not a universal intelligence score.'],
        ['Change the comparison', 'Use “Compare with” to switch between an AI result and a task-specific animal evidence view. Animal markers show whether a study reports a result for a faculty; they do not encode scores or imply an overall species ranking.'],
        ['Try a possible future', 'Choose Slower, Steady or Faster, then move the year slider. This is a what-if scenario, not a forecast or a claim about the pace AI will actually improve. The scenario controls are paused while animal faculty estimates are selected.'],
        ['Read the patterns, not just the leader', 'The impact cards explain where benchmark results may matter and where real-world context is missing. The watchlist surfaces close numerical results; close numbers still may come from different tests or samples.'],
        ['Check the evidence trail', 'Use the source and method links in the right-hand column to inspect how a score was produced. This prototype contains a manually compiled snapshot, not a live feed, so verify the original source, test version, date and whether the results are truly comparable before relying on a claim.'],
        ['Adjust the layout (optional)', 'Turn on Adjust layout to resize the right-hand panels for your screen. Reset sizes restores their default proportions. This changes the layout, not the scores or evidence.']
      ]
    },
    bn: {
      button: 'ব্যবহারবিধি', close: 'নির্দেশিকা বন্ধ করুন', eyebrow: 'কগনিটিভ তুলনা অ্যাটলাস · ব্যবহার নির্দেশিকা',
      title: 'মানচিত্রটি পড়ুন। স্কোরকেও প্রশ্ন করুন।',
      intro: 'মানচিত্র, তুলনা ও প্রমাণ বোঝার সংক্ষিপ্ত পথনির্দেশ। কী দেখবেন, তা আপনি ঠিক করবেন; প্রতিটি স্কোরেরই নিজস্ব সীমা আছে।',
      back: '← পেছনে', next: 'পরের ধাপ →', restart: 'শুরু থেকে দেখুন ↻',
      steps: [
        ['দৃষ্টিভঙ্গি বেছে নিন', 'ক্ষেত্র, ব্যবধান, পথ, প্রমাণ ও প্রভাবের দৃশ্য বেছে নিন। প্রতিটি দৃশ্য আলাদা প্রশ্নকে সামনে আনে, তবে অন্য দৃশ্যেও যেকোনো সময় যাওয়া যায়।'],
        ['গ্যালাক্সি ঘুরে দেখুন', 'গ্যালাক্সির কোনো চিহ্নে বা পর্যবেক্ষণ তালিকার কোনো সারিতে ক্লিক করুন। নির্বাচিত মানব-রেফারেন্স ও তুলনার চিহ্ন সমান মাপের বৃত্ত; অন্য তুলনা-বিন্দু রম্বস। দূরত্ব শুধু সেই পরীক্ষার স্কোর-ব্যবধান দেখায়।'],
        ['একটি সক্ষমতা বুঝে দেখুন', 'ডান পাশের প্যানেলে নির্বাচিত সক্ষমতা, মানব-রেফারেন্স, নির্বাচিত মডেল বা প্রোফাইল, ব্যবহৃত পরীক্ষা এবং সংক্ষিপ্ত ব্যাখ্যা পাবেন। প্রতিটি ফল নির্দিষ্ট কাজের প্রমাণ; এটি বুদ্ধিমত্তার সর্বজনীন স্কেল নয়।'],
        ['তুলনার বিষয় বদলান', '“তুলনা করুন” তালিকা থেকে এআই-এর ফল বা প্রাণী-সংক্রান্ত গবেষণালব্ধ তথ্য বেছে নিন। প্রাণীর চিহ্নগুলো গবেষণার ধরন ও প্রমাণের ভিত্তি বোঝায়; এগুলো প্রজাতির সামগ্রিক বৈজ্ঞানিক র‍্যাঙ্কিং নয়।'],
        ['সম্ভাব্য ভবিষ্যৎ দেখুন', 'ধীর, মাঝারি বা দ্রুত অগ্রগতির দৃশ্য বেছে নিয়ে বছরের স্লাইডার সরান। এটি “এমন হলে কী হতে পারে” ধরনের উদাহরণ, পূর্বাভাস নয়; এআই বাস্তবে এই গতিতেই এগোবে, এমন দাবিও নয়। প্রাণী-প্রোফাইল বেছে নিলে এই নিয়ন্ত্রণগুলো ব্যবহার করা যাবে না।'],
        ['শুধু এগিয়ে থাকা স্কোর নয়, প্রেক্ষাপটও দেখুন', 'প্রভাব-কার্ডগুলো দেখায় পরীক্ষার ফল কোথায় কাজে লাগতে পারে এবং বাস্তব জীবনের কোন বিষয়গুলো পরীক্ষায় ধরা পড়ে না। পর্যবেক্ষণ তালিকায় কাছাকাছি স্কোর দেখা যায়; কিন্তু স্কোর কাছাকাছি হলেই পরীক্ষা বা নমুনা এক হয়ে যায় না।'],
        ['প্রমাণের সূত্র যাচাই করুন', 'ডান পাশের উৎস ও পদ্ধতির লিংক দিয়ে স্কোর কীভাবে এসেছে, তা যাচাই করুন। এই প্রোটোটাইপে হাতে সংকলিত একটি নির্দিষ্ট সময়ের তথ্য-স্ন্যাপশট আছে, সরাসরি হালনাগাদ তথ্য নয়। কোনো দাবি ব্যবহারের আগে মূল উৎস, পরীক্ষার সংস্করণ, তারিখ এবং দুটি ফল সত্যিই তুলনাযোগ্য কি না যাচাই করুন।'],
        ['বিন্যাস বদলান (ঐচ্ছিক)', 'বিন্যাস বদলানোর নিয়ন্ত্রণ চালু করে ডান পাশের অংশগুলোর মাপ পর্দা অনুযায়ী সাজাতে পারেন। মাপ আগের অবস্থায় ফেরানোর বোতাম আগের মাপ ফিরিয়ে আনে। এতে শুধু বিন্যাস বদলায়, স্কোর বা প্রমাণ নয়।']
      ]
    }
  };
  let index = 0;
  let returnFocus = null;
  function currentLang() { return document.documentElement.lang === 'bn' ? 'bn' : 'en'; }
  function accentColor() {
    return getComputedStyle(document.documentElement).getPropertyValue('--faculty-accent').trim()
      || getComputedStyle(document.documentElement).getPropertyValue('--site-primary').trim()
      || '#526b2c';
  }
  function setCloseContrast() {
    const color = accentColor();
    closeButton.style.backgroundColor = color;
    const hex = color.match(/^#([\da-f]{3}|[\da-f]{6})$/i);
    if (hex) {
      let value = hex[1];
      if (value.length === 3) value = value.split('').map(ch => ch + ch).join('');
      const rgb = [0, 2, 4].map(offset => parseInt(value.slice(offset, offset + 2), 16) / 255).map(v => v <= .04045 ? v / 12.92 : Math.pow((v + .055) / 1.055, 2));
      const luminance = .2126 * rgb[0] + .7152 * rgb[1] + .0722 * rgb[2];
      closeButton.style.color = luminance > .43 ? '#161914' : '#ffffff';
    } else closeButton.style.color = '#ffffff';
  }
  function render() {
    const c = guide[currentLang()];
    const step = c.steps[index];
    document.getElementById('howToUse').textContent = c.button;
    closeButton.setAttribute('aria-label', c.close);
    closeButton.title = c.close;
    document.getElementById('howToUseEyebrow').textContent = c.eyebrow;
    document.getElementById('howToUseTitle').textContent = c.title;
    document.getElementById('howToUseIntro').textContent = c.intro;
    document.getElementById('howToUseStepTitle').textContent = step[0];
    document.getElementById('howToUseStepText').textContent = step[1];
    prevButton.textContent = c.back;
    prevButton.disabled = index === 0;
    nextButton.textContent = index === c.steps.length - 1 ? c.restart : c.next;
    const bnDigits = value => String(value).replace(/[0-9]/g, digit => '০১২৩৪৫৬৭৮৯'[Number(digit)]);
    document.getElementById('howToUseCount').textContent = currentLang() === 'bn' ? bnDigits(String(index + 1).padStart(2, '0') + ' / ' + String(c.steps.length).padStart(2, '0')) : String(index + 1).padStart(2, '0') + ' / ' + String(c.steps.length).padStart(2, '0');
    const progress = document.getElementById('howToUseProgress');
    progress.innerHTML = '';
    c.steps.forEach((_, i) => {
      const segment = document.createElement('span');
      if (i === index) segment.setAttribute('aria-current', 'step');
      progress.appendChild(segment);
    });
    setCloseContrast();
  }
  function open() {
    index = 0;
    returnFocus = document.activeElement;
    render();
    modal.dataset.open = 'true';
    modal.setAttribute('aria-hidden', 'false');
    document.body.style.overflow = 'hidden';
    closeButton.focus();
  }
  function close() {
    modal.dataset.open = 'false';
    modal.setAttribute('aria-hidden', 'true');
    document.body.style.overflow = '';
    if (returnFocus && typeof returnFocus.focus === 'function') returnFocus.focus();
  }
  opener.addEventListener('click', open);
  closeButton.addEventListener('click', close);
  modal.addEventListener('click', event => { if (event.target === modal) close(); });
  prevButton.addEventListener('click', () => { index = Math.max(0, index - 1); render(); });
  nextButton.addEventListener('click', () => { index = index === guide[currentLang()].steps.length - 1 ? 0 : index + 1; render(); });
  document.addEventListener('keydown', event => {
    if (modal.dataset.open !== 'true') return;
    if (event.key === 'Escape') { event.preventDefault(); close(); return; }
    if (event.key === 'ArrowRight') { event.preventDefault(); index = index === guide[currentLang()].steps.length - 1 ? 0 : index + 1; render(); return; }
    if (event.key === 'ArrowLeft') { event.preventDefault(); index = Math.max(0, index - 1); render(); return; }
    if (event.key === 'Tab') {
      const focusable = Array.from(dialog.querySelectorAll('button:not(:disabled)'));
      const first = focusable[0], last = focusable[focusable.length - 1];
      if (event.shiftKey && document.activeElement === first) { event.preventDefault(); last.focus(); }
      else if (!event.shiftKey && document.activeElement === last) { event.preventDefault(); first.focus(); }
    }
  });
  document.getElementById('languageToggle').addEventListener('click', () => {
    render();
  });
  // Keep the chosen faculty's color on the close control while the guide is open.
  const observer = new MutationObserver(() => { if (modal.dataset.open === 'true') setCloseContrast(); });
  observer.observe(document.documentElement, { attributes: true, attributeFilter: ['style'] });
  render();
})();
</script>

<style id="ccAtlasV10Overrides">
  /* The intended two-font system takes precedence over preview-theme defaults. */
  :root {
    --site-font-body: 'Manrope', Arial, sans-serif !important;
    --site-font-heading: 'Space Grotesk', Arial, sans-serif !important;
  }
  .mode-pill { text-transform: none !important; }

  /* The guide inherits the site's clean paper surface. */
  .howto-dialog {
    background: #fff !important;
    color: #17191f !important;
    border-color: #dfe3e9 !important;
    font-family: 'Manrope', Arial, sans-serif !important;
  }
  .howto-step {
    background: #f7f6f2 !important;
    color: #17191f !important;
    border-color: #e1e4e9 !important;
  }
  .howto-step p { color: #4e5663 !important; }
  .howto-eyebrow, .howto-count { font-family: 'Manrope', Arial, sans-serif !important; }

  /* Widen the human-reference note slightly so the same copy occupies fewer lines. */
  @media (min-width: 1100px) {
    .right-rail .model-block { grid-template-columns: minmax(0, 1.08fr) minmax(0, .92fr); column-gap: 8px; }
  }

  /* -1px headline reduction at each responsive size, for English and Bangla alike. */
  @media (min-width: 1100px) {
    .galaxy-title { font-size: clamp(30px, calc(3.3vw - 1px), 48px) !important; }
  }
  @media (max-width: 1099px) and (min-width: 761px) {
    .galaxy-title { font-size: clamp(26px, calc(3.3vw - 1px), 39px) !important; }
  }
  @media (max-width: 760px) {
    .galaxy-title { font-size: clamp(23px, calc(6vw - 1px), 33px) !important; }
  }
  @media (max-height: 850px) and (min-width: 761px) {
    .galaxy-title { font-size: clamp(26px, calc(2.8vw - 1px), 39px) !important; }
  }

  .site-credit {
    position: fixed;
    left: 12px;
    bottom: 4px;
    z-index: 999;
    pointer-events: none;
    color: #777b84;
    opacity: .68;
    font-family: 'Space Grotesk', Arial, sans-serif !important;
    font-size: 8px !important;
    font-weight: 400;
    letter-spacing: .01em;
    line-height: 1;
    white-space: nowrap;
  }
  @media (max-width: 760px) {
    .site-credit { left: 8px; bottom: 3px; font-size: 7px !important; }
  }
</style>
<div id="siteCredit" class="site-credit" aria-label="Developed by Wasi Uz Zaman, version 1.0">Developed by Wasi Uz Zaman · V1.0</div>
<script id="ccAtlasV10Runtime">
(function () {
  'use strict';

  // Keep the badge's brand format while translating its descriptor with the active locale.
  const atlasBadge = document.getElementById('projectionMode');
  if (atlasBadge) {
    const lockAtlasBadge = () => {
      const next = document.documentElement.lang === 'bn' ? 'CC ATLAS · মানুষকেন্দ্রিক' : 'CC ATLAS · Human-centered';
      if (atlasBadge.textContent.trim() !== next) atlasBadge.textContent = next;
    };
    lockAtlasBadge();
    new MutationObserver(lockAtlasBadge).observe(document.documentElement, { attributes: true, attributeFilter: ['lang'] });
    new MutationObserver(lockAtlasBadge).observe(atlasBadge, { childList: true, characterData: true, subtree: true });
  }

  // Increase each right-column text element by 0.2px without flattening its existing hierarchy.
  const rail = document.querySelector('.right-rail');
  if (rail) {
    function bumpRailFonts() {
      const targets = Array.from(rail.querySelectorAll('*')).filter(el =>
        Array.from(el.childNodes).some(node => node.nodeType === Node.TEXT_NODE && node.nodeValue.trim())
      );
      targets.forEach(el => {
        if (!el.dataset.ccV10OriginalFontSize) {
          el.dataset.ccV10OriginalFontSize = el.style.fontSize || '__none__';
        }
        const originalInline = el.dataset.ccV10OriginalFontSize;
        if (originalInline === '__none__') el.style.removeProperty('font-size');
        else el.style.fontSize = originalInline;
      });
      const sizes = targets.map(el => ({ el, size: parseFloat(getComputedStyle(el).fontSize) }));
      sizes.forEach(({el, size}) => {
        if (Number.isFinite(size)) el.style.fontSize = (size + 0.2).toFixed(2) + 'px';
      });
    }
    bumpRailFonts();
    window.addEventListener('resize', bumpRailFonts, { passive: true });
    const railTextObserver = new MutationObserver(() => bumpRailFonts());
    railTextObserver.observe(rail, { childList: true, characterData: true, subtree: true });
  }
})();
</script>


<style id="ccAtlasV11Refinements">
  /* Reference caveat gets more horizontal room; its complete content remains visible. */
  @media (min-width:1100px) {
    .right-rail .model-block {
      grid-template-columns:minmax(0,1.22fr) minmax(0,.78fr) !important;
      column-gap:8px !important;
      row-gap:2px !important;
    }
    .right-rail .model-block > .reference-caveat {
      grid-column:1 / -1 !important;
      display:block !important;
      min-width:0;
      height:auto !important;
      max-height:none !important;
      overflow:visible !important;
      white-space:normal !important;
      -webkit-line-clamp:unset !important;
      line-clamp:unset !important;
      padding:4px 6px !important;
      line-height:1.24 !important;
    }
    .right-rail .model-block > .everyday-meaning {
      padding-top:4px !important;
      padding-left:7px !important;
    }
  }

  /* The sphere legend names the active territory and explains it in one sentence. */
  .legend .territory-legend-item {
    align-items:flex-start !important;
    gap:5px !important;
    max-width:185px;
    min-width:0;
  }
  .legend .territory-legend-item > .territory-key {
    flex:0 0 6px;
    margin-top:3px;
    width:6px;
    height:6px;
    border-radius:50%;
    background:var(--faculty-accent) !important;
    box-shadow:0 0 0 2px var(--faculty-accent-soft);
  }
  .legend .territory-legend-copy {
    display:flex !important;
    flex-direction:column;
    align-items:flex-start !important;
    gap:2px !important;
    min-width:0;
    white-space:normal;
  }
  .legend #legendTerritory {
    display:block;
    color:var(--faculty-accent) !important;
    font-size:8px;
    font-weight:750;
    line-height:1.15;
    white-space:normal;
  }
  .legend #legendTerritoryDesc {
    display:block;
    max-width:168px;
    color:#586171;
    font-size:8px;
    font-weight:400;
    line-height:1.2;
    white-space:normal;
  }

  /* Center the two useful methods links and remove the third, redundant source option. */
  @media (min-width:1100px) {
    .right-rail .data-note {
      grid-template-columns:12px minmax(0,1fr) !important;
      grid-template-rows:auto auto;
      align-items:start;
      row-gap:5px !important;
    }
    .right-rail .data-note > .data-links {
      grid-column:2 / -1 !important;
      grid-row:2;
      justify-self:stretch;
      align-self:center;
    }
  }
  .right-rail .data-links {
    display:flex !important;
    flex-direction:row !important;
    flex-wrap:wrap !important;
    justify-content:center !important;
    align-items:center !important;
    gap:8px 14px !important;
    width:100%;
    text-align:center;
  }
  .right-rail .data-links #sourceLink { display:none !important; }
  .right-rail .data-links a {
    max-width:100%;
    text-align:center !important;
    white-space:normal;
    line-height:1.25;
  }

  /* Compact, comfortable information tooltip next to the calibration mark. */
  .right-rail .projection-card > .calibration-strip .calibration-tooltip {
    width:min(215px,calc(100vw - 32px)) !important;
    max-width:215px !important;
    padding:7px 8px !important;
    background:#fff !important;
    color:#30343b !important;
    font-size:9px !important;
    line-height:1.35 !important;
  }
  .right-rail .projection-card > .calibration-strip #calibrationText {
    margin:0 !important;
    white-space:normal !important;
  }
  .right-rail .projection-card > .calibration-strip .calibration-mark {
    cursor:help;
  }
  .right-rail .impactSub { color:#292d35; }

  @media (max-width:1099px) {
    .legend .territory-legend-item { max-width:155px; }
    .legend #legendTerritoryDesc { max-width:140px; }
    .right-rail .data-links { gap:7px 12px !important; }
  }
  @media (max-width:760px) {
    .legend .territory-legend-item { max-width:145px; }
    .legend #legendTerritoryDesc { max-width:130px; font-size:7px; }
    .right-rail .data-links { justify-content:flex-start !important; }
  }
</style>


<style id="ccAtlasV11Mobile">
  @media (max-width:760px) {
    html, body, #app {
      width:100% !important;
      height:auto !important;
      min-height:100% !important;
      overflow-x:hidden !important;
      overflow-y:auto !important;
    }
    body { min-height:100svh !important; }
    #app { min-height:100svh !important; }
    .shell {
      height:auto !important;
      min-height:100svh !important;
      overflow:visible !important;
      padding:12px 12px 34px !important;
    }
    .cosmos-layout {
      display:grid !important;
      grid-template-columns:minmax(0,1fr) !important;
      grid-template-rows:none !important;
      grid-template-areas:none !important;
      grid-auto-rows:auto !important;
      align-content:start !important;
      gap:14px !important;
      width:100% !important;
      height:auto !important;
      min-height:0 !important;
      overflow:visible !important;
    }
    .stage-column {
      display:flex !important;
      min-width:0 !important;
      min-height:0 !important;
      height:auto !important;
      overflow:visible !important;
    }
    .galaxy-panel {
      display:flex !important;
      flex:0 0 auto !important;
      min-height:0 !important;
      height:auto !important;
      overflow:visible !important;
    }
    .galaxy-head {
      position:relative !important;
      display:flex !important;
      flex-direction:column !important;
      align-items:stretch !important;
      gap:9px !important;
      padding:6px 0 8px !important;
      width:100% !important;
    }
    .galaxy-head > div:first-child {
      width:100% !important;
      max-width:100% !important;
      min-width:0 !important;
    }
    .galaxy-title {
      display:block !important;
      max-width:100% !important;
      white-space:normal !important;
      font-size:clamp(25px,7.5vw,34px) !important;
      line-height:.98 !important;
      letter-spacing:-.05em !important;
      text-wrap:balance;
    }
    .stage-actions {
      position:static !important;
      display:flex !important;
      flex-direction:column !important;
      align-items:stretch !important;
      justify-content:flex-start !important;
      gap:5px !important;
      width:100% !important;
      max-width:100% !important;
      min-width:0 !important;
    }
    .view-controls {
      display:flex !important;
      flex-direction:column !important;
      align-items:stretch !important;
      width:100% !important;
      max-width:100% !important;
      min-width:0 !important;
      gap:4px !important;
    }
    .view-controls .mode-pill { align-self:flex-start !important; width:auto !important; }
    .view-controls .mode-switch {
      display:grid !important;
      grid-template-columns:repeat(5,minmax(0,1fr)) !important;
      width:100% !important;
      margin:0 !important;
      gap:2px !important;
      order:0 !important;
    }
    .view-controls .mode-switch button {
      min-width:0 !important;
      padding:7px 1px !important;
      font-size:8px !important;
      white-space:normal !important;
    }
    .zoom-controls {
      display:flex !important;
      justify-content:flex-start !important;
      align-items:center !important;
      width:100% !important;
      max-width:100% !important;
      flex-wrap:wrap !important;
      gap:4px !important;
    }
    .galaxy-subtitle { display:none !important; }
    .activity-log {
      width:100% !important;
      max-width:100% !important;
      max-height:none !important;
      margin:0 0 6px !important;
      overflow:visible !important;
    }
    .activity-entries { grid-template-columns:repeat(2,minmax(0,1fr)) !important; gap:0 10px !important; }
    .activity-entry { min-width:0 !important; grid-template-columns:17px minmax(0,1fr) auto !important; gap:4px !important; }
    .canvas-wrap {
      flex:0 0 auto !important;
      height:min(64svh,520px) !important;
      min-height:360px !important;
      max-height:520px !important;
      overflow:hidden !important;
    }
    .legend {
      left:8px !important;
      right:52px !important;
      bottom:8px !important;
      max-width:none !important;
      justify-content:flex-start !important;
      flex-wrap:wrap !important;
      gap:5px 7px !important;
      padding:6px !important;
      font-size:8px !important;
    }
    .legend .territory-legend-item { max-width:145px !important; }
    .legend #legendTerritoryDesc { max-width:136px !important; font-size:7.5px !important; }
    .journey-trigger { width:38px !important; height:38px !important; right:5px !important; bottom:5px !important; }
    .right-rail {
      display:flex !important;
      flex-direction:column !important;
      gap:14px !important;
      width:100% !important;
      height:auto !important;
      min-height:0 !important;
      overflow:visible !important;
      border-left:0 !important;
      padding:0 !important;
    }
    .right-rail > .metrics { order:0 !important; }
    .right-rail .rail-row-resize,
    .right-rail .rail-column-resize { display:none !important; }
    .right-rail > .sidepanel { order:1 !important; grid-template-rows:none !important; grid-template-areas:none !important; }
    .right-rail > .impact-section { order:2 !important; }
    .right-rail > .watch-section { order:3 !important; }
    .right-rail > .data-note { order:4 !important; }
    .right-rail > .metrics { display:grid !important; grid-template-columns:repeat(2,minmax(0,1fr)) !important; width:100% !important; }
    .right-rail .metric { min-width:0 !important; padding:10px 8px !important; }
    .right-rail .metric-label { font-size:8px !important; }
    .right-rail .metric-value { font-size:22px !important; }
    .right-rail .metric-foot { font-size:8px !important; line-height:1.25 !important; }
    .right-rail > .sidepanel {
      display:grid !important;
      grid-template-columns:minmax(0,1fr) !important;
      gap:12px !important;
      width:100% !important;
      height:auto !important;
      min-height:0 !important;
      overflow:visible !important;
    }
    .right-rail .inspector, .right-rail .projection-card {
      display:block !important;
      width:100% !important;
      height:auto !important;
      min-height:0 !important;
      overflow:visible !important;
      padding:13px 0 !important;
    }
    .right-rail .faculty-name { font-size:clamp(21px,5.6vw,27px) !important; white-space:normal !important; }
    .right-rail .faculty-desc { font-size:11px !important; line-height:1.45 !important; display:block !important; overflow:visible !important; -webkit-line-clamp:unset !important; }
    .right-rail .compare-line { grid-template-columns:minmax(70px,.8fr) minmax(0,1fr) 34px !important; font-size:9px !important; }
    .right-rail .model-block { display:grid !important; grid-template-columns:minmax(0,1fr) !important; row-gap:5px !important; }
    .right-rail .model-block > .small-label,
    .right-rail .model-block > .model-name,
    .right-rail .model-block > .model-source,
    .right-rail .model-block > .reference-caveat,
    .right-rail .model-block > .everyday-meaning,
    .right-rail .model-block > .source-inline,
    .right-rail .model-block > .test-inline { grid-column:1 / -1 !important; }
    .right-rail .model-block > .reference-caveat {
      display:block !important;
      width:100% !important;
      font-size:9.5px !important;
      line-height:1.4 !important;
      padding:7px 8px !important;
      overflow:visible !important;
      max-height:none !important;
      -webkit-line-clamp:unset !important;
    }
    .right-rail .everyday-meaning { margin-top:4px !important; padding:8px 0 0 !important; border-top:1px solid #e4e8ef !important; border-left:0 !important; }
    .right-rail .everyday-meaning p { font-size:10px !important; line-height:1.45 !important; display:block !important; max-height:none !important; overflow:visible !important; -webkit-line-clamp:unset !important; }
    .right-rail .projection-title { font-size:12px !important; white-space:normal !important; }
    .right-rail .projection-explain { display:block !important; font-size:10px !important; line-height:1.45 !important; }
    .right-rail .scenario { font-size:9px !important; padding:8px 4px !important; }
    .right-rail .result-main { font-size:12px !important; white-space:normal !important; }
    .right-rail .result-sub { font-size:9px !important; line-height:1.4 !important; }
    .right-rail .calibration-strip { display:grid !important; grid-template-columns:14px minmax(0,1fr) !important; margin:0 0 10px !important; padding:0 0 10px !important; }
    .right-rail .calibration-strip .calibration-mark { width:14px !important; height:14px !important; }
    .right-rail .calibration-strip p { font-size:10px !important; line-height:1.4 !important; }
    .right-rail .data-note {
      display:grid !important;
      grid-template-columns:18px minmax(0,1fr) !important;
      grid-template-rows:auto auto !important;
      gap:6px !important;
      padding:10px 0 !important;
      overflow:visible !important;
    }
    .right-rail .data-note p { font-size:10px !important; line-height:1.4 !important; display:block !important; overflow:visible !important; -webkit-line-clamp:unset !important; }
    .right-rail .data-note > .data-links { grid-column:2 / -1 !important; grid-row:2 !important; justify-content:flex-start !important; }
    .right-rail .impact-section, .right-rail .watch-section { height:auto !important; min-height:0 !important; overflow:visible !important; }
    .right-rail .impact-grid { grid-template-columns:minmax(0,1fr) !important; }
    .right-rail .impact { padding:12px 0 !important; }
    .right-rail .impact h3 { font-size:14px !important; white-space:normal !important; }
    .right-rail .impact p, .right-rail .watch-intro p { font-size:10px !important; line-height:1.45 !important; display:block !important; }
    .right-rail .watch-list { grid-template-columns:minmax(0,1fr) !important; }
    .right-rail .watch-item { padding:9px 0 !important; }
    .site-credit {
      position:static !important;
      display:block;
      margin:10px 0 0 2px;
      font-size:8px !important;
      opacity:.72;
    }
  }
</style>


<style id="atlasV17ControlAndGuideRefinements">
  .atlas-action-row { display:grid !important; grid-template-columns:minmax(0,1fr) minmax(0,1fr); align-items:stretch; gap:7px; width:100%; }
  .atlas-action-row > .atlas-action,
  .atlas-action-row .evidence-hover-wrap > .atlas-action { width:100% !important; min-width:0 !important; min-height:34px !important; height:34px !important; max-height:34px !important; padding:6px 8px !important; white-space:nowrap !important; overflow:hidden; text-overflow:ellipsis; }
  .evidence-hover-wrap { position:relative; display:block; min-width:0; width:100%; }
  .evidence-passport { display:none; position:absolute; z-index:9999; bottom:calc(100% + 8px); right:0; width:min(265px,calc(100vw - 36px)); max-height:210px; overflow:hidden; box-sizing:border-box; padding:10px 12px; border:1px solid #dfe3e9; border-radius:7px; background:#fff !important; color:#30343b !important; box-shadow:0 10px 28px rgba(20,24,32,.18); white-space:normal; pointer-events:none; }
  .evidence-hover-wrap:hover .evidence-passport,
  .evidence-hover-wrap:focus-within .evidence-passport { display:block; }
  .evidence-passport-heading { display:block; margin:0 0 6px; color:#252b39; font:750 10px/1.35 'Manrope',Arial,sans-serif; }
  .evidence-passport-content { display:block; margin:0; padding-left:15px; color:#485163; font:500 9px/1.42 'Manrope',Arial,sans-serif; }
  .evidence-passport-content li { margin:0 0 4px; overflow-wrap:anywhere; }
  .evidence-passport-content li:last-child { margin-bottom:0; }
  .atlas-action-status { min-height:0; }
  .right-rail .selection-switchers .comparator-switcher { padding-bottom:7px; border-bottom:1px solid color-mix(in srgb,var(--faculty-accent) 22%,#fff); }
  .right-rail .selection-switchers .comparator-switcher label { display:flex; grid-column:auto; }
  .howto-dialog { max-height:min(80vh,640px) !important; padding:22px clamp(20px,3.4vw,32px) 18px !important; background:#fff !important; color:#20251f !important; }
  .howto-eyebrow { margin-bottom:8px !important; }
  .howto-title { font-size:clamp(23px,3.2vw,31px) !important; line-height:1.12 !important; margin-bottom:7px !important; }
  .howto-intro { margin-bottom:14px !important; line-height:1.5 !important; }
  .howto-progress { margin-bottom:12px !important; }
  .howto-step { min-height:0 !important; padding:14px 16px 13px !important; background:var(--faculty-accent-soft,#f7f6f2) !important; }
  .howto-step h3 { margin-bottom:6px !important; font-size:17px !important; line-height:1.3 !important; }
  .howto-step p { font-size:12.5px !important; line-height:1.55 !important; }
  .howto-nav { margin-top:13px !important; }
  html[lang="bn"] .howto-step h3 { line-height:1.4 !important; }
  html[lang="bn"] .howto-step p { line-height:1.65 !important; }
  @media (max-width:760px) {
    .atlas-action-row { gap:6px; }
    .atlas-action-row > .atlas-action,
    .atlas-action-row .evidence-hover-wrap > .atlas-action { padding:5px 5px !important; font-size:7.8px !important; }
    .evidence-passport { right:0; width:min(250px,calc(100vw - 28px)); max-height:190px; }
    .howto-dialog { max-height:84vh !important; padding:18px 15px 14px !important; }
    .howto-intro { margin-bottom:11px !important; }
    .howto-progress { margin-bottom:9px !important; }
    .howto-step { padding:12px 12px 11px !important; }
    .howto-step p { font-size:12px !important; line-height:1.55 !important; }
    .howto-nav { margin-top:11px !important; }
  }
  @media (prefers-reduced-motion:reduce) { .atlas-action-row .atlas-action { transition:none !important; } }
</style>


<script id="atlasV17StrictLocalization">
(function(){
  const $ = (sel) => document.querySelector(sel);
  const txt = (sel, value) => { const el = $(sel); if (el) el.textContent = value; };
  const sync = () => {
    const bn = document.documentElement.lang === 'bn';
    document.title = bn ? 'কগনিটিভ তুলনা অ্যাটলাস | মানুষকেন্দ্রিক সক্ষমতার মানচিত্র' : 'Cognitive Comparison Atlas | Human-centred capability map';
    txt('#heroEyebrow', bn ? 'মানুষ ও যন্ত্রের বুদ্ধিমত্তা' : 'Human × machine intelligence');
    const title = $('#heroTitle');
    if (title) title.innerHTML = bn ? 'মানুষের মহাবিশ্বে <span class="gradient" id="heroTitleAccent">এআই কোথায়?</span>' : 'Where does AI sit<br>in the <span class="gradient" id="heroTitleAccent">human universe?</span>';
    txt('#heroCopy', bn ? 'দশটি জ্ঞানীয় সক্ষমতা জুড়ে তুলনা ঘুরে দেখুন। প্রতিটি মডেল-চিহ্ন মানব-তুলনার পাশে দেখানো হয়েছে, যাতে বোঝা যায় কোন কাজে এআই এগিয়ে, কোথায় মানুষ এগিয়ে এবং কোথায় ব্যবধান কম।' : 'Explore the frontier across ten cognitive faculties. Each model marker is positioned against a human reference, so you can see where AI leads, where people lead, and where the gap is still small.');
    txt('#heroNoteTitle', bn ? 'একটি মানচিত্র। বুদ্ধিমত্তার দুই রূপ।' : 'One map. Two kinds of intelligence.');
    txt('#heroNoteText', bn ? 'গ্যালাক্সি ঘোরান, একটি বিন্দু বেছে নিন, তারপর ভবিষ্যৎ-দৃশ্য বদলে দেখুন আজকের ব্যবধান কীভাবে বদলাতে পারে। বর্তমানের পরের অংশটি কেবল একটি সম্ভাব্য দৃশ্য, পূর্বাভাস নয়।' : 'Drag the cosmos, select a star, then change the future scenario to see how today’s gaps could move. Past the present, the display is a transparent what-if, not a prediction.');
    txt('#feedbackIdea', bn ? 'মতামত · ধারণা' : 'Feedback · Idea');
    txt('#comparatorLabel', bn ? 'তুলনা করুন' : 'COMPARE WITH');
    txt('#atlasDownloadCard', bn ? 'নিজের জন্য কপি সংরক্ষণ করুন' : 'Save a copy for you');
    txt('#atlasEvidencePassport', bn ? 'প্রমাণের বিবরণ দেখুন' : 'See evidence passport');
    txt('#projectionMode', bn ? 'CC ATLAS · মানুষকেন্দ্রিক' : 'CC ATLAS · Human-centered');
    const comparatorOptions = bn ? ['কৃত্রিম বুদ্ধিমত্তা (এআই)','শিম্পাঞ্জি','কুকুর','মৌমাছি'] : ['Artificial Intelligence (AI)','Chimpanzee','Dog','Honeybee'];
    const options = $('#comparatorSelect');
    if (options) Array.from(options.options).forEach((option, i) => { if (comparatorOptions[i]) option.textContent = comparatorOptions[i]; });
    const howto = $('#howToUse');
    if (howto) { howto.textContent = bn ? 'ব্যবহারবিধি' : 'How to use'; howto.setAttribute('aria-label', bn ? 'ব্যবহারবিধি দেখুন' : 'Open the guide'); howto.title = bn ? 'ব্যবহারবিধি দেখুন' : 'Open the guide'; }
    const toggle = $('#languageToggle');
    if (toggle) { toggle.textContent = bn ? 'English' : 'বাংলা'; toggle.setAttribute('aria-label', bn ? 'ভাষা ইংরেজিতে বদলান' : 'Switch language to Bangla'); toggle.title = bn ? 'ভাষা ইংরেজিতে বদলান' : 'Switch language to Bangla'; toggle.setAttribute('aria-pressed', String(bn)); }
    const credit = $('#siteCredit');
    if (credit) { credit.textContent = bn ? 'নির্মাণ: Wasi Uz Zaman · সংস্করণ ১.০' : 'Built by Wasi Uz Zaman · V1.0'; credit.setAttribute('aria-label', bn ? 'নির্মাণ করেছেন Wasi Uz Zaman, সংস্করণ ১.০' : 'Built by Wasi Uz Zaman, version 1.0'); }
    const prevC = $('#prevComparator'), nextC = $('#nextComparator');
    if (prevC) { prevC.setAttribute('aria-label', bn ? 'আগের তুলনা' : 'Previous comparison'); prevC.title = bn ? 'আগের তুলনা' : 'Previous comparison'; }
    if (nextC) { nextC.setAttribute('aria-label', bn ? 'পরের তুলনা' : 'Next comparison'); nextC.title = bn ? 'পরের তুলনা' : 'Next comparison'; }
    const prevF = $('#prevFaculty'), nextF = $('#nextFaculty');
    if (prevF) { prevF.setAttribute('aria-label', bn ? 'আগের সক্ষমতা' : 'Previous faculty'); prevF.title = bn ? 'আগের সক্ষমতা' : 'Previous faculty'; }
    if (nextF) { nextF.setAttribute('aria-label', bn ? 'পরের সক্ষমতা' : 'Next faculty'); nextF.title = bn ? 'পরের সক্ষমতা' : 'Next faculty'; }
    const canvas = $('#cosmos');
    if (canvas) canvas.setAttribute('aria-label', bn ? 'ইন্টার‌্যাকটিভ গ্যালাক্সি। তীরচিহ্ন দিয়ে সক্ষমতা বদলান, প্লাস ও মাইনাস দিয়ে জুম করুন। বিস্তারিত দেখতে একটি চিহ্ন বেছে নিন।' : 'Interactive galaxy. Use arrow keys to change faculty, plus and minus to zoom. Select a marker for details.');
    const labels = [
      ['#resetView',bn?'দৃশ্য আগের অবস্থায় ফেরান':'Reset view'],
      ['#facultySelect',null],['#comparatorSelect',null],['#horizon',null]
    ];
    labels.forEach(([sel,val])=>{ const el=$(sel); if(!el) return; if(val){if(el.tagName==='BUTTON' && !['zoomIn','zoomOut'].includes(el.id))el.textContent=val;el.setAttribute('aria-label',val);el.title=val;} });
    const zoomIn = $('#zoomIn'), zoomOut = $('#zoomOut');
    if (zoomIn) { zoomIn.textContent = '+'; zoomIn.setAttribute('aria-label', bn ? 'জুম বাড়ান' : 'Zoom in'); zoomIn.removeAttribute('title'); }
    if (zoomOut) { zoomOut.textContent = '−'; zoomOut.setAttribute('aria-label', bn ? 'জুম কমান' : 'Zoom out'); zoomOut.removeAttribute('title'); }
    if (bn) {
      const modeLabels = ['ক্ষেত্র','ব্যবধান','পথ','প্রমাণ','প্রভাব'];
      document.querySelectorAll('.mode-switch button').forEach((b,i)=>{ if(modeLabels[i]) b.textContent=modeLabels[i]; });
      const scenarioLabels = ['ধীর +১','মাঝারি +৩','দ্রুত +৬'];
      document.querySelectorAll('.scenario').forEach((b,i)=>{ if(scenarioLabels[i]) b.textContent=scenarioLabels[i]; });
    } else {
      const modeLabels = ['Field','Gaps','Path','Evidence','Impact'];
      document.querySelectorAll('.mode-switch button').forEach((b,i)=>{ if(modeLabels[i]) b.textContent=modeLabels[i]; });
      const scenarioLabels = ['Slower +1','Steady +3','Faster +6'];
      document.querySelectorAll('.scenario').forEach((b,i)=>{ if(scenarioLabels[i]) b.textContent=scenarioLabels[i]; });
    }
    const passport = $('#evidencePassport');
    if (passport) passport.setAttribute('aria-label', bn ? 'নির্বাচিত তুলনার প্রমাণ ও সীমাবদ্ধতা' : 'Evidence and limitations for the selected comparison');
    // Localize the remaining semantic labels too, so screen-reader text follows the visible language.
    const semanticLabels = [
      ['.metrics',bn?'বর্তমান তুলনার সারাংশ':'Current comparison summary'],
      ['.explorer',bn?'ইন্টার‌্যাকটিভ সক্ষমতা গ্যালাক্সি':'Interactive capability galaxy'],
      ['.zoom-controls',bn?'জুম ও দৃশ্য নিয়ন্ত্রণ':'Zoom and view controls'],
      ['.selection-switchers',bn?'তুলনা ও সক্ষমতা নিয়ন্ত্রণ':'Comparison and faculty controls'],
      ['#animalEstimate',bn?'প্রাণীর সক্ষমতা-অনুমান':'Animal faculty estimate'],
      ['.calibration-strip',bn?'তুলনা কীভাবে বুঝবেন':'How to interpret the comparison'],
      ['.calibration-mark',bn?'তুলনার নোট দেখুন':'Show comparison notes']
    ];
    semanticLabels.forEach(([selector,label])=>{const el=$(selector);if(el)el.setAttribute('aria-label',label);});
  };
  const toggle = $('#languageToggle');
  if (toggle) toggle.addEventListener('click', () => setTimeout(sync, 0));
  // Keep every fixed label in the active language, including after the app rebuilds controls.
  const root = document.documentElement;
  new MutationObserver(() => { if (root.dataset.v17Sync !== root.lang) { root.dataset.v17Sync = root.lang; sync(); } }).observe(root, {attributes:true,attributeFilter:['lang']});
  document.addEventListener('click', e => { if (e.target.closest('.mode-switch,.scenario,#prevComparator,#nextComparator,#prevFaculty,#nextFaculty,#comparatorSelect,#facultySelect')) setTimeout(sync, 0); });
  sync();
})();
</script>




<style id="ccAtlasV13AnimalEvidence">
  .inspector.animal-mode .compare { display:none !important; }
  .inspector.animal-mode .animal-estimate { display:block !important; margin:12px 0 4px; }
  .animal-estimate { display:none; }
  .animal-estimate-line { display:grid; grid-template-columns:minmax(90px,.8fr) minmax(0,1fr) 36px; align-items:center; gap:8px; font:10px 'Manrope',sans-serif; }
  .animal-estimate-line .who { color:#5f6877; }
  .animal-estimate-fill { background:var(--faculty-accent) !important; }
  .inspector.animal-mode .status-chip.evidence { color:#145a4b; background:#d9f5ec; border-color:#b7e9d9; }
  .inspector.animal-mode .status-chip.reasoning { color:#5d4792; background:#efe9ff; border-color:#d9ccff; }
  .inspector.animal-mode .gap-label { max-width:55%; text-align:right; line-height:1.4; }
  .inspector.animal-mode .model-source { margin-top:8px; font-size:11px; line-height:1.6; color:#354153; }
  .inspector.animal-mode .reference-caveat { margin-top:8px; line-height:1.6; }
  .legend.animal-mode .hum { background:var(--faculty-accent) !important; }
  .legend.animal-mode .machine { background:transparent !important; border:1px dashed var(--faculty-accent); box-shadow:none !important; width:7px; height:7px; }
  .feedback-button { color:var(--faculty-accent) !important; background:color-mix(in srgb,var(--faculty-accent) 9%,#fff) !important; border-color:color-mix(in srgb,var(--faculty-accent) 28%,#fff) !important; text-decoration:none !important; white-space:nowrap; }
  .feedback-button:hover,.feedback-button:focus-visible { color:var(--faculty-accent) !important; background:color-mix(in srgb,var(--faculty-accent) 15%,#fff) !important; border-color:color-mix(in srgb,var(--faculty-accent) 48%,#fff) !important; }
  .stage-actions .mode-pill#projectionMode { font-size:9px !important; }
  @media (max-width:1100px) { .stage-actions .mode-pill#projectionMode { font-size:9px !important; } }
  .legend { right:44px !important; }
  @media (max-width:760px) { .legend { right:44px !important; } }
</style>

<style id="ccAtlasV14LegendWidth">
  /* Widen the existing floating sphere legend while preserving its items and spacing language. */
  #canvasWrap > .legend {
    left: 24px !important;
    right: 44px !important;
    width: auto !important;
    max-width: none !important;
    box-sizing: border-box !important;
    justify-content: space-between !important;
  }
  @media (max-width: 760px) {
    #canvasWrap > .legend {
      left: 9px !important;
      right: 9px !important;
      width: auto !important;
      max-width: none !important;
      justify-content: flex-start !important;
    }
  }
</style>

<style id="atlasMobilePdfDownloadFix">
  @media (max-width: 600px) {
    .atlas-action-row { display:grid !important; grid-template-columns:minmax(0,1fr) !important; gap:8px !important; }
    .atlas-action-row .atlas-action { width:100% !important; min-height:44px !important; height:auto !important; max-height:none !important; padding:10px 12px !important; font-size:12px !important; white-space:normal !important; overflow:visible !important; text-overflow:clip !important; touch-action:manipulation; }
    .atlas-action-status { font-size:11px !important; line-height:1.5 !important; }
  }
</style>

<style id="atlasEvidenceShareEnhancements">
  .atlas-action-row { display:flex; flex-wrap:wrap; gap:7px; margin-top:12px; width:100%; grid-column:1 / -1; }
  .atlas-action-row .atlas-action { appearance:none; display:inline-flex !important; align-items:center; justify-content:center; width:auto !important; max-width:100%; border:1px solid #dfe3ec; background:#fff; color:#232938; border-radius:8px; padding:8px 10px !important; min-height:34px; font:700 9px/1.25 'Manrope',Arial,sans-serif !important; text-align:center; white-space:normal; cursor:pointer; transition:background .15s ease,border-color .15s ease,transform .15s ease; }
  .atlas-action.primary { background:#171b25; border-color:#171b25; color:#fff; }
  .atlas-action:hover { border-color:#e30613; transform:translateY(-1px); }
  .atlas-action:focus-visible,.evidence-passport summary:focus-visible { outline:2px solid #e30613; outline-offset:3px; }
  .atlas-action-status { min-height:0; font-size:9px; line-height:1.45; color:#687083; margin-top:5px; overflow-wrap:anywhere; grid-column:1 / -1; }
  .evidence-passport { margin-top:8px; border:1px solid #e0e4ec; border-radius:10px; background:rgba(247,248,251,.82); overflow:hidden; grid-column:1 / -1; }
  .evidence-passport summary { cursor:pointer; list-style:none; display:flex; align-items:center; justify-content:space-between; gap:8px; padding:10px 11px; font:750 9px/1.4 'Manrope',Arial,sans-serif; color:#252b39; }
  .evidence-passport summary::-webkit-details-marker { display:none; }
  .evidence-passport summary::after { content:'+'; color:#e30613; font-size:15px; line-height:1; }
  .evidence-passport[open] summary::after { content:'−'; }
  .evidence-passport-content { padding:0 11px 11px; }
  .evidence-fields { display:grid; gap:8px; }
  .evidence-field { padding-top:8px; border-top:1px solid #e5e8ee; }
  .evidence-field-label { display:block; color:#8b3340; font:750 8px/1.35 'DM Mono',monospace; text-transform:uppercase; letter-spacing:.08em; }
  .evidence-field-value { margin:4px 0 0; color:#495164; font:500 10px/1.55 'Manrope',Arial,sans-serif; overflow-wrap:anywhere; }
  .evidence-source-list { display:flex; flex-wrap:wrap; gap:7px 12px; padding-top:10px; }
  .evidence-source-link { color:#b20f1b; font-size:9px; font-weight:750; line-height:1.4; white-space:normal; }
  .evidence-passport-caution { margin:10px 0 0; padding:9px 10px; border-left:2px solid #e30613; background:#fff; color:#5d6575; font:500 9px/1.55 'Manrope',Arial,sans-serif; }
  .scenario-stamp { margin-top:10px; border-left:2px solid #737c8d; padding:7px 9px; background:rgba(125,136,153,.08); color:#626b7b; font:750 8px/1.5 'DM Mono',monospace !important; letter-spacing:.025em; }
  .scenario-stamp.is-scenario { border-left-color:#a05b16; background:#fff4e8; color:#855016; }
  .scenario-stamp.is-estimate { border-left-color:#7561bb; background:#f3f0ff; color:#5d4e9d; }
  @media (max-width:760px) {
    .atlas-action-row { display:grid; grid-template-columns:1fr 1fr; gap:6px; }
    .atlas-action-row .atlas-action { width:100% !important; padding:8px 7px !important; font-size:8px !important; }
    .evidence-passport summary { font-size:9px; }
  }
  @media (prefers-reduced-motion:reduce) { .atlas-action { transition:none; } .atlas-action:hover { transform:none; } }
</style>



<style id="atlasV18FinalLayoutAndInteraction">
  /* Compare-with arrows share the same compact proportions and accent behavior as faculty arrows. */
  .right-rail .selection-switchers .comparator-switcher { display:block !important; }
  .right-rail .selection-switchers .comparator-switcher label { display:flex !important; margin-bottom:4px !important; }
  .right-rail .selection-switchers .comparator-controls { display:grid !important; grid-template-columns:minmax(0,1fr) 25px 25px !important; align-items:stretch !important; gap:4px !important; width:100% !important; }
  .right-rail .selection-switchers #comparatorSelect { grid-column:1; grid-row:1; width:100%; min-width:0; height:26px; min-height:26px !important; padding:3px 5px !important; font:8.5px 'Manrope',Arial,sans-serif !important; }
  .right-rail .selection-switchers #prevComparator,
  .right-rail .selection-switchers #nextComparator { width:25px !important; min-width:25px !important; height:26px !important; min-height:26px !important; padding:0 !important; display:flex !important; align-items:center !important; justify-content:center !important; font:10px 'Manrope',Arial,sans-serif !important; color:var(--faculty-accent) !important; background:#fff !important; border:1px solid color-mix(in srgb,var(--faculty-accent) 26%,#dfe4ec) !important; border-radius:3px !important; }
  .right-rail .selection-switchers #prevComparator { grid-column:2; grid-row:1; }
  .right-rail .selection-switchers #nextComparator { grid-column:3; grid-row:1; }
  .right-rail .selection-switchers #prevComparator:hover,
  .right-rail .selection-switchers #nextComparator:hover { color:#fff !important; background:var(--faculty-accent) !important; border-color:var(--faculty-accent) !important; }
  .evidence-passport { background:#fff !important; color:#252b39 !important; max-height:238px !important; overflow-y:auto !important; overflow-x:hidden !important; box-shadow:0 8px 24px rgba(17,24,39,.14) !important; }
  .evidence-passport::before { border-bottom-color:#fff !important; }
  .evidence-passport-content { color:#485163 !important; }
  .howto-dialog { max-height:min(74vh,560px) !important; padding:18px clamp(18px,2.6vw,26px) 14px !important; background:#fff !important; }
  .howto-eyebrow { margin-bottom:5px !important; }
  .howto-title { margin-bottom:5px !important; }
  .howto-intro { margin-bottom:9px !important; }
  .howto-progress { margin-bottom:8px !important; }
  .howto-step { padding:11px 14px 10px !important; background:var(--faculty-accent-soft,#f7f6f2) !important; }
  .howto-step h3 { margin-bottom:4px !important; }
  .howto-step p { line-height:1.48 !important; }
  .howto-nav { margin-top:9px !important; }
  html[lang="bn"] .howto-step p { line-height:1.55 !important; }
  @media(max-width:760px) {
    .right-rail .selection-switchers .comparator-controls { grid-template-columns:minmax(0,1fr) 22px 22px !important; gap:3px !important; }
    .right-rail .selection-switchers #comparatorSelect { height:24px; min-height:24px !important; font-size:7.5px !important; }
    .right-rail .selection-switchers #prevComparator,
    .right-rail .selection-switchers #nextComparator { width:22px !important; min-width:22px !important; height:24px !important; min-height:24px !important; font-size:9px !important; }
    .evidence-passport { max-height:190px !important; }
    .howto-dialog { max-height:78vh !important; padding:15px 13px 12px !important; }
    .howto-step { padding:10px 11px 9px !important; }
    .howto-step p { font-size:11.8px !important; }
  }
</style>








<script id="atlasT02ScoreTrailLinks">
(() => {
  const facultyNames = ['Perception','Generation','Attention','Learning','Memory','Reasoning','Metacognition','Executive functions','Problem solving','Social cognition'];
  const scoreTrailUrls = {
    'Perception':'https://www.humanbaseline.org/benchmarks/perception-test/',
    'Generation':'https://www.humanbaseline.org/benchmarks/gdpval/',
    'Attention':'https://www.humanbaseline.org/faculties/attention/',
    'Learning':'https://www.humanbaseline.org/faculties/learning/',
    'Memory':'https://www.humanbaseline.org/benchmarks/locomo/',
    'Reasoning':'https://llmbenchmark.ai/benchmarks/epoch-gpqa-diamond',
    'Metacognition':'https://www.humanbaseline.org/faculties/metacognition/',
    'Executive functions':'https://www.humanbaseline.org/benchmarks/gaia/',
    'Problem solving':'https://llmbenchmark.ai/benchmarks/epoch-simplebench',
    'Social cognition':'https://www.humanbaseline.org/benchmarks/cogtom/'
  };
  const $ = sel => document.querySelector(sel);
  function syncScoreTrailLinks() {
    const bn = document.documentElement.lang === 'bn';
    const faculty = $('#facultySelect');
    const comparator = $('#comparatorSelect');
    const primary = $('#facultySourceLink');
    const trail = $('#takeTestLink');
    const modelRecommend = $('#modelRecommendLink');
    if (modelRecommend) {
      modelRecommend.href = 'https://artificialanalysis.ai/models/recommend';
      modelRecommend.target = '_blank'; modelRecommend.rel = 'noreferrer';
      modelRecommend.textContent = bn ? 'নিজের জন্য উপযুক্ত এআই মডেল খুঁজুন ↗' : 'Find your match AI Model ↗';
      modelRecommend.setAttribute('aria-label', modelRecommend.textContent);
      modelRecommend.title = modelRecommend.textContent;
    }
    if (!faculty || !comparator || !primary || !trail) return;
    const name = facultyNames[Number(faculty.value)] || 'Perception';
    const animal = comparator.value !== 'ai';
    primary.textContent = animal
      ? (bn ? 'প্রাসঙ্গিক প্রাণী-গবেষণা খুলুন ↗' : 'Open related animal study ↗')
      : (bn ? 'মূল গবেষণা বা বেঞ্চমার্ক খুলুন ↗' : 'Open primary study or benchmark ↗');
    primary.setAttribute('aria-label', primary.textContent);
    primary.title = primary.textContent;
    if (animal) {
      trail.hidden = true;
      trail.style.setProperty('display', 'none', 'important');
      trail.removeAttribute('href');
    } else {
      trail.hidden = false;
      trail.style.removeProperty('display');
      trail.href = scoreTrailUrls[name] || 'https://www.humanbaseline.org/faculties/';
      trail.textContent = bn ? 'স্কোরের উৎস ও সীমাবদ্ধতা ↗' : 'Score trail & caveats ↗';
      trail.setAttribute('aria-label', trail.textContent);
      trail.title = trail.textContent;
      trail.target = '_blank';
      trail.rel = 'noreferrer';
    }
  }
  document.addEventListener('change', e => { if (e.target.matches('#facultySelect,#comparatorSelect,#horizon')) setTimeout(syncScoreTrailLinks, 30); });
  document.addEventListener('click', e => { if (e.target.closest('#languageToggle,.mode-switch,.scenario,#prevComparator,#nextComparator,#prevFaculty,#nextFaculty')) setTimeout(syncScoreTrailLinks, 30); });
  new MutationObserver(() => setTimeout(syncScoreTrailLinks, 20)).observe(document.documentElement, {attributes:true,attributeFilter:['lang']});
  syncScoreTrailLinks();
})();
</script>

<style id="atlasV23T02T03Refinements">
  /* Let the evidence popover reveal every bullet without clipping or a tiny internal scroll box. */
  .right-rail .evidence-hover-wrap { position:relative !important; overflow:visible !important; }
  .right-rail .evidence-passport {
    display:none;
    position:absolute;
    z-index:12000;
    bottom:calc(100% + 9px);
    top:auto;
    right:0;
    width:min(330px, calc(100vw - 24px));
    max-width:calc(100vw - 24px) !important;
    height:auto !important;
    max-height:none !important;
    overflow:visible !important;
    overflow-y:visible !important;
    overflow-x:visible !important;
    padding:13px 15px !important;
    border:1px solid #dfe3e9;
    border-radius:8px;
    background:#fff !important;
    color:#30343b !important;
    white-space:normal !important;
    box-shadow:0 12px 32px rgba(20,24,32,.19) !important;
    pointer-events:auto;
    box-sizing:border-box;
  }
  .right-rail .evidence-hover-wrap:hover .evidence-passport,
  .right-rail .evidence-hover-wrap:focus-within .evidence-passport { display:block !important; }
  /* Temporarily lift overflow clipping only while the passport is revealed; the instrument layout stays unchanged otherwise. */
  #app:has(.evidence-hover-wrap:hover),
  #app:has(.evidence-hover-wrap:focus-within),
  .shell:has(.evidence-hover-wrap:hover),
  .shell:has(.evidence-hover-wrap:focus-within),
  .right-rail:has(.evidence-hover-wrap:hover),
  .right-rail:has(.evidence-hover-wrap:focus-within),
  .right-rail .inspector:has(.evidence-hover-wrap:hover),
  .right-rail .inspector:has(.evidence-hover-wrap:focus-within) {
    overflow:visible !important;
  }
  .right-rail:has(.evidence-hover-wrap:hover),
  .right-rail:has(.evidence-hover-wrap:focus-within),
  .right-rail .inspector:has(.evidence-hover-wrap:hover),
  .right-rail .inspector:has(.evidence-hover-wrap:focus-within) {
    position:relative;
    z-index:12000;
  }
  .right-rail .evidence-passport-heading { display:block; margin:0 0 8px; font-size:11px !important; line-height:1.4 !important; }
  .right-rail .evidence-passport-content { display:block; margin:0; padding:0 0 0 17px !important; font-size:10px !important; line-height:1.5 !important; overflow:visible !important; }
  .right-rail .evidence-passport-content li { display:list-item; height:auto !important; max-height:none !important; margin:0 0 6px !important; white-space:normal !important; overflow:visible !important; overflow-wrap:anywhere; line-height:1.5 !important; }
  .right-rail .evidence-passport-content li:last-child { margin-bottom:0 !important; }
  /* The three footer-right links are a single coherent, centered row; they wrap as a group on smaller screens. */
  .right-rail .data-note > .data-links {
    display:flex !important;
    flex-direction:row !important;
    flex-wrap:wrap !important;
    align-items:center !important;
    justify-content:center !important;
    align-content:center !important;
    gap:7px 15px !important;
    width:100% !important;
    text-align:center !important;
  }
  .right-rail .data-note > .data-links a {
    display:inline-block !important;
    flex:0 1 auto !important;
    text-align:center !important;
    white-space:normal !important;
    line-height:1.35 !important;
    max-width:100% !important;
  }
  @media (max-width:760px) {
    .right-rail .data-note > .data-links { justify-content:center !important; gap:7px 12px !important; }
    .right-rail .data-note > .data-links a { font-size:8px !important; }
  }
  /* In Bangla, the zoom controls remain graphic symbols only; accessible names remain localized. */
  html[lang="bn"] .map-button.zoom,
  html[lang="bn"] #zoomIn,
  html[lang="bn"] #zoomOut {
    display:inline-flex;
    align-items:center;
    justify-content:center;
    flex:0 0 32px;
    width:32px;
    min-width:32px !important;
    height:32px;
    min-height:32px !important;
    padding:0 !important;
    font-family:'Manrope',Arial,sans-serif !important;
    font-size:19px !important;
    font-weight:600 !important;
    line-height:1 !important;
    text-align:center !important;
    white-space:nowrap !important;
  }
  /* Avoid clipped Bangla labels. Keep matched control sizing and center each label in its own button. */
  html[lang="bn"] .atlas-action-row .atlas-action {
    height:auto !important;
    max-height:none !important;
    min-height:36px !important;
    padding:7px 8px !important;
    font-size:9px !important;
    line-height:1.35 !important;
    text-align:center !important;
    white-space:normal !important;
    overflow:visible !important;
    text-overflow:clip !important;
    overflow-wrap:anywhere;
    align-items:center !important;
    justify-content:center !important;
  }
  html[lang="bn"] .mode-switch button,
  html[lang="bn"] .scenario,
  html[lang="bn"] #resetView,
  html[lang="bn"] #howToUse,
  html[lang="bn"] .howto-nav button,
  html[lang="bn"] .language-toggle {
    display:inline-flex;
    align-items:center;
    justify-content:center;
    text-align:center;
    line-height:1.35;
    overflow-wrap:anywhere;
  }
  html[lang="bn"] .right-rail .selection-switchers #comparatorSelect,
  html[lang="bn"] .right-rail .selection-switchers #facultySelect {
    font-size:9px !important;
    line-height:1.35 !important;
  }
</style>
</body>
</html>



