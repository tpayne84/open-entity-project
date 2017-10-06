## Open Entity Project

The goal of the open entity project is to construct a verified and rated entity database.  An 'Entity' can be nearly anything, though each entity will have several base attributes.  Not the least of which is its core classification type; proper, abstract, or generic ( ...potentially more as I think this through a bit more... ).

- Proper: Think proper noun... An individual person ( IE: John Doe ), Official Business ( IE: Acme Inc ), Specific model of an automobile ( IE: Ford Mustang ), etc...
- Generic: The same as above, but without the specificity.  Any person, any business, any automobile, etc...
- Abstract: This category is for things that are not tangible or do not fit into the other categories.  An idea, an emotion, state of mind, etc...

### What does this solution provide?

1. Heightened data quality: Data is both user submitted and user verified, the user (or cluster of users) that verify submitted data are rewarded by the protocol.
2. Richer entity data: Users are encouraged to share data attributes for entities.  Sharing is encouraged in a supplemental manner, this is to say the users may query the system for entities as long as they pay back into the system with supplemental data of some kind ( this may be in the form of; de-duplication processing, new content, verified supplemental attributes, unverified supplemental attributes, or attribute verification / confidence modification ).
3. Public and Private attributes: Entities are encouraged to claim their entity within the system, as this will allow them to mark select attributes as private.  This will allow users across systems to have a single source for verified entity values, while simultaneously encouraging developers to use the system for identification and authorization.
4. Global association store: Associate an entity with other entities that reference it.

#### Global / Cross domain associations
Quick example on associations: Lets say that a media organization publishes a news article. That article may then be associated with all entities found within the article.  Think of this as a universal backlink index.  Allowing users or applications to create associations ( aka links ) between entities via the appropriate attribute.

### What is verified and what is not?
- Verified: Data that has been added by an official source.  For instance, a person can claim their own identity and provide additional details on themselves.  Note: Even verified data will be subject to the crowd rating for quality control purposes.
- Unverified: User added entities and attributes.  These unverified entities and attributes will have a crowd rated confidence value. Developers can make their own choices about what level of confidence they require.

---

## Contribute

This is all still just an idea I have, though I believe that it could evolve into something very useful.


If you like the idea and would like to join the project let me know!

@ <travis.payne84@me.com>