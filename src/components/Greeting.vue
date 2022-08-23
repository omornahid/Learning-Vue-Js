<template>
    <div class="container mb-4">
        <div class="row">
            <div class="col-md-7">
                <div class="card shadow-lg">
                    <div class="card-body">
                        <p class="h3">Hello <span class="text">{{msg}}</span></p>
                        <button @click="greet('Good Morning')" class="btn btn-primary m-1">Good Morning</button>
                        <button @click="greet('Good Afternoon')" class="btn btn-info m-1">Good Afternoon</button>
                        <button @click="greet('Good Night')" class="btn btn-secondary m-1">Good Night</button>
                    </div>
                </div>
                

            </div>
        </div>
    </div>
</template>

<script>
export default {
    name : "greetIng",
    data: ()=>{
        return{
            msg : ""
        }
    },
    methods:{
        greet : function(value){
            this.msg = value

        }
    }
}
</script>
<style>
.text{
    color:darkblue;
}

</style>