<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge" refresh="2">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" integrity="sha384-JcKb8q3iqJ61gNV9KGb8thSsNjpSL0n8PARn9HuZOnIxN0hoP+VmmDGMN5t9UJ0Z" crossorigin="anonymous">
    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js" integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js" integrity="sha384-9/reFTGAW83EW2RDu2S0VKaIzap3H66lZH81PoYlFhbGU+6BZp6G7niu735Sk7lN" crossorigin="anonymous"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js" integrity="sha384-B4gt1jrGC7Jh4AgTPSdUtOBvfO8shuf57BaghqFfPlYxofvL8/KUEfYiJOMMV+rV" crossorigin="anonymous"></script>
    <style>
    .pro-che{
                background-color: rgb(174, 244, 249);
            }
    .crd-fst{
                 margin:15px;
                 border:2px solid transparent;
                 border-radius:30px;
                 background-color: aquamarine;
             }
    .crd-fst-desc{
                    width:30vw;
                    padding:20px;
                }
    .img1{
             height:30vw;
             width:30vw;
             margin-left:30rem;
        }
    .img2,.d-block {
             height:20vw;
             width:20vw;
             border:2px solid transparent;
             border-radius:10px;
         }
         .img4{
            height:20vw;
             width:20vw;
             padding: 15px;
             border-radius: 15px;
             margin-top: 5px;
         }
         .img3{
            height:20vw;
            width:20vw;
            padding:15px;
            border: 2px solid rgb(249, 249, 1);
            border-radius: 10px 10px 10px 10px;
            
         }
         .img5 {
            height:15vw;
            width:15vw;
            margin-left:6vw;

         }
    .crd-fst-img1{
                    padding: 5px;
                 }
    .crd-sec{
                background-color:rgb(250, 131, 131);
                border:2px solid transparent;
                border-radius:15px;
                padding:5px;
                margin:10px;
             }
    .crd-sec-img2{
                    padding:10px;
                 }
    .crd-sec-content{
                        padding:10px;
                        
        
        
                    }
    .crd-thrd{
        border:2px solid transparent;
        margin: 10px;
        background-color: rgb(230, 230, 140);
        border-radius: 15px;
    }
    .crd-thrd-desc{
        padding:15px;
    }
    .crd-frth{
        border:2px solid transparent;
        margin: 15px;
        background-color: rgb(181, 147, 212);
        border-radius:15px;
    }
    .crd-frth-img4{
        border-radius:15px;
    }
    .crd-frth-desc{
        margin-left: 15px;
    }
    .sub-card-box-1,.sub-card-box-2,.sub-card-box-3{
        border:2px solid transparent;
        border-radius: 15px;
        background-color: rgb(255, 255, 255);
        margin:10px;
        padding:10px;
        box-shadow: 2px 2px 2px black;

    }
    .btn{ 
        font-size: 13px;
        padding:10px;
    }
    .navigation-bar{
        background-color: black;
        color:white;
        padding: 15px;
    }
    .item1{
        margin-left: 25px;
        padding: 5px;
        
        
    }
    .item1:hover,.login:hover,.sign-in:hover{
        background-color: azure;
        color:black;
        transition: 0.5s;
        border-radius: 10px;
        padding-top: 5px;
        cursor: pointer;
        
    }
    .login,.sign-in{
        position: relative;
        left:60vw;
        margin-left: 10px;
        

    }
    .a3p{border:5px solid white;
    padding:10px;
    border-radius: 25px;
    height:50px;
    width:50px;
    cursor:pointer;
}
.a3p:hover{
    border:5px dotted greenyellow;
    color:greenyellow;
    transition:5s;

}
.sub-cards{
    margin-left:150px ;
}
.sub-card-box3-img,.sub-card-box1-img{
    margin-right: 50px;
}
.sub-card-box2-heading,.sub-card-box1-heading,.sub-card-box3-heading{
    text-decoration: underline;
}
.cardabt-us{
background-color: rgb(26, 25, 25);
color:#ffffff;
font-size: 12px;
}
.hrw{
    border:1px solid gray;
    width: 90%;
}
a{
    text-decoration: none;
    color:white;
}
.abt-us-add{
    text-decoration: underline;
    cursor: pointer;
}
.myimg{
    height:10vh;
    width:5vw;
}
 
    
       
    
    </style>
