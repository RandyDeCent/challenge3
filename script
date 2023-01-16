function generate() {
    let length = document.getElementById("length").value;
    let lowercase = "abcdefghijklmnopqrstuvwxyz";
    let uppercase = "ABCDEFGHIJKLMNOPQRSTUVWXYZ";
    let numeric = "0123456789";
    let special = "!@#$%^&*()_+-=[]{}|;':\"<>,.?/\\`~";
    let characters = "";
    let password = "";
  
    if (document.getElementById("lowercase").checked) {
      characters += lowercase;
    }
    if (document.getElementById("uppercase").checked) {
      characters += uppercase;
    }
    if (document.getElementById("numeric").checked) {
      characters += numeric;
    }
    if (document.getElementById("special").checked) {
      characters += special;
    }
  
    for (let i = 0; i < length; i++) {
      password += characters.charAt(Math.floor(Math.random() *
       characters.length));
    }
  
    document.getElementById("password").value = password;
  }
