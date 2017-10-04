<p align="center"><img width="40%" src="media/logo.png" /></p>

-------------------------------------------------------------------------------

*This is a project created by Tiger Feng, Peter Huang, George Yu and Charlie Zhu for the project of the 2017 Shanghai hack.init() hackathon.*

The basics of Classroom Pi is a monitoring and tracking system, but we have combined it with software and data, to achieve a multi-functional product. Using Classroom Pi, teachers are able to take attendance more efficiently and more conveniently, thus saving many time that are otherwise wasted. Students can use this system to find friends and teachers easily. Administrative staffs can use this system to track and collect students' attendance data, which can act not only as a reference of the student's behavior and attitude, but also as a method to find a specific student under emergency situations, and thus minimizing any possible hazards. Furthermore, using Classroom Pi's numerous features, we can make extended system, such as tracking the elders' position in nursing homes; locating prisoners' location and status in jails; fast check-in process in businesses, etc. All these functionalities make Classroom Pi a very useful product.

**Check out our introduction video of Classroom Pi [over here](https://cache.peterhuang.cn/video2.mov).**

## Idea
In our school, before every class, the teachers will need to spend quite a lot of time taking attendance. And, if the teacher forgot about it, our school assigned a teacher to just go around and remind the teachers to take attendance. We think this system is really time-wasting and inefficient, and also a waste of staff resources, therefore, the idea of Classroom Pi came into our minds.

## Technology
We used Raspberry Pi as the server side device that is picking up the device from the bands. It uploads the data from the bands to the main server, where the data is processed by a Python script, and then deployed to the user-side H5 pages, allowing fast, easy connection.

## Design
We have put a lot of efforts into the design and UI/UX of the product, for our intention was to make the attendance-taking process faster and easier. So we need to provide the users with the fastest and easiest access to the data they want. In the landing page, we visualized the data in the server using a pie chart, allowing for a general understanding of the data at just one quick glance. In locating the students, we used a visualization of the position on a map, and not just pale texts, this allows the user to have a intuitive and audio-visual knowledge of the data.
In the designing of the webpage, we have adopted Google's Material Design language, to allow a clean UI without losing a tinge of joy, in order to give comfortable experiences to the users.
In the designing of the satellite, we used the rounded cube, and used clean white exterior, to allow great experience to the users and minimize the feeling of being watched.
