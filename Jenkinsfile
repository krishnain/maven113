@Library("mylibrary")_
node("built-in")
{
    stage('ContDownload_Loans')
    {
        cicd.newGit("maven.git")
    }
    stage('ContBuild_Loans')
    {
        cicd.newMaven()
    }
    
}
