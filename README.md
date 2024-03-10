# SimpleServer

Just build a container

`docker build --rm -t simple_elixir_stress .`

And then you can start a simple server on :4000

`docker run --rm -t simple_elixir_stress -p 4000:4000`
