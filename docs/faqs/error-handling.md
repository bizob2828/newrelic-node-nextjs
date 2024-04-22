# Injecting Browser Agent

Q: How can I get `@newrelic/next` to log errors to [New Relic Errors Inbox](https://docs.newrelic.com/docs/errors-inbox/errors-inbox/)?

A: The Node.js agent has an API to log errors `newrelic.noticeError`. Next.js has an error page that can be used to add the API call. 


## Log errors to Errors Inbox

The error page varies between [Pages Router](https://nextjs.org/docs/pages/building-your-application/routing/custom-error) and [App Router](https://nextjs.org/docs/app/building-your-application/routing/error-handling) Next.js projects.


 * [Pages Router](https://github.com/newrelic/newrelic-node-examples/blob/main/nextjs-legacy/pages/_error.jsx) error handling example.
 * App Router error handling example coming soon!


