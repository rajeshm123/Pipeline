node {
   
   	stage 'Stage 1'
   		echo 'Hello there, shell scripts'
   	stage 'Checkout'
   		git url: 'https://rajeshm123:rajesh06@github.com/rajeshm123/Pipeline.git'
   	stage 'Build'
   		sh './myBuild.sh'
   	stage 'Deploy'
   		sh './myDeployment.sh'
  
}
