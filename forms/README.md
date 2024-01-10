## Getting Started

- Install the version of Node JS for your OS https://nodejs.org/en/download
- From a terminal run the following commands to check if the installation was successful:
  - `$ node -v`
  - `$ npm -v`
  - Set PATH environment variable to path/to/bin/node and path/to/bin/npm if the above commands failed to return the version number.
- In the terminal install dependencies using the command:
    `$ npm install`
- In the terminal run the local server using the command:
  - `node form-server.js`
- Open "form.html" in a browser. Enter username and password and click "Submit".

## Questions for you to answer
1. What is the purpose of the _action_ attribute in the _form_ tag?

Determines the destination of the form data (via URL)

2. What is the purpose of the _method_ attribute in the _form_ tag?

Determines how the form data is sent to the destination

3. What is the purpose of the _name_ attribute in the _input_ tag?

A name allows the input's data to be passed to the destination when submitted

4. What is the purpose of the _type_ attrbute in the _input_ tag?

Determines the specific input element used for this tag (e.g. password, text, 
radio, button, etc...)

5. What is the purpose of the _label_ tag?

Provides a description of the input element AND makes it easier to select the
element connected to the label by serving as a button

6. What is the purpose of the _required_ attribute?

Prevents the form from being submitted without completing the input elements
with this attribute (enforce mandatory inputs)