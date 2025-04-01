🌐 Application Architecture - Easy Study Notes
🧱 1. Monolith vs. Microservices
Monolithic App:

Single codebase.

All features (UI, business logic, database) live together.

Easier to start, harder to scale or update parts independently.

Microservices App:

Split into independent services (auth, payments, etc.).

Easier to scale, update, and deploy individually.

Requires good communication between services (APIs).

🛜 2. Client-Server Model
Client: User-facing (e.g., browser or mobile app).

Server: Responds to requests (e.g., delivers data, processes logic).

Communication: Usually through HTTP/HTTPS.

🧑‍💻 3. Frontend vs. Backend
Frontend (Client-side):

What users see: UI, buttons, forms.

Tech: HTML, CSS, JavaScript, React, etc.

Backend (Server-side):

Logic and data processing.

Tech: Node.js, Java, Python, databases, etc.

🧰 4. APIs (Application Programming Interface)
Definition: Rules that allow software to talk to each other.

REST API: Common type using HTTP methods like GET, POST, PUT, DELETE.

🗃️ 5. Databases
Stores persistent data.

Types:

Relational (SQL): Structured (e.g., MySQL, PostgreSQL).

Non-relational (NoSQL): Flexible schema (e.g., MongoDB).

☁️ 6. Deployment & Hosting
Localhost: Your own computer.

Production: Live for users on the internet.

Cloud Providers: AWS, GCP, Azure, Heroku.

🔁 7. Load Balancers
Distributes traffic across multiple servers.

Helps with scalability and availability.

🧠 8. Stateless vs. Stateful
Stateless: Each request is independent (no memory).

Stateful: Server remembers previous interactions (e.g., sessions).

🧱 9. Layers of an App (MVC Pattern)
Model: Data & business logic.

View: What the user sees.

Controller: Handles user input and updates model/view.

🔐 10. Authentication & Authorization
Authentication: Who are you? (e.g., login).

Authorization: What can you do? (e.g., permissions).

⚙️ 11. DevOps Tools
Helps with CI/CD: Continuous Integration/Continuous Deployment.

Tools: GitHub Actions, Jenkins, Docker, Kubernetes.

🧾 12. Logging & Monitoring
Logging: Record of system activity (errors, info, warnings).

Monitoring: Real-time insights (e.g., app health, server load).

✅ Quick Recap
Concept	Meaning
Monolith	All-in-one app
Microservices	Independent services
Client	Sends request
Server	Responds to request
API	Communication rules
Database	Stores data
Deployment	Make app live
Load Balancer	Distributes traffic
Stateless	No memory
Stateful	Has memory
MVC	Model-View-Controller
Auth	Login + Permissions
DevOps	Automate build & deploy
Logs/Monitoring	Track and observe app behavior
