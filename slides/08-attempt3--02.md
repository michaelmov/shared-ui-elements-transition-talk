### Story.vue

``` html
 <overdrive :id="`card-${article[0].id}`" :duration="300">
    <header class="article__hero d-flex justify-content-center align-items-center"  :style="{ backgroundImage: `url('${article[0].imageUrl}')` }">
        <h1 class="article__title">{{ article[0].title }}</h1>
    </header>
</overdrive>
```