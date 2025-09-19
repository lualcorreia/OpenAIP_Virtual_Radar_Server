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

## 📌 Changelog

### V1.0 – Initial Release
- Basic integration of **OpenAIP tiles** into Virtual Radar Server (VRS).  
- Added fallback to **OpenStreetMap** if OpenAIP service was unavailable.  
- Included attribution, max zoom, and default opacity settings.  

### V1.1 – Service Check & Error Handling
- Implemented **service availability check** before loading OpenAIP tiles.  
- Added **error handling for failed tiles**, with automatic opacity reduction.  
- Improved **zoom-based opacity control**, reducing opacity at high zoom levels for clarity.  

### V1.2 – Contrast Control & UI Improvements
- Added **darkening and contrast adjustment** to the OpenAIP layer, making it easier to visualize over OpenStreetMap.  
- Implemented a **Leaflet control slider** to dynamically adjust brightness/contrast in real time.  
- Enhanced error handling to avoid blank tiles.  
- Minor refinements in zoom/opacity balance for better readability.  

---

73 de **PP2LA**
