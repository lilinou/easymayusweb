---
layout: default
title: 易美教育 | 易美高端留学 | Easymay
partner_array:
   - 36k
   - abc news
   - 东方财务
   - 中华网
   - 中国日报
   - 中国网
   - 中金在线
   - 人民日报
   - 光明网
   - 投资界
   - 搜狐
   - 搜狐教育
   - 新浪财经
   - 新芽
   - 猎云网
   - 环球网
   - 网易
   - 腾讯教育
   - 腾讯财经
   - 鲸媒体
   - 值得依赖
   - 行业创新
   - 真诚稳健
   - 充满活力
   - 安全可靠
   - 威斯康星大学麦迪逊分校华人本科学生会
   - 普渡大学中国学生学者联谊会
   - 宾州州立大学华人本科学生会
   - 华盛顿大学中国学生学者联谊会
   - 加州大学戴维斯分校中国学生学者联谊会
   - 俄亥俄州立大学中国学生学者联合会
   - 天普大学中国学生学者联谊会
   - 亚利桑那州立大学中国学生会
   - 内布拉斯加林肯大学中国学生学者联合会
   - 罗格斯大学中国学生学者联谊会
   - 亚利桑那州立大学中国学生会
   - 特拉华大学中国学生学者联谊会
   - 爱荷华大学中国学生学者联谊会
   - 伊利诺伊大学香槟分校华人学生学者联合会
   - 迈阿密大学牛津分校中国学生学者联谊会
   - 佛罗里达大学大学中国学生会
   - 堪萨斯大学中国学生学者联谊会
   - 俄勒冈大学中国留学生学者联谊会
   - 俄勒冈州立大学中国留学生学者联谊会
   - 明尼苏达大学中国学生学者联谊会
   - 爱荷华州立大学中国学生学者联谊会
   - 波特兰州立大学中国学生学者联合会
   - 威斯康星大学密尔沃基分校中国学生学者联谊会
   - 福特汉姆大学中国学生学者联合会
   - 南加州大学中国学生学者联合会
   - 雪城大学中国学生学者联谊会
   - 美利坚大学中国学生学者联谊会
   - 乔治华盛顿大学中国学生学者联合会
   - 马里兰大学中国学生学者联合会
   - 弗吉尼亚理工大学中国学生学者联谊会
   - 科罗拉多大学波尔多分校中国学生学者联谊会
---

