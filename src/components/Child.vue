<template>
    <div>
        <slot name="title"></slot>
        <h1>{{ greeting }}</h1>
        <slot name="text-1"></slot>
        <h1>Random</h1>
        <slot name="text-2"></slot>
    </div>
</template>

<script>
    export default {
        name: 'Child',
        data () {
            return {
                greeting: 'I am Child component'
            }
        }
    }
</script>
