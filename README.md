# Aiir Developer Recruitment Test #

Thanks for your recent application to join us here at [Aiir][aiir] and for agreeing to take the time to complete this technical test.

At our company we're aware that some people can find it difficult to convey their strengths in a traditional interview format. Because you are applying for a technical role, we feel that getting candidates to spend a bit of time working through a problem in code is a good additional way of evaluating what you might be able to bring to a role with us.

When completing this assignment, we would like you to email back a single zip file named {your-name}.zip containing:

1. a folder containing the technical test
2. a single markdown file with the answers to the technical questions

## Coding Test ##

As part of our package we sell mobile applications for iOS and Android. One of the features of the app is the ability for radio stations to send short text messages as push notifications to their listeners phones.

This requires an HTTP API endpoint for the mobile application to hit, to supply a token for that device to be able to send messages to it.

We also require an easy-to-use web form for clients to be able to compose and send these messages. This interface should also show a count of total number of devices available to receive (based on the number of received tokens to the previously described endpoint) and also show a message history of previously sent messages.

The code does not need to actually send a message, though you should clearly show in your code where such a call to dispatch the message would be placed.

### Platform Choice ###

As our primary codebase is written in PHP, your code must also. You may use features up to and inclusive of the latest stable release.

If you use a database, please ensure you supply a schema, dump or provisioning script so that we can recreate the DB for testing.

We deploy all our code to, and make use of the various services offered by, [Amazon Web Services (AWS)][aws]. Consider how you might make best use of the services offered by AWS to complete the task.

### Requirements ###

Feel free to spend as much or as little time on the exercise as you like as long as the following requirements have been met:

* Ensure you have provided all the functionality described above.
* Your code should execute without any errors or exceptions.
* Feel free to use whatever frameworks / libraries / packages you like.

If you require the code to be executed in a particular way, e.g. "Ensure you hit index.php first", please make sure you provide a `README.md` to explain the process required.

If you do decide to develop against any AWS services, we are aware that developing against real services will incur costs, so this is not a requirement. Please simply show the appropriate calls in your code where you would expect to hit live services.

## Technical Questions ##

Please answer the following questions in a markdown file called `Answers to technical questions.md`.

1. How long did you spend on the coding test? What would you add to your solution if you had more time? If you didn't spend much time on the coding test then use this as an opportunity to explain what you would add.
2. How would you track down a performance issue in production? Have you ever had to do this?
3. Please describe yourself using JSON.

Thanks for your time, we look forward to hearing from you!

[aiir]: http://aiir.com/
[aws]: http://aws.amazon.com