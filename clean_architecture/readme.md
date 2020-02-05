# Clean Architecture, Martin

## Notes
1. Матрица Эйзенхауэра - "есть два вида дел: срочные и важные. Срочные, как правило, не самые важные, а важные - не самые срочные.
2. Парадигмы 
  * Структурная - отказ от прямой передачи управления
  * ООП - отказ от косвенной передачи управления, дает, посредством поддержки полиморфизма, абсолютный контроль над всеми зависимостя- ми в исходном коде
  * Функциональная - отказ от операции присваивания
3. SOLID [wiki](https://en.wikipedia.org/wiki/SOLID)
  * S - SRP - Single Responsibility Principle - "Модуль должен иметь одну и только одну причину для изменения."
  * O - OCP - Open-Closed Principle - "Программные сущности должны быть открыты для расширения и закрыты для изменения."
  * L - LSP - Liskov Substitution Principle - "свойства подстановки: если для каждого объекта o1 типа S существует такой объект o2 типа T, что для всех программ P, определенных в терминах T, поведение P не изменяется при подстановке o1 вместо o2, то S является подтипом T"
  * I - ISP - Interface Segregation Principle - "разделять реализацию и интерфейс"
  * D - DIP - Dependency Inversion Principle - "наиболее гибкими получаются системы, в которых зависимости в исходном коде направлены на абстракции, а не на конкретные реализации" 
4. Principles of package cohesion [wiki](https://en.wikipedia.org/wiki/Package_principles)
  * REP - Reuse/Release Equivalence Principle — принцип эквивалентности повторного использования и выпусков;
  * CCP - Common Closure Principle — принцип согласованного изменения;
  * CRP -  Common Reuse Principle — принцип совместного повторного использования;
  ![image](https://adriancitu.files.wordpress.com/2017/11/componetcohesion.jpg?w=401&h=294)
5. Principles of package coupling [wiki](https://en.wikipedia.org/wiki/Package_principles)
  * ADP - Acyclic Dependencies Principle - "Циклы в графе зависимостей компонентов недопустимы";
  * SDP - Stable-Dependencies Principle - "Зависимости должны быть направлены в сторону устойчивости".
  * SAP - Stable-Abstractions Principle - "зависимости должны быть направлены в сторону абстрактности". 
  * Метрика: 
    * неустойчивость `I = Fan-out ÷ (Fan-in + Fan-out)`, где `Fan-in` (число входов): количество входящих зависимостей, `Fan-out` (число выходов): количество исходящих зависимостей
    * абстрактность `A = Na ÷ Nc`, где `Nc`: число классов в компоненте, `Na`: число абстрактных классов и интерфейсов в компоненте
  
  ![image](https://www.prototechsolutions.com/wp-content/uploads/2019/07/blog-image-3-website.png)