<div class="" id="HomeIndex">
  <div id="wrapper" class="clearfix">

    <!-- preloader -->
    <!-- {% include preloader.html %} -->

    <!-- Header -->
    {% include navigation.html %}

    <!-- Start main-content -->

    <div class="main-content">
      <section id="home" class="divider mobileShowArrow">
        <div class="container-fluid p-0">
          <!--this part is the banner of the index page-->
          <div id="rev_slider_5_1_wrapper" class="rev_slider_wrapper fullwidthbanner-container" data-alias="test"
               data-source="gallery"
               style="margin:0px auto;background:#0c0b09;padding:0px;margin-top:0px;margin-bottom:0px;">

            <!-- START REVOLUTION SLIDER 5.4.7.2 fullwidth mode -->

            <div id="rev_slider_5_1" class="rev_slider fullwidthabanner" style="display:none;" data-version="5.4.7.2">
              <ul>

                <!-- SLIDES  -->

          {% assign i = 27 %}
          {% assign sorted = site.banners | sort:"sequence" %}
          {% for banner in sorted %}

          <li data-index="rs-{{i}}" data-transition="fade" data-slotamount="7,7" data-hideafterloop="0"
                    data-hideslideonmobile="off" data-easein="default,default" data-easeout="default,default"
                    data-masterspeed="300,300" data-thumb="{{banner.src}}" data-rotate="0,0"
                    data-fstransition="fade" data-fsmasterspeed="300" data-fsslotamount="7" data-saveperformance="off"
                    data-title="Welcome" data-param1="" data-param2="" data-param3="" data-param4="" data-param5=""
                    data-param6="" data-param7="" data-param8="" data-param9="" data-param10="" data-description="">

                  <!-- MAIN IMAGE -->

                  <a href="{{banner.href}}" target="_blank" class="customURLOverlay">
                  </a>
                    <img src="{{banner.src}}" alt="" title="1" width="1920" height="480"
                         data-bgposition="center center" data-bgfit="cover" data-bgrepeat="no-repeat" data-bgparallax="off"
                         class="rev-slidebg" data-no-retina>

                  <!-- LAYERS -->
          </li>

          {% assign i = i | plus:1 %}
          {% endfor %}
               
              </ul>
              <div class="tp-bannertimer tp-bottom" style="visibility: hidden !important;"></div>
            </div>
          </div>
          <!-- END REVOLUTION SLIDER -->

        </div>
      </section>

      <!-- Section About, introduction to easy may, who we are -->
      <section class="bg-silver-light aboutus-container preload">
        <div class="container">
          <div class="section-content">
            <div class="row">
              <div class="col-md-6">
                <h2 class="text-uppercasetext-theme-colored mt-0 line-bottom-theme-colored2 mb-20">Who We <span
                  class="text-color-golden">Are</span></h2>
                <p class="mb-8 font-13 text-white text-justify">
                  易美教育集团成立于美国纽约华尔街，多年来结合美国本土化服务优势，以数据为驱动，构建精细化一体化的服务体系，致力于打造集国际教育咨询、房地产信息咨询、海外置业与财富管理为一体的多维度垂直领域服务商。易美教育和易美居地产是易美集团旗下高端教育咨询子品牌和创新型房产咨询服务平台，依靠超高水准的服务品质、注重效果的服务流程、丰富的海外教育资源和优秀的海外专业化团队作为核心竞争力，持续给美国留学生提供真实可靠的一站式留学解决方案，服务链覆盖长线教育规划、留学申请、职业教育、学习规划、考试培训、房产咨询等几大版块。易美教育现已成为美国本土留学咨询公信力第一品牌。
                </p>
                <p class="text-white font-13 text-justify">
                  2018年，易美教育完成数千万元战略投资，战略投资方是中国最大的房地产流通服务企业、拥有多家上市企业的易居中国。2016与2017年，易美教育两次成为中美投融资峰会的独家教育类赞助商，连续两年成为“北美企业校园行”的唯一美国本土教育机构，横跨美国几大州，覆盖美国名校60多所和在美留学生近7万人，并与校方学生组织达成官方战略合作，覆盖在美留学生超过7万人，同时也是唯一一家通过背景调查的教育机构进入哈佛、宾大、哥大、康奈尔等藤校大型峰会与宣讲会，与招生办互通有无。易美独家招生官顾问委员会和名企职业咨询顾问委员会，拥有近50位TOP30名校前招生官和上千位名企中高管为学生1对1全程指导。强大的名校名企资源和本土化服务团队，都是您圆梦名校和名企的最佳选择。
                </p>
              </div>
              <div class="col-md-6">
                <!-- large video box -->
                <div class="box-hover-effect about-video mt-sm-30">
                  <div class="effect-wrapper">
                    <div class="thumb active-video"><img class="img-fullwidth" src="assets/home/Block2/A1.jpeg" alt="project"></div>


                    <!-- Modal -->
                    <div class="modal fade video-wrapper " id="myModal1" tabindex="-1" role="dialog">
                      <div class="modal-dialog" role="document">
                        <div class="modal-content">
                          <div class="modal-header">
                            <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span
                              aria-hidden="true">&times;</span></button>
                            <!--<h4 class="modal-title" id="myModalLabel">Modal title</h4>-->
                          </div>
                          <div class="modal-body">
                            <video class="video-html5" width="320" height="240" controls>
                              <source src="assets/home/Block2/1.m4v" type="video/mp4">
                              Your browser does not support the HTML video.
                            </video>
                          </div>
                        </div>
                      </div>
                    </div>



                    <div data-toggle="modal" data-target="#myModal" class="video-button"></div>
                    <a class="hover-link-video" data-toggle="modal" data-target="#myModal1" href="#" title="Video"></a>
                  </div>
                </div>
              </div>
            </div>
              <!-- gallery constrcted from small video box -->




            {% assign i = 2 %}
            {% assign vs = site.ivideos | sort:"sequence" %}
            {% for video in vs %}

            <!-- Modal Video-1 -->
            <div class="modal fade video-wrapper" id="myModal{{i}}" tabindex="-1" role="dialog">
              <div class="modal-dialog" role="document">
                <div class="modal-content">
                  <div class="modal-header">
                    <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span>
                    </button>
                    <!--<h4 class="modal-title">Modal title</h4>-->
                  </div>
                  <div class="modal-body">
                    <video class="video-html5" width="320" height="240" controls>
                      <source src="{{video.src}}" type="video/mp4">
                      Your browser does not support the HTML video.
                    </video>
                  </div>
                </div>
              </div>
            </div>
            {% assign i = i | plus:1 %}
            {% endfor %}
          




            <div class="row mt-15 pl-15 pr-15">
              <div class="owl-carousel-4col memorabilia">

            {% assign i = 2 %}
            {% assign vs = site.ivideos | sort:"sequence" %}
            {% for video in vs %}

                <div class="item">
                  <div class="item col-md-12">
                    <div class="box-hover-effect about-video mt-sm-30">
                      <div class="effect-wrapper">
                        <div class="thumb"><img class="img-fullwidth" src="{{video.imgsrc}}" alt="project">
                        </div>
                        <div class="video-button"></div>
                        <a class="hover-link-video" data-toggle="modal" data-target="#myModal{{i}}" href="#"
                           title="Youtube Video">Youtube Video</a>
                      </div>
                    </div>
                  </div>
                </div>

            {% assign i = i | plus:1 %}
            {% endfor %}

            
              </div>
            </div>
          </div>
        </div>
      </section>


