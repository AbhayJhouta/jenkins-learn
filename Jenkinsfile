pipeline{
    agent any
    def a=False
    stages{
        stage("builds"){
        steps {
         ls
         }
         }
         stage("test"){
          if (a==False)
             {echo "naa"
             }
          else
          {Utils.markStageSkippedForConditional('mystage')
          }
         }
    }

}
