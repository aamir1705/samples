<template>
  <div class="everything-under">
    <div style="background-color:#98DBC6">
        <p>
            EVERYTHING UNDER <br><strong>399 </strong>  
        </p>
    </div>
    <div style="background-color:#5BC8AC ">
        <p>
        EVERYTHING UNDER <br>
        <strong>599</strong>  
        </p>
    </div>
    <div style="background-color:#ECD72A">
        <p>
        EVERYTHING UNDER <br><strong>799</strong>  
        </p>
    </div>
    <div style="background-color:#F18D9E">
        <p>
        EVERYTHING UNDER <br><strong>999</strong>  
        </p>
    </div>
    
  </div>
</template>

<script>
export default {

}
</script>
    
<style lang="scss">
    .everything-under{
        display: grid;
        grid-template-columns: repeat(2,1fr);
        grid-gap: 2em 2em;
        height:1080px;
        width: 100%;
        padding: 2em;
        

        div{
            display: flex;
            justify-content: center;
            align-items: center;
            
            color: white;
            font-size: 3em;
            height: 100%;
            width: 100%;
            // justify-content: center
            margin: 0 auto;
            p{
                text-align: center;
            }
        }

    }
    @media screen and (max-width: 600px){
        .everything-under{
            grid-template-columns: repeat(1,1fr);
            height: auto;
        }

    }
</style>