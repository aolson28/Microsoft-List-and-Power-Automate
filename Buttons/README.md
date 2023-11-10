A collection of buttons and other action elements that are used in the Sharepoint List formatting.


Below is a sample button and how to wrap this into a div element:


{
  "elmType": "div",
  "attributes": {
    "class": "sp-card-displayColumnContainer"
  },
  "style": {
    "justify-content": "space-evenly",
    "display": "flex"
  },
  "children": [
    {
      "elmType": "button",
      "txtContent": "Test",
      "style": {
        "width": "108px",
        "height": "30px",
        "color": "#ffffff",
        "background-color": "Green",
        "font-size": "15px",
        "font-weight": "bold",
        "border": "solid",
        "border-width": "2px",
        "border-color": "#c9c9c9",
        "border-radius": "4px",
        "cursor": "pointer",
        "text-align": "center",
        "visibility": "visible",
        "justify-content": "center",
        "box-shadow": "0px 1.6px 3.6px 0 #00000024, 0px 0.3px 0.9px 0 #00000024"
      },
    "customRowAction": {
      "action": "setValue",
      "actionInput": {
        "emailTextField": "@me",
        "DateField": "@now"
        }
      }
    }
  ]
}
