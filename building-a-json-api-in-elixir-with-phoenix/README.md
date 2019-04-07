# Building a JSON API in Elixir with Phoenix 1.4

- [Tutorial](https://lobotuerto.com/blog/building-a-json-api-in-elixir-with-phoenix/)

- Start postgres by docker
```shell
docker run --name elixir-postgres -e POSTGRES_PASSWORD=postgres -d -p 5432:5432 postgres
# or just
docker start elixir-postgres
```

- Go to app:
```shell
cd my-app
```

- Then configure your database in config/dev.exs and run:
```shell
mix ecto.create
```

- Start your Phoenix app with:
```shell
mix phx.server
```

- You can also run your app inside IEx (Interactive Elixir) as:
```shell
iex -S mix phx.server
```
