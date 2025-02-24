# TIPS FOR DATA
## If it's some article, text, book, etc.
Avoid:
- too much hot words (>1% is bad)
- outdated words
- too much slang
- this type of data actually
The data should be contained as json file of the structure
{
    "text": < the text >;
    "topics": < list of 1-word topics (please) >
}
and they can be as big as politics debates
## If it contains dialogs
That is cool! But avoid:
- first 2 points from the above
- just fast talks (like "hi howdy fine bye" no it is boring)
You also should separate differrent topics in the same dialog (if you find it difficult than don't mind)
So json for this should look like
{
    "meta-data": < list of topics >;
    "number or name of replic": < replic >;
    "number or name of replic": < replic1 >;
    "number or name of replic": < replic2 >
}
and they don't need to be as big as politics debates