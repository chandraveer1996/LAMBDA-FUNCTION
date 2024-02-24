# LAMBDA-FUNCTION

Author Lambda Function in Python

    Navigate to Lambda.

    Click Create function.

    Make sure the Author from scratch option at the top is selected, and then use the following settings:
        Function name: Type myfunction.
        Runtime: Select the latest version of Python.

    Expand Change default execution role section, and verify that Create a new role with basic Lambda permissions is selected.

    Click Create function.

    Once the function has been created, scroll down to the Code tab.

    Under Code source, select lambda_function.py.

    Replace the existing sample code with the following:

    click Deploy
    
Create a Test Event and Execute Lambda



    Select Test > Configure test event.

    For Event name, type mytest.

    In the Event JSON box, replace the sample code with the following:

    { "first_name": "Your First Name Here", "last_name": "Your Last Name Here" }

    Update the code to use your first and last name.

    Click Format JSON.

    Click Save.

    Click Test.

    Review the execution results that appear.

Verify that CloudWatch has Captured Function Logs

    Click the Monitor tab.
    Click View logs in CloudWatch.
    Under Log streams, click the most recent log stream.
    Review the log. You should see similar output as you did in the execution results.

