# Threads or Processes? Benchmarking a Booking Handler on a Student Laptop

SCS1103-Group5-Processes and Threads 

## Group 5 Members
- Tinevimbo Muvirimi. N02657072J (Write)
- Shekinah Ndlovu. N02654189F
- Humphrey M Ndodha N02641211X
- Latoya L Judah N02646873G
- Michael V Tagarira N02642278X
- Patience E Dladla N02643454W
- Ngonidzashe Mugashu N02650155M
- Willie N Chimunya N02644203F
- Thamsanqua Chagwiza N02645531M
- Tinotenda Tauzeni N02652583X
- Pavel Musakaruka N02642379F
- Ryan Mutemeri N02640644Y
- Olgah Tore N026422278X
- Julius Marecha N02652384Y
  
## Part b)
Research Question: 
Does a thread-based booking handler process booking requests faster and with lower waiting time than a process-based booking handler on a student laptop, when both are to handle the same booking workload?

AIMS:

To compare a thread-based and a process-based booking handler on the same workload derived from the Azure Functions 2021 trace and find out which one gives faster bookings on a typical student laptop.

OBJECTIVES:

1. To build both a thread-based and a process-based booking handler in python that can handle 10,20 or more concurrent booking requests.
2. To run both handlers on three workload sizes built from the Azure Functions 2021 trace to test how each scales.
3. To evaluate and compare the perfomance of threads and processes by measuring execution time, CPU usage and memory consumption using the same workload and determine which approach performs more efficiently.
