AxiosError: Request failed with status code 400
    at settle (C:\Users\lkeki\OneDrive\Desktop\BF Lay\node_modules\axios\dist\node\axios.cjs:1909:12)
    at IncomingMessage.handleStreamEnd (C:\Users\lkeki\OneDrive\Desktop\BF Lay\node_modules\axios\dist\node\axios.cjs:2989:11)
    at IncomingMessage.emit (node:events:525:35)
    at endReadableNT (node:internal/streams/readable:1359:12)
    at process.processTicksAndRejections (node:internal/process/task_queues:82:21) {
  code: 'ERR_BAD_REQUEST',
  config: {
    transitional: {
      silentJSONParsing: true,
      forcedJSONParsing: true,
      clarifyTimeoutError: false
    },
    adapter: [ 'xhr', 'http' ],
    transformRequest: [ [Function: transformRequest] ],
    transformResponse: [ [Function: transformResponse] ],
    timeout: 0,
    xsrfCookieName: 'XSRF-TOKEN',
    xsrfHeaderName: 'X-XSRF-TOKEN',
    maxContentLength: -1,
    maxBodyLength: -1,
    env: { FormData: [Function], Blob: [class Blob] },
    validateStatus: [Function: validateStatus],
    headers: AxiosHeaders {
      Accept: 'application/json, text/plain, */*',
      'Content-Type': 'application/json',
      'Cache-Control': 'no-cache, private, no-store, must-revalidate, max-stale=0, post-check=0, pre-check=0',
      'User-Agent': 'axios/1.4.0',
      'Accept-Encoding': 'gzip, compress, deflate, br'
    },
    method: 'get',
    url: 'http://localhost:8888/api/transaction',
    data: undefined
  },
  request: <ref *1> ClientRequest {
    _events: [Object: null prototype] {
      abort: [Function (anonymous)],
      aborted: [Function (anonymous)],
      connect: [Function (anonymous)],
      error: [Function (anonymous)],
      socket: [Function (anonymous)],
      timeout: [Function (anonymous)],
      finish: [Function: requestOnFinish]
    },
    _eventsCount: 7,
    _maxListeners: undefined,
    outputData: [],
    outputSize: 0,
    writable: true,
    destroyed: false,
    _last: true,
    chunkedEncoding: false,
    shouldKeepAlive: false,
    maxRequestsOnConnectionReached: false,
    _defaultKeepAlive: true,
    useChunkedEncodingByDefault: false,
    sendDate: false,
    _removedConnection: false,
    _removedContLen: false,
    _removedTE: false,
    strictContentLength: false,
    _contentLength: 0,
    _hasBody: true,
    _trailer: '',
    finished: true,
    _headerSent: true,
    _closed: false,
    socket: TLSSocket {
      _tlsOptions: [Object],
      _secureEstablished: true,
      _securePending: false,
      _newSessionPending: false,
      _controlReleased: true,
      secureConnecting: false,
      _SNICallback: null,
      servername: 'dev-0ztm3v8co54it1fh.us.auth0.com',
      alpnProtocol: false,
      authorized: true,
      authorizationError: null,
      encrypted: true,
      _events: [Object: null prototype],
      _eventsCount: 10,
      connecting: false,
      _hadError: false,
      _parent: null,
      _host: 'dev-0ztm3v8co54it1fh.us.auth0.com',
      _closeAfterHandlingError: false,
      _readableState: [ReadableState],
      _maxListeners: undefined,
      _writableState: [WritableState],
      allowHalfOpen: false,
      _sockname: null,
      _pendingData: null,
      _pendingEncoding: '',
      server: undefined,
      _server: null,
      ssl: [TLSWrap],
      _requestCert: true,
      _rejectUnauthorized: true,
      parser: null,
      _httpMessage: [Circular *1],
      [Symbol(res)]: [TLSWrap],
      [Symbol(verified)]: true,
      [Symbol(pendingSession)]: null,
      [Symbol(async_id_symbol)]: 71,
      [Symbol(kHandle)]: [TLSWrap],
      [Symbol(lastWriteQueueSize)]: 0,
      [Symbol(timeout)]: null,
      [Symbol(kBuffer)]: null,
      [Symbol(kBufferCb)]: null,
      [Symbol(kBufferGen)]: null,
      [Symbol(kCapture)]: false,
      [Symbol(kSetNoDelay)]: false,
      [Symbol(kSetKeepAlive)]: true,
      [Symbol(kSetKeepAliveInitialDelay)]: 60,
      [Symbol(kBytesRead)]: 0,
      [Symbol(kBytesWritten)]: 0,
      [Symbol(connect-options)]: [Object]
    },
    _header: 'GET /u/login?state=hKFo2SBWaGFyVVM0eXVGSGY2M0RlellMbWtENjBYcW5EeENmZaFur3VuaXZlcnNhbC1sb2dpbqN0aWTZIEswWUstTHlFdTJ3RFpReU9vMTFvRDI5WFFHU1RhTXlmo2NpZNkgcnpMV3loT3RMN3I4Z2ppYld0MllqNVh6ME1OZmhJMzg HTTP/1.1\r\n' +
      'Accept: application/json, text/plain, */*\r\n' +
      'Content-Type: application/json\r\n' +
      'Cache-Control: no-cache, private, no-store, must-revalidate, max-stale=0, post-check=0, pre-check=0\r\n' +
      'User-Agent: axios/1.4.0\r\n' +
      'Accept-Encoding: gzip, compress, deflate, br\r\n' +
      'Host: dev-0ztm3v8co54it1fh.us.auth0.com\r\n' +
      'Connection: close\r\n' +
      '\r\n',
    _keepAliveTimeout: 0,
    _onPendingData: [Function: nop],
    agent: Agent {
      _events: [Object: null prototype],
      _eventsCount: 2,
      _maxListeners: undefined,
      defaultPort: 443,
      protocol: 'https:',
      options: [Object: null prototype],
      requests: [Object: null prototype] {},
      sockets: [Object: null prototype],
      freeSockets: [Object: null prototype] {},
      keepAliveMsecs: 1000,
      keepAlive: false,
      maxSockets: Infinity,
      maxFreeSockets: 256,
      scheduling: 'lifo',
      maxTotalSockets: Infinity,
      totalSocketCount: 1,
      maxCachedSessions: 100,
      _sessionCache: [Object],
      [Symbol(kCapture)]: false
    },
    socketPath: undefined,
    method: 'GET',
    maxHeaderSize: undefined,
    insecureHTTPParser: undefined,
    joinDuplicateHeaders: undefined,
    path: '/u/login?state=hKFo2SBWaGFyVVM0eXVGSGY2M0RlellMbWtENjBYcW5EeENmZaFur3VuaXZlcnNhbC1sb2dpbqN0aWTZIEswWUstTHlFdTJ3RFpReU9vMTFvRDI5WFFHU1RhTXlmo2NpZNkgcnpMV3loT3RMN3I4Z2ppYld0MllqNVh6ME1OZmhJMzg',
    _ended: true,
    res: IncomingMessage {
      _readableState: [ReadableState],
      _events: [Object: null prototype],
      _eventsCount: 4,
      _maxListeners: undefined,
      socket: [TLSSocket],
      httpVersionMajor: 1,
      httpVersionMinor: 1,
      httpVersion: '1.1',
      complete: true,
      rawHeaders: [Array],
      rawTrailers: [],
      joinDuplicateHeaders: undefined,
      aborted: false,
      upgrade: false,
      url: '',
      method: null,
      statusCode: 400,
      statusMessage: 'Bad Request',
      client: [TLSSocket],
      _consuming: true,
      _dumped: false,
      req: [Circular *1],
      responseUrl: 'https://dev-0ztm3v8co54it1fh.us.auth0.com/u/login?state=hKFo2SBWaGFyVVM0eXVGSGY2M0RlellMbWtENjBYcW5EeENmZaFur3VuaXZlcnNhbC1sb2dpbqN0aWTZIEswWUstTHlFdTJ3RFpReU9vMTFvRDI5WFFHU1RhTXlmo2NpZNkgcnpMV3loT3RMN3I4Z2ppYld0MllqNVh6ME1OZmhJMzg',
      redirects: [],
      [Symbol(kCapture)]: false,
      [Symbol(kHeaders)]: [Object],
      [Symbol(kHeadersCount)]: 50,
      [Symbol(kTrailers)]: null,
      [Symbol(kTrailersCount)]: 0
    },
    aborted: false,
    timeoutCb: null,
    upgradeOrConnect: false,
    parser: null,
    maxHeadersCount: null,
    reusedSocket: false,
    host: 'dev-0ztm3v8co54it1fh.us.auth0.com',
    protocol: 'https:',
    _redirectable: Writable {
      _writableState: [WritableState],
      _events: [Object: null prototype],
      _eventsCount: 3,
      _maxListeners: undefined,
      _options: [Object],
      _ended: true,
      _ending: true,
      _redirectCount: 3,
      _redirects: [],
      _requestBodyLength: 0,
      _requestBodyBuffers: [],
      _onNativeResponse: [Function (anonymous)],
      _currentRequest: [Circular *1],
      _currentUrl: 'https://dev-0ztm3v8co54it1fh.us.auth0.com/u/login?state=hKFo2SBWaGFyVVM0eXVGSGY2M0RlellMbWtENjBYcW5EeENmZaFur3VuaXZlcnNhbC1sb2dpbqN0aWTZIEswWUstTHlFdTJ3RFpReU9vMTFvRDI5WFFHU1RhTXlmo2NpZNkgcnpMV3loT3RMN3I4Z2ppYld0MllqNVh6ME1OZmhJMzg',
      _isRedirect: true,
      [Symbol(kCapture)]: false
    },
    [Symbol(kCapture)]: false,
    [Symbol(kBytesWritten)]: 0,
    [Symbol(kNeedDrain)]: false,
    [Symbol(corked)]: 0,
    [Symbol(kOutHeaders)]: [Object: null prototype] {
      accept: [Array],
      'content-type': [Array],
      'cache-control': [Array],
      'user-agent': [Array],
      'accept-encoding': [Array],
      host: [Array]
    },
    [Symbol(errored)]: null,
    [Symbol(kUniqueHeaders)]: null
  },
  response: {
    status: 400,
    statusText: 'Bad Request',
    headers: AxiosHeaders {
      date: 'Fri, 07 Jul 2023 07:36:22 GMT',
      'content-type': 'text/html; charset=utf-8',
      'content-length': '2513',
      connection: 'close',
      'cf-ray': '7e2e6a80b99c392d-KUL',
      'cf-cache-status': 'DYNAMIC',
      'cache-control': 'private, no-store, no-cache, must-revalidate, post-check=0, pre-check=0, no-transform',
      etag: 'W/"9d1-6hiUUXnhLI6r4oAf0L12OmELhQ4"',
      'set-cookie': [Array],
      'strict-transport-security': 'max-age=31536000',
      'ot-baggage-auth0-request-id': '7e2e6a80b99c392d',
      'ot-tracer-sampled': 'true',
      'ot-tracer-spanid': '28539e9f150d8c96',
      'ot-tracer-traceid': '1095029d770cdd9e',
      traceparent: '00-00000000000000001095029d770cdd9e-28539e9f150d8c96-01',
      tracestate: 'auth0-request-id=7e2e6a80b99c392d,auth0=true',
      'x-auth0-requestid': '4ad55daa560e468bdfe1',
      'x-content-type-options': 'nosniff',
      'x-ratelimit-limit': '20',
      'x-ratelimit-remaining': '19',
      'x-ratelimit-reset': '1688715389',
      vary: 'Accept-Encoding',
      server: 'cloudflare',
      'alt-svc': 'h3=":443"; ma=86400'
    },
    config: {
      transitional: [Object],
      adapter: [Array],
      transformRequest: [Array],
      transformResponse: [Array],
      timeout: 0,
      xsrfCookieName: 'XSRF-TOKEN',
      xsrfHeaderName: 'X-XSRF-TOKEN',
      maxContentLength: -1,
      maxBodyLength: -1,
      env: [Object],
      validateStatus: [Function: validateStatus],
      headers: [AxiosHeaders],
      method: 'get',
      url: 'http://localhost:8888/api/transaction',
      data: undefined
    },
    request: <ref *1> ClientRequest {
      _events: [Object: null prototype],
      _eventsCount: 7,
      _maxListeners: undefined,
      outputData: [],
      outputSize: 0,
      writable: true,
      destroyed: false,
      _last: true,
      chunkedEncoding: false,
      shouldKeepAlive: false,
      maxRequestsOnConnectionReached: false,
      _defaultKeepAlive: true,
      useChunkedEncodingByDefault: false,
      sendDate: false,
      _removedConnection: false,
      _removedContLen: false,
      _removedTE: false,
      strictContentLength: false,
      _contentLength: 0,
      _hasBody: true,
      _trailer: '',
      finished: true,
      _headerSent: true,
      _closed: false,
      socket: [TLSSocket],
      _header: 'GET /u/login?state=hKFo2SBWaGFyVVM0eXVGSGY2M0RlellMbWtENjBYcW5EeENmZaFur3VuaXZlcnNhbC1sb2dpbqN0aWTZIEswWUstTHlFdTJ3RFpReU9vMTFvRDI5WFFHU1RhTXlmo2NpZNkgcnpMV3loT3RMN3I4Z2ppYld0MllqNVh6ME1OZmhJMzg HTTP/1.1\r\n' +
        'Accept: application/json, text/plain, */*\r\n' +
        'Content-Type: application/json\r\n' +
        'Cache-Control: no-cache, private, no-store, must-revalidate, max-stale=0, post-check=0, pre-check=0\r\n' +
        'User-Agent: axios/1.4.0\r\n' +
        'Accept-Encoding: gzip, compress, deflate, br\r\n' +
        'Host: dev-0ztm3v8co54it1fh.us.auth0.com\r\n' +
        'Connection: close\r\n' +
        '\r\n',
      _keepAliveTimeout: 0,
      _onPendingData: [Function: nop],
      agent: [Agent],
      socketPath: undefined,
      method: 'GET',
      maxHeaderSize: undefined,
      insecureHTTPParser: undefined,
      joinDuplicateHeaders: undefined,
      path: '/u/login?state=hKFo2SBWaGFyVVM0eXVGSGY2M0RlellMbWtENjBYcW5EeENmZaFur3VuaXZlcnNhbC1sb2dpbqN0aWTZIEswWUstTHlFdTJ3RFpReU9vMTFvRDI5WFFHU1RhTXlmo2NpZNkgcnpMV3loT3RMN3I4Z2ppYld0MllqNVh6ME1OZmhJMzg',
      _ended: true,
      res: [IncomingMessage],
      aborted: false,
      timeoutCb: null,
      upgradeOrConnect: false,
      parser: null,
      maxHeadersCount: null,
      reusedSocket: false,
      host: 'dev-0ztm3v8co54it1fh.us.auth0.com',
      protocol: 'https:',
      _redirectable: [Writable],
      [Symbol(kCapture)]: false,
      [Symbol(kBytesWritten)]: 0,
      [Symbol(kNeedDrain)]: false,
      [Symbol(corked)]: 0,
      [Symbol(kOutHeaders)]: [Object: null prototype],
      [Symbol(errored)]: null,
      [Symbol(kUniqueHeaders)]: null
    },
    data: '<html>\n' +
      '  <head>\n' +
      '    <meta charset="utf-8">\n' +
      '    <link href="https://cdn.auth0.com/styleguide/latest/index.min.css" rel="stylesheet" />\n' +
      '    <link rel="stylesheet" href="https://cdn.auth0.com/backend-templates/main.css">\n' +
      '    <meta name="viewport" content="width=device-width, initial-scale=1">\n' +
      '    <title>dev-0ztm3v8co54it1fh</title>\n' +
      '  </head>\n' +
      '  <body>\n' +
      '    <div class="unhandled-error-cont tenant-error-cont has-logo">\n' +
      '      <div class="error-header">\n' +
      '        <span class="error-icon">\n' +
      '          \n' +
      `          <span class="error-logo" style="background-image: url('https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSEx-OyPnXVp1czLjvEUrHi1DHdTszfe03-Uw&amp;usqp=CAU');"></span>\n` +
      '          \n' +
      '        </span>\n' +
      '        <h3 class="error-title">dev-0ztm3v8co54it1fh</h3>\n' +
      '        \n' +
      '          <h3 class="error-subtitle">Oops!, something went wrong</h3>\n' +
      '        \n' +
      '      </div>\n' +
      '      <div class="error-body">\n' +
      '        <p class="error-message">\n' +
      '          \n' +
      '          There could be a misconfiguration in the system or a service outage. We track these errors automatically, but if the problem persists feel free to contact us.<br/>Please try again.\n' +
      '          \n' +
      '        </p>\n' +
      '      </div>\n' +
      '      <div class="error-footer">\n' +
      '        <div class="footer-groups cf">\n' +
      '          <span class="footer-group">\n' +
      '            <i class="footer-group-icon read-docs"></i>\n' +
      '            <h4 class="footer-group-title">TECHNICAL DETAILS</h4>\n' +
      '            <a href="#" class="toggle-details">See details for this error</a>\n' +
      '          </span>\n' +
      '          <span class="footer-group">\n' +
      '            <h4 class="footer-group-title">SUPPORT</h4>\n' +
      '            \n' +
      '              <p class="footer-group-detail">Please contact the systems administrator.</p>\n' +
      '            \n' +
      '          </span>\n' +
      '        </div>\n' +
      '        <div class="error-details">\n' +
      '          <p class="error-status">\n' +
      '            \n' +
      '            <strong>invalid_request</strong>: You may have pressed the back button, refreshed during login, opened too many login dialogs, or there is some issue with cookies, since we couldn&#39;t find your session. Try logging in again from the application and if the problem persists please contact the administrator.\n' +
      '            \n' +
      '          </p>\n' +
      '          \n' +
      '\n' +
      '          \n' +
      '          <span class="error-id">\n' +
      '            <span class="error-id-title">TRACKING ID: </span><span class="error-id-content">4ad55daa560e468bdfe1</span>\n' +
      '          </span>\n' +
      '          \n' +
      '        </div>\n' +
      '      </div>\n' +
      '    </div>\n' +
      '    <script src="https://cdn.auth0.com/backend-templates/main.js?v=1"></script>\n' +
      '  </body>\n' +
      '</html>\n'
  }
}
