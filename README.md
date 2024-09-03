# CVML-Shaft-Color-Detection-
CVML Object color Detection for Shaft and Wheel Manufacturing
This project addresses the challenge of manual verification of wheel and shaft pairings in friction welding by implementing an automated system using computer vision and machine learning technologies.

Camera Integration: Utilizing a strategically positioned camera to capture images of wheel and shaft assemblies before friction welding.
Image Pre-processing: Implementing software to pre-process captured images for color detection, enhancing clarity, adjusting color levels, and reducing noise to optimize images for accurate color classification and validation.
Deep Learning Model: Incorporating a pre-trained Faster R-CNN (Region-based Convolutional Neural Network) algorithm to efficiently detect and classify wheel types and shaft colours in the pre-processed images.The choice of Faster R-CNN was motivated by its robust feature extraction capabilities and proven effectiveness in spatial localization tasks, making it suitable for accurately identifying and validating complex color patterns and object configurations in industrial settings.
Raspberry Pi and PLC Integration: Connecting Raspberry Pi to a Programmable Logic Controller (PLC) to automate machine control based on detected wheel and shaft pairings. The system uses input from the Raspberry Pi to autonomously start or stop the machine, ensuring correct matches for friction welding operations.
Output Generation: Generating real-time feedback indicating the validity of the wheel and shaft pairing, ensuring correct matches for friction welding operations.
