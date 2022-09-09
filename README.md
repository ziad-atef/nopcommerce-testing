# nopcommerce-testing

## Tests results
> [Web Report](https://rawcdn.githack.com/ziad-atef/nopcommerce-testing/c2aa0cf22f4a4865bac61ab14740a51ba4e2fa54/target/cucumber-html-reports/overview-features.html)

## Prerequisites
* JDK 8+ (recommended JDK 17)
  * In case of using other versions these lines should be change in pom.xml with the new version
  ``` xml
  <properties>
    <maven.compiler.source>17</maven.compiler.source>
    <maven.compiler.target>17</maven.compiler.target>
  </properties>
  ```
* Apache Maven 3.0+
* Downloading suitable web driver and putting it in (src/main/resources)
  * Chromedriver: https://chromedriver.chromium.org/downloads (Recommended)
  * Edge: https://developer.microsoft.com/en-us/microsoft-edge/tools/webdriver/
  * you can use any other driver

## Running tests & generating report
```
mvn clean verify
```