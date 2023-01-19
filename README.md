# duchpops# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`


### Deployment

This section has moved here: [https://facebook.github.io/create-react-app/docs/deployment](https://facebook.github.io/create-react-app/docs/deployment)

### `npm run build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)
\///////

This project was created by: Kristal Davis Mitchell
This is a multi-page application. The app was built to create, read, update , and delete data in a database and produce it in the frontend of the application.

Built With
React
Bootstrap 5.2a
[Express](nom install express) [EJS Templates]($ npm install ejs) [Sequelize](npm install --save sequelize) CSS Javascript

dependencies
node_modules]: https://nodejs.org/en/download/current/. /.pnp .pnp.js

Getting Started
Create a new node project folder. Initialize the Git Repository Connect to GitHub (optional) Create your main application file Initialize the Node Project --> First install and configure the modules for Bootstrap,Express,EJS, SQl for a virtual environment just like any other application on your computer, ensure that they are installed..

Prerequisites
Front-end Requirements
You must have a UI of some kind! But you can build using any number of technologies. Here are some ideas:
React, React Native, ReactVR
Hardware based (motion, gesture, or voice activated)
Electron (HTML/CSS/JavaScript apps for the desktop


What is DuchPopsDuchPops is a homemade popsicle company based in Bermuda. They have been in business for seven years and currently does not have a website. This project is a prototype for an e-commerce website. The main objective is to provide a way for consumers to view current products, add to bag, *check-out via cart, book ept.js via a clean sleek optimal viewing site.

Roadmap
M.V.P.

Provide the following:
Achieved functionality 
Renders correct template with data
Uses routes and route parameters 
Correctly structures routes to create readable, nested URL paths.
Add to cart responsive.
Calendly installation
Database in progress

Stretch Goals

Provide the following:
-The ability to upload items into a cart modal
-Complete finishing touches on the styling
-Connect Backend

Code Snippet

  const listCards = ProductInfo.map((product, index) => 
    
    <Card key={index} style={{ width: '18rem' }} className="mx-3 mb-3">
      <Card.Img variant="top" src={product.image} />
    
      <Card.Body>
        <Card.Title> {product.description} </Card.Title>
      
        {product.price}
        <br>
        </br>
        <Button variant="primary" onClick={()=>{handleSubmit(product.description,product.price,1 )}}>Add to Cart</Button>
        {/* <Button variant="primary" onClick={handleClick}>Add to Cart</Button>
         */}
      </Card.Body>
    </Card> 
  );

  return <>
    <div>
      <Container className='justify-items-center' style={{border:
      '1px  black'}}>
        <Row className="align-items-center">

          { listCards }

        </Row>
      </Container>
    </div>
  </>
}

export default ProductsCard

Contact
Kristal Davis Mitchell: https://www.linkedin.com/in/kristal-davis-mitchell-05777841/
JavaScript HTML CSS Bootstrap Sequelize Express Ejs Node.js Bcrypt
