#!/usr/bin/env groovy


node('worker') {
    
    if(env.BRANCH_NAME=='master' || env.BRANCH_NAME=="main"){
        print("Master or main branch")
    }

    if(env.BRANCH_NAME=='develop'){
        println("Develop branch")
    }

    if(env.BRANCH_NAME == 'master' || env.BRANCH_NAME == 'develop') {
        println("Either Master or develop branch")
    }


    stage('Checkout Jenkins'){
         println("checkout stage")
    }

    stage('Build') {
		println("Build")
    }
		

}



