<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" type="text/css" href="style.css">
    <title>Play Game 2048</title>
</head>

<body style="background-color: black;" id="body">
    <div class="main-box">
        <div class="head">
            <button onclick="New_Game()">Click</button>
            <button onclick="">Undo</button>
        </div>
        <div class="grid-container">
            <div class="num-box" id="1"></div>
            <div class="num-box" id="2"></div>
            <div class="num-box" id="3"></div>
            <div class="num-box" id="4"></div>
            <div class="num-box" id="5"></div>
            <div class="num-box" id="6"></div>
            <div class="num-box" id="7"></div>
            <div class="num-box" id="8"></div>
            <div class="num-box" id="9"></div>
            <div class="num-box" id="10"></div>
            <div class="num-box" id="11"></div>
            <div class="num-box" id="12"></div>
            <div class="num-box" id="13"></div>
            <div class="num-box" id="14"></div>
            <div class="num-box" id="15"></div>
            <div class="num-box" id="16"></div>
        </div>
    </div>
    
</body>

<script>
    var number = [0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0];
    var cond = 0;

    /*Ini buat nge random angka*/
    function prob(){
            let list = [2,2,2,2,2,2,2,2,2,4]; 
            let ran_num = Math.floor((Math.random() * 10)+0);
            return list[ran_num];
        }
    
    function FontChnager() {
        for (let i = 0; i < 16;i++){
            document.getElementById('x16').style.fontSize = "40px";
            document.getElementById('x32').style.fontSize = "40px";
            document.getElementById('x64').style.fontSize = "40px";
            document.getElementById('x128').style.fontSize = "30px";
            document.getElementById('x1024').style.fontSize = "25px";
        }
    }
    /*Ini to buat mbikin game baru atau mulai game baru*/
    function New_Game(){
        number = [0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0];
        let count_num = 0;

        for (let i = 0; i < 16; i++) {
            document.getElementById(i+1).innerHTML = ``;        
        }
        
        for (let i = 0; i <256; i++){
            let ran_index = Math.floor((Math.random() * 16)+0);
            if (number[ran_index] == 0){
                number[ran_index] = prob();
                count_num+=1;
            }
            if (count_num ==2) {
                break;
            }
        }
        
        for (let i = 0; i < 16; i++) {
            if (number[i] > 0 ) {
                document.getElementById(i+1).innerHTML = 
                `<div class='active-box' align='center' id='x${number[i]}' style="font-size:50px;">${number[i]}</div>`;        
            }
            
        } 
        let temp_array = [[],[],[],[]];
        let j = 0;
        for (let i = 0; i < 16; i++) {
            temp_array[0+j].push(number[i]);
            if (temp_array[0+j].length == 4) {
                j += 1;
            }
        }
        number = temp_array; 
        return number;
    }
    console.log(number);
    /*Waktu mulai*/
    New_Game();
    console.log(number);
    /*Ini mulai geser*/
    function GeserKanan() {
        let temp = [[],[],[],[]]
        let temp2 = [[],[],[],[]]
        let final = []
        
        for (let y = 0; y < 4; y++) {
            /*for (let i in number[y].reverse()){
                if (number[y] != 0) {
                    temp[y].push(0);
                }
            }*/
            for (let i = (number[y].length - 1); i >= 0; i--){
                if (number[y][i] != 0) {
                    temp[y].push(number[y][i]);
                }
            }
            let min = 4 - temp[y].length;
            /*console.log(`Ini min ke ${min} = `,min);*/
            if (temp[y].length < 4) {
                /*console.log(`Ini y ke ${y} = `,temp[y].length);*/
                for (let z = 0;z < min; z++){
                    /*console.log(`Ini z ke ${z} = `,z);*/
                    temp[y].push(0);
                }
            }
            
            for (let i =0; i < 3; i++){
                if (temp[y][i] == temp[y][i+1]) {
                    temp[y][i] += temp[y][i+1];
                    temp[y][i+1] = 0;
                }
            }
            for (let i in temp[y]) {
                if (temp[y][i] != 0) {
                    temp2[y].push(temp[y][i]);
                }
            }
            let min2 = 4 - temp2[y].length;
            if (temp2[y].length < 4) {
                for (let z = 0;z < min2; z++){
                    temp2[y].push(0);
                }
            }           
            final.push(temp2[y].reverse());
        }

        let count_num = 0;
        let temp_array = [[],[],[],[]];
        let j = 0;
        let Number_Temp = [];
        let state = 0;
        for (let d = 0; d < 4;d++) {
            for (let x = 0; x < 4;x++) {
                if (number[d][x]==final[d][x]){
                    state +=1;
                }
            }
        }
        
        if (state != 16) {
            for (let i = 0; i < 4; i++) {
                for (let y = 0; y < 4; y++) {
                    Number_Temp.push(final[i][y]);
                }   
            }
            
            while (count_num == 0){
                let ran_index = Math.floor((Math.random() * 16)+0);
                if (Number_Temp[ran_index] == 0){
                    Number_Temp[ran_index] = prob();
                    count_num+=1;
                }
                
                if (count_num == 1) {
                    for (let i = 0; i < 16; i++) {
                        temp_array[0+j].push(Number_Temp[i]);
                        if (temp_array[0+j].length == 4) {
                            j += 1;
                        }
                    }
                    final = temp_array; 
                
                    break;
                }
            }
        }else{
            console.log('blok');
        }
        
        
        for (let i = 0; i < 4; i++) {
                for (let y = 0; y < 4; y++) {
                    Number_Temp.push(final[i][y]);
                }   
            }
        for (let i = 0; i < 16; i++) {
            document.getElementById(i+1).innerHTML = ``;        
        }
        for (let i = 0; i < 16; i++) {
            if (Number_Temp[i] > 0 ) {
                document.getElementById(i+1).innerHTML = 
                    `<div class='active-box' align='center' id='x${Number_Temp[i]}' style="font-size:50px;">${Number_Temp[i]}</div>`;        
            }
            
        }
        
        console.log("Ini final2 - ",final);
        
        return final;
    }

    function GeserKiri() {
        let temp = [[],[],[],[]]
        let temp2 = [[],[],[],[]]
        let final = []
        
        for (let y = 0; y < 4; y++) {
            /*for (let i in number[y].reverse()){
                if (number[y] != 0) {
                    temp[y].push(0);
                }
            }*/
            for (let i in number[y]){
                if (number[y][i] != 0) {
                    temp[y].push(number[y][i]);
                }
            }
            let min = 4 - temp[y].length;
            /*console.log(`Ini min ke ${min} = `,min);*/
            if (temp[y].length < 4) {
                /*console.log(`Ini y ke ${y} = `,temp[y].length);*/
                for (let z = 0;z < min; z++){
                    /*console.log(`Ini z ke ${z} = `,z);*/
                    temp[y].push(0);
                }
            }
            
            for (let i =0; i < 3; i++){
                if (temp[y][i] == temp[y][i+1]) {
                    temp[y][i] += temp[y][i+1];
                    temp[y][i+1] = 0;
                }
            }
            for (let i in temp[y]) {
                if (temp[y][i] != 0) {
                    temp2[y].push(temp[y][i]);
                }
            }
            let min2 = 4 - temp2[y].length;
            if (temp2[y].length < 4) {
                for (let z = 0;z < min2; z++){
                    temp2[y].push(0);
                }
            }           
            final.push(temp2[y]);
        }

        let count_num = 0;
        let temp_array = [[],[],[],[]];
        let j = 0;
        let Number_Temp = [];
        
        let state = 0;
        for (let d = 0; d < 4;d++) {
            for (let x = 0; x < 4;x++) {
                if (number[d][x]==final[d][x]){
                    state +=1;
                }
            }
        }
        console.log(state);
        if (state != 16) {
            for (let i = 0; i < 4; i++) {
                for (let y = 0; y < 4; y++) {
                    Number_Temp.push(final[i][y]);
                }   
            }
            while (count_num == 0){
                let ran_index = Math.floor((Math.random() * 16)+0);
                if (Number_Temp[ran_index] == 0){
                    Number_Temp[ran_index] = prob();
                    count_num+=1;
                }
                
                if (count_num == 1) {
                    for (let i = 0; i < 16; i++) {
                        temp_array[0+j].push(Number_Temp[i]);
                        if (temp_array[0+j].length == 4) {
                            j += 1;
                        }
                    }
                    final = temp_array; 
                
                    break;
                }
            }
        }else{
            console.log('blok');
        }
        
        for (let i = 0; i < 4; i++) {
                for (let y = 0; y < 4; y++) {
                    Number_Temp.push(final[i][y]);
                }   
            }
        for (let i = 0; i < 16; i++) {
            document.getElementById(i+1).innerHTML = ``;        
        }
        for (let i = 0; i < 16; i++) {
            if (Number_Temp[i] > 0 ) {
                document.getElementById(i+1).innerHTML = 
                    `<div class='active-box' align='center' id='x${Number_Temp[i]}' style="font-size:50px;">${Number_Temp[i]}</div>`;        
            }
            
        }
        
        console.log("Ini final2 - ",final);
        
        return final;
    }
