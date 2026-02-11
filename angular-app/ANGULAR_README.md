# Angular Hello World Application

A modern Angular application that displays "Hello World" with routing enabled and SCSS styling.

## Features

- ✅ **Modern Angular** - Built with the latest Angular framework
- ✅ **Routing Enabled** - Configured with Angular Router and ready for additional routes
- ✅ **SCSS Styling** - Beautiful gradient background with animations
- ✅ **Responsive Design** - Centered layout that works on all screen sizes
- ✅ **Clean Code** - Minimal, focused implementation following Angular best practices

## Screenshot

![Hello World Angular App](https://github.com/user-attachments/assets/6b4e4e4d-f8b7-4386-a83c-3730638986b1)

## Prerequisites

- Node.js (v18 or higher)
- npm (v9 or higher)

## Installation

```bash
# Navigate to the angular-app directory
cd angular-app

# Install dependencies
npm install
```

## Development Server

```bash
# Start the development server
npm start
```

Navigate to `http://localhost:4200/` in your browser. The application will automatically reload if you change any source files.

## Build

```bash
# Build the project
npm run build
```

Build artifacts will be stored in the `dist/` directory.

## Running Tests

```bash
# Run unit tests
npm test
```

## Project Structure

```
angular-app/
├── src/
│   ├── app/
│   │   ├── app.ts              # Root component
│   │   ├── app.html            # Template with Hello World
│   │   ├── app.scss            # Component styles
│   │   ├── app.config.ts       # Application configuration
│   │   └── app.routes.ts       # Routing configuration
│   ├── index.html              # Main HTML file
│   ├── main.ts                 # Application entry point
│   └── styles.scss             # Global styles
├── angular.json                # Angular CLI configuration
└── package.json                # npm dependencies
```

## Key Technologies

- **Angular**: Modern web framework
- **TypeScript**: Type-safe JavaScript
- **SCSS**: Advanced CSS with nesting and variables
- **Angular Router**: Client-side routing

## Customization

### Changing the Message

Edit `src/app/app.html`:
```html
<div class="hello-world-container">
  <h1>Your Custom Message</h1>
  <router-outlet></router-outlet>
</div>
```

### Modifying Styles

Edit `src/app/app.scss` to customize the gradient, colors, or animations:
```scss
.hello-world-container {
  background: linear-gradient(135deg, #your-color-1 0%, #your-color-2 100%);
  // ... other styles
}
```

### Adding Routes

Edit `src/app/app.routes.ts`:
```typescript
export const routes: Routes = [
  { path: 'home', component: HomeComponent },
  { path: 'about', component: AboutComponent },
  // ... more routes
];
```

## License

MIT
