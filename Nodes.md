Created 3 instances with 40 GB volume. I was planning to do 4 instances(1 master,3 worker) but volume quota exceeded so i was able to make 3 instances(1 master,2 worker).

Use ldsa2813.pem key to login into the instance(take the key from me). Everything is already installed including spark,jupyter and pyspark. 
Enter jupyter notebook for the master node only as we need to make the code there to visualize it in the spark UI.

# Master node(group12main) 
- IPv4 - 192.168.1.71
- Floating ip- 130.238.28.213

# Worker node 
- Floating ip - 130.238.28.162(asproject12)
- Floating ip - 130.238.28.185(group12work2)

Crimes.csv is already in the master node so you can ssh into it and play with it. Think of the analysis which we can do in crimes section(check the link in project_plan.md)