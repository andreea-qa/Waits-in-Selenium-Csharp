# SeleniumExplicitWaits
This is a demo project to show how to work with explicit waits in C# using LambdaTest Selenium grid.
Selenium Waits are a great way to avoid running into errors such as NoSuchElementException. 

<h2> Setting up environment variables </h2>
Before the tests are run, please set the following environment variables from the terminal to set up the LambdaTest environment variables:

For macOS:

```
export LT_USERNAME=LT_USERNAME
export LT_ACCESS_KEY=LT_ACCESS_KEY
export HYPEREXECUTE_PLATFORM='windows 10'
export HYPEREXECUTE_WORKING_DIR='<full_path_project_directory>'
```
For Linux:
```
export LT_USERNAME=LT_USERNAME
export LT_ACCESS_KEY=LT_ACCESS_KEY
export HYPEREXECUTE_PLATFORM='windows 10'
export HYPEREXECUTE_WORKING_DIR='<full_path_project_directory>'
```
For Windows:
```
set LT_USERNAME=LT_USERNAME
set LT_ACCESS_KEY=LT_ACCESS_KEY
set HYPEREXECUTE_PLATFORM='windows 10'
set HYPEREXECUTE_WORKING_DIR='<full_path_project_directory>'
```

<h2> Browser  Capabilities </h2>
You can use the <a href = "https://www.lambdatest.com/capabilities-generator/"> Automation Capabilities Generator </a> to configure the browser settings you want to use:
![Automation capabilities](https://user-images.githubusercontent.com/60468653/200382450-0ffcb37b-ce1d-41d8-8b27-046215616b90.png)

<h2> Execute the tests </h2>
Run your tests and you will be able to see the results in the Dashboard:
![Test results in LT](https://user-images.githubusercontent.com/60468653/200383046-f0cffeb8-5adc-453d-a355-ee8b61e8b2e0.png)
