node('cirunner') {
    stage 'Checkout'
    git([url:'https://github.com/hanlaipeng11/docker-test.git',branch:'master'])
    stage 'Run'
    sh "ls ../"
    sh "pwd"
    sh "python ./test.py"
}