/*---------------------------------------------------------------------------------------------*/
/*---------------------------------------------------------------------------------------------*/
/*---------------------------------------------------------------------------------------------*/
/*---------------------------------------------------------------------------------------------*/
    function GeserBawah() {
        let temp = [[],[],[],[]]
        let temp2 = [[],[],[],[]]
        let final = []
        let trans = [[],[],[],[]]
        let compare = number;
        for (let i = 0;i < 4;i++){
            for (let v = 0; v < 4;v++){
                trans[i].push(number[v][i]);
                console.log(trans[v]);        
            }
        }
        number = trans;
        console.log(trans);        
        for (let y = 0; y < 4; y++) {
            /*for (let i in number[y].reverse()){
                if (number[y] != 0) {
                    temp[y].push(0);
                }
            }*/
            for (let i = (number[y].length - 1); i >= 0; i--){
                if (number[y][i] != 0) {
                    temp[y].push(number[y][i]);
                }
            }
            let min = 4 - temp[y].length;
            /*console.log(`Ini min ke ${min} = `,min);*/
            if (temp[y].length < 4) {
                /*console.log(`Ini y ke ${y} = `,temp[y].length);*/
                for (let z = 0;z < min; z++){
                    /*console.log(`Ini z ke ${z} = `,z);*/
                    temp[y].push(0);
                }
            }
            
            for (let i =0; i < 3; i++){
                if (temp[y][i] == temp[y][i+1]) {
                    temp[y][i] += temp[y][i+1];
                    temp[y][i+1] = 0;
                }
            }
            for (let i in temp[y]) {
                if (temp[y][i] != 0) {
                    temp2[y].push(temp[y][i]);
                }
            }
            let min2 = 4 - temp2[y].length;
            if (temp2[y].length < 4) {
                for (let z = 0;z < min2; z++){
                    temp2[y].push(0);
                }
            }           
            final.push(temp2[y].reverse());
        }
        for (let i = 0;i < 4;i++){
            for (let v = 0; v < 4;v++){
                trans[i][v] = final[v][i];
                console.log(trans[v]);        
            }
        }
        final = trans;
        console.log(trans);  

        let count_num = 0;
        let temp_array = [[],[],[],[]];
        let j = 0;
        let Number_Temp = [];
        let state = 0;
        for (let d = 0; d < 4;d++) {
            for (let x = 0; x < 4;x++) {
                if (compare[d][x]==final[d][x]){
                    state +=1;
                }
            }
        }
        
        if (state != 16) {
            for (let i = 0; i < 4; i++) {
                for (let y = 0; y < 4; y++) {
                    Number_Temp.push(final[i][y]);
                }   
            }
            
            while (count_num == 0){
                let ran_index = Math.floor((Math.random() * 16)+0);
                if (Number_Temp[ran_index] == 0){
                    Number_Temp[ran_index] = prob();
                    count_num+=1;
                }
                
                if (count_num == 1) {
                    for (let i = 0; i < 16; i++) {
                        temp_array[0+j].push(Number_Temp[i]);
                        if (temp_array[0+j].length == 4) {
                            j += 1;
                        }
                    }
                    final = temp_array; 
                
                    break;
                }
            }
        }else{
            console.log('blok');
        }
        
        
        for (let i = 0; i < 4; i++) {
                for (let y = 0; y < 4; y++) {
                    Number_Temp.push(final[i][y]);
                }   
            }
        for (let i = 0; i < 16; i++) {
            document.getElementById(i+1).innerHTML = ``;        
        }
        for (let i = 0; i < 16; i++) {
            if (Number_Temp[i] > 0 ) {
                document.getElementById(i+1).innerHTML = 
                `<div class='active-box' align='center' id='x${Number_Temp[i]}' style="font-size:50px;">${Number_Temp[i]}</div>`;           
            }
            
        }
        
        console.log("Ini final2 - ",final);
        
        return final;
    }

    function GeserAtas() {
        let temp = [[],[],[],[]]
        let temp2 = [[],[],[],[]]
        let final = []
        let trans = [[],[],[],[]]
        let compare = number;
        for (let i = 0;i < 4;i++){
            for (let v = 0; v < 4;v++){
                trans[i].push(number[v][i]);
                console.log(trans[v]);        
            }
        }
        number = trans;
        for (let y = 0; y < 4; y++) {
            /*for (let i in number[y].reverse()){
                if (number[y] != 0) {
                    temp[y].push(0);
                }
            }*/
            for (let i in number[y]){
                if (number[y][i] != 0) {
                    temp[y].push(number[y][i]);
                }
            }
            let min = 4 - temp[y].length;
            /*console.log(`Ini min ke ${min} = `,min);*/
            if (temp[y].length < 4) {
                /*console.log(`Ini y ke ${y} = `,temp[y].length);*/
                for (let z = 0;z < min; z++){
                    /*console.log(`Ini z ke ${z} = `,z);*/
                    temp[y].push(0);
                }
            }
            
            for (let i =0; i < 3; i++){
                if (temp[y][i] == temp[y][i+1]) {
                    temp[y][i] += temp[y][i+1];
                    temp[y][i+1] = 0;
                }
            }
            for (let i in temp[y]) {
                if (temp[y][i] != 0) {
                    temp2[y].push(temp[y][i]);
                }
            }
            let min2 = 4 - temp2[y].length;
            if (temp2[y].length < 4) {
                for (let z = 0;z < min2; z++){
                    temp2[y].push(0);
                }
            }           
            final.push(temp2[y]);
        }
        for (let i = 0;i < 4;i++){
            for (let v = 0; v < 4;v++){
                trans[i][v] = final[v][i];
                console.log(trans[v]);        
            }
        }
        final = trans;

        let count_num = 0;
        let temp_array = [[],[],[],[]];
        let j = 0;
        let Number_Temp = [];
        let state = 0;
        for (let d = 0; d < 4;d++) {
            for (let x = 0; x < 4;x++) {
                if (compare[d][x]==final[d][x]){
                    state +=1;
                }
            }
        }
        console.log(state);
        if (state != 16) {
            for (let i = 0; i < 4; i++) {
                for (let y = 0; y < 4; y++) {
                    Number_Temp.push(final[i][y]);
                }   
            }
            while (count_num == 0){
                let ran_index = Math.floor((Math.random() * 16)+0);
                if (Number_Temp[ran_index] == 0){
                    Number_Temp[ran_index] = prob();
                    count_num+=1;
                }
                
                if (count_num == 1) {
                    for (let i = 0; i < 16; i++) {
                        temp_array[0+j].push(Number_Temp[i]);
                        if (temp_array[0+j].length == 4) {
                            j += 1;
                        }
                    }
                    final = temp_array; 
                
                    break;
                }
            }
        }else{
            console.log('blok');
        }
        
        for (let i = 0; i < 4; i++) {
                for (let y = 0; y < 4; y++) {
                    Number_Temp.push(final[i][y]);
                }   
            }
        for (let i = 0; i < 16; i++) {
            document.getElementById(i+1).innerHTML = ``;        
        }
        for (let i = 0; i < 16; i++) {
            if (Number_Temp[i] > 0 ) {
                document.getElementById(i+1).innerHTML = 
                `<div class='active-box' align='center' id='x${Number_Temp[i]}' style="font-size:50px;">${Number_Temp[i]}</div>`;               
            }
            
        }
        
        console.log("Ini final2 - ",final);
        
        return final;
    }
    /ini To buat arah gerak/
    let CommandGeser = document.getElementById('body');
    CommandGeser.addEventListener('keydown', (event) => {
        console.log(event.key);
        if (event.key == 'a'||event.key == 'ArrowLeft'||event.key == 'A') {
            console.log(`masuk ${event.code}`);
            console.log("KIRI");
            number = GeserKiri();
            FontChnager();
        }else if (event.key == 'w'||event.key == 'ArrowUp'||event.key == 'W') {
            console.log(`masuk ${event.code}`);
            console.log("ATAS");
            number = GeserAtas();
            FontChnager();
        }else if (event.key == 'd'||event.key == 'ArrowRight'||event.key == 'D') {
            console.log(`masuk ${event.code}`);
            console.log("KANAN");
            number = GeserKanan();
            FontChnager();
        }else if (event.key == 's'||event.key == 'ArrowDown'||event.key == 'S') {
            console.log(`masuk ${event.code}`);
            console.log("BAWAH");
            number = GeserBawah();
            FontChnager();
        }
    });





