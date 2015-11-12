# Piper
Welcome to Piper, Rawnet's UI styleguide and boilerplate.

To use the boilerplate: 
- Download the [ZIP](https://github.com/dahliacreative/piper/zipball/master)
- Extract the ZIP to your project root
- In terminal, from your project root, run `npm install`
- Edit `GruntConfig.json` to meet your requirments
- Ensure there is a `.gitignore` file with the following:
    -   ```
        .sass-cache\s\s
        .DS_Store\s\s
        node_modules\s\s
        *.map\s\s
        /path/to/build/directory
        ```
- In terminal from your project root, run `grunt` to compile and watch for further changes; or
- Run `grunt build` to simply build the project
