# Prerequisites and Setup

## 1.1 An animated introduction to MVC
- What happens when a request comes in.
  - First we hit a server then load laravel.
  - Easy to associate URI with a response. Can register these with routes
  - Route will load a controller
    - Recieves a request and provides a response.
  - Controller can delegate to get information from DB. This is done via an Eloquent model.
  - The view is the HTML portion. It recieves data from controller and renders it.

Summary: Request -> Route -> Controller -> Controller delegates to get data for response -> Controller sends data to the view
