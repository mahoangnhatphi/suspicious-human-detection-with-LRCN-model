# International Conference on Intelligent Information Technology
## Reference data for International Conference on Intelligent Information Technology (ICIIT 2025),
## "ENHANCED REAL-TIME SURVEILLANCE WITH LRCN: AUTOMATING SUSPICIOUS ACTIVITY DETECTION FOR SCALABLE SECURITY SOLUTIONS IN VIETNAM"

Fig. 4 illustrates the overall structure of the system, from video input to classification output.

![image](https://github.com/mahoangnhatphi/suspicious-human-detection-with-LRCN-model/blob/main/Figure/Figure04.jpg?raw=true)

The system architecture follows a standard flow:
- Video Processing: The CCTV footage is broken down into individual frames. These frames are resized and normalized to provide consistent input to the model.
- LRCN Model Processing: The spatial features of the video frames are extracted through Convolutional Neural Networks (CNN), while the temporal sequence of frames is handled by the Long Short-Term Memory (LSTM) layers. This allows the system to identify suspicious behaviors, such as theft and unauthorized access, across time.
- Action Classification: The model outputs classifications of the observed actions into predefined categories such as stealing, lifting, jogging, or handclapping. This enables real-time detection and alerts for suspicious behaviors.

The data used in this paper includes the following files:

- **Dataset:** This contains the KTH and UCF-Crime datasets for detecting suspicious actions, like theft, in public spaces, and includes real-world surveillance footage of various types of criminal activities as well as normal actions..