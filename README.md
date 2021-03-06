# Software Engineering 2019 
This repo contains a software project and some other stuff for University of Helsinki course on software engineering.

## Tower Defence
**Tower Defence** is a classic tower defence game. The point of the game is to prevent waves of attacking invaders from reaching the end of the maze. This is done by building towers along the way and trying to eliminate as many attacking invaders as possible. Building towers costs gold and gold is acquired via surviving waves and eliminating invaders. There are multiple kinds of towers. There is currently only one types of invaders. The game comes with just one map, but users can create their own maps. [Full Software Requirements Specification](https://github.com/Melimet/TowerDefence/blob/master/documentation/SoftwareRequirementsSpecification.md)

[Software Architecture](https://github.com/Melimet/TowerDefence/blob/master/documentation/SoftwareArchitecture.md)

[User manual](https://github.com/Melimet/TowerDefence/blob/master/documentation/UserManual.md)

[Testing document](https://github.com/Melimet/TowerDefence/blob/master/documentation/TestingDocument.md)

[Timesheet](https://github.com/Melimet/TowerDefence/blob/master/documentation/Timesheet.md)

### Releases
  [Week 5 release](https://github.com/Melimet/TowerDefence/releases/tag/week5)
  
  [Week 6 release](https://github.com/Melimet/TowerDefence/releases/tag/Week6)
  
  [Final release](https://github.com/Melimet/TowerDefence/releases/tag/1.0)
### Commands for terminal

Run unit tests with `mvn test`

Generate jacoco report with  `mvn jacoco:report`

Generate checkstyle report with `mvn jxr:jxr checkstyle:checkstyle`

The jar file can be run by typing in `java -jar TowerDefenceWeek5.jar` while inside folder where the jar file is

Generate javadoc with `mvn javadoc:javadoc`
