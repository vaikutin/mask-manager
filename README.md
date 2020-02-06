#mask-manager

The mask is a table with products and customers as coordinates.  Each cell tells how backend can send feed optimization messages for user about a product.  Four alternative markings (F no adds or drops, A= adds alloded, D=drops allowed, G=both A and D.  

Similar tables are used also in other AI modules.  Recommender system uses tabling users and product and also tabling users to other users.  Similarities of users and product are tables like this also.

The Mask is a tool for Marketing Manager.

Use cases:
- mark everything as F in the beginning when a new customer starts using JustBrowse, then open up small windows of A and D so that some test customers get optimized feeds for a subset of products.
- Sales persons can receive warnings if they try to drom items that are not marked with D (or G) or add items that are not market with A (or G).
- Marketing Manager can run test marketing by opening feed optimization to some user groups, this primarily tests the effects feed optimication by autogeneration has.  
- Special products like cigarettes, alcohol, or products forbidden for under 18 can be masked so the are not added to decks where they are not wanted or allowed.

Since this is a prototype, please consider modified use cases.  A 3D visualization of the matrix could show the Mask.  But if it is usefull also heat maps of "like/dislike" over the map of customers/products could be usefull.  Think creative in the beginning.  First Mask mapped to 2D is shown in the images subfolder.

