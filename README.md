<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Login Member</title>
    <style>
        * {
            margin: 0vw 0vw;
            
        }
        body {
            background-color:#ffd26a;
        }
        img {
            height: 30vw;
            width: 30vw;
            margin-left: 34vw;
            margin-top: 35vw;
            margin-bottom:13vw;
            border-radius: 50%;
        }
        label {
            font-size: 6vw;
            margin-left: 0.5vw;
        }
        #rks,#ps,#kk, #ss, #ms{
            height: 7vw;
            margin-left: 1.5vw;
            background: white;
            border:0;
            border-radius: 2vw;
            font-size:3.88vw;
        }
        #kk {
            margin-left: 28.5vw;
            margin-top: 2vw;
        }
        #rks:hover {
            background: #55ff97;
        }
        #ps:hover {
            background: #55ff97;
        }
        #kk:hover {
            background: #55ff97;
        }
        #ss:hover {
            background: #55ff97;
        }
        #ms:hover {
            background: #55ff97;
        }
        input {
            margin-top: 6vw;
            margin-left: 3.5vw;
            background: white;
            text-align:center;
            font-size:4vw;
            border:0;
            height: 8vw;
            width: 58.5vw;
            border-radius: 2vw;
            
        }
        #login {
            margin-top: 15vw;
            margin-left:15vw;
            background: #7f98ff;
            text-align:center;
            font-size:5vw;
            border:0;
            height: 10vw;
            width: 65vw;
            border-radius: 10vw;
        }
        hr {
            background-color:transparent;
            margin-top: -500px;
            
        }
        a {
            text-decoration:none;
            margin-top:-20vw;
            color:#ffd26a;
        }
        h1 {
            font-size:0vw;
            margin-top:-100px;
        }
    </style>
</head>
<body>
    <img src="https://cdn-icons-png.flaticon.com/512/149/149071.png" id="icon"><br>
    <label>NAME : </label>
    <button id="rks" onClick="rksimg()">RAKESH KR. SONI</button>
    <button id="ps" onClick="psimg()">POONAM SONI</button>
    <button id="kk" onClick="kkimg()">KHUSHI</button>
    <button id="ss" onClick="ssimg()">SAKSHI</button>
    <button id="ms" onClick="msimg()">MANISH SONI</button>
    
    <br>
    <label>CODE : </label>
    <input type="number" placeholder="Enter your CODE" id="pin">
    
    <button id="login" onClick="passMatch()">LOGIN</button>
    
    <script>
        function rksimg() {
            document.getElementById("icon").src="https://firebasestorage.googleapis.com/v0/b/photo-to-link.appspot.com/o/21107534?alt=media&token=6bcdd844-cc36-4470-b05f-23e5324de472";
        }
        function psimg() {
            document.getElementById("icon").src="https://firebasestorage.googleapis.com/v0/b/photo-to-link.appspot.com/o/794668128?alt=media&token=cebf6566-d841-408b-8348-19eb91565ad8";
        }
        function kkimg() {
            document.getElementById("icon").src="https://cdn-icons-png.flaticon.com/512/149/149071.png";
        }
        function ssimg() {
            document.getElementById("icon").src="https://cdn-icons-png.flaticon.com/512/149/149071.png";
        }
        function msimg() {
            document.getElementById("icon").src="https://firebasestorage.googleapis.com/v0/b/photo-to-link.appspot.com/o/331918330?alt=media&token=979dfe85-2c31-4856-bd6b-2430a7c35000";
        }
        
        
        
        var pass = document.getElementById("pin").value;
        var a = 1
        
        function passMatch() {
            var pass = document.getElementById("pin").value;
            if(pass==301107) {
                alert("Hello, RAKESH KUMAR SONI");
            }else if(pass==""){
                alert("Please Fill Code!! ")
            }else if(pass!==301107){
                alert("Wrong CODE......")
            }
        }
    </script>
</body>
</html>
