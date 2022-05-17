# Public_Dataset
Here we will store information on the public Datasets for Consumption and Production. 


Uppsala - Energiportal
---------------------------------------------------------------------------------------------------------------------------------------------------
This website has both, real time (API key necesarry?) abd historical data from public PVs in Uppsala. Information on the houses etc. are here: https://energiportalregionuppsala.se/about. In total they promote 24 PV-Panels there. Furthermore they have historical datasets publicly available: https://energiportalregionuppsala.se/open-data. 

They have either: separated information on each house / facility from 2019 - 2021, or combined information. Sadly they only provide the production side and NOT the consumption side. 

The combined dataset is divided into two CSV Files. The first one described the PV panels in detail and which ID corresponds to them:
![Uppsala_All_Production_Sides](https://user-images.githubusercontent.com/84837075/168606489-c3f770fe-5720-4a6f-967a-92f3b2ec6bff.png)

The second one is a combined view of the production in KW: 
![Uppsala_Combined_Data](https://user-images.githubusercontent.com/84837075/168606960-0163fcbd-deec-4938-99b6-18343487ec7a.png)


With this we have a total of 17 Production Sides! 


Additionally this site gives, as mentioned, singular information on for example Uppsala Tiunda School. In this case it provides the consumtion (15 Minutes interval): https://tinyurl.com/TiundaProduction and production (1 Hour Interval): https://tinyurl.com/TiundaConsumption.


---------------------------------------------------------------------------------------------------------------------------------------------------
Consumption of 69 Houses in Karlstad from Andreas T.: 
---------------------------------------------------------------------------------------------------------------------------------------------------


It only contains normal households and not facilities like schools etc.

---------------------------------------------------------------------------------------------------------------------------------------------------

Svensksolenergi
---------------------------------------------------------------------------------------------------------------------------------------------------

They provide PV Production from gigantic PV Parks (GWh), which is not applicable for our usecase: https://svensksolenergi.se/statistik/solkraft/.

---------------------------------------------------------------------------------------------------------------------------------------------------
Open Power System Data
---------------------------------------------------------------------------------------------------------------------------------------------------

OPSD provides also two kinds of data. Firstly country-wise, which is not applicable. Secondy, they also have information on 11 Households in southern Germany in an hourly resolution: https://tinyurl.com/SouthGermanOPSD. 



Name | Production | Consumption | Country | Prosumer Type | Data Type | RE Type | Battery | Time Resolution | Time Span |  Additional Information
--- | --- | --- | --- |--- |--- |--- |--- |--- |--- |---
[Glava](https://github.com/AI-4-Energy/Dataset) | :white_check_mark: | &cross;| Sweden | Industrial | CSV | Solar | &cross; | 6s | 2015 - Today | 3 PV Grids
[Uppsala Energiporal](https://energiportalregionuppsala.se/open-data) | :white_check_mark: | &cross;| Sweden | Residential + Non-Residential | JSON+CSV | Solar | &cross; | 1-5 Minutes or 1 Hour | 2019 - 2021 | 17 Prosumers
[Uppsala Tidunda](https://tinyurl.com/SchoolTiunda) | :white_check_mark: | :white_check_mark: | Sweden | Non-Residential | JSON+CSV | Solar | :white_check_mark: | 15 Minutes or 1 Hour | 2019 - 2021 | 1 PV Grid; School
[Open Power System Data](https://data.open-power-system-data.org/household_data/2020-04-15) | :white_check_mark: | :white_check_mark: | Germany | Residential | CSV+SQLite | Solar + Wind | &cross; | 1-15 Minute Resolution | 2014 - 2019 | 11 Households
[nrgyhub](https://nrgyhub.mdh.se/map) | &cross; | :white_check_mark: | Sweden | Residential + Non-Residential | 
Andreas T. | &cross; | :white_check_mark: | Sweden | Residential | TODO | TODO | TODO | Hourly | 69 Households




