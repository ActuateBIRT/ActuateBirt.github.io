-----------------------------------------------------------------------
Installing R support for OpenText Magellan BI & Reporting
-----------------------------------------------------------------------
You must install the Rserve plug-in to enable R integration in Analytics Designer and BI & Reporting. 
Analytics Designer and BI & Reporting use a dedicated plug-in to connect to and query Rserve. 
The plug-in contains third-party libraries licensed under LGPL 2.1.

How to install the Rserve plug-in for Analytics Designer:

1. Open Analytics Designer. 

2. Choose Help > Install New Software from the main menu.

3. In Work with, enter the following URL:
https://actuatebirt.github.io/rsupport/16.x.0

4. Click Add. In Name, enter Rserve plug-in, and choose Add to save this location.

5. Select R Support for BIRT. Choose Next.

6. Review the items to be installed, and choose Next.

7. Choose I accept the terms of the license agreement. Choose Finish.

8. Choose Install anyway to accept the unsigned content.

9. When the installation completes, choose Restart Now to restart Analytics Designer.

How to install the Rserve plug-in for BI & Reporting:

1. Download com.actuate.birt.script.ext.rserve_24.2.0.<time stamp>.jar from the following GitHub location:
https://actuatebirt.github.io/rsupport/16.x.0

2. Copy the file to:
<AC_SERVER_HOME>\web\birtservice\WEB-INF\platform\plugins

3. Restart BI & Reporting.

------------------------------------------------------------------------