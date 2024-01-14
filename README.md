# UnityPackageTemplateLite

Template for organizing custom unity package.     
This is the lite version that organize sample code and package code at the same unity project.

## Usage
Just create a new repository from this public template and clone it or download this repository by zip file directly.      

Then rename `UnityPackageTemplate` folder, `UnityPackageTemplate/Assets/UnityPackageTemplate` folder and all `UnityPackageTemplate.xxx.asmdef` files to the package name you like.

Develop package code under `UnityPackageTemplate/Assets/UnityPackageTemplate` folder and sample code under `UnityPackageTemplate/Assets/Sample` folder.

Last, publish the the whole repositoy to github and then your package can be accquired by following steps,

1. Open Package Manager from Window > Package Manager.
2. Click the "+" button > Add package from git URL.
3. Enter the following URL:

```
https://github.com/YourGithubUserName/YourRepositoryName.git?path=YourPackageName/Assets/YourPackageName
```


