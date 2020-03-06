
pipeline { 
    agent any 

    stages { 
        stage('STAGE 00'){ 
            steps{
                echo "Git Clone"
                cd /Volumes/Workstation
                git clone https://github.com/Rennanxp2/casadocodigo.git
            }
        }
        stage('STAGE 01'){ 
            steps{
                echo "instalando dependencias"
                cd /Volumes/Workstation/casadocodigo
                npm install
            }
        }
        stage('STAGE 02'){ 
            steps{
                echo "iniciando projeto"
                cd /Volumes/Workstation/casadocodigo
                npm start
            }
        }
    } 
} 
