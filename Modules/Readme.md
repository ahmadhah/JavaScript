### [*Modules*](#advance)

## simply follow the following steps :

<br>

1. Add type module in index.html script 

       <script src="./index.js" type="module"></script>
<br>

2. Export something from sub file/ module  file

        export default sum = ()=>{
                         alert('sum') }

    <br>
3. Now import this file in your root file..Note : also type extension type with file name 

        import sum from './sum.js'
        sum() //calling our sum function