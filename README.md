# angular-todo   

## Built With  
* [TypeScript](https://www.typescriptlang.org/docs/// "TypeScript documentation")  
* [Angular](https://angular.io/docs// "Angular Documentation")  

## Getting Started  
### Prerequisites
* [Node.js](https://nodejs.org/en/ "Download Node.js 16.15.0 LTS")  

### Project Setup (VS Code)
* Angular
  * Install Angular CLI  globally (one time setup)  
  ```bash
  npm install -g @angular/cli
  ng version
  ```   
  * Open project in vsCode (command run in the project directory)  
  ```bash
  code .
  ```   
  * Create Angular App  
  ```bash
  ng new todo-list
  ```    
  * Run the project and open http://localhost:4200   
  ```bash
  ng serve
  ```   
  * Install Bootstrap   
  ```bash
  npm i bootstrap
  ```   


* Create new Angular Component  
  ```bash
  ng generate component component-name
  ```
  * Create new Angular Service  
  ```bash
  ng generate service service-name
  ```

### Topics practiced to get things done  
## Angular  
- Project Structure   
- Component Structure / Creation   
- Data Binding   
- List Iteration   
- Services    
- Dependency Injection   
- Event Handling   

### Error messages for future reference  
❌ Error: Invalid Character (typing ng --version in the terminal)   
Solution: Use bash (workaround)
❌ Error: Property 'name' has no initializer and is not definitely assigned in the constructor.      
Solution: Add ```"strictPropertyInitialization": false``` in the compiler options of the tsconfig.json or a default value to the property.

