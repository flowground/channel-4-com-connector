# ![LOGO](logo.png) Channel 4 **flow**ground Connector

## Description

A generated **flow**ground connector for the Channel 4 API (version 1.0.0).

Generated from: https://api.apis.guru/v2/specs/channel4.com/1.0.0/swagger.json<br/>
Generated at: 2019-05-07T17:39:55+03:00

## API Description

This is the place to come for all the technical details you need to power your applications with Channel 4's deep programmes data.

## Authorization

Supported authorization schemes:
- API Key
## Actions

### 4oD Browse by Date Feed

> Information of daily broadcast content available on 4oD, according to <br/>
>   broadcast date<br/>
> <br/>
>   http://api.channel4.com/pmlsd/4od/episode-list/date/[yyyy]/[mm]/[dd].atom?apikey=xxxxxxxxxxxxxxxxxxxxxxxx<br/>
> <br/>
>   http://api.channel4.com/pmlsd/4od/episode-list/date/2010/11/28.atom?apikey=xxxxxxxxxxxxxxxxxxxxxxxx

*Tags:* `discoveryresources`

#### Input Parameters
* `platform` - _optional_ - The platform to use for the query. Alias 'client'.
    Possible values: c4, ps3, yv, ios, fm, p06, ctv, freesat, android, samsung.
* `yyyy` - _required_ - The date for which you wish to see programming information
* `mm` - _required_ - The date for which you wish to see programming information
* `dd` - _required_ - The date for which you wish to see programming information

### 4oD Most Popular Episodes Feed

> Information of the most popular content available on 4oD, according to user <br/>
>   data driven.<br/>
> <br/>
>   http://api.channel4.com/pmlsd/4od/episode-list/popular.atom?apikey=xxxxxxxxxxxxxxxxxxxxxxxx<br/>
> <br/>
>   http://api.channel4.com/pmlsd/4od/episode-list/popular.atom?apikey=xxxxxxxxxxxxxxxxxxxxxxxx

*Tags:* `discoveryresources`

#### Input Parameters
* `platform` - _optional_ - The platform to use for the query. Alias 'client'.
    Possible values: c4, ps3, yv, ios, fm, p06, ctv, freesat, android, samsung.

### 4oD Clips Catch Up Feed

> A feed containing metadata about short-form content relating to 4oD Episodes <br/>
>   recently added to 4oD based on linear transmission. The entries for the <br/>
>   Clips Landing Feed contain references to each short-form asset. It will <br/>
>   return up to 20 entries.<br/>
> <br/>
>   http://api.channel4.com/pmlsd/4od/recently-added/videos.atom?apikey=xxxxxxxxxxxxxxxxxxxxxxxx<br/>
> <br/>
>   http://api.channel4.com/pmlsd/4od/episode-list/videos.atom?apikey=xxxxxxxxxxxxxxxxxxxxxxxx

*Tags:* `discoveryresources`

#### Input Parameters
* `platform` - _optional_ - The platform to use for the query. Alias 'client'.
    Possible values: c4, ps3, yv, ios, fm, p06, ctv, freesat, android, samsung.

### A to Z Landing Feed

> Lists Channel 4 programmes alphabetically from A to Z, providing the same <br/>
>   functionality and information as is available in the A to Z section of the <br/>
>   Channel 4 Programmes page, http://www.channel4.com/programmes.<br/>
> <br/>
>   http://api.channel4.com/pmlsd/atoz.atom<br/>
> <br/>
>   http://api.channel4.com/pmlsd/atoz.atom?apikey=xxxxxxxxxxxxxxxxxxxxxxxx

*Tags:* `discoveryresources`

#### Input Parameters
* `platform` - _optional_ - The platform to use for the query. Alias 'client'.
    Possible values: c4, ps3, yv, ios, fm, p06, ctv, freesat, android, samsung.

### A to Z Letter Feed

> Lists Channel 4 programmes whose names begin with the associated letter.<br/>
> <br/>
>   http://api.channel4.com/pmlsd/atoz/start_letter.atom?apikey=xxxxxxxxxxxxxxxxxxxxxxxx<br/>
> <br/>
>   http://api.channel4.com/pmlsd/atoz/a.atom?apikey=xxxxxxxxxxxxxxxxxxxxxxxx

*Tags:* `discoveryresources`

#### Input Parameters
* `platform` - _optional_ - The platform to use for the query. Alias 'client'.
    Possible values: c4, ps3, yv, ios, fm, p06, ctv, freesat, android, samsung.
* `start_letter` - _required_ - The letter of the alphabet for which you seek associated Channel 4 programmes

### A to Z Letter Feed(2)

> Lists Channel 4 programmes whose names begin with the associated letter.<br/>
> <br/>
>   http://api.channel4.com/pmlsd/atoz/start_letter/page-{pageno}.atom?apikey=xxxxxxxxxxxxxxxxxxxxxxxx<br/>
> <br/>
>   http://api.channel4.com/pmlsd/atoz/a.atom?apikey=xxxxxxxxxxxxxxxxxxxxxxxx

*Tags:* `discoveryresources`

#### Input Parameters
* `platform` - _optional_ - The platform to use for the query. Alias 'client'.
    Possible values: c4, ps3, yv, ios, fm, p06, ctv, freesat, android, samsung.
* `start_letter` - _required_ - The letter of the alphabet for which you seek associated Channel 4 programmes
* `pageno` - _required_ - Page number of results to return

### 4oD Title All Brands Feed

> Lists all Channel 4 programmes available on 4oD.  By default, the programmes <br/>
>   are listed by title in alphabetical order (case unsensitive).<br/>
> <br/>
>   http://api.channel4.com/pmlsd/brands/4od.atom?apikey=xxxxxxxxxxxxxxxxxxxxxxxx<br/>
> <br/>
>   http://api.channel4.com/pmlsd/brands/4od.atom?apikey=xxxxxxxxxxxxxxxxxxxxxxxx

*Tags:* `discoveryresources`

#### Input Parameters
* `platform` - _optional_ - The platform to use for the query. Alias 'client'.
    Possible values: c4, ps3, yv, ios, fm, p06, ctv, freesat, android, samsung.

### 4oD Title All Brands Feed(2)

> Lists all Channel 4 programmes available on 4oD.  By default, the programmes <br/>
>   are listed by title in alphabetical order (case unsensitive).<br/>
> <br/>
>   http://api.channel4.com/pmlsd/brands/4od/page-{pageno}.atom?apikey=xxxxxxxxxxxxxxxxxxxxxxxx<br/>
> <br/>
>   http://api.channel4.com/pmlsd/brands/4od.atom?apikey=xxxxxxxxxxxxxxxxxxxxxxxx

*Tags:* `discoveryresources`

#### Input Parameters
* `platform` - _optional_ - The platform to use for the query. Alias 'client'.
    Possible values: c4, ps3, yv, ios, fm, p06, ctv, freesat, android, samsung.
* `pageno` - _required_ - Page number of results to return

### 4oD Popular All Brands Feed

> Lists all Channel 4 programmes available on 4oD by popularity considering <br/>
>   the data gathered within the last 7 days.<br/>
> <br/>
>   http://api.channel4.com/pmlsd/brands/4od/popular.atom?apikey=xxxxxxxxxxxxxxxxxxxxxxxx<br/>
> <br/>
>   http://api.channel4.com/pmlsd/brands/4od/popular.atom?apikey=xxxxxxxxxxxxxxxxxxxxxxxx

*Tags:* `discoveryresources`

#### Input Parameters
* `platform` - _optional_ - The platform to use for the query. Alias 'client'.
    Possible values: c4, ps3, yv, ios, fm, p06, ctv, freesat, android, samsung.

### 4oD Popular All Brands Feed(2)

> Lists all Channel 4 programmes available on 4oD by popularity considering <br/>
>   the data gathered within the last 7 days.<br/>
> <br/>
>   http://api.channel4.com/pmlsd/brands/4od/popular/page-{pageno}.atom?apikey=xxxxxxxxxxxxxxxxxxxxxxxx<br/>
> <br/>
>   http://api.channel4.com/pmlsd/brands/4od/popular.atom?apikey=xxxxxxxxxxxxxxxxxxxxxxxx

*Tags:* `discoveryresources`

#### Input Parameters
* `platform` - _optional_ - The platform to use for the query. Alias 'client'.
    Possible values: c4, ps3, yv, ios, fm, p06, ctv, freesat, android, samsung.
* `pageno` - _required_ - Page number of results to return

