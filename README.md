# Search App
## Search output API
```json
{
    "id": 207,
    "region": {
        "id": 4,
        "name": "تشرين",
        "governorate": {
            "id": 1,
            "name": "دمشق"
        }
    },
    "images": [
        {
            "id": 613,
            "image": "/files/Property_Images/apartment_image_51000.jpg",
            "is_special": false
        }
    ],
    "location": {
        "latitude": 33.53548684822669,
        "longitude": 36.215399900455466
    },
    "location_details": "96640 نديم Vista Apt. 134\nالنقيبview, WA 77637",
    "price": 771,
    "number_of_rooms": 3,
    "number_of_bathrooms": 2,
    "property_side": "غرب",
    "description": "مليون وانهاء والديون والحزب المجتمع الخاطفة مئات. المنتصر اليميني اتفاق للأراضي تزامناً. الجوي مرمى وإعلان إختار.",
    "furniture": false,
    "property_rights": "Green title deed",
    "contract_type": "Daily rent",
    "total_area": 232.67807604148533,
    "internal_area": 206.7199672991119,
    "external_area": 84.56902835532932,
    "view_360": null,
    "nearby_places": "لعملة, وصل, هو",
    "additional_services": "بالتوقيع, الأمور",
    "special": true,
    "parking": 2,
    "favorites": 0,
    "property_type": "شقة",
    "floor_number": 13,
    "elevator": true,
    "surface_ownership": "Nothing",
    "water_tank": "Individually",
    "fuel_tank": "Shared",
    "apartment_type": "Clinic",
    "registration_statement": null,
    "equipment": "ألمّ, الخاطفة, حالية",
    "is_favorite": null,
    "update_date": "2024-11-17T11:24:00.661720+03:00",
    "create_date": "2024-11-17T11:24:00.661685+03:00",
}
```

# Property App
## 1] Property card API
`~new api (needed for flutter team)~`</br>
This API needed at:
1. Search
2. List All [villas, apartments]
3. favorites

```json
{
    "id": 207,
    "region": {
        "id": 4,
        "name": "تشرين",
        "governorate": {
            "id": 1,
            "name": "دمشق"
        }
    },
    "images": [
        {
            "id": 613,
            "image": "/files/Property_Images/apartment_image_51000.jpg",
            "is_special": false
        }
    ],
    "price": "",
    "total_area": "",
    "number_of_rooms": "",
    "update_date": "2024-11-17T11:24:00.661720+03:00",
    "create_date": "2024-11-17T11:24:00.661685+03:00",
}
```

## 2] Region output API
```json
{
    "id": 1,
    "name": "الحرية_ عش الورور",
    "governorate": 1
}
```

## 3] Governorate output API
```json
{
    "id": 1,
    "name": "Damascus"
}
```

## 4] Apartment OutPut API

```json
{
    "id": 3,
    "property_type": "apartment",
    "owner": {
        "id": 1,
        "full_name": " ",
        "phone_number": "+963991283593",
        "gender": "M",
        "birthday": "2024-09-29"
    },
    "region": {
        "id": 52,
        "name": "Al Qanawat",
        "governorate": {
            "id": 1,
            "name": "Damascus"
        }
    },
    "images": [
        {
            "id": 613,
            "image": "/files/Property_Images/apartment_image_51000.jpg",
            "is_special": false
        },
        {
            "id": 614,
            "image": "/files/Property_Images/apartment_image_51001.jpg",
            "is_special": true
        }
    ],
    "favorites": 0,
    "is_favorite": null,
    "location": {
        "latitude": 33.598526064559124,
        "longitude": 36.242503830703264
        },
    "location_details": "473 Kiara Village\nSouth Mary, FL 06442",
    "price": 5084,
    "number_of_rooms": 5,
    "number_of_bathrooms": 2,
    "property_side": "North",
    "description": "My current much agency much between bit he. Score catch successful school. May tell research those.\nRange nothing population beyond. South speech attention great list over.",
    "furniture": true,
    "property_rights": "Green title deed",
    "contract_type": "Annual rent",
    "total_area": 311.4101916883683,
    "internal_area": 252.7908652339779,
    "external_area": 73.4095855869526,
    "view_360": null,
    "nearby_places": "find, because, chance",
    "additional_services": "office, along",
    "special": true,
    "parking": 1,
    "create_date": "2024-09-29T11:17:24.519609+03:00",
    "update_date": "2024-09-29T11:17:24.519637+03:00",
    "floor_number": 6,
    "elevator": true,
    "surface_ownership": "Nothing",
    "water_tank": "Shared",
    "fuel_tank": "Individually",
    "apartment_type": "Apartment",
    "registration_statement": null,
    "equipment": "agreement, tax, then",
    "update_date": "2024-09-29T11:17:21.232123+03:00",
    "create_date": "2024-09-29T11:17:21.232020+03:00"
}
```

