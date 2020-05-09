# Using jupyter on Amazon Web Services EC2 Instance
Tutorial for using jupyter on EC2 instance


What's Here
-----------

This sample includes:

* README.md - this file
 
Getting Started
---------------

You will need to create an EC2 Instance

1. Navigate to AWS EC2

2. Click create instance
   
3. Choose Deep Learning AMI Ubuntu 18.04
   
3. Configure security settings :

What Do I Do Next?
------------------

Open a terminal and connect using ssh similar to this

          > ssh -i "yourkey.pem" -L 8000:localhost:8888 ubuntu@ec2-52-10-141-125.us-west-2.compute.amazonaws.com

Activate your environment

          $source activate tensorflow_p36
          
And run 

          $jupyter notebook --no-browser --port=8888
          
Open in your browser

          localhost:8000
          
 Type in your token
 
 
 ------------------
 Finally, experiment with interactive visualizations using jupyter notebook
