## Borisov Vladislav Alexandrovich


telephone: <u>+79027603429</u>
e-mail: <u>borisovlad_98@bk.ru</u>
rs-school Discord: titor29

---

__About me:__ I can do everything you teach me. Give me some money

### Skils
* Git
* C++, UE4
* HTML5, CSS, JS
* VS Code, Visual Studio
* Multisim, DipTrace, Active HDL, CorelDraw, MathCad, Labview
---
### Some code

```
/* Нахождение объектов по ID */
let form=document.getElementById("main_form");

/* подписка на эвенты */
form.addEventListener("submit", check_form);
let testus=document.getElementById('NB_Cont');
class Person{
    constructor(form){
        this.name=form.Name_Place.value;
        this.password=form.Password_Place.value;
        this.t_number=form.t_nomber.value;
        this.gender=form.gender.value;
        //this.info=form.info.value;                      
    }    

    Show_Info(){        
        console.log("Имя: "+this.name);
        console.log("Пол: "+this.gender);
        console.log("Пароль: "+this.password);
        console.log("Телефон: "+this.t_number);
        //console.log("Дополнительная информация: "+this.info); 
    }
}

function check_form(event){
    event.preventDefault();

    let name=form.Name_Place.value;
    let password=form.Password_Place.value;
    let password_conf=form.Password_Place_2.value;
    let gender=form.gender.value;

    let error_type=" ";
    if (name=="" || name.length<5) {
        error_type="Введите корректное имя";
    }

    else if (password=="" || password.length<5) {
        error_type="Пароль хуйня";
    }
    else if (password!=password_conf) {
        error_type="Пароли не совпадают";
    }
    else if (gender!="Мужской" && gender!="Женский") {
        error_type="Пидорам тут не рады";
    }
    if (error_type!=" ") {
        document.getElementById("error_div").style.color="red";
        document.getElementById("error_div").textContent=error_type;
    }
    else{
         document.getElementById("error_div").style.color="green";
         document.getElementById("error_div").textContent="Всё ок";
        
        
         let New_Person=new Person(form);
         let But_Holder=document.createElement('button');
         But_Holder.classList.add("NB_Style_Class");        
         But_Holder.textContent=New_Person.name;
         testus.appendChild(But_Holder);
         
         
         But_Holder.addEventListener("click", function () {New_Person.Show_Info()});

         form.reset();
    }
}
```

---

__Experience:__ <u>no experience</u>

---

### Education

* Higher education, Master's degree
 specialty; Electronics and Nanoelectronics	
Form of study: full-time
Faculty of Technical Cybernetics, AnGTU, Angarsk

* Game development on Unreal Engine 4	
Geekbrains educational institution, remotely
---

### English skill:

<u>Horoshiy</u>
