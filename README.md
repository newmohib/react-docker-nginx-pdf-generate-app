#### Make the Script Executable: Run the following command to make the script executable:

    chmod +x script.sh

#### Run the Script: You can now run the script by executing:

    ./script.sh

### Run with Docker

    docker build -t my-react-app .
    docker run -p 3001:80 my-react-app

## Available Scripts

In the project directory, you can run:

### `npm start`

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can't go back!**

If you aren't satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you're on your own.

You don't have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn't feel obligated to use this feature. However we understand that this tool wouldn't be useful if you couldn't customize it when you are ready for it.

### Deployment

### `npm run build` fails to minify
