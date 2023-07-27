node{
  ('Get Code'){ 
       git credentialsId: '3bb99695-b337-4320-9273-1db911cbfb1a', url: 'https://github.com/mukunthan11/v-profile-application.git'
     }
 stage('Build package'){
        def mavenHome = tool name:"maven-3.8.8", type:"maven"
        def mavenCMD = "${mavenHome}/bin/mvn"
        sh "${mavenCMD} test"
     }
}
