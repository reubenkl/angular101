# angular101
## Part 1 & Part 2
Step 1: Install pre-requisites
1. Install Node.js (LTS version - currently 18 or 20)
Download from nodejs.org

2. Verify installation
node --version
npm --version

3. Install Angular CLI globally
npm install -g @angular/cli@17

4. Verify Angular CLI
ng version

Step 2: Create your first Angular project
ng new my-angular-journey
cd my-angular-journey
ng serve

What does ng-serve do?
 - Compiles TypeScript to JavaScript
 - Bundles your code with Webpack
 - Starts a development server with hot reload
 - Watches for file changes

## Part 3: Angular Architecture Deep Dive
Understanding the Mental Model
Think of Angular like a city:

Components = Buildings (where people live/work)
Services = Utilities (electricity, water, internet)
Modules = Districts (group related buildings)
Dependency Injection = The city's infrastructure system
 Project Structure (Expert Breakdown)

src/
├── app/                    # Your application code
│   ├── app.component.ts    # Root component (the foundation)
│   ├── app.component.html  # Root template
│   ├── app.component.css   # Root styles
│   ├── app.module.ts       # Root module (the blueprint)
│   └── app-routing.module.ts # Navigation routes
├── assets/                 # Static files (images, icons)
├── environments/           # Configuration for different builds
├── index.html             # The single page of your SPA
├── main.ts                # Application bootstrap
└── styles.css             # Global styles

