<template>
    <div>
        <p>
            b: {{b}}
            <br>
            <button @click="b++">add</button>
        </p>
    </div>
</template>

<script>
export default {
    data() {
        return {
            b: 1
        }
    }
}
</script>
