

```python
import mediacloud, datetime
mc = mediacloud.api.MediaCloud('KEY')
res = mc.sentenceCount('( obama AND president)', solr_filter=[mc.publish_date_query( datetime.date( 2015, 8, 1), datetime.date( 2015, 8, 31) ), 'media_sets_id:1' ])
print res['count']
```

    5501



```python
import mediacloud, datetime
mc = mediacloud.api.MediaCloud('KEY')
res = mc.sentenceCount('( trump AND president)', solr_filter=[mc.publish_date_query( datetime.date( 2015, 8, 1), datetime.date( 2015, 8, 31) ), 'media_sets_id:1' ])
print res['count']
```

    1076



```python
import mediacloud, datetime
mc = mediacloud.api.MediaCloud('KEY')
res = mc.sentenceCount('( sanders AND president)', solr_filter=[mc.publish_date_query( datetime.date( 2015, 8, 1), datetime.date( 2015, 8, 31) ), 'media_sets_id:1' ])
print res['count']
```

    261



```python
import mediacloud, datetime
mc = mediacloud.api.MediaCloud('KEY')
res = mc.sentenceCount('( clinton AND president)', solr_filter=[mc.publish_date_query( datetime.date( 2015, 8, 1), datetime.date( 2015, 8, 31) ), 'media_sets_id:1' ])
print res['count']
```

    1758



```python
import mediacloud, datetime
mc = mediacloud.api.MediaCloud('KEY')
res = mc.sentenceCount('( digital AND comics)', solr_filter=[mc.publish_date_query( datetime.date( 2015, 1, 1), datetime.date( 2015, 11, 15) ), 'media_sets_id:1' ])
print res['count']
```

    132



```python
import mediacloud, datetime
mc = mediacloud.api.MediaCloud('KEY')
res = mc.sentenceCount('( comics)', solr_filter=[mc.publish_date_query( datetime.date( 2015, 1, 1), datetime.date( 2015, 12, 31) ), 'media_sets_id:1' ])
print res['count']
```

    10406



```python
import mediacloud, datetime
mc = mediacloud.api.MediaCloud('KEY')
res = mc.sentenceCount('( comic books)', solr_filter=[mc.publish_date_query( datetime.date( 2015, 1, 1), datetime.date( 2015, 12, 31) ), 'media_sets_id:1' ])
print res['count']
```

    106218



```python
import mediacloud, datetime
mc = mediacloud.api.MediaCloud('KEY')
res = mc.sentenceCount('( comics OR comic books)', solr_filter=[mc.publish_date_query( datetime.date( 2015, 1, 1), datetime.date( 2015, 12, 31) ), 'media_sets_id:1' ])
print res['count']
```

    115423



```python
import mediacloud, datetime
mc = mediacloud.api.MediaCloud('KEY')
res = mc.sentenceCount('( graphic novels)', solr_filter=[mc.publish_date_query( datetime.date( 2015, 1, 1), datetime.date( 2015, 12, 31) ), 'media_sets_id:1' ])
print res['count']
```

    27145



```python
import mediacloud, datetime
mc = mediacloud.api.MediaCloud('KEY')
res = mc.sentenceCount('( comics OR graphic novels)', solr_filter=[mc.publish_date_query( datetime.date( 2015, 1, 1), datetime.date( 2015, 12, 31) ), 'media_sets_id:1' ])
print res['count']
```

    37297



```python
import mediacloud, datetime
mc = mediacloud.api.MediaCloud('KEY')
res = mc.sentenceCount('( comics AND graphic novels)', solr_filter=[mc.publish_date_query( datetime.date( 2015, 1, 1), datetime.date( 2015, 12, 31) ), 'media_sets_id:1' ])
print res['count']
```

    198



```python

```
