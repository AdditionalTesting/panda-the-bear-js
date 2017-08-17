

1.
var image = document.querySelector(".profile-image")
image.src = 'https://pbs.twimg.com/profile_images/673891811849543680/MxTAuI5a.png'

1.
var image = document.querySelector("#left-image")
image.firstElementChild.src =
     'https://pbs.twimg.com/profile_images/673891811849543680/MxTAuI5a.png'

2.
var firstHeading = document.querySelector('h1.highlight')
firstHeading.innerText = 'AB'

3.
var employment23 = document.querySelector('#employment > h3')
undefined
employment23.innerText = 'cool things'
"cool things"

4.
var coolBody = document.body
undefined
coolBody.style.backgroundColor = 'red'
"red"

5.
var newThing = document.querySelectorAll('.highlight')
undefined
newThing.forEach ( function(color) { color.style.backgroundColor = 'blue'})
undefined

6.
var newColor = document.querySelectorAll('h1')
undefined
newColor.forEach ( function(color) { color.style.fontFamily = 'monospace' })
undefined

7.
var coolThing = document.querySelectorAll('.action-icon-bg')
undefined
coolThing.forEach ( function(color) {color.style.backgroundColor = 'red'})
undefined

8.