## 5] Villa Output API
```json
{
    "id": 53,
    "property_type": "villa",
    "owner": {
        "id": 1,
        "full_name": " ",
        "phone_number": "+963991283593",
        "gender": "M",
        "birthday": "2024-09-29"
    },
    "region": {
        "id": 208,
        "name": "Jouret Ash-Shayyah",
        "governorate": {
            "id": 4,
            "name": "Homs"
        }
    },
    "images": [
        {
            "id": 613,
            "image": "/files/Property_Images/apartment_image_51000.jpg",
            "is_special": false
        },
        {
            "id": 614,
            "image": "/files/Property_Images/apartment_image_51001.jpg",
            "is_special": true
        }
    ],
    "favorites": 0,
    "is_favorite": null,
    "location": {
        "latitude": 33.598526064559124,
        "longitude": 36.242503830703264
        },
    "location_details": "8743 Christine Crest\nNew Zoe, AZ 72564",
    "price": 2130,
    "number_of_rooms": 2,
    "number_of_bathrooms": 1,
    "property_side": "North",
    "description": "Politics feeling say throughout become. Economy behavior former above employee respond. Direction campaign or wind treat hard. Bag what technology analysis stage tell.",
    "furniture": false,
    "property_rights": "Green title deed",
    "contract_type": "Daily rent",
    "total_area": 181.8285995384003,
    "internal_area": 287.7697936721746,
    "external_area": 40.850395019353165,
    "view_360": null,
    "nearby_places": "enjoy, pattern, evening, item",
    "additional_services": "by, little, leave, sure",
    "special": true,
    "parking": 2,
    "number_floors": 2,
    "pool": true,
    "children_pool": true,
    "pool_depth": 0.6981105346718247,
    "pool_covered": true,
    "bbq_place": true,
    "bbq_kit": "state, wife, those",
    "kitchen_kit": "including, approach, if, picture",
    "update_date": "2024-09-29T11:17:25.940491+03:00",
    "create_date": "2024-09-29T11:17:25.940450+03:00"
}
```

# Booking App
## 1] Booking Output API

```json
{
    "id": 105,
    "related_property": {
        "id": 151,
        "region": {
            "id": 1,
            "name": "الحرية_ عش الورور",
            "governorate": {
                "id": 1,
                "name": "دمشق"
            }
        },
        "owner": {
            "id": 103,
            "full_name": "Mohammed Rajjab",
            "phone_number": "+963998749221",
        },
        "location": {
            "latitude": 33.07,
            "longitude": 38.04
        },
        "location_details": "شارع خالد بن الوليد",
        "price": 1500,
        "nearby_places": "مقابل مدسة ومول وحديقة",
        "apartment_type": "Apartment",
        },
    "client": {
        "id": 104,
        "phone_number": "+963997749221",
        "full_name": "Mohammed Rajab"
    },
    "client_checking_range": {
        "lower": "2159-08-08T14:00:00+03:00",
        "upper": "2159-08-08T15:00:00+03:00",
        "bounds": "()"
    },
    "original_reservation": {
        "lower": "2159-08-08T14:00:00+03:00",
        "upper": "2159-08-08T15:00:00+03:00",
        "bounds": "()"
    },
    "checked_in": true,
    "checked_out": true,
    "num_of_adults": 4,
    "num_of_children": 6,
    "price": 1500,
    "status": "Paid",
    "create_date": "2024-10-07T18:57:00.536865+03:00",
    "update_date": "2024-10-09T11:05:49.965942+03:00",
}
```

