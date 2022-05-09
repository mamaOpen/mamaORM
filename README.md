![mama health logo](https://uploads-ssl.webflow.com/60b4abb6a0bbd14c38ea9621/61b77977d66025433c995676_mama%20health%20slim-p-800.png)

# mamaORM - Redshift Native ORM

#### The ORM you needed, at your fingertips

When we had a transition from DynamoDB, due to a urge to get a OLAP DB working with the front-end, we decided to switch to Redshift instead - aborting the initial idea to have a direct integration with Typeform (that was awful actually).
We at mama health knew that OLAP DB are not the best with ACID transactions, but we also knew that we need a robust DB to handle multiple millions of data and connecting it to a BI tool like Data Studio, and then Redshift came in my mind.
I tried to integrate it to TypeORM but the postgres integration had so many error, that I decided to make our own ORM.
Since this is part of our core system, we will mantain it constantly and we will open just the core functionalities of it.
Feel free to contribute!


Patty @ mama health GmbH
