# token-factories
Collection of token factories for various services. Solves the common problems of token management such as create/save/renew/invalidation etc. Also it could have common logic to choose the best token for the concrete request in order to get maximum info from this request. Ideally it should return Promise or Async Generator with actual request and token.
