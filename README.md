# word-frequency-named-entities
## Computed the word frequency for named entities in a large file.

1. Used a NLP library to extract only the named entities from the text.

2. Wrote code for a mapreduce program that performs wordcount on the extracted named entities.

3. The output from the map task is in the form of (key, Value) where key is the named
entity, and value is its count (i.e. once every time it occurs).

4. The output from the reducer is sorted in descending order of count. That is, the named
entity that is most frequent should appear at the top.
