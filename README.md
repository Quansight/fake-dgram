# fake-dgram
Mock dgram package to use on the web


https://github.com/jaegertracing/jaeger-client-node depends on the dgram node package. cause its for node.

I wanna try running it in my browser, not using its UDP support, which is what the dgram package provides.

So I am making a mock `dgram` package here that i can still from github so that webpack doesn't complain about a missing module.
