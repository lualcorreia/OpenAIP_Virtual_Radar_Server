## Setup Instructions

To make it work correctly, follow the steps below:

1. **Create an account on OpenAIP**  
   Go to [https://www.openaip.net/](https://www.openaip.net/) and create your free account.

2. **Generate your API Key**  
   On the website, navigate to **"API Clients"** and create a new API.  
   Copy the generated code — it will be added to the script in the sections labeled `"Your API"`.

3. **Check the plugin installation in VRS**  
   In **Virtual Radar Server**, make sure the **"Custom Content Plugin"** is already installed.  
   If not, you can download it for free here:  
   [https://www.virtualradarserver.co.uk/Download.aspx](https://www.virtualradarserver.co.uk/Download.aspx)

4. **Configure the script in VRS**  
   - Insert your **API Key** into the script.  
   - Place the `vrs_openaip_layers` folder in a directory of your choice.  
   - Configure it in the plugin options as shown in the image.

---

## V1.2 – Changes & Improvements

- Added **darkening and contrast adjustment** to the OpenAIP layer, making it easier to read over the OpenStreetMap background.  
- Implemented a **custom Leaflet control** with a **slider** that allows you to dynamically adjust brightness and contrast of the OpenAIP layer while the map is running.  
- Improved error handling: if OpenAIP tiles fail, the opacity is reduced to signal issues instead of leaving the map blank.  
- Minor refinements in zoom-based opacity control (better visual balance when zooming in beyond level 14).  

---

73 de **PP2LA**
