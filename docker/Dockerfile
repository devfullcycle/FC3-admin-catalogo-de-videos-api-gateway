FROM kong:2.8.1-alpine

USER root
RUN luarocks install kong-oidc && \
    luarocks install kong-jwt2header && \
    luarocks install kong-upstream-jwt

USER kong
