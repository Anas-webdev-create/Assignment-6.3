* {
  box-sizing: border-box;
}

body {
  margin: 0;
  padding: 32px 20px;
  font-family: Arial, sans-serif;
  background: #f3f6fa;
  color: #243247;
}

.page {
  max-width: 1000px;
  margin: 0 auto;
}

.examples {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
  gap: 24px;
  align-items: start;
}

.examples article {
  min-width: 0;
}

.box {
  height: 150px;
  padding: 14px;
  border: 2px solid #54718f;
  border-radius: 8px;
  background: white;
}

.box p,
.scroll-panel p {
  margin-top: 0;
  line-height: 1.5;
}

.visible {
  overflow: visible;
}

.hidden {
  overflow: hidden;
}

.auto {
  overflow: auto;
}

.scroll {
  overflow: scroll;
}

.fixed-example {
  margin-top: 34px;
}

.scroll-panel {
  height: 120px;
  max-width: 600px;
  padding: 16px;
  overflow: auto;
  border: 2px solid #35866a;
  border-radius: 8px;
  background: #e7f5ee;
}