https://boilfield.github.io/cox/

+++
Created By [Atikur Rahman](https://arahmandc.github.io/ "https://arahmandc.github.io").
+++

# Instractions

  : **Have To download every implementation agencies data separately.**

| NGOF Cats1  | NGOF Cats4   | DSK     | VERC            |
|-------------|--------------|---------|-----------------|
| Ukhiya      | Ashrayan 21  | Teknaf  | Pekua, Chakaria | 



   : **Then need this  Columns for updating map from excel file.**

| Data List			     | Column Name Need		     | Find Column		| Rename Needed |
|--------------------|-------------------------|----------------|--------------- |
| Collector Name:	   | *created_by*				     | JV					    | No
| Upazila: 			     | *Upazila*				       | C					    | No
| Union:				     | *Union*	"Union"				 | D					    | No
| Ward:				       | *Ward*					         | E					    | No
| CAP ID:			       | *HH_CAP_ID*				     | GY					    | No
| HH HeadName:		   | *HC5_HHHeadName*			   | GX					    | Yes	
| Respondent:		     | *Wash_HC3_gender*		   | BA					    | Yes	
| Family Members:	   | *Wash_HC4FamilyMembers* | BE					    | No
| Creation Time:		 | *create_time*			     | J					    | No
| Geo Location:		   | *yx*						         | AZ					    | Yes
| Toilet photo:      | *Wash_HSO2Image*  		   |					      | No |


   :  **Note: Only First photo link will priorities**.

Example : http://cxb-wash.info/Upload/media/f539df99-c983-25d9-cb80-501012db9785.jpg

   : **Rename the files**

Must be Save as **NGOF Cats4** or **Ashrayan Areas**  *cats4.geojson*, **NGOF Cats1** or others *cats1.geojson*, **DSK** *dsk.geojson* and for **VERC** *verc.geojson* named.

   : **Upload File**
   
Then Upload all geojson in [**data**](https://github.com/boilfield/cox/tree/master/data "Data") folder 

