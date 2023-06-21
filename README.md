# lecture4
// function sum(a){
//    return a.length==0
// }
// console.log(sum("0"));

// function sum(a,b){
//     let str=b
//     console.log(b.concat(",",a));
// }
// sum("John","Doe");

// function sum(a){
// return a.length%2==0
// }
// console.log(sum("look"));

// function sum(a){
// return a.at(-1)=="n"
// }
// console.log(sum("neka"));

// function sum(a,b){
// if (typeof(a)=="string")return a.repeat(b)
// else{
//     return "Not A String"
// }
// }
// console.log(sum("Mubashir",3));

// function sum(a,b,c){
// if (typeof(a,b)==Number)(typeof(c)=="string")
//    if(c=="*"){
//    return a*b
//    }
//    if(c=="+"){
//     return a+b
//     }
//     if(c=="%"){
//         return a%b
//         }
// }
// console.log(sum(14,3,"%"));

// function sum(a){
//     return a.split("-").length
// }
// console.log(sum("bea-uti-full"));

// function sum(str){
//   let count = 0
//   for (let i=0;i<str.length;i++){
// if (str[i]===str[i].toUpperCase()){
//   count++
// }
// }
//   return count
// }
// console.log(sum("MMD"));

//     function combineFirstAndLast(str) {
//         return str.charAt(0) + str.charAt(str.length - 1);
// }
// console.log(combineFirstAndLast("qwer"));
// function repeatLastChar(str, n) {
//  let lastchar=str.charAt(str.length-1)
//  let repeatchar=lastchar.repeat(n)
//  return str.slice(0, str.length-1)+repeatchar
//   }
//   console.log(repeatLastChar("hello",3));

// function sum(str){
//     if (str.at(-1)=="string"){
//      return true
//     }
//     else{
//         return false
//     }
// }
// console.log(sum("dudes"));

// function sum(a){
//     return( a.split("").reverse().join("").toUpperCase());
// }
// console.log(sum("hellothere"));

// function sum(a){
//     let b=a.split("").reverse().join("");
//     return b.concat(a)
// }
// console.log(sum("123456789"));

// function sum(a){
//     let b="something"
//  return b.concat(" ",a)
// }
// console.log(sum("is better than nothing"));

// function sum(a){
//     return( Number(a));
// }
// console.log(sum("1000"));

// function sum(a){
//     let b="Hello"
//     console.log(b.concat(",",a,"!").replace("Mubashir","my Love"));
// }
// console.log(sum("Mubashir"));

// function boolToString(str) {
//   return `"${str}"`;
// }

// console.log(boolToString(true));

// function sum(a){
//   if (typeof a=="string"){
//     return a
//   }
//   else if (typeof a=="number") {
//     return `"${a}"`
//   }
// }
// console.log(sum("77"));


// function sum(a,b){
//   return a.includes(b)
// }
// console.log(sum("feminine","nine"));

// function Wowel(a,b){
//   let cnt=0
// for (let i=b;i<a.length;i++){
//   if (b.at[i]==a){
//     cnt++
//   }
// }
// return cnt
// }
// console.log(Wowel("a","edabit"));

// function sum(str){
//   let start=''
//   let end=''
//   for (let i=0;i<str.length;i++){
//     if (str[i]==str[i].toUpperCase())start+=str[i]
//     if (str[i]==str[i].toLowerCase())end+=str[i]
//   }
//   return start+end
// }
// console.log(sum('haPi'));

// function sum(a,b){
//   return a.length==b.length
// }
// console.log(sum("AB","CD"));

// function sum(str){
//   return(str.replaceAll("a",1).replaceAll("e",2).replaceAll("i",3).replaceAll("u",5).replaceAll("o",4));
// }
// console.log(sum("chembur"));


// function sum(str){
//   console.log(str.replaceAll("a","").replaceAll("b","").replaceAll("c",""))
// }
// console.log(sum("This might be a bit hard"));


// function sum(str){
//   let even=''
//   let odd=''
//   for (let i=0;i<str.length;i++){
//     if (i%2==0) even+=str[i]
//     if (i%2==1) odd+=str[i]
//   }
//   return even.concat(" ",odd)
// }
// console.log(sum("mubashir"));

// function sum(str){
//   let cnt=0
//   str=str.replaceAll("potato",1)
//   for (let i=0;i<str.length;i++){
//     if (str[i]==str[i])cnt++
//   }
//   return cnt
// }
// console.log(sum("potatoapple"));
// 1.rest
// function sum(...a){
//   return a
// }
// console.log(sum(1,2,3,4,5));

//2.spread
