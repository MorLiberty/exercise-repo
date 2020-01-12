node {
    stage("checkout"){
        git "https://github.com/MorLiberty/exercise-repo.git"
    }
    stage("test"){
        bat label: '', script: 'python exercise.py'
    }
}