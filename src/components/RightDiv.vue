<script setup lang="ts">
import { CardImage, CardBody, SearchBar, Button } from '@swarmakit/vue'

</script>

<template>
    <div class="form-div">
        <div class="search-bar">
            <SearchBar placeholder="check other devs"/>
        </div>
        <div class="content-div">
            <CardImage src="/2150169179.jpg" alt="A random image"/>
            <CardBody>
                <h1>Please Employ Me🥺</h1>
                <p>I built a simple webpage with Vue + Vite and Swarmakit library... The <b>search bar</b> above, the <b>card body</b> wrapping these texts and the <b>buttons</b> below are all from  </p> ⬇️ <br/> <a href="https://www.npmjs.com/package/@swarmakit/vue?activeTab=readme" target="_blank">Swarmakit Library</a>
            </CardBody>
    </div>
    <Button type="primary">
        <a href="https://www.linkedin.com/in/oluwaferanmi-emmanuel-280746270/" target="_blank" class="link">Employ Me</a>
    </Button>
    <Button type="primary" disabled>
        don't employ - disabled button
    </Button>
    
</div>

</template>

<style scoped>
.form-div {
    display: flex;
    flex-direction: column;
    color: black;
    background-color: white;
    gap: 10px;
    height: 100%;
}
.search-bar{
    display: flex;
    justify-content: end;
}
.try {
    height: 300px;
}
.content-div{
    display: flex;
    margin: auto;
}
.link{
    text-decoration: none;
    color: black;
    font-size: 18px;
    font-weight: 500;
}
h1{
    font-size: 3.2em;
  line-height: 1.1;
}
</style>
