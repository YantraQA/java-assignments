# Java Assignments

This repository contains assignments over different topics on core java. For training purposes.

---

### Assignment - 1 
 [Topics covred - Inheritance, Polymorphism(Overriding)] 

* STEP - I 
Create an project with name "EduationCulture"

* STEP - II 
    Create 3 classes,  
    1. Class Graduation, 
    2. Class Engineering & 
    3. Class ComputerScienceEngg

    Where,
    Class Engineering extends class Graduation & 
    Class ComputerScienceEngg extends class Engineering.

* STEP - III
  Create following methods in respective class
  1. Inside Class Graduation ->
  
      i. streams() as method -> add print line as "BCA, BBA, B.E." inside the method.

      ii. hscPercentage() as method -> add print statement as "for graduation minimun 60% is critera" inside the method.

      iii. ageCritera() as method -> add print statement as "for graduation minimun age critera for cadidate is 20 years" inside the method.

  2. Inside Class Engineering -> (which extends Class Graduation)
  
      i. streams() as method -> add print line as "Computer Sciance, Information Technology, Electronics & Mechanical Engineering"

      ii. typeOfEngineering() as method -> add print line as "Engineeing can be done as Regular as well as from distance learing"

      Note - streams() method in Class Engineering will override the streams() method from Graduation class.

  3. Inside Class ComputerScienceEngg -> (which extends Class Engineering)
  
      i.hscPercentage() as method -> add print statement as "To get admission for Computer Science Engineering HSC percentage should be minimun 65%" inside the method.

      ii. subjects() as methods ->  add print statement as "Core Java, C sharp & Python are subjects offered in Computer Science Engineering" inside the method.

      Note - hscPercentage() method in Class ComputerScienceEngg will override the hscPercentage() method from Graduation class.

* STEP - IV
    Now create an class with name EducationSystem()
  
      Inside main method create objects as following
      
      i. Graduation gd = new Graduation();
      and call all the methods with gd reference variable.
      
      ii. Engineering eg = new Engineering();
      and call all the methods with eg reference variable.
      
      iii. ComputerScienceEngg cse = new ComputerScienceEngg();
      and call all the methods with cse reference variable.

* STEP - V
    Post this entire project inside an github repository & share the URL.
    
 ---
