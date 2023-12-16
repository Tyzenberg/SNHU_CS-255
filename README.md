# SNHU_CS-255

Briefly summarize the DriverPass project. Who was the client? What type of system did they want you to design?
  DriverPass wanted to implement an LMS to their current student driver training. They system would start with 3 training packages offering varying levels of in person training as well as online training. However, DriverPass didn't want these packages to be perminent, they wanted to be able to edit, remove, and add packages. They also requested to receive a notification when the DMV made an update, as well as being able to download Excel reports on their trainers.

What did you do particularly well?
  DriverPass put an emphasis on being able to update their packages and training, so I wanted to build a system that would make it user friendly for the company and the students. I also tried to find a good mix of security and functionality. There are multiple credential checks as well as a cap on login attempts to prevent a brute force attack. Two factor authentication is only used on Admin side, giving quicker and easir access for customers. 

If you could choose one part of your work on these documents to revise, what would you pick? How would you improve it?
  The notification from the DMV was the worst section of my project. There wasn't much clarity on if DriverPass already has a way to be notified from the DMV, or if we would have to find a way to get that notification. I think I listed it as a limitation, if not, I meant to. If this was a real-world scenario, I would have asked for more detail from DriverPass.


How did you interpret the user’s needs and implement them into your system design? Why is it so important to consider the user’s needs when designing?
  I mentioned this in the section I thought I did well. I used a good mix of security with ease of use for the customer, but also focused on ease of use for the DriverPass employees. Trainers have a system to block off time for vacation, students can't schedule if the trainers time is blocked off. I made the training packages a Class with the idea that DriverPass would have a template UI where they could add/remove/edit training packages. This is a much better alternative than asking a programmer to adjust code.


How do you approach designing software? What techniques or strategies would you use in the future to analyze and design a system?
  The first step is understanding customer needs, what do they want, how do they want it to perform. I theorize an idea, then look into similar systems to see what they are doing. They don't have to be too similar, but getting ideas as simple as locking an account after 3 incorrect login attempts helps build new ideas and tie the system together. I like to think of the different Use Cases and build an idea of how the system will work from a top level, before diving deeper into more technical diagrams like a Class Diagram.