### Popular Brands Feed

> Lists all Channel 4 programmes by popularity considering the data gathered <br/>
>   within the last 7 days.<br/>
> <br/>
>   http://api.channel4.com/pmlsd/brands/popular.atom?apikey=xxxxxxxxxxxxxxxxxxxxxxxx<br/>
> <br/>
>   http://api.channel4.com/pmlsd/brands/popular.atom?apikey=xxxxxxxxxxxxxxxxxxxxxxxx

*Tags:* `discoveryresources`

#### Input Parameters
* `platform` - _optional_ - The platform to use for the query. Alias 'client'.
    Possible values: c4, ps3, yv, ios, fm, p06, ctv, freesat, android, samsung.

### Popular Brands Feed(2)

> Lists all Channel 4 programmes by popularity considering the data gathered <br/>
>   within the last 7 days.<br/>
> <br/>
>   http://api.channel4.com/pmlsd/brands/popular/page-{pageno}.atom?apikey=xxxxxxxxxxxxxxxxxxxxxxxx<br/>
> <br/>
>   http://api.channel4.com/pmlsd/brands/popular.atom?apikey=xxxxxxxxxxxxxxxxxxxxxxxx

*Tags:* `discoveryresources`

#### Input Parameters
* `platform` - _optional_ - The platform to use for the query. Alias 'client'.
    Possible values: c4, ps3, yv, ios, fm, p06, ctv, freesat, android, samsung.
* `pageno` - _required_ - Page number of results to return

### Categories Landing Feed

> Lists Channel 4 programmes by category (/ tag).<br/>
> <br/>
>   http://api.channel4.com/pmlsd/categories.atom?apikey=xxxxxxxxxxxxxxxxxxxxxxxx<br/>
> <br/>
>   http://api.channel4.com/pmlsd/categories.atom?apikey=xxxxxxxxxxxxxxxxxxxxxxxx

*Tags:* `discoveryresources`

#### Input Parameters
* `platform` - _optional_ - The platform to use for the query. Alias 'client'.
    Possible values: c4, ps3, yv, ios, fm, p06, ctv, freesat, android, samsung.

### All Programmes by TX Date

> Lists all Channel 4 programmes associated with the specified category (tag).  <br/>
>   By default, the programmes are listed in order of Transmission (TX) Date, <br/>
>   with the most-recently-transmitted programmes listed first.<br/>
> <br/>
>   http://api.channel4.com/pmlsd/categories/category.atom?apikey=xxxxxxxxxxxxxxxxxxxxxxxx<br/>
> <br/>
>   http://api.channel4.com/pmlsd/categories/animals.atom?apikey=xxxxxxxxxxxxxxxxxxxxxxxx

*Tags:* `discoveryresources`

#### Input Parameters
* `platform` - _optional_ - The platform to use for the query. Alias 'client'.
    Possible values: c4, ps3, yv, ios, fm, p06, ctv, freesat, android, samsung.
