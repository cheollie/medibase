# MediBase

MediBase is a medication assistant allowing people who have poorer eyesight, language barriers, or are forgetful - to safely take medication.

Get important information about a drug based on its Drug Identification Number, or DIN, found on every Canadian medication. Searching by this number returns information regarding the drug instantly, and allowing it to be starred.

Summaries and information of all your starred medications can be found on the medication tab. This includes a built-in text-to-speech function that says the summary out loud.

Conforming to the topic of accessibility, MediBase contains a large range of features including a colorblind-friendly theme, text-to-speech, full-site translation, push notifications, and a simple UI to navigate through it all.

## inspiration:
Have you ever had your parents or grandparents ask you to read the prescription label for them because it is too tiny and hard to read? Have you ever had them also ask you to translate it since they might not understand English?

We have experienced this ourselves, and it made us wonder, what if other people like our parents/grandparents didn’t have someone like us to read and translate? How many people have accidentally taken an incorrect amount of their prescription medication that impacted their health?

> The mortality rate from drug overdoses tripled in the United States between 1990 and 2006. In the United States, unintentional overdose deaths among adults aged 25 to 64 years exceeded motor vehicle crash deaths and suicides as a leading cause of injury death from 2008 onward. Likewise, unintentional overdose deaths outnumbered motor vehicle crash deaths in Australia in 2011. In Europe, rates have been stable since 2005, but most European countries also have high overdose rates. For example, overdose rates of more than 20 deaths per million are found in 14 of 30 European countries, and rates of more than 40 deaths per million in 7 countries. (https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4605170/)

With this in mind, MediBase was created with the intention to tackle these issues and reduce these risks, bettering the world.


## features:

- search medication by DIN number and QR code
 - returns info about the medication, has option to add the medication to personal list allows you text to speech
- save all your medication in one place
 - navigate between medication where you can see details, have it spoken out loud, and remind you (currently daily) to take the medication - can add and remove
 - provides information on consumption quantity, frequency, warnings, amount left, and any specific instructions from your doctor
- reminds you to take medication
 - uses desktop notifications
- entire website can be translated (TTS too!)
 - profile page lets you switch languages
 - text to speech can speak in other languages as well
- accessibility
 - UI is color-blind friendly
 - has been run through Stark, an accessibility-detection service/program
 - however, we plan to add increased color-blind friendly mode

## to use:
1. clone using `git clone https://github.com/cheollie/medibase`
2. create a `.env` file inside the app directory, inside add api keys
   ```
   REACT_APP_TRANSLATE_KEY=<redacted>
   REACT_APP_TTS_KEY=<redacted>
   ```
3. run `npm install`
4. go into the `app` directory and run `npm start`   
   

## disclaimer: 
If you are testing the site, here are some DIN numbers you can use. Alternatively, see [this API](https://health-products.canada.ca/api/drug/drugproduct/?lang=en&type=json).

```
00000019
00002208
00006211
02368943
00679186
00001783
02454904
02091119
00680583
02369966
00678740
```

## originally for [lyonHacks ii](https://lyonhacks-ii.devpost.com/), adapted for tsf
early code made by [Aaron Z](https://github.com/AAZZAZRON), [Daniel Y](https://github.com/Trentiumz), [Shane C,](https://github.com/mars-flat) and [Chelsea W](https://github.com/cheollie)

adaptions, update with new features made by [Chelsea W](https://github.com/cheollie)


## links
- devpost: https://devpost.com/software/medibase
- pitch: https://docs.google.com/presentation/d/1xFYdHH-4dRTIgZvqZ4tgCKUQOzEZ5CUg_kNnDy_cQ8c/edit
- rough plan: https://www.figma.com/file/ickNcNSETU0XjVJxxnrn8C/MediBase---LyonHacks-II
- website: https://lyonhacks-ii-medibase.herokuapp.com/
