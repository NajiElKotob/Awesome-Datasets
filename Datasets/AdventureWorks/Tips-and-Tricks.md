## Connect to Power BI Desktop Model
### Option 1
* TASKLIST /FI "imagename eq msmdsrv.exe” /FI “sessionname eq console"
* netstat /ano | findstr "{PID}"
* TCP    127.0.0.1:{Port}
### Option 2
* %UserProfile%\Microsoft\Power BI Desktop Store App\AnalysisServicesWorkspaces > AnalysisServicesWorkspace_XXXXX > Data > msmdsrv.port.txt
* %LocalAppData%\Microsoft\Power BI Desktop\AnalysisServicesWorkspaces > AnalysisServicesWorkspace_XXXXX > Data > msmdsrv.port.txt
* %LocalAppData%\Microsoft\Power BI Desktop SSRS\AnalysisServicesWorkspaces > AnalysisServicesWorkspace_XXXXX > Data > msmdsrv.port.txt
