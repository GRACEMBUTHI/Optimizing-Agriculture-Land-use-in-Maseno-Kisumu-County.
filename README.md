<h1> Optimizing Agriculture Land-use for crop production in Maseno,Kisumu County. </h1>


<h2>Description</h2>
This project applies Geographic Information Systems (GIS) and remote sensing to optimize agricultural land use in Maseno, Kisumu County, Kenya. It analyzes land use/land cover changes, soil erosion risks, and crop suitability between 2016 and 2024 using tools like NDVI, NDBI, and RUSLE models. The goal is to identify high-potential zones for agriculture, assess environmental degradation, and inform sustainable land management.
<br />


<h2>Project Objectives </h2>

- <b>To map current land use patterns in the Maseno area.</b> 
- <b>To analyze the suitability of land for growing crops in Maseno using GIS.</b>
- <b>To identify areas prone to environmental degradation that is hindering sustainable agriculture land use practices.</b> 
  

<h2>Tools & Data</h2>

- <b>ArcGIS</b> 
- <b>Landsat 8 imagery</b> 
- <b>SRTM DEM</b> 
- <b>FAO & WorldClim datasets</b> 
- <b>NDVI/NDBI index calculations</b> 
- <b>RUSLE for erosion estimation</b> 
- <b>Field surveys, questionnaires, and key informant interviews</b>

  
<h2>Data analysis </h2>
The satellite imagery was used to map and classify land use patterns in Maseno area.GIS software,ArcGIS was utilized where supervised classification was the technique used.
For the suitability analysis,  weighted overlay analysis in GIS was used.This technique involved assigning weights to different factors ;soil type, rainfall, landuse landcover and slope based on their importance for crop growing. This method allowed the combination of  the different suitability layers and assign weights to each factor based on its importance.Soil Suitability (40%),Climate (Rainfall ) (25%),Slope (15%),Land Use (10%).The result was a land suitability map indicating areas optimal for various crops.

For Identifying areas showing high-risk areas for environmental degradation including soil erosion ,urbanisation and deforestation, the following analyses were conducted:

Soil Erosion Risk Analysis:This analysis utilized Use the Revised Universal Soil Loss Equation (RUSLE) models in GIS.These models help calculate potential soil erosion based on factors including;rainfall intensity, soil type, slope gradient, vegetation cover, and land use practices.The LS factor is a key component of the Revised Universal Soil Loss Equation (RUSLE) used to estimate soil erosion. It represents the combined effect of slope length (L) and slope steepness (S) on soil erosion. Ls=(("fac"*30/22.1)^0.5)*(0.065+0.045*"slopprcent"+0.0065*("slopprcent"* "slopprcent")).Fac is the  Flow accumulation and Slope in %.The outcome was a map showing areas with high, moderate, and low soil erosion risk.
Land Use Change Detection:There was use of time-series satellite imagery from year 2014 to  2024 to help detect changes in land use and land cover (LULC) over the specific period. Technique for Supervised classification  and Normalized Difference Builtup Index (NDBI) was used.NDBI=(band6 - band 5)/(band 6 + band5).The outcome was NDBI  maps  highlighting deforestation, agricultural expansion, and urbanization.

Deforestation and Vegetation Loss Analysis:The NDVI technique was used detect areas undergoing deforestation or degradation due to human activities such as logging or farming.Landsat 8 bands:Band 5 for NIR and band 4 for Red,  NDVI=(band5 -band4)/(band5 + band4).This helped in adressing the environmental challenges that is negatively affecting both agricultural productivity and long-term sustainability in Maseno Area.The output was NDVI outputs for 2016,2020 and 2024.
                 
By identifying areas that are prone to these issues, the research helped directly tackle the environmental challenges hindering agricultural productivity.Also;By identifying and mitigating environmental degradation, farmers will  optimize land use and achieve higher, more sustainable crop yields, which aligns with the  goal of enhancing productivity.Addressing soil erosion and deforestation,  addresses the sustainability aspect of this research, ensuring that the proposed solutions are not only productive but also environmentally responsible.
<br />


<h2>Project Workflow :</h2>

<p align="center">
Conceptual Framework : <br/>
<img src="https://i.imgur.com/5RMWYZb.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
 Study area: <br/>
<img src="https://i.imgur.com/6V26OHz.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Maseno Landuse landcover map 2016,2020,2024:  <br/>
<img src="https://i.imgur.com/maCPY0W.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br /> 
Maseno Landuse landcover graph 2016,2020,2024:  <br/>
<img src="https://i.imgur.com/Cy9bJd7.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
An image showing bareland in Maseno :  <br/>
<img src="https://i.imgur.com/6JTL22G.jpeg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
A map showing suitable areas to grow crops in Maseno:  <br/>
<img src="https://i.imgur.com/vR3wES6.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
A farm in Maseno showing maize and kales been grown.:  <br/>
<img src="https://i.imgur.com/0m5nd16.jpeg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br /> 
A map showing soil erosion risk in Maseno :  <br/>
<img src="https://i.imgur.com/58CxFhh.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />  
 An image showing soil erosion risk in Maseno. :  <br/>
