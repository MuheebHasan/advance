**GreenThumb- The project outlined in the document involves the development of a backend API for GreenThumb, a platform dedicated to fostering urban gardening, sustainable living, and community-driven food production. The API will serve as a central hub for individuals, communities, and organizations to collaborate, share knowledge, and access resources related to urban gardening and sustainable living practices. It will incorporate features such as community garden directories, crop planning and tracking, knowledge sharing, resource exchange, volunteer coordination, and local partnership integration. The climate emphasis is on integrating weather and data, soil and pest management resources, user privacy, and data security. The projects encourage creativity and offers flexibility in technology choices, while also requiring thorough documentation, version control, and testing.**
## Table of Contents 
* [Introdcution](https://github.com/MuheebHasan/advance.wiki.git?tab=readme-ov-file#-introdcution)
* [Main Features](https://github.com/MuheebHasan/advance.wiki.git?tab=readme-ov-file#main-features)
* [Additional Features](https://github.com/MuheebHasan/advance.wiki.git?tab=readme-ov-file#additional-features)
* [Technologies Used](https://github.com/MuheebHasan/advance.wiki.git?tab=readme-ov-file#technologies-used)
* [Project Folders](https://github.com/MuheebHasan/advance.wiki.git?tab=readme-ov-file#project-folders)
* [API Documentation](https://github.com/MuheebHasan/advance.wiki.git?tab=readme-ov-file#api-documentation)
* [Getting Started](https://github.com/MuheebHasan/advance.wiki.git?tab=readme-ov-file#getting-started)

## Introdcution 

**GreenThumb- The project outlined in the document involves the development of a backend API for GreenThumb, a platform dedicated to fostering urban gardening, sustainable living, and community-driven food production. The API will serve as a central hub for individuals, communities, and organizations to collaborate, share knowledge, and access resources related to urban gardening and sustainable living practices. It will incorporate features such as community garden directories, crop planning and tracking, knowledge sharing, resource exchange, volunteer coordination, and local partnership integration. The climate emphasis is on integrating weather and data, soil and pest management resources, user privacy, and data security. The projects encourage creativity and offers flexibility in technology choices, while also requiring thorough documentation, version control, and testing.**

## Main Features
1. Community Gardens: A directory of community gardens, including their locations, 
available plots, and specific growing conditions (sunlight, soil type, etc.), allowing users to 
find and join local gardening initiatives. 
2. Crop Planning and Tracking: Users can plan and track their gardening activities, including 
crop rotations, planting schedules, and harvest records, enabling data-driven decision
making and resource optimization. 
3. Knowledge Sharing: A curated library of gardening guides, tutorials, and best practices, 
contributed by experienced gardeners and organizations, fostering knowledge sharing 
within the community. 
4. Resource Exchange: A platform for users to exchange or share gardening resources, such 
as tools, seeds, compost, and surplus produce, and reducing waste. 
5. Volunteer Coordination: coordinating volunteers for community garden maintenance, 
events, and educational workshops, facilitating community collaboration. 
6. Local Partnership Integration: Integration with local nurseries, farms, and organizations 
to promote their products, services, and events.

## Additional Features
*  External API Integration: Used to improve functionality and augment data collecting.
*  Authentication and Authorizationusing JWT library : JWT provides a compact and secure way to authenticate users and manage authorization by allowing identity information to be securely transmitted between parties and including authorization claims within the token payload.
*  Roles features : admin role and user .


## Technologies Used
1. Node.js: as a Backend development platform.
2. MySQL: Database.
3. Postman: API building and documentation tool.
4. Git: Version control system.
5. Axios: making and managing HTTP requests.

## API Documentation
The API is fully documented using Postman. Access the documentation [here] ([link](https://www.postman.com/grey-satellite-759134/workspace/advance/collection/34092625-8bf83446-9fb7-41ca-acf5-a8ba15c500a5?action=share&creator=34092625)).

## Project Folders
 In our project, we've chosen a layered architecture, consisting of the Model, Controller, and Services components. Here's why it's important:

* Controller:
1. Manages the flow of data and user interaction.
2. Receives input from the user interface and delegates tasks to appropriate services.
3. Organizes the application's behavior and ensures proper communication between different parts of the system.

* Service:
1. Contains reusable business logic and operations.
2. Performs tasks such as data manipulation, validation, and interaction with external systems.
3. Encapsulates complex operations into modular and reusable units, promoting maintainability and scalability.

* Model:
1. Represents the data and business logic of the application.
2. Manages data storage, manipulation, and validation.
3. Defines the structure and behavior of the application's data, ensuring consistency and integrity.

![image](https://github.com/MuheebHasan/advance/tree/main/utils/Capture.PNG)

## Getting Started
1. Clone the repository:https://github.com/MuheebHasan/advance.git.
2. Install dependencies: `npm install`
3. Configure environment variables.
4. Setup the database using mysql.
5. Run the application: `npm start`
