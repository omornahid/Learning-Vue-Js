<template>
    <div class="container">
        <div class="row">
            <div class="col">
                <h2 class="my-4">Counter - {{this.count}}</h2>
                <button @click="incr" class="btn btn-success p-3 m-3">Increment</button>
                <button @click="dec" class="btn btn-danger p-3 m-3">Decrement</button>
            </div>
        </div> 
    </div>
</template>

<script>
export default {
  name: "CounterInfo",
  data : ()=>{
    return{
        count : 0,
    };
  },
    // data(){
    //     return{
    //         count :0
    //     }
    // },
  methods:{
    inc(){
        this.count = this.count + 1 ;
    },
    dec(){
        this.count = Math.max(0, this.count - 1);
    },
    incr : function(){
        this.count = this.count + 1 ;
    }
  }
};
</script>

<style></style>
