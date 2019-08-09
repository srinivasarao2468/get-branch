node {
    stage('checkout'){
    echo "${getGitBranchName()}"
    }
}
def getGitBranchName() {
    return scm.branches[0].name
}
