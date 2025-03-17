java cAcademic Year: 2024-2025
Assessment Introduction:
Course:
BEng Electronic Engineering
BEng Robotic Engineering
MEng Robotic Engineering	Module Code: EL3105
Module Title: Computer Vision
Title of the Brief: Video Stabilisation	Type of assessment: Assignment
 
Introduction
This Assessment Pack consists of a detailed assignment brief, guidance on what you need to prepare, and information on how class sessions support your ability to complete successfully. The tutor responsible for this coursework will be available on 28th of January 2025 to answer questions related to this assessment. You’ll also find information on this page to guide you on how, where, and when to submit. If you need additional support, please make a note of the services detailed in this document. 
 
Submission details; How, when, and where to submit:
Assessment Release date: 21/01/2025.
Assessment Deadline Date and time: 28/03/2024 (23:59).
Please note that this is the final time you can submit – not the time to submit!
You should aim to submit your assessment in advance of the deadline.
The Turnitin submission link on Blackboard, will be visible to you on: 03/03/2025.
Feedback will be provided by: 06/05/2025.
This assignment constitutes 50% of the total module assessment mark. You should write a report for this assignment documenting your solutions for the tasks defined in the assignment brief given below. The report should include a very short introduction describing the problem, description of your adopted solutions, a more extensive description of the results and conclusions section summarising the results. The report should be approximately 1500 words long, plus relevant materials (References and Appendices). You should use Harvard referencing system for this report. The report should be submitted electronically to “Video Stabilisation”Turnitin through Blackboard.
You should submit a documented matlab/python code solving the given tasks. The code should be self-contained, i.e., it should be able to run as it is, without a need for any additional tools/libraries. In case, there are multiple files please create a single zip code archive containing all the files. The code should be submitted separately from the report into Blackboard EL3105 assignment area denoted as “Video Stabilisation Code”.
Note: If you have any valid mitigating circumstances that mean you cannot meet an assessment submission deadline and you wish to request an extension, you will need to apply online, via MyUCLan with your evidence prior to the deadline. Further information on Mitigating Circumstances via this link.
We wish you all success in completing your assessment. Read this guidance carefully, and any questions, please discuss with your Module Leader. 
 
Teaching into assessment
The tutor responsible for this coursework will be available on 28/01/2025between 14:00 in the 16:00 to answer questions related to this assessment.
All the algorithmic aspects necessary for the successful completion of the assignment have been covered during the lectures, tutorial, and laboratory sessions, these include feature detection, descriptor calculation, robust matching, estimation of a transformation aligning matched features, tracking and image warping.
 
Additional Support
All links are available through the online Student Hub
1. Our Library resources link can be found in the library area of the Student Hub.
2. Support with your academic skills development (academic writing, critical thinking and referencing) is available through WISER on the Study Skills section of the Student Hub.
3. For help with Turnitin, see Blackboard and Turnitin Support on the Student Hub 
4. If you have a disability, specific learning difficulty, long-term health or mental health condition, and not yet advised us, or would like to review your support, Inclusive Support can assist with reasonable adjustments and support. To find out more, you can visit the Inclusive Support page of the Student Hub.
5. For mental health and wellbeing support, please complete our online referral form, or email wellbeing@uclan.ac.uk. You can also call 01772 893020, attend a drop-in, or visit our UCLan Wellbeing Service Student Hub pages for more information.
6. For any other support query, please contact Student Support via studentsupport@uclan.ac.uk.
7. For consideration of Academic Integrity, please refer to detailed guidelines in our policy document . All assessed work should be genuinely your own work, and all resources fully cited.
8. For this assignment, you are not permitted to use any category of AI tools.
 
