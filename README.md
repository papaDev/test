# test


import com.google.gson.Gson;
import com.google.gson.JsonParser;
import com.google.gson.stream.JsonReader;
import com.oracle.javafx.jmx.json.JSONReader;
import com.sun.org.apache.xpath.internal.operations.String;
import com.sun.tools.internal.xjc.reader.internalizer.DOMForest;
import com.sun.xml.internal.dtdparser.XmlReader;
import jdk.nashorn.internal.parser.JSONParser;


import java.io.*;
import java.text.ParseException;
import java.util.logging.Filter;

public class MainClass {

    private static JsonReader Json;

    public static void main(String[] args) throws FileNotFoundException {

        FileReader fichier = new FileReader("/Users/sebastien/Documents/Dev/test.json");
        
        try(JsonReader reader = Json.createReader(new FileReader("/Users/sebastien/Documents/Dev/test.json"))) {
            JsonReader reader1 = Json.
        }
        
        System.out.println();

    }
}


<?xml version="1.0" encoding="UTF-8"?>
<project xmlns="http://maven.apache.org/POM/4.0.0"
         xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"
         xsi:schemaLocation="http://maven.apache.org/POM/4.0.0 http://maven.apache.org/xsd/maven-4.0.0.xsd">
    <modelVersion>4.0.0</modelVersion>

    <groupId>fr.test.java</groupId>
    <artifactId>Test_JSON</artifactId>
    <version>1.0-SNAPSHOT</version>

    <dependencies>
        <dependency>
            <groupId>com.google.code.gson</groupId>
            <artifactId>gson</artifactId>
            <version>2.8.5</version>
        </dependency>

    </dependencies>

</project>
