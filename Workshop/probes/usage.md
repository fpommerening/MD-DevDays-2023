# BaseUrl
Set in ingressroute.yaml
Sample: http://coffeemaker.t.container-training.de

# List of Orders
GET: BaseUrl/order/ 

# Order a Coffee
PUT: BaseUrl/order/ 
Content-Type: Json
Sample:
{
    "Order" : "Kaffee schwarz"
}

# Get Health Status
GET: BaseUrl/probe/alive/

# Set Health Status
PUT: BaseUrl/probe/alive/false
Content-Type: Json
Sample:
{

}
