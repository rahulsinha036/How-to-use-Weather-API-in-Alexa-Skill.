# How-to-use-Weather-API-in-Alexa-Skill.
Here you will know to create an Alexa skill using weather API in node js.
#prerequisite :
1. Alexa Developer Account -> https://developer.amazon.com/alexa/console/ask
2. Open Weather Map account -> https://openweathermap.org/
tutorial to generate API openweathermap -> https://www.youtube.com/watch?v=oN4ohLj0fkY

API URL --> http://api.openweathermap.org/data/2.5/weather?appid={Your_API_Key}&q={city_name}&units=metric
{units=metric} --> celsius and {units=imperial} --> fahrenheit

In package.json just add this -->  "axios": "^0.19.1" after aws-sdk.
Rest things are in code only with comment.
