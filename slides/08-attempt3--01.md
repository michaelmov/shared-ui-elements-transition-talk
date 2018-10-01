### Home.vue

``` html
<overdrive :id="`card-${index}`" :duration="300">
    <div class="card__thumbnail" :style="{ backgroundImage: `url('${article.imageUrl}')` }"></div>
</overdrive>
```