## 2] RejectedCancelledBooking Output API
```json
{
    "id": 38,
    "booking": {
        "id": 59,
        "client_checking_range": {
            "lower": "2159-08-08T14:00:00+03:00",
            "upper": "2159-08-08T15:00:00+03:00",
            "bounds": "()"
        },
        "status": "Cancelled",
        "checked_in": false,
        "checked_out": false
    },
    "reason": "just another loream",
    "is_read": true,
    "create_date": "2024-07-20T12:19:52.922819+03:00",
    "update_date": "2024-07-20T12:20:31.206204+03:00"
}
```

## 3] Intersted Output API
```json
{
    "id": 15,
    "related_property": 2,
    "interest_datetime_range": {
        "lower": "2159-08-08T14:00:00+03:00",
        "upper": "2159-08-08T15:00:00+03:00",
        "bounds": "()"
    },
    "client": {
        "id": 2,
        "phone_number": "+963959539503",
        "full_name": ""
    },
    "bookings": [
        {
            "id": 48,
            "client_checking_range": {
                "lower": "2159-08-08T14:00:00+03:00",
                "upper": "2159-08-08T15:00:00+03:00",
                "bounds": "()"
            },
            "status": "Paid",
            "checked_in": false,
            "checked_out": false
        }
    ],
    "create_date": "2024-07-10T12:11:00.316548+03:00",
    "update_date": "2024-07-10T12:11:00.316548+03:00"
}
```

# PaymentGates App
## 1] MTN App
### MTN create payment output API
```json
{
    "response_datetime": "2024-10-29T09:20:20.366+03:00",
    "success": true,
    "status_code": 200,
    "message": "Create payment request result.",
    "data": {
        "ErrorCode": 0,
        "ErrorMessage": "The request handled successfully",
        "InvoiceStatus": [
            "Invoice waits auth token",
            "InvoiceStatusActive"
        ],
        "PaymentData": {
            "id": 3,
            "amount": 1,
            "create_date": "2024-10-29T09:20:19.513136+03:00",
            "update_date": "2024-10-29T09:20:20.282442+03:00",
            "status": "Pending",
            "gateway": "MTN",
            "currency": "SYP",
            "object_id": 101,
            "customer_phone_number": null,
            "guid": null,
            "operation_number": null,
            "invoice_number": 899717053337,
            "pos": 9001000000054221,
            "mtn_status": 1,
            "transaction": null,
            "created_invoice_at": "2024-10-29T09:20:30+03:00",
            "expired_invoice_at": "2024-10-29T14:20:30+03:00",
            "processed_invoice_at": null,
            "qr_code": "MTN-M-9001000000054221-899717053337-304502204A9EDB6821DCBC268764BB0866A0D37962721E77B9CECEA3021F94CDB0B77464022100A5AD7E96E01E28745AE7E3B3B23E0F9FEC19CE65A704B6458F7C8D4650426590",
            "paid": false,
            "cancelable": true,
            "canceled": false
        },
        "ReceiptError": {
            "Number": 0,
            "Msg": "No issues"
        }
    }
}
```

