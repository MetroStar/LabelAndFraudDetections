# ML_FraudDetections
Used for the TTB efforts to detect fraudulent labels and formulas

# Instructions to configure LabelValidation.ipynb
***
# When in a local laptop/desktop, need to pip3 install -r requirements.txt

# From the SageMaker HomePage
# Select "Create notebook instance"
![test info](TTB/images/Step1_CreateNotebook.png)
# After selecting Create notebook instance go to the Notebook instance settings page.
# Enter "Notebook instance name", and "Notebook instance type"
![test info](TTB/images/Step2_NameNotebook.png)
# From the Notebook instance settings page,
# Select "Enter a custom IAM role ARN"
# Enter an IAM role ARN
# Select "Enable - Give users root access to the notebook"
# Select "No Custom Encryption"
![test info](TTB/images/Step3_IAMRole.png)
# From the Notebook instance settings page,
# Select "us-east-1a"
![test info](TTB/images/Step5_SelectRegionSubnet.png)
# From the Notebook instance settings page,
# Select "sagemakerConnectionSecurityGrp"
![test info](TTB/images/Step4_VPCSelection.png)
# From the Notebook instance settings page,
# Look for the "Pending" button indicating pending creation of Notebook Instance
![test info](TTB/images/Step7_Pending.png)
# From the SageMaker Homepage select "Open Jupyter"
![test info](TTB/images/SageMaker_Homepage.png)

# From the Jupyter Notebook "Upload" LabelValidation.ipynb, FraudLabelConfig.json, and create labelImages.tar from TestData directory
![test info](TTB/images/Upload_Image.png)
# Select Upload twice to upload properly
![test info](TTB/images/Push_Load_Button_Twice.png)

# Untar labelImages.tar in a terminal
# Open a terminal
![test info](TTB/images/Get_To_Terminal.png)
# Go to the terminal, cd to SageMaker, mkdir TestData, and in TestData tar xvf labelImages.tar
![test info](TTB/images/Terminal_SageMaker.png)
# Click to open LabelValidation.ipynb
# When in  Jupyter Notebook, need to use the "conda_tensorflow_p36" kernel 
# If UI asks to select Kernel upon opening notebook, enter X, and cancel
![test info](TTB/images/Change_Kernel.png)
# Make certain that you do not select "conda_amazaonei_tensorflow_p36" kernel
![test info](TTB/images/Amazonei_Tensorflow36.png)
# Make certain that you are using the correct kernel "conda_tensorflow_p36" kernel
![test info](TTB/images/Tensorflow_Kernel_Version.png)

# Instructions to configure FormulaFraudDetection.ipynb
***
# When in a local laptop/desktop, need to pip3 install -r requirements.txt

# From the SageMaker Homepage select "Open Jupyter"
![test info](TTB/images/SageMaker_Homepage.png)

# From the Jupyter Notebook "Upload" FormulaFraudDetection.ipynb, and create formula_fraud.tar from TestData directory
![test info](TTB/images/Upload_Image.png)
# Select Upload twice to upload properly
![test info](TTB/images/Push_Load_Button_Twice.png)

# Untar formula_fraud.tar in a terminal
# Open a terminal
![test info](TTB/images/Get_To_Terminal.png)
# Go to the terminal, cd to SageMaker, mkdir TestData, and in TestData tar xvf formula_fraud.tar
![test info](TTB/images/Terminal_SageMaker.png)
# Click to open FormulaFraudDetection.ipynb
# When in  Jupyter Notebook, need to use the conda_python3 kernel 
# If UI asks to select Kernel upon opening notebook, enter X, and cancel
![test info](TTB/images/Change_Kernel.png)
# Make certain that you are using the correct kernel "conda_tensorflow_p36" kernel
![test info](TTB/images/Kernel_Version.png)
