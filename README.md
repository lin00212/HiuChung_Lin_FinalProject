# HiuChung_Lin_FinalProject
```
let today = new Date();
    
    function getDaysUntilChristmas(){
        let christmasYear = today.getFullYear();
        if (today.getMonth() == 11 && today.getDate() > 25) {
            christmasYear = christmasYear + 1;
        }
        let christmasDate = new Date(christmasYear, 11, 25);
        let dayMilliseconds = 1000 * 60 * 60 * 24;
        let remainingDays = Math.ceil(
        (christmasDate.getTime() - today.getTime()) / (dayMilliseconds));
        return remainingDays;
    }
    console.log(getDaysUntilChristmas());
```
![image](/Screenshot%202023-12-12%20at%2011.44.59%20AM.png)
![image](/Screenshot%202023-12-12%20at%2011.50.21%20AM.png)
![image](/Screenshot%202023-12-12%20at%2011.53.13%20AM.png)# HiuChung_Lin_FinalProject
