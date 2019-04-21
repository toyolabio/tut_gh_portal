# TutGhPortal

To start your Phoenix server:

  * Run services with `docker-compose up -d`

## If you don't have `Docker` installed yet, you need to install `Docker` first.
## Download `Docker` for Mac or Window via this [link](https://www.docker.com/get-started)
## You need to Sign Up first if you don't have Docker account yet. 

And run following commands with `docker-compose run web <commands>`

  * Install dependencies with `mix deps.get`
  * Create and migrate your database with `mix ecto.setup`
  * Compile assets with `bash -c "cd assets && yarn"`

Now you can visit [`localhost:4000`](http://localhost:4000) from your browser.

You can enter running container with `docker exec -it tut_gh_portal_web_1 bash`

If you stop Docker services
  * Stop with `docker-compose stop`
  * Stop and remove volumes with `docker-compose down`

Ready to run in production? Please [check our deployment guides](https://hexdocs.pm/phoenix/deployment.html).

## Learn more

  * Official website: http://www.phoenixframework.org/
  * Guides: https://hexdocs.pm/phoenix/overview.html
  * Docs: https://hexdocs.pm/phoenix
  * Mailing list: http://groups.google.com/group/phoenix-talk
  * Source: https://github.com/phoenixframework/phoenix
