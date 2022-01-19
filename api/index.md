# API examples 

    URL: api.2ip.site

[api_docs]: https://volodichev.com/api

## /proxy
> сервис для получения proxy

    https://api.2ip.site/proxy?type=http&count=10

## /phone
> сервис для получения информации по номеру телефона

    https://api.2ip.site/phone?number=74941234567

## /text
> сервис для работы с текстом
#### type:synonim
> "синонимизирует" тексты c pymorphy2 и базой синонимов больше 6000 слов

    https://api.2ip.site/text?type=synonim&text='переданный текст'
    
#### type:perenos
> сервис получения специальных переносов для instagram

    https://api.2ip.site/synonim?type=perenos&text='переданный текст'

