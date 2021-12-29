const signInButton = document.querySelector('#signInButton');
const signUpButton = document.querySelector('#signUpButton');
const overlay_container = document.querySelector('.container .overlay-container');
const overlay = document.querySelector('.container .overlay-container .overlay');

signInButton.addEventListener('click',()=>{
overlay_container.style.transform = 'translateX(100%)';
overlay.style.transform = 'translateX(-50%)';
});

signUpButton.addEventListener('click',()=>{
    overlay_container.style.transform = 'translateX(0)';
    overlay.style.transform = 'translateX(0)';
    });