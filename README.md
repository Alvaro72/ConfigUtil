# ConfigUtil
Config Utilities for Java to read properties file from classpath or url to java class fields

Example:

    @ConfigFile("proyect.properties")
    public class ProyectConfig {
        @ConfigValue("datasource")
        private String datasource;
    
        @ConfigValue("waitSeconds")
        private int waitSeconds;
    
        @ConfigValue("readonly")
        private boolean readonly;
    
    }
