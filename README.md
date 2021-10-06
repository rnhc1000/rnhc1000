# rnhc1000
<a href="https://app.daily.dev/rferreira"><img src="https://api.daily.dev/devcards/862599f4777c4f3ca1263d4114e29dd0.png?r=ti9" width="400" alt="Ricardo Alves Ferreira Silva's Dev Card"/></a>
function getUsers() {
  fetch("http://jsonplaceholder.typicode.com/users")
    .then(res => res.json())
    .then(data => console.log(data));
}
