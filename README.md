PowerBI ODBC connector for Greenplum supporting Direct Mode (not possible with any default connectors).  </br></br>

The connector is supporting this Greenplum ODBC driver. Install it in your PC </br><br>

https://gpdb.docs.pivotal.io/500/datadirect/datadirect_ODBC_71.html

</br>

Then configure a DNS ODBC in your windows machine

</br>

Then copy the .mez plugin file from /bin/debug/Greenplum_ODBC_DirectConnect.mez </br>
in</br>
C:\Users\Daniele\Documents\Power BI Desktop\Custom Connectors</br>

Restart PowerBI and you should see it when deciding to import the data (follow then the usual procedure to import data in direct mode putting as first step the dns configured).


</br>
You can open the project with visual studio. main file is: </br>
Greenplum_ODBC_DirectConnect.query.pq
