#### Installing Polymer Using Bower
- Step 1
    - To start from scratch using Bower method, install the Bower using the following command.

        `npm install -g bower`
- Step 2
    - Install the Polymer using the following command.

        `npm install -g polymer-cli`
- Step 3
    - Check the successful installation and version of Polymer, using the following command.

    `polymer --version`
    
    If it has installed successfully, then it will show the version as −

    `1.6.0`
- Step 4
    - To install the latest Polymer from bower, use the following command.

    `bower install Polymer/polymer#^2.5.0`
    
- Step 5
    - Create a index.html file and add the following code in the `<head>` tag.
    
            <!-- to load the polyfills -->
            <script src="/bower_components/webcomponentsjs/webcomponents-loader.js"></script>
            <!-- to import Polymer -->
            <link rel="import" href="/bower_components/polymer/polymer.html">
            
- Step 6 
    - Import and use whichever elements you’d like in <body> section.
    
- Step 7 
    - Start your project using the following command.

        `polymer serve`