<!--hide-->
# Create REST API in node js with ***express***
<!--endhide-->

```
🔥 This exercise is designed to be performed by 1 person.
```

<!-- <p align="center">
  <img height="200" src="assets/form.png" />
</p> -->

Technologies: Node, express, express-generator.

We are going to create a REST API that in it we can manage an array of tasks from node/express.

The idea is to create with node and express the different endpoints or routes to perform a CRUD (Create, List, Update, Delete) on an array of tasks.

<onlyfor saas="false" withBanner="false">
  
## 🌱  How to start this project

a) Configure express from scratch.

b) Create the project using express-generator.

💡 Important: save your code to your new repository using `add`, `commit` and `push`.

</onlyfor>

## Strategy

Take a few minutes to analyze 🤯 your strategy on it, identify the elements that you are going to use as express:

Once the strategy is finished you can start coding, start programming 🎊!

## About the project we are going to build

In this project we must build a REST API that exposes the following 4 routes to the internet:

```txt
GET /todos
POST /todos
PUT /todos/:position
DELETE /todos/:position
```

### GET /todos

It should return the existing tasks in the array.

```javascript
[
    {
        "done": false,
        "label": "Sample Todo 1"
    },
    {
        "done": false,
        "label": "Sample Todo 2"
    }
]
```

### POST /todos

We must be able to send the following data to the endpoint and be able to add said data to the tasks array.

```javascript
{
    "done": false,
    "label": "Sample Todo 1"
}
```

### PUT /todos/:position

We must be able to send the following data to the endpoint and be able to update said data in the task array according to its position.

```javascript
{
    "done": true,
    "label": "Sample Todo 1"
}
```

And return the updated list of all.

### DELETE /todos/:position

You should remove the task from our array according to the position given to the endpoint in the url and return the updated list of tasks.
