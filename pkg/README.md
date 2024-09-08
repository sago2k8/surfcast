# pkg

Shared packages with no clearly owning application go here. Examples: logging,
interceptors for logs, metrics, configuration library stuff, ...

Shared code that is clearly owned by some microservice (but is allowed to be
consumed by other apps) should instead go to apps/some-microservice/\*.
