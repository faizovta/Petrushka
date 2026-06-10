# Rest API запрос
### Request
```markdown
GET/api/v1/partners?lat=53.199895&lon=50.1538&include=shipping_options%2Cpartners_count%2Cnearest_partners%2Сshipping_options&start_time&order=desc
```
### Response



```markdown
[    
	   {  
        "id": 7,
        "uuid": "9d54c27b-9b04-459e-a301-8167983be07b",
        "name": "METRO",
        "slug": "metro",
        "partners_count": 2,
        "appearance": {
            "image_color": "#0f447c",
            "logo_image": "https://static.petrushka.ru/statics/partners-appearances/0830b712-08a8-4fe9-b2bb-962f284c0c58-metro.png",
            "mini_logo_image": "https://static.petrushka.ru/statics/partners-appearances/e4b85199-a27f-4b09-9396-351340ca8da5-Metro.png",
            "external_link": "https://metro-cc.ru?utm_source=petrushka&nearest_partners_id=12"
        },
        "nearest_partners": {
            "id": 12,
            "name": "METRO",
            "distance": 1654,
            "start_time": "21:00",
            "end_time": "23:00",
            "location": {
                "city": "Самара",
                "street": "Самара, ул. Уральская",
                  "lat": "53.133508",
                "lon": "50.139123"
            }
        },
           "shipping_options": [
                {
                    "option_id": "by_courier:47b6e4f87864",
                    "start_time": "21:00:00.000+04:00",
                    "end_time": "23:00:00.000+04:00",
                    "express_delivery": false,
                    "summary": "Ближайшая доставка сегодня 21:00–23:00"
                }
           ]
       }, 
       {
	    "id": 24,
        "uuid": "dde6ebd4-8fc4-43d9-a299-09385ae5f573",
        "name": "АШАН",
        "slug": "auchan",
        "partners_count": 4,
        "appearance": {
            "image_color": "#ffffff",
            "logo_image": "https://static.petrushka.ru/statics/partners-appearances/7ad134aa-06d2-42d5-8942-85360f501784-fify-auchan.png",
            "mini_logo_image": "https://static.petrushka.ru/statics/partners-appearances/b4bb4dd0-c220-4d51-b256-10d746e04470-Auchan.png",
            "external_link": "https://www.auchan.ru?utm_source=petrushka&nearest_partners_id=17"
        },
         "nearest_partners": {
            "id": 17,
            "name": "Ашан",
            "distance": 2700,
            "start_time": "18:00",
            "end_time": "20:00",
            "location": {
                "city": "Самара",
                "street": "Самара, ул. Дыбенко",
                  "lat": "53.207505",
                "lon": "50.200969"
            }
		  },
           "shipping_options": [
                {
                    "option_id": "by_courier:47b6e4f87864",
                    "start_time": "18:00:00.000+04:00",
                    "end_time": "20:00:00.000+04:00",
                    "express_delivery": false,
                    "summary": "Ближайшая доставка сегодня 18:00–20:00"
                }
           ]
       }, 
     {"id": 43,
        "uuid": "c438cab1-7818-4c26-99e5-d60381672812",
        "name": "ВкусВилл",
        "slug": "vkusvill",
        "partners_count": 7, 
        "appearance": {
        "image_color": "#DDDDDD",
        "black_theme": false,
        "logo_image": "https://static.petrushka.ru/statics/partners-selection/retailer-appearances/48af636c-1d33-4a20-9dcc-96401a28caac-vkusvill_supermarket.png",
        "mini_logo_image": "https://static.petrushka.ru/statics/partners-selection/retailer-appearances/9a406b1a-18b3-4bf2-8cb7-3e19a6dba7b4-Vkusvill.png",
		"external_link": "https://vkusvill.ru?utm_source=petrushka&nearest_partners_id=11"
	    },
      "nearest_partners": {
            "id": 11,
            "name": "ВкусВилл",
            "distance": 3000,
            "location": {
                "city": "Самара",
                "street": "Самара, ул. Авроры",
                  "lat": "53.207505",
                "lon": "50.230453"
            }
		  },
           "shipping_options": [
                {
                    "option_id": "by_courier:34b8k4f6523",
                    "express_delivery": true,
                    "summary": "Быстрая доставка от 20 до 60 минут"
                }
           ]        
        },
     {"id": 122,
        "uuid": "c438cab1-7818-4c26-99e5-f50671284313",
        "name": "ВИКТОРИЯ",
        "slug": "victoria",
        "partners_count": 2, 
        "appearance": {
        "image_color": "#DDDDDD",
        "black_theme": false,
        "logo_image": "https://static.petrushka.ru/statics/partners-selection/retailer-appearances/48af636c-1d33-6a33-9dcc-96403a48waa3-victoria_new.png",
        "mini_logo_image": "https://static.petrushka.ru/statics/partners-selection/retailer-appearances/9a406b1a-15b3-3bf3-6cb4-2b15a6sta5b2-Victoria.png",
		"external_link": "https://victoria-group.ru?utm_source=petrushka&nearest_partners_id=15"
	    },
      "nearest_partners": {
            "id": 15,
            "name": "ВИКТОРИЯ",
            "distance": 3500,
            "start_time": "17:00",
            "end_time": "19:00",
            "location": {
                "city": "Самара",
                "street": "Самара, ул. Ленинградская",
                  "lat": "53.207505",
                "lon": "50.430453"
            }
		  },
           "shipping_options": [
                {
                    "option_id": "by_courier:24dc7e4f84454",
                    "start_time": "17:00:00.000+04:00",
                    "end_time": "19:00:00.000+04:00",
                    "express_delivery": false,
                    "summary": "Ближайшая доставка сегодня 17:00–19:00"
                }
           ]        
        }
  ]
```
