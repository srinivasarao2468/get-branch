node {
    def getGitBranchName() {
        return scm.branches[0].name
    }
    stage('checkout'){
    echo "${getGitBranchName}"
    }
}
