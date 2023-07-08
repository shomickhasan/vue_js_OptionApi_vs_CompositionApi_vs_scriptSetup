<template>
    <div class="card">
        <div class="card-header">
            <h3>Option API</h3>
            <p class="text-capitalize">{{des}}}</p>
        </div>
        <div class="card-body">
            <pre>
                 <code>{{syntex}}}</code>
            </pre>
        </div>

    </div>
</template>

<script>
    export default {
       data(){
           return {
               des:'in this option api start with export default object and this object contain data() function the data function return all object property value and function',
               syntex:`
                    export defoult{
                        data(){
                            return {
                                fname: 'jone',
                                lname: 35,
                                grtMessage:()=> {
                                    alert('hello');
                                },
                            }
                        }
                    }
               `,
           }
       }
    }
</script>

<style scoped>

</style>