title: rest (representational state transfer)
level: basic

REST is a set of general requirements for client-server communciation.

Most of the time, REST is talked about in the context of Web API. It's also called RESTful API.

RESTful APIs are most commonly seen using [JSON](/json) over [HTTP](/http).

### Constraints

* URI for resource access
    * `http://example.com/items` for collection
    * `http://example.com/items/item_id` for member
* Standard HTTP methods
    * `GET` for retrieve. repeatable and cacheable
    * `POST` for create
    * `PUT` for replace
    * `PATCH` for update
    * `DELETE` for delete
