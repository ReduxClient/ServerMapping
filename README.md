To add changes related to a server, the procedure involves a folder containing data.json and logo.png files. 
By adhering to the instructions below, you can initiate a pull request in this repository, and we will promptly review it.

The data.json folder contains all the data a Server needs for Redux Client.
```json
{
  "name": "Hypixel",
  "website": "https://hypixel.net",
  "store": "https://store.hypixel.net",
  "address": [
      "mc.hypixel.net",
      "hypixel.net"
  ],
  "versions": [
      "1.8.*",
      "1.12.*",
      "1.16.*",
      "1.17.*",
      "1.18.*",
      "1.19.*",
      "1.20.*"
  ],
  "regions": [
      "NA"
  ]
}
```
Each time there is a list the first value in it is treated as the primary. So on hypixel primary version is 1.8.*, and primary address is mc.hypixel.net