### MTN payment by phone output API
```json
{
    "response_datetime": "2024-10-29T09:22:24.588+03:00",
    "success": true,
    "status_code": 200,
    "message": "Payment by phone request result.",
    "data": {
        "ErrorCode": 0,
        "ErrorMessage": "The request handled successfully",
        "InvoiceStatus": [
            "Invoice waits auth token",
            "InvoiceStatusActive"
        ],
        "PaymentData": {
            "id": 3,
            "amount": 1,
            "create_date": "2024-10-29T09:20:19.513136+03:00",
            "update_date": "2024-10-29T09:22:24.533669+03:00",
            "status": "Pending",
            "gateway": "MTN",
            "currency": "SYP",
            "object_id": 101,
            "customer_phone_number": "963962400125",
            "guid": "af13abba-3731-4ca7-9985-351dab62618f",
            "operation_number": 7227340930324573,
            "invoice_number": 899717053337,
            "pos": 9001000000054221,
            "mtn_status": 1,
            "transaction": null,
            "created_invoice_at": "2024-10-29T09:20:30+03:00",
            "expired_invoice_at": "2024-10-29T14:20:30+03:00",
            "processed_invoice_at": null,
            "qr_code": "MTN-M-9001000000054221-899717053337-304502204A9EDB6821DCBC268764BB0866A0D37962721E77B9CECEA3021F94CDB0B77464022100A5AD7E96E01E28745AE7E3B3B23E0F9FEC19CE65A704B6458F7C8D4650426590",
            "paid": false,
            "cancelable": true,
            "canceled": false
        },
        "ReceiptError": {}
    }
}
```

### MTN confirm payment output API
```json
{
    "response_datetime": "2024-10-29T09:37:34.563+03:00",
    "success": true,
    "status_code": 200,
    "message": "Confirm payment request result.",
    "data": {
        "ErrorCode": 0,
        "ErrorMessage": "The request handled successfully",
        "InvoiceStatus": [
            "Invoice paid successfully",
            "InvoiceStatusSuccess"
        ],
        "PaymentData": {
            "id": 4,
            "amount": 1,
            "create_date": "2024-10-29T09:36:52.152842+03:00",
            "update_date": "2024-10-29T09:37:34.538397+03:00",
            "status": "Success",
            "gateway": "MTN",
            "currency": "SYP",
            "object_id": 102,
            "customer_phone_number": "963962400125",
            "guid": "d911f397-2251-4222-adda-783204efc0d3",
            "operation_number": 7377130930324585,
            "invoice_number": 299895757809,
            "pos": 9001000000054221,
            "mtn_status": 9,
            "transaction": "9449370930342508",
            "created_invoice_at": "2024-10-29T09:37:03+03:00",
            "expired_invoice_at": "2024-10-29T14:39:03+03:00",
            "processed_invoice_at": "2024-10-29T09:37:44+03:00",
            "qr_code": "MTN-M-9001000000054221-299895757809-3045022031761223F4E70F1E5428F3D7C7D1C470AE75FAD22B0E449F7287DD695F41F150022100F061C588053044F8A5240437306E97C5068FC737A2DC8BD082603EA8D05EFC09",
            "paid": true,
            "cancelable": false,
            "canceled": false
        },
        "ReceiptError": {}
    }
}
```

### MTN check payment status output API
```json
{
    "response_datetime": "2024-10-29T09:39:30.970+03:00",
    "success": true,
    "status_code": 200,
    "message": "Check payment status request result.",
    "data": {
        "ErrorCode": 0,
        "ErrorMessage": "The request handled successfully",
        "InvoiceStatus": [
            "Invoice paid successfully",
            "InvoiceStatusSuccess"
        ],
        "PaymentData": {
            "id": 4,
            "amount": 1,
            "create_date": "2024-10-29T09:36:52.152842+03:00",
            "update_date": "2024-10-29T09:39:30.938531+03:00",
            "status": "Success",
            "gateway": "MTN",
            "currency": "SYP",
            "object_id": 102,
            "customer_phone_number": "963962400125",
            "guid": "d911f397-2251-4222-adda-783204efc0d3",
            "operation_number": 7377130930324585,
            "invoice_number": 299895757809,
            "pos": 9001000000054221,
            "mtn_status": 9,
            "transaction": "9449370930342508",
            "created_invoice_at": "2024-10-29T09:37:03+03:00",
            "expired_invoice_at": "2024-10-29T14:39:03+03:00",
            "processed_invoice_at": "2024-10-29T09:37:44+03:00",
            "qr_code": "MTN-M-9001000000054221-299895757809-3045022031761223F4E70F1E5428F3D7C7D1C470AE75FAD22B0E449F7287DD695F41F150022100F061C588053044F8A5240437306E97C5068FC737A2DC8BD082603EA8D05EFC09",
            "paid": true,
            "cancelable": false,
            "canceled": false
        },
        "ReceiptError": {
            "Number": 0,
            "Msg": "No issues"
        }
    }
}
```

