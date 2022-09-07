pipeline { 
agent any 
stages { 
stage ('Build') {
 steps { 
sh 'echo "HELLO Angela"' 
sh ''' 
echo "Welcome to Branch 2"
uname -a
 '''
 } 
} 
stage ('Test') { 
steps { 
sh 'echo "HELLO Branch2"' 
sh ''' 
echo "Ran a uname command" 
uname -a 
'''
 }
 }
 }
 }
