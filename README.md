# dev_H2O
Workspace and Notes for H2O

#### Downloads and Environment Setup
- Data
  - [https://github.com/h2oai/h2o-meetups/find/master](https://github.com/h2oai/h2o-meetups/find/master) <br/>

- Info
  - Difference between mojo.zip and genmodel.jar
    [https://stackoverflow.com/questions/49864021/h2o-whats-the-difference-between-mojo-zip-file-and-genmodel-jar-file](https://stackoverflow.com/questions/49864021/h2o-whats-the-difference-between-mojo-zip-file-and-genmodel-jar-file) <br/>

#### Github Links
- [https://github.com/h2oai/sparkling-water.git](https://github.com/h2oai/sparkling-water.git) <br/>

Using Spark v2.4 <br/>
- [http://h2o-release.s3.amazonaws.com/sparkling-water/spark-2.4/latest.html](http://h2o-release.s3.amazonaws.com/sparkling-water/spark-2.4/latest.html) <br/>

Step-by_step Example Setup and Walkthrough: <br/>
1) Clone following github repo:
   ```
   $git clone https://github.com/h2oai/sparkling-water.git
   $cd sparkling-water/examples
   $gradle assemble
   ```
   ![https://github.com/lel99999/dev_H2O/blob/main/gradle_assemble-01.png](https://github.com/lel99999/dev_H2O/blob/main/gradle_assemble-01.png) <br/>
   ![https://github.com/lel99999/dev_H2O/blob/main/gradle_assemble-02.png](https://github.com/lel99999/dev_H2O/blob/main/gradle_assemble-02.png) <br/>
   
   
2) Gradle is a build automation tool. To view available gradle commands: <br/>
   `$gradle tasks` <br/>
   ![https://github.com/lel99999/dev_H2O/blob/main/sparkling-water_gradle_tasks-01.png](https://github.com/lel99999/dev_H2O/blob/main/sparkling-water_gradle_tasks-01.png) <br/>
   
3) Go to Examples directory, and build the jar
   ```
   $cd 
   $gradle build
   ```
#### Data Model Guide
