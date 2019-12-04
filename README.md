# Pursuit-Core-Introduction-To-Networking-and-APIs-Lab

# Part One

Status Code Scavenger Hunt!

Use Postman to find each of the following HTTP codes:


1. 200 

```
Ok

```
1. 301
```
Movied permenatly 
```
1. 400

```
bad request 
```
1. 401

```

Unauthorized

```
1. 403

```
forbidden 

```
1. 404

```
not found

```
1. 418

```
Im a teapot

```
1. 500

```
internal server error

```


For each of the questions below, write:

1. The website which generated the HTTP status code
2. A description of what the status code means
3. If an app you were writing encountered this status code, what would you do (if anything) to resolve any issues?


For reference, see:

https://en.wikipedia.org/wiki/List_of_HTTP_status_codes (Links to an external site.)
https://http.cat


# Part Two

API Scavenger Hunt!

For each of the questions below, identify a website and search query that will give you the appropriate JSON.  Paste the url and a snippet of the json below.  Googling the category + API will generally take you to where you need.  Ex. https://lmgtfy.com/?q=cat+fact+api

1. A random cat fact
```
Answer: 
https://catfact.ninja/

{
  "breed": "string",
  "country": "string",
  "origin": "string",
  "coat": "string",
  "pattern": "string"
}

```
1. A list of 150 random users in English.
```
https://randomuser.me/

{
  "results": [
    {
      "gender": "male",
      "name": {
        "title": "mr",
        "first": "brad",
        "last": "gibson"
      },
      "location": {
        "street": "9278 new road",
        "city": "kilcoole",
        "state": "waterford",
        "postcode": "93027",
        "coordinates": {
          "latitude": "20.9267",
          "longitude": "-7.9310"
        },
        "timezone": {
          "offset": "-3:30",
          "description": "Newfoundland"
        }
      },
      "email": "brad.gibson@example.com",
      "login": {
        "uuid": "155e77ee-ba6d-486f-95ce-0e0c0fb4b919",
        "username": "silverswan131",
        "password": "firewall",
        "salt": "TQA1Gz7x",
        "md5": "dc523cb313b63dfe5be2140b0c05b3bc",
        "sha1": "7a4aa07d1bedcc6bcf4b7f8856643492c191540d",
        "sha256": "74364e96174afa7d17ee52dd2c9c7a4651fe1254f471a78bda0190135dcd3480"
      },
      "dob": {
        "date": "1993-07-20T09:44:18.674Z",
        "age": 26
      },
      "registered": {
        "date": "2002-05-21T10:59:49.966Z",
        "age": 17
      },
      "phone": "011-962-7516",
      "cell": "081-454-0666",
      "id": {
        "name": "PPS",
        "value": "0390511T"
      },
      "picture": {
        "large": "https://randomuser.me/api/portraits/men/75.jpg",
        "medium": "https://randomuser.me/api/portraits/med/men/75.jpg",
        "thumbnail": "https://randomuser.me/api/portraits/thumb/men/75.jpg"
      },
      "nat": "IE"
    }
  ],
  "info": {
    "seed": "fea8be3e64777240",
    "results": 1,
    "page": 1,
    "version": "1.3"
  }
}

```

1. All the repos on Github with Pursuit their name
```
https://learn.co/lessons/github-repo-list

"owner": {
  "login": "mojombo",
  "id": 1,
  "avatar_url": "https://avatars.githubusercontent.com/u/1?",
  "gravatar_id": "25c7c18223fb42a4c6ae1c8db6f50f9b",
  "url": "https://api.github.com/users/mojombo",
  "html_url": "https://github.com/mojombo",
  "followers_url": "https://api.github.com/users/mojombo/followers",
  "following_url": "https://api.github.com/users/mojombo/following{/other_user}",
  "gists_url": "https://api.github.com/users/mojombo/gists{/gist_id}",
  "starred_url": "https://api.github.com/users/mojombo/starred{/owner}{/repo}",
  "subscriptions_url": "https://api.github.com/users/mojombo/subscriptions",
  "organizations_url": "https://api.github.com/users/mojombo/orgs",
  "repos_url": "https://api.github.com/users/mojombo/repos",
  "events_url": "https://api.github.com/users/mojombo/events{/privacy}",
  "received_events_url": "https://api.github.com/users/mojombo/received_events",
  "type": "User",
  "site_admin": false
}

```

1. All the JavaScript repos on Github with Pursuit in their name


1. All the Swift repos on Github with Pursuit in their name


1. A list of all Pokemon

1. A list of all items in Fortnite

```
https://docs.fortniteapi.com/?version=latest


{
    "data": [
        {
            "itemId": "2fad344-834e456-dcf643d-91f9712",
            "lastUpdate": 1553386039,
            "store": {
                "isFeatured": true,
                "isRefundable": true,
                "cost": "1500"
            },
            "item": {
                "name": "Beastmode",
                "description": "Gassed up and ready to roar.",
                "type": "outfit",
                "rarity": "epic",
                "images": {
                    "icon": "https://fortnite-public-files.theapinetwork.com/outfit/c567e52c290292c99c7c9b44dd36827c.png",
                    "featured": "https://fortnite-public-files.theapinetwork.com/featured/2fad344-834e456-dcf643d-91f9712.png",
                    "background": "https://fortnite-public-files.theapinetwork.com/image/2fad344-834e456-dcf643d-91f9712.png",
                    "information": "https://fortnite-public-files.theapinetwork.com/image/2fad344-834e456-dcf643d-91f9712/icon.png"
                },
                "obtained_type": "vbucks",
                "ratings": {
                    "avgStars": 3.66,
                    "totalPoints": 597,
                    "numberVotes": 163
                }
            }
        },
        {
            /*/ SAME STRUCTURE AS ABOVE /*/
        }
    ]
}
```

1. A list of all Game of Thrones Episodes.

1. A list of all songs with "Love" in the title.
1. All information about Petyr Baelish from the Game of Thrones books
1. All the movies Leonardo Dicaprio has acted in
