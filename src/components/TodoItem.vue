<template>
    <div>
       <strong> {{todo.id}} </strong>
       {{todo.title}}
    </div>
</template>

<script>
export default {
    props:{
        todo:{
            type:Object,
            required:true
        }
    }
}
</script>