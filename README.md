# AR-Navigation

An Augmented Reality Navigation App using ARCore Cloud Anchors and the ARCore Geospatial API, built with SceneView.

> **Note:** This was made for a university course — it’s a tech demo, not a finished product.

---

## 🎥 Demo Video

Watch the app in action! The video covers:

- Creating a new route  
- Navigating that route  
- Searching & showing all routes in AR, then navigating one

<details>
<summary>▶️ Click to watch</summary>

<iframe 
  width="560" 
  height="315" 
  src="https://www.youtube.com/embed/LICAceF-56M" 
  title="AR-Navigation Demo" 
  frameborder="0" 
  allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" 
  allowfullscreen>
</iframe>

</details>

---

## ⚙️ Setup & Usage

- **Clone** this repo and open it in Android Studio  
- **Google Cloud Setup:**  
  - Create a Google Cloud Console account  
  - Enable **ARCore API** with OAuth 2.0 authentication  
  - Get an API key for **Maps SDK for Android**  
  - Add this key to `local.properties` as `MAPS_KEY`  
- **REST Server:**  
  - Needed to store/load routes (not included here)  
  - Repo: [ar-navigation-server](https://github.com/morhenny/ar-navigation-server)  
  - Change server IP in [Webservice.kt](https://github.com/morhenny/ar-navigation/blob/master/app/src/main/java/de/morhenn/ar_navigation/persistance/Webservice.kt)  

---

## 🔗 Core References

- [SceneView Android](https://github.com/SceneView/sceneview-android)  
- [ARCore Cloud Anchors](https://developers.google.com/ar/develop/cloud-anchors)  
- [ARCore Geospatial API](https://developers.google.com/ar/develop/geospatial)
