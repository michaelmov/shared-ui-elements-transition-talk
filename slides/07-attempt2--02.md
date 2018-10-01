``` html
<div class="app-container">
    <router-view></router-view>
    <div id="ghost" ref="transitionGhost"></div>
</div>
```

```css
#ghost {
  pointer-events: none;
  position: fixed;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  z-index: 1000;
}
```