// Step 1: Pack
$ dotnet pack --configuration Release

// Step 2: Publish
dotnet nuget push "bin/Release/repository-name.1.0.0.nupkg" --source "github"
