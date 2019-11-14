# Interview Test
Test for candidates interested in _Server Side_ development.

## INSTRUCTIONS

* **Collections** are containers, **Products** belong to.
* **Products** have **Collections** associated with them.
* Example of a **Collection** object:
```javascript
{
  id: "0B5F2B26-56BC-43EB-8A3C-3FF607FD079A",
  collectionName: "Women Destination Winter 19 Tees"
}
```
* Example of a **Product** object (after `JSON.parse()`-ing `productCollections`):
```javascript
{
  productName: "Pastel Blue Boxes",
  productCollections: {
    "0B5F2B26-56BC-43EB-8A3C-3FF607FD079A": {
	 name:"Women Destination Winter 19 Tees",
	 id:"0B5F2B26-56BC-43EB-8A3C-3FF607FD079A",
	 .
	 .
	 .
    }
  }
}
```
* You need to write _RESTful APIs_ for both **Products** and **Collections**.
* You need to write an API that updates **Collections** with _Product IDs_
   of the **Products** that are associated with them.
* There's a theoretical/conceptual question in `/question.txt`,
   you'll need to answer that as well.

* You can find the data for both **Collections** and **Products** in `/data` folder.
* The _folder structure_ should be chosen with future development in mind.
    * If you feel there's a certain reason for the _folder structure_ you've
	 chosen to go with, mention it in a seperate file as well.
	 (not important though)
* Use _Express_ to setup the server.
* There will be a million ways to do this, so the way you choose to do it
   will be looked at carefully.
* Fork this repository, do your work, and once the code is done, share your
   repository link in a reply to the original email.

 ## WHAT WE ARE LOOKING FOR
* The _approach_ you take to solve the problems.
* The way you _code_ (this includes coding practices, standards, formatting, etc).
* _Git_ usage.
