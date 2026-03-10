# System Architecture

LearnSphere follows a **three-layer architecture**.

Client Layer
React frontend application.

Application Layer
Node.js backend API.

Data Layer
MySQL database.

System flow:

Client → API Server → Database → Storage

Each organization is assigned a **tenant ID** to isolate data.

Example:

Organization A

* Users
* Courses
* Analytics

Organization B

* Users
* Courses
* Analytics
