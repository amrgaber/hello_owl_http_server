# Static Server Setup

1. Navigate to the source directory (where the `src` folder is located):
   ```
   cd src
   ```
2. Start the Python simple HTTP server with port 8022:
   ```
   python3 -m http.server 8022
   ```

This will make the content available at `http://localhost:8022`.

## About Python's HTTP Server
Python's `http.server` (or `SimpleHTTPServer` in Python 2) is a quick and easy way to serve static files for development or simple deployments. Here are some key points:

- **Simplicity**: It requires no configuration and works out of the box.
- **Directory Listing**: It automatically generates directory listings.
- **Cross-Platform**: Works on any system with Python installed.
- **No Dependencies**: Uses Python's standard library, no additional packages needed.

## Use Cases

- **Local Development**: Test your web projects without setting up a complex server.
- **Quick File Sharing**: Easily share files on your local network.
- **Simple Deployments**: For small projects or prototypes that don't require advanced server features.

## Limitations

- **Performance**: Not suitable for high-traffic production environments.
- **Security**: Lacks advanced security features, use only in trusted environments.
- **Features**: No support for server-side processing or databases.
