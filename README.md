# Golang CRUD API

Golang CRUD API is a simple RESTful API project implemented in Go that provides basic CRUD operations for managing a list of movies. The project uses the Gorilla Mux router to handle HTTP requests.

## Project Structure

The project structure is straightforward:

- **main.go:** Entry point of the application. Initializes the router, defines the Movie and Director structs, and implements CRUD operations for managing a list of movies.

## API Endpoints

- `GET /movies`: Retrieve a list of all movies.
- `GET /movies/{id}`: Retrieve a specific movie by ID.
- `POST /movies`: Create a new movie.
- `PUT /movies/{id}`: Update a movie by ID.
- `DELETE /movies/{id}`: Delete a movie by ID.

## Usage

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/yourusername/golang-crud-api.git
   cd golang-crud-api
   ```

2. **Run the Application:**
   ```bash
   go run main.go
   ```
   The application will start on port `8000` by default.

3. **Test Endpoints:**
   - Use a tool like [Postman](https://www.postman.com/) or any HTTP client to test the API endpoints.

4. **Example Data:**
   - The application initializes with some example movie data.

## API Examples

### Get All Movies

- **Endpoint:** `GET /movies`
- **Description:** Retrieve a list of all movies.

### Get Movie by ID

- **Endpoint:** `GET /movies/{id}`
- **Description:** Retrieve details of a specific movie by providing its ID.

### Create New Movie

- **Endpoint:** `POST /movies`
- **Description:** Create a new movie by providing movie details in the request body.

### Update Movie

- **Endpoint:** `PUT /movies/{id}`
- **Description:** Update an existing movie by providing its ID and updated details in the request body.

### Delete Movie

- **Endpoint:** `DELETE /movies/{id}`
- **Description:** Delete a movie by providing its ID.

## Dependencies

- [Gorilla Mux](https://github.com/gorilla/mux): A powerful URL router and dispatcher for golang.

## Contribution

Feel free to contribute to the project by opening issues or submitting pull requests. Your feedback and contributions are highly appreciated!

Happy coding!

