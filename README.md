# javascript

local storage
code:

const  = JSON.parse(localStorage.getItem('')) ||
{
   property: string,
   property: string,
   property: string,
    };//here is the javascript style

localStorge.setItem('', JSON.stringify(''))//we need change to json style
//then it will save this object into the local storage

to remove the data
localStorage.removeItem('')


DOM

document.title = ''
//it changes the title

<button></button>
document.querySelector('button')
// querySelector will choose the tag/element that we need inside the HTML body

<button class='js-button'></button>
document.querySelector('.js-button')
// querySelector will choose the class/class selector that we named

.innerHTML
//it can select the information inside the HTML body

<button>Hello</button>
document.querySelector('button')
  .innerHTML = 'changed'
//it changes the selection of the information inside the HTML body to other string text
// result: <button>changed</button>


.innerText
// the text inside the element 


example 
function subscribe() {
                const buttonElement = document.querySelector('.js-subscribe-button');
                  if(buttonElement.innerText === 'Subscribe'){
                      buttonElement.innerHTML = 'Subscribed';
                  } else {
                      buttonElement.innerHTML = 'Subscribe'
                  }
              }
// to change the subscribe button from subscribe to subscribed after clicking it

HTML:
<p class='js-text'></p>
JavaScript:
const score.win = 1;
document.querySelector('.js-text')
  .innerHTML = `Wins: ${score.wins}`

//showing in the browser: it will show 'Wins: 1', even we do not type anything inside the <p> element
  

.classList 
//gives us control of the class attribute
.clsssList.add()
.classList.remove()

for the above example 
buttonElement.classList.add('is-subscribed')
buttonElement.classList.remove('is-subscribed')

css:
.is-subscribed {

}


.value
//allows you to get the value inside the element <input> when people typing in the browser

const inputElement = document.querySelector('')
const name = inputElement.value
console.log(name)


advanced function:

addEventerListener('even', function)

buttonElement.addEventListener('click')//it will run the code when we click , it can be used to replace onclick function

buttonElement.addEventListener('click', () => {
  console.log('click)
})
//it prints out 'click' when you click the button

example:

document.body.addEventListener('keydown', (event) =>{
    if (event.key === 'r') {
        playGame('rock');
    } else if (event.key === 'p') {
        playGame('paper')
    } else if (event.key === 's') {
        playGame('scissors')
    }
});

//it can replace the keydown function 



//for amazon product

data attribute
just an HTML attribute
start with 'data-'
then give it any name 

suhc as 
<button data-product-name = "${product.name}"></button>

then in side the script :
  button.addEventListener('click', () => {
      button.dataset.productName;//prouduct-name => productName//
      //it will only show the product name 
      //dataset basically give us all the data attributes that are attached to this button
  })






