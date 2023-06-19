# Accelerator Log

## Options
```json
{
  "cpuLimit" : "1",
  "cpuRequest" : "500m",
  "dependsOnStateness" : "8089",
  "javaVersion" : "18",
  "memLimit" : "2Gi",
  "memRequest" : "80Mi",
  "nameSpace" : "tap-uat",
  "needPv" : true,
  "projectName" : "tanzu-java-web-app",
  "stateNess" : true,
  "testWhenBuild" : false,
  "workloadName" : "tap-test-5"
}
```
## Log
```
┏ engine (Chain)
┃  Info Running Chain(GeneratorValidationTransform, UniquePath)
┃ ┏ ┏ engine.transformations[0].validated (Combo)
┃ ┃ ┃  Info Combo running as Chain
┃ ┃ ┃ engine.transformations[0].validated.delegate (Chain)
┃ ┃ ┃  Info Running Chain(Merge, UniquePath)
┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[0] (Merge)
┃ ┃ ┃ ┃  Info Running Merge(Combo, Combo, Combo)
┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[0].sources[0] (Combo)
┃ ┃ ┃ ┃ ┃  Info Combo running as Include
┃ ┃ ┃ ┃ ┃ engine.transformations[0].validated.delegate.transformations[0].sources[0].delegate (Include)
┃ ┃ ┃ ┃ ┃  Info Will include [**]
┃ ┃ ┃ ┃ ┃ Debug .gitignore matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug .mvn/wrapper/MavenWrapperDownloader.java matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug .mvn/wrapper/maven-wrapper.jar matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug .mvn/wrapper/maven-wrapper.properties matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug .tanzuignore matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug LICENSE matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug README.md matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug Tiltfile matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug accelerator-log.md matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug catalog-info.yaml matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug config/workload.yaml matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug mvnw matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug mvnw.cmd matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug pom.xml matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/example/springboot/Application.java matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/example/springboot/HelloController.java matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/application.yml matched [**] -> included
┃ ┃ ┃ ┃ ┗ Debug src/test/java/com/example/springboot/HelloControllerTest.java matched [**] -> included
┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[0].sources[1] (Combo)
┃ ┃ ┃ ┃ ┃  Info Combo running as Chain
┃ ┃ ┃ ┃ ┃ engine.transformations[0].validated.delegate.transformations[0].sources[1].delegate (Chain)
┃ ┃ ┃ ┃ ┃  Info Running Chain(Include, Exclude)
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[0].sources[1].delegate.transformations[0] (Include)
┃ ┃ ┃ ┃ ┃ ┃  Info Will include [**]
┃ ┃ ┃ ┃ ┃ ┃ Debug .gitignore matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug .mvn/wrapper/MavenWrapperDownloader.java matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug .mvn/wrapper/maven-wrapper.jar matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug .mvn/wrapper/maven-wrapper.properties matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug .tanzuignore matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug LICENSE matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug README.md matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug Tiltfile matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug accelerator-log.md matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog-info.yaml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug config/workload.yaml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug mvnw matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug mvnw.cmd matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug pom.xml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/example/springboot/Application.java matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/example/springboot/HelloController.java matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/application.yml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┗ Debug src/test/java/com/example/springboot/HelloControllerTest.java matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[0].sources[1].delegate.transformations[1] (Exclude)
┃ ┃ ┃ ┃ ┃ ┃  Info Will exclude [pom.xml, config/**, README.md]
┃ ┃ ┃ ┃ ┃ ┃ Debug .gitignore didn't match [pom.xml, config/**, README.md] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug .mvn/wrapper/MavenWrapperDownloader.java didn't match [pom.xml, config/**, README.md] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug .mvn/wrapper/maven-wrapper.jar didn't match [pom.xml, config/**, README.md] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug .mvn/wrapper/maven-wrapper.properties didn't match [pom.xml, config/**, README.md] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug .tanzuignore didn't match [pom.xml, config/**, README.md] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug LICENSE didn't match [pom.xml, config/**, README.md] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug README.md matched [pom.xml, config/**, README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug Tiltfile didn't match [pom.xml, config/**, README.md] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug accelerator-log.md didn't match [pom.xml, config/**, README.md] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog-info.yaml didn't match [pom.xml, config/**, README.md] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug config/workload.yaml matched [pom.xml, config/**, README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug mvnw didn't match [pom.xml, config/**, README.md] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug mvnw.cmd didn't match [pom.xml, config/**, README.md] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug pom.xml matched [pom.xml, config/**, README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/example/springboot/Application.java didn't match [pom.xml, config/**, README.md] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/example/springboot/HelloController.java didn't match [pom.xml, config/**, README.md] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/application.yml didn't match [pom.xml, config/**, README.md] -> included
┃ ┃ ┃ ┃ ┗ ┗ Debug src/test/java/com/example/springboot/HelloControllerTest.java didn't match [pom.xml, config/**, README.md] -> included
┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[0].sources[2] (Combo)
┃ ┃ ┃ ┃ ┃  Info Combo running as Chain
┃ ┃ ┃ ┃ ┃ engine.transformations[0].validated.delegate.transformations[0].sources[2].delegate (Chain)
┃ ┃ ┃ ┃ ┃  Info Running Chain(Include, ReplaceText, ReplaceText, ReplaceText, ReplaceText, ReplaceText, ReplaceText, ReplaceText, ReplaceText, ReplaceText, ReplaceText, ReplaceText)
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[0].sources[2].delegate.transformations[0] (Include)
┃ ┃ ┃ ┃ ┃ ┃  Info Will include [config/workload.yaml, Tiltfile]
┃ ┃ ┃ ┃ ┃ ┃ Debug .gitignore didn't match [config/workload.yaml, Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .mvn/wrapper/MavenWrapperDownloader.java didn't match [config/workload.yaml, Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .mvn/wrapper/maven-wrapper.jar didn't match [config/workload.yaml, Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .mvn/wrapper/maven-wrapper.properties didn't match [config/workload.yaml, Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .tanzuignore didn't match [config/workload.yaml, Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug LICENSE didn't match [config/workload.yaml, Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug README.md didn't match [config/workload.yaml, Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug Tiltfile matched [config/workload.yaml, Tiltfile] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug accelerator-log.md didn't match [config/workload.yaml, Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog-info.yaml didn't match [config/workload.yaml, Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug config/workload.yaml matched [config/workload.yaml, Tiltfile] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug mvnw didn't match [config/workload.yaml, Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug mvnw.cmd didn't match [config/workload.yaml, Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug pom.xml didn't match [config/workload.yaml, Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/example/springboot/Application.java didn't match [config/workload.yaml, Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/example/springboot/HelloController.java didn't match [config/workload.yaml, Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/application.yml didn't match [config/workload.yaml, Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┗ Debug src/test/java/com/example/springboot/HelloControllerTest.java didn't match [config/workload.yaml, Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[0].sources[2].delegate.transformations[1] (ReplaceText)
┃ ┃ ┃ ┃ ┃ ┃  Info Condition (#needPv == true) evaluated to true
┃ ┃ ┃ ┃ ┃ ┃  Info Will replace [params:->params:
┃ ┃ ┃ ┃ ┃ ┗  Info   - name: vo...(truncated)]
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[0].sources[2].delegate.transformations[2] (ReplaceText)
┃ ┃ ┃ ┃ ┃ ┃  Info Condition (#stateNess == true) evaluated to true
┃ ┃ ┃ ┃ ┃ ┃  Info Will replace [params:->params:
┃ ┃ ┃ ┃ ┃ ┗  Info   - name: li...(truncated)]
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[0].sources[2].delegate.transformations[3] (ReplaceText)
┃ ┃ ┃ ┃ ┃ ┃  Info Condition (#stateNess == true) evaluated to true
┃ ┃ ┃ ┃ ┃ ┗  Info Will replace [dependsOnStateness->8089]
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[0].sources[2].delegate.transformations[4] (ReplaceText)
┃ ┃ ┃ ┃ ┃ ┗  Info Will replace [cpuLimit->1]
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[0].sources[2].delegate.transformations[5] (ReplaceText)
┃ ┃ ┃ ┃ ┃ ┗  Info Will replace [memLimit->2Gi]
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[0].sources[2].delegate.transformations[6] (ReplaceText)
┃ ┃ ┃ ┃ ┃ ┗  Info Will replace [cpuRequest->500m]
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[0].sources[2].delegate.transformations[7] (ReplaceText)
┃ ┃ ┃ ┃ ┃ ┗  Info Will replace [memRequest->80Mi]
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[0].sources[2].delegate.transformations[8] (ReplaceText)
┃ ┃ ┃ ┃ ┃ ┗  Info Condition (#testWhenBuild == true) evaluated to false
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[0].sources[2].delegate.transformations[9] (ReplaceText)
┃ ┃ ┃ ┃ ┃ ┗  Info Will replace [nameSpace->tap-uat]
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[0].sources[2].delegate.transformations[10] (ReplaceText)
┃ ┃ ┃ ┃ ┃ ┗  Info Will replace [workloadName->tap-test-5]
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[0].sources[2].delegate.transformations[11] (ReplaceText)
┃ ┃ ┃ ┗ ┗ ┗  Info Will replace [javaVersion->18]
┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[1] (UniquePath)
┃ ┃ ┃ ┃ Debug Multiple representations for path 'src/test/java/com/example/springboot/HelloControllerTest.java', will use the one appearing last 
┃ ┃ ┃ ┃ Debug Multiple representations for path 'mvnw', will use the one appearing last 
┃ ┃ ┃ ┃ Debug Multiple representations for path 'accelerator-log.md', will use the one appearing last 
┃ ┃ ┃ ┃ Debug Multiple representations for path '.gitignore', will use the one appearing last 
┃ ┃ ┃ ┃ Debug Multiple representations for path 'src/main/java/com/example/springboot/HelloController.java', will use the one appearing last 
┃ ┃ ┃ ┃ Debug Multiple representations for path 'mvnw.cmd', will use the one appearing last 
┃ ┃ ┃ ┃ Debug Multiple representations for path 'catalog-info.yaml', will use the one appearing last 
┃ ┃ ┃ ┃ Debug Multiple representations for path '.mvn/wrapper/maven-wrapper.jar', will use the one appearing last 
┃ ┃ ┃ ┃ Debug Multiple representations for path '.mvn/wrapper/maven-wrapper.properties', will use the one appearing last 
┃ ┃ ┃ ┃ Debug Multiple representations for path 'src/main/java/com/example/springboot/Application.java', will use the one appearing last 
┃ ┃ ┃ ┃ Debug Multiple representations for path 'config/workload.yaml', will use the one appearing last 
┃ ┃ ┃ ┃ Debug Multiple representations for path 'Tiltfile', will use the one appearing last 
┃ ┃ ┃ ┃ Debug Multiple representations for path '.mvn/wrapper/MavenWrapperDownloader.java', will use the one appearing last 
┃ ┃ ┃ ┃ Debug Multiple representations for path '.tanzuignore', will use the one appearing last 
┃ ┃ ┃ ┃ Debug Multiple representations for path 'LICENSE', will use the one appearing last 
┃ ┗ ┗ ┗ Debug Multiple representations for path 'src/main/resources/application.yml', will use the one appearing last 
┗ ╺ engine.transformations[1] (UniquePath)
```
