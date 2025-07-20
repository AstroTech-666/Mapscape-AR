# AR-Navigation

An Augmented Reality Navigation App using ARCore Cloud Anchors and the ARCore Geospatial API, built with SceneView.

---

## 🎥 Demo Video

Watch the app in action! The video covers:

- Creating a new route  
- Navigating that route  
- Searching & showing all routes in AR, then navigating one

<details>
  <summary>▶️ Click to watch</summary>

  [![Watch the demo](https://img.youtube.com/vi/R9s3sm3D4ZI/0.jpg)](https://youtu.be/R9s3sm3D4ZI)

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
  - Repo: [Mapscape AR](https://github.com/AstroTech-666/Mapscape-AR)  
  - Change server IP in [Webservice.kt](https://github.com/AstroTech-666/Mapscape-AR/blob/master/app/src/main/java/de/morhenn/ar_navigation/persistance/Webservice.kt)  

---

## 🔗 Core References

- [SceneView Android](https://github.com/SceneView/sceneview-android)  
- [ARCore Cloud Anchors](https://developers.google.com/ar/develop/cloud-anchors)  
- [ARCore Geospatial API](https://developers.google.com/ar/develop/geospatial)
  
