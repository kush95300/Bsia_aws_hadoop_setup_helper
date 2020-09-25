# Basic_aws_hadoop_setup_helper

This repository is created to creatre haddop over ec2 instannce easily. This is created to help those guys who want to test ghadoop over aws cloud without spending their resources. 

I will explain step by step process to use these script.

# Steps :

##Step 1 : 
  create one ec2 instance with 20 gb space. ( which is easily available with free tier)

## step 2 :
Now login in  it by puuty or any other medium and install git in it by using command  :  " yum install git"

## step 3 :
clone the repository

## step 4 :
 
 Run these two command after clonig :
 1. chmod +x hadoop_file_setup_script
 2. ./hadoop_file_setup_script          (use tab to avoid mistake)
 
## step 5 :
 now follow the instruction by these script.
 (
 in sciptin between you have to run these command also :
 1. /home/ec2-user/hadoop_file_setup_script_root
 2. source basic_hadoop_command      ( run this command every time when you login to root as it contain short hadoop command)
 )
 
 Thanks guys !!!!!
