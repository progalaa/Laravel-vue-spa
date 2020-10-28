<template>
    <div>
        <bookable-list-item title="Cheap villa" content="A very cheap villa" :price="1000"></bookable-list-item>
        <bookable-list-item title="Cheap villa 2" content="A very cheap villa 2" :price="255"></bookable-list-item>
        <bookable-list-item title="Cheap villa 3" content="A very cheap villa 3" :price="500"></bookable-list-item>

    </div>
</template>


<script>
import BookableListItem from "./BookableListItem";
export default {
    components: {
        BookableListItem
    },
    // beforeCreate() {
    //     console.log("beforeCreate");
    // },
    created() {
        console.log("created");
    },
    // beforeMount() {
    //     console.log("beforeMount");
    // },
    // mounted() {
    //     console.log("mounted");
    // },
    // beforeDestroy() {
    //     console.log("beforeDestroy");
    // },
    // destroyed() {
    //     console.log("destroyed");
    // }
}
</script>