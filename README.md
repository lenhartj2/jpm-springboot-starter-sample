# jpm-springboot-starter-sample
jBPM spring boot starter with multiple kjar module example

https://access.redhat.com/documentation/en-us/red_hat_process_automation_manager/7.12/html-single/integrating_red_hat_process_automation_manager_with_other_products_and_components/index


http://localhost:8090/rest/server/containers/demo-app-kjar-1_0_0/processes/demo-app-kjar.my-biz-process/instances


Notes:

Oracle jdbc

<dependency>
            <groupId>org.springframework.boot</groupId>
            <artifactId>spring-boot-starter-data-jdbc</artifactId>
        </dependency>
        <dependency>
            <groupId>com.oracle.database.jdbc</groupId>
            <artifactId>ojdbc8</artifactId>
            <version>${oracle.jdbc.version}</version>
        </dependency>
        <dependency>
            <groupId>com.oracle.database.jdbc</groupId>
            <artifactId>ucp</artifactId>
            <version>${oracle.jdbc.version}</version>
        </dependency>
