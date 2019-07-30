# Full Stack 1 Assessment

Try your best to answer each question on your own before looking up the answer online. Once you're done writing your first answer, you can google the question and write the best answer you find.

#### 1. What is Enzyme and what are some of the methods that it provides?

Enzyme is a testing application for React. 
Google: Enzyme is a JavaScript Testing utility for React that makes it easier to assert, manipulate, and traverse your React Components’ output. Methods: .toEqual(), .text(), .simulate()

#### 2. What is the difference between dynamic and a static routes? 

Google: In the Static routing, the table is set up and modified manually whereas in the Dynamic routing the table is built automatically with the help of the routing protocols.

#### 3. What is a JSON API?

Google: JSON API documents work as any other API format, you send a request to an endpoint and receive your document. The JSON API specification defines how resources are structured. This structure helps in normalizing how you consume the API. Requests will be sent and received as JSON objects.

#### 4. What is a migration and why would you use one?

A migration is how you add changes/updates to a table in a database, you use it by running db:migrate
Google: Requirements change all the time, and those changes often lead to database changes. Migrations give you a way to modify your database schema within your Rails application. So you use Ruby code instead of SQL. Using Rails migrations instead of SQL has several advantages. Rails migrations are useful any time you need to make a change to your application’s database.

#### 5. Explain how to set up a route in React.

Google: 
  <Router>
    <div>
      <ul>
        <li>
          <Link to="/">Home</Link>
        </li>
        <li>
          <Link to="/users">Users</Link>
        </li>
        <li>
          <Link to="/contact">Contact</Link>
        </li>
      </ul>
      <Route exact path="/" component={App} />
      <Route path="/users" component={Users} />
      <Route path="/contact" component={Contact} />
    </div>
  </Router>
  
The Route tells which component to render when a link is clicked

#### 6. When would you use a generate resource over a generate controller?

Generate resources gives you both a controller and a model, while generate controller gives you just a controller and you would still need to make a model. You use resources to save time.
Google: Generate resource gives you a model, a migration, a controller, and a resource file.

#### 7. Explain the difference between a controller spec and a request spec.

Google: Controller specs are RSpec wrappers for Rails functional tests. They simulate a single HTTP request in each example. By default views are not rendered; the controller spec stubs views with a template that renders an empty string (the template must exist). As you only call a controller action, only the controller is tested. Request specs are RSpec wrappers for Rails integration tests. They are designed to test the entire stack, including routing. You can specify single or multiple requests across multiple controllers or sessions. 

#### 8. Describe the React component lifecycle. What are some of the lifecycle methods?

ComponentDidMount will run as soon as the page is loaded, and componentDidUpdate will run everytime the state of the component is updated
Google: The first thing that gets called is your component constructor, if your component is a class component. This does not apply to functional components. The componentDidMount() method runs after the component output has been rendered to the DOM. componentWillUnmount() runs when the component is removed. 

#### 9. At this point in the program, what technologies/languages do you find yourself gravitating to?

I am really enjoying React the more I use it!