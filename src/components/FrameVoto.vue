<template>
  <div class="box">
    
    <div class="social_network">
        <div class="line_1 theme_line">
            <div class="special_box">
                <div class="social_image">
                    <img src="../assets/opinion.jpg" class="images" alt="image">
                </div>
                <div class="group_data">
                    <div class="name_face">Lorem ipsum dolor</div>
                    <div class="description">nec dignissim diam</div>
                </div>
            </div>
            <div class="story_1">
                Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec iaculis mauris a dolor rhoncus scelerisque.
            </div>
            <div class="story_2">
                Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec iaculis mauris a dolor rhoncus scelerisque. Donec fermentum vitae leo et lacinia. Donec ex mauris, tempus eu sapien nec, varius ultricies ligula. Nulla a lectus cursus, luctus est vel, lacinia augue. Phasellus non velit at ante bibendum tempor. Pellentesque ac nibh a mi sodales blandit. Quisque varius rhoncus tincidunt. Proin sit amet ultrices diam. Suspendisse rhoncus magna ut lorem ornare auctor. Mauris ullamcorper ultricies ultricies. Aenean at auctor arcu.
Nam vulputate quam magna, sit amet finibus eros euismod in.
            </div>
        </div>
        <div class="line_2 theme_line">
            <div class="special_box">
                <div class="social_image">
                    <img src="../assets/opinion.jpg" class="images" alt="image">
                </div>
                <div class="group_data">
                    <div class="name_face">Lorem ipsum dolor</div>
                    <div class="description">nec dignissim diam</div>
                </div>
            </div>
            <div class="story_1">
                Lorem ipsum dolor sit amet, consectetur adipiscing elit.
            </div>
            <div class="story_2">
                Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec iaculis mauris a dolor rhoncus scelerisque. Donec fermentum vitae leo et lacinia. Donec ex mauris, tempus eu sapien nec, varius ultricies ligula. Nulla a lectus cursus, luctus est vel, lacinia augue. Phasellus non velit at ante bibendum tempor. Pellentesque ac nibh a mi sodales blandit. Quisque varius rhoncus tincidunt. Proin sit amet ultrices diam.
            </div>
        </div>
        <div class="line_3 theme_line">
            <div class="special_box">
                <div class="social_image">
                    <img src="../assets/opinion.jpg" class="images" alt="image">
                </div>
                <div class="group_data">
                    <div class="name_face black_text_1">Lorem ipsum dolor</div>
                    <div class="description black_text_2">nec dignissim diam</div>
                </div>
            </div>
            <div class="story_1 black_text_1">
                Lorem ipsum dolor sit amet, consectetur adipiscing elit.
            </div>
            <div class="story_2 black_text_2">
                Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec iaculis mauris a dolor rhoncus scelerisque. Donec fermentum vitae leo et lacinia. Donec ex mauris, tempus eu sapien nec, varius ultricies ligula. Nulla a lectus cursus, luctus est vel, lacinia augue. Phasellus non velit at ante bibendum tempor. Pellentesque ac nibh a mi sodales blandit. Quisque varius rhoncus tincidunt.
            </div>
        </div>
        <div class="line_4 theme_line">
            <div class="special_box">
                <div class="social_image">
                    <img src="../assets/opinion.jpg" class="images" alt="image">
                </div>
                <div class="group_data">
                    <div class="name_face black_text_1">Lorem ipsum dolor</div>
                    <div class="description black_text_2">nec dignissim diam</div>
                </div>
            </div>
            <div class="story_1 black_text_1">
                Lorem ipsum dolor sit amet, consectetur adipiscing elit.
            </div>
            <div class="story_2 black_text_2">
                Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec iaculis mauris a dolor rhoncus scelerisque. Donec fermentum vitae leo et lacinia. Donec ex mauris, tempus eu sapien nec, varius ultricies ligula. Nulla a lectus cursus, luctus est vel, lacinia augue. Phasellus non velit at ante bibendum tempor. Pellentesque ac nibh a mi sodales blandit. Quisque varius rhoncus tincidunt. Proin sit amet ultrices diam.
            </div>
        </div>
        <div class="line_5 theme_line">
            <div class="special_box">
                <div class="social_image">
                    <img src="../assets/opinion.jpg" class="images" alt="image">
                </div>
                <div class="group_data">
                    <div class="name_face">Lorem ipsum dolor</div>
                    <div class="description">nec dignissim diam</div>
                </div>
            </div>
            <div class="story_1">
                Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec iaculis mauris a dolor rhoncus scelerisque.
            </div>
            <div class="story_2">
                Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec iaculis mauris a dolor rhoncus scelerisque. Donec fermentum vitae leo et lacinia. Donec ex mauris, tempus eu sapien nec, varius ultricies ligula. Nulla a lectus cursus, luctus est vel, lacinia augue. Phasellus non velit at ante bibendum tempor. Pellentesque ac nibh a mi sodales blandit. Quisque varius rhoncus tincidunt. Proin sit amet ultrices diam. Suspendisse rhoncus magna ut lorem ornare auctor. Mauris ullamcorper ultricies ultricies. Aenean at auctor arcu.
Nam vulputate quam magna, sit amet finibus eros euismod in.
            </div>
        </div>
    </div>
    
  </div>
