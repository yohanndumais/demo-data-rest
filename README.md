# demo-data-rest
For issue submission

# test project
```
./mvnw clean install
```

# output 
```
$ ./mvnw clean install
[INFO] Scanning for projects...
[INFO]
[INFO] ---------------------< com.example:demo-data-rest >---------------------
[INFO] Building demo-data-rest 0.0.1-SNAPSHOT
[INFO] --------------------------------[ jar ]---------------------------------
[INFO]
[INFO] --- maven-clean-plugin:3.1.0:clean (default-clean) @ demo-data-rest ---
[INFO] Deleting C:\dev\git\spring-boot\demo-data-rest\target
[INFO]
[INFO] --- maven-resources-plugin:3.2.0:resources (default-resources) @ demo-data-rest ---
[INFO] Using 'UTF-8' encoding to copy filtered resources.
[INFO] Using 'UTF-8' encoding to copy filtered properties files.
[INFO] Copying 1 resource
[INFO] Copying 0 resource
[INFO] The encoding used to copy filtered properties files have not been set. This means that the same encoding will be used to copy filtered properties files as when copying other filtered resources. This might not be what you want! Run your build with --debug to see which files might be affected. Read more at https://maven.apache.org/plugins/maven-resources-plugin/examples/filtering-properties-files.html
[INFO]
[INFO] --- maven-compiler-plugin:3.8.1:compile (default-compile) @ demo-data-rest ---
[INFO] Changes detected - recompiling the module!
[INFO] Compiling 1 source file to C:\dev\git\spring-boot\demo-data-rest\target\classes
[INFO]
[INFO] --- maven-resources-plugin:3.2.0:testResources (default-testResources) @ demo-data-rest ---
[INFO] Using 'UTF-8' encoding to copy filtered resources.
[INFO] Using 'UTF-8' encoding to copy filtered properties files.
[INFO] skip non existing resourceDirectory C:\dev\git\spring-boot\demo-data-rest\src\test\resources
[INFO]
[INFO] --- maven-compiler-plugin:3.8.1:testCompile (default-testCompile) @ demo-data-rest ---
[INFO] Changes detected - recompiling the module!
[INFO] Compiling 1 source file to C:\dev\git\spring-boot\demo-data-rest\target\test-classes
[INFO]
[INFO] --- maven-surefire-plugin:2.22.2:test (default-test) @ demo-data-rest ---
[INFO]
[INFO] -------------------------------------------------------
[INFO]  T E S T S
[INFO] -------------------------------------------------------
[INFO] Running com.example.demodatarest.DemoDataRestApplicationTests
11:02:24.886 [main] DEBUG org.springframework.test.context.BootstrapUtils - Instantiating CacheAwareContextLoaderDelegate from class [org.springframework.test.context.cache.DefaultCacheAwareContextLoaderDelegate]
11:02:24.911 [main] DEBUG org.springframework.test.context.BootstrapUtils - Instantiating BootstrapContext using constructor [public org.springframework.test.context.support.DefaultBootstrapContext(java.lang.Class,org.springframework.test.context.CacheAwareContextLoaderDelegate)]
11:02:24.952 [main] DEBUG org.springframework.test.context.BootstrapUtils - Instantiating TestContextBootstrapper for test class [com.example.demodatarest.DemoDataRestApplicationTests] from class [org.springframework.boot.test.context.SpringBootTestContextBootstrapper]
11:02:24.963 [main] INFO org.springframework.boot.test.context.SpringBootTestContextBootstrapper - Neither @ContextConfiguration nor @ContextHierarchy found for test class [com.example.demodatarest.DemoDataRestApplicationTests], using SpringBootContextLoader
11:02:24.966 [main] DEBUG org.springframework.test.context.support.AbstractContextLoader - Did not detect default resource location for test class [com.example.demodatarest.DemoDataRestApplicationTests]: class path resource [com/example/demodatarest/DemoDataRestApplicationTests-context.xml] does not exist
11:02:24.967 [main] DEBUG org.springframework.test.context.support.AbstractContextLoader - Did not detect default resource location for test class [com.example.demodatarest.DemoDataRestApplicationTests]: class path resource [com/example/demodatarest/DemoDataRestApplicationTestsContext.groovy] does not exist
11:02:24.967 [main] INFO org.springframework.test.context.support.AbstractContextLoader - Could not detect default resource locations for test class [com.example.demodatarest.DemoDataRestApplicationTests]: no resource found for suffixes {-context.xml, Context.groovy}.
11:02:24.968 [main] INFO org.springframework.test.context.support.AnnotationConfigContextLoaderUtils - Could not detect default configuration classes for test class [com.example.demodatarest.DemoDataRestApplicationTests]: DemoDataRestApplicationTests does not declare any static, non-private, non-final, nested classes annotated with @Configuration.
11:02:25.018 [main] DEBUG org.springframework.test.context.support.ActiveProfilesUtils - Could not find an 'annotation declaring class' for annotation type [org.springframework.test.context.ActiveProfiles] and class [com.example.demodatarest.DemoDataRestApplicationTests]
11:02:25.074 [main] DEBUG org.springframework.context.annotation.ClassPathScanningCandidateComponentProvider - Identified candidate component class: file [C:\dev\git\spring-boot\demo-data-rest\target\classes\com\example\demodatarest\DemoDataRestApplication.class]
11:02:25.075 [main] INFO org.springframework.boot.test.context.SpringBootTestContextBootstrapper - Found @SpringBootConfiguration com.example.demodatarest.DemoDataRestApplication for test class com.example.demodatarest.DemoDataRestApplicationTests
11:02:25.182 [main] DEBUG org.springframework.boot.test.context.SpringBootTestContextBootstrapper - @TestExecutionListeners is not present for class [com.example.demodatarest.DemoDataRestApplicationTests]: using defaults.
11:02:25.184 [main] INFO org.springframework.boot.test.context.SpringBootTestContextBootstrapper - Loaded default TestExecutionListener class names from location [META-INF/spring.factories]: [org.springframework.boot.test.mock.mockito.MockitoTestExecutionListener, org.springframework.boot.test.mock.mockito.ResetMocksTestExecutionListener, org.springframework.boot.test.autoconfigure.restdocs.RestDocsTestExecutionListener, org.springframework.boot.test.autoconfigure.web.client.MockRestServiceServerResetTestExecutionListener, org.springframework.boot.test.autoconfigure.web.servlet.MockMvcPrintOnlyOnFailureTestExecutionListener, org.springframework.boot.test.autoconfigure.web.servlet.WebDriverTestExecutionListener, org.springframework.boot.test.autoconfigure.webservices.client.MockWebServiceServerTestExecutionListener, org.springframework.test.context.web.ServletTestExecutionListener, org.springframework.test.context.support.DirtiesContextBeforeModesTestExecutionListener, org.springframework.test.context.support.DependencyInjectionTestExecutionListener, org.springframework.test.context.support.DirtiesContextTestExecutionListener, org.springframework.test.context.transaction.TransactionalTestExecutionListener, org.springframework.test.context.jdbc.SqlScriptsTestExecutionListener, org.springframework.test.context.event.EventPublishingTestExecutionListener]
11:02:25.202 [main] INFO org.springframework.boot.test.context.SpringBootTestContextBootstrapper - Using TestExecutionListeners: [org.springframework.test.context.web.ServletTestExecutionListener@20f5281c, org.springframework.test.context.support.DirtiesContextBeforeModesTestExecutionListener@56c4278e, org.springframework.boot.test.mock.mockito.MockitoTestExecutionListener@301eda63, org.springframework.boot.test.autoconfigure.SpringBootDependencyInjectionTestExecutionListener@3d246ea3, org.springframework.test.context.support.DirtiesContextTestExecutionListener@341814d3, org.springframework.test.context.transaction.TransactionalTestExecutionListener@4397ad89, org.springframework.test.context.jdbc.SqlScriptsTestExecutionListener@59cba5a, org.springframework.test.context.event.EventPublishingTestExecutionListener@1bd39d3c, org.springframework.boot.test.mock.mockito.ResetMocksTestExecutionListener@6f19ac19, org.springframework.boot.test.autoconfigure.restdocs.RestDocsTestExecutionListener@119cbf96, org.springframework.boot.test.autoconfigure.web.client.MockRestServiceServerResetTestExecutionListener@71329995, org.springframework.boot.test.autoconfigure.web.servlet.MockMvcPrintOnlyOnFailureTestExecutionListener@768fc0f2, org.springframework.boot.test.autoconfigure.web.servlet.WebDriverTestExecutionListener@5454d35e, org.springframework.boot.test.autoconfigure.webservices.client.MockWebServiceServerTestExecutionListener@20c0a64d]
11:02:25.207 [main] DEBUG org.springframework.test.context.support.AbstractDirtiesContextTestExecutionListener - Before test class: context [DefaultTestContext@6c2ed0cd testClass = DemoDataRestApplicationTests, testInstance = [null], testMethod = [null], testException = [null], mergedContextConfiguration = [WebMergedContextConfiguration@7d9e8ef7 testClass = DemoDataRestApplicationTests, locations = '{}', classes = '{class com.example.demodatarest.DemoDataRestApplication}', contextInitializerClasses = '[]', activeProfiles = '{}', propertySourceLocations = '{}', propertySourceProperties = '{org.springframework.boot.test.context.SpringBootTestContextBootstrapper=true}', contextCustomizers = set[org.springframework.boot.test.context.filter.ExcludeFilterContextCustomizer@346d61be, org.springframework.boot.test.json.DuplicateJsonObjectContextCustomizerFactory$DuplicateJsonObjectContextCustomizer@3d1cfad4, org.springframework.boot.test.mock.mockito.MockitoContextCustomizer@0, org.springframework.boot.test.web.client.TestRestTemplateContextCustomizer@272ed83b, org.springframework.boot.test.web.reactive.server.WebTestClientContextCustomizer@1e6454ec, org.springframework.boot.test.autoconfigure.actuate.metrics.MetricsExportContextCustomizerFactory$DisableMetricExportContextCustomizer@4e096385, org.springframework.boot.test.autoconfigure.properties.PropertyMappingContextCustomizer@0, org.springframework.boot.test.autoconfigure.web.servlet.WebDriverContextCustomizerFactory$Customizer@793be5ca, org.springframework.boot.test.context.SpringBootTestArgs@1, org.springframework.boot.test.context.SpringBootTestWebEnvironment@e320068], resourceBasePath = 'src/main/webapp', contextLoader = 'org.springframework.boot.test.context.SpringBootContextLoader', parent = [null]], attributes = map['org.springframework.test.context.web.ServletTestExecutionListener.activateListener' -> true]], class annotated with @DirtiesContext [false] with mode [null].
11:02:25.244 [main] DEBUG org.springframework.test.context.support.TestPropertySourceUtils - Adding inlined properties to environment: {spring.jmx.enabled=false, org.springframework.boot.test.context.SpringBootTestContextBootstrapper=true}

  .   ____          _            __ _ _
 /\\ / ___'_ __ _ _(_)_ __  __ _ \ \ \ \
( ( )\___ | '_ | '_| | '_ \/ _` | \ \ \ \
 \\/  ___)| |_)| | | | | || (_| |  ) ) ) )
  '  |____| .__|_| |_|_| |_\__, | / / / /
 =========|_|==============|___/=/_/_/_/
 :: Spring Boot ::                (v2.4.0)

