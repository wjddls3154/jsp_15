# jsp_15 : 단일, 복수 element 반환

![image](https://user-images.githubusercontent.com/37132897/158132665-ec69edb7-17d6-4a19-9d5c-85d052b75594.png)



  // 1. 단일 element 를 반환하는 함수
  
  // document.getElementById('id')
  
  // document.querySelector('query')
  
  // 2. 복수의 element 를 반환하는 함수
  
  // document.querySelectorAll('query')
  
  // document.getElementByName('name')
  
  k = document.getElementsByClassName('one'); // 1. hi world, hi world two, hi world three 출력
  
  console.log(k);
  
  document.write(k['0']['innerHTML']); // 2. hi world 출력
  
  document.write('<br>');
  
  document.write(k['2']['className']); // 3. one two four 출력
