# Software Engineering 2019 
This repo contains a software project and some other stuff for University of Helsinki course on software engineering.

## Tower Defence
Tower Defence is a classic tower defence game. The point of the game is to prevent waves of attacking invaders from reaching the end of the maze. This is done by building towers along the way and trying to eliminate as many attacking invaders as possible. Building towers costs gold and gold is acquired via surviving waves and eliminating invaders. There are multiple kinds of towers and they excel at different things. There are multiple types of invaders. [Full Software Requirements Specification](https://github.com/Melimet/TowerDefence/blob/master/documentation/SoftwareRequirementsSpecification.md)


[Timesheet](https://github.com/Melimet/TowerDefence/blob/master/documentation/Timesheet.md)

### Commands for terminal

Run unit tests with `mvn test`

Jacoco didnt work with only `mvn jacoco:report' so I found this workaround`:
Generate jacoco report with `mvn clean org.jacoco:jacoco-maven-plugin:0.8.3:prepare-agent install org.jacoco:jacoco-maven-plugin:0.8.3:report`

Generate checkstyle report with `mvn jxr:jxr checkstyle:checkstyle`
