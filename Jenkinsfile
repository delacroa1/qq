task myTask(type:  MyTaskType) {
    destFile = file("$buildDir/somefile.txt")
}

artifacts {
    archives(myTask.destFile) {
        name 'my-artifact'
        type 'text'
        builtBy myTask
    }
}
