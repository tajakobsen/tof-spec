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
 * Type ({Rehersal, Concert, Dugnad, Party})

#### Song

 * Title
 * Notes
 * Duration
 * ComposerFirstName
 * ComposerLastName
 * ArrangedBy
 * Level (`Integer`)
 * ArciveNumber (`Integer`)
 * ArchiveUrl (*Only visible when logged in*)
 * MediaUrl (`[Media]`)

### Blog

#### Article

 * Title
 * Introtext
 * Body
 * Image
 * Related (`[Article]`)
 * RelatedEvents (`[Event]`)
 
#### Comments

TODO

## Views

### 1. Event List

 * List all upcoming `Events`.
 * Show expired events on current day with striketrough (~~Like this~~)
 * Show `Title`, `Location`,`Start`, `End` (and formatted to/from time)
 * Navigate to older events

### 2. Event detail view
 
 * Show all fields
 * Show list of `Songs` related to this event
 
### 3. Song detail view

 * Show all fields

### 4. Article list view

 * Show `Image`, `Title`, `PublishedDate`, `Introtext`

### 5. Article detail view

TODO

### 6. Landing page

 * Join-button → Join page (describing how to join)
 * Contact information
 * Grasrotandelen-button

