Created 3 instances with 40 GB volume. We made 1 master and 3 worker node with ldsa2813.pem key file.

Everything is already installed including spark,jupyter and pyspark. Enter jupyter notebook for the master node only as we need to make the code there to visualize it in the spark UI.

# Master node(group12main) 
- IPv4 - 192.168.1.71
- Floating ip- 130.238.28.213

# Worker node 
- Floating ip - 130.238.28.162(asproject12)
- Floating ip - 130.238.28.185(group12work2)
- Floating ip - 130.238.28.197(group12work3)

Crimes.csv is already in the master node so you can ssh into it and play with it.
