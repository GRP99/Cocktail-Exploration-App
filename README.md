# Knowledge Processing and Representation
<div align="center">
    <img src="Images/favicon.ico" width="200" height="200">
    <h1>Cocktail Exploration App</h1>
    <br>
</div>

### Goals
* This work intended to explore knowledge in order to build a computer application that takes advantage of it. For this, it was necessary to choose a theme and a set of data related to it, in order to develop an interactive web interface that makes information available in an easy and accessible way. 
* In the modern world and in the information age, cocktail recipes are widely shared online. The cocktails and bars that serve them are often covered and evaluated in magazines and tourist guides, in this sense the theme chosen for this work was about cocktails. This theme was chosen because it is a theme that the group found with potential to be explored and since there is great knowledge about this area, it would be interesting to build an application that would allow exploring and presenting this knowledge in an easy-to-interpret and interactive way.
---
### How to run
1. Start GraphDB
    1. Create a repository with the name "projectPRC";
    2. Import this [file](/Ontologies/ontology-inferred.ttl) into the created repository;
    3. Make sure GraphDB is listening on port 7200.
2. Start MongoDB
    1. Create a database with the name "cocktailsDB";
    2. With the help of mongoimport import the files present in this [folder](App/api-server/data/);
    3. Make sure MongoDB is listening on port 27017.
3. Start API-Server
    1. Open terminal and access the following directory "[api-server](App/api-server)";
    2. Run <code>npm i</code>;
    3. Run <code>npm start</code>;
    4. Check if API-Server is listening at the port 7300.
4. Start View-Server
    1. Open terminal and access the following directory "[view-server](App/view-server)";
    2. Run <code>npm i</code>;
    3. Run <code>npm start</code>;
    4. Check if API-Server is listening at the port 7301.
---
## Dependencies
* **[GraphDB](https://www.ontotext.com/products/graphdb/graphdb-free/)**
* **[Node](https://nodejs.org/en/)**
* **[Mongo](https://www.mongodb.com/)**
---
### Team
![Gonçalo Pinto][grp-pic] | ![Luís Ribeiro][luis-pic]
:---: | :---:
[Gonçalo Pinto][grp] | [Luís Ribeiro][luis]

[grp]: https://github.com/GRP99
[grp-pic]: https://github.com/GRP99.png?size=120
[luis]: https://github.com/luis1ribeiro
[luis-pic]: https://github.com/luis1ribeiro.png?size=120

<div align="center">
  <sub>February 2021 - July 2021</sub>
</div>