<!-- Friday Todo starts from here -->
      <section id="blog-story">
        <div class="container pb-sm-40" style="margin-top: -50px;">
          <div class="row justify-content-center">
            <div class="section-title text-center pl-15 pr-15">

              <a href="success.html"><h2 class="title-effect text-theme-colored2 mt-0">易美成功案例故事</h2></a>
              <p class="text-white">整合美国顶尖教育资源，以实力创造辉煌成就</p>
            </div>
          </div>
          <div class="section-content">
            <div class="row pl-15 pr-15">
              <div class="owl-carousel-5col memorabilia" data-duration="1000">

            {% assign ar = site.articles | sort:"sequence" %}
            {% for article in ar %}
            {% if article.appear_page contains 'index_short' %}

                <div class="item">
                  <article class="post">
                  <div class="post-thumb position-relative">
                  <img class="img-fullwidth" src="{{article.src}}" alt="" title="" height="172px" width="260px"> <span>易美独家</span></div>
                  <div class="post-description border-bottom-theme-colored2-1px pb-20">
                  <h5 class="font-weight-600 text-gray-lightgray mt-20 mb-0">2019</h5>
                  <a href="{{article.url}}" target="_blank">
                  <h3 class="title text-theme-colored2 font-weight-600 mt-0 mb-15 font-14 on-hover-underlined">
                  {% if article.use_short_title == "true" %}
                  {{article.title_short}}
                  {% else %}
                  {{article.title}}
                  {% endif %}

                  </h3></a>
                  </div>
                  </article>
                </div>
            {% endif %}
            {% endfor %}

              </div>
            </div>
          </div>
        </div>
      </section>
