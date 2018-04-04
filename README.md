![](https://raw.githubusercontent.com/Netflix/vizceral/master/logo.png)

# JumpCloud Vizceral Dashboard Frontend

Forked from [vizceral-example](https://github.com/Netflix/vizceral-example) and changed to point at a custom backend rather than `src/sample_data.json`. Runs as a webpack dev server with a proxy to `vizeral-api` for the `/data` route.


# Original Documentation
## Vizceral Example
This is a sample application using the [React wrapper](https://github.com/Netflix/vizceral-react) around the [vizceral](https://github.com/Netflix/vizceral) graph.
For more details about using vizceral in your own projects with your own data, refer to the above repositories.

## Setup
1. Get source, install deps, and run demo server.

   ```sh
   git clone git@github.com:Netflix/vizceral-example.git
   cd vizceral-example
   npm install
   npm run dev
   ```

2. Open `localhost:8080` in your browser.

##### Using Docker
If you don't have a node environment setup or would like to run this example on a platform, there is a Dockerfile for experimental usage.

```
$ docker build -t <name>/vizceral-example .
```
```
$ docker run -p 41911:8080 -d <name>/vizceral-example
```

Then you should be able to navigate to http://localhost:41911
