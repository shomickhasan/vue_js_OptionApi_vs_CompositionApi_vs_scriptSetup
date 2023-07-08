<template>
    <div class="card">
        <div class="card-header">
            <h3>Composition API</h3>
            <p class="text-capitalize">{{des}}</p>
        </div>
        <div class="card-body">
            <pre>
                 <code>{{syntex}}</code>
            </pre>
        </div>
    </div>
</template>

<script>
  export default {
      setup(){
          const des = 'in composition api not need to return data with object it can  like normal js code (variable function etc) then return them'
          const syntex = `
            export default{
                setup() {
                    const fname : 'jone'
                    const lname : 'due'
                    const message = () =>{
                        alert('hello world')
                    }
                }
            }`
          return {des,syntex}
      }

  }
</script>

<style scoped>

</style>