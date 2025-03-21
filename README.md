```Java

public class Programmer extends Person implements Carrer {
    // knowledges
    private String[] languageProgram = {"Java", "PHP", "Javascript", "SQL"};
    private String[] frameworksBack = {"Spring", "Laravel", "Express"};
    private String[] frameworksFront = {"Next.JS, Vue.JS, Vite.JS"};
    
    public Programmer(String name, Integer age){
      super(name, age);
    }

    @Override
    public String welcomePerson(){
      return "Hello, my name is " + super.name + ", i am a " + super.age + " years old" +
             " and an aspiring programmer open for jobs.";
    }

    @Override
    public String carrerObjectives(){
       return "My goal is to enter the web development career, you can see my projects below.";
    }

    // Yes Java is verbose and so my readme :D
}

public class Main {
  public static void main(string[] args){
      Programmer me = new Programmer("André", 24);

      System.out.println(me.welcomeProgrammer());
      System.out.println(me.carrerObjectives());
  }
}

```
