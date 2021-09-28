# Goal
The goal of this task is to predict which new customers are going to purchase additional baggage for their trips using historical from previous customers. The code can be developed in any of the following languages: R, Python or Java.

# Data Description
The data fields are the following ones:

- **TIMESTAMP**: (date) Date when the booking was bought.
- **WEBSITE**: (string) Website where the trip was purchased. It is composed of a prefix that stands for the website (“ED” = Edreams, “OP” = Opodo, “GO” = Go Voyage) and a suffix for the country (for example: ES = Spain)
- **GDS**: (integer) Number of flights bought through the Global Distribution System
- **NO GDS**: (integer) Number of flights bought though other channels.
- **DEPARTURE**: (date) Departure date
- **ARRIVAL**: (date) Arrival date
- **ADULTS**: (integer) Number of adults
- **CHILDREN**: (integer) Number of children
- **INFANTS**: (integer) Number of infants
- **TRAIN**: (boolean) Whether the booking contains train tickets or not
- **DISTANCE**: (float) Distance travelled
- **DEVICE**: (string) Device used for the purchase
- **HAUL TYPE**: (string) Whether the trip was “Domestic”, “Continental” or “Intercontinental”.
- **TRIP TYPE**: (string) Trips can be either “One Way”, “Round Trip” or “Multi-Destination”
- **PRODUCT**: (string) Bookings can contain only travel (“Trip”) or the travel and a hotel (“Dynpack”).
- **SMS**: (boolean) Indicates if the customer has selected a confirmation by SMS
- **EXTRA BAGGAGE**: (boolean) Variable to predict, only in the train dataset. Indicates if the customer has purchased extra baggage for the trip or not.
