<template>
<!-- This is how state works -->
    <div class="container">
        <div class="row">
            <div class="col">
                <p class="h3 my-4 text-warning">Employee - This is from state</p>
                <ul class="list-group">
                    <li class="list-group-item">
                        Name : {{this.emp.name}}
                    </li>
                    <li class="list-group-item">
                        Age : {{this.emp.age}}
                    </li>
                    <li class="list-group-item">
                        Designation : {{this.emp.deg}}
                    </li>
                </ul>


            </div>
        </div>
    </div>
</template>
 
<script>
export default{
    name : "EmployeeInfo",
    data : ()=>{
        return{         // this is state
            emp :{
            name : "Nahid",
            age : 22 ,
            deg : "Doc" 
        }
        } 
    }
}
</script>

<style>

</style>