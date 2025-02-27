# TIPS FOR DATA
### If it's some article, text, book, etc.
Avoid:
- too much hot words (>1% is bad)
- outdated words
- too much slang
- this type of data actually
- 
The data should be contained as json file of the structure

{

    "text": < the text >;
    "topics": < list of 1-word topics (please) >

}

and they can be as big as politics debates
### If it contains dialogs
That is cool! But avoid:
- first 2 points from the above
- just fast talks (like "hi howdy fine bye" no it is boring)

You also should separate differrent topics in the same dialog (if you find it

difficult than don't mind)

So json for this should look like

{

    "meta-data": < list of topics >;
    "number or name of replic": < replic >;
    "number or name of replic": < replic1 >;
    "number or name of replic": < replic2 >
}

and they don't need to be as big as politics debates

# ЗАМЕТКИ О РАЗМЕТКЕ
### Если это какая-то статья, текст, книга и т.п.
Избегать:
- слишком много мата (>1% — плохо)
- устаревшие слова
- слишком много сленга
- этот тип текстов лол
- 
Данные должны содержаться в виде json-файла структуры.

{

    "текст": <текст>;
    "topics": <список тем, каждая в 1 слово (пожалуйста)>
}
и они могут быть такими же масштабными, как политические дебаты
### Если он содержит диалоги
Это круто! Но избегайте:
- первые 2 пункта из раздела про тексты
- просто быстрые разговоры (типа «привет, че как, пока», нет, это скучно)

Вам также следует разделить разные темы в одном диалоге (если вам сложно, то черт бы с ним)

Итак, json для этого должен выглядеть так

{

    "метаданные": <список тем>;
    "номер или имя реплики": <реплик>;
    "номер или имя реплики": <replic1>;
    «номер или имя реплики»: <replic2>
}

и они не должны быть такими огромными и длинными, как политические дебаты