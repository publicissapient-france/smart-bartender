# smart-bartender

The purpose of this project is to build an end-to-end solution of a smart bar by using cloud technologies, mainly amazon cloud services.

## Description:
A PiCamera connected to a Raspberry pi is able to reconize drinks in a bar (beers, sodas, water) and send the reconized object to the cloud. In the cloud, the reconized object is registred in DynamoDB And an order of the drink is launched. The front part shows a visualization of the total numeber of orders launched  in the bar.

The project contains 3 main parts that correspond to the 3 following folders:

### Edge:

This part implements the Edge computing part that can be deployed on a Raspberry pi 3B using Greengrass Aws.

### Back:

This part implements the Back-end part using AWS IoT Core platform.

### Front:

This part implements the Front-end part of the project. It's shows the numbers of drinks ordered in the bar.