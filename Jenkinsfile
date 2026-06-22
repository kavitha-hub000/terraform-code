pipeline{
  agent any

  stages{
    stage('Terraform init'){{
      steps{
         bat'"C:\\terraform.exe"init'
      }
    }
    stage('Terraform Validate'){
      steps{
         bat'"C:\\terraform.exe"validate'
      }
    }
    stage('Terraform Plan'){
      steps{
         bat'"C:\\terraform.exe"plan'
      }
    }
    stage('Terraform Apply'){
      steps{
         bat'"C:\\terraform.exe"apply-auto-approve'
      }
    }
  }
}
