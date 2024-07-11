# Project Plan

Pod Members: **Kiahna Isadore, Lucky Beulla Muhoza, Samuel Rebuelta-Sanchez, Hanna Abrahem**

## Problem Statement and Description

Insert the latest summary of your problem statement and app description.

## User Roles and Personas

### Roles

- Voter

### Personas

Include at least 2 personas per User Role

- Carmen is a recent high school graduate living a suburb of Cleveland, Ohio. She recently registered to vote but lacks political knowledge. Carmen never paid attention to previous elections, but now wants to educate herself on political candidates. (first-timer)
- Chelsea is a 45 year-old teacher in New York City teaching AP US Government & Politics. She is looking to inform her students on how to keep up with current local elections. (regular)
- Jason is a recent college graduate living San Francisco. He has a good idea about the current political climate and wants to find somewhere he can view elections and possible candidates. (regular)
- Howard is 57 years old and recently became a US citizen but is unfamiliar and overwhelmed by the way the US political system works. He wants to find nearby polling places to exercise his new ability to vote without the hassle of making an account. (first-timer)

## User Stories

1. **As a [new voter], I want to [have a clear and concise explanation of the US election system], so that [I can understand how my vote contributes to the election process]**
2. **As a [frequent voter], I want to [view representatives in my state], so that [I know who my representatives are]**
3. **As a [voter], I want to [receive updates], so that [I know what is coming up]**
4. **As a [voter seeking information], I want to [see election information], so that [I can make informed decisions]**
5. **As a [voter wanting to engage with others], I want to [add/view other users' insights on elections/candidates], so that [I can form better political opinions]**
6. **As a [regular voter], I want to [easily scroll through a list of candidates], so that [I know who is running for a particular election]**
7. **As a [frequent voter], I want to [be able to make an account], so that [I can save my address.]**
8. **As a [voter interested in local politics], I want to [find nearby polling locations], so that [I can vote for candidates in my district.]**
9. **As a [voter interested in local politics], I want to [input my location], so that [I can find info about elections in my area]**
10. **As a [voter], I want to [have access to a chatbot], so that [I can ask further questions that might not be on the website]**

## Pages/Screens

List all the pages and screens in the app. Include wireframes for at least 3 of them.

## Data Model

Describe your app's data model using diagrams or tables

<img width="1792" alt="Screenshot 2024-07-10 at 4 18 31 PM" src="https://github.com/FTL-2024-Pod-H/PollPal/assets/117693506/8496832b-24f2-48cf-8d05-11cdde3b0c69">


## Endpoints

**Google Civic Information API**:
1. Gets all current US Elections: https://www.googleapis.com/civicinfo/v2/elections?key=APIKEY
2. Gets Specifc Election Information by address and ID: https://www.googleapis.com/civicinfo/v2/voterinfo?key=APIKEY&address=ADDRESS&electionId=####
3. Gets US Representatives and local officials: https://www.googleapis.com/civicinfo/v2/representatives?key=APIKEY&address=ADDRESS

**Google Maps API**: 
1. Providing autocomplete suggestions for addresses based on user input: https://maps.googleapis.com/maps/api/place/autocomplete/json?input=USER_INPUT&key=API_KEY
2. Fetch complete address with google format when user selects one place: https://maps.googleapis.com/maps/api/place/details/json?place_id=PLACE_ID&key=API_KEY

**Congress.gov API**:
1. Gets Current Congress members by state: https://api.congress.gov/v3/member/congress/118/STATE?limit=80&api_key=APIKEY



***Don't forget to set up your Issues, Milestones, and Project Board!***
