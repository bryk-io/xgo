# Go cross compiler (xgo): Go 1.13.8
# Copyright (c) 2018 Péter Szilágyi. All rights reserved.
#
# Released under the MIT license.

FROM karalabe/xgo-base

MAINTAINER Péter Szilágyi <peterke@gmail.com>

# Configure the root Go distribution and bootstrap based on it
ENV GO_VERSION 1138

RUN \
  export ROOT_DIST=https://dl.google.com/go/go1.13.8.linux-amd64.tar.gz && \
  export ROOT_DIST_SHA=0567734d558aef19112f2b2873caa0c600f1b4a5827930eb5a7f35235219e9d8 && \
  $BOOTSTRAP_PURE
