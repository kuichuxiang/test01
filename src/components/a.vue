<template>
    <div>
        <p>
            a: {{a}}
            <br>
            <button @click="a++">add</button>
        </p>
    </div>
</template>

<script>
export default {
    data() {
        return {
            a: 1
        }
    }
}
</script>
