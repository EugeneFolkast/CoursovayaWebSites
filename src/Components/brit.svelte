<script>
    let k = 0;
    function viewInfo(){
        k= k+1;
        if(k==1){
            document.getElementById("iotInfo").style.display="block";
        }
        else{
            k=0;
            document.getElementById("iotInfo").style.display="none";
        }
    }
</script>
<div class="IoT">
    <div id="textContainerIoT">
        <h1 id="IoT">Британские <br> короткошёрстные</h1>
        <p id="IoTTextUnderHeader"><br><br> </p>
        <button class="PressMe" on:click={viewInfo}>Подробнее</button>
    </div>
    <img class="photo-IoT" src="images/brit.jpg" alt="Британская кошка">
</div>
<div class="iotInfoHolder">
    <p id="iotInfo">
        «Британцы» узнаваемы по крупному приземистому телосложению и мягкой плюшевой шерстке. Они растут до четырех лет и достигают веса ≈6±2 килограмм (хотя внешне выглядят намного массивнее и тяжелее).
        <br>
        Эта порода не отличается грациозностью и практически не умеет лазать по деревьям, зато у нее чуткий слух и поразительные способности в отлове мышей и даже крыс.
        <br>
        Впервые стандарты британской короткошерстной породы были описаны Гаррисоном Уэйром в 1880 году. Считается, что эталоном для описания он выбрал знаменитого Чеширского кота.
        <br>
        Окрас у «британцев» не имеет четко прописанных стандартов. Самыми распространенными считается голубой (серый) и серебристый табби, но возможных вариантов расцветок этой породы насчитывается больше шестидесяти (и это абсолютный рекорд среди кошачьих пород). Во многом такое изобилие расцветок связано с активным скрещиванием «британцев» с другими породами в 60-х годах ХХ века (в частности с «персами» и очень похожей французской породой шартрез).
        <br>
        Хотите узнать больше? - <a href="https://cattish.ru/breed/british-shorthair/">Смотрите здесь!</a> <br>
    </p>
</div>
<style>
    .IoT{
        background-color: white;
        display: -webkit-flex;
        display: -ms-flex;
        display: flex;
        align-items: center;
        max-width: 80%;
        margin-left: 10%;
    }
    .photo-IoT{
        margin-left: auto;
        margin-right: 5px;
        margin-bottom: 5px;
        margin-top: 5px;
        border-radius: 10px;
        height: auto;
        width: 100%;
        max-width: 180px;
    }
    #IoT{
        font-size: 3vw;
        font-family: Gilroy;
        margin-bottom: auto;
        margin-left: 5px;
    }
    #IoTTextUnderHeader{
        font-size: 2.5vw;
        display: block;
        margin-left: 5px;
    }
    #textContainerIoT{
        display: block;
        margin-left: 10px;
    }
    .PressMe{
        margin-left: 7px;
        max-width: 100%;
        background-color: rgba(0,217,255,0.58);
        color: black;
        border-radius: 5px;
        font-size: 3vw;
        text-shadow: #333333;
    }
    iotInfoHolder{
        display: flex;
        max-width: 100%;
    }
    #iotInfo{
        display: none;
        margin:10px;
        font-size: 3.5vw;
        word-break: break-all;
    }
</style>