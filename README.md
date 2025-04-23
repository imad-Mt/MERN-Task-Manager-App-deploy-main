
1. Backend (Express.js + MongoDB)
API REST avec les routes suivantes :

POST /tasks : Ajouter une nouvelle tâche

GET /tasks : Récupérer toutes les tâches

GET /tasks/:id : Récupérer une tâche par son ID

PUT /tasks/:id : Mettre à jour une tâche par son ID

DELETE /tasks/:id : Supprimer une tâche par son ID

2. Frontend (React.js)
Composants et fonctionnalités :

Input Box : Pour saisir une nouvelle tâche

Search : Pour filtrer les tâches par mot-clé

Liste des tâches : Affichage dynamique de toutes les tâches

Édition : Modifier une tâche existante

Suppression : Supprimer une tâche


Frontend
React.js 18.2.0
React Router DOM 6.30.0
Axios for API calls
Bootstrap 5.3.5 for styling
Backend
Node.js
Express.js
MongoDB
Mongoose
CORS enabled
Prerequisites
Before running this project, make sure you have the following installed:

Node.js
MongoDB (v8.0.4 or higher)
npm (Node Package Manager)



Install frontend dependencies:
npm install
Install backend dependencies:
cd backend
npm install
Running the Application
Start MongoDB service on your machine

Start the backend server:

cd backend
node server.js
The server will run on http://localhost:5000

In a new terminal, start the frontend development server:
cd ..  # Go back to root directory
npm start
The frontend will be available at http://localhost:3000

API Documentation
The API endpoints are available at http://localhost:5000/api:
