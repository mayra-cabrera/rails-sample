This is a simple rails application made for demonstration purposes

### Setup

1. You need to have Docker installed in your machine. And that's it!

### Run the project

To run this application, fire up a terminal and run:

```bash
docker-compose up
```

The first time you run the above command it will download the images and install the gems so be patient :v:. After that, you will see a message like the following in your terminal

```
web_1  | => Rails 5.1.2 application starting in development on http://0.0.0.0:3000
web_1  | => Run `rails server -h` for more startup options
web_1  | Puma starting in single mode...
web_1  | * Version 3.9.1 (ruby 2.4.0-p0), codename: Private Caller
web_1  | * Min threads: 5, max threads: 5
web_1  | * Environment: development
web_1  | * Listening on tcp://0.0.0.0:3000
web_1  | Use Ctrl-C to stop
```

Go to `http://0.0.0.0:3000` on your browser, you should see Rails logo. So congratulations! You have successfully lifted up this application with Docker 🐳
