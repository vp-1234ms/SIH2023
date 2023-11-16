![image](https://github.com/vp-1234ms/SIH2023/assets/102847008/ee170e57-ceb3-4572-b119-01f2ab65c8b1)<p align="center">
  <a href="" rel="noopener"></a>
</p>
<h1 align="center">Development of motion amplification video techniques for vibration analysis - Smart India Hackathon 2023</h1>

![mav1](https://github.com/vp-1234ms/SIH2023/assets/102847008/421bf306-46cb-4869-a285-32557d155ca5)

# 📝 Description <a name = "description"></a>

Motion Amplification video (MAV) is a technique for visualizing and measuring vibration of structures and machinery. This processes a video clip of an object, extracts feature that are moving from frame to frame, then amplifies and replays the motion in each frame. Defects at micro scales are rendered visible. Vibration amplitudes and mode shape can be thereafter be determined. Time waveform and FFT spectrum can also be captured. This would be extremely useful in evaluating noise, vibration and shock on various platforms. It is also useful in automobile, power plants, industry and other engineering sectors.

# 💡 Approach <a name = "approach"></a>
Input the video to desktop application that contains the object or structure with vibrations to be analyzed.
Frame-by-frame analysis and use of 2-frame-approach for motion amplification. Define necessary parameters for motion analysis, such as frame rate, resolution, and desired analysis duration.
Use Lucas-Kanade method, Optical Flow to calculate motion between consecutive frames. Set up a mask to visualize the motion vectors and adjust parameters for point selection and motion accuracy. Visualize the motion using red lines and circles. 
Using Eulerian Video Magnification, amplify motion in each frame by scaling pixel values (the scaling factor can be adjusted). Apply a color map to enhance motion visualization.
Generation of data, mode shapes, FFT(Fast Fourier Transform) spectrum results, and time waveforms for vibrational analysis. Detailed reports including above data.
Use of Temporal filters to enhance MAV video clarity and reduce noise.

# 📝 Use Cases <a name = "use"></a>
Structural Health Monitoring: Generated MAV (Motion Amplification Video) can be used to identify hidden structural defects, such as cracks or deformations, in  buildings and bridges, ensuring their safety and integrity.
Machinery Condition Assessment: It helps in detecting structural defects, imbalances or misalignments in industrial equipment, preventing costly breakdowns and optimizing maintenance.
Automotive Diagnostics: In the automotive industry, MAV is employed to diagnose and improve vehicle components performance, ensuring safety and reliability.
Automobile Industry: MAV can be utilized to analyze vibrations in automotive components, helping to identify issues with engines, suspensions, and other critical parts. This is valuable for both manufacturing quality control and vehicle maintenance.
Power Plants: Monitoring vibrations in power plant structures and equipment is essential for ensuring the reliability and safety of power generation. MAV can help identify potential faults and optimize maintenance schedules.
Aerospace Industry: In the aerospace sector, MAV can be employed to assess the structural integrity of aircraft, spacecraft, and related components. This is crucial for safety and compliance with aviation standards.

# 💡 Novelty <a name = "novelty"></a>
Use of Eulerian Video Magnification: This method has one of the best results when it comes to amplifying subtle changes in color video. Capable of generating MAV in colors instead of generating black and white output.
Use of Temporal Filters:  This filters reduces noise and generates clear motion amplification video. 
Detailed report on vibrational analysis: Report consist of FFT spectrum, time waveform and insightful statistical data collected from video frames. 
Use of Lucas-Kanade method:  Generation of optical flow helps in detecting direction of vibrations.



![mav2](https://github.com/vp-1234ms/SIH2023/assets/102847008/8685995d-a156-4e86-b75a-2ab273630e05)

## ⛏️ Built With <a name = "tech_stack"></a>
- [Data Collection,Data Integration,Data Hadelling,Data Management,Data Processing]-Data Analysis
- [NodeJS, ExpressJS, GraphQL, Flask]-Backend Service
- [Python, TensorFlow , Numpy, Pandas , Scikit_Learn,Jupyter Notebook,VsCode , Flask , Keras ,ML , DL(CNN , ANN , Neural Networking]-Machine Learning
- [Matplotlib,Seaborn,Statistics]-Data Visualization
- [ReactJS, NextJS, MaterialUI, Tauri, ElectronJS, CSS, HTML, JS, ApolloClient]-Frontend Service

![mav3](https://github.com/vp-1234ms/SIH2023/assets/102847008/52330a3e-c2cd-48db-9bca-1090c2f97cc3)

## 🎉 Built By Team Future Bits <a name = "acknowledgments"></a>
- Vaibhav Vilas Pawar
- Avishkar Kolte
- Rishita Gagrani
- Suvarsha Chennareddy
- Yashaswini Shivathaya
- Sai Shashank

![Flow](https://github.com/vp-1234ms/SIH2023/assets/102847008/c3c043d1-0e81-46dd-8d87-d54e4ffde545)

## Demonstration
https://github.com/vp-1234ms/SIH2023/assets/102847008/ae5fca94-d9d8-4003-ac83-76b313294f65
