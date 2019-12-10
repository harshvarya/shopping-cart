# shopping-cart
Apply discount : Get call
http://localhost:8081/shopping-cart/discount/apply/15000.00


Add discount : Post call
http://localhost:8081/shopping-cart/discount/add
{
	"lowerLimit":"20000.00",
	"upperLimit":"50000.00",
	"percentage":"30.00"
}

Remove discount : Post call
http://localhost:8081/shopping-cart/discount/remove
{
	"lowerLimit":"20000.00",
	"upperLimit":"50000.00",
	"percentage":"30.00"
}