* `category` - _required_ - The name of the category for which you seek associated Channel 4 programmes. (For a full list of categories, please see http://api.channel4.com/pmlsd/categories.atom?apikey=xxxxxxxxxxxxxxxxxxxxxxxx)

### 4oD Programmes by TX Date

> Lists all Channel 4oD programmes associated with the specified category <br/>
>   (tag).By default, the programmes are listed in order of Transmission (TX) <br/>
>   Date, with the most-recently-transmitted programmes listed first.<br/>
> <br/>
>   http://api.channel4.com/pmlsd/categories/category/4od.atom?apikey=xxxxxxxxxxxxxxxxxxxxxxxx<br/>
> <br/>
>   http://api.channel4.com/pmlsd/categories/animals/4oD.atom?apikey=xxxxxxxxxxxxxxxxxxxxxxxx

*Tags:* `discoveryresources`

#### Input Parameters
* `platform` - _optional_ - The platform to use for the query. Alias 'client'.
    Possible values: c4, ps3, yv, ios, fm, p06, ctv, freesat, android, samsung.
* `category` - _required_ - The name of the category for which you seek associated Channel 4 programmes. (For a full list of categories, please see http://api.channel4.com/pmlsd/categories.atom?apikey=xxxxxxxxxxxxxxxxxxxxxxxx)

### 4oD Programmes by TX Date(4)

> Lists all Channel 4oD programmes associated with the specified category <br/>
>   (tag).By default, the programmes are listed in order of Transmission (TX) <br/>
>   Date, with the most-recently-transmitted programmes listed first.<br/>
> <br/>
>   http://api.channel4.com/pmlsd/categories/category/4od/page-{pageno}.atom?apikey=xxxxxxxxxxxxxxxxxxxxxxxx<br/>
> <br/>
>   http://api.channel4.com/pmlsd/categories/animals/4oD.atom?apikey=xxxxxxxxxxxxxxxxxxxxxxxx

*Tags:* `discoveryresources`

#### Input Parameters
* `platform` - _optional_ - The platform to use for the query. Alias 'client'.
    Possible values: c4, ps3, yv, ios, fm, p06, ctv, freesat, android, samsung.
* `category` - _required_ - The name of the category for which you seek associated Channel 4 programmes. (For a full list of categories, please see http://api.channel4.com/pmlsd/categories.atom?apikey=xxxxxxxxxxxxxxxxxxxxxxxx)
* `pageno` - _required_ - Page number of results to return

### Most Popular Brands Feed

> Lists all Channel 4oD most popular brands for the given category within the <br/>
>   last 7 days, in order of popularity.<br/>
> <br/>
>   http://api.channel4.com/pmlsd/categories/category/4od/popular.atom?apikey=xxxxxxxxxxxxxxxxxxxxxxxx<br/>
> <br/>
>   http://api.channel4.com/pmlsd/categories/comedy/4od/popular.atom?apikey=xxxxxxxxxxxxxxxxxxxxxxxx

*Tags:* `discoveryresources`

#### Input Parameters
* `platform` - _optional_ - The platform to use for the query. Alias 'client'.
    Possible values: c4, ps3, yv, ios, fm, p06, ctv, freesat, android, samsung.
* `category` - _required_ - The name of the category for which you seek associated Channel 4 programmes. (For a full list of categories, please see http://api.channel4.com/pmlsd/categories.atom?apikey=xxxxxxxxxxxxxxxxxxxxxxxx)

### Most Popular Brands Feed(5)

> Lists all Channel 4oD most popular brands for the given category within the <br/>
>   last 7 days, in order of popularity.<br/>
> <br/>
>   http://api.channel4.com/pmlsd/categories/category/4od/popular/page-{pageno}.atom?apikey=xxxxxxxxxxxxxxxxxxxxxxxx<br/>
> <br/>
>   http://api.channel4.com/pmlsd/categories/comedy/4od/popular.atom?apikey=xxxxxxxxxxxxxxxxxxxxxxxx

*Tags:* `discoveryresources`

#### Input Parameters
* `platform` - _optional_ - The platform to use for the query. Alias 'client'.
    Possible values: c4, ps3, yv, ios, fm, p06, ctv, freesat, android, samsung.
* `category` - _required_ - The name of the category for which you seek associated Channel 4 programmes. (For a full list of categories, please see http://api.channel4.com/pmlsd/categories.atom?apikey=xxxxxxxxxxxxxxxxxxxxxxxx)
* `pageno` - _required_ - Page number of results to return

### 4oD Programmes by Title

> Lists all Channel 4oD programmes associated with the specified category <br/>
>   (tag), alphanumerically in order of Title.<br/>
> <br/>
>   http://api.channel4.com/pmlsd/categories/category/4od/title.atom?apikey=xxxxxxxxxxxxxxxxxxxxxxxx<br/>
> <br/>
>   http://api.channel4.com/pmlsd/categories/religion-and-belief/4oD/title.atom?apikey=xxxxxxxxxxxxxxxxxxxxxxxx

*Tags:* `discoveryresources`

#### Input Parameters
* `platform` - _optional_ - The platform to use for the query. Alias 'client'.
    Possible values: c4, ps3, yv, ios, fm, p06, ctv, freesat, android, samsung.
* `category` - _required_ - The name of the category for which you seek associated Channel 4 programmes. (For a full list of categories, please see http://api.channel4.com/pmlsd/categories.atom?apikey=xxxxxxxxxxxxxxxxxxxxxxxx)

### 4oD Programmes by Title(4)

> Lists all Channel 4oD programmes associated with the specified category <br/>
>   (tag), alphanumerically in order of Title.<br/>
> <br/>
>   http://api.channel4.com/pmlsd/categories/category/4od/title/page-{pageno}.atom?apikey=xxxxxxxxxxxxxxxxxxxxxxxx<br/>
> <br/>
>   http://api.channel4.com/pmlsd/categories/religion-and-belief/4oD/title.atom?apikey=xxxxxxxxxxxxxxxxxxxxxxxx

*Tags:* `discoveryresources`

#### Input Parameters
* `platform` - _optional_ - The platform to use for the query. Alias 'client'.
    Possible values: c4, ps3, yv, ios, fm, p06, ctv, freesat, android, samsung.
* `category` - _required_ - The name of the category for which you seek associated Channel 4 programmes. (For a full list of categories, please see http://api.channel4.com/pmlsd/categories.atom?apikey=xxxxxxxxxxxxxxxxxxxxxxxx)
* `pageno` - _required_ - Page number of results to return

### All Programmes by TX Date(2)

> Lists all Channel 4 programmes associated with the specified category (tag).  <br/>
>   By default, the programmes are listed in order of Transmission (TX) Date, <br/>
>   with the most-recently-transmitted programmes listed first.<br/>
> <br/>
>   http://api.channel4.com/pmlsd/categories/category/channel/[channel].atom?apikey=xxxxxxxxxxxxxxxxxxxxxxxx<br/>
> <br/>
>   http://api.channel4.com/pmlsd/categories/animals.atom?apikey=xxxxxxxxxxxxxxxxxxxxxxxx

*Tags:* `discoveryresources`

#### Input Parameters
* `platform` - _optional_ - The platform to use for the query. Alias 'client'.
    Possible values: c4, ps3, yv, ios, fm, p06, ctv, freesat, android, samsung.
* `category` - _required_ - The name of the category for which you seek associated Channel 4 programmes. (For a full list of categories, please see http://api.channel4.com/pmlsd/categories.atom?apikey=xxxxxxxxxxxxxxxxxxxxxxxx)
* `channel` - _required_ - The name of the channel for which you seek associated Channel 4oD programmes
    Possible values: c4, f4, e4, m4, 4m, 4s.

### 4oD Programmes by TX Date(2)

> Lists all Channel 4oD programmes associated with the specified category <br/>
>   (tag).By default, the programmes are listed in order of Transmission (TX) <br/>
>   Date, with the most-recently-transmitted programmes listed first.<br/>
> <br/>
>   http://api.channel4.com/pmlsd/categories/category/channel/[channel]/4od.atom?apikey=xxxxxxxxxxxxxxxxxxxxxxxx<br/>
> <br/>
>   http://api.channel4.com/pmlsd/categories/animals/4oD.atom?apikey=xxxxxxxxxxxxxxxxxxxxxxxx

*Tags:* `discoveryresources`

#### Input Parameters
* `platform` - _optional_ - The platform to use for the query. Alias 'client'.
    Possible values: c4, ps3, yv, ios, fm, p06, ctv, freesat, android, samsung.
* `category` - _required_ - The name of the category for which you seek associated Channel 4 programmes. (For a full list of categories, please see http://api.channel4.com/pmlsd/categories.atom?apikey=xxxxxxxxxxxxxxxxxxxxxxxx)
* `channel` - _required_ - The name of the channel for which you seek associated Channel 4oD programmes
    Possible values: c4, f4, e4, m4, 4m, 4s.

### 4oD Programmes by TX Date(5)

> Lists all Channel 4oD programmes associated with the specified category <br/>
>   (tag).By default, the programmes are listed in order of Transmission (TX) <br/>
>   Date, with the most-recently-transmitted programmes listed first.<br/>
> <br/>
>   http://api.channel4.com/pmlsd/categories/category/channel/[channel]/4od/page-{pageno}.atom?apikey=xxxxxxxxxxxxxxxxxxxxxxxx<br/>
> <br/>
>   http://api.channel4.com/pmlsd/categories/animals/4oD.atom?apikey=xxxxxxxxxxxxxxxxxxxxxxxx

*Tags:* `discoveryresources`

#### Input Parameters
* `platform` - _optional_ - The platform to use for the query. Alias 'client'.
    Possible values: c4, ps3, yv, ios, fm, p06, ctv, freesat, android, samsung.
* `category` - _required_ - The name of the category for which you seek associated Channel 4 programmes. (For a full list of categories, please see http://api.channel4.com/pmlsd/categories.atom?apikey=xxxxxxxxxxxxxxxxxxxxxxxx)
* `channel` - _required_ - The name of the channel for which you seek associated Channel 4oD programmes
    Possible values: c4, f4, e4, m4, 4m, 4s.
* `pageno` - _required_ - Page number of results to return

### Most Popular Brands Feed(3)

> Lists all Channel 4oD most popular brands for the given category within the <br/>
>   last 7 days, in order of popularity.<br/>
> <br/>
>   http://api.channel4.com/pmlsd/categories/category/channel/[channel]/4od/popular.atom?apikey=xxxxxxxxxxxxxxxxxxxxxxxx<br/>
> <br/>
>   http://api.channel4.com/pmlsd/categories/comedy/4od/popular.atom?apikey=xxxxxxxxxxxxxxxxxxxxxxxx

*Tags:* `discoveryresources`

#### Input Parameters
* `platform` - _optional_ - The platform to use for the query. Alias 'client'.
    Possible values: c4, ps3, yv, ios, fm, p06, ctv, freesat, android, samsung.
* `category` - _required_ - The name of the category for which you seek associated Channel 4 programmes. (For a full list of categories, please see http://api.channel4.com/pmlsd/categories.atom?apikey=xxxxxxxxxxxxxxxxxxxxxxxx)
* `channel` - _required_ - The name of the channel for which you seek associated Channel 4oD programmes
    Possible values: c4, f4, e4, m4, 4m, 4s.

### Most Popular Brands Feed(7)

> Lists all Channel 4oD most popular brands for the given category within the <br/>
>   last 7 days, in order of popularity.<br/>
> <br/>
>   http://api.channel4.com/pmlsd/categories/category/channel/[channel]/4od/popular/page-{pageno}.atom?apikey=xxxxxxxxxxxxxxxxxxxxxxxx<br/>
> <br/>
>   http://api.channel4.com/pmlsd/categories/comedy/4od/popular.atom?apikey=xxxxxxxxxxxxxxxxxxxxxxxx

*Tags:* `discoveryresources`

#### Input Parameters
* `platform` - _optional_ - The platform to use for the query. Alias 'client'.
    Possible values: c4, ps3, yv, ios, fm, p06, ctv, freesat, android, samsung.
* `category` - _required_ - The name of the category for which you seek associated Channel 4 programmes. (For a full list of categories, please see http://api.channel4.com/pmlsd/categories.atom?apikey=xxxxxxxxxxxxxxxxxxxxxxxx)
* `channel` - _required_ - The name of the channel for which you seek associated Channel 4oD programmes
    Possible values: c4, f4, e4, m4, 4m, 4s.
* `pageno` - _required_ - Page number of results to return

### 4oD Programmes by Title(2)

> Lists all Channel 4oD programmes associated with the specified category <br/>
>   (tag), alphanumerically in order of Title.<br/>
> <br/>
>   http://api.channel4.com/pmlsd/categories/category/channel/[channel]/4od/title.atom?apikey=xxxxxxxxxxxxxxxxxxxxxxxx<br/>
> <br/>
>   http://api.channel4.com/pmlsd/categories/religion-and-belief/4oD/title.atom?apikey=xxxxxxxxxxxxxxxxxxxxxxxx

*Tags:* `discoveryresources`

#### Input Parameters
* `platform` - _optional_ - The platform to use for the query. Alias 'client'.
    Possible values: c4, ps3, yv, ios, fm, p06, ctv, freesat, android, samsung.
* `category` - _required_ - The name of the category for which you seek associated Channel 4 programmes. (For a full list of categories, please see http://api.channel4.com/pmlsd/categories.atom?apikey=xxxxxxxxxxxxxxxxxxxxxxxx)
* `channel` - _required_ - The name of the channel for which you seek associated Channel 4oD programmes
    Possible values: c4, f4, e4, m4, 4m, 4s.

### 4oD Programmes by Title(5)

> Lists all Channel 4oD programmes associated with the specified category <br/>
>   (tag), alphanumerically in order of Title.<br/>
> <br/>
>   http://api.channel4.com/pmlsd/categories/category/channel/[channel]/4od/title/page-{pageno}.atom?apikey=xxxxxxxxxxxxxxxxxxxxxxxx<br/>
> <br/>
>   http://api.channel4.com/pmlsd/categories/religion-and-belief/4oD/title.atom?apikey=xxxxxxxxxxxxxxxxxxxxxxxx

*Tags:* `discoveryresources`

#### Input Parameters
* `platform` - _optional_ - The platform to use for the query. Alias 'client'.
    Possible values: c4, ps3, yv, ios, fm, p06, ctv, freesat, android, samsung.
* `category` - _required_ - The name of the category for which you seek associated Channel 4 programmes. (For a full list of categories, please see http://api.channel4.com/pmlsd/categories.atom?apikey=xxxxxxxxxxxxxxxxxxxxxxxx)
* `channel` - _required_ - The name of the channel for which you seek associated Channel 4oD programmes
    Possible values: c4, f4, e4, m4, 4m, 4s.
* `pageno` - _required_ - Page number of results to return

### All Programmes by TX Date(5)

> Lists all Channel 4 programmes associated with the specified category (tag).  <br/>
>   By default, the programmes are listed in order of Transmission (TX) Date, <br/>
>   with the most-recently-transmitted programmes listed first.<br/>
> <br/>
>   http://api.channel4.com/pmlsd/categories/category/channel/[channel]/page-{pageno}.atom?apikey=xxxxxxxxxxxxxxxxxxxxxxxx<br/>
> <br/>
>   http://api.channel4.com/pmlsd/categories/animals.atom?apikey=xxxxxxxxxxxxxxxxxxxxxxxx

*Tags:* `discoveryresources`

#### Input Parameters
* `platform` - _optional_ - The platform to use for the query. Alias 'client'.
    Possible values: c4, ps3, yv, ios, fm, p06, ctv, freesat, android, samsung.
* `category` - _required_ - The name of the category for which you seek associated Channel 4 programmes. (For a full list of categories, please see http://api.channel4.com/pmlsd/categories.atom?apikey=xxxxxxxxxxxxxxxxxxxxxxxx)
* `channel` - _required_ - The name of the channel for which you seek associated Channel 4oD programmes
    Possible values: c4, f4, e4, m4, 4m, 4s.
* `pageno` - _required_ - Page number of results to return

### All Programmes by Title(2)

> Lists all Channel 4 programmes associated with the specified category (tag), <br/>
>   alphanumerically in order of Title.<br/>
> <br/>
>   http://api.channel4.com/pmlsd/categories/category/channel/[channel]/title.atom?apikey=xxxxxxxxxxxxxxxxxxxxxxxx<br/>
> <br/>
>   http://api.channel4.com/pmlsd/categories/history/title.atom?apikey=xxxxxxxxxxxxxxxxxxxxxxxx

*Tags:* `discoveryresources`

#### Input Parameters
* `platform` - _optional_ - The platform to use for the query. Alias 'client'.
    Possible values: c4, ps3, yv, ios, fm, p06, ctv, freesat, android, samsung.
* `category` - _required_ - The name of the category for which you seek associated Channel 4 programmes. (For a full list of categories, please see http://api.channel4.com/pmlsd/categories.atom?apikey=xxxxxxxxxxxxxxxxxxxxxxxx)
* `channel` - _required_ - The name of the channel for which you seek associated Channel 4oD programmes
    Possible values: c4, f4, e4, m4, 4m, 4s.

### All Programmes by Title(5)

> Lists all Channel 4 programmes associated with the specified category (tag), <br/>
>   alphanumerically in order of Title.<br/>
> <br/>
>   http://api.channel4.com/pmlsd/categories/category/channel/[channel]/title/page-{pageno}.atom?apikey=xxxxxxxxxxxxxxxxxxxxxxxx<br/>
> <br/>
>   http://api.channel4.com/pmlsd/categories/history/title.atom?apikey=xxxxxxxxxxxxxxxxxxxxxxxx

*Tags:* `discoveryresources`

#### Input Parameters
* `platform` - _optional_ - The platform to use for the query. Alias 'client'.
    Possible values: c4, ps3, yv, ios, fm, p06, ctv, freesat, android, samsung.
* `category` - _required_ - The name of the category for which you seek associated Channel 4 programmes. (For a full list of categories, please see http://api.channel4.com/pmlsd/categories.atom?apikey=xxxxxxxxxxxxxxxxxxxxxxxx)
* `channel` - _required_ - The name of the channel for which you seek associated Channel 4oD programmes
    Possible values: c4, f4, e4, m4, 4m, 4s.
* `pageno` - _required_ - Page number of results to return

### All Programmes by TX Date(3)

> Lists all Channel 4 programmes associated with the specified category (tag).  <br/>
>   By default, the programmes are listed in order of Transmission (TX) Date, <br/>
>   with the most-recently-transmitted programmes listed first.<br/>
> <br/>
>   http://api.channel4.com/pmlsd/categories/category/derived/ad.atom?apikey=xxxxxxxxxxxxxxxxxxxxxxxx<br/>
> <br/>
>   http://api.channel4.com/pmlsd/categories/animals.atom?apikey=xxxxxxxxxxxxxxxxxxxxxxxx

*Tags:* `discoveryresources`

#### Input Parameters
* `platform` - _optional_ - The platform to use for the query. Alias 'client'.
    Possible values: c4, ps3, yv, ios, fm, p06, ctv, freesat, android, samsung.
* `category` - _required_ - The name of the category for which you seek associated Channel 4 programmes. (For a full list of categories, please see http://api.channel4.com/pmlsd/categories.atom?apikey=xxxxxxxxxxxxxxxxxxxxxxxx)

### 4oD Programmes by TX Date(3)

> Lists all Channel 4oD programmes associated with the specified category <br/>
>   (tag).By default, the programmes are listed in order of Transmission (TX) <br/>
>   Date, with the most-recently-transmitted programmes listed first.<br/>
> <br/>
>   http://api.channel4.com/pmlsd/categories/category/derived/ad/4od.atom?apikey=xxxxxxxxxxxxxxxxxxxxxxxx<br/>
> <br/>
>   http://api.channel4.com/pmlsd/categories/animals/4oD.atom?apikey=xxxxxxxxxxxxxxxxxxxxxxxx

*Tags:* `discoveryresources`

#### Input Parameters
* `platform` - _optional_ - The platform to use for the query. Alias 'client'.
    Possible values: c4, ps3, yv, ios, fm, p06, ctv, freesat, android, samsung.
* `category` - _required_ - The name of the category for which you seek associated Channel 4 programmes. (For a full list of categories, please see http://api.channel4.com/pmlsd/categories.atom?apikey=xxxxxxxxxxxxxxxxxxxxxxxx)

### 4oD Programmes by TX Date(6)

> Lists all Channel 4oD programmes associated with the specified category <br/>
>   (tag).By default, the programmes are listed in order of Transmission (TX) <br/>
>   Date, with the most-recently-transmitted programmes listed first.<br/>
> <br/>
>   http://api.channel4.com/pmlsd/categories/category/derived/ad/4od/page-{pageno}.atom?apikey=xxxxxxxxxxxxxxxxxxxxxxxx<br/>
> <br/>
>   http://api.channel4.com/pmlsd/categories/animals/4oD.atom?apikey=xxxxxxxxxxxxxxxxxxxxxxxx

*Tags:* `discoveryresources`

#### Input Parameters
* `platform` - _optional_ - The platform to use for the query. Alias 'client'.
    Possible values: c4, ps3, yv, ios, fm, p06, ctv, freesat, android, samsung.
* `category` - _required_ - The name of the category for which you seek associated Channel 4 programmes. (For a full list of categories, please see http://api.channel4.com/pmlsd/categories.atom?apikey=xxxxxxxxxxxxxxxxxxxxxxxx)
* `pageno` - _required_ - Page number of results to return

### Most Popular Brands Feed(4)

> Lists all Channel 4oD most popular brands for the given category within the <br/>
>   last 7 days, in order of popularity.<br/>
> <br/>
>   http://api.channel4.com/pmlsd/categories/category/derived/ad/4od/popular.atom?apikey=xxxxxxxxxxxxxxxxxxxxxxxx<br/>
> <br/>
>   http://api.channel4.com/pmlsd/categories/comedy/4od/popular.atom?apikey=xxxxxxxxxxxxxxxxxxxxxxxx

*Tags:* `discoveryresources`

#### Input Parameters
* `platform` - _optional_ - The platform to use for the query. Alias 'client'.
    Possible values: c4, ps3, yv, ios, fm, p06, ctv, freesat, android, samsung.
* `category` - _required_ - The name of the category for which you seek associated Channel 4 programmes. (For a full list of categories, please see http://api.channel4.com/pmlsd/categories.atom?apikey=xxxxxxxxxxxxxxxxxxxxxxxx)

### Most Popular Brands Feed(8)

> Lists all Channel 4oD most popular brands for the given category within the <br/>
>   last 7 days, in order of popularity.<br/>
> <br/>
>   http://api.channel4.com/pmlsd/categories/category/derived/ad/4od/popular/page-{pageno}.atom?apikey=xxxxxxxxxxxxxxxxxxxxxxxx<br/>
> <br/>
>   http://api.channel4.com/pmlsd/categories/comedy/4od/popular.atom?apikey=xxxxxxxxxxxxxxxxxxxxxxxx

*Tags:* `discoveryresources`

#### Input Parameters
* `platform` - _optional_ - The platform to use for the query. Alias 'client'.
    Possible values: c4, ps3, yv, ios, fm, p06, ctv, freesat, android, samsung.
* `category` - _required_ - The name of the category for which you seek associated Channel 4 programmes. (For a full list of categories, please see http://api.channel4.com/pmlsd/categories.atom?apikey=xxxxxxxxxxxxxxxxxxxxxxxx)
* `pageno` - _required_ - Page number of results to return

### 4oD Programmes by Title(3)

> Lists all Channel 4oD programmes associated with the specified category <br/>
>   (tag), alphanumerically in order of Title.<br/>
> <br/>
>   http://api.channel4.com/pmlsd/categories/category/derived/ad/4od/title.atom?apikey=xxxxxxxxxxxxxxxxxxxxxxxx<br/>
> <br/>
>   http://api.channel4.com/pmlsd/categories/religion-and-belief/4oD/title.atom?apikey=xxxxxxxxxxxxxxxxxxxxxxxx

*Tags:* `discoveryresources`

#### Input Parameters
* `platform` - _optional_ - The platform to use for the query. Alias 'client'.
    Possible values: c4, ps3, yv, ios, fm, p06, ctv, freesat, android, samsung.
* `category` - _required_ - The name of the category for which you seek associated Channel 4 programmes. (For a full list of categories, please see http://api.channel4.com/pmlsd/categories.atom?apikey=xxxxxxxxxxxxxxxxxxxxxxxx)

### 4oD Programmes by Title(6)

> Lists all Channel 4oD programmes associated with the specified category <br/>
>   (tag), alphanumerically in order of Title.<br/>
> <br/>
>   http://api.channel4.com/pmlsd/categories/category/derived/ad/4od/title/page-{pageno}.atom?apikey=xxxxxxxxxxxxxxxxxxxxxxxx<br/>
> <br/>
>   http://api.channel4.com/pmlsd/categories/religion-and-belief/4oD/title.atom?apikey=xxxxxxxxxxxxxxxxxxxxxxxx

*Tags:* `discoveryresources`

#### Input Parameters
* `platform` - _optional_ - The platform to use for the query. Alias 'client'.
    Possible values: c4, ps3, yv, ios, fm, p06, ctv, freesat, android, samsung.
* `category` - _required_ - The name of the category for which you seek associated Channel 4 programmes. (For a full list of categories, please see http://api.channel4.com/pmlsd/categories.atom?apikey=xxxxxxxxxxxxxxxxxxxxxxxx)
* `pageno` - _required_ - Page number of results to return

### All Programmes by TX Date(6)

> Lists all Channel 4 programmes associated with the specified category (tag).  <br/>
>   By default, the programmes are listed in order of Transmission (TX) Date, <br/>
>   with the most-recently-transmitted programmes listed first.<br/>
> <br/>
>   http://api.channel4.com/pmlsd/categories/category/derived/ad/page-{pageno}.atom?apikey=xxxxxxxxxxxxxxxxxxxxxxxx<br/>
> <br/>
>   http://api.channel4.com/pmlsd/categories/animals.atom?apikey=xxxxxxxxxxxxxxxxxxxxxxxx

*Tags:* `discoveryresources`

#### Input Parameters
* `platform` - _optional_ - The platform to use for the query. Alias 'client'.
    Possible values: c4, ps3, yv, ios, fm, p06, ctv, freesat, android, samsung.
* `category` - _required_ - The name of the category for which you seek associated Channel 4 programmes. (For a full list of categories, please see http://api.channel4.com/pmlsd/categories.atom?apikey=xxxxxxxxxxxxxxxxxxxxxxxx)
* `pageno` - _required_ - Page number of results to return

### All Programmes by Title(3)

> Lists all Channel 4 programmes associated with the specified category (tag), <br/>
>   alphanumerically in order of Title.<br/>
> <br/>
>   http://api.channel4.com/pmlsd/categories/category/derived/ad/title.atom?apikey=xxxxxxxxxxxxxxxxxxxxxxxx<br/>
> <br/>
>   http://api.channel4.com/pmlsd/categories/history/title.atom?apikey=xxxxxxxxxxxxxxxxxxxxxxxx

*Tags:* `discoveryresources`

#### Input Parameters
* `platform` - _optional_ - The platform to use for the query. Alias 'client'.
    Possible values: c4, ps3, yv, ios, fm, p06, ctv, freesat, android, samsung.
* `category` - _required_ - The name of the category for which you seek associated Channel 4 programmes. (For a full list of categories, please see http://api.channel4.com/pmlsd/categories.atom?apikey=xxxxxxxxxxxxxxxxxxxxxxxx)

### All Programmes by Title(6)

> Lists all Channel 4 programmes associated with the specified category (tag), <br/>
>   alphanumerically in order of Title.<br/>
> <br/>
>   http://api.channel4.com/pmlsd/categories/category/derived/ad/title/page-{pageno}.atom?apikey=xxxxxxxxxxxxxxxxxxxxxxxx<br/>
> <br/>
>   http://api.channel4.com/pmlsd/categories/history/title.atom?apikey=xxxxxxxxxxxxxxxxxxxxxxxx

*Tags:* `discoveryresources`

#### Input Parameters
* `platform` - _optional_ - The platform to use for the query. Alias 'client'.
    Possible values: c4, ps3, yv, ios, fm, p06, ctv, freesat, android, samsung.
* `category` - _required_ - The name of the category for which you seek associated Channel 4 programmes. (For a full list of categories, please see http://api.channel4.com/pmlsd/categories.atom?apikey=xxxxxxxxxxxxxxxxxxxxxxxx)
* `pageno` - _required_ - Page number of results to return

### All Programmes by TX Date(4)

> Lists all Channel 4 programmes associated with the specified category (tag).  <br/>
>   By default, the programmes are listed in order of Transmission (TX) Date, <br/>
>   with the most-recently-transmitted programmes listed first.<br/>
> <br/>
>   http://api.channel4.com/pmlsd/categories/category/page-{pageno}.atom?apikey=xxxxxxxxxxxxxxxxxxxxxxxx<br/>
> <br/>
>   http://api.channel4.com/pmlsd/categories/animals.atom?apikey=xxxxxxxxxxxxxxxxxxxxxxxx

*Tags:* `discoveryresources`

#### Input Parameters
* `platform` - _optional_ - The platform to use for the query. Alias 'client'.
    Possible values: c4, ps3, yv, ios, fm, p06, ctv, freesat, android, samsung.
* `category` - _required_ - The name of the category for which you seek associated Channel 4 programmes. (For a full list of categories, please see http://api.channel4.com/pmlsd/categories.atom?apikey=xxxxxxxxxxxxxxxxxxxxxxxx)
* `pageno` - _required_ - Page number of results to return

### Most Popular Brands Feed(2)

> Lists all Channel 4oD most popular brands for the given category within the <br/>
>   last 7 days, in order of popularity.<br/>
> <br/>
>   http://api.channel4.com/pmlsd/categories/category/popular.atom?apikey=xxxxxxxxxxxxxxxxxxxxxxxx<br/>
> <br/>
>   http://api.channel4.com/pmlsd/categories/comedy/4od/popular.atom?apikey=xxxxxxxxxxxxxxxxxxxxxxxx

*Tags:* `discoveryresources`

#### Input Parameters
* `platform` - _optional_ - The platform to use for the query. Alias 'client'.
    Possible values: c4, ps3, yv, ios, fm, p06, ctv, freesat, android, samsung.
* `category` - _required_ - The name of the category for which you seek associated Channel 4 programmes. (For a full list of categories, please see http://api.channel4.com/pmlsd/categories.atom?apikey=xxxxxxxxxxxxxxxxxxxxxxxx)

### Most Popular Brands Feed(6)

> Lists all Channel 4oD most popular brands for the given category within the <br/>
>   last 7 days, in order of popularity.<br/>
> <br/>
>   http://api.channel4.com/pmlsd/categories/category/popular/page-{pageno}.atom?apikey=xxxxxxxxxxxxxxxxxxxxxxxx<br/>
> <br/>
>   http://api.channel4.com/pmlsd/categories/comedy/4od/popular.atom?apikey=xxxxxxxxxxxxxxxxxxxxxxxx

*Tags:* `discoveryresources`

#### Input Parameters
* `platform` - _optional_ - The platform to use for the query. Alias 'client'.
    Possible values: c4, ps3, yv, ios, fm, p06, ctv, freesat, android, samsung.
* `category` - _required_ - The name of the category for which you seek associated Channel 4 programmes. (For a full list of categories, please see http://api.channel4.com/pmlsd/categories.atom?apikey=xxxxxxxxxxxxxxxxxxxxxxxx)
* `pageno` - _required_ - Page number of results to return

### All Programmes by Title

> Lists all Channel 4 programmes associated with the specified category (tag), <br/>
>   alphanumerically in order of Title.<br/>
> <br/>
>   http://api.channel4.com/pmlsd/categories/category/title.atom?apikey=xxxxxxxxxxxxxxxxxxxxxxxx<br/>
> <br/>
>   http://api.channel4.com/pmlsd/categories/history/title.atom?apikey=xxxxxxxxxxxxxxxxxxxxxxxx

*Tags:* `discoveryresources`

#### Input Parameters
* `platform` - _optional_ - The platform to use for the query. Alias 'client'.
    Possible values: c4, ps3, yv, ios, fm, p06, ctv, freesat, android, samsung.
* `category` - _required_ - The name of the category for which you seek associated Channel 4 programmes. (For a full list of categories, please see http://api.channel4.com/pmlsd/categories.atom?apikey=xxxxxxxxxxxxxxxxxxxxxxxx)

### All Programmes by Title(4)

> Lists all Channel 4 programmes associated with the specified category (tag), <br/>
>   alphanumerically in order of Title.<br/>
> <br/>
>   http://api.channel4.com/pmlsd/categories/category/title/page-{pageno}.atom?apikey=xxxxxxxxxxxxxxxxxxxxxxxx<br/>
> <br/>
>   http://api.channel4.com/pmlsd/categories/history/title.atom?apikey=xxxxxxxxxxxxxxxxxxxxxxxx

*Tags:* `discoveryresources`

#### Input Parameters
* `platform` - _optional_ - The platform to use for the query. Alias 'client'.
    Possible values: c4, ps3, yv, ios, fm, p06, ctv, freesat, android, samsung.
* `category` - _required_ - The name of the category for which you seek associated Channel 4 programmes. (For a full list of categories, please see http://api.channel4.com/pmlsd/categories.atom?apikey=xxxxxxxxxxxxxxxxxxxxxxxx)
* `pageno` - _required_ - Page number of results to return

### Collections Feed(2)

> Collections are editorially controlled groups of brands, series, episodes or <br/>
>   other collections used for promotion and discovery of content. A SIMPLE <br/>
>   collection can contain an assortment of Brands, Series, Episodes or Freeform <br/>
>   items. A GROUP collection contains other collections.<br/>
> <br/>
>   http://api.channel4.com/pmlsd/collections/collection_name.atom?apikey=xxxxxxxxxxxxxxxxxxxxxxxx<br/>
> <br/>
>   http://api.channel4.com/pmlsd/collections/4od-home-promo/4od.atom?apikey=xxxxxxxxxxxxxxxxxxxxxxxx

*Tags:* `discoveryresources`

#### Input Parameters
* `platform` - _optional_ - The platform to use for the query. Alias 'client'.
    Possible values: c4, ps3, yv, ios, fm, p06, ctv, freesat, android, samsung.
* `collection_name` - _required_ - Web safe title for the collection.

### Collections Feed

> Collections are editorially controlled groups of brands, series, episodes or <br/>
>   other collections used for promotion and discovery of content. A SIMPLE <br/>
>   collection can contain an assortment of Brands, Series, Episodes or Freeform <br/>
>   items. A GROUP collection contains other collections.<br/>
> <br/>
>   http://api.channel4.com/pmlsd/collections/collection_name/4od.atom?apikey=xxxxxxxxxxxxxxxxxxxxxxxx<br/>
> <br/>
>   http://api.channel4.com/pmlsd/collections/4od-home-promo/4od.atom?apikey=xxxxxxxxxxxxxxxxxxxxxxxx

*Tags:* `discoveryresources`

#### Input Parameters
* `platform` - _optional_ - The platform to use for the query. Alias 'client'.
    Possible values: c4, ps3, yv, ios, fm, p06, ctv, freesat, android, samsung.
* `collection_name` - _required_ - Web safe title for the collection.

### Flattened Collection Feed(2)

> The Flattened Collections Feed is only applicable for GROUP collections and <br/>
>   its purpose is mainly return 3 items (BRAND, SERIES or EPSIODE) of each of <br/>
>   the simple collections assigned to the GROUP.<br/>
> <br/>
>   http://api.channel4.com/pmlsd/collections/collection_name/flattened.atom?apikey=xxxxxxxxxxxxxxxxxxxxxxxx<br/>
> <br/>
>   http://api.channel4.com/pmlsd/collections/4od-home-promo/flattened/4od.atom?apikey=xxxxxxxxxxxxxxxxxxxxxxxx

*Tags:* `discoveryresources`

#### Input Parameters
* `platform` - _optional_ - The platform to use for the query. Alias 'client'.
    Possible values: c4, ps3, yv, ios, fm, p06, ctv, freesat, android, samsung.
* `collection_name` - _required_ - Web safe title for the collection.

### Flattened Collection Feed

> The Flattened Collections Feed is only applicable for GROUP collections and <br/>
>   its purpose is mainly return 3 items (BRAND, SERIES or EPSIODE) of each of <br/>
>   the simple collections assigned to the GROUP.<br/>
> <br/>
>   http://api.channel4.com/pmlsd/collections/collection_name/flattened/4od.atom?apikey=xxxxxxxxxxxxxxxxxxxxxxxx<br/>
> <br/>
>   http://api.channel4.com/pmlsd/collections/4od-home-promo/flattened/4od.atom?apikey=xxxxxxxxxxxxxxxxxxxxxxxx

*Tags:* `discoveryresources`

#### Input Parameters
* `platform` - _optional_ - The platform to use for the query. Alias 'client'.
    Possible values: c4, ps3, yv, ios, fm, p06, ctv, freesat, android, samsung.
* `collection_name` - _required_ - Web safe title for the collection.

### Coming Soon feed

> Coming Soon feed display a list of episodes coming soon to linear TV so that <br/>
>   I can promote new Channel 4 content.<br/>
> <br/>
>   http://api.channel4.com/pmlsd/coming-soon.atom?apikey=xxxxxxxxxxxxxxxxxxxxxxxx<br/>
> <br/>
>   http://api.channel4.com/pmlsd/coming-soon.atom?apikey=xxxxxxxxxxxxxxxxxxxxxxxx

*Tags:* `metadataresources`

#### Input Parameters
* `platform` - _optional_ - The platform to use for the query. Alias 'client'.
    Possible values: c4, ps3, yv, ios, fm, p06, ctv, freesat, android, samsung.

### Coming Soon feed(2)

> Coming Soon feed display a list of episodes coming soon to linear TV so that <br/>
>   I can promote new Channel 4 content.<br/>
> <br/>
>   http://api.channel4.com/pmlsd/coming-soon/[category].atom?apikey=xxxxxxxxxxxxxxxxxxxxxxxx<br/>
> <br/>
>   http://api.channel4.com/pmlsd/coming-soon.atom?apikey=xxxxxxxxxxxxxxxxxxxxxxxx

*Tags:* `metadataresources`

#### Input Parameters
* `platform` - _optional_ - The platform to use for the query. Alias 'client'.
    Possible values: c4, ps3, yv, ios, fm, p06, ctv, freesat, android, samsung.
* `category` - _required_ - The category websafe_title to filter the coming soon programmes on TV.

### Programme Feed

> A feed containing all long-form content currently or previously available <br/>
>   for a specified Programme Id. The entries for the Programme feed contain <br/>
>   references to long-form assets for each platform.<br/>
> <br/>
>   http://api.channel4.com/pmlsd/programme/[programme-id].atom?apikey=xxxxxxxxxxxxxxxxxxxxxxxx<br/>
> <br/>
>   http://api.channel4.com/pmlsd/programme/33881-001/4od.atom?apikey=xxxxxxxxxxxxxxxxxxxxxxxx

*Tags:* `metadataresources`

#### Input Parameters
* `platform` - _optional_ - The platform to use for the query. Alias 'client'.
    Possible values: c4, ps3, yv, ios, fm, p06, ctv, freesat, android, samsung.
* `programme-id` - _required_ - The websafe programme identifier for the episode for which you seek on-demand content

### Search Feed

> Lists all Channel 4 programmes where title (brand name) matching the search <br/>
>   term. Matches are made from the beginning of individual words in the title.<br/>
> <br/>
>   http://api.channel4.com/pmlsd/search.atom?q=search-term&apikey=xxx<br/>
> <br/>
>   http://api.channel4.com/pmlsd/search.atom?q=the+it+crowd&apikey=xxxxxxxxxxxxxxxxxxxxxxxx

*Tags:* `discoveryresources`

#### Input Parameters
* `platform` - _optional_ - The platform to use for the query. Alias 'client'.
    Possible values: c4, ps3, yv, ios, fm, p06, ctv, freesat, android, samsung.
* `q` - _required_ - The programme name to look for, minimum length: 2 chars.Looking for programme names with special chars might be URL encoded.

### Search Feed(3)

> Lists all Channel 4 programmes where title (brand name) matching the search <br/>
>   term. Matches are made from the beginning of individual words in the title.<br/>
> <br/>
>   http://api.channel4.com/pmlsd/search/page-{pageno}.atom?q=search-term&apikey=xxx<br/>
> <br/>
>   http://api.channel4.com/pmlsd/search.atom?q=the+it+crowd&apikey=xxxxxxxxxxxxxxxxxxxxxxxx

*Tags:* `discoveryresources`

#### Input Parameters
* `platform` - _optional_ - The platform to use for the query. Alias 'client'.
    Possible values: c4, ps3, yv, ios, fm, p06, ctv, freesat, android, samsung.
* `q` - _required_ - The programme name to look for, minimum length: 2 chars.Looking for programme names with special chars might be URL encoded.
* `pageno` - _required_ - Page number of results to return

### Search Feed(2)

> Lists all Channel 4 programmes where title (brand name) matching the search <br/>
>   term. Matches are made from the beginning of individual words in the title.<br/>
> <br/>
>   http://api.channel4.com/pmlsd/search/search-term.atom?apikey=xxx<br/>
> <br/>
>   http://api.channel4.com/pmlsd/search.atom?q=the+it+crowd&apikey=xxxxxxxxxxxxxxxxxxxxxxxx

*Tags:* `discoveryresources`

#### Input Parameters
* `platform` - _optional_ - The platform to use for the query. Alias 'client'.
    Possible values: c4, ps3, yv, ios, fm, p06, ctv, freesat, android, samsung.
* `q` - _required_ - The programme name to look for, minimum length: 2 chars.Looking for programme names with special chars might be URL encoded.

### Search Feed(4)

> Lists all Channel 4 programmes where title (brand name) matching the search <br/>
>   term. Matches are made from the beginning of individual words in the title.<br/>
> <br/>
>   http://api.channel4.com/pmlsd/search/search-term/page-{pageno}.atom?apikey=xxx<br/>
> <br/>
>   http://api.channel4.com/pmlsd/search.atom?q=the+it+crowd&apikey=xxxxxxxxxxxxxxxxxxxxxxxx

*Tags:* `discoveryresources`

#### Input Parameters
* `platform` - _optional_ - The platform to use for the query. Alias 'client'.
    Possible values: c4, ps3, yv, ios, fm, p06, ctv, freesat, android, samsung.
* `q` - _required_ - The programme name to look for, minimum length: 2 chars.Looking for programme names with special chars might be URL encoded.
* `pageno` - _required_ - Page number of results to return

### TV Listings Feed

> EPG Information of daily broadcast content aired per channels, according to <br/>
>   broadcast date<br/>
> <br/>
>   http://api.channel4.com/pmlsd/tv-listings/daily/[yyyy]/[mm]/[dd].atom?apikey=xxxxxxxxxxxxxxxxxxxxxxxx<br/>
> <br/>
>   http://api.channel4.com/pmlsd/tv-listings/daily/2010/11/28.atom?apikey=xxxxxxxxxxxxxxxxxxxxxxxx

*Tags:* `discoveryresources`

#### Input Parameters
* `platform` - _optional_ - The platform to use for the query. Alias 'client'.
    Possible values: c4, ps3, yv, ios, fm, p06, ctv, freesat, android, samsung.
* `yyyy` - _required_ - The date for which you wish to see programming information. Note the schedule days start from 6am and run until 6am on the next calendar day.
* `mm` - _required_ - The date for which you wish to see programming information. Note the schedule days start from 6am and run until 6am on the next calendar day.
* `dd` - _required_ - The date for which you wish to see programming information. Note the schedule days start from 6am and run until 6am on the next calendar day.

### TV Listings Feed(2)

> EPG Information of daily broadcast content aired per channels, according to <br/>
>   broadcast date<br/>
> <br/>
>   http://api.channel4.com/pmlsd/tv-listings/daily/[yyyy]/[mm]/[dd]/[channel].atom?apikey=xxxxxxxxxxxxxxxxxxxxxxxx<br/>
> <br/>
>   http://api.channel4.com/pmlsd/tv-listings/daily/2010/11/28.atom?apikey=xxxxxxxxxxxxxxxxxxxxxxxx

*Tags:* `discoveryresources`

#### Input Parameters
* `platform` - _optional_ - The platform to use for the query. Alias 'client'.
    Possible values: c4, ps3, yv, ios, fm, p06, ctv, freesat, android, samsung.
* `yyyy` - _required_ - The date for which you wish to see programming information. Note the schedule days start from 6am and run until 6am on the next calendar day.
* `mm` - _required_ - The date for which you wish to see programming information. Note the schedule days start from 6am and run until 6am on the next calendar day.
* `dd` - _required_ - The date for which you wish to see programming information. Note the schedule days start from 6am and run until 6am on the next calendar day.
* `channel` - _required_ - The EPG for a specific channel (c4, e4, m4, 4m, f4, 4s)
    Possible values: c4, f4, e4, m4, 4m, 4s.

### Hub Feed

> The basis for all brand information<br/>
> <br/>
>   http://api.channel4.com/pmlsd/brand-web-safe-title.atom?apikey=xxxxxxxxxxxxxxxxxxxxxxxx<br/>
> <br/>
>   http://api.channel4.com/pmlsd/the-it-crowd.atom?apikey=xxxxxxxxxxxxxxxxxxxxxxxx

*Tags:* `metadataresources`

#### Input Parameters
* `platform` - _optional_ - The platform to use for the query. Alias 'client'.
    Possible values: c4, ps3, yv, ios, fm, p06, ctv, freesat, android, samsung.
* `brand-web-safe-title` - _required_ - The title of the programme for which you seek associated data

### 4oD Feed

> A feed containing all available on-demand long-form content for a specified <br/>
>   brand. The entries for the 4oD feed contain references to each long-form <br/>
>   asset for a brand, ordered by series number and episode number.<br/>
> <br/>
>   http://api.channel4.com/pmlsd/[brand-web-safe-title]/4od.atom?apikey=xxxxxxxxxxxxxxxxxxxxxxxx<br/>
> <br/>
>   http://api.channel4.com/pmlsd/the-it-crowd/4od.atom?apikey=xxxxxxxxxxxxxxxxxxxxxxxx

*Tags:* `metadataresources`

#### Input Parameters
* `platform` - _optional_ - The platform to use for the query. Alias 'client'.
    Possible values: c4, ps3, yv, ios, fm, p06, ctv, freesat, android, samsung.
* `brand-web-safe-title` - _required_ - The title of the programme for which you seek on-demand content

### Brand EPG Atom Feed

> This feed contains metadata about upcoming electronic programme guide (EPG) <br/>
>   information for a brand. The entry details upcoming transmission slots for <br/>
>   this brand.<br/>
> <br/>
>   http://api.channel4.com/pmlsd/brand-web-safe-title/epg.atom?apikey=xxxxxxxxxxxxxxxxxxxxxxxx<br/>
> <br/>
>   http://api.channel4.com/pmlsd/the-simpsons/epg.atom?apikey=xxxxxxxxxxxxxxxxxxxxxxxx

*Tags:* `metadataresources`

#### Input Parameters
* `platform` - _optional_ - The platform to use for the query. Alias 'client'.
    Possible values: c4, ps3, yv, ios, fm, p06, ctv, freesat, android, samsung.
* `brand-web-safe-title` - _required_ - Title of the programme for which you seek EPG information

### Episode Guide Feed Series Landing

> A feed containing metadata about all series for a specified brand. The <br/>
>   entries in this feed contain references to each of the series (where <br/>
>   metadata has been published), with some convenient links.<br/>
> <br/>
>   http://api.channel4.com/pmlsd/brand-web-safe-title/episode-guide.atom?apikey=xxxxxxxxxxxxxxxxxxxxxxxx<br/>
> <br/>
>   http://api.channel4.com/pmlsd/father-ted/episode-guide.atom?apikey=xxxxxxxxxxxxxxxxxxxxxxxx

*Tags:* `metadataresources`

#### Input Parameters
* `platform` - _optional_ - The platform to use for the query. Alias 'client'.
    Possible values: c4, ps3, yv, ios, fm, p06, ctv, freesat, android, samsung.
* `brand-web-safe-title` - _required_ - The title of the programme for which you seek episode-guide information

### Episode Guide Feed Series Detail

> A feed containing metadata about all the episodes for a specific series. The <br/>
>   entries in this feed contain references to each of the episodes (where <br/>
>   metadata has been published), with some convenient links.<br/>
> <br/>
>   http://api.channel4.com/pmlsd/brand-web-safe-title/episode-guide/series-series_number.atom?apikey=xxxxxxxxxxxxxxxxxxxxxxxx<br/>
> <br/>
>   http://api.channel4.com/pmlsd/chelmsford-123/episode-guide/series-1.atom?apikey=xxxxxxxxxxxxxxxxxxxxxxxx

*Tags:* `metadataresources`

#### Input Parameters
* `platform` - _optional_ - The platform to use for the query. Alias 'client'.
    Possible values: c4, ps3, yv, ios, fm, p06, ctv, freesat, android, samsung.
* `brand-web-safe-title` - _required_ - The title of the programme for which you seek series-related information
* `series_number` - _required_ - Unique enumerated identifier of the series within its brand

### Episode Guide Feed Episode Detail

> A feed containing metadata about a specified episode. (This feed does not <br/>
>   contain any entries and only contains a feed element regarding this <br/>
>   episode.)<br/>
> <br/>
>   http://api.channel4.com/pmlsd/brand-web-safe-title/episode-guide/series-series_number/episode-episode_number.atom?apikey=xxxxxxxxxxxxxxxxxxxxxxxx<br/>
> <br/>
>   http://api.channel4.com/pmlsd/the-it-crowd/episode-guide/series-1/episode-1.atom?apikey=xxxxxxxxxxxxxxxxxxxxxxxx

*Tags:* `metadataresources`

#### Input Parameters
* `platform` - _optional_ - The platform to use for the query. Alias 'client'.
    Possible values: c4, ps3, yv, ios, fm, p06, ctv, freesat, android, samsung.
* `brand-web-safe-title` - _required_ - Title of the brand to which the episode belongs
* `series_number` - _required_ - Unique enumerated identifier of the series within its brand to which the episode belongs
* `episode_number` - _required_ - Unique enumerated identifier of the episode within its series

### Clips Landing Feed Brand Series and Episode Levels

> A feed containing metadata about all the short-form (clip) videos. The clips <br/>
>   feed can be accessed at different levels: the content is then filtered <br/>
>   depending on the level, but the structure is identical.When accessed: from <br/>
>   the top, the feed contains all the clips for the brand;  at series level, <br/>
>   the feed contains only clips from the series; and  at episode level, the <br/>
>   feed contains only clips for the episode (and is very unlikely to require <br/>
>   pagination). The entries for the Clips Landing Feed contain references to <br/>
>   each short-form asset.<br/>
> <br/>
>   http://api.channel4.com/pmlsd/brand-web-safe-title/videos/all.atom?apikey=xxxxxxxxxxxxxxxxxxxxxxxx<br/>
> <br/>
>   http://api.channel4.com/pmlsd/peep-show/videos.atom?apikey=xxxxxxxxxxxxxxxxxxxxxxxx

*Tags:* `metadataresources`

#### Input Parameters
* `platform` - _optional_ - The platform to use for the query. Alias 'client'.
    Possible values: c4, ps3, yv, ios, fm, p06, ctv, freesat, android, samsung.
* `brand-web-safe-title` - _required_ - Title of brand to which clips belong

### Clips Landing Feed Brand Series and Episode Levels(2)

> A feed containing metadata about all the short-form (clip) videos. The clips <br/>
>   feed can be accessed at different levels: the content is then filtered <br/>
>   depending on the level, but the structure is identical.When accessed: from <br/>
>   the top, the feed contains all the clips for the brand;  at series level, <br/>
>   the feed contains only clips from the series; and  at episode level, the <br/>
>   feed contains only clips for the episode (and is very unlikely to require <br/>
>   pagination). The entries for the Clips Landing Feed contain references to <br/>
>   each short-form asset.<br/>
> <br/>
>   http://api.channel4.com/pmlsd/brand-web-safe-title/videos/series-series_number.atom?apikey=xxxxxxxxxxxxxxxxxxxxxxxx<br/>
> <br/>
>   http://api.channel4.com/pmlsd/peep-show/videos.atom?apikey=xxxxxxxxxxxxxxxxxxxxxxxx

*Tags:* `metadataresources`

#### Input Parameters
* `platform` - _optional_ - The platform to use for the query. Alias 'client'.
    Possible values: c4, ps3, yv, ios, fm, p06, ctv, freesat, android, samsung.
* `brand-web-safe-title` - _required_ - Title of brand to which clips belong
* `series_number` - _required_ - Unique identifier of series to which clips belong

### Clips Landing Feed Brand Series and Episode Levels(3)

> A feed containing metadata about all the short-form (clip) videos. The clips <br/>
>   feed can be accessed at different levels: the content is then filtered <br/>
>   depending on the level, but the structure is identical.When accessed: from <br/>
>   the top, the feed contains all the clips for the brand;  at series level, <br/>
>   the feed contains only clips from the series; and  at episode level, the <br/>
>   feed contains only clips for the episode (and is very unlikely to require <br/>
>   pagination). The entries for the Clips Landing Feed contain references to <br/>
>   each short-form asset.<br/>
> <br/>
>   http://api.channel4.com/pmlsd/brand-web-safe-title/videos/series-series_number/episode-episode_number.atom?apikey=xxxxxxxxxxxxxxxxxxxxxx<br/>
> <br/>
>   http://api.channel4.com/pmlsd/peep-show/videos.atom?apikey=xxxxxxxxxxxxxxxxxxxxxxxx

*Tags:* `metadataresources`

#### Input Parameters
* `platform` - _optional_ - The platform to use for the query. Alias 'client'.
    Possible values: c4, ps3, yv, ios, fm, p06, ctv, freesat, android, samsung.
* `brand-web-safe-title` - _required_ - Title of brand to which clips belong
* `series_number` - _required_ - Unique identifier of series to which clips belong
* `episode_number` - _required_ - Unique identifier of episode to which clips belong

### Clip Detail Atom Feed

> A feed containing metadata about a single short-form video (clip).<br/>
> <br/>
>   http://api.channel4.com/pmlsd/brand-web-safe-title/videos/clip-asset-id.atom?apikey=xxxxxxxxxxxxxxxxxxxxxxxx<br/>
> <br/>
>   http://api.channel4.com/pmlsd/the-it-crowd/videos/TCGS_CLIP_0000001015.atom?apikey=xxxxxxxxxxxxxxxxxxxxxxxx

*Tags:* `metadataresources`

#### Input Parameters
* `platform` - _optional_ - The platform to use for the query. Alias 'client'.
    Possible values: c4, ps3, yv, ios, fm, p06, ctv, freesat, android, samsung.
* `brand-web-safe-title` - _required_ - Title of the brand for which you seek a clip
* `clip-asset-id` - _required_ - Asset id for this clip

## License

**flow**ground :- Telekom iPaaS / channel-4-com-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