Assignment Brief
This assignment is designed to give you an insight into selected aspects of computer vision applied to image feature extraction, feature matching, and motion compensation. You are ask代 写program 、 MATLAB/Python
代做程序编程语言ed to solve various tasks including detection of image features and their robust matching, write computer vision software as well as test your solution and interpret the results.
This assignment will enable you to:
• Deepen your understanding of the features/keypoints detection and robust matching between features, image transformation and warping models.
• Recognise software design challenges behind implementations of computer vision algorithms.
• Design and optimise software to meet specified requirements.
• Acquire a hands-on understanding of image-based camera motion compensation.
(These correspond to point 1, 2, 4 and 5 of the module’s learning outcomes. Module learning outcomes are provided in the Module Descriptor) 
 
 
The assignment consists of two main tasks. The first task is to explain and justify your selected methodology for video stabilisation, specifically focusing on camera motion jitter compensation. This should include a discussion of jitter compensation for a moving camera, handling moving objects within the scene, depth of field, and the ability to operate in real-time.
The second task is to implement the selected method using MATLAB and/or Python. You are provided with two pre-recorded videos that increase in scene complexity. The first video features a static scene with a jittering, but otherwise static, camera. The second video contains a scene with moving objects. The two videos, video_seq_1.avi and video_seq_2.avi, are available on the Computer Vision Blackboard site.
You are expected to write a MATLAB (and/or Python) program that removes the apparent scene motion caused by the camera jitter in the video sequences. Your algorithm should be designed to process the images sequentially, meaning that when estimating the current image correction, it should only use the current and preceding frames. Additionally, the algorithm should be optimized to work in real-time, with computational complexity that does not depend on the length of the sequence.
 
 
 
 
Late work 
If the report and/or code are submitted after the deadline they will be automatically flagged as late. Except where an extension of the hand-in deadline date has been approved lateness penalties will be applied in accordance with the University policies.
 
 
Marking scheme
Your report should contain the following elements; it will be marked in accordance with the following marking scheme:
 
Item	Weight (%)
1. Justification of the adopted video stabilisation approach	30
2. Software implementation	40
3. Evaluation of the results	15
4. Presentation of the report	15
Total	100
 
 
References
Wang, Y., Huang, Q., Jiang, C., Liu, J., Shang, M. and Miao, Z. (2023) Video stabilization: A comprehensive survey, Neurocomputing, Volume 516, pp. 205-230.
Wang, A., Zhang, L. and Huang, H. (2018) High-Quality Real-Time Video Stabilization Using Trajectory Smoothing and Mesh-Based Warping. IEEE Access, Vol 6. pp. 25157:66.
Souza, M.R. and Pedrini, H. (2018) Digital Video Stabilization Based on Adaptive Camera Trajectory Smoothing, EURASIP Journal on Image and Video Processing, pp. 2018:37.
Litvin, A., Konrad, J. and Karl, W.C. (2003) Probabilistic Video Stabilization Using Kalman Filtering and Mosaicking. IST/SPIE Symposium on Electronic Imaging, Image and Video Communications and Proc.
Tordoff, B. and Murray, D.W. (2002) Guided Sampling and Consensus for Motion Estimation. European Conference on Computer Vision
 
 
 
 
 
Disclaimer: The information provided in this assessment brief is correct at time of publication. In the unlikely event that any changes are deemed necessary, they will be communicated clearly via e-mail and a new version of this assessment brief will be circulated.

Feedback Guidance:
Reflecting on Feedback: how to improve.
From the feedback you receive, you should understand:
• The grade you achieved.
• The best features of your work.
• Areas you may not have fully understood.
• Areas you are doing well but could develop your understanding. 
• What you can do to improve in the future - feedforward.
 
Use the WISER: Academic Skills Development service. WISER can review feedback and help you understand your feedback. You can also use the WISER Feedback Glossary
Next Steps:
• List the steps have you taken to respond to previous feedback.
• Summarise your achievements 
• Evaluate where you need to improve here (keep handy for future work):
 
 
 
 
Disclaimer: The information provided in this assessment brief is correct at time of publication. In the unlikely event that any changes are deemed necessary, they will be communicated clearly via e-mail and a new version of this assessment brief will be circulated.

         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
