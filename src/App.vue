<template>
  <img alt="Vue logo" src="./assets/logo.png">
  <HelloWorld msg="Welcome to Your Vue.js + TypeScript App"/>
</template>

<script lang="ts">
import { Options, Vue } from 'vue-class-component';
import HelloWorld from './components/HelloWorld.vue';

@Options({
  components: {
    HelloWorld,
  },
})
export default class App extends Vue {}


// var miString: string ="Hello World"
// var miNumber: number = 22
// var miBoolean: boolean = true

// var cualquierDato: any = 22
// cualquierDato = '22'

// var arregloStrings:string[] = ['','','']
// var arregloNumeros: number[] = [1,2,3]
// var arregloCualquiera: any[] = [1,2,3,'asdasd',true]

// //tuple - arreglos con una extructura

// var stringNumTuple:[string,number,string];
// stringNumTuple = ['hello',2,'sa']

// //void = undefined, null

// let miUndefined:void = undefined;
// let miNull:null = null


// //functions 

// function sumar(num1:number, num2:number){

//   return num1 + num2
// }

// //function sin return

// function myVoidFunction():void{
  
// }


// //interfaces

// interface ITodo{
//   title:string;
//   description:string;
// }

// function showTodo(todo:ITodo){
//   console.log(`${todo.title} - ${todo.description}`);

// }
// let list:ITodo = {
//   title: "comer",
//   description: "necesito comer"
// }



// //clases

// class User{
//   name:string;
//   email:string;
//   age:number;
  
//   constructor(name:string, email:string, age:number){
//     this.name = name;
//     this.email = email;
//     this.age = age;
//   }
//   register(){
//     console.log(`${this.name} se registro con exito`)
//   }
//   showMeAge(){
    
//       return this.age;
//     }

//     private AgeInYears(){
//       return this.age + ' years';
//     }
  
// }
// var john = new User('john','asdasd@gmail.com',21)

// console.log(john.register())



</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
