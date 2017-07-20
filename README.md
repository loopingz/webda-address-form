# \<webda-address-form\>

Project name:

 - webda-address-form from http://webda.io/

 Description:

  - polymer component that autocomplete an address form using google-map-api -> places-library

 Installation: bower install --save webda-address-form

 Usage:

  - Start typing into "Address input 1" field will provide google places library suggestions

  - When a suggestion is validated (with left-click or Enter) all following fields complete automatically

  - You need to create a google API-KEY access in order to use this component, please visit https://console.developers.google.com/apis/

  - The previously created API-key can be add directly in apiKey value property:

      apiKey: {
        type: String,
        value: 'hereYouCanAddYourApiKey'
      }

  - Otherwise you pass give your API-key through the component when calling it like this:

      <webda-address-form api-key="hereYouCanAddYourApiKey"></webda-address-form>

 Credits:
  - loopingz https://github.com/loopingz
  - 8llouch  https://github.com/8llouch

 External library:
  - google map api
