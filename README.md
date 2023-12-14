<!DOCTYPE html>
<html>
   <body>
      <script>
         var password = "123";
         (function passcodeprotect() {
            var passcode = prompt("Enter PassCode");
            while (passcode !== password) {
               alert("Incorrect PassCode");
               return passcodeprotect();
            }
         }());
         alert('here is code');
      </script>
   </body>
</html>
