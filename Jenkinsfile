node(){
    
        stage("builds"){
         echo "naa"
         }
         stage("test"){
          catchError(buildResult: 'FAILURE', stageResult: 'FAILURE')
             {
          if (false)
             {echo "mhhhhmmaa"
             }
          else
          {Utils.markStageSkippedForConditional('test')
          }
             }
         }

        stage("ssddd"){
         echo "naa"
         }
}
