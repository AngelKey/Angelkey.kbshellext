 node ('windows-release'){
  stage 'Build'
  checkout scm
  // TODO: Environment set from a separate bat entry does not seem to work
  bat '"%ProgramFiles(x86)%\\Microsoft Visual Studio 14.0\\vc\\bin\\vcvars32.bat" && MSBuild KBShellExt.sln /p:Configuration=Release /p:Platform=x86 /t:Build' 
 }