<script>



  // async function open(){
  //   rzp1.open()

  // }
  
  

  var options = {
    "key": "rzp_test_wZsCHShozJ8ncL", // Enter the Key ID generated from the Dashboard
    "amount": "50000", // Amount is in currency subunits. Default currency is INR. Hence, 50000 refers to 50000 paise
    "currency": "INR",
    "name": "Acme Corp",
    "description": "Test Transaction",
    "image": "https://i.pinimg.com/originals/b5/d4/99/b5d4997066694fa0dffb70977a101c08.jpg",
    "order_id": "order_I7evPLr7zro1OG", //This is a sample Order ID. Pass the `id` obtained in the response of Step 1
    "handler": function (response){
        alert(response.razorpay_payment_id);
        alert(response.razorpay_order_id);
        alert(response.razorpay_signature)
    },
    "prefill": {
        "name": "Gaurav Kumar",
        "email": "gaurav.kumar@example.com",
        "contact": "9999999999"
    },
    "notes": {
        "address": "Razorpay Corporate Office"
    },
    "theme": {
        "color": "#3399cc"
    }
};
//var rzp1 = new Razorpay(options);

</script>

<main>


  <h1 class="text-red-300" > Razorpay Donation </h1>


  

</main>