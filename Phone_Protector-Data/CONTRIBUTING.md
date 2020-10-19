# Contributing instructions

---
## Usage
This dataset is created for image recognition of food over various doneness levels.

## Instructions

1. Take a look at your phone screen and note down any cracks or scratches.
2. Add in the relevant data (in the correct form) on a new row in the `phone_protector.csv` file
      * Phone Model (use the official name given)
            * For eg: iPhone XR (:+1:), iphonexr (:-1:)
      * Phone's Age (state in years and round up to the nearest whole number)
      * User's Age (state in years and round up to the nearest whole number)
      * User's Gender (choose one of the following)
      ```
            M - Male
            F - Female
            O - Others
      ```
      * User's Occupation
      * Second-Hand (choose one of the following)
      ```
            Y - Yes
            N - No
            U - Unconfirmed
      ```
      * Scratches Severity (choose one of the following)
      ```
            None
            Minor
            Severe
      ```
      * Number of Scratches (whole numbers only)
      * Air Bubbles (choose one of the following)
      ```
            Y - Yes
            N - No
      ```
      * Cracks Severity (choose one of the following)
      ```
            None
            Minor
            Severe
      ```
      * Number of Cracks (whole numbers only)
3. Submit a pull request with your updated csv file. 


## Creating the pull request

1. Fork the project
2. Create a new branch (`git checkout -b "new_contribution"`)
      * Please make sure that the branch is named appropriately. 
3. Commit your change (`git commit -m "Added new phone_protector data"`)
4. Push to your branch (`git push origin new_contribution`)
5. Return to Github and open the pull request
      * Pull request naming convention: `Phone_Protector/<Description_Of_PR>`

## Requirements
1. `phone_protector.csv` file should be updated with your new data entry
2. Data given should be authentic
3. Format of data should be followed


**_Failure to comply with the requirements will lead to your PR being marked as invalid_**

  
  

