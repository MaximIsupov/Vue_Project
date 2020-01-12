<template>

<div id="a" >
    <div id="b" class="container">
        <div id="c" >
            <form  @submit.prevent="sub" id="form">
            <div class="form-group px-1" id="formGroupExampleInput">
                <input id="inp1" type="text" class="form-control" v-model="name"  placeholder="ФИО" name="LastSecondName" required>
            </div>
            <div class="form-group px-1">
                <input type="tel" class="form-control" v-model="number" name="phonenumber" id="formGroupExampleInput2" placeholder="Телефон" required>
            </div>
            <div class="form-group px-1" >
                <select id="inputState" v-model="reg" class="form-control" name="Region" required>
                    <option selected >Регион</option>
                    <option>Краснодарский край</option>
                    <option>Московская область</option>
                    <option>Кировская область</option>
                    <option>Другое...</option>
                </select>
                <div class="form-group " id="exampleFormControlTextarea1">
                  <textarea class="form-control"  rows="3" name="Message" v-model="message" placeholder="Сообщение"></textarea>
                </div>
            </div>
            <div class="mx-auto">
                <input type="submit" id="butn" class="btn" value= "Отправить"/> {{ response }}
            </div>
            
        </form>
        </div>
    </div>
</div>

</template>

<script>
import axios from 'axios'
export default {
    name: 'Form',
    data(){
        return{
            name: '',
            number: '',
            reg: '',
            message: '',
            response: '',
            error: 'Ошибка при отправке!'
        }
    },
    methods:{
        sub(){
            axios.post('https://formcarry.com/s/RTDL3lgXWvw',{
                name:this.name,
                number:this.number,
                reg:this.reg,
                message:this.message
            }).then(response => {
                alert('Form has been delivered!!')
                return response;
            })
            .catch(error => alert(error));
        }
    }
}
</script>

<style scoped>
    input{
        margin-top:10px;
              
    }

    textarea{
        margin-top:10px;
    }

    #inp1{
        margin-top:40px;
    }

    #a {
        position: fixed;
        width: 100%;
        height: 100%;
        z-index: 2;
        background-color: rgba(0, 0, 0, 0.3);
       
    }

    #b {
        width: 50%;
        height: 50%; 

    }

    #c { 
        margin-top:100px;
        width: 800px;
        height: 400px;
        position: absolute;
        background-color: white;
  
    }
</style>

