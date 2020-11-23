pipline{
    agent none
    stages{
            stage('Build '){
                steps {
                    sh 'python -m py_compile HelloPython.py'
                    stash(name: 'compiled-results', includes:'*.py*')
                    
                }
            }
        
        }
    }