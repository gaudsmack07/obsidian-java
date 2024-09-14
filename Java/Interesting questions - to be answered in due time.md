1. Is the JDK just the compiler + the runtime (JVM + libraries)?
		The JDK

 2. What is the entire process of building and packaging java programs - using javac and build tools like Maven? How does the compilation of trivial one or two file programs compare to the build process of massive structured projects in both cases? How do external dependencies factor into this? How does that influence dockerization? And what do terms like classpath mean in this entire picture?
 3. Why can't a top level class be private of protected? Why can they only be public or package-private?
 4. Since a project can have multiple main methods, how to configure which one to run in build tools like maven? And how does that influence dockerization? And what is a jar's manifest and how does that figure into this?