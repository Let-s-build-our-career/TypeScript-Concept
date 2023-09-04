
# TypeScript-Concept

<details>
<summary>Introduction to TypeScript</summary>

#### 1. What is TypeScript?

TypeScript is a programming language developed by microsoft and superset of JavaScript. When combined, they provide a powerful development environment for building robust and maintainable web applications.

#### 2. Advantages of TypeScript over JavaScript or Why TypeScript?

 * Adds static typing to JavaScript
 * It helps us to see bugs when writing codes; easy to find and fix bugs
 * Gives us auto suggestion
 * Provides us better documentation

#### 3. Setting up the Development Environment
</details>



 <details>
<summary>
#Start React TypeScript Project
</summary>

### Installation

Install my-project with npm

```bash
  npm create vite@latest School-Management -- --template react typescript
  cd School-Management
  npm run dev
```

    
### Usage/Examples

```javascript
import React from 'react';

// Define the props interface for the component
interface GreetingProps {
  name: string;
}

// Define a functional component using an arrow function
const Greeting: React.FC<GreetingProps> = ({ name }) => {
  return (
    <div>
      <h1>Hello, {name}!</h1>
      <p>This is a React functional component written in TypeScript.</p>
    </div>
  );
};

export default Greeting;
```
</details>







