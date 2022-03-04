# Used Car Market

[eBay Kleinanzeigen](https://www.ebay-kleinanzeigen.de/), a [classifieds](https://en.wikipedia.org/wiki/Classified_advertising) section of the German eBay website is a popular market place for used cars. 

## Aim

To get insights into the used car market in Germany and to find the various factors that affect the
resale value, by analyzing [eBay Kleinanzeigen](https://www.ebay-kleinanzeigen.de/).

## Dataset

The entire dataset can be found [here](https://data.world/data-society/used-cars-data). Below are the description of the columns present in the dataset.

* `dateCrawled`: When this ad was first crawled. All field-values are taken from this date.
* `name`: Name of the car.
* `seller`: Whether the seller is private or a dealer.
* `offerType`: The type of listing
* `price`: The price on the ad to sell the car.
* `abtest`: Whether the listing is included in an A/B test.
* `vehicleType`: The vehicle Type.
* `yearOfRegistration`: The year in which the car was first registered.
* `gearbox`: The transmission type.
* `powerPS`: The power of the car in PS.
* `model`: The car model name.
* `odometer`: How many kilometers the car has driven.
* `monthOfRegistration`: The month in which the car was first registered.
* `fuelType`: What type of fuel the car uses.
* `brand`: The brand of the car.
* `notRepairedDamage`: If the car has a damage which is not yet repaired.
* `dateCreated`: The date on which the eBay listing was created.
* `nrOfPictures`: The number of pictures in the ad.
* `postalCode`: The postal code for the location of the vehicle.
* `lastSeen`: When the crawler saw this ad last online.

## Data Cleaning

* Renaming columns to snakecase.
* Removing irrelevent columns.
* Convert `price` and `odometer` columns to int type.
* Removing unrealistic data points.
* Change language of `unrepaired_damage` and `seller` column from german to english.

## Data Analysis

* 97.46% of listing on ebay Kleinanzeigen has a registration year of 1990 or later.
* Volkswagen, BMW and Opel are the top three used car brands being sold on ebay Kleinanzeigen. These companies make affordable car for the general public.
* Porsche, Land Rover and Sonstige autos are the top three most priced used car brands on ebay Kleinanzeigen.They prefer to makes cars for the wealthy.
* Volkswagen Golf is the most popular used car on ebay Kleinanzeigen.
* A damaged used car is ~ 67% cheaper than a non-damaged car.
* As the number of traveled kilometer increased, the average price decreased. Thus kilometers traveled by a used car is indirectly proportional to the price.

## Conclusion

The following conclusions can be made about the used car market in Germany.

* Volkswagen, BMW and Opel are the most popular used cars for sale. These brands offer affordable cars that can be easily resold on eBay Kleinanzeigen.
* Porsche, Land Rover and Sonstige autos are the top three most priced used car brands. These brands tend to bring in a premium and thus can be listed at a higher sticker price.
* Damaged and kilometers traveled are the main reasons for a reduced price in used car.  
