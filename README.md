*Important:

-> All files for template are in folder [Solution Files]

-> When starting a new project from template, it is recomended to have Place Solution and Project in same directory selected

0 -

Add template to user templates folder (copy zip file [KRFTemplateApi_[version].zip] to location bellow)

C:\Users\[your_username]\Documents\Visual Studio 2019\Templates\ProjectTemplates\

Copy item templates KRF_[item]_[Version].zip
C:\Users\[your_username]\Documents\Visual Studio 2019\Templates\ItemTemplates\KRF\

----- > or install vsix from file [KRF_Template_Installer_Version.zip]

Import editor settings if you desire to use my codeStyle (VS2019_CSharpEditorSettings.editorconfig) 


1 -

Add KRFCommon nuget repository

*you can add nuget.config file to solution root or add to your user for use in all projects on file bellow

C:\Users\[your_username]\AppData\Roaming\NuGet\NuGet.Config

check file nuget.config

2 -

Select default start project to be WebApi, use Kestrel profile
Create database, select Infrastructure project on package manager console and run 
add-migration "migration_name"

3 -

Add .gitignore to project repository

-> Vsix project for template is on [TemplateInstaller] folder

