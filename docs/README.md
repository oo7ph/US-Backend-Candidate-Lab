at# CP+B Backend Candidate Lab

## Documentation

API Hosted at: http://cplab.gopagoda.com/

## Notes

### Stuff to note (no pun intended):
* Authentication is done over basic HTTP
* Notes stored securely using a RIJNDAEL-256 block cipher

### TO DO:
* Implment OAuth for a more robust authentication layer
* Abstract/Refactor business logic from controllers to models
* Abstract cryptastic from httpbasicauth into it's own middleware
* Implement over HTTPS vs normal http
* Implement Digest instead of basic auth
* Abstract controller return value so you no longer have to set headers, do json etc.
* Started work on integration unit tests but did
* add pagination for return results

## Documentation:

API Documentation can be found at http://docs.cplab.apiary.io/

apiary serves as an easy integration testing and document generator
