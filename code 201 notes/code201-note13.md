# Read 13

Local Storage is a web storage solution that allows web applications to store data on the client's browser. It provides a simple key-value storage mechanism.

#### 1. Why would a developer use local storage for a web application?

Developers use local storage in web applications to store and manage data on the client-side (in the user's browser). Local storage is a web storage solution that stores key-value pairs locally.

#### 2. What information should not be stored in local storage?

- Sensitive User Information

- Authentication Tokens without Encryption

- Sensitive Application State

- Large Amounts of Data

- Unencrypted Data

- Sensitive Configuration Information

#### 3. Local storage can store what type of data? How would you convert it to that type before storing?

Local sttorage stores data in the form of strings. To store arrays or objects, you'll need to convert them to JSON strings using `JSON.stringify()` before storing. The data can be retrieved by using `JSON.parse()`.


# Things I want to know more about
