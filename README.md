# Animation-effects
12 cool animations in plain HTML, CSS and JavaScript. Press Show code under any card, then Copy to get a complete snippet you can paste into an .html file.
<!DOCTYPE html>
<html><head><meta charset="utf-8"><style>
body{background:#0b1020;color:#fff;display:grid;place-items:center;min-height:100vh;margin:0}
.stage{position:relative;width:360px;height:220px;display:grid;place-items:center}
.flip{width:190px;height:120px;perspective:800px}
.in{position:relative;width:100%;height:100%;transition:transform .8s cubic-bezier(.3,1.3,.5,1);transform-style:preserve-3d}
.flip:hover .in{transform:rotateY(180deg)}
.f{position:absolute;inset:0;display:grid;place-content:center;text-align:center;border-radius:14px;font:700 18px system-ui;backface-visibility:hidden;color:#06121f}
.front{background:linear-gradient(135deg,#60a5fa,#2dd4bf)}
.back{background:linear-gradient(135deg,#fbbf24,#fb7185);transform:rotateY(180deg)}
</style></head><body>
<div class="stage">
<div class="flip"><div class="in"><div class="f front">Hover me</div><div class="f back">Wings of Fire<br><small>4 copies available</small></div></div></div>
</div>
</body></html>