</head>
<body>
<div class="pro-che">
    <div class="navigation-bar d-flex flex-row">
        <div class="a3p">3p</div>
        <div class="item1" onclick="alert('You are in the home page'+'save earth')">Home</div>
        <div class="item1"><a href="#sectionaboutus">About-us</a></div>
        <div class="item1" onclick="alert('for any feedback or information please contact (abhishekmathur226@gmail.com)')">Contact</div>
        <div class="item1">Join-us</div>
        <div class="login">login</div>
        <div class="sign-in">sign-in</div>
    </div>
    <div class="crd-fst d-flex flex-row justify-content-middle">
        <div class="crd-fst-desc">
            <h1 class="crd-fst-heading">Three pillars of sustainable development</h1>
            <p class="crd-fst-desc">ECOSOC operates at the centre of the UN system's work on all three
            pillars of sustainable development—economic, social and environmental.
            The term sustainability is broadly used to indicate programs, 
            initiatives and actions aimed at the preservation of a particular resource. 
            However, it actually refers to four distinct areas: human, social, economic
            and environmental - known as the four pillars of sustainability.
            Human sustainability</p>
        </div>
         <div class="crd-fst-img1">
            <img src="https://sustrainy.erasmus.site/wp-content/uploads/2021/05/3-pillars-sustainable-economy.png" alt="image-1" class="img1">
         </div>
         
    </div>
        <div class="crd-sec">
            <div class="crd-sec-desc d-flex flex-row">
                 <div class="crd-sec-img2">
                    <img src="https://www.aimsindia.com/wp-content/uploads/2022/06/world-environment.png" alt="img2" class="img2"> 
                </div>
                <div class="crd-sec-content">
                    <h1 class="crd-sec-heading">Enviromental</h1>
                    <p class="crd-sec-txt">Environment can be defined as
                         a sum total of all the 
                         living and non-living elements
                          and their effects that influence 
                          human life. While all living or 
                          biotic elements are animals, 
                          plants, forests, fisheries,
                          and birds, non-living or abiotic elements 
                          include water, land, sunlight, rocks, and air.<br/><br/>he most important thing about global warming is this. Whether humans are responsible for the bulk of climate change is going to be left to the scientists, but it’s all of our responsibility to leave this planet in better shape for the future generations
                           than we found it. – Mike Huckabee</p>
                </div>
            
        </div>
            
        </div>
            <div class="crd-thrd d-flex flex-row justify-content-center">
                <div class="crd-thrd-desc  ">
                    <h1 class="crd-thrd-heading">Economic</h1>
                    <p class="crd-thrd-txt">Economic sustainability refers to balanced growth that is not based on the loss of resources
                         or indebtedness. Economic sustainability can be 
                        achieved through efficient recycling and the use of renewable resources..
                    <br><br>As economic and environmental volatility becomes the new normal, CNT’s Sustainable Economic 
                    Development program is focused on recovery from these related crises. Sustainable Economic Development 
                    is a national initiative built on local economies’ unique assets to address their individual challenges
                     and provide quantifiable real-world benefits. It is a practical, implementable 
                    oolkit that tailors strategies to work for local people, businesses, and institutions.</p>
                </div>
                <div class="crd-thrd-img3 d-flex flex-column justify-content-between ">
                    <img src="https://miro.medium.com/v2/resize:fit:700/1*2NY126ys5C-nnFFKz1ejnQ.jpeg" alt="img3" class="img3"> 
                </div>
            
            </div>
        <div class="crd-frth d-flex flex-row">
            <div class="crd-frth-img4">
                <img src="https://img.freepik.com/premium-vector/people-grow-money-form-flowers-from-hemisphere-planet-colorful-vector-illustration_569417-518.jpg" alt="img4" class="img4"> 
            </div>
            <div class="crd-frth-desc">
                 <h1 class="crd-frth-heading">Social</h1>
                 <p class="crd-frth-txt">Social sustainability is about identifying and managing business impacts, both positive and negative, on people. The quality of a company's relationships and engagement with its stakeholders is critical.
                    Social sustainability is about identifying and managing business impacts, 
                    both positive and negative, on people. The quality of a company’s relationships 
                    and engagement with its stakeholders is critical. Directly or indirectly, companies 
                    affect what happens to employees, workers in the value chain, customers and local communities,
                     and it is important to manage impacts proactively.

                    <br><br>At the same time, actions to achieve social 
                      sustainability may unlock new markets, help retain and attract business partners, or be the source 
                      for innovation for new product or service lines. Internal morale and employee engagement may rise, while 
                      productivity, risk management and company-community conflict improve.

                      The first six of the UN Global Compact's principles focus on this social dimension of corporate sustainability, 
                      of which human rights is the cornerstone. Our work on social sustainability also covers the human rights of 
                      specific groups: labour, women's empowerment and gender equality, children, indigenous peoples, people with 
                      disabilities, as well as people-centered approaches to business impacts on poverty. As well as covering groups 
                      of rights holders, social sustainability encompasses issues that affecting them, for example, education and health.
                 </p>
            </div>
            
        </div>


        <!-- ------------------------------------------SUB CARDS------------------------------------------------------------------ -->
        <div class="sub-cards d-flex flex-row">
            <div class="sub-card-box-1">
                <div class="sub-card-box1-desc">
                    <h1 class="sub-card-box1-heading">Enviromental</h1>
                    <p class="sub-card-box1-txt">
                        <ul>
                            <li>Green initiatives</li>
                            <li>Spent cake recycle</li>
                            <li>Reclamation Efforts</li>
                            <li>Natural Alternatives</li>
                            <li>Operational Efficiencies</li>
                        </ul>
                    </p>
                </div>
                <div class="sub-card-box1-img d-flex justify-content-between">
                    <img src="https://www.aimsindia.com/wp-content/uploads/2022/06/world-environment.png" alt="sub-card-image" class="img5">
                </div>
                <div class="sun-card-btn1"><button class="btn btn-primary">Read more</button></div>
            </div>
            <!-- ---------------------------------------------------------------------------------------------- -->
            <!-- ------------------------------------------SUB CARDS------------------------------------------------------------------ -->
        
            <div class="sub-card-box-2">
                <div class="sub-card-box2-desc">
                    <h1 class="sub-card-box2-heading">Econmical</h1>
                    <p class="sub-card-box2-txt">
                        <ul>
                            <li>Providing Resources and products to Customers</li>
                            <li>Capital improvements</li>
                            <li>Employment</li>
                            <li>Product Stewardship</li>
                            <li>New Market Development</li>
                        </ul>
                    </p>
                </div>
                <div class="sub-card-box2-img d-flex justify-content-between">
                    <img src="https://www.aimsindia.com/wp-content/uploads/2022/06/world-environment.png" alt="sub-card-image" class="img5">
                </div>
                <div class="sun-card-btn2"><button class="btn btn-primary">Read more</button></div>
            </div>
            <!-- ---------------------------------------------------------------------------------------------- -->
            <!-- ------------------------------------------SUB CARDS------------------------------------------------------------------ -->
        
            <div class="sub-card-box-3">
                <div class="sub-card-box3-desc">
                    <h1 class="sub-card-box3-heading">Social</h1>
                    <p class="sub-card-box3-txt">
                        <ul>
                            <li>The EP way</li>
                            <li>Training</li>
                            <li>Compliance</li>
                            <li>EP in the Community</li>
                            <li>Customer Service</li>
                        </ul>
                    </p>
                </div>
                <div class="sub-card-box3-img d-flex justify-content-between">
                    <img src="https://www.aimsindia.com/wp-content/uploads/2022/06/world-environment.png" alt="sub-card-image" class="img5">
                </div>
                <div class="sun-card-btn3"><button class="btn btn-primary">Read more</button></div>
            </div>
            <!-- ---------------------------------------------------------------------------------------------- -->
        </div>
        <!------------------------------------------------------------------------------------------------------------------>
        <div class="corousel-part-card">
            <div id="carouselExampleControls" class="carousel slide" data-ride="carousel">
                <div class="carousel-inner">
                  <div class="carousel-item active">
                    <img class="d-block w-100" src="https://www.nsenergybusiness.com/wp-content/uploads/sites/3/2020/04/windmills-740x520.jpg" alt="First slide">
                  </div>
                  <div class="carousel-item">
                    <img class="d-block w-100" src="https://qph.cf2.quoracdn.net/main-qimg-eb9f84d8159a4ff58636634a6da84aa0-lq" alt="Second slide">
                  </div>
                  <div class="carousel-item">
                    <img class="d-block w-100" src="https://thewire.in/wp-content/uploads/2017/05/poverty-reuters.jpg" alt="Third slide">
                  </div>
                </div>
                <a class="carousel-control-prev" href="#carouselExampleControls" role="button" data-slide="prev">
                  <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                  <span class="sr-only">Previous</span>
                </a>
                <a class="carousel-control-next" href="#carouselExampleControls" role="button" data-slide="next">
                  <span class="carousel-control-next-icon" aria-hidden="true"></span>
                  <span class="sr-only">Next</span>
                </a>
              </div>
        </div>
        <!----------------------------------------------------------------------------------------------------------------------->
        <!--- About us-->
        <div id="sectionaboutus" class="cardabt-us ">
            <div class="abt-us-card d-flex flex-column justify-content-center">
                <div class="abt-us-img1"><img src="https://res.cloudinary.com/dylrwftyl/image/upload/v1682015306/formal1_zubayi.png" alt="myimg" class="myimg"></div>
                <div class="abt-us-heading">Abhishek mathur</div>
                <div class="abt-us-desc">
                    <ul>
                        <li>Roll no.- 36</li>
                        <li>Group-1</li>
                        <li>section: KOCEF</li>
                        <li>Reg id:-12223433</li>
                        <li>Web-site creater</li>
                    </ul>
                </div>
                        <hr class="hrw"/>
            </div>
            <div class="abt-us-card d-flex flex-column justify-content-center">
                <div class="abt-us-img1"><img src="https://res.cloudinary.com/dylrwftyl/image/upload/v1682016263/WhatsApp_Image_2023-04-21_at_00.09.38_tpmeaq.jpg" alt="ze-img" class="myimg"></div>
                <div class="abt-us-heading">Zeaul Hassan</div>
                <div class="abt-us-desc">
                    <ul>
                        <li>Roll no.-34</li>
                        <li>Group-1</li>
                        <li>section: KOCEF</li>
                        <li>Reg id:-12222276</li>
                        <li>Report file writer</li>
                    </ul>
                </div>

            </div>
            <hr class="hrw"/>
            <div class="abt-us-add d-flex justify-content-center">
                Lovely Professional University
                    Private university in Phagwara, Punjab

            </div>
        </div>
        <script type="text/javascript" src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/js/ccbp-ui-kit.js"></script>
        
</div>
</body>
</html>
