<template>
<div class="home overflow">
    <div class="title warp flex-between">
        <img class="icon-back" src="../../assets/images/icon_back.png" alt="">
        <div class="font-16 title-text">Local screencast</div>
        <div class="icon-back"> </div>
    </div>
    <div class="search warp">
        <input class="search-input" placeholder="search" type="text">
        <img class="icon-size" src="../../assets/images/icon_search.png" alt="">
    </div>
    <div class="tip  warp mr-t-37">
        <img class="img-sit" src="../../assets/images/sit.png" alt="">
        <div class="tip-text font-20">Mirror guide</div>
        <div class="tip-text font-10">common problem</div>
    </div>
    <div class="swiper mr-t-37">
        <div class="item">
            <img class="item-img item-1" src="../../assets/images/icon_picture.png" alt="">
            <div class="font-15  mr-t-18">Picture</div>
            <div class="font-10  mr-t-10">Local screencast</div>
        </div>
        <div class="item">
            <img class="item-img item-2" src="../../assets/images/icon_book.png" alt="">
            <div class="font-15 mr-t-18">Picture</div>
            <div class="font-10 mr-t-10">Local screencast</div>
        </div>
        <div class="item">
            <img class="item-img item-3" src="../../assets/images/icon_picture.png" alt="">
            <div class="font-15 mr-t-18">Picture</div>
            <div class="font-10 mr-t-10">Local screencast</div>
        </div>
        <div class="item">
            <img class="item-img item-1" src="../../assets/images/icon_picture.png" alt="">
            <div class="font-15 mr-t-18">Picture</div>
            <div class="font-10  mr-t-10">Local screencast</div>
        </div>
    </div>
    <div class="foot  warp mr-t-37">
        <div class="foot-top">
            <img src="../../assets/images/yuan1.png" alt="">
            <div class="foot-text">
                <div class="text-top">
                    Screen mirroring aaaaaa
                </div>
                <div class="text-top">
                    Mobile screen sharing to TV
                </div>
            </div>
        </div>
        <div class="foot-bottom">
            <div class="button-item"><img src="" alt="">Time out</div>
            <div class="button-item"><img src="" alt="">End</div>
        </div>
    </div>
</div>
</template>

<style scoped>
.home {
    height: 100vh;
    box-sizing: border-box;
    padding: 2.4rem 0;
    background-color: #dbcbf7;
}

.title {
    padding: 1.8rem 0;
}

.title-text {
    color: #445068;
    font-weight: 700;
}

.icon-back {
    width: 2.1rem;
    height: 2.1rem;

}

.search {
    display: flex;
    background-color: #efefff;
    box-sizing: border-box;
    border-radius: 2.3rem;
    padding: 2.2rem 2rem;
}

.search-input {
    width: 100%;
    background-color: #efefff;
    border: none;
    outline: none;
    font-size: 1.6rem;
}

input:-moz-placeholder {

    color: #999;

}

input:-ms-input-placeholder {

    color: #999;

}

input::-webkit-input-placeholder {

    color: #999;

}

.tip {
    background-color: #eceaff;
    border-radius: 5rem;
    position: relative;
    padding: 2.8rem 0;
    display: flex;
    flex-direction: column;
    gap: 0.4rem;
}

.img-sit {
    height: 11.4rem;
    width: 9.5rem;
    position: absolute;
    left: 2.2rem;
    bottom: 0;
}

.tip-text {
    padding-left: 13.2rem;
}
.swiper{
    /* width: 37.5rem; */
    overflow-x: scroll;
    padding:0 2.5rem;
    display: flex;
    gap: 0 1.6rem ;
}
.item:nth-child(1){
    background-color: #7469fb;
}
.item:nth-child(2){
    background-color: white;
}
.item:nth-child(3){
    background-color: #eceaff;
}
.item:nth-child(4){
    background-color: #7469fb;
}
.item{
    min-width: 13.4rem;
    padding: 2.7rem 0;
    text-align: center;
    border-radius: 3rem;
}

.item-img{
    width: 6.2rem;
    height: 6.2rem;
    padding: 1.6rem;
    box-sizing: border-box;
    border-radius: 1.5rem;
    
}
.item-1{
    
    background-color: #d2d3ff;
}
.item-2{
background-color: #ffebdc;
}
.item-3{
background-color: #eceaff;
}
</style>
