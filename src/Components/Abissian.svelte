<script>
let k = 0;
function viewMediaInfo(){
    k= k+1;
    if(k==1){
    document.getElementById("mediaInfo").style.display="block";
    }
    else{
        k=0;
        document.getElementById("mediaInfo").style.display="none";
    }
}

let k1 = 0;
function viewRadioInfo(){
    k1= k1+1;
    if(k1==1){
        document.getElementById("radioInfo").style.display="block";
    }
    else{
        k1=0;
        document.getElementById("radioInfo").style.display="none";
    }
}
</script>


<div class="qst">
    <p> Какие бывают котики?</p>
</div>

<div class="mediacenter">
    <div id="textContainerMedia">
        <h1 id="mediaHeader">Абиссинская кошка</h1>
        <p id="mediaTextUnderHeader"><br><br> </p>
        <button class="PressMe" on:click={viewMediaInfo}>Подробнее</button>
    </div>
    <img class="photo-media" src="images/abissian.jpg" alt="Изображение котика Абиссианской породы">

</div>
<div class="mediaInfoHolder">
    <p id="mediaInfo">
        Абиссинская порода — это элегантные кошки средних размеров с сильными грациозными телами и длинными стройными лапами. Для этой породы характерны округлая клиновидная форма головы с большими миндалевидными глазами и уши с небольшими кисточками на кончиках. Короткая прилегающая шерсть абиссинской кошки отличается тикингом — смешением цветов на каждом из волосков. Наиболее популярный окрас — «дикий» (ruddy), но также встречаются и другие виды.<br><br>
        Происхождение<br>
        Абиссинская кошка похожа на африканскую дикую — предка домашней кошки. Как именно абиссинская кошка оказалась в Соединенном Королевстве, точно сказать невозможно. Вероятно, в 60-ых годах 19 века ее завезли на континент армейские офицеры из Абиссинии (современной Эфиопии). Первые абиссинские кошки были скрещены с британскими короткошерстными, а позже — с восточными породами. Длинношерстные абиссинские котята обнаруживались в пометах на протяжении многих лет. С 70-х годов этих котят стали относить к отдельной породе, называемой сомалийской.<br>
        Абиссинская кошка достаточно уравновешенное по характеру животное. Это активная, умная и очень любопытная порода. Ей нравится общество человека, она сильно привязывается к семье. Кошки этой породы любят свободное пространство, подвижные игры и подъемы на высоту. Например, им понравятся игры в саду, где кошка сможет взбираться на деревья.<br>
        Хотите узнать больше? - <a href="https://www.purina.ru/cats/cat-breeds/library/abyssinian">Смотрите здесь!</a> <br>
    </p>
</div>

<hr color="#EBEDF0" class="spacer">

<div class="radio">
    <div id="textContainerRadio">
        <h1 id="radioHeader">Шотландская <br> вислоухая </h1>
        <p id="radioTextUnderHeader"><br><br> </p>
        <button class="PressMe" on:click={viewRadioInfo}>Подробнее</button>
    </div>
    <img class="photo-radio" src="images/scotland.jpg" alt="Радио СПбГУТ">
</div>
<div class="radioInfoHolder">
    <p id="radioInfo">
        Данная порода во всем мире именуется как «Scottish Fold», но нам привычней называть их «шотландскими вислоухими».<br>

        Их запоминающийся внешний вид никого не оставляет равнодушным – такого милого котика сразу хочется взять на руки и затискать.<br>

        Эти кошки имеют настолько уникальную внешность, что любая путаница исключается. <br>

        Это необычайно спокойные создания, которые быстро адаптируются в новой обстановке. «Шотландцы» невозмутимы, интеллигентны, послушны и ненавязчивы. Они не станут носиться по дому и лазать по шкафам, а будут держаться ближе к хозяину, устроившись рядышком. Но апатичной эту породу назвать тоже нельзя – поиграть они не откажутся. Пушистый вислоухий комочек с удовольствием будет ловить фантик на ниточке или катать мячик. «Шотландцы» прекрасно уживаются рядом с детьми.

        Если вам нужен питомец, который будет послушно лежать у вас на коленях и довольно мурлыкать на руках, то лучше шотландской вислоухой кошки вам не найти – это настоящий релакс! Это очень нежные, ласковые и потрясающе уравновешенные существа, которые не выносят одиночества – идеальный компаньон для тех, кто любит спокойных животных.

        <br>
        Хотите узнать больше? - <a href="https://cattish.ru/breed/scottish-fold/">Смотрите здесь!</a> <br>
    </p>
</div>

<style>
    .qst{
        font-size: 10px;
        margin-left: 65%;

    }

    .mediacenter{
        background-color: white;
        display: -webkit-flex;
        display: -ms-flex;
        display: flex;
        align-items: center;
        max-width: 80%;
        margin-left: 10%;
    }
    .photo-media{
        margin: 5px 5px 5px auto;
        border-radius: 10px;
        width: 180px;
        height: 130px;
    }
    #mediaHeader{
        font-size: 3vw;
        font-family: Gilroy;
        margin-bottom: auto;
        margin-left: 5px;
    }
    #mediaTextUnderHeader{
        font-size: 2.5vw;
        display: block;
        margin-left: 5px;
    }
    #textContainerMedia{
        display: block;
        margin-left: 10px;
    }
    .mediaInfoHolder{
        display: flex;
        max-width: 100%;
    }
    #mediaInfo{
        display: none;
        margin:10px;
        font-size: 3.5vw;
        word-break: break-all;
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
    .radio{
        background-color: white;
        display: -webkit-flex;
        display: -ms-flex;
        display: flex;
        align-items: center;
        max-width: 80%;
        margin-left: 10%;
    }

    .photo-radio{
        margin-left: auto;
        margin-right: 5px;
        margin-bottom: 5px;
        margin-top: 5px;
        border-radius: 10px;
        height: auto;
        width: 100%;
        max-width: 180px;

    }
    #radioHeader{
        font-size: 2.6vw;
        margin-bottom: auto;
        margin-left: 5px;
    }
    #radioTextUnderHeader{
        font-size: 2.5vw;
        display: block;
        margin-left: 5px;
    }
    #textContainerRadio{
        display: block;
        margin-left: 10px;
    }
    .spacer{
        padding: 15px;
    }
    .radioInfoHolder{
        display: flex;
        max-width: 100%;
    }
    #radioInfo{
        display: none;
        margin:10px;
        font-size: 3.5vw;
        word-break: break-all;
    }
</style>