# Threat Detection and Remediation Workshop
## Workshop Delivery Instructions

Anyone with interest, time and students can deliver this workshop. Everything needed to deliver the content is available in this repository. This workshop is designed take individuals with a 200-300 level understanding of AWS and provide them with the tools and knowledge they need to get started with threat detection on AWS. The following directions are meant for the prospective instructor(s).

### Workshop description you can share with students:
Join us for this hands-on workshop where you learn about a number of AWS services involved with threat detection and remediation by walking through some real-world threat scenarios. Learn about the threat detection capabilities of GuardDuty, Macie and Config and the available remediation options. In each hands on scenario we look at methods to investigate and remediate a threat. We will use the following services: AWS CloudFormation, Amazon S3, AWS CloudTrail, Amazon VPC flow logs, Amazon CloudWatch events, Amazon SNS, Amazon Macie, DNS Logs, AWS Lambda, AWS Config, Amazon Inspector and, of course, Amazon GuardDuty. 

### Initial setup and planning:

1. The workshop was designed to be delivered in about 2 hours. Even with this timing some students may not be able to finish the entire workshop. When you get to module 4 it is possible some students will still be working through module 3. Ideally if you could devote 3 hours to the workshop there will be a greater chance that all of the students will finish the exercises. 
2. The workshop has been delivered to audiences of between 20 and 150 people and there are no practical limits in audience size.
3. There is about 50 minutes of lecture and presentations and the rest of the time should be devoted to having the students work through the exercises.
4. The students should not use their work AWS accounts for the labs. Ideally new accounts should be created before the workshop for each student.
5. The workshop is designed for each student to work individually but there is no reason why the students couldn't work in groups with one person driving.

### Workshop Directions:

#### Module 1
	
1. Start the workshop by displaying the module 1 presentation slides. This is designed to introduce the workshop and get the attendees started on module 1. 
2. The presentation ends with directing the students to begin the module 1 exercises (which involves running a CloudFormation template and taking some manual actions). 
4. When the students begin the module 1 exercises the instructor(s) should walk around to assist anyone having difficulty. 
5. Total time for module 1 (including the presentation) is about 20 minutes. 
	
#### Module 2

1. After you have given the students time to complete the module 1 exercises (not everyone will complete this in time - you should start the module 2 presentation though within 20 minutes of starting the workshop.) Start by displaying the module 2 presentation slides. 
2. The first step is to have the students run the CloudFormation template in module 2. The template will create a stack that will launch a number of resources in order to simulate an attack. The simulation can take up to 20 minutes to complete. Give the students about five minutes to run the template.
3. Now start the full module 2 presentation. This will be the longest presentation in the workshop and has the side effect of allowing enough time to transpire so that the simulation can complete.
4. Module 2 ends with telling the students to get started with the module 3 exercises. The exercises represent the bulk of the student activities. 
5. Total time for module 2 (including the presentation) is about 40 minutes.
	
#### Module 3

1. There is no presentation to show for module 3. At this point the instructor(s) should walk around to assist anyone having difficulty with the exercises. 
2. Total time to complete the module 3 exercises is about 45 minutes. It is possible that not all of the students will complete the exercise in that time.
	
#### Module 4

1. Start module 4 by displaying the module 4 presentation slides. You want to do this when there are about 15 minutes left in the time allotted for the workshop. You can also start earlier if all the students are done with the module 3 exercises.
2. Module 4 is used to educate the students about how the attack simulation was actually carried out and to do some review questions to test their understanding of the material. A prize or prizes can be given out here for good answers to some of the more difficult questions (like the final question.)
3. Module 4 should end with a reminder to clean up the resources that were created in the workshop. Some students may still be working on module 3 at this point so just remind them to do the cleanup when they finish. The module 4 exercises show how to cleanup all the resources.
4. Total time for module 4 (including the presentation) is about 15 minutes.		 