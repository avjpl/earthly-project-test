VERSION 0.7
PROJECT avjpl/my-project

FROM alpine:3.18

some-pipeline:
  PIPELINE
  TRIGGER push main
  TRIGGER pr main
  BUILD +my-build

my-build:
  RUN echo Hello world

