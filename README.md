<div align = "center">
  <h1>Yah-ho👋 Welcome Geeks!🤓</h1> 
  <h4>(_　_)。゜zｚＺ</h4>
<h2>情報工学科1年生 !💻</h2>
<h3>I'm currently working on</h3>
<div align ="left">
  
```
puts("UX-UI Designs🎨");
puts("Front-End Development💻");
```
</div><br>

  <img src ="https://i.pinimg.com/originals/f8/94/19/f89419c5bc4357c8686eb7ab380ed61c.gif" alt ="yuichan"> </div>
</div><br>

<h3>Labor of Love💕</h3>

```
puts("Playing a guitar 🎸");
puts("Photography & VDO-graphy📸");
puts("Baking🥐");
```

```
SELECT* FROM World
WHERE "Someone"
LIKE'%You%' 
...
/>no results!
```


<h3 align="left">Languages and Tools:</h3>
<p align="left"> <a href="https://developer.android.com" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/android/android-original-wordmark.svg" alt="android" width="40" height="40"/> </a> <a href="https://www.arduino.cc/" target="_blank" rel="noreferrer"> <img src="https://cdn.worldvectorlogo.com/logos/arduino-1.svg" alt="arduino" width="40" height="40"/> </a> <a href="https://www.cprogramming.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/c/c-original.svg" alt="c" width="40" height="40"/> </a> <a href="https://www.w3schools.com/cpp/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/cplusplus/cplusplus-original.svg" alt="cplusplus" width="40" height="40"/> </a> <a href="https://www.w3schools.com/css/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original-wordmark.svg" alt="css3" width="40" height="40"/> </a> <a href="https://www.figma.com/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/figma/figma-icon.svg" alt="figma" width="40" height="40"/> </a> <a href="https://firebase.google.com/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/firebase/firebase-icon.svg" alt="firebase" width="40" height="40"/> </a> <a href="https://git-scm.com/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg" alt="git" width="40" height="40"/> </a> <a href="https://www.w3.org/html/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original-wordmark.svg" alt="html5" width="40" height="40"/> </a> <a href="https://www.adobe.com/in/products/illustrator.html" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/adobe_illustrator/adobe_illustrator-icon.svg" alt="illustrator" width="40" height="40"/> </a> <a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" alt="javascript" width="40" height="40"/> </a> <a href="https://www.mysql.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original-wordmark.svg" alt="mysql" width="40" height="40"/> </a> <a href="https://nextjs.org/" target="_blank" rel="noreferrer"> <img src="https://cdn.worldvectorlogo.com/logos/nextjs-2.svg" alt="nextjs" width="40" height="40"/> </a> <a href="https://nodejs.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-original-wordmark.svg" alt="nodejs" width="40" height="40"/> </a> <a href="https://www.python.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="40" height="40"/> </a> <a href="https://tailwindcss.com/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/tailwindcss/tailwindcss-icon.svg" alt="tailwind" width="40" height="40"/> </a> </p> <br>
<div align ="center" width: full-screen>
<img src = "https://pa1.narvii.com/6168/cee6539f62b473d7192fc90940d547d78f41aafc_hq.gif" alt ="hanabi">
</div><br>

```
import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        int N = scanner.nextInt();
        
        for (int i = 0; i < N; i++) {
            int Q = scanner.nextInt();
            for (int j = 0; j < (Q / 2) + (Q / 4) + 1; j++) {
                for (int k = 0; k < Q; k++) {
                    if (j < Q / 4) {
                        if (Q % 4 < 2) {
                            if (k >= (Q / 2) - (Q / 4) - j && k <= (Q / 2) - (Q / 4) + j) {
                                System.out.print("#");
                            } else if (k >= (Q / 2) + (Q / 4) - j && k <= (Q / 2) + (Q / 4) + j) {
                                System.out.print("#");
                            } else {
                                System.out.print(".");
                            }
                        } else if (Q % 4 > 2) {
                            if (k >= (Q / 2) - (Q / 4) - j - 1 && k <= (Q / 2) - (Q / 4) + j) {
                                System.out.print("#");
                            } else if (k >= (Q / 2) + (Q / 4) - j && k <= (Q / 2) + (Q / 4) + j + 1) {
                                System.out.print("#");
                            } else {
                                System.out.print(".");
                            }
                        }
                    } else if (j == Q / 4) {
                        System.out.print("#");
                    } else if (j > Q / 4) {
                        if (k >= j - Q / 4 && k < Q - (j - Q / 4)) {
                            System.out.print("#");
                        } else {
                            System.out.print(".");
                        }
                    }
                }
                System.out.println();
            }
        }
        scanner.close();
    }
}
```
[![Ashutosh's github activity graph](https://github-readme-activity-graph.vercel.app/graph?username=yiiipunn&theme=dracula)](https://github.com/ashutosh00710/github-readme-activity-graph)
[![trophy](https://github-profile-trophy.vercel.app/?username=yiiipunn&theme=onedark)](https://github.com/ryo-ma/github-profile-trophy) <br>
[![An image of @yiiipunn's Holopin badges, which is a link to view their full Holopin profile](https://holopin.me/yiiipunn)](https://holopin.io/@yiiipunn)