</template>
<script>
export default {
    data() {
        return{
            
        };
    },
    methods: {
        
    }
};
</script>
<style scoped>
@media screen and (min-width : 769px){
.box{
    display: block;
    padding:50px;
    margin: 10px;
}
.social_network {
    display: grid;
    grid-template-columns: repeat(4, 1fr);
    grid-template-rows: repeat(4, 1fr);
    grid-column-gap: 20px;
    grid-row-gap: 20px;
}
.theme_line{
    box-shadow:
    2.8px 2.8px 2.2px rgba(0, 0, 0, 0.02),
    6.7px 6.7px 5.3px rgba(0, 0, 0, 0.028),
    12.5px 12.5px 10px rgba(0, 0, 0, 0.035),
    22.3px 22.3px 17.9px rgba(0, 0, 0, 0.042),
    41.8px 41.8px 33.4px rgba(0, 0, 0, 0.05),
    100px 100px 80px rgba(0, 0, 0, 0.07);
}
.theme_line>div{
    margin: 10px;
}
.line_1 { 
    background-color: #733FC7;
    padding: 20px;
    border: 0px solid black;
    border-radius: 15px;
    grid-area: 1 / 1 / 3 / 3;
}
.line_2 { 
    background-color: #49556A;
    padding: 20px;
    border: 0px solid black;
    border-radius: 15px;
    grid-area: 1 / 3 / 3 / 4; 
}
.line_3 { 
    background-color: #FFFFFF;
    padding: 20px;
    border: 0px solid black;
    border-radius: 15px;
    grid-area: 1 / 4 / 5 / 5; 
}
.line_4 { background-color: #FEFEFE;
    padding: 20px;
    border: 0px solid black;
    border-radius: 15px;
    grid-area: 3 / 1 / 5 / 2; 
}
.line_5 { background-color: #19202E;
    padding: 20px;
    border: 0px solid black;
    border-radius: 15px;
    grid-area: 3 / 2 / 5 / 4; 
}
.special_box{
    display: flex;
    align-content: center;
}
.social_name{
    width: 20%;
}
.group_data{
    width: 80%;
    padding: 10px;
    font-size: 15px;
    font-family: Arial, Helvetica, sans-serif;
}
.name_face{
    font-weight: 900;
    color: rgba(255, 255, 255, 0.7);
}
.description{
    color: rgba(255, 255, 255, 0.5);
}
.images{
    width: 60px;
    height: 60px;
    border-radius: 100px;
}
.story_1{
    font-family: Arial, Helvetica, sans-serif;
    font-size: 22px;
    font-weight: 900;
    color: white;
}
.story_2{
    font-family: Arial, Helvetica, sans-serif;
    font-size: 12px;
    color: rgba(255, 255, 255, 0.5);
    line-height: 20px;
}
.black_text_1{
    color: #19202E !important;
}
.black_text_2{
    color: rgba(25, 32, 46, 0.7)!important;
}

}

@media (max-width: 768px) {
.box{
    display: block;
    padding:50px;
    margin: 10px;
}
.social_network {
    display: grid;
    grid-template-columns: repeat(1, 1fr);
    grid-template-rows: repeat(1, 1fr);
    grid-column-gap: 5px;
    grid-row-gap: 35px;
}
.theme_line{
    box-shadow:
    2.8px 2.8px 2.2px rgba(0, 0, 0, 0.02),
    6.7px 6.7px 5.3px rgba(0, 0, 0, 0.028),
    12.5px 12.5px 10px rgba(0, 0, 0, 0.035),
    22.3px 22.3px 17.9px rgba(0, 0, 0, 0.042),
    41.8px 41.8px 33.4px rgba(0, 0, 0, 0.05),
    100px 100px 80px rgba(0, 0, 0, 0.07);
}
.theme_line>div{
    margin: 10px;
}
.line_1 { 
    background-color: #733FC7;
    padding: 20px;
    border: 0px solid black;
    border-radius: 15px;
    /* grid-area: 1 / 1 / 3 / 3; */
}
.line_2 { 
    background-color: #49556A;
    padding: 20px;
    border: 0px solid black;
    border-radius: 15px;
    /* grid-area: 1 / 3 / 3 / 4;  */
}
.line_3 { 
    background-color: #FFFFFF;
    padding: 20px;
    border: 0px solid black;
    border-radius: 15px;
    /* grid-area: 1 / 4 / 5 / 5;  */
}
.line_4 { background-color: #FEFEFE;
    padding: 20px;
    border: 0px solid black;
    border-radius: 15px;
    /* grid-area: 3 / 1 / 5 / 2;  */
}
.line_5 { background-color: #19202E;
    padding: 20px;
    border: 0px solid black;
    border-radius: 15px;
    /* grid-area: 3 / 2 / 5 / 4;  */
}
.special_box{
    display: flex;
    align-content: center;
}
.social_name{
    width: 20%;
}
.group_data{
    width: 80%;
    padding: 10px;
    font-size: 15px;
    font-family: Arial, Helvetica, sans-serif;
}
.name_face{
    font-weight: 900;
    color: rgba(255, 255, 255, 0.7);
}
.description{
    color: rgba(255, 255, 255, 0.5);
}
.images{
    width: 60px;
    height: 60px;
    border-radius: 100px;
}
.story_1{
    font-family: Arial, Helvetica, sans-serif;
    font-size: 22px;
    font-weight: 900;
    color: white;
}
.story_2{
    font-family: Arial, Helvetica, sans-serif;
    font-size: 12px;
    color: rgba(255, 255, 255, 0.5);
    line-height: 20px;
}
.black_text_1{
    color: #19202E !important;
}
.black_text_2{
    color: rgba(25, 32, 46, 0.7)!important;
}
}
</style>