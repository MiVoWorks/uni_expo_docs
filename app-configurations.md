# App Configurations

## Firebase App Configuration

Bellow, there is a JSON of all the values that you can use to manage the app 

```
{
  "appImage" : "IMAGE_LINK",
  "appLogo" : "IMAGE_LINK",
  "appNavLogo" : "IMAGE_LINK",
  "appSplash" : "IMAGE_LINK",
  "name" : "News app",
  "design" : {
    "general" : {
      "backgroundColor" : "#e9e9ef",
      "buttonColor" : "#9C26B0",
    },
  },
  "settings":{
    "login":{
      "hideLogin":false
    }
  },
  "navigation" : {
    "menus" : [ 
    {
      "categorySetup" : {
        "category_style" : "grid2",
        "data_point" : "news_collection",
        "fields" : {
          "description" : "description",
          "image" : "image",
          "title" : "title"
        }
      },
      "category_first" : false,
      "detailsSetup" : {
        "cartIcons" : [ "ios-calendar-outline", "ios-person-outline", "ios-card-outline", "ios-list-box-outline" ],
        "cartLabels" : [ "Event", "Register", "Payment", "Summary" ],
        "cartPayPalAvailable" : true,
        "collections" : [ "variants", "ingredients", "photos" ],
        "descriptionTitle" : "Description",
        "fields" : {
          "description" : "description",
          "descriptionFunctions" : ",",
          "direction" : "eventLocation",
          "price" : "price",
          "priceFunctions" : "round,toCurrency~USD,prepend~Price: ",
          "shareLink" : "shareLink",
          "subPrice" : "price",
          "subPriceFunctions" : "multiply~{qty},round,toCurrency~USD,prepend~/per ticket.",
          "subtitle" : "locationName",
          "subtitle2" : "eventDateStart",
          "subtitle2Functions" : "toReadableDate~YYYY-MM-DD HH:mm",
          "subtitle2Icon" : "ios-time-outline",
          "subtitle3" : "eventDateEnd",
          "subtitle3Functions" : "toReadableDate~YYYY-MM-DD HH:mm",
          "subtitle3Icon" : "ios-timer-outline",
          "subtitleAction" : "location",
          "subtitleActionFunction" : "openGps",
          "subtitleFunctions" : " ",
          "subtitleIcon" : "ios-pin-outline",
          "title" : "title",
          "titleFunctions" : "trim:40",
          "video" : "video"
        },
        "isDirectShopping" : true,
        "isShopping" : false,
        "navButtonAction" : "add-to-favorites",
        "navButtonActionDoneIcon" : "check",
        "navButtonIconActiveIcon" : "star",
        "photosTitle" : "Photos",
        "shareButton" : "Share this post",
        "showNavButton" : true,
        "showPhotos" : false,
        "videoButton" : "View Video"
      },
      "icon" : "FeBook",
      "isRoot" : true,
      "listStyle" : "grid",
      "listingSetup" : {
        "collection_key" : "collection_news",
        "data_point" : "news",
        "fields" : {
          "actionButton" : "BUY",
          "description" : "description",
          "image" : "image",
          "subtitle" : "date",
          "subtitleFunctions" : "toReadableDate~YYYY-MM-DD HH:mm",
          "title" : "title"
        },
        "hasFeatures" : true,
        "listing_style" : "list",
        "showCategoryFilter" : false
      },
      "name" : "News",
      "section-type": "masterdetail"
    }],
    "type" : "tab"
  }
}

```



