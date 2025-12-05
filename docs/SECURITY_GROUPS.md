# Security Group Configuration

## Goal
Configure security groups to allow EC2 web server to communicate with RDS database.

## Steps Taken

### Step 1: Go into EC2 Console
![Step 1](../images/SecurityGroupScreenshot_1.png)

### Step 2: Locate Security Group
![Step 2](../images/SecurityGroupScreenshot_2.png)

### Step 3: Edit Inbound Rules
![Step 3](../images/SecurityGroupScreenshot_3.png)

### Step 4: Add New Rule
![Step 4](../images/SecurityGroupScreenshot_4.png)

### Step 5: Allow EC2 Conncetion
![Step 5](../images/SecurityGroupScreenshot_5.png)

### Step 6: Rule Successfully Created
![Step 6](../images/SecurityGroupScreenshot_6.png)

## Result
EC2 instance can now connect to RDS database on port 3306.
