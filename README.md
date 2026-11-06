9# Threads or Processes? Benchmarking a Booking Handler on a Student Laptop

SCS1103-Group5-Processes and Threads 

## Group 5 Members
- Tinevimbo Muvirimi. N02657072J (Write)
- Shekinah Ndlovu. N02654189F
- Humphrey M Ndodha N02641211X
- Latoya L Judah N02646873G
- Michael V Tagarira N02642278X
- Patience E Dladla N02643454W
- Willie N Chimunya N02644203F
- Thamsanqua Chagwiza. N02645531M
- Tinotenda Tauzeni N02652583X
- Pavel Musakaruka N02642379F
- Ryan Mutemeri N02640644Y
- Julius Marecha N02652384Y
- Ngonidzashe Mugashu N02650155M
- Olgah Tore N02643547D
  
## Part b)

Research Question 

Does a thread based booking handler process booking requests faster and with low waiting time than a process based booking handler on a student laptop, when both handled the same booking workload?

AIMS:

To compare a thread-based and a process-based booking handler on the same workload derived from the Azure Functions 2021 trace and find out which one gives faster bookings on a typical student laptop.

OBJECTIVES:

1. To build both a thread-based and a process-based booking in python that can handle 10,20 or more concurrent booking requests.
2. To run both handlers on three workload sizes built from the Azure Functions 2021 trace to test how each scales.
3. To evaluate and compare the perfomance of threads and processes by measuring execution time, CPU usage and memory consumption using the same workload and determine which approach performs more efficiently.

Part B
1. Research Question
2. 
Does a thread-based booking handler process booking requests faster and with lower waiting times than a process-based booking handler on a student laptop when both handle the same booking workload?
3. Aim
4. 
To compare a thread-based and a process-based booking handler using the same

 Part c)

Modern applications, including online booking systems, must handle multiple user requests efficiently and reliably. When several requests arrive simultaneously, the processing method used can affect response time, system throughput and resource consumption. These challenges are particularly important on student laptops and other low-spec computers, where CPU capacity and available memory are http://limited.Therefore, this research is important because it will establish, through practical benchmarking, whether multithreading or multiprocessing provides measurable performance improvements over sequential processing. The findings will help identify a suitable request-processing approach for applications operating on computers with limited hardware resources, while consideringworkload derived from the Azure Functions 2021 trace and determine which approach processes bookings faster on a typical student laptop.
6. Objectives
7. 
To develop both a thread-based and a process-based booking handler in Python capable of handling 10, 20, or more concurrent booking requests.
To test both booking handlers using three different workload sizes derived from the Azure Functions 2021 trace to determine how each approach scales as the number of booking requests increases.
To evaluate and compare the performance of threads and processes by measuring execution time, CPU usage, and memory consumption.
