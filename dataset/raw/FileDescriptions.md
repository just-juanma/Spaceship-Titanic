# File and Data Field Descriptions
* __trains.csv__ - Personal records for about two-thirds (~8700) of the passengers, to be used as training data.
    * _PassengerId_ - A unique Id for each passenger. Each Id takes the form _gggg_pp_ where _gggg_ indicates a group the passenger is travelling with and _pp_ is their number within the group. People in a group are often family members, but not always.
    * _HomePlanet_ - The planet the passenger departed from, typically their planet of permanent residence.
    * _CryoSleep_ - Indicates whether the passenger elected to be put into suspended animation for the duration of the voyage. Passengers in cryosleep are confined to their cabins.
    * _Cabin_ - The cabin number where the passenger is staying. Takes from _deck/num/side_, where _side_ can be either _P_ for Port ir _S_ for Starboard.
    * _Destination_ - The planet the passenger will be debarking to.
    * _Age_ - The age of the passenger.
    * _VIP_ - Whether the passenger has paid for special VIP service during the voyage.
    * _RoomService, FoodCourt, ShoppingMall, Spa, VRDeck_ - Amount the passenger has billed at each of the Spaceship Titanic's many luxury amenities.
    * _Name_ - The first and last names of the passenger.
    * _Transported_ - Whether the passenger was transported to another dimension. This is the target, the column trying to predict.
* __test.csv__ - Personal records for the remaining one-third (~4300) of the passengers, to be used as test data. Your task is to predict the value of _Transported_ for the passengers in this set. 