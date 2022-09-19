# API examples 

    URL: api.py4.fun

[api_docs]: https://volodichev.com/api

## /proxy
> сервис для получения proxy

    https://api.py4.fun/proxy?type=http&count=10

## /phone
> сервис для получения информации по номеру телефона

    https://api.py4.fun/phone?number=74941234567

## /text
> сервис для работы с текстом


#### type:synonim
> "синонимизирует" тексты c pymorphy2 и базой синонимов больше 6000 слов

    https://api.py4.fun/text?type=synonim&text='переданный текст'

    
#### type:perenos
> сервис получения специальных переносов для instagram

    https://api.py4.fun/synonim?type=perenos&text='переданный текст'

