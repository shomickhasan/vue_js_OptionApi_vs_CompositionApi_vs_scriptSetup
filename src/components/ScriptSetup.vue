<template>
    <div class="card">
        <div class="card-header">
            <h3>Script Setup</h3>
            <p class="text-capitalize">{{des}}</p>
        </div>
        <div class="card-body">
            <pre>
                 <code>{{syntex}}</code>
            </pre>
        </div>
    </div>
</template>

<script setup>
    const des = "in the script setup not need to define export of any function. only define setup keyword in script opening tag and not need to return. by default it can return "
    const syntex= `
        const fname = 'jone'
        const lname =  'due'
        const message = () ={
            alert('hellow world')
        }
    `
</script>

<style scoped>

</style>