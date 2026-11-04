<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Overflow Examples</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <main class="page">
    <h1>CSS Overflow Examples</h1>
    <p>Each box has a fixed height. Compare how it handles extra content.</p>

    <section class="examples">
      <article>
        <h2>Visible</h2>
        <div class="box visible">
          <p>Content starts inside this fixed-height box.</p>
          <p>This extra paragraph extends beyond the box. With visible overflow, the content remains visible outside its container.</p>
          <p>Here is another paragraph to show the overflow clearly.</p>
        </div>
      </article>

      <article>
        <h2>Hidden</h2>
        <div class="box hidden">
          <p>Content starts inside this fixed-height box.</p>
          <p>This extra paragraph extends beyond the box. With hidden overflow, the extra content is clipped.</p>
          <p>This paragraph is clipped too.</p>
        </div>
      </article>

      <article>
        <h2>Auto</h2>
        <div class="box auto">
          <p>Content starts inside this fixed-height box.</p>
          <p>This extra paragraph extends beyond the box. With auto overflow, a scrollbar appears when the content does not fit.</p>
          <p>Scroll inside the box to read this paragraph.</p>
        </div>
      </article>

      <article>
        <h2>Scroll</h2>
        <div class="box scroll">
          <p>Content starts inside this fixed-height box.</p>
          <p>With scroll overflow, a scrollbar is provided even when it is not needed.</p>
          <p>Keep scrolling to see more content in this fixed-size container.</p>
        </div>
      </article>
    </section>

    <section class="fixed-example">
      <h2>Fixed layout using overflow: auto</h2>
      <div class="scroll-panel">
        <p>This second container also has a fixed height and uses overflow: auto.</p>
        <p>When content exceeds its available space, you can scroll within this panel instead of letting it cover other page content.</p>
        <p>Adding more text demonstrates that the layout remains contained and usable.</p>
      </div>
    </section>
  </main>
</body>
</html>