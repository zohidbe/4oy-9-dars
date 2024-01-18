# Lessons - 4 
## Theme: Funtions, while and do-while, switch-case



  // Function Decloration

  function square(x) {
    return x * x;
  }
  square(10);

  // output: 100



  // Function Expression

  const square = function(x) {
    reuturn x * x;
  }




  // Arrow Function Expression

  const square = (x) => {
    return x * x;
  }
  square(10); 

  // output 100


## Switch - case


  let weeksUser = prompt("hafta kunini kiriting");

  switch (weeksUser) {
    case 1:
      console.log('dushanba');
      break;
    case 2:
      console.log('seshanba');
      break;
    case 3:
      console.log('chorshanba');
      break;
    case 4:
      console.log("payshanba");
      break;
    case 5:
      console.log('juma');
      break;
    case 6:
      console.log('shanba');
      break;
    case 7:
      console.log("yakshanba);
      break;
    default:
      console.log("bunaka kun mavjud emas!");
  }


## Do - While Loop

### While

  int i = 0;

  while (i > 0) {
    printf("%d", i);
    i--;
  }


  ### Do - While

  int i = 0;

  do {
    printf("%d", i);
    i--;
  } while (i > 0);



  ##  Var, Let va Const
JavaScriptda o'zgaruvchilarni e'lon qilish uchun bir nechta keywordlar mavjud. Keyinroq 
versiyalarda (ES6 va undan keyin) let va const o'zgaruvchi e'lon qilish uchun kengaytma qo'shdi. 
var, let va constni quyidagi kabi ishlatish mumkin:

// Misol:
var x = 10; // Eskisi usul
let y = 20; // ES6 dan keyin
const z = 30; // ES6 dan keyin, o'zgarmaydigan o'zgaruvchi


##  undefined qiymati, o'zgaruvchiga qiymat bermagan paytda olinadi.


// Misol:
let undefinedValue;
console.log(undefinedValue); // undefined

## Array


Massivlar, o'lchamlari ozgina bo'lgan elementlarni o'z ichiga olgan datalar to'plamidir.

// Misol:
let fruits = ['Apple', 'Banana', 'Orange'];


##  String
Matnlar, qatorlarda yozilgan matn ma'lumotlardir.

// Misol:
let greeting = 'Assalomu alaykum';
