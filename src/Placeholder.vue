<script setup>
    import "./assets/main.css"
    const props = defineProps({
        title: String,
    })
</script>

<template>
    <div>
        <div class="title" v-if="title !== undefined">
            {{title}}
        </div>
        <div class="title" v-else></div>
        <div class="block">
            <div class="label">
                <slot>
                </slot>
            </div>
        </div>
    </div>
  
</template>

<style scoped>

</style>