#tsuru-static-app

Docker image that can be easily deployed as a tsuru static application.

You can deploy it to tsuru using:

```
% tsuru app-deploy -a myapp -i fsouza/tsuru-static-app
```

If you prefer to just upload the code to tsuru, you can have a static app and deploy it:

```
% tsuru app-deploy -a myapp .
```
