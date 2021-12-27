<script>
    let k = 0;
    function viewInfo(){
        k= k+1;
        if(k==1){
            document.getElementById("tiosInfoHolderID").style.display="block";
            document.getElementById("tiosInfo").style.display="flex";

            document.getElementById("ssilka").style.display="block";
            document.getElementById("btnIntiosInfoHolder").style.display="block";
        }
        else{
            k=0;
            document.getElementsByClassName("tiosInfoHolder").display="none";
            document.getElementById("tiosInfo").style.display="none";
            document.getElementById("machinesHolderID").style.display="none";
            document.getElementById("ssilka").style.display="none";
            document.getElementById("btnIntiosInfoHolder").style.display="none";
            k1 = 0;

        }
    }
    let k1 = 0;
    function viewMachines(){
        k1=k1+1;
        if(k1==1){
            document.getElementById("machinesHolderID").style.display="block";

        }
        else {
            k1=0;
            document.getElementById("machinesHolderID").style.display="none";
        }
    }
</script>
<div class="Tios">
    <div id="textContainerTios">
        <h1 id="Tios">Норвежские <br> Лесные</h1>
        <p id="TiosTextUnderHeader"><br><br></p>
        <button class="PressMe" on:click={viewInfo}>Подробнее</button>
    </div>
    <img class="photo-Tios" src="images/norv.jpg" alt="Технологии информационных
образовательных систем">
</div>
<div class="tiosInfoHolder" id="tiosInfoHolderID">
    <p id="tiosInfo">
        Данная порода похожа на маленьких рысей, что неудивительно – ведь норвежские лесные кошки произошли от диких котов. Это необычайно выносливые животные, обладающие уникальными качествами – ловкостью и умением приспосабливаться к практически любым условиям.
        <br>
        «Норвежки» – животные свободолюбивые, энергичные и храбрые, любят высоту и не боятся незнакомых людей. Своих хозяев уважают, но ко всем домочадцам относятся одинаково, «любимцев» себе не выбирают. Обожают играть с маленькими детьми. Не терпят «телячьих нежностей» и не позволяют себя тискать. На коленях сидеть не любят, предпочитая просто находиться рядом с людьми. Это необычайно терпеливая и спокойная порода, они могут с холодным равнодушием выдержать любой контакт, будь то ребенок или животное. Также норвежские лесные кошки очень верные и преданные компаньоны.
        <br>
        Несмотря свой немного грозный «рысий» вид, это совершенно миролюбивые и безобидные создания, отличающиеся послушным и мягким характером. Об этих созданиях можно сказать, что у них от природы хорошие манеры. Очень любят гулять и сидеть на высоте, будь то дерево или шкаф.
        <br>
        «Норвежцы» умны и сообразительны, если им что-то не по нраву – они просто «гордо удалятся». И, несмотря на свою терпеливость и безвредность, за себя постоять они умеют. Одинаково комфортно чувствуют себя и в домашних условиях, и на воле. Причина тому – их потрясающая и редкая особенность приспосабливаться ко всему.
        <br>
        Когда именно появилась первая норвежская лесная кошка – точной информации нет. За историей происхождения этой породы стоит немало легенд.
        <br>
        Если верить одной из них, в Скандинавию такая кошка была впервые завезена еще в IX веке – матросы использовали «норвежцев» в качестве крысоловов. А чтобы развить в них желание истреблять грызунов, животных почти не кормили, отсюда и отличные охотничьи навыки.
        <br>
        Другая версия гласит, что впервые эти кошки были замечены в лесах Норвегии (отсюда и название), недалеко от поселений. Люди были настолько потрясены красотой их красотой, что решили приручить.
        <br>
        Что касается современной истории норвежских лесных кошек, то до 30-х годов прошлого века эти животные жили на фермах в качестве охотников на мелких грызунов. Но в 1934 году их роскошным внешним видом заинтересовались питомники, а уже в 1938 году на выставке в Осло впервые была представлена «норвежка» красно-белого окраса. Однако официальную регистрацию от организации FIF порода «норвежская лесная» получила только в 1977 году… а король Норвегии за красоту наградил ее статусом «порода страны».
        <br>

        Хотите узнать больше? - <a href="https://cattish.ru/breed/norsk-skogkatt/">Смотрите здесь!</a> <br>
    </p>

</div>
<style>
    .Tios{
        background-color: white;
        display: -webkit-flex;
        display: -ms-flex;
        display: flex;
        align-items: center;
        max-width: 80%;
        margin-left: 10%;
    }
    .photo-Tios{
        margin-left: auto;
        margin-right: 5px;
        margin-bottom: 5px;
        margin-top: 5px;
        border-radius: 10px;
        height: auto;
        width: 100%;
        max-width: 180px;
    }
    #Tios{
        font-size: 3vw;
        font-family: Gilroy;
        margin-bottom: auto;
        margin-left: 5px;
    }
    #TiosTextUnderHeader{
        font-size: 2.5vw;
        display: block;
        margin-left: 5px;
    }
    #textContainerTios{
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
    .tiosInfoHolder{
        max-width: 100%;
    }
    #tiosInfo{
        display: none;
        margin:10px;
        font-size: 3.5vw;
        word-break: break-all;
    }
    #tiosInfoHolderID{
        display: none;
    }
    #3dPrinterText{
        margin:10px;
        font-size: 3.5vw;
        word-break: break-all;
    }
    .machineryPics{
        margin: auto;
        border-radius: 10px;
        height: auto;
        width: 100%;
    }
    #machinesHolderID{
        display: none;
    }
    #ssilka{
        margin-left: 10px;
    }
    #btnIntiosInfoHolder{

    }
    .spacerSmall{
        padding: 20px;
    }
    #laser{
        margin:10px;
        font-size: 3.5vw;
        word-break: break-all;
    }
    #tokar{
        margin:10px;
        font-size: 3.5vw;
        word-break: break-all;
    }
    #ultrafio{
        margin:10px;
        font-size: 3.5vw;
        word-break: break-all;
    }
    #diyprinter{
        margin:10px;
        font-size: 3.5vw;
        word-break: break-all;
    }
    #raspberry{
        margin:10px;
        font-size: 3.5vw;
        word-break: break-all;
    }
    #cyclon{
        margin:10px;
        font-size: 3.5vw;
        word-break: break-all;
    }
    #generator{
        margin:10px;
        font-size: 3.5vw;
        word-break: break-all;
    }
    #hacker{
        margin:10px;
        font-size: 3.5vw;
        word-break: break-all;
    }
    #platform{
        margin:10px;
        font-size: 3.5vw;
        word-break: break-all;
    }

</style>