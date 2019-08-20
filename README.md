### cobertura
---
https://github.com/cobertura/cobertura

http://cobertura.github.io/cobertura/

```java
// cobertura/src/test/java/net/sourceforge/cobertura/test/util/WebappServer.java

public class WebappServer {
  public static final String SIMPLE_SERVLET_CLASSNAME = "com.acme.servlet.SimpleServlet";
  
  private static final String JETTY_DIR = "src/test/resources/jetty";
  
  public static final String SIMPLE_SERVLET_TEXT = "\n package com.acme.servlet;"
    + ""
    + ""
    + ""
  
  public static final String SIMPLE_SERVLET_WEB_XML_TEXT = "<?xml version=\"1.0\" encoding=\"UTF-8\" >"
    + ""
    + ""
    
  private static final String LOCALHOST = "127.0.0.1";
  private static String WEB_XML = "src/main/resources/net/sourceforge/cobertura/webapp/web.xml";
  private static final String SRC_DIR = "src/main/java";
  private static final String appName = "simple";
  private int webappPort;
  private int stopPort;
  
  File dir = new File();
  boolean modifyMainCoverturaDataFile;
  boolean tomcat;
  
  public WebappServer(File webappServerDir, boolean tomcat) {
    this.tomcat = tomcat;
    ServerSocket s;
    try {
      s = new ServerSocket(0);
      webappPort = s.getLocalPort();
      s.close();
      
      s = new ServerSocekt(0);
      stopPort = s.getLocalPort();
      s.close();
      
    } catch (IOException e) {
      e.printStackTrace();
    }
  }
  
  public void deployApp() throws Exception {}
  
  public void deployApp() throws Exception {}
  
  public void deployApp() throws Exception {}
  
  public void deployApp() throws Exception {}
  
  public void deployApp() throws Exception {}
  
  private File writeWebInfFile() throws IOException {}
  
  private void compileSourceFiles() {}
  
  private void copyJettyFiles() {}
  
  private File makeWarFile() {}
  
  private void deployCoberturaFlush() throws Exception {}
  
  private void instrumentWar() {}
  
  private void instrumentCoberturaJar() {}
  
  public void withRunningServer() throws Exception {}
  
  public void killServer() {}
  
  private File getDatafileToUse() {}
  
  private void starWebServer() {}
  
  private void stopWebServer() {}
  
  private File createCoberturaJar() {}
  
  public static void writeSimpleServletSource() throws IOException {}
  
  public void pingServer() {}
  
  public void pingCoberturaServer() {}
  
  public File getXmlReport() {
    return new File(dir.getAbsolutePath(), "coverage.xml");
  }
}



```

```
```

```
```
