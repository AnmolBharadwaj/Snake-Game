========================  
BUILD OUTPUT DESCRIPTION  
========================  

When building a Java application project with a main class, the IDE automatically copies all JAR files from the project's classpath to the `dist/lib` folder. Additionally, the IDE includes each JAR file in the `Class-Path` element of the application's JAR file manifest (`MANIFEST.MF`).

To run the project from the command line, navigate to the `dist` folder and execute the following command:

```
java -jar "SnakeGame.jar"
```

For distribution, compress the `dist` folder (including the `lib` folder) into a ZIP file.

**Notes:**

- If two JAR files on the project classpath share the same name, only the first JAR file will be copied to the `lib` folder.
- Only JAR files are copied to the `lib` folder. Other file types or folders on the classpath will not be included.
- If a library on the classpath has a `Class-Path` element specified in its manifest, its content must be available on the project's runtime path.
- To set the main class in a standard Java project, right-click the project node in the Projects window, select **Properties**, click **Run**, and specify the main class name. Alternatively, you can manually add the main class name to the `Main-Class` element in the manifest.
