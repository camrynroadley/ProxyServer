1. Run the project in an IDE by clicking the "start" button then load an HTML page in Firefox.
   Ensure "new ProxyServer().startServer(8080); is uncommented" in the ProxyServer.java main method
   Ensure "new ProxyServer().startServer(Integer.parseInt(args[0])); is commented" in the ProxyServer.java main method

2. Run the program via the command line with the following command
   ./ProxyServer <port>
   Ensure "new ProxyServer().startServer(8080); is commented" in the ProxyServer.java main method
   Ensure "new ProxyServer().startServer(Integer.parseInt(args[0])); is uncommented" in the ProxyServer.java main method