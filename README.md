# Specification for the new TOF Webpage

## ContentTypes

### Events

#### Event content-type

 * Title
 * Description
 * Start (`DateTime`)
 * End (`DateTime`)
 * Location
 * GoogleMapsUrl
 * Image
 * Songs (`[Song]`)
 * ContactPerson (`User`)

#### Song

 * Title
 * Notes
 * ComposerFirstName
 * ComposerLastName
 * ArrangedBy
 * Level (`Integer`)
 * ArchiveUrl (*Only visible when logged in*)
 * VideoUrl

### Blog

#### Article

 * Title
 * Body
 * Image
 * Related (`[Article]`)
 * RelatedEvents (`[Event]`)
 
#### Comments

TODO


