pipeline{


    agent any

    stages{


        stage("compile")
        {
            steps{
                bat "javac Test.java"
            }
        }

        stage("run")
        {
           steps{
            bat "'C:\Program Files\Java\jdk-24\bin\java.exe' '--enable-preview' '-XX:+ShowCodeDetailsInExceptionMessages' '-cp' 'C:\Users\SIDDHARTH\AppData\Roaming\Code\User\workspaceStorage\8244645699fa68e9bd3e6b650b7e531c\redhat.java\jdt_ws\pipeline-example_d691e809\bin' 'Test'"
           }
        }
    }
}