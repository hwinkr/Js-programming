# YOUTUBE 김버그 드롭다운 실습
[링크](https://www.youtube.com/watch?v=X0bf0hfE3qA)<br />
***
### 이벤트 위임
```
function optionHandler(event){
    console.log(event.target)
    console.log(event.currentTarget)
    let value = event.target.innerText
    toggleBtn.innerText = value
    toggleBtn.classList.add('selected')
    menu.classList.remove('show')
    nextBtn.removeAttribute('disabled')
}

menu.addEventListener('click' , optionHandler)
<<<<<<< HEAD
```
=======
```
>>>>>>> 1ed70e922c38026c387d2ab69587a5522f8c0bf7
