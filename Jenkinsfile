pipeline{
    agent any
    def a=False
    stages{
        stage("builds"){
        steps {
         echo "naa"
         }
         }
         stage("test"){
          if (true)
             {echo "naa"
             }
          else
          {Utils.markStageSkippedForConditional('mystage')
          }
         }
    }

}
