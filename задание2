let txt = document.querySelector('#txt');
let title = document.querySelector('#title');

txt.addEventListener("keyup", (e)=>{
  e.preventDefault();
  setTimeout(replaceTitle, 300);
});

function replaceTitle() {
  title.textContent = txt.value;
  document.title = txt.value;
}
