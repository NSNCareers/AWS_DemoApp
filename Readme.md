# AWS_DemoApp
Demo app

dotnet restore
dotnet build
dotnet publish -c Release -r win-x64 --output ./publishBuild
zip -r publishBuild.zip publishBuild
unzip publishBuild.zip