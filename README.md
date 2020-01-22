# ML_FraudDetections
Used for the TTB efforts to detect fraudulent labels and formulas

# Instructions to configure LabelValidation.ipynb locally
- When in a local laptop/desktop, just perform `pip3 install -r requirements.txt`

# Configure to run in Sagemaker
- From the SageMaker Homepage select "Open Jupyter"
- Inside the Jupyter Notebook "Upload" LabelValidation.ipynb, LabelValidationFunc.py, FraudLabelConfig.json, and create labelImages.tar from TestData directory
- Select Upload twice to upload properly

<img style="float: left;" src="TTB/images/SageMaker_Homepage.png"/>
<br/><br/>
<img style="float: left;" src="TTB/images/Upload_Image.png"/>
<br/><br/>
<img style="float: left;" src="TTB/images/Push_Load_Button_Twice.png"/>
<br/><br/>

# Untar labelImages.tar in a terminal
- Open a terminal
- Go to the terminal, cd to SageMaker, `mkdir TestData`, and in TestData `tar xvf labelImages.tar`
- Click to open LabelValidation.ipynb

<img style="float: left;" src="TTB/images/Get_To_Terminal.png"/>
<br/><br/>
<img style="float: left;" src="TTB/images/Terminal_SageMaker.png"/>
<br/><br/>

# When in  Jupyter Notebook, use the "conda_tensorflow_p36" kernel
- If UI asks to select Kernel upon opening notebook, enter X, and cancel
- Make certain that you are using the correct kernel "conda_tensorflow_p36" kernel

<img style="float: left;" src="TTB/images/Change_Kernel.png"/>
<br/><br/>
<img style="float: left;" src="TTB/images/Tensorflow_Kernel_Version.png"/>
<br/><br/>

# Instructions to configure FormulaFraudDetection.ipynb
- When in a local laptop/desktop, just need to `pip3 install -r requirements.txt`

# From the SageMaker Homepage select "Open Jupyter"
- From the Jupyter Notebook "Upload" FormulaFraudDetection.ipynb, and create formula_fraud.tar from TestData directory
- Select Upload twice to upload properly

<img style="float: left;" src="TTB/images/SageMaker_Homepage.png"/>
<br/><br/>
<img style="float: left;" src="TTB/images/Upload_Image.png"/>
<br/><br/>
<img style="float: left;" src="TTB/images/Push_Load_Button_Twice.png"/>
<br/><br/>

# Untar formula_fraud.tar in a terminal
- Open a terminal
- Go to the terminal, cd to SageMaker, mkdir TestData, and in TestData tar xvf formula_fraud.tar
- Click to open FormulaFraudDetection.ipynb

<img style="float: left;" src="TTB/images/Get_To_Terminal.png"/>
<br/><br/>
<img style="float: left;" src="TTB/images/Terminal_SageMaker.png"/>
<br/><br/>

# When in  Jupyter Notebook, need to use the conda_python3 kernel
- If UI asks to select Kernel upon opening notebook, enter X, and cancel
- Make certain that you are using the correct kernel "conda_tensorflow_p36" kernel

<img style="float: left;" src="TTB/images/Change_Kernel.png"/>
<br/><br/>