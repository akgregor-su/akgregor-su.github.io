# akgregor-su.github.io

The extra functionality I have added for extra credit is Javascript embedded in my html. 

<script>
                function myFunction() {
                    var txt;
                    if (confirm("You have successfully submitted your message to Travel363!")) {
                        txt = "You have submitted a message to Travel363.";
                    } else {
                    txt = "You have unsubmitted your message to Travel363.";
                    }
                    document.getElementById("demo").innerHTML = txt;
                    }
            </script>
            
This adds the functionality of when someone submits a message to the website, an 
alert pops up saying, "You have successfully submitted your message to Travel363!".
