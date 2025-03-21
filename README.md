# NamasteReact_2025
This is Git Repository to Practice the React 


React Notes:

1. Try to create hello world program using React CDN Link.
2. Create React Element and render that Element On DOM.
3. Check by trying console what React Create Element method return
    -- Does it have 3 parameters
    -- what 2nd parameter does. props?
    -- 3rd Parameter -> Child 
4. ReactDOM what it does?
5. Create index.css index.html index.js file 

------------------------------------------------------
# Igniting the App

1. What if we want to create nested elements then does create Element method is useful?
2. NPM does not stand for npm package manager - it manages all the packages. All the packages are hosted to npm.
   All the libraries and utilities comes from the NPM.
   NPM init 
   package.json -> Dependencies and configurations.
   Bundler -> Whole code needs to be clean and bundler minifies
   webpack, parcel, vite
   create-react-app -> uses babel and webpack behind the scene
   vite -> is trending now
3. Parcel -> Ignite your app, strength
   Install parcel
   npm install parcel -D
   -D?
   devdependency -> it is requied for the development
   dependency -> for production
   ^ and ~ 
   package.json -> Approximate version of dependencies
   package.lock.json  -> Exact version of dependencies are locked here
   What are the other things in lock.json file then
   node_modules -> why are they -> fetched all the code and copied to the local machine.-> huge.
   Transitive dependencies 
   Dont put all the code of node_modules on production and also on the github too.
   Put package.json and package.lock.json on git.

4. Build app using parcel
   npx parcel index.html
   - npx vs npm
   - execute a package npx -
   - Parcel
      - Dev Build
      - local server
      - hot module replacement
      - File watching algorithm
      - caching builds
      - image optimization
      - file compression
      - bundling
      - minification
   Browserslist

--------------------------------------------------------------------------------
# laying the foundation