2020-11-30 11:02:25.504  INFO 16844 --- [           main] c.e.d.DemoDataRestApplicationTests       : Starting DemoDataRestApplicationTests using Java 15.0.1 on DESKTOP-LK52M9Q with PID 16844 (started by Yohann in C:\dev\git\spring-boot\demo-data-rest)
2020-11-30 11:02:25.508  INFO 16844 --- [           main] c.e.d.DemoDataRestApplicationTests       : No active profile set, falling back to default profiles: default
2020-11-30 11:02:26.517  INFO 16844 --- [           main] trationDelegate$BeanPostProcessorChecker : Bean 'org.springframework.hateoas.config.HateoasConfiguration' of type [org.springframework.hateoas.config.HateoasConfiguration] is not eligible for getting processed by all BeanPostProcessors (for example: not eligible for auto-proxying)
2020-11-30 11:02:26.527  INFO 16844 --- [           main] trationDelegate$BeanPostProcessorChecker : Bean 'relProviderPluginRegistry' of type [org.springframework.plugin.core.support.PluginRegistryFactoryBean] is not eligible for getting processed by all BeanPostProcessors (for example: not eligible for auto-proxying)
2020-11-30 11:02:26.537  INFO 16844 --- [           main] trationDelegate$BeanPostProcessorChecker : Bean 'relProviderPluginRegistry' of type [org.springframework.plugin.core.OrderAwarePluginRegistry] is not eligible for getting processed by all BeanPostProcessors (for example: not eligible for auto-proxying)
2020-11-30 11:02:26.542  INFO 16844 --- [           main] trationDelegate$BeanPostProcessorChecker : Bean '_relProvider' of type [org.springframework.hateoas.server.core.DelegatingLinkRelationProvider] is not eligible for getting processed by all BeanPostProcessors (for example: not eligible for auto-proxying)
2020-11-30 11:02:26.552  INFO 16844 --- [           main] trationDelegate$BeanPostProcessorChecker : Bean 'messageResolver' of type [org.springframework.hateoas.mediatype.MessageSourceResolver] is not eligible for getting processed by all BeanPostProcessors (for example: not eligible for auto-proxying)
2020-11-30 11:02:26.556  INFO 16844 --- [           main] trationDelegate$BeanPostProcessorChecker : Bean 'org.springframework.data.web.config.SpringDataJacksonConfiguration' of type [org.springframework.data.web.config.SpringDataJacksonConfiguration] is not eligible for getting processed by all BeanPostProcessors (for example: not eligible for auto-proxying)
2020-11-30 11:02:26.573  INFO 16844 --- [           main] trationDelegate$BeanPostProcessorChecker : Bean 'jacksonGeoModule' of type [org.springframework.data.geo.GeoModule] is not eligible for getting processed by all BeanPostProcessors (for example: not eligible for auto-proxying)
2020-11-30 11:02:26.605  INFO 16844 --- [           main] trationDelegate$BeanPostProcessorChecker : Bean 'org.springframework.boot.autoconfigure.data.rest.RepositoryRestMvcAutoConfiguration' of type [org.springframework.boot.autoconfigure.data.rest.RepositoryRestMvcAutoConfiguration] is not eligible for getting processed by all BeanPostProcessors (for example: not eligible for auto-proxying)
2020-11-30 11:02:26.612  INFO 16844 --- [           main] trationDelegate$BeanPostProcessorChecker : Bean 'org.springframework.boot.autoconfigure.jackson.JacksonAutoConfiguration$JacksonObjectMapperBuilderConfiguration' of type [org.springframework.boot.autoconfigure.jackson.JacksonAutoConfiguration$JacksonObjectMapperBuilderConfiguration] is not eligible for getting processed by all BeanPostProcessors (for example: not eligible for auto-proxying)
2020-11-30 11:02:26.617  INFO 16844 --- [           main] trationDelegate$BeanPostProcessorChecker : Bean 'org.springframework.boot.autoconfigure.jackson.JacksonAutoConfiguration$Jackson2ObjectMapperBuilderCustomizerConfiguration' of type [org.springframework.boot.autoconfigure.jackson.JacksonAutoConfiguration$Jackson2ObjectMapperBuilderCustomizerConfiguration] is not eligible for getting processed by all BeanPostProcessors (for example: not eligible for auto-proxying)
2020-11-30 11:02:26.637  INFO 16844 --- [           main] trationDelegate$BeanPostProcessorChecker : Bean 'spring.jackson-org.springframework.boot.autoconfigure.jackson.JacksonProperties' of type [org.springframework.boot.autoconfigure.jackson.JacksonProperties] is not eligible for getting processed by all BeanPostProcessors (for example: not eligible for auto-proxying)
2020-11-30 11:02:26.641  INFO 16844 --- [           main] trationDelegate$BeanPostProcessorChecker : Bean 'standardJacksonObjectMapperBuilderCustomizer' of type [org.springframework.boot.autoconfigure.jackson.JacksonAutoConfiguration$Jackson2ObjectMapperBuilderCustomizerConfiguration$StandardJackson2ObjectMapperBuilderCustomizer] is not eligible for getting processed by all BeanPostProcessors (for example: not eligible for auto-proxying)
2020-11-30 11:02:26.645  INFO 16844 --- [           main] trationDelegate$BeanPostProcessorChecker : Bean 'org.springframework.boot.autoconfigure.jackson.JacksonAutoConfiguration$ParameterNamesModuleConfiguration' of type [org.springframework.boot.autoconfigure.jackson.JacksonAutoConfiguration$ParameterNamesModuleConfiguration] is not eligible for getting processed by all BeanPostProcessors (for example: not eligible for auto-proxying)
2020-11-30 11:02:26.651  INFO 16844 --- [           main] trationDelegate$BeanPostProcessorChecker : Bean 'parameterNamesModule' of type [com.fasterxml.jackson.module.paramnames.ParameterNamesModule] is not eligible for getting processed by all BeanPostProcessors (for example: not eligible for auto-proxying)
2020-11-30 11:02:26.653  INFO 16844 --- [           main] trationDelegate$BeanPostProcessorChecker : Bean 'org.springframework.boot.autoconfigure.jackson.JacksonAutoConfiguration' of type [org.springframework.boot.autoconfigure.jackson.JacksonAutoConfiguration] is not eligible for getting processed by all BeanPostProcessors (for example: not eligible for auto-proxying)
2020-11-30 11:02:26.676  INFO 16844 --- [           main] trationDelegate$BeanPostProcessorChecker : Bean 'jsonComponentModule' of type [org.springframework.boot.jackson.JsonComponentModule] is not eligible for getting processed by all BeanPostProcessors (for example: not eligible for auto-proxying)
2020-11-30 11:02:26.682  INFO 16844 --- [           main] trationDelegate$BeanPostProcessorChecker : Bean 'jacksonObjectMapperBuilder' of type [org.springframework.http.converter.json.Jackson2ObjectMapperBuilder] is not eligible for getting processed by all BeanPostProcessors (for example: not eligible for auto-proxying)
2020-11-30 11:02:26.699  INFO 16844 --- [           main] trationDelegate$BeanPostProcessorChecker : Bean 'spring.data.rest-org.springframework.boot.autoconfigure.data.rest.RepositoryRestProperties' of type [org.springframework.boot.autoconfigure.data.rest.RepositoryRestProperties] is not eligible for getting processed by all BeanPostProcessors (for example: not eligible for auto-proxying)
2020-11-30 11:02:26.700  INFO 16844 --- [           main] trationDelegate$BeanPostProcessorChecker : Bean 'springBootRepositoryRestConfigurer' of type [org.springframework.boot.autoconfigure.data.rest.SpringBootRepositoryRestConfigurer] is not eligible for getting processed by all BeanPostProcessors (for example: not eligible for auto-proxying)
2020-11-30 11:02:26.703  INFO 16844 --- [           main] trationDelegate$BeanPostProcessorChecker : Bean 'configurerDelegate' of type [org.springframework.data.rest.webmvc.config.RepositoryRestConfigurerDelegate] is not eligible for getting processed by all BeanPostProcessors (for example: not eligible for auto-proxying)
2020-11-30 11:02:26.711  INFO 16844 --- [           main] trationDelegate$BeanPostProcessorChecker : Bean 'org.springframework.boot.autoconfigure.http.HttpMessageConvertersAutoConfiguration$StringHttpMessageConverterConfiguration' of type [org.springframework.boot.autoconfigure.http.HttpMessageConvertersAutoConfiguration$StringHttpMessageConverterConfiguration] is not eligible for getting processed by all BeanPostProcessors (for example: not eligible for auto-proxying)
2020-11-30 11:02:26.724  INFO 16844 --- [           main] trationDelegate$BeanPostProcessorChecker : Bean 'stringHttpMessageConverter' of type [org.springframework.http.converter.StringHttpMessageConverter] is not eligible for getting processed by all BeanPostProcessors (for example: not eligible for auto-proxying)
2020-11-30 11:02:26.727  INFO 16844 --- [           main] trationDelegate$BeanPostProcessorChecker : Bean 'org.springframework.boot.autoconfigure.http.JacksonHttpMessageConvertersConfiguration$MappingJackson2HttpMessageConverterConfiguration' of type [org.springframework.boot.autoconfigure.http.JacksonHttpMessageConvertersConfiguration$MappingJackson2HttpMessageConverterConfiguration] is not eligible for getting processed by all BeanPostProcessors (for example: not eligible for auto-proxying)
2020-11-30 11:02:26.729  INFO 16844 --- [           main] trationDelegate$BeanPostProcessorChecker : Bean 'org.springframework.boot.autoconfigure.jackson.JacksonAutoConfiguration$JacksonObjectMapperConfiguration' of type [org.springframework.boot.autoconfigure.jackson.JacksonAutoConfiguration$JacksonObjectMapperConfiguration] is not eligible for getting processed by all BeanPostProcessors (for example: not eligible for auto-proxying)
2020-11-30 11:02:26.735  INFO 16844 --- [           main] trationDelegate$BeanPostProcessorChecker : Bean 'jacksonObjectMapperBuilder' of type [org.springframework.http.converter.json.Jackson2ObjectMapperBuilder] is not eligible for getting processed by all BeanPostProcessors (for example: not eligible for auto-proxying)
2020-11-30 11:02:26.764  INFO 16844 --- [           main] trationDelegate$BeanPostProcessorChecker : Bean 'jacksonObjectMapper' of type [com.fasterxml.jackson.databind.ObjectMapper] is not eligible for getting processed by all BeanPostProcessors (for example: not eligible for auto-proxying)
2020-11-30 11:02:26.777  INFO 16844 --- [           main] trationDelegate$BeanPostProcessorChecker : Bean 'mappingJackson2HttpMessageConverter' of type [org.springframework.http.converter.json.MappingJackson2HttpMessageConverter] is not eligible for getting processed by all BeanPostProcessors (for example: not eligible for auto-proxying)
2020-11-30 11:02:26.778  INFO 16844 --- [           main] trationDelegate$BeanPostProcessorChecker : Bean 'org.springframework.data.rest.webmvc.config.RepositoryRestMvcConfiguration' of type [org.springframework.data.rest.webmvc.config.RepositoryRestMvcConfiguration] is not eligible for getting processed by all BeanPostProcessors (for example: not eligible for auto-proxying)
2020-11-30 11:02:27.453  INFO 16844 --- [           main] o.s.s.concurrent.ThreadPoolTaskExecutor  : Initializing ExecutorService 'applicationTaskExecutor'
2020-11-30 11:02:28.016  INFO 16844 --- [           main] c.e.d.DemoDataRestApplicationTests       : Started DemoDataRestApplicationTests in 2.764 seconds (JVM running for 3.75)
[INFO] Tests run: 1, Failures: 0, Errors: 0, Skipped: 0, Time elapsed: 3.742 s - in com.example.demodatarest.DemoDataRestApplicationTests
2020-11-30 11:02:28.596  INFO 16844 --- [extShutdownHook] o.s.s.concurrent.ThreadPoolTaskExecutor  : Shutting down ExecutorService 'applicationTaskExecutor'
[INFO]
[INFO] Results:
[INFO]
[INFO] Tests run: 1, Failures: 0, Errors: 0, Skipped: 0
[INFO]
[INFO]
[INFO] --- maven-jar-plugin:3.2.0:jar (default-jar) @ demo-data-rest ---
[INFO] Building jar: C:\dev\git\spring-boot\demo-data-rest\target\demo-data-rest-0.0.1-SNAPSHOT.jar
[INFO]
[INFO] --- spring-boot-maven-plugin:2.4.0:repackage (repackage) @ demo-data-rest ---
[INFO] Replacing main artifact with repackaged archive
[INFO]
[INFO] --- maven-install-plugin:2.5.2:install (default-install) @ demo-data-rest ---
[INFO] Installing C:\dev\git\spring-boot\demo-data-rest\target\demo-data-rest-0.0.1-SNAPSHOT.jar to C:\Users\Yohann\.m2\repository\com\example\demo-data-rest\0.0.1-SNAPSHOT\demo-data-rest-0.0.1-SNAPSHOT.jar
[INFO] Installing C:\dev\git\spring-boot\demo-data-rest\pom.xml to C:\Users\Yohann\.m2\repository\com\example\demo-data-rest\0.0.1-SNAPSHOT\demo-data-rest-0.0.1-SNAPSHOT.pom
[INFO] ------------------------------------------------------------------------
[INFO] BUILD SUCCESS
[INFO] ------------------------------------------------------------------------
[INFO] Total time:  8.727 s
[INFO] Finished at: 2020-11-30T11:02:29-05:00
[INFO] ------------------------------------------------------------------------

```
