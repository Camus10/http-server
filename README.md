# HTTP Server

for example :  
fetch('http://localhost:3000/friends', {
    method: 'POST',
    body: JSON.stringify({ id: 3, name: 'Camus' })
})
.then((response) => response.json())
.then((friend) => console.log(friend));