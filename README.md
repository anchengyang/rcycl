# rcycl
Recycling app built using the React Native framework.

1. Users sign in using their Web3 wallet such as Metamask or Trust Wallet, 
allowing them to receive tokens for every act of recycling.

2. Establishes a connection to Firebase and pulls the latitude, longitude and description of 
recycling bins around the user's live location.

3. Utitlises Google Maps API and React-native-geolocation to display the map with pins of 
current location and location of recycling bins.

4. Scan custom QR codes containing the QR code of a recycling bin, querying the database and 
confirming that the user is within 30 meters of the recycling bin.

5. Custom green tokens called Green N Roll (GNR) would be credited to the user's wallet
within 1 working day from the time of recycling.
