

# Library REST API

Representative State Transfer Application Programming Interface is a verifies if the data from User interface is valid enough for the sending to server and also vice versa
## Applications [/questions]

### /books [GET]

+ Response 200 (application/json)

        [
            {
                "question": "Operation",
                "choices": [
                    {
                        "choice": "Get"
                    }, {
                        "choice": "Put"
                    }, {
                        "choice": "Post"
                    }, {
                        "choice": "Delete"
                    }
                ]
            }
        ]

### /books/{bookid} [GET]

+ Response 200 (application/json)

        [
            {
                "question": "Operation",
                "choices": [
                    {
                        "choice": "Get"
                    }, {
                        "choice": "Put"
                    }, {
                        "choice": "Post"
                    }, {
                        "choice": "Delete"
                    }
                ]
            }
        ]
        

### /books/{bookname} [GET]

+ Response 200 (application/json)

        [
            {
                "question": "Operation",
                "choices": [
                    {
                        "choice": "Get"
                    }, {
                        "choice": "Put"
                    }, {
                        "choice": "Post"
                    }, {
                        "choice": "Delete"
                    }
                ]
            }
        ]
