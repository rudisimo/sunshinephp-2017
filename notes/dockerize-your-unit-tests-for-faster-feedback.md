# Dockerize your unit tests for faster feedback
> Michelangelo van Dam

## Notes

* Use `--list-groups` to list `@Group` annotations.
* Run phpunit as `CMD` when running container.
* GNU Parallel?
  * phpunit list groups > parallel > docker run > phpunit
* Run docker in daemon mode when running phpunit (`-d`).
* Only act on container exit status.
* Use containers for A/B testing PHP and extension updates.
