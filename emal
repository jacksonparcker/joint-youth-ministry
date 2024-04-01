
function sendEmail(){
    Email.send({
        Host : "smtp.elasticemail.com",
        Username : "jyministries256@gmail.com",
        Password : "FF88A15BEA9322238D0E2E9BE27F3C1B7871",
        To : 'jyministries256@gmail.com',
        From : "jyministries256@gmail.com",
        Subject : "This is the subject",
        Body : "firstname: " + document.getElementById("firstname").value
        +"<br>secondname. "  +document.getElementById("secondname").value
        +"<br>contact. "  +document.getElementById("contact").value
        +"<br>email. "  +document.getElementById("email").value
        +"<br>message. "  +document.getElementById("textarea").value
      }).then(
        message => alert(message)
      );
}
form1.addEventListener("submit", (e) => {
    e.preventDefault()
    sendEmail();
});