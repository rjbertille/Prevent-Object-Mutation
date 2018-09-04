# Prevent-Object-Mutation
ES6 JS_FreeCodeCamp
<p>As seen in the previous challenge, const declaration alone doesn't really protect your data from mutation. 
To ensure your data doesn't change, JavaScript provides a function Object.freeze to prevent data mutation.</p>
<p>Once the object is frozen, you can no longer add, update, or delete properties from it. 
Any attempt at changing the object will be rejected without an error.</p>
<p>let obj = {<br>
  name:"FreeCodeCamp",<br>
  review:"Awesome"<br>
};<br>
Object.freeze(obj);<br>
obj.review = "bad"; //will be ignored. Mutation not allowed<br>
obj.newProp = "Test"; // will be ignored. Mutation not allowed<br>
console.log(obj); <br>
// { name: "FreeCodeCamp", review:"Awesome"}</p>
<p>In this challenge you are going to use Object.freeze to prevent mathematical constants from changing. 
You need to freeze the MATH_CONSTANTS object so that no one is able alter the value of PI, add, or delete properties .</p>
