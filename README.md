# REST API Calls

## Learning Goals

- Review the REST API.

## RESTful API Review

REST (REpresentational State Transfer) is a common way of client-server
interaction. It is a set of rules that define how data should be queried and
managed. A service that is written with these rules is called a RESTful service,
or REST service. Since Spring supports REST services, we'll be working with the
REST API quite a bit in this module. With that said, let's review the six
principles of a REST service:

- **Client-Server Interaction Model:** the application rendering the data and
  the application processing the data are kept separate.
- **Stateless:** Every request from a client must contain the necessary
  information to retrieve or manipulate data on the server. It cannot rely on
  any stored state on the server.
- **Cacheable:** A request-response value can be cached on the server so that
  the server can return repeated requests without having to reprocess data.
- **Uniform Interface:** All RESTful services follow a consistent naming
  convention which makes it easy to work across different services.
- **Layered System:** The client request may be routed through other services
  before reaching the server. A client doesn’t know if it is directly connected
  to a server.
- **Code on Demand:** A client can request executable code from the server in
  the form of applets or scripts.

Be sure to follow
[REST resource naming conventions](https://restfulapi.net/resource-naming/) when
building a REST service.

## Conclusion

A short one or two paragraph summary of the contents of the lessons, recapping
the learning goals.

## Resources

- [Resource Link 1](example.com)
- [Resource Link 2](example.com)
