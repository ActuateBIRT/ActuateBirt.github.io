-----------------------------------------------------------------------
Installing R support for OpenText Magellan BI & Reporting
-----------------------------------------------------------------------
You must install the Rserve plug-in to enable R integration in Analytics Designer and BI & Reporting. 
Analytics Designer and BI & Reporting use a dedicated plug-in to connect to and query Rserve. 
The plug-in contains third-party libraries licensed under LGPL 2.1.

How to install the Rserve plug-in for Analytics Designer:

1. Download the R support update zip file from here:
     https://actuatebirt.github.io/rsupport/16.x.0/download/com.actuate.birt.script.r.support.update-24.2.0.zip 

2. Open Analytics Designer. 

3. Choose Help > Install New Software.

4. In Available Software, choose Add. Then choose Archive.

5. Browse to the ZIP file that you downloaded and select it. Choose Open. Choose Add to close the dialog.

6. In Available Software, select R Support for BIRT. Choose Next.

7. Review the items to be installed, and choose Next.

8. Choose I accept the terms of the license agreement. Choose Finish.

9. Choose Install anyway to accept the unsigned content.

10. When the installation completes, choose Restart Now to restart Analytics Designer.
    For more information, see Analytics Designer User Guide, available as product help and also on http://mysupport.opentext.com.

How to install the Rserve plug-in for BI & Reporting:

1. Download the jar file from here:
     https://actuatebirt.github.io/rsupport/16.x.0/download/com.actuate.birt.script.ext.rserve_24.2.0.v201705292336.jar

2. Copy the file to:
     <AC_SERVER_HOME>\web\birtservice\WEB-INF\platform\plugins

3. Restart BI & Reporting.

4. After BI & Reporting is restarted, log on to System Console to configure R connectivity. For more information, see BI & Reporting Installation, Configuration, and Administration Guide, available as product help and also on http://mysupport.opentext.com.

-----------------------------------------------------------------------