1.setImmediate is similar in this regard except that it doesn't use the queue of functions. It checks queue of I/O event handlers.
2.nextTickQueue will be processed after the current operation completes, regardless of the current phase of the event loop. setImmediate() is not exactly immediate
3.buffer, console, crypto, domain, events, globals, http, cluster, errors, os
