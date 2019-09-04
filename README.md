# Dynatrace-DashboardsV2
Dynatrace Dashboards (ver 174+)

Prereqs:
  1. The upload script uses Curl and Powershell. 
  2. Add a session property for revenue if it applies for your application (Applications->[Your App]->Edit->Session and User action prop)
  3. Generate a read/write token (Settings->Integration->Dynatrace API->Generate Token)

Deployment Steps:
  1. Download zip for entire repository
  2. Unzip into any directory
  3. Open command prompt, run Upload.bat and pass in your token (i.e. Upload.bat whhehdhsb-98dd)
  4. You will be prompted for the following info:<br/>
    A. Tenant Name (i.e. SaaS: aaa54321.live.dynatrace.com Managed: xyz123.dynatrace-managed.com/e/<Env UUID>)<br/>
    B. Dashboard Owner (ID that you loginto Dynatrace with)<br/>
    C. Funnel Name (any name you want for your funnel name, spaces fine)<br/>
    D. App NAme (any name you want for your app, spaces fine)<br/>
    E. Session property for revenue (hit return if no revenue)<br/>
    F. Funnel Step 1 - 12 (Enter each funnel step and header name in the correct order. Hit return twice when you have completed the last funnel step)<br/>
