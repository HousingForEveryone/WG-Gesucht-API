# WG-Gesucht-API
Unofficial API documentation for WG-Gesucht.de

## Offers
Endpoint: `https://www.wg-gesucht.de/api/asset/offers/`
Method: `GET`

### Headers
Host: `www.wg-gesucht.de`
Connection: `keep-alive`
Access-Control-Request-Method: `GET`
Access-Control-Request-Headers: `content-type,x-app-version,x-client-id`
Origin: `file://`
Sec-Fetch-Site: `cross-site`
User-Agent: `Mozilla/5.0`
Accept-Encoding: `gzip, deflate`
Accept-Language: `en-GB,en-US;q=0.9,en;q=0.8`

### Parameters
ad_type: 0
bal
category: 0
city_id: 8
dFr
dTo
dFrDe
dToDe
ot
wgFla
ff
wgArt
fur
kit
gar
han
noDeact: 1
img_only
img: 1
limit: 20
wgMxT
rMax
rmMax
wgMnF
rmMin
sMin
wgAge
wgSea
exc
sin
pet
radAdd
radDist
radLat
radLng
rent_type: 0
wgSmo
sort_order
sort_column
exContAds
page: 1

### Response
```js
{
  filter_items: {
    category: '0',
    city_id: '8',
    rent_type: '0',
    page: 1,
    limit: 20,
    noDeact: '1',
    img: '1'
  },
  total_items: '3411',
  page_number: '1',
  number_of_pages: '171',
  _links: {
    self: {
      href: 'https://www.wg-gesucht.de/api/asset/offers/?ad_type=0&bal=&category=0&city_id=8&dFr=&dFrDe=&dTo=&dToDe=&exContAds=&exc=&ff=&fur=&gar=&han=&img=1&img_only=&kit=&limit=20&noDeact=1&ot=&page=1&pet=&rMax=&radAdd=&radDist=&radLat=&radLng=&rent_type=0&rmMax=&rmMin=&sMin=&sin=&sort_column=&sort_order=&wgAge=&wgArt=&wgFla=&wgMnF=&wgMxT=&wgSea=&wgSmo='
    },
    next: {
      href: 'https://www.wg-gesucht.de/api/asset/offers/?ad_type=0&bal=&category=0&city_id=8&dFr=&dFrDe=&dTo=&dToDe=&exContAds=&exc=&ff=&fur=&gar=&han=&img=1&img_only=&kit=&limit=20&noDeact=1&ot=&page=2&pet=&rMax=&radAdd=&radDist=&radLat=&radLng=&rent_type=0&rmMax=&rmMin=&sMin=&sin=&sort_column=&sort_order=&wgAge=&wgArt=&wgFla=&wgMnF=&wgMxT=&wgSea=&wgSmo='
    },
    last: {
      href: 'https://www.wg-gesucht.de/api/asset/offers/?ad_type=0&bal=&category=0&city_id=8&dFr=&dFrDe=&dTo=&dToDe=&exContAds=&exc=&ff=&fur=&gar=&han=&img=1&img_only=&kit=&limit=20&noDeact=1&ot=&page=171&pet=&rMax=&radAdd=&radDist=&radLat=&radLng=&rent_type=0&rmMax=&rmMin=&sMin=&sin=&sort_column=&sort_order=&wgAge=&wgArt=&wgFla=&wgMnF=&wgMxT=&wgSea=&wgSmo='
    }
  },
  _embedded: {
    offers: [
        `Offers`
    ]
  }
}
```

#### Offers
```json
{
    "offer_id": "7805728",
    "category": "0",
    "total_costs": "700",
    "duration": "183",
    "available_from_date": "1583017200",
    "available_to_date": "1598824800",
    "date_edited": "1580889833",
    "date_of_entry": "05.02.20",
    "date_of_entry_details": "05.02.2020, 09:03:53",
    "offer_title": "Großes möbliertes Zimmer zur Zwischenmiete - Zeitraum flexibel (ggf. Wohnungsübernahme)",
    "user_id": "5816",
    "city_id": "8",
    "rent_type": "1",
    "property_size": "25",
    "number_of_rooms": "0",
    "street": "Karl-Marx-Straße",
    "district_custom": "Berlin - Neukölln",
    "offer_in_exchange": "0",
    "deactivated": "0",
    "geo_latitude": "52.470691",
    "geo_longitude": "13.441450",
    "first_name": "",
    "last_name": "",
    "flatshare_inhabitants_total": "2",
    "flatshare_males": "0",
    "flatshare_females": "1",
    "flatshare_divers": "0",
    "searched_for_gender": "1",
    "thumb": "media/up/2020/03/020d6da51d584cf8f8d3176452928b3243735d41aab14e19c4e88004b1e1e7fc_PHOTO_2020_01_14_13_01_53_3.thumb.jpg",
    "sized": "media/up/2020/03/020d6da51d584cf8f8d3176452928b3243735d41aab14e19c4e88004b1e1e7fc_PHOTO_2020_01_14_13_01_53_3.sized.jpg",
    "small": "media/up/2020/03/020d6da51d584cf8f8d3176452928b3243735d41aab14e19c4e88004b1e1e7fc_PHOTO_2020_01_14_13_01_53_3.small.jpg",
    "image_deleted": "0",
    "image_description": "",
    "town_name": "Berlin",
    "verified_user": "0",
    "verified_user_profile_image": ""
}
```