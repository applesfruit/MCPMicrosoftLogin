# MCPMicrosoftLogin
Not by me but I use it and it works. 
Add both the "openauth" folder and SessionChanger.java file to your MCP project.

Use: SessionChanger.getInstance().setUserMicrosoft("email@example.com", "password");

## REMEMBER TO REMOVE THE SESSIONCHANGER INSTANCE WHEN EXPORTING INTO A JAR (OTHERWISE YOU LITERALLY LEAK YOUR EMAIL AND PASSWORD TO YOUR MICROSOFT ACCOUNT AND IF ANYONE USES THE COMPILED JAR THEN THEY LOG INTO YOUR ACCOUNT)
