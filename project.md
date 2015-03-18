---
layout: page
title: Projects
---

<p>I will try to list all the projects i have worked on both self and guided. I will also list the things I learnt from these projects so someone can 
capture my experience and use it better. Hopefully it will be benificial to you. :-)
</p>
<ul>
			<li>3D reconstruction of a Tree</li>
			<p>This is project is under the guidance of Prof. Michael Gennert of WPI. We are exploring a Visual SLAM based algorithm for the generation of 3D image of
			   tree. This project was inititaed to provide a 3D image of a tree to US department of Argiculture, to aid them in the detection of Asian Long Horn Beetles
                        which pose a serious threat to the trees in the New England region.
			</p>
			<li>6D SLAM </li>
			<p>Initated as a part of SOCIS 2011. I am currenty implementing a component for the robocomp software for 6D SLAM using Kinnect.</p>
			<li>AD9833 at AIM Lab WPI</li>
			<p>This was a small weekend project in the AIM lab @ WPI with the aim to implement the AD 9833 for  signal generation in the <a href="http://aimlab.wpi.edu/research/projects/Modular_MRI-Compatible_Robot_Controller">MRI Robot Controller</a>. 
                         One of the primary requirements for a robot controller in MRI environment is low EM signature that does not affect the MRI working. <a href=http://www.analog.com/en/rfif-components/direct-digital-synthesis-dds/ad9833/products/product.html>AD9833</a>
                         which is a Low Power programmable waveform generator, is best suited for this application. AD 9833 has a power consumption of 12.65 mW @ 3V. I will try to
			    put up a tutorial for using AD9833 as soon as possible.
			</p>
			<li>FPGA Implementation of Neural Network Classifier aboard the satellite Flying Laptop</li>
			<p>This was joint suoervised by the Dr G Lakshminaryanan of NITT and Prof Roser and Felix of Universitat of Stuttagart. The hardware implementation 
                        and verification of the Back-propagation Neural Network for Land Classification using the FPGA of the satellite "Flying Laptop" was carried out 
                        using Handel-C. The parallel nature of ANN is exploited. An extended CORDIC algorithm was implemented for the activation function and the Handel C 
                        code was tested in Mentor Graphics DK suite. This was my final year thesis in NITT. It helped me to delve deeper into the feasibility study that i had
                        carried out in Stuttgart and prove the valididty of the implementation. It gave me an oppurtunity to explore FPGA programing. Verilog 
                        being the standard for HDL implementation in NITT programming in Handel C was a challenge and helped me learn an addition HDL programming software.
			   The succesful implentation of this project enabled me to complete my B.Tech in National Institute of Technology, Trichy.
			</p>   
			<li>Feasibility Study of Neural Network Classifier aboard the satellite Flying Laptop</li>
			<p>This project was under Prof. Dr. Hans-Peter Roser and Felix Bohringer at Institute of Space Systems, Universitat Stuttgart - Germany.
                        My study examined the possibilities of implementing an Artificial Neural Network Based Classifiers for land surface classification 
                        using the Payload FPGA-Onboard-Computing-System carrying Xilinx Vertex-II Pro of "Flying Laptop", an experimental micro-satellite 
                        with Multispectral camera to be launched in 2013. Back propagation Feed Forward Neural Network and Radial Basis Function Neural network 
                        were evaluated by computer simulation for land classification. This gave me an oppurtunity to travel to Germany and enjoy he research culture
                        there. My work can be segmented into three functional parts where in the first stage I explored the other satellites onboard image processing
                        capabilities. Soon I was able to conclude that Flying laptop will be the first satellite to do onboard image processing for land classification
                        using FPGA. The second part of my work was to examine feasible neural network approaches, we examined the RDF based neural network and Back propogation 
                        based neural network. BKPG had less complexity in implementation but also lacked performance. RDF had better perfomance and accuracy but was computationally
			   expensive. I wrote the C++ code to test both the ANN for classification and to simulate their perfomance on a workstation. The third part of my work
			   was to discuss considerations and architectures that can be used the FPGA implementation of ANN. I had to think of solutions that avoid floating point
			   on the FPGA and exploit the parallel nature of the FPGA.
			</p>
			<li>Lego Minstrorms face detection and Tracking robot</li>
			<p>This project was under Dr Marcelo H. ANG Jr and Dr Niak Wu, Koh at the Centre for Intelligent Products and Manufacturing Systems (CIPMAS), 
                       National University of Singapore. I designed and built a Face detection and Tracking mobile robot using Lego NXT Mindstorm Kit and a mounted 
                       webcam. The pan and tilt mechanism for the webcam was also designed. Voila & Jones face detection algorithm was implemented using OpenCV to 
                       sense face and a Particle Filter algorithm was implemented to track the face smoothly. This project resulted in a real time face tracking 
                        robot connected to a Workstation Computer which acted as a co-processor and compensated the limitations of the Lego NXT intelligent Brick.
                        We used bluetooth for communication between the nxt intelligent block and the computer. I wrote the C++ stack implementing the NXT bluetooth
                        protocol over. The robot was designed to throw a ball at the face of the person once detected. I made some good friends and enjoyed my singapore trip
			   thoroughly. It helped me appricieate the research in robotics as this was my first venture outside india in my quest for research.
                     </p>
			<li>6x6x4 LED cube</li>
			<p>This was a simple hobby project using AVR Atmega16 microcontroller and a bunch of blue LEDs. The idea was to develop a 3D display frame for my personal use.</p>
			<iframe width="420" height="315" src="http://www.youtube.com/embed/JEoPKPmlTJg" frameborder="0" allowfullscreen></iframe>
			<li>RMI shaastra IP competion 2011</li>
			<p>This was for Takeshi's castle maze solving competition Shaastra, the techfest of Indian Institute of Technology, Madras. We performed number detection and
                     path planning using images</p> 
			<iframe width="420" height="315" src="http://www.youtube.com/embed/lAW6OOze1Ck" frameborder="0" allowfullscreen></iframe>
			<li>AVR Atmega USART communication</li>
			<p>This was my first project in Robotics and Machine Intelligence, the official robotics club of NITT. I worked on the UART implementation in AVR and interfaced 
                        it with computer for serial communication. I also wrote a nice tutorial for it.
			</p>
</ul>