## 2] Fatora App

### Fatora create payment API
#### Input
```json
{
    "object_id": 87,
    "model_name": "Booking",
    "notes": "hello" // optional
}
```
#### OutPut
```json
{
    "response_datetime": "2024-09-23T14:08:53.459+03:00",
    "success": true,
    "status_code": 200,
    "message": "Payment request result",
    "data": {
        "ErrorMessage": "Payment request successfully intialized",
        "ErrorCode": 0,
        "Data": {
            "url": "https://egate-t.fatora.me/start/9b330a6a-157a-4860-ab68-881c77e1930f/en/1",
            "paymentId": "9b330a6a-157a-4860-ab68-881c77e1930f"
        }
    }
}
```

### Fatora check payment status API
#### Input
```json
{
    "payment_uuid": "1b2d8761-fd21-4495-a09e-de77ff9575e2"
}

```
#### OutPut
```json
{
    "response_datetime": "2024-09-23T19:22:08.868+03:00",
    "success": true,
    "status_code": 200,
    "message": "Payment status result",
    "data": {
        "ErrorMessage": "Check payment status success",
        "ErrorCode": 0,
        "Data": {
            "status": "Payment Pending",
            "creationTimestamp": "2024-09-23 19:21:36.780",
            "rrn": null,
            "amount": "65412.3",
            "terminalId": "14740089",
            "notes": "hello",
            "callbackURL": "https://www.google.com/",
            "triggerURL": "http://127.0.0.1:8000/api/v1/payment/fatora/payment_trigger_api/90/booking/"
        }
    }
}
```

## 3] Syriatel App
### Create payment output API


# Availability App
## 1] VisitingTime Output API
```json
{
    "id": 103,
    "related_property": {
        "id": 1,
        "price": 0
    },
    "day": "5 Saturday",
    "visiting_range": {
        "lower": "06:35:00+03:00",
        "upper": "23:15:00+03:00",
        "bounds": "()"
    },
    "str_range": "hours: 16, minutes: 40",
    "visiting_period_in_minutes": 60,
    "num_of_available_visitings": 16,
    "create_date": "2024-07-22T08:20:26.881734+03:00",
    "update_date": "2024-07-22T08:20:26.881734+03:00"
}
```

## 2] BookingVisit Output API
```json
{
    "id": 61,
    "visiting_time": {
        "id": 103,
        "day": "5 Saturday",
        "related_property": 1,
        "visiting_range": {
            "lower": "06:35:00+03:00",
            "upper": "23:15:00+03:00",
            "bounds": "()"
        },
        "visiting_period_in_minutes": 55
    },
    "client": {
        "id": 5,
        "phone_number": "+963951624837",
        "full_name": "Mohammed Rajab"
    },
    "visiting_datetime_range": {
        "lower": "06:35:00+03:00",
        "upper": "23:15:00+03:00",
        "bounds": "()"
    },
    "checked": false,
    "visit_status": "On hold", // to be changed into Pending instead of 'On hold'
    "create_date": "2024-07-22T12:04:17.176517+03:00",
    "update_date": "2024-07-22T12:04:17.176517+03:00",
}
```

## 3] RejectedCancelledBookingVisit output API
```json
{
    "id": 40,
    "original_booking_visit": {
        "id": 71,
        "visit_status": "Cancelled"
    },
    "reason": "I don't know",
    "is_read": false,
    "create_date": "2024-07-22T20:02:19.702080+03:00",
    "update_date": "2024-07-22T20:02:19.702080+03:00",
}
```

# Notification App

# Activity App
