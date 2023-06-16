# 💫 Scroll stars effect with JS
I practiced creating the scroll animation without the plugin first.

### Comments
```sh
window.addEventListener('scroll', function (event) {
  let scroll = this.scrollY;
  starBg.style.transform = `translateY(${-scroll / 3}px)`;
  title.style.transform = `translateY(${scroll / 1.7}px)`;
})
```
It is possible to create opposing animations with positive and negative values. <br />
In addition, division was used to adjust the scroll speed of the two star background layout.
