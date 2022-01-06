# tigercss
Tigercss is a css preprocessor.

You can use like this

### with Tailwindcss and CSS
```html
<div class="box pt-6 md:flex"></div>
<style>
.box {
  text-center;
  color-gary;
  background: red; 
}
</style>
```

### with Vue
```vue
<style lang="tcss">
.box {
  text-center;
  color-gary;
  background: red; 
  sapn {
     color-cyan-600;
  }
}
</style>
```

### Like Sass and Less
```css
<style>
<!-- Variables: $ or @ -->
$color-primary: red;
@color-second: cyan;

.box {
  text-center;
  color-gary;
  background: red; 
  
  <!-- Nested -->
  sapn {
     color-cyan-600;
  }
  
  <!-- Parent Selectors: &  -->
  &:p {
    color: @color-second;
    <!-- color: $color-second; -->
  }
}
</style>
```

