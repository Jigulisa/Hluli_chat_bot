# Tips for data
1. YOU NEED THE MARKING FOR YOUR DATA

What means you need a thing like
message (actually one message) - is or not spam-message (1 or 0)

you should use .csv format, that is like

{message<string>;is_spam<int>}

but more :)

in euthymic world this should be real messages... unexpected, isn't it?

and actually please don't invent messages, it won't help, but could make worse
in case there's more than one contributor (I wish)

that way we will get a bunch 
of csv files. that's not good. we need only one very big
(one for one language I guess). 

so in a commit what you need to ACTUALLY do is:
1. import pandas (or smth else I don't care, but I won't be able to help)
2. read the existing (now not really) csv dataset
3. in ANY way insert your new data in it
4. save with the same name csv file
5. commit!
that's all. now go to your vegetable chats / friends chat and do marking
