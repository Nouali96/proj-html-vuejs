<template>
    <div class="footer">
        <div class="container pt-5">
            <div class="row py-5 border-bottom border-1">
                <div class="col-3">
                    <img class="img-footer" src="..\public\assets\img\logo-light.png" alt="">
                    <ul class="mt-4">
                        <li>
                            Providing Life Changing Experiences Through Education. Class That Fit Your Busy Life. Closer to Home
                        </li>
                        <li>
                            <span><i class="fa-solid fa-phone"></i> 1-677-124-44227</span>
                        </li>
                        <li>
                            <span><i class="fa-regular fa-clock"></i> Mon - Sat 8.00 -18.00</span>
                        </li>
                    </ul>
                </div>
                <div class="col-3">
                    <h3>Popular courses</h3>
                    <ul class="mt-4">
                        <li>
                            <h5>Business English</h5>
                            <span>Preston Marshall</span>
                        </li>
                        <li>
                            <h5>Social Computing</h5>
                            <span>David Sanders</span>
                        </li>
                        <li>
                            <h5>Learn Spanish</h5>
                            <span>Jennie King</span>
                        </li>
                    </ul>
                </div>
                <div class="col-3">
                    <h3>Support</h3>
                    <ul class="mt-4">
                        <li>
                            <a href="#">User dashboard</a>
                        </li>
                        <li>
                            <a href="#">Contact Us</a>
                        </li>
                        <li>
                            <a href="#">FAQ</a>
                        </li>
                        <li>
                            <a href="#">Course Offer</a>
                        </li>
                        <li>
                            <a href="#">Events</a>
                        </li>
                    </ul>
                </div>
                <div class="col-3">
                    <h3>Flexible Learning</h3>
                    <img class="mt-4 img-map-footer" src="..\public\assets\img\footer-img-1.png" alt="">
                </div>
            </div>
            <div class="row pt-4 pb-5 f-bottom">
                <div class="col-8">
                    <span>Copyrights 2017 ©Mikado Themes</span> 
                </div>
                <div class="col-4 f-bottom-right">
                    <span>CALL +44 300 303 0266</span>
                    <span>FOLLOW US</span>
                    <a href="#"><i class="fa-brands fa-twitter"></i></a>
                    <a href="#"><i class="fa-brands fa-instagram"></i></a>
                    <a href="#"><i class="fa-brands fa-facebook-f"></i></a>
                </div>
            </div>
        </div>
        
    </div>
</template>

<script>
export default {
    name: 'MyFooter',
}
</script>

<style lang="scss">
@import "@/assets/style/general.scss";
.footer{
    background-color: #222222;
    color: white;
    text-decoration: none;
}
.footer ul{
    list-style-type: none;
    padding-left: 0;
}
.footer li{
    margin-top: 10px;
}
.footer a{
    color: white;
}
.img-map-footer{
    width: 100%;
}
.img-footer{
    height: 33px;
}
.f-bottom>div>span{
    font-size: 15px;
}
.f-bottom-right span,a{
    margin: 0 10px;
}
</style>