//////// READING #1 /////////
---------------------------------------------------------------------------------
A tool definition is made up of four pieces: the name, the description, the input schema, and the function itself. The name is just the identifier the model uses when it decides to call that tool. The description explains what the tool does and when it makes sense to use it so the model understands its purpose. The input schema lays out the exact arguments the tool expects and keeps the structure consistent, making sure the inputs are valid and accepted. The function is the actual code that runs once the tool is selected. It takes the inputs and does the work and returns the result. Each part plays a different role the name labels it, the description explains it, the schema keeps the inputs in check, and the function carries out the task. 

//////// READING #2 /////////
---------------------------------------------------------------------------------

Three ways I can improve my testing suite for my text editor : 

1) Shift the focus from coverage focused to risk focused. Although we were asked to get 100 percent coverage the blog post warns that testing every single small thing can be "Time consuming and unnecessary." This can lead to testing overkill and delays in projects and releases according to the post. 

2) Adopting a formal test driven development cycle. The blog post explains this is when you write failing test before the code which can "shape test suites" to reduce technical debt. So writing tests before the project can help the project take shape before anything is actually super helpful. 

3) Integrate Automation frameworks and CI/CD frameworks. The blog mentions that manual testing can be time consuming and suggests leveraging automation frameworks like katalon, which is the page the blog is on, integrated with CI/CD pipelines. This prevents the "increased testing time and costs" mentioned in the blog by catching bugs the moment they are introduced, rather than waiting for a developer to remember to run the coverage report locally.