<!-- Friday Todo Ends here -->

      <section class="divider parallax text-center" data-bg-img="assets/home/Block3/block3_bg_1.png">
        <div class="container pt-80 pb-80">
          <div class="row">
            <div class="col-md-12 text-center text-white">
              <h1 class="ml12">
              <span class="text-wrapper">
              <span class="letters font-weight-800 font-29 ">美国本土第一公信力的高端留学咨询品牌</span>
            </span>
              </h1>
              <script src="https://cdnjs.cloudflare.com/ajax/libs/animejs/2.0.2/anime.min.js"></script>
            </div>
          </div>
        </div>
      </section>

      <!-- Section: Gallery -->
      <section id="gallery" class="parallax professions-info">
        <div class="container">
          <div class="row justify-content-center">
            <div class="section-title text-center pl-15 pr-15">

              <h2 class="title-effect text-theme-colored2 mt-0">易美独家名校招生官顾问委员会</h2>
              <p class="text-white">数十位名校前招生官坐镇美国，为您名校之路保驾护航</p>
            </div>
          </div>
          <div class="section-content">
            <div class="row">
              <div class="col-md-12">

          <!-- Portfolio Gallery Grid -->
        <div id="grid" class="gallery-isotope default-animation-effect grid-3 gutter clearfix">

          <!-- Portfolio Item Start -->
            {% assign ris = site.recruiterintros | sort:"sequence" %}
            {% for ri in ris %}

              <div class="gallery-item">
                <div class="project-gallery">
                   <div class="project-thumb"><img class="img-fullwidth" alt="" src="{{ri.src}}">
                        <div class="project-caption font-11"> 

                          {{ri.content}}

                          <a href="#reservation_form" class="text-white font-13">马上预约 <span
                            class="fa fa-angle-right"></span></a>
                        </div>
                      </div>
                    </div>
                  </div>
            {% endfor %}

                </div>
                <!-- End Portfolio Gallery Grid -->

              </div>
            </div>
          </div>

          <div class="text-center">
            <a class=" solidButton" href="professions.html" style="transition: none 0s ease 0s; text-align: inherit; line-height: 19px; border-width: 1px; margin: 40px 20px; padding: 18px 22px; letter-spacing: 0px; font-weight: 400; font-size: 20px;">了解更多招生官信息</a>
          </div>
        </div>
        </section>

        <!-- Section: Team -->

      <section class="" data-bg-img="assets/home/Block5/bg2.jpg"
               data-bg-parallax="0.3">
        <div class="container pb-sm-20">
          <div class="section-content">
            <div class="row">
              <div class="col-xs-12 col-sm-6 col-md-3 pb-sm-20">
                <div class="image-box-thumb"><img class="img-fullwidth" alt="" src="assets/home/Block5/1.png"></div>
                <div class="image-box-details pt-30 pb-sm-20 text-white noBold">
                  <h4 class="title text-uppercase text-white font-weight-600 mt-0 mb-15 text-theme-colored2">强大美国名校顶尖教育资源</h4>
                  <!--<h6 class="text-gray-lightgray mt-0"><em>CEO - eConsulting</em></h6>-->
                  <p>易美凭借长期脚踏实地的努力以及坚实的客户信任基础，<b>扎根美国</b>，深耕美国高端教育咨询领域，持续为中国学子<b>整合美国顶尖教育资源</b>，召集大批拥有名校国际留学生办公室以及招生委员会工作经历的相关工作人员，并与美国TOP50名校建立紧密合作，持续提供最真实可靠的留学咨询方案，迅速成长为美国本土第一公信力的高端留学品牌。
                  </p>
                </div>
              </div>
              <div class="col-xs-12 col-sm-6 col-md-3 pb-sm-20">
                <div class="image-box-thumb"><img class="img-fullwidth" alt="" src="assets/home/Block5/2.png"></div>
                <div class="image-box-details pt-30 pb-sm-20 text-white noBold">
                  <h4 class="title text-uppercase text-white font-weight-600 mt-0 mb-15 text-theme-colored2">顶级海外专家团队协同服务</h4>
                  <!--<h6 class="text-gray-lightgray mt-0"><em>CEO - eConsulting</em></h6>-->
                  <p>
                    易美汇集数十位美籍名校资深前招生官、教授和名企招聘官，率先成立名校招生官顾问委员会和名企职业咨询顾问委员会，站在美国名校和名企的最前沿，结合中美文化差异，依靠多年美国名校招生工作经验与高水准的学术成就，全程把控申请策略和细节，大幅度提升申请者的学术与职业背景，与目标院校沟通顺畅，令后台申请高效运转。另配备美国名校优秀博士生、研究生以及拥有名校国际教育学背景的海外咨询服务团队，无缝连接，高度协同，为易美学员塑造完美申请者形象。</p>
                </div>
              </div>
              <div class="col-xs-12 col-sm-6 col-md-3 pb-sm-20">
                <div class="image-box-thumb"><img class="img-fullwidth" alt="" src="assets/home/Block5/3.png"></div>
                <div class="image-box-details pt-30 pb-sm-20 text-white noBold">
                  <h4 class="title text-uppercase text-white font-weight-600 mt-0 mb-15 text-theme-colored2">首创低定金冲刺名校模式</h4>
                  <!--<h6 class="text-gray-lightgray mt-0"><em>CEO - eConsulting</em></h6>-->
                  <p>
                    易美教育长期与北美留学生群体联系紧密，深知广大留学生和家长对于留学申请的担忧与顾虑。易美积极采用低定金获得offer再付款的模式，提出“先服务，后签约”的理念，真正站在留学生立场上维护学生与家长的利益，优化结算流程，从而赢得了学生和家长多年来对易美品牌和服务的高度认同和信赖。易美坚信通过长期良好的口碑传递与回馈，不仅提高企业的可信度，也不断鼓舞易美团队为学生和家长提供更优质的服务。</p>
                </div>
              </div>
              <div class="col-xs-12 col-sm-6 col-md-3 pb-sm-20">
                <div class="image-box-thumb"><img class="img-fullwidth" alt="" src="assets/home/Block5/4.png"></div>
                <div class="image-box-details pt-30 pb-sm-20 text-white noBold">
                  <h4 class="title text-uppercase text-white font-weight-600 mt-0 mb-15 text-theme-colored2">独家美国名校数据库</h4>
                  <!--<h6 class="text-gray-lightgray mt-0"><em>CEO - eConsulting</em></h6>-->
                  <p>
                    依据独特的本土化优势，独家建立北美名校内部数据库、案例库、合作院校信息库，精准把控各校季度最低录取分数线、最新录取率、最新课程设置、名校申请渠道和培养目标；与各校保持紧密合作关系，持续对名校一手录取信息进行跟踪并更新，大幅度提高咨询服务效率以及评估精准度，从而为易美学员进行特定数据筛选与匹配，实现精准定位理想院校和专业，助力易美学子圆梦名校。</p>
                </div>
              </div>
            </div>
          </div>
        </div>
      </section>

      <!-- Section: Services -->

      <section id="services" class="services">
        <div class="container pb-50 pt-100">
          <div class="section-content services-block">
            <div class="row">

              <!-- Item Start-->

              <div class="col-xs-12 col-sm-6 col-md-4">
                <div class="icon-box  icon-filled left media p-0 mb-5"><a
                  class="media-left pull-left flip numberl text-white" href="#">1</a>
                  <div class="media-body">
                    <h6 class="media-heading heading font-weight-600 text-theme-colored2 font-19">美式思维</h6>
                    <h6 class="media-heading heading font-weight-600 font-20 text-white">美籍藤校顾问高品质文书</h6>
                  </div>
                </div>
                <p class="pb-40 text-white">
                  易美配备本土博士生，职场精英，美籍文案三大制作团队，摆脱传统模板翻译式撰写方式。依据美国名校授课理念，专业特色，导师科研方向以及美国企业简历内容和格式差异，结合中美文化元素，无限接近美国名校文书审阅习惯与标准，精准提升学生整体背景和竞争力。 </p>
              </div>

              <!-- Item End-->

              <!-- Item Start-->

              <div class="col-xs-12 col-sm-6 col-md-4">
                <div class="icon-box  icon-filled left media p-0 mb-5"><a
                  class="media-left pull-left flip numberl text-white" href="#">2</a>
                  <div class="media-body">
                    <h6 class="media-heading heading font-weight-600 text-theme-colored2 font-19">高效服务</h6>
                    <h6 class="media-heading heading font-weight-600 font-20 text-white">24小时无时差沟通</h6>
                  </div>
                </div>
                <p class="pb-40 text-white">
                  易美申请团队全部拥有藤校国际教育学背景，通过邮件，电话以及面谈等通信方式帮助学生24小时无时差地与招生部门建立有效联系。利用地道的语言表达方式，突出学生对名校学习的人生追求以及全方位加深招生官对学生的印象，并及时反馈给学员和家长，加速申请进程并实时跟踪申请状态。
                </p>
              </div>

              <!-- Item End-->

              <!-- Item Start-->

              <div class="col-xs-12 col-sm-6 col-md-4">
                <div class="icon-box  icon-filled left media p-0 mb-5"><a
                  class="media-left pull-left flip numberl text-white" href="#">3</a>
                  <div class="media-body">
                    <h6 class="media-heading heading font-weight-600 text-theme-colored2 font-19">高录取率</h6>
                    <h6 class="media-heading heading font-weight-600 font-20 text-white">突破低分数录取极限</h6>
                  </div>
                </div>
                <p class="pb-40 text-white">
                  易美多年来与众多知名院校建立长期合作关系，定期更新各大名校录取标准，熟知各名校申请难度系数、申请底线、专业竞争情况以及多种GPA计算方法，通过名校招生官顾问委员会的全程指导和把控，知己知彼，与目标招生官高效沟通，为学员争取面试机会并且提供高匹配度的面试辅导，从而赢得招生官认可。
                </p>
              </div>

              <!-- Item End-->

              <!-- Item Start-->

              <div class="col-xs-12 col-sm-6 col-md-4">
                <div class="icon-box  icon-filled left media p-0 mb-5"><a
                  class="media-left pull-left flip numberl text-white" href="#">4</a>
                  <div class="media-body">
                    <h6 class="media-heading heading font-weight-600 text-theme-colored2 font-19">实力超群</h6>
                    <h6 class="media-heading heading font-weight-600 font-20 text-white">招生官团队权威指导</h6>
                  </div>
                </div>
                <p class="pb-40 text-white">
                  依据多年对录取信息的归纳与分析，针对个性化特点定制整体申请方案和策略，实时监督申请服务各个环节。易美美籍招生官顾问委员会，利用丰富的校内工作经验和内部资源，深度解析美国名校真正的审阅批录流程，运用独特的招生视角为学子精准选校，在网申后续流程的关键节点为学生扬长避短。全程指导，把控并规范申请材料细节，为每位学员在个性化申请道路上添砖加瓦。
                </p>
              </div>

              <!-- Item End-->

              <!-- Item Start-->

              <div class="col-xs-12 col-sm-6 col-md-4">
                <div class="icon-box  icon-filled left media p-0 mb-5"><a
                  class="media-left pull-left flip numberl text-white" href="#">5</a>
                  <div class="media-body">
                    <h6 class="media-heading heading font-weight-600 text-theme-colored2 font-19">高端定制</h6>
                    <h6 class="media-heading heading font-weight-600 font-20 text-white">个性化院校申请方案</h6>
                  </div>
                </div>
                <p class="pb-40 text-white">
                  针对学生和家长不同的专业需求和个性化择校需求，制定不同院校的文书与申请策略，依靠对美国名校的一手资讯分析和申请规律的深刻理解，把控申请过程中的重要节点与细节，摈弃传统中介机构“预收全款，录取保底院校”和流水线式的服务模式，寻找学生经历与名校契合点，精雕细琢，扬长避短，满足学生与名校招生特点的高度统一，从而实现较高的冲刺院校录取率。
                </p>
              </div>

              <!-- Item End-->

              <!-- Item Start-->

              <div class="col-xs-12 col-sm-6 col-md-4">
                <div class="icon-box  icon-filled left media p-0 mb-5"><a
                  class="media-left pull-left flip numberl text-white" href="#">6</a>
                  <div class="media-body">
                    <h6 class="media-heading heading font-weight-600 text-theme-colored2 font-19">定制规划</h6>
                    <h6 class="media-heading heading font-weight-600 font-20 text-white">远程科研实习背景提升</h6>
                  </div>
                </div>
                <p class="pb-40 text-white">
                  易美沉淀多年名企资源，汇聚全球上千位顶尖名企高管，携手世界五百强顶级龙头企业，率行业之先打造“易美名企职业咨询顾问委员会”，与独家招生官顾问委员会相得益彰，相辅相成，为学生从长远角度规划学业与职业发展，根据各大名校招生要求为学生定制名企实习与名校科研项目，提升申请者的软性申请背景，助其脱颖而出得到名校的青睐。
                </p>
              </div>

              <!-- Item End-->

            </div>
          </div>
        </div>
      </section>

      <!-- Section: Services -->

      <section class="services parallax" data-bg-img="assets/home/Block7/bg2.png">
        <div class="container pb-100 pt-100">
          <div class="section-content testimonial-block">
            <div class="owl-carousel">

              <div class="item">
                <div class="testimonials"><img class="" src="assets/home/test/1.jpeg" alt="" title="">
                  <p class="text-center text-white"> 大部分同事或其他学校的招生官都具备多年的招生经验，对各国学生的文书套路都非常熟悉。在成千上万的申请者都符合录取要求时，那些看似并没有被用心准备过的申请，将会被直接拒接，甚至得不到进一步的审核。"
                    <br /><br /><strong>  哥伦比亚大学前招生官阿尔伦女士 </strong></p>
                </div>
              </div>

              <div class="item">
                <div class="testimonials"><img class="" src="assets/home/test/2.jpeg" alt="" title="">
                  <p class="text-center text-white"> 高分不等于一切，我看到许多高分的申请者，由于他们的整体态度不够诚恳、在补充材料中表现平平而最终未能如愿得到offer。"
                    <br /><br /><strong>  哈佛大学前招生官伊万斯女士</strong></p>
                </div>
              </div>

              <div class="item">
                <div class="testimonials"><img class="" src="assets/home/test/3.jpeg" alt="" title="">
                  <p class="text-center text-white"> 我们会审查申请者的成绩单，寻找出与对应专业的核心课程的成绩。同时我们会评估课程的内容范围，以及学生是否达到了最低要求或成功完成难度较高的课程，根据不同的学生与课程分布去衡量学生的标准化成绩，而不是单单只看一个数字。"
                    <br /><br /><strong>  西北大学前招生官赛莱蒙女士 </strong></p>
                </div>
              </div>
              
            </div>
          </div>
        </div>
      </section>

      <!-- Section: blog -->

      <section id="blog">
        <div class="container pb-sm-40">
          <div class="row justify-content-center">
            <div class="section-title text-center pl-15 pr-15">

              <h2 class="title-effect text-theme-colored2 mt-0">易美独家大事记</h2>
              <p class="text-white">整合美国顶尖教育资源，以实力创造辉煌成就</p>
            </div>
          </div>
          <div class="section-content">
            <div class="row pl-20 pr-20">
              <div class="owl-carousel-3col-noAutoPlay memorabilia">

                {% assign sorted = site.articles | sort:"sequence" %}
                {% for case in sorted %}
                {% if case.appear_page contains 'easymaycase' %}

                <div class="item">
                  <article class="post">
                    <div class="post-thumb position-relative"><img src="{{case.src}}" class="img-fullwidth" alt="" height = "246" > <span>易美独家</span></div>
                    <div class="post-description border-bottom-theme-colored2-1px pb-20">
                      <h5 class="font-weight-600 text-gray-lightgray mt-20 mb-0">{{case.year}}</h5>
                      <h3 class="post-title text-theme-colored2 font-weight-600 mt-0 mb-20 font-20">
                        {{case.title}}
                      </h3>
                      <p class="mb-20 short-desc-text">
                        {{case.description}}
                      </p>
                      <a href="{{case.url}}" target="_blank">了解更多</a>
                    </div>
                  </article>
                </div>
                {% endif %}
                {% endfor %}

                

              </div>
            </div>
          </div>
        </div>
      </section>

      <!-- Divider: Clients -->

      <section class="clients">
        <div class="container pt-15 pb-40">
          <div class="row">
           {% assign i = 1%}
           {% for item in page.partner_array%}

            <div class="col-md-3 col-sm-3 col-xs-6">
              <div class="box-hover-effect effect-barlin wow fadeInLeft" data-wow-duration="1.2s" data-wow-offset="10">
                <div class="effect-wrapper">
                  <div class="thumb"><img class="img-fullwidth" src="assets/home/partners/m{{i}}.jpg" alt="project"></div>
                  <div class="overlay-shade"></div>
                  <div class="text-holder text-holder-middle text-center">
                    <div class="text_holder_inner">
                      <div class="text_holder_inner2">
                        <h2 class="title1 text-white mb-0 font-18">{{item}}</h2>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </div>
            {% assign i = i | plus:1 %}
            {% endfor %}
          </div>
        </div>
      </section>
    </div>

    <!-- end main-content -->

    <!-- Divider: Reservation Form -->

    <section id="reservation" class="bg-footer-color">
      <div class="container pb-60">
        <div class="row">
          <div class="col-md-5">
            <h3 class="title-effect text-white font-24 font-weight-600 mt-0 mb-20">真正的名校梦想，需要用心来实现</h3>
            <div class="line-bottom-rounded-theme-colored2"></div>
            <p class="text-white mt-15 mb-15">
              孩子一生的转折点，不仅仅是一纸合同，唯有专注与卓越，才能飞得更高。易美期待在留学路上做您最坚实的后盾，携手诸位名校前招生官为您破解美国名校申请的困局，站在美国制高点，为您拿下一座座名校之城。也希望有志于美国名校的学子能在漫长的求学道路上不忘初心，成功飞跃重洋，遇见更好的自己。
            </p>
          </div>
          <div class="col-md-7">
            <div class="mt-sm-40">
              <h5 class="text-white">让易美竭诚为您服务，共享成就</h5>

              <!-- Reservation Form Start-->

              <form role="form" method="post" id="reservation_form">
                <div class="row">
                  <div class="col-sm-12">
                    <div class="form-group mb-20">
                      <input type="text" class="form-control" id="firstname" name="firstname" maxlength="50"
                             placeholder="姓名*">
                    </div>
                  </div>
                  <div class="col-sm-12">
                    <div class="form-group mb-20">
                      <input type="text" class="form-control" id="email" name="email" maxlength="50" placeholder="邮箱*">
                    </div>
                  </div>
                  <div class="col-sm-12">
                    <div class="form-group mb-20">
                      <div class="styled-select">
                        <select id="category" name="category" class="form-control" aria-required="true">
                          <option value="NA">- 服务类别 -</option>
                          <option value="us_graduate_application ">美国研究生申请服务</option>
                          <option value="us_undergraduate_application">美国本科申请服务</option>
                          <option value="us_undergraduate_transfer">美国本科转学服务</option>
                          <option value="us_highschool_application">美国高中申请服务</option>
                        </select>
                        <i class="fa fa-caret-down"></i></div>
                    </div>
                  </div>

                  <div class="col-sm-3">
                    <div class="form-group mb-0 mt-0">
                      <button type="submit" class="btn btn-default btn-transparent btn-block pt-10 pb-10">预约咨询
                      </button>
                    </div>
                  </div>

                </div>
              </form>

              <div id="success_message" style="width:100%; height:100%; display:none; "><h3>预约成功！</h3></div>
              <div id="error_message" style="width:100%; height:100%; display:none; "><h3>Error</h3> 服务器更新中
              </div>

              <!-- Reservation Form End-->

            </div>
          </div>
        </div>
      </div>
    </section>
    {% include footer.html %}
  </div>
