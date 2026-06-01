const form = document.getElementById("loginForm");

form.addEventListener("submit", function(e){

    e.preventDefault();

    let email = document.getElementById("email").value;
    let password = document.getElementById("password").value;

    let emailError = document.getElementById("emailError");
    let passwordError = document.getElementById("passwordError");

    emailError.innerHTML = "";
    passwordError.innerHTML = "";

    let valid = true;

    if(email === ""){
        emailError.innerHTML = "Email wajib diisi";
        valid = false;
    }

    if(password === ""){
        passwordError.innerHTML = "Password wajib diisi";
        valid = false;
    }

    if(valid){
        alert("Login Berhasil");
        window.location.href = "index.html";
    }

});
