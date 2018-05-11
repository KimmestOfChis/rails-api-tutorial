What I did:
-Generated rails app with -T (skip default tests) and --api
*Application.rb should indicate config is 'api-only'
-Installed factory-girl-rails and rspec rails
-Ran bundle
-Visiting Rails server on localhost:3000

Goal of API:
Get(index & show actions): get data about object
Post(create action): create object with data sent 
Put/Patch (update action): update existing object
Delete (destroy): deletes object 

We want to show articles
Get /articles 
  Ex Response:
  { 
    articles: [
      {
        "id":1,
        "title": "Why do you use Ember?",
        "content": "Sample article content.",
        "slug": "1-why-do-you-use-ember",
      }
    ]
  }

  