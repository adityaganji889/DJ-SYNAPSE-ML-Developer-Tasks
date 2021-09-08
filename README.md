# OpenCv_Projects
OpenCV is a cross-platform library using which we can develop real-time computer vision applications. It mainly focuses on image processing, video capture and analysis including features like face detection and object detection.

Let’s start the chapter by defining the term "Computer Vision".

Computer Vision
Computer Vision can be defined as a discipline that explains how to reconstruct, interrupt, and understand a 3D scene from its 2D images, in terms of the properties of the structure present in the scene. It deals with modeling and replicating human vision using computer software and hardware.

Computer Vision overlaps significantly with the following fields −

Image Processing − It focuses on image manipulation.

Pattern Recognition − It explains various techniques to classify patterns.

Photogrammetry − It is concerned with obtaining accurate measurements from images.

Computer Vision Vs Image Processing
Image processing deals with image-to-image transformation. The input and output of image processing are both images.

Computer vision is the construction of explicit, meaningful descriptions of physical objects from their image. The output of computer vision is a description or an interpretation of structures in 3D scene.

Applications of Computer Vision
Here we have listed down some of major domains where Computer Vision is heavily used.

Robotics Application
Localization − Determine robot location automatically

Navigation

Obstacles avoidance

Assembly (peg-in-hole, welding, painting)

Manipulation (e.g. PUMA robot manipulator)

Human Robot Interaction (HRI) − Intelligent robotics to interact with and serve people

Medicine Application
Classification and detection (e.g. lesion or cells classification and tumor detection)
2D/3D segmentation
3D human organ reconstruction (MRI or ultrasound)
Vision-guided robotics surgery
Industrial Automation Application
Industrial inspection (defect detection)
Assembly
Barcode and package label reading
Object sorting
Document understanding (e.g. OCR)
Security Application
Biometrics (iris, finger print, face recognition)

Surveillance − Detecting certain suspicious activities or behaviors

Transportation Application
Autonomous vehicle
Safety, e.g., driver vigilance monitoring
Features of OpenCV Library
Using OpenCV library, you can −

Read and write images

Capture and save videos

Process images (filter, transform)

Perform feature detection

Detect specific objects such as faces, eyes, cars, in the videos or images.

Analyze the video, i.e., estimate the motion in it, subtract the background, and track objects in it.

OpenCV was originally developed in C++. In addition to it, Python and Java bindings were provided. OpenCV runs on various Operating Systems such as windows, Linux, OSx, FreeBSD, Net BSD, Open BSD, etc.

This tutorial explains the concepts of OpenCV with examples using Java bindings.

OpenCV Library Modules
Following are the main library modules of the OpenCV library.

Core Functionality
This module covers the basic data structures such as Scalar, Point, Range, etc., that are used to build OpenCV applications. In addition to these, it also includes the multidimensional array Mat, which is used to store the images. In the Java library of OpenCV, this module is included as a package with the name org.opencv.core.

Image Processing
This module covers various image processing operations such as image filtering, geometrical image transformations, color space conversion, histograms, etc. In the Java library of OpenCV, this module is included as a package with the name org.opencv.imgproc.

Video
This module covers the video analysis concepts such as motion estimation, background subtraction, and object tracking. In the Java library of OpenCV, this module is included as a package with the name org.opencv.video.

Video I/O
This module explains the video capturing and video codecs using OpenCV library. In the Java library of OpenCV, this module is included as a package with the name org.opencv.videoio.

calib3d
This module includes algorithms regarding basic multiple-view geometry algorithms, single and stereo camera calibration, object pose estimation, stereo correspondence and elements of 3D reconstruction. In the Java library of OpenCV, this module is included as a package with the name org.opencv.calib3d.

features2d
This module includes the concepts of feature detection and description. In the Java library of OpenCV, this module is included as a package with the name org.opencv.features2d.

Objdetect
This module includes the detection of objects and instances of the predefined classes such as faces, eyes, mugs, people, cars, etc. In the Java library of OpenCV, this module is included as a package with the name org.opencv.objdetect.

Highgui
This is an easy-to-use interface with simple UI capabilities. In the Java library of OpenCV, the features of this module is included in two different packages namely, org.opencv.imgcodecs and org.opencv.videoio.

A Brief History of OpenCV
OpenCV was initially an Intel research initiative to advise CPU-intensive applications. It was officially launched in 1999.

In the year 2006, its first major version, OpenCV 1.0 was released.
In October 2009, the second major version, OpenCV 2 was released.
In August 2012, OpenCV was taken by a nonprofit organization OpenCV.org.
