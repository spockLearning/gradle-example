# gradle-example
basic example of a gradle project for spock tests

build.gradle must include the following dependencies for spock tests

dependencies {
    compile 'org.codehaus.groovy:groovy-all:2.3.11'
    compile 'org.spockframework:spock-core:1.0-groovy-2.4'
    testCompile group: 'junit', name: 'junit', version: '4.12'
}
