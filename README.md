sandbox-gradle-maven-repos-testlib
===

gitに置いたmavenリポジトリのライブラリをgradleで読み込んでみるテスト(読み込まれる側)

## build

```
gradle build
gradle publish
```

## 読み込む側
- [sandbox-gradle-git-repo-plugin](szk213/sandbox-gradle-git-repo-plugin)

## 参考
- [GitHubのPrivateリポジトリにAndroidライブラリをデプロイする](https://qiita.com/shimada_takuya/items/9e8b14ae19540f7ad0a4)
- [Gradleのmaven-publishプラグインでライブラリーを発行する方法 - 1](http://mike-neck.github.io/blog/2013/06/19/publish-maven-artifact-with-sign-files-1/)
- [36.2.2. Publishing custom artifacts](https://docs.gradle.org/current/userguide/publishing_maven.html#sec:publishing_custom_artifacts_to_maven)