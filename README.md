# LD Application for Construction Product Data

## Summary
This project provides a web application for publishing and exploring construction product ontologies.  
Ontologies are formal models that describe concepts, properties, and relationships (often using RDF/OWL).  
While ontologies are machine-readable, this project focuses on making them **human-readable** by publishing them dynamically on the web.

The application uses:
- **GraphDB** for storing and managing ontology data.
- **Node.js & Express** for the backend.
- **Handlebars, HTML, CSS, and JavaScript** for the frontend.
- **SPARQL** for querying RDF data.

This makes it easier to browse, search, and analyze construction product ontologies in a user-friendly way.

---

##  Features
- Store and query construction product ontologies with **GraphDB**.
- Publish ontologies on a dynamic website (no manual file handling).
- SPARQL query interface for advanced data exploration.
- Visualization of ontology classes and relationships.
- Search and browse RDF/OWL classes, resources, and products.
- Download ontologies in multiple formats (Turtle, RDF/XML, JSON-LD).

---

## Project Structure
project/
├── server.js # Starts the server
├── app.js # Express configuration
├── config/ # Database, Express & Handlebars configs
├── controllers/ # Request handling logic
├── routes/ # API and page routes
├── services/ # Business logic & GraphDB interaction
├── utils/ # Helper functions
├── middlewares/ # Label & error handling
├── public/ # Static files (CSS, JS, images)
├── views/ # Handlebars templates
├── .env # Environment variables (GraphDB connection, port, etc.)

---

## Installation & Setup

### 1. Clone the repository
```bash
git clone https://github.com/your-username/ld-construction-product-app.git
cd ld-construction-product-app

2. Install dependencies
npm install


3. Start the server
npm start

4. Open in browser
Go to:
 http://localhost:3000