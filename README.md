let stars = decument.getElementById('stars');
let moon = decument.getElementById('moon');
let mo3 = decument.getElementById('mo3');
let mo4 = decument.getElementById('mo4');
let rev = decument.getElementById('rev');
let b6 = decument.getElementById('b6');
let code = decument.querSelector('.code');
window.onscroll = function(){
    let value = scrollY;
    stars.style.left = value + 'px';
    moon.style.top = value + 'px';
}    
