# shopping-cart
Apply resource : Get call
http://localhost:8081/shopping-cart/discount/apply/15000.00


Add resource : Post call
http://localhost:8081/shopping-cart/discount/
{
	"lowerLimit":"20000.00",
	"upperLimit":"50000.00",
	"percentage":"30.00"
}

Remove resource : Delete call
http://localhost:8081/shopping-cart/discount/{resourceId}

Get a resource by id : Get call
http://localhost:8081/shopping-cart/discount/{resourceId}

Get all resources : Get call
http://localhost:8081/shopping-cart/discount/
