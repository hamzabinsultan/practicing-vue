# practicing-vue
I am practicing vue js from official DOCs





todo.completed===true?todoTaskCompleted:todoTaskIncompleted





 mounted() {
      const getStorage = localStorage.getItem("key");
      if(Array.isArray(getStorage)&& !getStorage.length){
        console.log("array is  empty")
      }else{
        console.log("array is empty")
      }
      console.log(Array.isArray(getStorage))












JSON.stringify
JSON.parse // it converts a string into an object
localStorage.setItem()
localStorage.getItem()

localStorage.clear()


vue 
mounted(){

}

method

addtodo(){

}


  <!-- <p>PRODUCT IMAGE : {{data.images}}</p> -->  


  10,12,25,50,100  products should be per page when set by drop down menu >>> done
  upon 0 index previous button should not appear >>> done
   upon last index next button should not appear >>> done
   sort the products with respect to price heigh to low and vice versa 
   sort the product with respect to newest products
   I have to put condition in image because there is no image in some of the products.



<!-- 
 <li class="page-item"><a class="page-link"  v-on:click="$emit('click-pagination')" >{{pages-1}}</a></li>
      {{pagiation}}
      <li class="page-item"><a class="page-link" >{{pages}}</a></li>
      <li class="page-item"><a class="page-link" >{{pages+1}}</a></li> -->


      loooper.push({
       { page-no : 1,
       current-page: true/false
       },
        { page-no : 2,
       current-page: true/false
       }, { page-no : 3,
       current-page: true/false
       }, { page-no : 4,
       current-page: true/false
       }
       )}

         <li class="page-item"><a class="page-link" v-for ="(pagination ,index )in paginationarray">{{pagination.pageNo}}</a></li>


         :paginationarray ="paginationArray"\
         "paginationarray"