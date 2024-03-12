# Project 03: ROS 2

## Timeline

Activity                   | Deadline
-------------------------- | ------------------------------
Regular Commits:  | March 12th-26th, 2024 (total: 13 commit requirement, at least 1 on March 12th and 1 on March 19th)
Peer Interview (Google Form) | March 19th, 2024 during class
Final Submission: | March 26th, 2024 by 2:30pm

## Class Community Guidelines

Throughout the completion of this project you must adhere to the [course guidelines](https://github.com/CMPSC-304-Robotic-Agents-Spring-2024/course_information) that we developed as a class. To report any violations of the code of conduct, please submit an [anonymous form](https://forms.gle/tePfnLY12hyN1Xbd6). Students who think that the class should revise some aspect of the guidelines must use the GitHub issue tracker for that repository to suggest, discuss, and implement any required changes.

## Summary

This project assignment invites you to expand your knowledge of the Robot Operating System (ROS) by learning how to create packages and workspaces, and implement and use core ROS concepts. Specifically, you are to work individually to complete a set of ROS2 Humble tutorials, taking a screenshot of each one to demonstrate completion, and to reflect on your experiences in writing in the file `writing/report.md`. `writing/report.md` is a Markdown file that must adhere to the standards described in the [Markdown Syntax Guide](https://guides.github.com/features/mastering-markdown/). You will also engage in peer interviews mid-way through this project to discuss your understanding of concepts from the tutorial.

## Learning Outcomes

These assignment learning outcomes contribute to the following course learning outcomes described in the [course syllabus](https://github.com/CMPSC-304-Robotic-Agents-Spring-2024/course_information):

3. Demonstrate the use of a robot operating system (ROS) in simulation and in wheeled robots.
4. Demonstrate actuating, sensing, locomotion, navigation, manipulation, and learning capabilities of robotic systems.

## Instructions

Complete the following tutorials:

### Beginner: Client Libraries

- [Using colcon to build packages](https://docs.ros.org/en/humble/Tutorials/Beginner-Client-Libraries/Colcon-Tutorial.html)
  - Include a screenshot of a terminal showing subscriber and publisher nodes demo running
- [Creating a workspace](https://docs.ros.org/en/humble/Tutorials/Beginner-Client-Libraries/Creating-A-Workspace/Creating-A-Workspace.html)
  - Include a screenshot showing "MyTurtleSim" (overlay)
- [Creating a package](https://docs.ros.org/en/humble/Tutorials/Beginner-Client-Libraries/Creating-Your-First-ROS2-Package.html) (Python)
  - Include a screenshot of a terminal showing your package running (output from step 4)
- [Writing a simple publisher and subscriber (Python)](https://docs.ros.org/en/humble/Tutorials/Beginner-Client-Libraries/Writing-A-Simple-Py-Publisher-And-Subscriber.html)
  - Include a screenshot of a terminal showing outputs from step 4
- [Writing a simple service and client (Python)](https://docs.ros.org/en/humble/Tutorials/Beginner-Client-Libraries/Writing-A-Simple-Py-Service-And-Client.html)
  - Include a screenshot of a terminal showing outputs from step 4
- [Creating custom msg and srv files](https://docs.ros.org/en/humble/Tutorials/Beginner-Client-Libraries/Custom-ROS2-Interfaces.html)
  - Include a screenshot of a terminal showing output from running `py_srvcli service` and `py_srvcli client`
- [Implementing custom interfaces](https://docs.ros.org/en/humble/Tutorials/Beginner-Client-Libraries/Single-Package-Define-And-Use-Interface.html)
  - Include a screenshot of a terminal showing output from running `topic echo`
- [Using parameters in a class (Python)](https://docs.ros.org/en/humble/Tutorials/Beginner-Client-Libraries/Using-Parameters-In-A-Class-Python.html)
  - Include a screenshot of a terminal showing output from running the node using created launch file (end of step 3.2)
- [Using ros2doctor to identify issues](https://docs.ros.org/en/humble/Tutorials/Beginner-Client-Libraries/Getting-Started-With-Ros2doctor.html)
  - Include a screenshot of a terminal showing output from running the full report

### Intermediate

- [Managing Dependencies with rosdep](https://docs.ros.org/en/humble/Tutorials/Intermediate/Rosdep.html)
  - Include a screenshot of a terminal showing `rosdep` installation
- [Creating an action](https://docs.ros.org/en/humble/Tutorials/Intermediate/Creating-an-Action.html)
  - Include a screenshot of a terminal showing output from step 2
- [Writing an action server and client (Python)](https://docs.ros.org/en/humble/Tutorials/Intermediate/Writing-an-Action-Server-Client/Py.html)
  - Include a screenshot of a terminal showing output from running the action client

## Peer Interview

Class members will engage in peer interview process, where they will pair up and involve each other in a discussion of specific topics covered in the tutorials. The topics for selection are listed in the [Peer Interview Assessment Google Form](https://forms.gle/wGaoaEfZxdKH6XNB9) that each person must complete and submit. Student who does not submit a peer interview assessment form, will lose all of the points for this part of the assignment. The members will rank the discussion based on the criteria identified in the [Peer Interview Assessment](https://forms.gle/wGaoaEfZxdKH6XNB9).

## Resources

### ROS2 Humble

ROS2 Humble has been installed on the following machines in ALIC:

#5, 
#6, 
#10, 
#11, 
#12, 
#13, 
#14, 
#18, 
#19, 
#20,  
#21, 
#22, 
#24

Assuming you are working on Windows, open PowerShell and run the following command:
`Get-ExecutionPolicy`. If it says "Restricted", run the following command: `Set-ExecutionPolicy Unrestricted` and Enter `A`. 

Now run `Unblock-File C:\dev\ros2_humble\local_setup.ps1` and then run the "source" command, which is `C:\dev\ros2_humble\local_setup.ps1` on Windows, in PowerShell.

After starting each terminal window, you must run `source` command:

`C:\dev\ros2_humble\local_setup.ps1`

## Assessment

The grade that a student receives on this assignment will have the following components.

- **GitHub Actions CI Build Status [up to 5%]:**: For project3 repository associated with this assignment students will receive a checkmark grade if their last before-the-deadline build passes.

- **Mastery of Verbal Explanation during the Peer Review [up to 15%]:**: Since the ability to communicate technical concepts is crucial to building successful software and hardware applications, a portion of students' lab grade will be determined based on the quality of the discussions during peer interviews. Student who does not submit a peer interview assessment form, will lose all of the points for this part of the assignment.

- **Mastery of Technical Writing [up to 25%]:**: Students will also receive a part of their grade when the responses to the writing prompts presented in the `report.md` reveal a proficiency of both writing skills and technical knowledge. To receive full points of this component, the submitted writing should have correct spelling, grammar, and punctuation in addition to following the rules of Markdown and providing complete and conceptually and technically accurate answers.

  - Please note that the "Check Spelling" GitHub Actions check may flag proper nouns or other real words if the dictionary it uses does not contain them. If your "Check Spelling" GitHub Actions check is failing due to a correctly spelled word being incorrectly flagged as "unknown" by CSpell, you will need to add the word to the list of words in `.github/cspell.json`.

- **Mastery of Technical Knowledge and Skills [up to 55%]**: Students will receive a portion of their assignment grade when their project design and implementation reveals that they have mastered all of the technical knowledge and concepts developed during the completion of this project. Successful completion of each  tutorial must be demonstrated by including appropriate screenshots.

- **Continuous Progress [up to 40% deducted points]**: To ensure continuous effort and timely troubleshooting, students may lose up to 40% of points from their final deliverable for not demonstrating continuous effort on this project. There is a requirement of a 13 commit minimum, with at least 1 commit made on March 12th (lab) and March 19th (class). Each activity not submitted by the stated deadline in the [Timeline](#timeline) section  will result in -10% unless you can demonstrate circumstances beyond your control (e.g., illness).

All grades for this project will be reported through a student's gradebook GitHub repository.

### GatorGrade

You can check the baseline writing and commit requirements of this project by running department's assignment checking `gatorgrade` tool To use `gatorgrade`, you first need to make sure you have Python installed. If not, please see:

- [Setting Up Python on Windows](https://realpython.com/lessons/python-windows-setup/)
- [Python 3 Installation and Setup Guide](https://realpython.com/installing-python/)
- [How to Install Python 3 and Set Up a Local Programming Environment on Windows 10](https://www.digitalocean.com/community/tutorials/how-to-install-python-3-and-set-up-a-local-programming-environment-on-windows-10)

Then, you need to install `gatorgrade`:

- First, [install `pipx`](https://pypa.github.io/pipx/installation/)
- Then, install `gatorgrade` with `pipx install gatorgrade`

Finally, you can run `gatorgrade`:

`gatorgrade --config config/gatorgrade.yml`

## Assistance

If you are having trouble completing any part of this project, then please talk with the course instructor or TLs during the laboratory sessions. Alternatively, you may ask questions in the Discord channel for this course. Finally, you can schedule a meeting during the course instructor's office hours.
