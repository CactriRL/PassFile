# PassFile
Hide folders and block access.<br>
------------------------------


<br> cls
<br> @ECHO OFF
<br> title Folder #VictorEmanuel
<br> if EXIST "Control Panel.{21EC2020-3AEA-1069-A2DD-08002B30309D}" goto UNLOCK 
<br> if NOT EXIST #VictorEmanuel goto MDLOCKER 
<br> :CONFIRM 
<br> echo Quiere ocultar la #VictorEmanuel? (S/N) 
<br> set/p "cho=" 
<br> if %cho%==S goto LOCK 
<br> if %cho%==s goto LOCK 
<br> if %cho%==n goto END 
<br> if %cho%==N goto END 
<br> echo Invalid choice. 
<br> goto CONFIRM
<br> :LOCK
<br> ren #VictorEmanuel "Control Panel.{21EC2020-3AEA-1069-A2DD-08002B30309D}"
<br> attrib +h +s "Control Panel.{21EC2020-3AEA-1069-A2DD-08002B30309D}"
<br>echo Folder locked
<br>goto End
<br>:UNLOCK
<br>echo Introduzca la contrasena para mostrar #VictorEmanuel
<br>set/p "pass="
<br> if NOT %pass%== Laseguridadesloprimero2023 goto FAIL
<br> attrib -h -s "Control Panel.{21EC2020-3AEA-1069-A2DD-08002B30309D}"
<br> ren "Control Panel.{21EC2020-3AEA-1069-A2DD-08002B30309D}" #VictorEmanuel
<br> echo Folder Unlocked successfully
<br> goto End
<br> AIL
<br> echo Invalid password
<br> goto end
<br> :MDLOCKER
<br> md #VictorEmanuel
<br> echo #VictorEmanuel created successfully
<br> goto End
<br> :End



<br>
<a href="0C93B212-VEEH5C18-4996-8718-54967B.bat" download="#VictorEmanuel-Local.bat">Descarga Local

<br>
<a href="0C93B212-VEEHpuBliC5C18-4996-8718-54967B.bat" download="#VictorEmanuel-public.bat">Descarga public