<img src="https://i.imgur.com/C6gXcyo.jpeg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />  
 A map showing Builtup areas and non-builtup  areas in Maseno from 2016 to 2024.  :  <br/>
<img src="https://i.imgur.com/9ROZaj2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />  
 A graph showing NDBI trend in Maseno from 2016 to 2024 :  <br/>
<img src="https://i.imgur.com/yznWlX7.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />  
  An image showing Built-up areas in Maseno. :  <br/>
<img src="https://i.imgur.com/6V5yZsj.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />  
A map showing NDVI  variations from 2016 to 2024 . :  <br/>
<img src="https://i.imgur.com/yznWlX7.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />  
A graph showing NDVI ranges in Maseno from 2016 to 2024 :  <br/>
<img src="https://i.imgur.com/2BglXjp.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<h2> SUMMARY OF FINDINGS </h2>
The study successfully mapped the current land use patterns in the Maseno area, revealing significant changes between 2016 and 2024. A marked expansion in built-up areas was observed, increasing from 33.12 hectares to 132.84 hectares, indicating rapid urban development. In contrast, cropland drastically declined from 130.68 hectares to 11.07 hectares, while vegetation cover also decreased significantly. These shifts suggest a strong conversion of agricultural and vegetated lands to urban use, pointing to changing land use dynamics driven by population growth and infrastructural development.

In analyzing the suitability of land for crop production using GIS, the study found that the southern and western parts of Maseno exhibited the most favorable conditions. These areas were characterized by loamy soils, adequate rainfall, and gentle slopes, making them highly suitable for agriculture. Moderate suitability zones were identified in regions where one or two suitability factors were sub-optimal, indicating that these areas might support agriculture with appropriate interventions such as irrigation or soil amendments. Areas with steep slopes and poor drainage were categorized as unsuitable, emphasizing the need for spatially targeted agricultural planning.

Regarding areas prone to environmental degradation, the analysis revealed that the northern and eastern regions of Maseno are particularly vulnerable to soil erosion, as identified through the LS factor in the RUSLE model. Additionally, NDVI and NDBI analyses showed a strong negative correlation between urban expansion and vegetation health. Built-up areas, especially in central Maseno, exhibited increased surface imperviousness and a corresponding decline in vegetative cover. These patterns highlight significant degradation processes that hinder sustainable land use for agriculture.
<br />


<h2>CONCLUSIONS </h2>
From the mapping of land use patterns, it can be concluded that the Maseno area is experiencing rapid urban expansion at the expense of agricultural land and natural vegetation. This trend, if left unchecked, could have severe implications for food security and environmental sustainability in the region. The study underscores the urgent need for integrated land-use planning that balances development with the conservation of productive land.

The GIS-based land suitability analysis demonstrated that geospatial technologies are effective tools for optimizing agricultural land use. The identification of high and moderate suitability zones enables local authorities and farmers to make informed decisions on where to focus agricultural investments. As such, these findings support the promotion of GIS in agricultural planning to enhance crop yields and sustainability.

Lastly, the identification of environmentally degraded areas reveals that soil erosion and vegetation loss are significant obstacles to sustainable agriculture in Maseno. The degradation is largely driven by topography and intensified by anthropogenic activities such as urban development and poor land management. Therefore, it is concluded that addressing environmental degradation through targeted conservation efforts and policy interventions is critical to restoring land productivity and ensuring the long-term viability of agriculture in the region.
<br />


<h2> RECOMMENDATIONS </h2>
Based on the findings of this study, several recommendations are proposed to optimize agricultural land use in Maseno while ensuring sustainability.

Given the rapid urban expansion identified through NDBI analysis, local authorities should implement strict land use planning policies to protect agricultural land from uncontrolled development. Zoning regulations should be enforced to balance urbanization with food production, ensuring that prime agricultural zones remain dedicated to farming. Additionally, promoting vertical and peri-urban farming techniques can help maximize agricultural output in areas where land is limited due to urban expansion.

To enhance agricultural productivity, farmers should adopt soil conservation techniques, particularly in moderately suitable and high-risk erosion areas. The study identified zones with steep slopes as unsuitable for agriculture due to erosion risks. Therefore, sustainable land management practices such as terracing, agroforestry, and cover cropping should be encouraged to prevent soil degradation. The government and agricultural extension officers should provide training on these techniques to smallholder farmers, ensuring that they can implement effective soil conservation strategies.

Given the vegetation loss and environmental degradation identified through NDVI and land use change analyses, afforestation and reforestation programs should be prioritized. Communities should be encouraged to plant trees and maintain vegetation cover, especially in areas prone to deforestation. Incentives such as agroforestry programs and conservation subsidies can help farmers integrate tree planting with agricultural activities, improving both soil health and long-term sustainability.

Finally, continued use of GIS and remote sensing for monitoring land use changes and environmental degradation should be adopted by policymakers and researchers. Periodic assessment of land use patterns, soil conditions, and vegetation cover will provide critical data for informed decision-making. The integration of GIS-based early warning systems for erosion and deforestation can further aid in proactive land management. By implementing these recommendations, Maseno can achieve a balance between urban growth and sustainable agricultural practices, ensuring long-term food security and environmental conservation.
<br />



<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
