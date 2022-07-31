# Determining Influential Macroeconomic Indicators for the Australian Stock Market

### Summary
<br>
Macroeconomic Indicators help in drawing insights of a nation. These macroeconomic indicators are used here to predict the performance of the Australian Stock Exchange (ASX) and National Stock Exchange (NSX). Data ranges from 2010-2018, where it has been aggregated to monthly form. Before regressing the indices, the data has been put through data reduction tests like Correlation, Bartlett test, KMO test, Principal Component Analysis (PCA) and PCA with VARIMAX. Out of seventy-nine indices, the indices which failed to load onto a factor or component in PCA with VARIMAX were dropped, and the iteration of PCA and PCA with VARIMAX continued. As per Eigen Values, K1-Kaiser test, for the data being used, there were nine components or factors, the indices which had the highest loading on to these respective components were put to ADF test to check for the stationarity of the time series data, and this final data was used in regressing. The results and flowchart are attached below for a clear understanding.
<br>
<br>

### Australian Macroeconomic Indices

<br>
<br>

<table align="center">
  <tr>
    <td> AUSBOT </td>
    <td> AUSBP </td>
    <td> AUSBR </td>
    <td> AUSCA </td>
    <td> AUSCARS </td> 
    <td> AUSCBBS </td>
  </tr>
  <tr>
    <td> AUSCCON </td>
    <td> AUSCCPI </td>
    <td> AUSCF </td> 
    <td> AUSCI </td> 
    <td> AUSCINF </td> 
    <td> AUSCNCN </td>
  </tr>
  <tr>
    <td> AUSCONPMI </td> 
    <td> AUSCOP </td> 
    <td> AUSCP </td>
    <td> AUSCPI </td>
    <td> AUSCPIC </td> 
    <td> AUSCSP </td> 
  </tr>
  <tr>
    <td> AUSCU </td> 
    <td> AUSCUR </td> 
    <td> AUSDINV </td>
    <td> AUSDPINC </td>
    <td> AUSEC </td> 
    <td> AUSEDBT </td>
  </tr>
  <tr>
    <td> AUSEMP </td>
    <td> AUSEXPX </td> 
    <td> AUSEXVOL </td>
    <td> AUSFDI </td> 
    <td> AUSFER </td> 
    <td> AUSFTEMP </td> 
  </tr>
  <tr>
    <td> AUSG </td> 
    <td> AUSGAGR </td> 
    <td> AUSGBGT </td>
    <td> AUSGBVL </td>
    <td> AUSGCP </td> 
    <td> AUSGD </td>
  </tr>
  <tr>
    <td> AUSGDG </td> 
    <td> AUSGFCF </td> 
    <td> AUSGNP </td>
    <td> AUSWAGE </td> 
    <td> AUSGOLD </td>
    <td> AUSGPC </td>
  </tr>
  <tr>
    <td> AUSGSP </td> 
    <td> AUSGYLD </td> 
    <td> AUSHOOD </td>
    <td> AUSIBOR </td> 
    <td> AUSIMPX </td> 
    <td> AUSIMVOL </td>
  </tr>
  <tr>
    <td> AUSINFEX </td> 
    <td> AUSJOBADV </td> 
    <td> AUSJVAC </td>
    <td> AUSLC </td> 
    <td> AUSLEI </td> 
    <td> AUSLFPR </td>
  </tr>
  <tr>
    <td> AUSLPS </td> 
    <td> AUSM1 </td> 
    <td> AUSM3 </td> 
    <td> AUSMANWG </td> 
    <td> AUSMKT </td>  
    <td> AUSMP </td> 
  </tr>
  <tr>
    <td> AUSMPMI </td> 
    <td> AUSNHS </td> 
    <td> AUSOIL </td> 
    <td> AUSPPI </td>
    <td> AUSPPIC </td> 
    <td> AUSPROD </td> 
  </tr>
  <tr>
    <td> AUSPSAV </td> 
    <td> AUSPTEMP </td> 
    <td> AUSRSY </td> 
    <td> AUSSPMI </td> 
    <td> AUSSSR </td> 
    <td> AUSSSRC </td> 
  </tr>
  <tr>
    <td> AUSSSRE </td> 
    <td> AUSTOT </td> 
    <td> AUSTOUR </td> 
    <td> AUSTVS </td> 
    <td> AUSUNP </td> 
    <td> AUSUNR </td> 
  </tr>
  <tr>
    <td> AUSUNRY </td>
  </tr>
</table>

<br>
<br>

### Flowchart

<br>
<br>
<p align="center">
  <img src="flowcharts/Vaishu_Stocks_methodology_detail.drawio.png">
</p>

<br>
<br>

### Results

<br>
<br>

