# ROS_Bootcamp
Repository That Talk's About All Basic Features Of ROS As a Part Of The ROS

  1.  What is ROS,And it's merits and limitations for Roboticists?
And:. ROS, which means Robot Operating System,is a set of software libraries and tools to help you build robot applications.
      The point of ROS is to create a robotics standard,so you don't need to reinvent the wheel anymore when building a new 
      Robotic software.

      Merits of ROS:
      The hardware abstraction and it's ability to control a robot without the user having to know all of the details of 
      The robot.
 
      Limitations of ROS:
      If you are running a ultra low powered system such as just a microcontroller then you might not be able to afford
      The overhead required to run ROS




   2. Explain in own words the basic ROS technology:
      a.Workspace:A catkin workspace is a folder where you modify built and install cakin packages.
        The following is the recommended and typical catkin workspace layout:
        workspace_folder/
      
      b.Ros package: A ROS package is simply a directory descended from ROS_PACKAGE_PATH that has a package.xml file in it.
        Packages are the most atomic unit of build and the unit of release
    
      C.Nodes:nodes are combined into a graph and communicate with each other using ROS topics,services,actions,ect.

      D.Topics:the information in ROS is called a topic.A topic defines the types of messages that will be sent concering that topic
        the nodes that transmit data publish the topic name and the types of messages to be sent the actual data is published by the node.

      E.messages:A message is a simple data structure comprising typed files. Standard primitive types are supported as are Arrays of primitive types.
        Messages can include arbitrarily nested structures and arrays.

      F.Services:services are another way to pass data between nodes in our services are just synchronous remote procedure calls they allow one node to call a function that executes in another node we define the inputs and outputs of the function similarly to the way we define new messages types
