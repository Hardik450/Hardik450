### Hi there 👋

<!--
**Hardik450/Hardik450** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
<!DOCTYPE html>
<html>
    <head>
        <title>Page Title</title>
        <script src="https://unpkg.com/sweetalert/dist/sweetalert.min.js"></script>
        <script>
            function dis(val){
                document.getElementById("result").value+=val
            }
            function solve(){
                let x = document.getElementById("result").value 
                let y = eval(x)
                document.getElementById("result").value = y
            }
            function clr(){
                document.getElementById("result").value = ' '
            }
        </script>
    </head>
    <body>
    <script>
        swal({
            title:"Calculator",
            text:"Hi, friends. Welcome to my webpage. Please upvote and comment if you like it.  If you want to give some suggestion, please give me in comment section or message me. Thank you for visiting here and giving your precious time.",
        })
    </script>
    <div class="calculator">
    <center><h1>Calculator</h1></center>
<table>

            <tr>
            <center><td><input type="text"id="result"></td></center>     
            </tr>
            </table><table class="bomb">
            <tr>
                <td><input type="button"value="1"onclick="dis(1)"></td>  <td><input type="button"value="2"onclick="dis(2)"></td>
                         <td><input type="button"value="3"onclick="dis(3)"></td>
                                     <td><input type="button"value="+"onclick="dis('+')"></td>
                                                 <td><input type="button"value="-"onclick="dis('-')"></td>
                                                             
            </tr>
            <tr>
                            <td><input type="button"value="4"onclick="dis(4)"></td>
                                        <td><input type="button"value="5"onclick="dis(5)"></td>
                                                    <td><input type="button"value="6"onclick="dis(6)"></td>
        <td><input type="button"value="/"onclick="dis('/')"></td>
        <td><input type="button"value="^"onclick="dis('**')"></td>
    
           </tr>
                <tr>
                <td><input type="button"value="7"onclick="dis(7)"></td>
                       <td><input type="button"value="8"onclick="dis(8)"></td>
                                   <td><input type="button"value="9"onclick="dis(9)"></td>
                                   
                                   <td><input type="button"value="."onclick="dis('.')"></td>
                                   <td><input type="button"value="*"onclick="dis('*')"></td>
 
           </tr>
             <tr>
                             <td><input type="button"value="0"onclick="dis(0)"></td>
             <td><input type="button"value="00"onclick="dis('00')"></td>   
                      
                                             <td><input type="button"value="="onclick="solve()"></td>
                                                                         <td><input type="button"value="Clear"onclick="clr()"></td> 
             <td><input type="button" value="%" onclick="dis('%')"></td>                                                                 
             </tr>
        </table></div>
    </body>
</html>
