<template>
    <div class="contrainer">
        <input type="checkbox" >
        <label>{{ msg }}</label>

    </div>
</template>

<script>
export default {
    name: 'CheckBox',
    props: {
        msg: String
    }
}
</script>

<style>

</style>