</div>

 <script> var revapi5, tpj;
          (function () {
            if (!/loaded|interactive|complete/.test(document.readyState)) document.addEventListener("DOMContentLoaded", onLoad); else onLoad();

            function onLoad() {
              if (tpj === undefined) {
                tpj = jQuery;
                if ("on" == "on") tpj.noConflict();
              }
              if (tpj("#rev_slider_5_1").revolution == undefined) {
                revslider_showDoubleJqueryError("#rev_slider_5_1");
              } else {
                revapi5 = tpj("#rev_slider_5_1").show().revolution({
                  sliderType: "standard",
                  jsFileLocation: "//credentusa.com/wp-content/plugins/revslider/public/assets/js/",
                  sliderLayout: "fullwidth",
                  dottedOverlay: "none",
                  delay: 4000,
                  navigation: {
                    keyboardNavigation: "on",
                    keyboard_direction: "horizontal",
                    mouseScrollNavigation: "off",
                    mouseScrollReverse: "default",
                    onHoverStop: "on",
                    touch: {
                      touchenabled: "on",
                      touchOnDesktop: "off",
                      swipe_threshold: 75,
                      swipe_min_touches: 1,
                      swipe_direction: "horizontal",
                      drag_block_vertical: false
                    },
                    arrows: {
                      style: "hermes",
                      enable: true,
                      hide_onmobile: false,
                      hide_under: 700,
                      hide_onleave: false,
                      tmp: '<div class="tp-arr-allwrapper">  <div class="tp-arr-imgholder"></div>  <div class="tp-arr-titleholder">{{title}}</div> </div>',
                      left: {h_align: "left", v_align: "center", h_offset: 0, v_offset: 0},
                      right: {h_align: "right", v_align: "center", h_offset: 0, v_offset: 0}
                    }
                  },
                  visibilityLevels: [1240, 1024, 778, 480],
                  gridwidth: 1230,
                  gridheight: 650,
                  lazyType: "none",
                  parallax: {
                    type: "mouse",
                    origo: "enterpoint",
                    speed: 400,
                    speedbg: 0,
                    speedls: 0,
                    levels: [5, 10, 15, 20, 25, 30, 35, 40, 45, 50, 47, 48, 49, 50, 51, 55],
                  },
                  shadow: 0,
                  spinner: "spinner2",
                  stopLoop: "off",
                  stopAfterLoops: -1,
                  stopAtSlide: -1,
                  shuffle: "off",
                  autoHeight: "off",
                  disableProgressBar: "off",
                  hideThumbsOnMobile: "on",
                  hideSliderAtLimit: 0,
                  hideCaptionAtLimit: 0,
                  hideAllCaptionAtLilmit: 0,
                  debugMode: false,
                  fallbacks: {simplifyAll: "off", nextSlideOnWindowFocus: "off", disableFocusListener: false,}
                });
              }
              ; /* END OF revapi call */
            }; /* END OF ON LOAD FUNCTION */
          }()); /* END OF WRAPPING FUNCTION */ </script>