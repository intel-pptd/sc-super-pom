# MuleSoft Dependencies BOM

This Bill of Materials (BOM) provides centralized version management for MuleSoft runtime and connector dependencies.

## Purpose

- Centralized version control for all MuleSoft dependencies
- Simplified runtime upgrades across multiple applications
- Consistent dependency versions across your organization

## Usage

Import this BOM in your Mule application's pom.xml:

```xml
<dependencyManagement>
    <dependencies>
        <dependency>
            <groupId>com.mycompany</groupId>
            <artifactId>mule-super-pom</artifactId>
            <version>1.0.0</version>
            <type>pom</type>
            <scope>import</scope>
        </dependency>
    </dependencies>
</dependencyManagement>