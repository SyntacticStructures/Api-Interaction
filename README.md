# API interaction task

An html/js app that fetches data from an endpoint and displays them in lists.

## Spec

1) fetch JSON results from https://jsonplaceholder.typicode.com/posts

2) display the titles from the API results in a table, grouped by userId, where each userId is a list. 
    * NOTE: None of the data in the lists should be hard-coded.
    * The resulting lists should look something like:

```
userId: 1 
---------
* nesciunt quas odio
* eum et est occaecati

userId: 2
---------
* another title
* do the same for all users

userId: 3
---------
* ...
* ...
```

3) Use Promises and the fetch api to make your request:
    
    * [Promises](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise)
    * [Fetch API](https://developer.mozilla.org/en-US/docs/Web/API/WindowOrWorkerGlobalScope/fetch)

4) All of this should be tracked using git.
   * **Do not push directly to master. Work on your own branch.**
   * When you are finished, make a pull request to this project and we will do a code review.


## Out of Scope

* CSS is not necessary. Style it if you want, and I'll give feedback, but don't spend time on CSS for this unless you specifically want feedback.

* This is meant to be an exercise, not a good way to display the data. Don't worry about design here.