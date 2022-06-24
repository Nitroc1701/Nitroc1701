```bash
┌──(nitroc1701㉿root)-[~/src]
└─$ cat Main.java
```
```java
import java.util.Arrays;
import java.util.List;

public class Main {

    private static String PREFIX = "[ReadMe] ";

    public static void main(String[] args) {
        Project project =  new Project("EverBot", "a discord bot made to be fully customisable. Everything can be change.");
        List<String> languagesKnown = Arrays.asList("Java", "JavaScript", "HTML/CSS", "PHP");
        Developpeur developpeur = new Developpeur("Corentin", "Nitroc1701", 18, "DevOps", languagesKnown,"https://nitroc.xyz", project);

        System.out.println(PREFIX + "Hello, I'm " + developpeur.getName() + " ( " + developpeur.getDisplayName() + " ).");
        System.out.println(PREFIX + "I'm " + developpeur.getAge() + " years old.");
        System.out.println(PREFIX + "I'm currently working on " + project.toString());
        System.out.println(PREFIX + "I'm learning " + developpeur.getLearning() + ".");
        System.out.println(PREFIX + "I know these languages :");
        for (String language : developpeur.getLanguagesKnown()) {
            System.out.println(" - " + language);
        }
        System.out.println(PREFIX + "If you want more detail about me and the different projects I've done, go visit my website : " + developpeur.getPortofolioLink());
    }
}
```
```bash
┌──(nitroc1701㉿root)-[~/out]
└─$ java -jar ReadMe.jar
```
```java
[ReadMe] Hello, I'm Corentin ( Nitroc1701 ).
[ReadMe] I'm 18 years old.
[ReadMe] I'm currently working on Project@1b6d3586
[ReadMe] I'm learning DevOps.
[ReadMe] I know these languages :
 - Java
 - JavaScript
 - HTML/CSS
 - PHP
[ReadMe] If you want more detail about me and the different projects I've done, go visit my website : https://nitroc.xyz
```
<div style="text-align: center;">
  <a href="https://github.com/Nitroc1701">
    <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Nitroc1701&title_color=ff3855&text_color=30d5c8&icon_color=ffff00&bg_color=291b29" />
  </a>

  <a href="https://github.com/Nitroc1701">
    <img src="https://github-readme-stats.vercel.app/api?username=Nitroc1701&show_icons=true&line_height=27&count_private=true&title_color=ff3855&text_color=30d5c8&icon_color=ffff00&bg_color=291b29" alt="Nitroc1701's GitHub Stats" />
  </a>
</div>
