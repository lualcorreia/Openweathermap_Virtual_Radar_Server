# Weather Layer for Virtual Radar Server

This is a weather layer that can be integrated into your **Virtual Radar Server (VRS)** map, providing an even more complete experience. Installation and setup are straightforward:

## 1. Create an OpenWeatherMap Account
- Go to: [https://openweathermap.org/](https://openweathermap.org/)  
- Create your free account.  
- In the menu, navigate to **API → Maps Collection → Weather Maps 1.0 → Subscribe**.  

## 2. Get Your API Key
- After subscribing to the **Weather Maps 1.0** API, you will receive an email containing your **API Key**.  
- Copy this key and paste it into the provided script.  

## 3. Configure Virtual Radar Server
- Save the HTML file (with your API Key already added) in a folder of your choice.  
- In **VRS**, go to: **Tools → Plugins → Custom Content → Options**.  
- In **Inject file**, enter the path to your `.html` file.  
- Check the **"End of Body"** option.  
- In **Address**, delete all content and type only `"*"`.  
- Click **Enable** and restart VRS.  

## 4. Note
- To make this script work, you must have the **Custom Content** plugin installed, available for free at:  
  [https://www.virtualradarserver.co.uk/Download.aspx](https://www.virtualradarserver.co.uk/Download.aspx)  

**73 de PP2LA**
