# React-Native-Job-Scrapper

This is a mobile application built using React Native that helps users find job opportunities and internships that fit their needs. It uses the RapidAPI JSearch API to retrieve job data from the web.

## Getting started 

To use this application, you will need to obtain your own RapidAPI JSearch API key. Once you have your API key, add your api key in the hook/useFetch.js file here.

```javascript
  const options = {
    method: "GET",
    url: `https://jsearch.p.rapidapi.com/${endpoint}`,
    headers: {
      "X-RapidAPI-Key": "", // Add your own api key here <--
      "X-RapidAPI-Host": "jsearch.p.rapidapi.com",
    },
    params: { ...query },
  };
```

## Screenshots

<div style="display:flex; flex-direction:row; justify-content:center; gap:50px;">
  <img width="179" alt="image" src="https://user-images.githubusercontent.com/92062352/233835681-7ef90187-398d-4df5-83f6-fe6091a9f9a2.png">
  <img width="191" alt="image" src="https://user-images.githubusercontent.com/92062352/233836518-414171e0-dbcc-4ec7-9976-91c69a2f434b.png">
  <img width="180" alt="image" src="https://user-images.githubusercontent.com/92062352/233835639-cea8e4c8-7d8c-49da-8acc-bf471ba7de1e.png">
</div>

## Try it out

You can try out the application for yourself by downloading the source code and running it. 
Alternatively, you can use the Expo go app to run the application on your device without downloading the source code.

To run the application using the Expo go app, visit the following link and scan qr with Expo go app:

https://expo.dev/@expo.adi.02/jobsift?serviceType=classic&distribution=expo-go

## Contributing 

If you find any issues or have suggestions for new features, please feel free to open an issue or submit a pull request.

