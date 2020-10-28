<template>
    <div>
        <bookable-list-item :title="bookable1.title" :content="bookable1.content" :price="bookable1.price"></bookable-list-item>
        <bookable-list-item :title="bookable2.title" :content="bookable2.content" :price="bookable2.price"></bookable-list-item>
        <bookable-list-item :title="bookable3.title" :content="bookable3.content" :price="bookable2.price"></bookable-list-item>
    </div>
</template>


<script>
import BookableListItem from "./BookableListItem";
export default {
    components: {
        BookableListItem
    },
    data() {
        return {
            bookable1: {
               title: "Cheap villa1",
               content: "cheap villa 1 component",
               price: 150,     
            },
            bookable2: {
               title: "Cheap villa2",
               content: "cheap villa 2 component",
               price: 250,
            },
            bookable3: {
               title: "Cheap villa2",
               content: "cheap villa 2 component",
               price: 500,
            }
        }
    },
    created() {
        console.log(this.bookable1);
        console.log(this.bookable2);
    },
}
</script>