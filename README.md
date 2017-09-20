ng2inx make few changes in the official nginx image so it will server Angular 2+ correctly

### Usage

You could use it as you would it with the official image

To run it:

  $ docker run --name some-nginx -v /some/content:/usr/share/nginx/html:ro -d ng2inx
