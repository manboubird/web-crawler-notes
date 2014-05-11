Architecture
---

![architecture](images/architecture.png)

### Components

| component | software | 
| ------------- |:-------------:| 
| scheduler | scrapy | 
| downloader | scrapy | 
| extractor  | webstruct/boilerpipe/jsoup/kuromoji/tika/scalding |
| analyzer  | scalding/kiji/CascadingPattern | 
| server  | spray | 
| client  | - | 

