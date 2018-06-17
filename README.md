<!DOCTYPE html>
<html>
<head>
	<title>Parents Day Card</title>
	<script type="text/javascript">
		function changeimg()
		{
			var v=document.createElement("img");
			v.style.width="100%"
			v.style.height="auto"
			var vr=Math.floor(Math.random()*100);
			if(vr<20)
			v.src="1.jpg"
			else if (vr<30)
			v.src="2.jpg"
			else if (vr<40)
			v.src="3.jpg"
			else if(vr<50)
			v.src="4.jpg"
			else if(vr<60)
			v.src="5.jpg"
			else if(vr<70)
			v.src="6.jpg"
			else
			v.src="7.jpg"	

			var d=document.getElementById("div1");
			d.appendChild(v);



		}
		function intervalAppend()
		{
			timer= setInterval(changeimg,7000);
		}
		function intervalClear()
		{
			clearInterval(timer);		}
	</script>
	<style>
	p.p1
	{
		color: #FEF3DC;
		font-family: monospace;
		font-size: 40px;
	}
	p.p2
	{
		color: #FDCD6D;
		font-family: sans-serif;
		font-size: 30px;
	}
	body{
		background-color: #FED777;
	}
	 *{box-sizing: border-box;}

  		[class*="col-"] {
        width: 100%;  
    	}
    	@media only screen and (min-width: 300px){
 		.col-m-1 {width: 8.33%;}
 		.col-m-2 {width: 16.66%;}
 		.col-m-3 {width: 25%;}
 		.col-m-4 {width: 33.33%;}
 		.col-m-5 {width: 41.66%;}
 		.col-m-6 {width: 50%;}
 		.col-m-7 {width: 58.33%;}
 		.col-m-8 {width: 66.66%;}
 		.col-m-9 {width: 75%;}
 		.col-m-10 {width: 83.33%;}
 		.col-m-11 {width: 91.66%;}
 		.col-m-12 {width: 100%;}
    }
    @media only screen and (min-width: 600px) {
 		.col-1 {width: 8.33%;}
 		.col-2 {width: 16.66%;}
 		.col-3 {width: 25%;}
 		.col-4 {width: 33.33%;}
 		.col-5 {width: 41.66%;}
 		.col-6 {width: 50%;}
 		.col-7 {width: 58.33%;}
 		.col-8 {width: 66.66%;}
 		.col-9 {width: 75%;}
 		.col-10 {width: 83.33%;}
 		.col-11 {width: 91.66%;}
 		.col-12 {width: 100%;}
    }
 	@media only screen and (max-width: 400px) { 
 		.col-s-1 { width: 8.33%; }
		.col-s-2 {width: 16.66%;}
		.col-s-3{width: 25%;}
		.col-s-4{width: 33.33%;}
		.col-s-5 {width: 41.66%;}
 		.col-s-6 {width: 50%;}
  		.col-s-7 {width: 58.33%;}
 		.col-s-8 {width: 66.66%;}
 		.col-s-9 {width: 75%;}
  		.col-s-10 {width: 83.33%;}
 		.col-s-11 {width: 91.66%;}
 		.col-s-12 {width: 100%;}
  
 }

 
 [class*="col-"] {
  float:left;
  border:1px solid black;
  padding:15px;
  height: 500px;
 }

 .row::after {
    content: "";
    clear: both;
    display: table;
 }
	</style>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width,initial-scale=1.0">
</head>
<body  onload="intervalAppend()">
<div class="row">
 <div class="col-12 col-m-12" style="background-color:#FED777; border: none; height: 80px">
 </div>
 </div>
 <div class="row">
 <div class="col-1 col-m-12" style="background-color:#FED777;border: none;"></div>
 <div class="col-10 col-m-12" style="background-color:#FFF5DC;">
 	<button onclick="intervalClear()">Stop img</button><p style="color: #342809; font-size: 100px; text-align: center;">Parents Day</p>
 	<p style="color: #A77802; font-size: 100px; text-align: center;">CARD</p>
 </div>
 <div class="col-1 col-m-12" style="background-color:#FED777;border: none;"> </div>
 </div>
 <div class="row" style="height: 8000px">
 <div class="col-1 col-m-12" style="background-color:#FED777;height: 8000px; border:none;"></div>
 <div id="div1" class="col-5 col-m-12" style="background-color: #FFF5DC;height: 8000px" onclick="changeimg()"><img src="1.jpg" style="height: auto; width: 100%;"></div>
 <div class="col-5 col-m-12" style="background-color: #342809;height: 8000px"> <p style="color:#FBA90A; font-size: 60px; font-family: serif;">어버이날을 축하드립니다!!</p><p class="p1">왼쪽의 사진은 계속 추가되는 아들둘과 같이찍은 사진들이 나열됩니다! 중지하려면 위쪽의 버튼을 누르세요!</p>
 	<p class="p2">사실 어버이날은 이미 지난지 좀 오래됬죠 헌대 이 카드를 만들면서 생각해봤어요 제대로 부모님을 챙긴적이 있었는지 그래서 준비한 이벤트 카드 입니다.</p><img src="cake.jpg" style="width:100%; height:auto;"><p class="p2"> 축하드립니다! 그리고 감사합니다! 부모님의 보살핌으로 저는 어엿한 성인이 되었습니다.</p>
 </div>
 <div class="col-1 col-m-12" style="background-color:#FED777;  border:none;height: 8000px"></div>
 </div>
 
</body>
</html>
