# smartParking

This GUI performs the following features:

- Data management using JSON syntax (signup/login/place reservation/entry time)
- User Data handling in JSON file (to be created "subscribed.json" and directory set for the JSON module in node red)
- Data exchange between nodes via the MQTT broker Eclipse Mosquitto

System Nodes :

- Parking Entry (user check-in via access key generated)
- Parking Hall (places occupancy update for the GUI sake)
- Parking Exit (user check-out after payment of the ticket)
