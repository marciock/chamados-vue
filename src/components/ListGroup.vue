<template>
    <div class="list-group">
        <a href="#" class="list-group-item list-group-item-action  ">
            <div class="d-flex w-100 justify-content-between">
                <h5 class="mb-1">titulo</h5>
                <small>tempo</small>
            </div>
            <p class="mb-1">descrição</p>
            <small>inicio-fim</small>
        </a>
    </div>
    
</template>
<script>
export default {
    name:'ListGroup',
    data:()=>{
        return {
            list:[]

        }
    }
}
</script>