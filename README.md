
{  
   "status":"success",
   "number_offers":2,
   "offers":[   
      {  
         "title":"Example Title",
         "description":"Example Description",
         "link":"https:\/\/tracking-link-example\/offer.php?id=1234&pub=5678&token=xxxx&subid=&subid2=&subid3=",
         "amount":"1.00",
         "payout_currency":"USD",
         "payout_type":"CPA",
            // Payout Types: CPA, CPI
         "category_name":"pin_submit",
            // Category Names: email_submit, pin_submit, app_install, trial, purchase, download
         "traffic_type":"incentive",
            // Traffic Types: incentive, non-incentive
         "campid":1234,
         "country":"US",
         "rank":1,
         "epc":"0.05",
         "ratio":"3.51",
         "creatives":[  
            {  
               "size":"70x70",
               "url":"https:\/\/asset-example\/images\/campaigns\/5468161_70x70.jpeg"
            }
         ],
         "previews":[  
            {  
               "size":"300x240",
               "url":"https:\/\/asset-example\/preview\/5468161_300x240.png"
            },
            {  
               "size":"1280x1024",
               "url":"https:\/\/asset-example\/preview\/5468161_1280x1024.png"
            }
         ],
         "preview_url":"https:\/\/example.com\/4bb01df8d938579d251ebc18c083e381",
         "mobile_app":0,
            // Mobile App: 0 = Not an application, 1 = Application
         "mobile_app_type":null,
            // Mobile App Types: android, ios, ipad
         "mobile_app_id":null,
         "mobile_app_minimum_version":null,
         "mobile_app_icon_url":null,
         "button_text":"Get",
         "conversion":"Pin-Submit"
      },
      {
         "title":"Example App Title",
         "description":"Example Description",
         "link":"https:\/\/tracking-link-example\/offer.php?id=987&pub=5678&token=xxxx&subid=&subid2=&subid3=",
         "amount":"1.00",
         "payout_currency":"USD",
         "payout_type":"CPI",
            // Payout Types: CPA, CPI
         "category_name":"app_install",
            // Category Names: email_submit, pin_submit, app_install, trial, purchase, download
         "traffic_type":"incentive",
            // Traffic Types: incentive, non-incentive
         "campid":987,
         "country":"US",
         "rank":2,
         "epc":"0.05",
         "ratio":"3.51",
         "creatives":[  
            {  
               "size":"70x70",
               "url":"https:\/\/asset-example\/images\/campaigns\/5468161_70x70.jpeg"
            }
         ],
         "previews":[  
            {  
               "size":"300x240",
               "url":"https:\/\/asset-example\/preview\/5468161_300x240.png"
            },
            {  
               "size":"1280x1024",
               "url":"https:\/\/asset-example\/preview\/5468161_1280x1024.png"
            }
         ],
         "preview_url":"https:\/\/example.com\/4bb01df8d938579d251ebc18c083e381",
         "mobile_app":1,
            // Mobile App: 0 = Not an application, 1 = Application
         "mobile_app_type":"android",
            // Mobile App Types: android, ios, ipad
         "mobile_app_id":"com.example",
         "mobile_app_minimum_version":"5.0",
         "mobile_app_icon_url":"https://play.google.com/example.png",
         "button_text":"Install",
         "conversion":"Converts on install and open"
      }
    ]
}     
