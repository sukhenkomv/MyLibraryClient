# MyLibraryClient

В TextView на главной форме приложения печатается текст из объекта, взятого из библиотеки.

Библиотека

    implementation 'ntk.testlib:testlib-release:1.0'

берем из

    repositories {
        maven {
            url "http://m2-repo.ntk.novotelecom.ru:8081/artifactory/internal"
            allowInsecureProtocol = true
        }
    }

