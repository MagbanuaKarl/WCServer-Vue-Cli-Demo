<template>
    <div id="todo-card">
        <div id="todo-card">
            <div class="container">
                <div class="alert alert primary" role="alert">
                    <h1>{{ msg2 }}</h1>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: 'todo-card',
    data () {
        return {
            msg2: 'This is the TodoCards component'
        }
    }
}
</script>