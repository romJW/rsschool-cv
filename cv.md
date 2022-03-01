# Roman Bukharin

********************
**Contact information:**

Almaty, ALA 
                                                                   
Phone: +7 (707)3386135

Email: buxarin1999@gmail.com


telegram: @RomaJW


Discord: romJW (#4691)


## About me
I finished 3 of 4 years of telecomunications of the Saint-Petersburg Electrotechnical University. I was working at Skyeng online school for 2.5 years as a sales manager with knowledge of English. My responsibilities included: presenting the product, negotiating terms, handling objections and making deals, and filling out a lot of paperwork with real processes. Working for this company taught me a lot. I also got a huge experince of remote work.
After that for last 6 months I've been working as an English tutor for Russian speakers and Russian tutor for English speakers. Also I was interested in frontend since my second year in the University. But due to the lack of time I couldn't spend enough of it for learning programming so I kept postponing it for the better times. Those times came when I left Skyeng and started working as a tutor. I am really interested in getting Frontend development skills and landing my first job in this area. 
I know that learning something is always a long journey but I'll try to do my best to reach the goal.

******************************************


## Skill Higlishts
*	HTML5, CSS3, SASS(SCSS)      
* JavaScript
*	OOP 
*	Git, GitHub
* VS Code
*	Figma

*************************************************

## Code example
*Reverse or rotate? KATA from CodeWars*:
The input is a string str of digits. Cut the string into chunks (a chunk here is a substring of the initial string) of size sz (ignore the last chunk if its size is less than sz).

If a chunk represents an integer such as the sum of the cubes of its digits is divisible by 2, reverse that chunk; otherwise rotate it to the left by one position. Put together these modified chunks and return the result as a string.

If

* sz is <= 0 or if str is empty return ""
* sz is greater (>) than the length of str it is impossible to take a chunk of size sz hence return "".


```
function revrot(str, sz) {
  
  if ( sz<=0 || str=="" || sz > str.length) *return* "";

  let strArr = str.split("");

   let newArr = [];

  for (*let* i = 0; i <= strArr.length; i++){

     if (i % sz==0) newArr.push(strArr.slice((i - sz), i));
   }

    let lastArr = [];

   for (let i = 0; i < newArr.length; i++){

     if (newArr[i].reduce((sum,next) => (sum + Math.pow(+next, 3)),0) % 2 === 0){

      lastArr.push(newArr[i].reverse().join(""));

    }

    lastArr.push((newArr[i].slice(1,newArr[i].length).join("") + newArr[i][0]));
     
   }
    
    return lastArr.join("");
  }


console.log(revrot("123456987654", 6))

```
**********************

## Courses

* HTML and CSS tutorial on youtube
* JavaScript on learnjavascript.ru(in progeress)

******************************

## Languages

* English - Advanced(C1), practice with Americans
