<script setup>
    import "./assets/main.css"
    const props = defineProps({
        date: String,
        time: String,
        location: String,
        eventdescription: String
    })
</script>

<template>
    <div>
        <div class="title">
            General event data
        </div>
        <div class="block">
            
            <div>
               <b>Date: </b> {{date}}
            </div>
            <div>
                <b>Time: </b> {{time}}
            </div>
            <div>
                <b>Location: </b> {{location}}
            </div>
            <div>
                <b>Event description: </b> {{eventdescription}}
            </div>
        </div>
    </div>
</template>

<style scoped>

</style>