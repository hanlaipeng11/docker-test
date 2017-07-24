node {
    stage 'Checkout'
    git([url:'https://github.com/hanlaipeng11/docker-test.git'],branch:'master')
    stage 'Run'
    sh "python ./test.py"
}