document.addEventListener('touchstart', handleTouchStart, false);        
document.addEventListener('touchmove', handleTouchMove, false);

var xDown = null;                                                        
var yDown = null;

function getTouches(evt) {
  return evt.touches ||             // browser API
         evt.originalEvent.touches; // jQuery
}                                                     
                                                                         
function handleTouchStart(evt) {
    const firstTouch = getTouches(evt)[0];                                      
    xDown = firstTouch.clientX;                                      
    yDown = firstTouch.clientY;                                      
};                                                
                                                                         
function handleTouchMove(evt) {
    if ( ! xDown || ! yDown ) {
        return;
    }

    var xUp = evt.touches[0].clientX;                                    
    var yUp = evt.touches[0].clientY;

    var xDiff = xDown - xUp;
    var yDiff = yDown - yUp;
                                                                         
    if ( Math.abs( xDiff ) > Math.abs( yDiff ) ) {/*most significant*/
        if ( xDiff > 0 ) {
            number = GeserKiri();
            FontChnager();
            /* right swipe */ 
        } else {
            number = GeserKiri();
            FontChnager();
            /* left swipe */
        }                       
    } else {
        if ( yDiff > 0 ) {
            number = GeserAtas();
            FontChnager();
            /* down swipe */ 
        } else {
            number = GeserBawah();
            FontChnager();
            /* up swipe */
        }                                                                 
    }
    /* reset values */
    xDown = null;
    yDown = null;                                             
};
</script>


</html>