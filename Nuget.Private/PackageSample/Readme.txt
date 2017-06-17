
1.  启动运行Nuget.Private网站
2.  在PackageSample工程目录下，运行Nuget pack PackageSample.nuspec  生成PackageSample.0.0.2.nupkg包
3.  在PackageSample工程目录下，运行Nuget push PackageSample.0.0.2.nupkg Please.Change.To.Your.Nuget.Private.Key  -Source http://localhost:55545/nuget
4.  在c:\StorageForNugetPackage目录可以看到PackageSample已经上传了。也就是你可以引用自己的Nuget服务器来维护私有包了