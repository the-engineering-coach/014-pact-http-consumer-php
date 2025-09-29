# An Introduction to Pact: Consumer & Producer Testing (PHP)

This repository contains all the code for The Engineering Coach's two-part YouTube series on consumer-driven contract testing with Pact. This project serves as a practical demonstration of how to implement both the consumer and producer sides of the Pact workflow in PHP.

## What You'll Learn in This Series
  - The core concept of consumer-driven contract testing and why it's essential for microservices.
  - Part 1 (HTTP Consumer): How to test-drive an HTTP client's implementation by defining the contract it expects from a provider.
  - Part 2 (HTTP Producer): How to verify that an HTTP API's implementation meets the contract defined by its consumer.
  - The benefits of preventing breaking changes between microservices before they ever reach production.

## The Videos

### Part 1: An Introduction to Pact: Consumer-Driven Contract Testing (PHP)

This video covers the consumer side of the contract, where the pact file is generated.

[![Episode 014 Pact Consumer](https://img.youtube.com/vi/Y1Mt8T76-wA/0.jpg)](https://www.youtube.com/watch?v=Y1Mt8T76-wA)


### Part 2: An Introduction to Pact: Testing an HTTP Producer (PHP)

This video covers the producer side, where the contract is verified.

[![Episode 016 Pact Broker](https://img.youtube.com/vi/IEc1ze-OUeI/0.jpg)](https://www.youtube.com/watch?v=IEc1ze-OUeI)

## Getting Started with the Code
To run the code and follow along with the videos, you'll need PHP, Composer, and the Pact PHP library installed.

1. Clone the repository:

```shell
git clone https://github.com/testingallthethings/015-pact-http-producer-php
cd 015-pact-http-producer-php
```

2. Install the dependencies:

```shell
composer install
```

3. Run the tests for the HTTP consumer:

```shell
composer pact:test:consumer
```

4. Run the tests for the HTTP producer:

```shell
composer pact:test:producer
```

## About The Engineering Coach

The Engineering Coach is a YouTube channel dedicated to helping software engineers and engineering managers improve their skills and craft. We provide practical advice and tutorials on topics that matter in the real world of software development.

## Let's Connect

For more software engineering tutorials and coaching, subscribe to The Engineering Coach on YouTube. You can also connect with me on Bluesky or Mastodon.

  - YouTube: [https://www.youtube.com/c/TheEngineeringCoach](https://www.youtube.com/c/TheEngineeringCoac)
  - Mastodon: [https://mastodon.social/@braddle](https://mastodon.social/@braddle)
  - Bluesky: [https://bsky.app/profile/braddle1.bsky.social](https://bsky.app/profile/braddle1.bsky.social)
  - LinkedIn: [https://www.linkedin.com/in/mark-bradley-engineering-coach/](https://www.linkedin.com/in/mark-bradley-engineering-coach/)
 
