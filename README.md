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
 * DressCode

#### Song

 * Title
 * Notes
 * ComposerFirstName
 * ComposerLastName
 * ArrangedBy
 * Level (`Integer`)
 * ArciveNumber (`Integer`)
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

## Views

### Event List

 * List all upcoming `Events`.
 * Show expired events on current day with striketrough (~~Like this~~)
 * Show `Title`, `Location`,`Start`, `End` (and formatted to/from time)
 * Navigate to older events

### Event detail view
 
 * Show all fields
 * Show list of songs related to this event
 
### Song detail view

 * Show all fields

### Article list view

 * Show `Image`, `Title`, `PublishedDate`

### Article detail view

TODO

### Landing page

 * Join-button → Join page (describing how to join)
 * Contact information
 * 

