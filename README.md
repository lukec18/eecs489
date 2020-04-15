# EECS 489: Computer Networks (F’20)

## Administrivia
 - Catalog Number: 28220
 - Lectures: 2505 GGBL, MW: 3:30 PM – 5:00 PM
 - Discussion 1: 2150 DOW, F 9:30 AM – 10:30 AM
 - Discussion 2: 1005 DOW, Th 5:00 PM – 6:00 PM
 - Discussion 3: 1014 DOW, F 12:30 PM – 1:30 PM

### Team

| Member (uniqname) | Role | Office Hours |
| :---------------- | :--- | :----------- |
| [Mosharaf Chowdhury](http://www.mosharaf.com/) (mosharaf) | Faculty | 4820 BBB, W: 2:00 PM - 3:30 PM and by appt.
| TBA | GSI |  |
| TBA | GSI |  |

### Piazza
All communication regarding this course must be via [Piazza](TBA). 
This includes questions, discussions, announcements, as well as private messages.

## Lecture Recordings
Available at [https://caen.engin.umich.edu/lecrecording/students/](https://caen.engin.umich.edu/lecrecording/students/).

## Course Description
EECS 489 takes a top-down approach to explore how networks operate and how network applications are written. 
We study how popular distributed systems such as video streaming, content distribution networks (CDNs), and cloud computing systems work in the *application layer*.
We explore how these applications transfer data between their components and end users over the Internet using *transport layer* protocols such as TCP and UDP.
We go deeper to understand what keeps the transport layer running (hint: the *network layer* routes packets for them); specifically, we look at how packets are routed and how routers work.
Finally, we dive one more layer down to understand how the *link layer* transfer packets using Ethernet.
In addition to cutting through the layers and covering the basics, we learn about the state-of-the-art topics in networking such as datacenter networks and software-defined networking (SDN). 

From a practical point of view, we learn what sockets are and how to use them. 
And we write code. 
We write code to implement various protocols, to build client-server applications, HTTP proxies, and video distribution applications, and to learn how to use SDNs.

### Prerequisite

The enforced prerequisite for this course is EECS 281 (Data Structures and Algorithms) and EECS 370 (Introduction to Computer Organization) even though officially it is EECS 482 (Operating Systems). 
The current curriculum of this course does not assume or require any prior knowledge of EECS 482.
Nonetheless, you must have a good working knowledge of C/C++ and Unix family of operating systems.

If needed, you can get an override by signing up [here](https://forms.gle/vaW6x4UsbjFvT6WP7).

### Optional Textbook

- Kurose and Ross, Computer Networking: A Top-Down Approach, 7th. or Earlier Editions, Pearson, 2016. ISBN 978-0133594140.

## Tentative Schedule

| Week of  | Monday | Wednesday | Optional Readings | Assignments
|:---------|:------:|:---------:|:------------------|:----------:
| 08/31/20 | Introduction | Overview | 1.1
| 09/07/20 | **No Class** | Protocol Layering | 1.3, 1.4, 1.5 | A1 Out
| 09/14/20 | HTTP and the Web | DNS and CDN | 2.2, 2.4
| 09/21/20 | Video Streaming and Cloud Systems | Transport Layer | 2.6, 3.1, 3.2, 3.3, 3.4 | A1 Due<br>A2 Out
| 09/28/20 | TCP Basics | Flow and Congestion Control | 3.5, 3.6 | 
| 10/05/20 | More Congestion Control | Network Layer and IP | 3.7, 4.1, 4.3.1, 4.3.2, 4.3.5
| 10/12/20 | IP Routers | Midterm Review | 4.2
| 10/19/20 | **No Class** | **MIDTERM <br> TBA** |  | A2 Due<br>A3 Out
| 10/26/20 | Routing Fundamentals | Routing Algorithms | 5.1, 5.2, 5.3 | 
| 11/02/20 | IP Addressing and Inter-AS Routing | BGP | 4.3.3, 5.4
| 11/09/20 | **No Class** | SDN | 4.4, 5.5 | A3 Due<br>A4 Out
| 11/16/20 | Link Layer | Switched LAN | 6.1, 6.3, 6.4 | 
| 11/23/20 | Datacenter Networks | **No Class** | 6.6
| 11/30/20 | Networking in Datacenters | Wireless | 6.6, 7.1, 7.2, 7.3
| 12/07/20 | Final Review | **No Class** | | A4 Due
| 12/14/20 | **FINAL <br> FRIDAY 12/18/20 <br> 8AM - 10AM <br> TBA** | | | 

## Policies

### Assignments
Four assignments will be assigned during the semester; the first one will be done individually and the rest will be in groups.
Visit [this page](Assignments) for detailed policies on assignments (including late submission policies) as well as the assignments themselves. 

### Exams
There will be two exams during the semester: a midterm exam and the final exam. 
You are expected to take both exams at the scheduled times. 

If you miss an exam for reasons other than a documented medical or personal emergency, you will receive a zero for that exam. 
If you anticipate a conflict with an exam time, talk to the instructor **at least one month** before the exam date. 
Exam dates are given at the beginning of the semester so you can avoid scheduling job interviews or other commitments on those days. 
Outside commitments are not considered a valid reason for missing an exam.

### Attendance and Discussion Sections
You are expected to attend lecture regularly and to be at your discussion section weekly. 
Discussion section meetings will typically involve active participation by discussion, group exercises, or question-and-answer sessions.

## Grading
Final grades will be based on the total points earned on the assignments and exams. 
Factors such as class participation may be used to adjust your final grade, especially if it falls on a borderline. 
The tentative point breakdown is:

|              | Allocation 
| -------------| ----------:
| Assignment 1 |  5%        
| Assignment 2 | 15%        
| Assignment 3 | 15%        
| Assignment 4 | 15%        
| Midterm Exam | 25%        
| Final Exam   | 25%        
