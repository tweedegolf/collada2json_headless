# Collada to JSON converter

The tool runs in a browser and converts Colladas to Threejs' own JSON format. The resulting JSON file can be downloaded to your hard disk. Textures, multimaterial and transparency are supported.

There are 2 versions, this is the headless version: it just converts the Colladas to JSON files and you can download the converted models immediately. The second version shows a preview of the model both as Collada and as JSON and you can choose to download the JSON file, see this [repository](https://github.com/tweedegolf/collada2json)).

The preview version is suitable if you want to convert only one or a few models and check the models side by side for possible conversion errors. If you want to convert a large number of Colladas you’d better use the headless version.

You can checkout the code and run the tool on your local computer, or you can use live versions directly from these urls:

 - [preview version](https://tweedegolf.github.io/collada2json)
 - [headless version](https://tweedegolf.github.io/collada2json_headless)


To run the code on your local computer:

 - npm install
 - npm run watch

The last command starts a local webserver at http://localhost:8001.

All npm scripts:

 - npm start &rarr; starts a local webserver at http://localhost:8001
 - npm run watch &rarr; compiles esnext code to javascript as soon as you have changed code
 - npm run build &rarr; compiles and minifies the code and creates a source map
