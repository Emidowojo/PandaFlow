# PandaFlow
** CTO Search **
# These are the steps to adding JSON files to our Track CTO database
   Apollo uses API keys to allow access to the API, by searching, enriching, i.e passing info into an array, and then adding to databases.
The steps to follow for this task are below
## Step 1
     In Step 1, we are checking for the sequence named **Track CTOs** in the body and the API keys.
### Body of the request
![URL](/Rapidflow/a-1.png.jpeg
)
The URL is placed inside the POST option. Not GET, PATCH, PUT, or DELETE

## Step 2 
     Step 2 shows that the headers content type is an Application/JSON file
     ![URL](/Rapidflow/a-2.png.jpeg)

## Step 3
     In Step 3, we'd be passing an array  ["CTO", "Chief Technology Officer"] into the body. Which is also known as enriching the CTOs information thereby making it more possible to find a match.
![URL](/Rapidflow/b-1.png.jpeg
)

## Step 4
     This is the final step. In here, we'd be adding the contact IDs from the previous step to our sequence
     As Step 2 says, the content type is an Application/JSON file. After adding, we then find a match i.e Track CTOs.
     ![URL](/Rapidflow/c-1.png.jpeg
)
