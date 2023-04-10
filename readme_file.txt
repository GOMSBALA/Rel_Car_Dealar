Here, I used Django Framework

* In django It support the "WSGI" and "ASGI" methods. but FLask didn't have the ASGI .
* These both are used for communicating the web server with applications.
* Compared with Flask It have high security level,because it have the inbuild security system.
* This is used for "FullStack Developement". It have lot of inbuild functionality.
* It is supported for large kind of project.
* It have the inbuild "ORM" method.

I done the API for 
* Getting JSON from Dealer using POST method
* Give the Response to the user for the particular id using GET method
* DELETE method here describe to delete particular record in DB
* for Update I used PUT method

Here, Initially it is called to urls.py , them it is connected to views.py.
In views describe the models and serializer.
I am getting the user data by using serializer in JSON format.
Then models is connected to the serializer,so the data automatically stored in the DB table.

JSON:

API: "postdetails"

Input1:
{
"car_no":"TN13L9876",
"dealer_name":"MARUTHI",
 "dealer_number":"9876456780",
 "car_model":"Suzuki",
"manufacture_date":"04-04-2023",
"price":"900000"
}
Input2:
{
"car_no":"TN16L4563"
"dealer_name":"KIA",
 "dealer_number":"9232254650",
 "car_model":"KIA",
"manufacture_date":"20-04-2023",
"price":"1200000"
}


API : "getdetails"
Input:
{"car_no":"TN13L9876"}

API: "deletedetail"
Input:
{"car_no":"TN16L4563"}

API: "updatedetail"
Input:
{"car_no":"TN13L9876"}











