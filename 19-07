let foodOrders = [
  "Samosa",
  "Tea",
  "Sandwich",
  "Tea",
  "Burger",
  "Coffee",
  "Tea",
  "Pizza"
];


console.log(foodOrders.indexOf("Tea")); 


console.log(foodOrders.lastIndexOf("Tea")); 


console.log(foodOrders.includes("Pizza")); 
console.log(foodOrders.includes("Idli"));  
let orderDetails = [
  { orderId: 101, studentName: "Amit", item: "Tea", amount: 20, status: "Completed" },
  { orderId: 102, studentName: "Sneha", item: "Burger", amount: 80, status: "Pending" },
  { orderId: 103, studentName: "Rahul", item: "Pizza", amount: 120, status: "Completed" },
  { orderId: 104, studentName: "Priya", item: "Sandwich", amount: 60, status: "Pending" },
  { orderId: 105, studentName: "Kiran", item: "Tea", amount: 20, status: "Cancelled" },
  { orderId: 106, studentName: "Meena", item: "Coffee", amount: 40, status: "Completed" }
];


let firstPending = orderDetails.find(order => order.status === "Pending");
console.log(firstPending);



let firstPendingIndex = orderDetails.findIndex(order => order.status === "Pending");
console.log(firstPendingIndex); // Output: 1


let lastCompleted = orderDetails.findLast(order => order.status === "Completed");
console.log(lastCompleted);

let lastCompletedIndex = orderDetails.findLastIndex(order => order.status === "Completed");
console.log(lastCompletedIndex); // Output: 5
