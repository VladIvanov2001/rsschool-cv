**1.** **Vladislav Ivanov**

**2.** **Contacts** :     
 &nbsp;&nbsp;&nbsp; *Phone No.* : +375336945132   
    &nbsp;&nbsp;&nbsp; *email* : vladislavivanov440@gmail.com

**3.** I want to become a web-developer to provide my family and myself. Also I want to finish university.

**4.** **My skills**:      
  * HTMl     
  * CSS     
  * Little bit of React and JS;

**5.**  **Code example**

```javascript

        function read (str, restrictedSymbols) {
           return Array.from(str).filter(x => !Array.from(restrictedSymbols).includes(x)).join("");
        }
        function begin() {
            let text = document.getElementsByTagName("textarea")[0].value;
            let array = read(text, ',').split(' ').map(x => +x);
            document.getElementById("max").textContent = "Ваш наибольший элемент массива: " + maxValue(array);
            document.getElementById("min").textContent = "Ваш наименьший элемент массива: " + minValue(array);
            document.getElementById("sum").textContent = "Сумма элементов массивов: " + elementsSum(array);
            document.getElementById("sorted").textContent = "Ваш отсортированный массив: " + sort(array);
        }

        function sort(arr) {
        for(let i = 0; i<arr.length;i++){
            for(let j=0; j < arr.length-i;j++){
                if(arr[j] > arr[j + 1]){
                    let q = arr[j];
                    arr[j] = arr[j + 1];
                    arr[j + 1] = q;
                }
            }
        }
        return arr;
    }

    function elementsSum(arr) {
        let sum = 0;
        for (let i = 0; i < arr.length; i++) {
            sum += arr[i];
        }
        return sum;
    }

    function maxValue(arr) {
        let max = arr[0];
        for (let i = 0; i<arr.length;i++){
            if(arr[i]>max)
                max=arr[i];
        }
        return max;
    }

    function minValue(arr) {
        let min = arr[0];
        for (let i = 0; i<arr.length;i++){
            if(arr[i]<min) {
                min = arr[i];
            }
        }
        return min;
    }
```


**6.** ----


**7.**   **My education**:
  1. MMF BSU : 2-nd year   
  2. MyFreedom courses(HTML, CSS)   
  3. CodeAcademy courses

**8.** **English skills**:   
  English at the university( Math + High Math + IT) + courses at Streamline ( at B2 level)  
