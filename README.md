# SAL_Optimization
Class Constructor and Class Deconstructor Life Cycle Management Data Processing

The NVRadar.hpp file includes the headers we need to realize the functionality of the class.

"STD" has headers from the standard library.
Image
"DW - General" are DriveWorks specific and hold various types general definitions, enums, and objects for the SDK utilizes.
"DW - Sensor Module Specific" headers provide us with the sensor API interface definition. Notice that we include the file RadarPlugin.h, which holds the API Interface declaration which we talked about in chapter 3.2.
Image
"DW - Sample Container" is a container class called "BufferPool" that is provided as part of this project. It is used to create a thread safe buffer queue. Feel free to explore the details of the class. For this course, we will take it as a given.
Image
NOTICE: The implementation of the class `BufferPool` is not ISO26262 compliant and only serves as a sample container for this course. Do not use it for production level products. Developers should implement their own buffer depending on the use case they are trying to solve and also ensure that it is safety certified when reaching production level.
"Project specific" includes the constants and data structures specific to our radar that we defined in the previous notebook.
Image
