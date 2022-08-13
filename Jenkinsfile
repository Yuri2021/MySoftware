properties([pipelineTriggers([pollSCM('')])])
node {
    stage("clone"){
        git "https://github.com/Yuri2021/first-git-repo.git"
    }
    stage("show files"){
        sh (-ls -l)
    }
    
    
}
