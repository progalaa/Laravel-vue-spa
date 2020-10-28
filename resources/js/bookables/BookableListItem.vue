<template>
    <div>
        <h1>{{ title }}</h1>
        <p>{{ content }}  - {{ price }} $ </p>
    </div>
</template>



<script>
export default {
    props: {"title": String, "content": String, "price": Number},
}
</script>