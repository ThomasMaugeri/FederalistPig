<Script>


</Script>

<template>
<div class="header">

    <div class="leftheader">
        <span>federalist</span>
        <span>pig</span>
</div>

     <div class="rightheader">
        <ul>
            <li ><a href="" class="menus">menu</a></li>
            <li class="package"><a href="">catering</a></li>
            <li class="zone"><a href="">locations</a></li>
            <li class="product"><a href="">bbq box</a></li>
            <li class="club"><a href="">supper club</a></li>
            <li class="promo"><a href="">giftcard</a></li>
            <li class="order"><a href="">online order</a></li>

        </ul>
    </div>
</div>


</template>  

<style scoped lang="scss">
.header{
    width: 100%;
    display: flex;
    background-color:#ffd700;
    height:93px;
    text-transform: uppercase;
    .leftheader{
        width: 50%;
        display: flex;
        flex-direction: column;
        justify-content: center;
    }
    .rightheader{
        width: 50%;
        display:flex;
        align-items:center;
        justify-content: flex-end;
        ul{
            display:flex ;
            gap:30px;
            list-style-type: none;

            a{
                text-decoration: none;
                color:black;
            }

            
        }
    }
}


</style>