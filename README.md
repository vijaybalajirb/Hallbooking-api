# Hallbooking-api
API end point : https://hall-api-app.herokuapp.com/

To get all booking details use
https://hall-api-app.herokuapp.com/roomsbookingstatus

To createroom use
Post req:
https://hall-api-app.herokuapp.com/rooms
Format of json: To create room
{
    "name":"roomname",
    "amenities": [
        "Audio Visual Equipment",
        "Onsite Kitchen",
        "AC"
    ],
    "location": "Available",
    "oneHourPrice":120
}

To create booking of customer ie To Add customer
Post req:
https://hall-api-app.herokuapp.com/bookroom

Format of json: To book room for customer.
{
    "custid": "1",
    "roomid": "1",
    "startDate": "2021-04-08 07:13:10.847",
    "endDate": "2021-04-08 21:13:10.847"
}


