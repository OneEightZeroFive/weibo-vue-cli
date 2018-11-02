<template>
    <div style="margin-top: 84px">
        <div class="pannelwrap" style="padding-top: 0px; padding-bottom: 0px;">
        <div v-if="channel===0" class="wb-item-wrap">
                <div class="wb-item">
                        <div class="card m-panel card9 f-weibo">
                                <div class="card-wrap">

                                        <header class="weibo-top m-box">
                                                <div class="m-avatar-box m-box-center"><a href="/profile/2130294067"
                                                                class="m-img-box"><img src="https://tva1.sinaimg.cn/crop.0.0.451.451.180/7ef9b533jw1faiadmp8osj20ck0ckjsk.jpg">
                                                                <i class="m-icon m-icon-goldv-static"></i></a></div>
                                                <div class="m-box-dir m-box-col m-box-center">
                                                        <div class="m-text-box"><a href="/profile/2130294067" class="">
                                                                        <h3 class="m-text-cut">高达魔型
                                                                                <i class="m-icon m-icon-vipl6"></i></h3>
                                                                </a>
                                                                <h4 class="m-text-cut"><span class="time">10-31</span>
                                                                        <span class="from"> 来自 微博 weibo.com</span>

                                                                </h4>
                                                        </div>
                                                </div>
                                                <div callback="follow()" class="m-add-box m-followBtn"><span class="m-add-box"><i
                                                                        class="m-font m-font-plus"></i>
                                                                <h4>关注</h4>
                                                        </span></div>
                                        </header>
                                </div>
                                <article class="weibo-main">
                                        <div class="card-wrap">
                                                <div class="weibo-og">
                                                        <div class="weibo-text">笑死。。。。群里朋友三个月的屏幕这个样子。看着我手里一天亮屏十几个小时用了一年的iPhone我表示很欣慰
                                                        </div>
                                                        <div data-v-4ecfaa36="">
                                                                <div data-v-4ecfaa36="" class="weibo-media-wraps weibo-media f-media media-b">
                                                                        <ul data-v-4ecfaa36="" class="m-auto-list">
                                                                                <li data-v-4ecfaa36="" class="m-auto-box2">
                                                                                        <div data-v-4ecfaa36="" class="m-img-box m-imghold-4-3">
                                                                                                <img data-v-4ecfaa36=""
                                                                                                        src="https://wx4.sinaimg.cn/orj360/7ef9b533ly1fwrqqjwkc2j21kw23v1l0.jpg"
                                                                                                        class="f-bg-img">

                                                                                        </div>
                                                                                </li>
                                                                                <li data-v-4ecfaa36="" class="m-auto-box2">
                                                                                        <div data-v-4ecfaa36="" class="m-img-box m-imghold-4-3">
                                                                                                <img data-v-4ecfaa36=""
                                                                                                        src="https://wx1.sinaimg.cn/orj360/7ef9b533ly1fwrqr7jvqsj20u0140wfj.jpg"
                                                                                                        class="f-bg-img">

                                                                                        </div>
                                                                                </li>
                                                                        </ul>
                                                                </div>
                                                        </div>
                                                </div>
                                        </div>

                                </article>
                                <footer class="f-footer-ctrl">
                                        <div class="m-diy-btn m-box-center-a"><i class="lite-iconf lite-iconf-report"></i>
                                                <h4>3</h4>
                                        </div>
                                        <div class="m-diy-btn m-box-center-a"><i class="lite-iconf lite-iconf-comments"></i>
                                                <h4>46</h4>
                                        </div>
                                        <div class="m-diy-btn m-box-center-a"><i class="lite-iconf lite-iconf-like"></i>
                                                <h4>44</h4>
                                        </div>
                                        <aside><i class="m-font m-font-dot-more"></i></aside>
                                </footer>
                        </div>
                </div>
        </div>
        <div v-if="channel===1" class="wb-item-wrap">
                <div class="wb-item">
                        <div class="card m-panel card9 f-weibo">
                                <div class="card-wrap">

                                        <header class="weibo-top m-box">
                                                <div class="m-avatar-box m-box-center"><a href="/profile/3948881580"
                                                                class="m-img-box"><img src="https://tvax1.sinaimg.cn/crop.0.0.996.996.180/eb5f26acly8fwsq0bdzrmj20ro0roabl.jpg">
                                                                <i class="m-icon m-icon-yellowv"></i></a></div>
                                                <div class="m-box-dir m-box-col m-box-center">
                                                        <div class="m-text-box"><a href="/profile/3948881580" class="">
                                                                        <h3 class="m-text-cut">全球科技之家
                                                                                <i class="m-icon m-icon-vipl6"></i></h3>
                                                                </a>
                                                                <h4 class="m-text-cut"><span class="time">10-31</span>
                                                                        <span class="from"> 来自 HUAWEI Mate 10</span>

                                                                </h4>
                                                        </div>
                                                </div>
                                                <div callback="follow()" class="m-add-box m-followBtn"><span class="m-add-box"><i
                                                                        class="m-font m-font-plus"></i>
                                                                <h4>关注</h4>
                                                        </span></div>
                                        </header>
                                </div>
                                <article class="weibo-main">
                                        <div class="card-wrap">
                                                <div class="weibo-og">
                                                        <div class="weibo-text">努比亚X真机上手：副屏亮屏后我瞬间醉了，这货……还能买？<span class="url-icon"><img
                                                                                alt="[笑cry]" src="//h5.sinaimg.cn/m/emoticon/icon/default/d_xiaoku-7430606cb7.png"
                                                                                style="width:1em; height:1em;"></span><span
                                                                        class="url-icon"><img alt="[笑cry]" src="//h5.sinaimg.cn/m/emoticon/icon/default/d_xiaoku-7430606cb7.png"
                                                                                style="width:1em; height:1em;"></span><span
                                                                        class="url-icon"><img alt="[笑cry]" src="//h5.sinaimg.cn/m/emoticon/icon/default/d_xiaoku-7430606cb7.png"
                                                                                style="width:1em; height:1em;"></span>
                                                        </div>
                                                        <div data-v-4ecfaa36="">
                                                                <div data-v-4ecfaa36="" class="weibo-media-wraps weibo-media f-media media-b">
                                                                        <ul data-v-4ecfaa36="" class="m-auto-list">
                                                                                <li data-v-4ecfaa36="" class="m-auto-box2">
                                                                                        <div data-v-4ecfaa36="" class="m-img-box m-imghold-4-3">
                                                                                                <img data-v-4ecfaa36=""
                                                                                                        src="https://wx4.sinaimg.cn/orj360/eb5f26acgy1fwrj9g25ozj20k00qomy7.jpg"
                                                                                                        class="f-bg-img">

                                                                                        </div>
                                                                                </li>
                                                                                <li data-v-4ecfaa36="" class="m-auto-box2">
                                                                                        <div data-v-4ecfaa36="" class="m-img-box m-imghold-4-3">
                                                                                                <img data-v-4ecfaa36=""
                                                                                                        src="https://wx2.sinaimg.cn/orj360/eb5f26acgy1fwrj9gb83xj20k00qot9w.jpg"
                                                                                                        class="f-bg-img">

                                                                                        </div>
                                                                                </li>
                                                                        </ul>
                                                                </div>
                                                        </div>
                                                </div>
                                        </div>

                                </article>
                                <footer class="f-footer-ctrl">
                                        <div class="m-diy-btn m-box-center-a"><i class="lite-iconf lite-iconf-report"></i>
                                                <h4>23</h4>
                                        </div>
                                        <div class="m-diy-btn m-box-center-a"><i class="lite-iconf lite-iconf-comments"></i>
                                                <h4>516</h4>
                                        </div>
                                        <div class="m-diy-btn m-box-center-a"><i class="lite-iconf lite-iconf-like"></i>
                                                <h4>456</h4>
                                        </div>
                                        <aside><i class="m-font m-font-dot-more"></i></aside>
                                </footer>
                        </div>
                </div>
        </div>
        <!-- <div class="wb-item-wrap">
                <div class="wb-item">
                        <div class="card m-panel card9 f-weibo">
                                <div class="card-wrap">

                                        <header class="weibo-top m-box">
                                                <div class="m-avatar-box m-box-center"><a href="/profile/1192504311"
                                                                class="m-img-box"><img src="https://tvax2.sinaimg.cn/crop.0.0.1242.1242.180/47142bf7ly8fwqfhb6w2xj20yi0yignm.jpg">
                                                                <i class="m-icon m-icon-goldv-static"></i></a></div>
                                                <div class="m-box-dir m-box-col m-box-center">
                                                        <div class="m-text-box"><a href="/profile/1192504311" class="">
                                                                        <h3 class="m-text-cut">黄觉
                                                                                <i class="m-icon m-icon-vipl6"></i></h3>
                                                                </a>
                                                                <h4 class="m-text-cut"><span class="time">10-31</span>
                                                                        <span class="from"> 来自 iPhone XS Max(金色)</span>

                                                                </h4>
                                                        </div>
                                                </div>
                                                <div callback="follow()" class="m-add-box m-followBtn"><span class="m-add-box"><i
                                                                        class="m-font m-font-plus"></i>
                                                                <h4>关注</h4>
                                                        </span></div>
                                        </header>
                                </div>
                                <article class="weibo-main">
                                        <div class="card-wrap">
                                                <div class="weibo-og">
                                                        <div class="weibo-text">小孩儿其实都OK的、叫他别玩那么多ipad他就画画、画台笔记本电脑继续玩儿
                                                        </div>
                                                        <div data-v-4ecfaa36="">
                                                                <div data-v-4ecfaa36="" class="weibo-media-wraps weibo-media f-media media-b">
                                                                        <ul data-v-4ecfaa36="" class="m-auto-list">
                                                                                <li data-v-4ecfaa36="" class="m-auto-box2">
                                                                                        <div data-v-4ecfaa36="" class="m-img-box m-imghold-4-3">
                                                                                                <img data-v-4ecfaa36=""
                                                                                                        src="https://wx3.sinaimg.cn/orj360/47142bf7gy1fwr874ji1rj23402c0hdu.jpg"
                                                                                                        class="f-bg-img">

                                                                                        </div>
                                                                                </li>
                                                                        </ul>
                                                                </div>
                                                        </div>
                                                </div>
                                        </div>

                                </article>
                                <footer class="f-footer-ctrl">
                                        <div class="m-diy-btn m-box-center-a"><i class="lite-iconf lite-iconf-report"></i>
                                                <h4>66</h4>
                                        </div>
                                        <div class="m-diy-btn m-box-center-a"><i class="lite-iconf lite-iconf-comments"></i>
                                                <h4>90</h4>
                                        </div>
                                        <div class="m-diy-btn m-box-center-a"><i class="lite-iconf lite-iconf-like"></i>
                                                <h4>1294</h4>
                                        </div>
                                        <aside><i class="m-font m-font-dot-more"></i></aside>
                                </footer>
                        </div>
                </div>
        </div>
        <div class="wb-item-wrap">
                <div class="wb-item">
                        <div class="card m-panel card9 f-weibo">
                                <div class="card-wrap">

                                        <header class="weibo-top m-box">
                                                <div class="m-avatar-box m-box-center"><a href="/profile/2827386331"
                                                                class="m-img-box"><img src="https://tva3.sinaimg.cn/crop.0.0.440.440.180/a8867ddbjw8fb22zrho8mj20c80c8wen.jpg">
                                                                <i class="m-icon m-icon-goldv-static"></i></a></div>
                                                <div class="m-box-dir m-box-col m-box-center">
                                                        <div class="m-text-box"><a href="/profile/2827386331" class="">
                                                                        <h3 class="m-text-cut">科技新一
                                                                                <i class="m-icon m-icon-vipl7"></i></h3>
                                                                </a>
                                                                <h4 class="m-text-cut"><span class="time">10-29</span>


                                                                </h4>
                                                        </div>
                                                </div>
                                                <div callback="follow()" class="m-add-box m-followBtn"><span class="m-add-box"><i
                                                                        class="m-font m-font-plus"></i>
                                                                <h4>关注</h4>
                                                        </span></div>
                                        </header>
                                </div>
                                <article class="weibo-main">
                                        <div class="card-wrap">
                                                <div class="weibo-og">
                                                        <div class="weibo-text">震惊：华为公司老总身份彻底曝光！全世界都感到害怕！！！ </div>
                                                        <div data-v-4ecfaa36="">
                                                                <div data-v-4ecfaa36="" class="weibo-media-wraps weibo-media f-media media-b">
                                                                        <ul data-v-4ecfaa36="" class="m-auto-list">
                                                                                <li data-v-4ecfaa36="" class="m-auto-box2">
                                                                                        <div data-v-4ecfaa36="" class="m-img-box m-imghold-4-3">
                                                                                                <img data-v-4ecfaa36=""
                                                                                                        src="https://wx2.sinaimg.cn/orj360/a8867ddbly1fwp39xyiggj20qo1it44i.jpg"
                                                                                                        class="f-bg-img">

                                                                                        </div>
                                                                                </li>
                                                                                <li data-v-4ecfaa36="" class="m-auto-box2">
                                                                                        <div data-v-4ecfaa36="" class="m-img-box m-imghold-4-3">
                                                                                                <img data-v-4ecfaa36=""
                                                                                                        src="https://wx4.sinaimg.cn/orj360/a8867ddbly1fwp39yktfqj20qo1it0z9.jpg"
                                                                                                        class="f-bg-img">

                                                                                        </div>
                                                                                </li>
                                                                        </ul>
                                                                </div>
                                                        </div>
                                                </div>
                                        </div>

                                </article>
                                <footer class="f-footer-ctrl">
                                        <div class="m-diy-btn m-box-center-a"><i class="lite-iconf lite-iconf-report"></i>
                                                <h4>44</h4>
                                        </div>
                                        <div class="m-diy-btn m-box-center-a"><i class="lite-iconf lite-iconf-comments"></i>
                                                <h4>369</h4>
                                        </div>
                                        <div class="m-diy-btn m-box-center-a"><i class="lite-iconf lite-iconf-like"></i>
                                                <h4>546</h4>
                                        </div>
                                        <aside><i class="m-font m-font-dot-more"></i></aside>
                                </footer>
                        </div>
                </div>
        </div>
        <div class="wb-item-wrap">
                <div class="wb-item">
                        <div class="card m-panel card9 f-weibo">
                                <div class="card-wrap">

                                        <header class="weibo-top m-box">
                                                <div class="m-avatar-box m-box-center"><a href="/profile/1742042067"
                                                                class="m-img-box"><img src="https://tvax1.sinaimg.cn/crop.0.0.1010.1010.180/67d573d3ly8fu4ayta638j20s20s2mzs.jpg">
                                                                <i class="m-icon m-icon-yellowv"></i></a></div>
                                                <div class="m-box-dir m-box-col m-box-center">
                                                        <div class="m-text-box"><a href="/profile/1742042067" class="">
                                                                        <h3 class="m-text-cut">王员外
                                                                                <i class="m-icon m-icon-vipl4"></i></h3>
                                                                </a>
                                                                <h4 class="m-text-cut"><span class="time">昨天 08:29</span>
                                                                        <span class="from"> 来自 库克同款Android</span> <span
                                                                                class="time">已编辑</span></h4>
                                                        </div>
                                                </div>
                                                <div callback="follow()" class="m-add-box m-followBtn"><span class="m-add-box"><i
                                                                        class="m-font m-font-plus"></i>
                                                                <h4>关注</h4>
                                                        </span></div>
                                        </header>
                                </div>
                                <article class="weibo-main">
                                        <div class="card-wrap">
                                                <div class="weibo-og">
                                                        <div class="weibo-text">努比亚 X ，啧啧啧……<span class="url-icon"><img
                                                                                alt="[吃瓜]" src="//h5.sinaimg.cn/m/emoticon/icon/default/d_chigua-90cb948c34.png"
                                                                                style="width:1em; height:1em;"></span><br><br>（图源：ZAEKE知客
                                                                ） </div>
                                                        <div data-v-4ecfaa36="">
                                                                <div data-v-4ecfaa36="" class="weibo-media-wraps weibo-media f-media media-b">
                                                                        <ul data-v-4ecfaa36="" class="m-auto-list">
                                                                                <li data-v-4ecfaa36="" class="m-auto-box2">
                                                                                        <div data-v-4ecfaa36="" class="m-img-box m-imghold-4-3">
                                                                                                <img data-v-4ecfaa36=""
                                                                                                        src="https://wx4.sinaimg.cn/orj360/67d573d3ly1fws9axbmkqj20k40fa75l.jpg"
                                                                                                        class="f-bg-img">

                                                                                        </div>
                                                                                </li>
                                                                        </ul>
                                                                </div>
                                                        </div>
                                                </div>
                                        </div>

                                </article>
                                <footer class="f-footer-ctrl">
                                        <div class="m-diy-btn m-box-center-a"><i class="lite-iconf lite-iconf-report"></i>
                                                <h4>4</h4>
                                        </div>
                                        <div class="m-diy-btn m-box-center-a"><i class="lite-iconf lite-iconf-comments"></i>
                                                <h4>69</h4>
                                        </div>
                                        <div class="m-diy-btn m-box-center-a"><i class="lite-iconf lite-iconf-like"></i>
                                                <h4>154</h4>
                                        </div>
                                        <aside><i class="m-font m-font-dot-more"></i></aside>
                                </footer>
                        </div>
                </div>
        </div>
        <div class="wb-item-wrap">
                <div class="wb-item">
                        <div class="card m-panel card9 f-weibo">
                                <div class="card-wrap">

                                        <header class="weibo-top m-box">
                                                <div class="m-avatar-box m-box-center"><a href="/profile/2320841425"
                                                                class="m-img-box"><img src="https://tvax2.sinaimg.cn/crop.0.0.1125.1125.180/8a553ad1ly8fvriq5zw4yj20v90v9gmc.jpg">
                                                                <i class="m-icon m-icon-goldv-static"></i></a></div>
                                                <div class="m-box-dir m-box-col m-box-center">
                                                        <div class="m-text-box"><a href="/profile/2320841425" class="">
                                                                        <h3 class="m-text-cut">搞科技
                                                                                <i class="m-icon m-icon-vipl6"></i></h3>
                                                                </a>
                                                                <h4 class="m-text-cut"><span class="time">10-31</span>
                                                                        <span class="from"> 来自 微博 weibo.com</span>

                                                                </h4>
                                                        </div>
                                                </div>
                                                <div callback="follow()" class="m-add-box m-followBtn"><span class="m-add-box"><i
                                                                        class="m-font m-font-plus"></i>
                                                                <h4>关注</h4>
                                                        </span></div>
                                        </header>
                                </div>
                                <article class="weibo-main">
                                        <div class="card-wrap">
                                                <div class="weibo-og">
                                                        <div class="weibo-text">iPad刻字服务，一经印刻贬值500。 </div>
                                                        <div data-v-4ecfaa36="">
                                                                <div data-v-4ecfaa36="" class="weibo-media-wraps weibo-media f-media media-b">
                                                                        <ul data-v-4ecfaa36="" class="m-auto-list">
                                                                                <li data-v-4ecfaa36="" class="m-auto-box2">
                                                                                        <div data-v-4ecfaa36="" class="m-img-box m-imghold-4-3">
                                                                                                <img data-v-4ecfaa36=""
                                                                                                        src="https://wx1.sinaimg.cn/orj360/8a553ad1ly1fwrrwmalmjj218a0zg7wh.jpg"
                                                                                                        class="f-bg-img">

                                                                                        </div>
                                                                                </li>
                                                                        </ul>
                                                                </div>
                                                        </div>
                                                </div>
                                        </div>

                                </article>
                                <footer class="f-footer-ctrl">
                                        <div class="m-diy-btn m-box-center-a"><i class="lite-iconf lite-iconf-report"></i>
                                                <h4>10</h4>
                                        </div>
                                        <div class="m-diy-btn m-box-center-a"><i class="lite-iconf lite-iconf-comments"></i>
                                                <h4>123</h4>
                                        </div>
                                        <div class="m-diy-btn m-box-center-a"><i class="lite-iconf lite-iconf-like"></i>
                                                <h4>324</h4>
                                        </div>
                                        <aside><i class="m-font m-font-dot-more"></i></aside>
                                </footer>
                        </div>
                </div>
        </div>
        <div class="wb-item-wrap">
                <div class="wb-item">
                        <div class="card m-panel card9 f-weibo">
                                <div class="card-wrap">

                                        <header class="weibo-top m-box">
                                                <div class="m-avatar-box m-box-center"><a href="/profile/1871821935"
                                                                class="m-img-box"><img src="https://tva1.sinaimg.cn/crop.0.73.440.440.180/6f91bc6fjw8f8o2wa7ts8j20c80gpgp3.jpg">
                                                                <i class="m-icon m-icon-goldv-static"></i></a></div>
                                                <div class="m-box-dir m-box-col m-box-center">
                                                        <div class="m-text-box"><a href="/profile/1871821935" class="">
                                                                        <h3 class="m-text-cut">大米评测
                                                                                <i class="m-icon m-icon-vipl7"></i></h3>
                                                                </a>
                                                                <h4 class="m-text-cut"><span class="time">22小时前</span>
                                                                        <span class="from"> 来自 微博 weibo.com</span>

                                                                </h4>
                                                        </div>
                                                </div>
                                                <div callback="follow()" class="m-add-box m-followBtn"><span class="m-add-box"><i
                                                                        class="m-font m-font-plus"></i>
                                                                <h4>关注</h4>
                                                        </span></div>
                                        </header>
                                </div>
                                <article class="weibo-main">
                                        <div class="card-wrap">
                                                <div class="weibo-og">
                                                        <div class="weibo-text"><span class="url-icon"><img alt="[允悲]"
                                                                                src="//h5.sinaimg.cn/m/emoticon/icon/default/d_yunbei-c6964bf237.png"
                                                                                style="width:1em; height:1em;"></span><span
                                                                        class="url-icon"><img alt="[允悲]" src="//h5.sinaimg.cn/m/emoticon/icon/default/d_yunbei-c6964bf237.png"
                                                                                style="width:1em; height:1em;"></span><span
                                                                        class="url-icon"><img alt="[允悲]" src="//h5.sinaimg.cn/m/emoticon/icon/default/d_yunbei-c6964bf237.png"
                                                                                style="width:1em; height:1em;"></span>这。。。
                                                        </div>
                                                        <div data-v-4ecfaa36="">
                                                                <div data-v-4ecfaa36="" class="weibo-media-wraps weibo-media f-media media-b">
                                                                        <ul data-v-4ecfaa36="" class="m-auto-list">
                                                                                <li data-v-4ecfaa36="" class="m-auto-box2">
                                                                                        <div data-v-4ecfaa36="" class="m-img-box m-imghold-4-3">
                                                                                                <img data-v-4ecfaa36=""
                                                                                                        src="https://wx4.sinaimg.cn/orj360/6f91bc6fgy1fwsfg5gjekj20k70ba3z9.jpg"
                                                                                                        class="f-bg-img">

                                                                                        </div>
                                                                                </li>
                                                                                <li data-v-4ecfaa36="" class="m-auto-box2">
                                                                                        <div data-v-4ecfaa36="" class="m-img-box m-imghold-4-3">
                                                                                                <img data-v-4ecfaa36=""
                                                                                                        src="https://wx2.sinaimg.cn/orj360/6f91bc6fgy1fwsfg5f5paj20i10dcwfk.jpg"
                                                                                                        class="f-bg-img">

                                                                                        </div>
                                                                                </li>
                                                                        </ul>
                                                                </div>
                                                        </div>
                                                </div>
                                        </div>

                                </article>
                                <footer class="f-footer-ctrl">
                                        <div class="m-diy-btn m-box-center-a"><i class="lite-iconf lite-iconf-report"></i>
                                                <h4>30</h4>
                                        </div>
                                        <div class="m-diy-btn m-box-center-a"><i class="lite-iconf lite-iconf-comments"></i>
                                                <h4>246</h4>
                                        </div>
                                        <div class="m-diy-btn m-box-center-a"><i class="lite-iconf lite-iconf-like"></i>
                                                <h4>282</h4>
                                        </div>
                                        <aside><i class="m-font m-font-dot-more"></i></aside>
                                </footer>
                        </div>
                </div>
        </div>
        <div class="wb-item-wrap">
                <div class="wb-item">
                        <div class="card m-panel card9 f-weibo">
                                <div class="card-wrap">

                                        <header class="weibo-top m-box">
                                                <div class="m-avatar-box m-box-center"><a href="/profile/2022252207"
                                                                class="m-img-box"><img src="https://tvax4.sinaimg.cn/crop.0.0.1242.1242.180/78891eafly8fj8r9qeqnqj20yi0yjwfx.jpg">
                                                                <i class="m-icon m-icon-goldv-static"></i></a></div>
                                                <div class="m-box-dir m-box-col m-box-center">
                                                        <div class="m-text-box"><a href="/profile/2022252207" class="">
                                                                        <h3 class="m-text-cut">小白MTX
                                                                                <i class="m-icon m-icon-vipl6"></i></h3>
                                                                </a>
                                                                <h4 class="m-text-cut"><span class="time">21小时前</span>


                                                                </h4>
                                                        </div>
                                                </div>
                                                <div callback="follow()" class="m-add-box m-followBtn"><span class="m-add-box"><i
                                                                        class="m-font m-font-plus"></i>
                                                                <h4>关注</h4>
                                                        </span></div>
                                        </header>
                                </div>
                                <article class="weibo-main">
                                        <div class="card-wrap">
                                                <div class="weibo-og">
                                                        <div class="weibo-text">不开玩笑……这台电脑应该可以用个10年左右！ </div>
                                                        <div data-v-4ecfaa36="">
                                                                <div data-v-4ecfaa36="" class="weibo-media-wraps weibo-media f-media media-b">
                                                                        <ul data-v-4ecfaa36="" class="m-auto-list">
                                                                                <li data-v-4ecfaa36="" class="m-auto-box2">
                                                                                        <div data-v-4ecfaa36="" class="m-img-box m-imghold-4-3">
                                                                                                <img data-v-4ecfaa36=""
                                                                                                        src="https://wx3.sinaimg.cn/orj360/78891eafgy1fwsh7f75n4j20yi0gp41i.jpg"
                                                                                                        class="f-bg-img">

                                                                                        </div>
                                                                                </li>
                                                                                <li data-v-4ecfaa36="" class="m-auto-box2">
                                                                                        <div data-v-4ecfaa36="" class="m-img-box m-imghold-4-3">
                                                                                                <img data-v-4ecfaa36=""
                                                                                                        src="https://wx2.sinaimg.cn/orj360/78891eafgy1fwsh7ent1bj20un0q5jws.jpg"
                                                                                                        class="f-bg-img">

                                                                                        </div>
                                                                                </li>
                                                                        </ul>
                                                                </div>
                                                        </div>
                                                </div>
                                        </div>

                                </article>
                                <footer class="f-footer-ctrl">
                                        <div class="m-diy-btn m-box-center-a"><i class="lite-iconf lite-iconf-report"></i>
                                                <h4>10</h4>
                                        </div>
                                        <div class="m-diy-btn m-box-center-a"><i class="lite-iconf lite-iconf-comments"></i>
                                                <h4>158</h4>
                                        </div>
                                        <div class="m-diy-btn m-box-center-a"><i class="lite-iconf lite-iconf-like"></i>
                                                <h4>301</h4>
                                        </div>
                                        <aside><i class="m-font m-font-dot-more"></i></aside>
                                </footer>
                        </div>
                </div>
        </div>
        <div class="wb-item-wrap">
                <div class="wb-item">
                        <div class="card m-panel card9 f-weibo">
                                <div class="card-wrap">

                                        <header class="weibo-top m-box">
                                                <div class="m-avatar-box m-box-center"><a href="/profile/1898587152"
                                                                class="m-img-box"><img src="https://tva4.sinaimg.cn/crop.0.0.199.199.180/712a2410gw1ena59rjiavj205k05k748.jpg">
                                                                <i class="m-icon m-icon-goldv-static"></i></a></div>
                                                <div class="m-box-dir m-box-col m-box-center">
                                                        <div class="m-text-box"><a href="/profile/1898587152" class="">
                                                                        <h3 class="m-text-cut">IT大施兄
                                                                                <i class="m-icon m-icon-vipl6"></i></h3>
                                                                </a>
                                                                <h4 class="m-text-cut"><span class="time">19小时前</span>


                                                                </h4>
                                                        </div>
                                                </div>
                                                <div callback="follow()" class="m-add-box m-followBtn"><span class="m-add-box"><i
                                                                        class="m-font m-font-plus"></i>
                                                                <h4>关注</h4>
                                                        </span></div>
                                        </header>
                                </div>
                                <article class="weibo-main">
                                        <div class="card-wrap">
                                                <div class="weibo-og">
                                                        <div class="weibo-text">联想公司真大<span class="url-icon"><img alt="[doge]"
                                                                                src="//h5.sinaimg.cn/m/emoticon/icon/others/d_doge-d903433c82.png"
                                                                                style="width:1em; height:1em;"></span><span
                                                                        class="url-icon"><img alt="[doge]" src="//h5.sinaimg.cn/m/emoticon/icon/others/d_doge-d903433c82.png"
                                                                                style="width:1em; height:1em;"></span><span
                                                                        class="url-icon"><img alt="[doge]" src="//h5.sinaimg.cn/m/emoticon/icon/others/d_doge-d903433c82.png"
                                                                                style="width:1em; height:1em;"></span>
                                                        </div>
                                                        <div data-v-4ecfaa36="">
                                                                <div data-v-4ecfaa36="" class="weibo-media-wraps weibo-media f-media media-b">
                                                                        <ul data-v-4ecfaa36="" class="m-auto-list">
                                                                                <li data-v-4ecfaa36="" class="m-auto-box2">
                                                                                        <div data-v-4ecfaa36="" class="m-img-box m-imghold-4-3">
                                                                                                <img data-v-4ecfaa36=""
                                                                                                        src="https://wx3.sinaimg.cn/orj360/712a2410gy1fwsjcib0w2j23k02o0kjn.jpg"
                                                                                                        class="f-bg-img">

                                                                                        </div>
                                                                                </li>
                                                                        </ul>
                                                                </div>
                                                        </div>
                                                </div>
                                        </div>

                                </article>
                                <footer class="f-footer-ctrl">
                                        <div class="m-diy-btn m-box-center-a"><i class="lite-iconf lite-iconf-report"></i>
                                                <h4>10</h4>
                                        </div>
                                        <div class="m-diy-btn m-box-center-a"><i class="lite-iconf lite-iconf-comments"></i>
                                                <h4>53</h4>
                                        </div>
                                        <div class="m-diy-btn m-box-center-a"><i class="lite-iconf lite-iconf-like"></i>
                                                <h4>75</h4>
                                        </div>
                                        <aside><i class="m-font m-font-dot-more"></i></aside>
                                </footer>
                        </div>
                </div>
        </div>
        <div class="wb-item-wrap">
                <div class="wb-item">
                        <div class="card m-panel card9 f-weibo">
                                <div class="card-wrap">

                                        <header class="weibo-top m-box">
                                                <div class="m-avatar-box m-box-center"><a href="/profile/2827386331"
                                                                class="m-img-box"><img src="https://tva3.sinaimg.cn/crop.0.0.440.440.180/a8867ddbjw8fb22zrho8mj20c80c8wen.jpg">
                                                                <i class="m-icon m-icon-goldv-static"></i></a></div>
                                                <div class="m-box-dir m-box-col m-box-center">
                                                        <div class="m-text-box"><a href="/profile/2827386331" class="">
                                                                        <h3 class="m-text-cut">科技新一
                                                                                <i class="m-icon m-icon-vipl7"></i></h3>
                                                                </a>
                                                                <h4 class="m-text-cut"><span class="time">10-31</span>


                                                                </h4>
                                                        </div>
                                                </div>
                                                <div callback="follow()" class="m-add-box m-followBtn"><span class="m-add-box"><i
                                                                        class="m-font m-font-plus"></i>
                                                                <h4>关注</h4>
                                                        </span></div>
                                        </header>
                                </div>
                                <article class="weibo-main">
                                        <div class="card-wrap">
                                                <div class="weibo-og">
                                                        <div class="weibo-text">像吗？<span class="url-icon"><img alt="[允悲]"
                                                                                src="//h5.sinaimg.cn/m/emoticon/icon/default/d_yunbei-c6964bf237.png"
                                                                                style="width:1em; height:1em;"></span>
                                                        </div>
                                                        <div data-v-4ecfaa36="">
                                                                <div data-v-4ecfaa36="" class="weibo-media-wraps weibo-media f-media media-b">
                                                                        <ul data-v-4ecfaa36="" class="m-auto-list">
                                                                                <li data-v-4ecfaa36="" class="m-auto-box2">
                                                                                        <div data-v-4ecfaa36="" class="m-img-box m-imghold-4-3">
                                                                                                <img data-v-4ecfaa36=""
                                                                                                        src="https://wx1.sinaimg.cn/orj360/a8867ddbly1fwrex7v3uzj20wd0hsmxv.jpg"
                                                                                                        class="f-bg-img">

                                                                                        </div>
                                                                                </li>
                                                                                <li data-v-4ecfaa36="" class="m-auto-box2">
                                                                                        <div data-v-4ecfaa36="" class="m-img-box m-imghold-4-3">
                                                                                                <img data-v-4ecfaa36=""
                                                                                                        src="https://wx1.sinaimg.cn/orj360/a8867ddbly1fwrewbjhojj20hs0npgn4.jpg"
                                                                                                        class="f-bg-img">

                                                                                        </div>
                                                                                </li>
                                                                        </ul>
                                                                </div>
                                                        </div>
                                                </div>
                                        </div>

                                </article>
                                <footer class="f-footer-ctrl">
                                        <div class="m-diy-btn m-box-center-a"><i class="lite-iconf lite-iconf-report"></i>
                                                <h4>14</h4>
                                        </div>
                                        <div class="m-diy-btn m-box-center-a"><i class="lite-iconf lite-iconf-comments"></i>
                                                <h4>180</h4>
                                        </div>
                                        <div class="m-diy-btn m-box-center-a"><i class="lite-iconf lite-iconf-like"></i>
                                                <h4>255</h4>
                                        </div>
                                        <aside><i class="m-font m-font-dot-more"></i></aside>
                                </footer>
                        </div>
                </div>
        </div>
        <div class="wb-item-wrap">
                <div class="wb-item">
                        <div class="card m-panel card9 f-weibo">
                                <div class="card-wrap">

                                        <header class="weibo-top m-box">
                                                <div class="m-avatar-box m-box-center"><a href="/profile/1870795791"
                                                                class="m-img-box"><img src="https://tvax3.sinaimg.cn/crop.0.0.996.996.180/6f82140fly8ff4g8p94glj20ro0ro40g.jpg">
                                                                <i class="m-icon m-icon-goldv-static"></i></a></div>
                                                <div class="m-box-dir m-box-col m-box-center">
                                                        <div class="m-text-box"><a href="/profile/1870795791" class="">
                                                                        <h3 class="m-text-cut">极客村长
                                                                                <i class="m-icon m-icon-vipl7"></i></h3>
                                                                </a>
                                                                <h4 class="m-text-cut"><span class="time">22小时前</span>


                                                                </h4>
                                                        </div>
                                                </div>
                                                <div callback="follow()" class="m-add-box m-followBtn"><span class="m-add-box"><i
                                                                        class="m-font m-font-plus"></i>
                                                                <h4>关注</h4>
                                                        </span></div>
                                        </header>
                                </div>
                                <article class="weibo-main">
                                        <div class="card-wrap">
                                                <div class="weibo-og">
                                                        <div class="weibo-text">今年的手机屏占比已经做到这种效果了，明年会是什么样？<span class="url-icon"><img
                                                                                alt="[笑cry]" src="//h5.sinaimg.cn/m/emoticon/icon/default/d_xiaoku-7430606cb7.png"
                                                                                style="width:1em; height:1em;"></span>
                                                        </div>
                                                        <div data-v-4ecfaa36="">
                                                                <div data-v-4ecfaa36="" class="weibo-media-wraps weibo-media f-media media-b">
                                                                        <ul data-v-4ecfaa36="" class="m-auto-list">
                                                                                <li data-v-4ecfaa36="" class="m-auto-box2">
                                                                                        <div data-v-4ecfaa36="" class="m-img-box m-imghold-4-3">
                                                                                                <img data-v-4ecfaa36=""
                                                                                                        src="https://wx4.sinaimg.cn/orj360/6f82140fly1fwsecpgok2j22s21u3x6s.jpg"
                                                                                                        class="f-bg-img">

                                                                                        </div>
                                                                                </li>
                                                                        </ul>
                                                                </div>
                                                        </div>
                                                </div>
                                        </div>

                                </article>
                                <footer class="f-footer-ctrl">
                                        <div class="m-diy-btn m-box-center-a"><i class="lite-iconf lite-iconf-report"></i>
                                                <h4>4</h4>
                                        </div>
                                        <div class="m-diy-btn m-box-center-a"><i class="lite-iconf lite-iconf-comments"></i>
                                                <h4>63</h4>
                                        </div>
                                        <div class="m-diy-btn m-box-center-a"><i class="lite-iconf lite-iconf-like"></i>
                                                <h4>59</h4>
                                        </div>
                                        <aside><i class="m-font m-font-dot-more"></i></aside>
                                </footer>
                        </div>
                </div>
        </div>
        <div class="wb-item-wrap">
                <div class="wb-item">
                        <div class="card m-panel card9 f-weibo">
                                <div class="card-wrap">

                                        <header class="weibo-top m-box">
                                                <div class="m-avatar-box m-box-center"><a href="/profile/2803265504"
                                                                class="m-img-box"><img src="https://tvax4.sinaimg.cn/crop.0.0.1014.1014.180/a7166fe0ly8fhr0ncv3rwj20s60s7jui.jpg">
                                                                <i class="m-icon m-icon-goldv-static"></i></a></div>
                                                <div class="m-box-dir m-box-col m-box-center">
                                                        <div class="m-text-box"><a href="/profile/2803265504" class="">
                                                                        <h3 class="m-text-cut">天策麻花
                                                                                <i class="m-icon m-icon-vipl6"></i></h3>
                                                                </a>
                                                                <h4 class="m-text-cut"><span class="time">10-29</span>
                                                                        <span class="from"> 来自 没有信号的iPhone XS Max</span>

                                                                </h4>
                                                        </div>
                                                </div>
                                                <div callback="follow()" class="m-add-box m-followBtn"><span class="m-add-box"><i
                                                                        class="m-font m-font-plus"></i>
                                                                <h4>关注</h4>
                                                        </span></div>
                                        </header>
                                </div>
                                <article class="weibo-main">
                                        <div class="card-wrap">
                                                <div class="weibo-og">
                                                        <div class="weibo-text">华为这个本子屏幕真的漂亮，就是这个鼠标挺硬的，，。。。 </div>
                                                        <div data-v-4ecfaa36="">
                                                                <div data-v-4ecfaa36="" class="weibo-media-wraps weibo-media f-media media-b">
                                                                        <ul data-v-4ecfaa36="" class="m-auto-list">
                                                                                <li data-v-4ecfaa36="" class="m-auto-box2">
                                                                                        <div data-v-4ecfaa36="" class="m-img-box m-imghold-4-3">
                                                                                                <img data-v-4ecfaa36=""
                                                                                                        src="https://wx2.sinaimg.cn/orj360/a7166fe0gy1fwp981awifj22c0340b29.jpg"
                                                                                                        class="f-bg-img">

                                                                                        </div>
                                                                                </li>
                                                                        </ul>
                                                                </div>
                                                        </div>
                                                </div>
                                        </div>

                                </article>
                                <footer class="f-footer-ctrl">
                                        <div class="m-diy-btn m-box-center-a"><i class="lite-iconf lite-iconf-report"></i>
                                                <h4>3</h4>
                                        </div>
                                        <div class="m-diy-btn m-box-center-a"><i class="lite-iconf lite-iconf-comments"></i>
                                                <h4>60</h4>
                                        </div>
                                        <div class="m-diy-btn m-box-center-a"><i class="lite-iconf lite-iconf-like"></i>
                                                <h4>181</h4>
                                        </div>
                                        <aside><i class="m-font m-font-dot-more"></i></aside>
                                </footer>
                        </div>
                </div>
        </div>
        <div class="wb-item-wrap">
                <div class="wb-item">
                        <div class="card m-panel card9 f-weibo">
                                <div class="card-wrap">

                                        <header class="weibo-top m-box">
                                                <div class="m-avatar-box m-box-center"><a href="/profile/2320841425"
                                                                class="m-img-box"><img src="https://tvax2.sinaimg.cn/crop.0.0.1125.1125.180/8a553ad1ly8fvriq5zw4yj20v90v9gmc.jpg">
                                                                <i class="m-icon m-icon-goldv-static"></i></a></div>
                                                <div class="m-box-dir m-box-col m-box-center">
                                                        <div class="m-text-box"><a href="/profile/2320841425" class="">
                                                                        <h3 class="m-text-cut">搞科技
                                                                                <i class="m-icon m-icon-vipl6"></i></h3>
                                                                </a>
                                                                <h4 class="m-text-cut"><span class="time">10-29</span>
                                                                        <span class="from"> 来自 HUAWEI Mate 20 Pro</span>

                                                                </h4>
                                                        </div>
                                                </div>
                                                <div callback="follow()" class="m-add-box m-followBtn"><span class="m-add-box"><i
                                                                        class="m-font m-font-plus"></i>
                                                                <h4>关注</h4>
                                                        </span></div>
                                        </header>
                                </div>
                                <article class="weibo-main">
                                        <div class="card-wrap">
                                                <div class="weibo-og">
                                                        <div class="weibo-text">无语凝咽。 </div>
                                                        <div data-v-4ecfaa36="">
                                                                <div data-v-4ecfaa36="" class="weibo-media-wraps weibo-media f-media media-b">
                                                                        <ul data-v-4ecfaa36="" class="m-auto-list">
                                                                                <li data-v-4ecfaa36="" class="m-auto-box2">
                                                                                        <div data-v-4ecfaa36="" class="m-img-box m-imghold-4-3">
                                                                                                <img data-v-4ecfaa36=""
                                                                                                        src="https://wx3.sinaimg.cn/orj360/8a553ad1ly1fwow9zdhobj20pb11ggoy.jpg"
                                                                                                        class="f-bg-img">

                                                                                        </div>
                                                                                </li>
                                                                        </ul>
                                                                </div>
                                                        </div>
                                                </div>
                                        </div>

                                </article>
                                <footer class="f-footer-ctrl">
                                        <div class="m-diy-btn m-box-center-a"><i class="lite-iconf lite-iconf-report"></i>
                                                <h4>12</h4>
                                        </div>
                                        <div class="m-diy-btn m-box-center-a"><i class="lite-iconf lite-iconf-comments"></i>
                                                <h4>277</h4>
                                        </div>
                                        <div class="m-diy-btn m-box-center-a"><i class="lite-iconf lite-iconf-like"></i>
                                                <h4>298</h4>
                                        </div>
                                        <aside><i class="m-font m-font-dot-more"></i></aside>
                                </footer>
                        </div>
                </div>
        </div>
        <div class="wb-item-wrap">
                <div class="wb-item">
                        <div class="card m-panel card9 f-weibo">
                                <div class="card-wrap">

                                        <header class="weibo-top m-box">
                                                <div class="m-avatar-box m-box-center"><a href="/profile/2743487997"
                                                                class="m-img-box"><img src="https://tvax4.sinaimg.cn/crop.0.0.996.996.180/a3864dfdly8fqkoosxrbpj20ro0rodhy.jpg">
                                                                <i class="m-icon m-icon-yellowv"></i></a></div>
                                                <div class="m-box-dir m-box-col m-box-center">
                                                        <div class="m-text-box"><a href="/profile/2743487997" class="">
                                                                        <h3 class="m-text-cut">小白撩机
                                                                                <i class="m-icon m-icon-vipl6"></i></h3>
                                                                </a>
                                                                <h4 class="m-text-cut"><span class="time">10-30</span>
                                                                        <span class="from"> 来自 iPhone XS Max</span>

                                                                </h4>
                                                        </div>
                                                </div>
                                                <div callback="follow()" class="m-add-box m-followBtn"><span class="m-add-box"><i
                                                                        class="m-font m-font-plus"></i>
                                                                <h4>关注</h4>
                                                        </span></div>
                                        </header>
                                </div>
                                <article class="weibo-main">
                                        <div class="card-wrap">
                                                <div class="weibo-og">
                                                        <div class="weibo-text">我说MIX3的滑盖设计毫无意义，你们同意吧？ </div>
                                                        <div data-v-4ecfaa36="">
                                                                <div data-v-4ecfaa36="" class="weibo-media-wraps weibo-media f-media media-b">
                                                                        <ul data-v-4ecfaa36="" class="m-auto-list">
                                                                                <li data-v-4ecfaa36="" class="m-auto-box2">
                                                                                        <div data-v-4ecfaa36="" class="m-img-box m-imghold-4-3">
                                                                                                <img data-v-4ecfaa36=""
                                                                                                        src="https://wx1.sinaimg.cn/orj360/a3864dfdgy1fwq9i6tci9j21rh19fh4v.jpg"
                                                                                                        class="f-bg-img">

                                                                                        </div>
                                                                                </li>
                                                                        </ul>
                                                                </div>
                                                        </div>
                                                </div>
                                        </div>

                                </article>
                                <footer class="f-footer-ctrl">
                                        <div class="m-diy-btn m-box-center-a"><i class="lite-iconf lite-iconf-report"></i>
                                                <h4>16</h4>
                                        </div>
                                        <div class="m-diy-btn m-box-center-a"><i class="lite-iconf lite-iconf-comments"></i>
                                                <h4>516</h4>
                                        </div>
                                        <div class="m-diy-btn m-box-center-a"><i class="lite-iconf lite-iconf-like"></i>
                                                <h4>623</h4>
                                        </div>
                                        <aside><i class="m-font m-font-dot-more"></i></aside>
                                </footer>
                        </div>
                </div>
        </div>
        <div class="wb-item-wrap">
                <div class="wb-item">
                        <div class="card m-panel card9 f-weibo">
                                <div class="card-wrap">

                                        <header class="weibo-top m-box">
                                                <div class="m-avatar-box m-box-center"><a href="/profile/5103458366"
                                                                class="m-img-box"><img src="https://tvax2.sinaimg.cn/crop.0.0.996.996.180/005znAECly8fwikd18sflj30ro0romxg.jpg">
                                                                <i class="m-icon m-icon-goldv-static"></i></a></div>
                                                <div class="m-box-dir m-box-col m-box-center">
                                                        <div class="m-text-box"><a href="/profile/5103458366" class="">
                                                                        <h3 class="m-text-cut">laenix_
                                                                                <i class="m-icon m-icon-vipl6"></i></h3>
                                                                </a>
                                                                <h4 class="m-text-cut"><span class="time">10-31</span>
                                                                        <span class="from"> 来自 vivo NEX AI智慧旗舰</span>
                                                                        <span class="time">已编辑</span></h4>
                                                        </div>
                                                </div>
                                                <div callback="follow()" class="m-add-box m-followBtn"><span class="m-add-box"><i
                                                                        class="m-font m-font-plus"></i>
                                                                <h4>关注</h4>
                                                        </span></div>
                                        </header>
                                </div>
                                <article class="weibo-main">
                                        <div class="card-wrap">
                                                <div class="weibo-og">
                                                        <div class="weibo-text">不好意思，刚才吹早了。努比亚X后面的这个「智窗」息屏显示是真漂亮，结果一亮起来太特么难看了。
                                                        </div>
                                                        <div data-v-4ecfaa36="">
                                                                <div data-v-4ecfaa36="" class="weibo-media-wraps weibo-media f-media media-b">
                                                                        <ul data-v-4ecfaa36="" class="m-auto-list">
                                                                                <li data-v-4ecfaa36="" class="m-auto-box2">
                                                                                        <div data-v-4ecfaa36="" class="m-img-box m-imghold-4-3">
                                                                                                <img data-v-4ecfaa36=""
                                                                                                        src="https://wx4.sinaimg.cn/orj360/005znAECly1fwrh3ggvxyj30u00tyn51.jpg"
                                                                                                        class="f-bg-img">

                                                                                        </div>
                                                                                </li>
                                                                                <li data-v-4ecfaa36="" class="m-auto-box2">
                                                                                        <div data-v-4ecfaa36="" class="m-img-box m-imghold-4-3">
                                                                                                <img data-v-4ecfaa36=""
                                                                                                        src="https://wx4.sinaimg.cn/orj360/005znAECly1fwrh3leuajj31901o0x6q.jpg"
                                                                                                        class="f-bg-img">

                                                                                        </div>
                                                                                </li>
                                                                        </ul>
                                                                </div>
                                                        </div>
                                                </div>
                                        </div>

                                </article>
                                <footer class="f-footer-ctrl">
                                        <div class="m-diy-btn m-box-center-a"><i class="lite-iconf lite-iconf-report"></i>
                                                <h4>13</h4>
                                        </div>
                                        <div class="m-diy-btn m-box-center-a"><i class="lite-iconf lite-iconf-comments"></i>
                                                <h4>194</h4>
                                        </div>
                                        <div class="m-diy-btn m-box-center-a"><i class="lite-iconf lite-iconf-like"></i>
                                                <h4>228</h4>
                                        </div>
                                        <aside><i class="m-font m-font-dot-more"></i></aside>
                                </footer>
                        </div>
                </div>
        </div>
        <div class="wb-item-wrap">
                <div class="wb-item">
                        <div class="card m-panel card9 f-weibo">
                                <div class="card-wrap">

                                        <header class="weibo-top m-box">
                                                <div class="m-avatar-box m-box-center"><a href="/profile/2158982787"
                                                                class="m-img-box"><img src="https://tvax2.sinaimg.cn/crop.0.0.1342.1342.180/80af7683ly8fghaoqwbhjj211a11aq7r.jpg">
                                                                <i class="m-icon m-icon-goldv-static"></i></a></div>
                                                <div class="m-box-dir m-box-col m-box-center">
                                                        <div class="m-text-box"><a href="/profile/2158982787" class="">
                                                                        <h3 class="m-text-cut">姜唯
                                                                                <i class="m-icon m-icon-vipl6"></i></h3>
                                                                </a>
                                                                <h4 class="m-text-cut"><span class="time">12小时前</span>
                                                                        <span class="from"> 来自 yoo视频</span>

                                                                </h4>
                                                        </div>
                                                </div>
                                                <div callback="follow()" class="m-add-box m-followBtn"><span class="m-add-box"><i
                                                                        class="m-font m-font-plus"></i>
                                                                <h4>关注</h4>
                                                        </span></div>
                                        </header>
                                </div>
                                <article class="weibo-main">
                                        <div class="card-wrap">
                                                <div class="weibo-og">
                                                        <div class="weibo-text">努比亚X的双屏居然能这么玩！丨yoo视频 <a data-url="http://t.cn/EwVMgOA"
                                                                        target="_blank" href="https://weibo.cn/sinaurl/blocked73ecb66d?id=o0777dfprrs&amp;ptag=huoguo&amp;share_uin=18073517&amp;first=1&amp;luicode=10000011&amp;lfid=102803_ctg1_5088_-_ctg1_5088&amp;u=http%3A%2F%2Fyoo.qq.com%2Fm%2Fvideo.html%3Fid%3Do0777dfprrs%26ptag%3Dhuoguo%26share_uin%3D18073517%26first%3D1"
                                                                        class=""><span class="url-icon"><img style="width: 1rem;height: 1rem"
                                                                                        src="//h5.sinaimg.cn/upload/2015/09/25/3/timeline_card_small_web_default.png"></span><span
                                                                                class="surl-text">网页链接</span></a> </div>
                                                        <div data-v-4ecfaa36="">
                                                                <div data-v-4ecfaa36="" class="weibo-media-wraps weibo-media f-media media-b">
                                                                        <ul data-v-4ecfaa36="" class="m-auto-list">
                                                                                <li data-v-4ecfaa36="" class="m-auto-box2">
                                                                                        <div data-v-4ecfaa36="" class="m-img-box m-imghold-4-3">
                                                                                                <img data-v-4ecfaa36=""
                                                                                                        src="https://wx1.sinaimg.cn/orj360/80af7683gy1fwsw1t32wpj20hs0a0abb.jpg"
                                                                                                        class="f-bg-img">

                                                                                        </div>
                                                                                </li>
                                                                        </ul>
                                                                </div>
                                                        </div>
                                                </div>
                                        </div>

                                </article>
                                <footer class="f-footer-ctrl">
                                        <div class="m-diy-btn m-box-center-a"><i class="lite-iconf lite-iconf-report"></i>
                                                <h4>4</h4>
                                        </div>
                                        <div class="m-diy-btn m-box-center-a"><i class="lite-iconf lite-iconf-comments"></i>
                                                <h4>18</h4>
                                        </div>
                                        <div class="m-diy-btn m-box-center-a"><i class="lite-iconf lite-iconf-like"></i>
                                                <h4>22</h4>
                                        </div>
                                        <aside><i class="m-font m-font-dot-more"></i></aside>
                                </footer>
                        </div>
                </div>
        </div>
        <div class="wb-item-wrap">
                <div class="wb-item">
                        <div class="card m-panel card9 f-weibo">
                                <div class="card-wrap">

                                        <header class="weibo-top m-box">
                                                <div class="m-avatar-box m-box-center"><a href="/profile/3962657498"
                                                                class="m-img-box"><img src="https://tva4.sinaimg.cn/crop.0.2.1242.1242.180/ec315adajw8fcaxc5rszmj20yi0ymgn6.jpg">
                                                                <i class="m-icon m-icon-goldv-static"></i></a></div>
                                                <div class="m-box-dir m-box-col m-box-center">
                                                        <div class="m-text-box"><a href="/profile/3962657498" class="">
                                                                        <h3 class="m-text-cut">测评君
                                                                                <i class="m-icon m-icon-vipl6"></i></h3>
                                                                </a>
                                                                <h4 class="m-text-cut"><span class="time">19小时前</span>


                                                                </h4>
                                                        </div>
                                                </div>
                                                <div callback="follow()" class="m-add-box m-followBtn"><span class="m-add-box"><i
                                                                        class="m-font m-font-plus"></i>
                                                                <h4>关注</h4>
                                                        </span></div>
                                        </header>
                                </div>
                                <article class="weibo-main">
                                        <div class="card-wrap">
                                                <div class="weibo-og">
                                                        <div class="weibo-text">联想ZUI 10更换新图标，很熟悉的感觉 </div>
                                                        <div data-v-4ecfaa36="">
                                                                <div data-v-4ecfaa36="" class="weibo-media-wraps weibo-media f-media media-b">
                                                                        <ul data-v-4ecfaa36="" class="m-auto-list">
                                                                                <li data-v-4ecfaa36="" class="m-auto-box2">
                                                                                        <div data-v-4ecfaa36="" class="m-img-box m-imghold-4-3">
                                                                                                <img data-v-4ecfaa36=""
                                                                                                        src="https://wx4.sinaimg.cn/orj360/ec315adaly1fwsjqusu9qj23k02o0e81.jpg"
                                                                                                        class="f-bg-img">

                                                                                        </div>
                                                                                </li>
                                                                                <li data-v-4ecfaa36="" class="m-auto-box2">
                                                                                        <div data-v-4ecfaa36="" class="m-img-box m-imghold-4-3">
                                                                                                <img data-v-4ecfaa36=""
                                                                                                        src="https://wx3.sinaimg.cn/orj360/ec315adaly1fwsjr0doetj20qo0k0whh.jpg"
                                                                                                        class="f-bg-img">

                                                                                        </div>
                                                                                </li>
                                                                        </ul>
                                                                </div>
                                                        </div>
                                                </div>
                                        </div>

                                </article>
                                <footer class="f-footer-ctrl">
                                        <div class="m-diy-btn m-box-center-a"><i class="lite-iconf lite-iconf-report"></i>
                                                <h4>6</h4>
                                        </div>
                                        <div class="m-diy-btn m-box-center-a"><i class="lite-iconf lite-iconf-comments"></i>
                                                <h4>85</h4>
                                        </div>
                                        <div class="m-diy-btn m-box-center-a"><i class="lite-iconf lite-iconf-like"></i>
                                                <h4>36</h4>
                                        </div>
                                        <aside><i class="m-font m-font-dot-more"></i></aside>
                                </footer>
                        </div>
                </div>
        </div>
        <div class="wb-item-wrap">
                <div class="wb-item">
                        <div class="card m-panel card9 f-weibo">
                                <div class="card-wrap">

                                        <header class="weibo-top m-box">
                                                <div class="m-avatar-box m-box-center"><a href="/profile/5143897135"
                                                                class="m-img-box"><img src="https://tvax1.sinaimg.cn/crop.2.0.507.507.180/005C7gCPly8fequpq8pgvj30e80e3dgb.jpg">
                                                                <i class="m-icon m-icon-goldv-static"></i></a></div>
                                                <div class="m-box-dir m-box-col m-box-center">
                                                        <div class="m-text-box"><a href="/profile/5143897135" class="">
                                                                        <h3 class="m-text-cut">刹那数码
                                                                                <i class="m-icon m-icon-vipl6"></i></h3>
                                                                </a>
                                                                <h4 class="m-text-cut"><span class="time">21小时前</span>


                                                                </h4>
                                                        </div>
                                                </div>
                                                <div callback="follow()" class="m-add-box m-followBtn"><span class="m-add-box"><i
                                                                        class="m-font m-font-plus"></i>
                                                                <h4>关注</h4>
                                                        </span></div>
                                        </header>
                                </div>
                                <article class="weibo-main">
                                        <div class="card-wrap">
                                                <div class="weibo-og">
                                                        <div class="weibo-text">百分之80可信度 </div>
                                                        <div data-v-4ecfaa36="">
                                                                <div data-v-4ecfaa36="" class="weibo-media-wraps weibo-media f-media media-b">
                                                                        <ul data-v-4ecfaa36="" class="m-auto-list">
                                                                                <li data-v-4ecfaa36="" class="m-auto-box2">
                                                                                        <div data-v-4ecfaa36="" class="m-img-box m-imghold-4-3">
                                                                                                <img data-v-4ecfaa36=""
                                                                                                        src="https://wx4.sinaimg.cn/orj360/005C7gCPly1fwsgevuyq9j318g0xctbv.jpg"
                                                                                                        class="f-bg-img">

                                                                                        </div>
                                                                                </li>
                                                                        </ul>
                                                                </div>
                                                        </div>
                                                </div>
                                        </div>

                                </article>
                                <footer class="f-footer-ctrl">
                                        <div class="m-diy-btn m-box-center-a"><i class="lite-iconf lite-iconf-report"></i>
                                                <h4>9</h4>
                                        </div>
                                        <div class="m-diy-btn m-box-center-a"><i class="lite-iconf lite-iconf-comments"></i>
                                                <h4>93</h4>
                                        </div>
                                        <div class="m-diy-btn m-box-center-a"><i class="lite-iconf lite-iconf-like"></i>
                                                <h4>89</h4>
                                        </div>
                                        <aside><i class="m-font m-font-dot-more"></i></aside>
                                </footer>
                        </div>
                </div>
        </div>
        <div class="wb-item-wrap">
                <div class="wb-item">
                        <div class="card m-panel card9 f-weibo">
                                <div class="card-wrap">

                                        <header class="weibo-top m-box">
                                                <div class="m-avatar-box m-box-center"><a href="/profile/3825067581"
                                                                class="m-img-box"><img src="https://tvax2.sinaimg.cn/crop.0.0.1125.1125.180/e3fde63dly8fqv3pr1jnsj20v90v9abp.jpg">
                                                                <i class="m-icon m-icon-goldv-static"></i></a></div>
                                                <div class="m-box-dir m-box-col m-box-center">
                                                        <div class="m-text-box"><a href="/profile/3825067581" class="">
                                                                        <h3 class="m-text-cut">园姐
                                                                                <i class="m-icon m-icon-vipl6"></i></h3>
                                                                </a>
                                                                <h4 class="m-text-cut"><span class="time">21小时前</span>


                                                                </h4>
                                                        </div>
                                                </div>
                                                <div callback="follow()" class="m-add-box m-followBtn"><span class="m-add-box"><i
                                                                        class="m-font m-font-plus"></i>
                                                                <h4>关注</h4>
                                                        </span></div>
                                        </header>
                                </div>
                                <article class="weibo-main">
                                        <div class="card-wrap">
                                                <div class="weibo-og">
                                                        <div class="weibo-text"><span class="url-icon"><img alt="[允悲]"
                                                                                src="//h5.sinaimg.cn/m/emoticon/icon/default/d_yunbei-c6964bf237.png"
                                                                                style="width:1em; height:1em;"></span>
                                                        </div>
                                                        <div data-v-4ecfaa36="">
                                                                <div data-v-4ecfaa36="" class="weibo-media-wraps weibo-media f-media media-b">
                                                                        <ul data-v-4ecfaa36="" class="m-auto-list">
                                                                                <li data-v-4ecfaa36="" class="m-auto-box2">
                                                                                        <div data-v-4ecfaa36="" class="m-img-box m-imghold-4-3">
                                                                                                <img data-v-4ecfaa36=""
                                                                                                        src="https://wx2.sinaimg.cn/orj360/e3fde63dly1fwsglbmq5tj20v90rqwoy.jpg"
                                                                                                        class="f-bg-img">

                                                                                        </div>
                                                                                </li>
                                                                                <li data-v-4ecfaa36="" class="m-auto-box2">
                                                                                        <div data-v-4ecfaa36="" class="m-img-box m-imghold-4-3">
                                                                                                <img data-v-4ecfaa36=""
                                                                                                        src="https://wx3.sinaimg.cn/orj360/e3fde63dly1fwsglb7tnuj21kw16o423.jpg"
                                                                                                        class="f-bg-img">

                                                                                        </div>
                                                                                </li>
                                                                        </ul>
                                                                </div>
                                                        </div>
                                                </div>
                                        </div>

                                </article>
                                <footer class="f-footer-ctrl">
                                        <div class="m-diy-btn m-box-center-a"><i class="lite-iconf lite-iconf-report"></i>
                                                <h4>15</h4>
                                        </div>
                                        <div class="m-diy-btn m-box-center-a"><i class="lite-iconf lite-iconf-comments"></i>
                                                <h4>95</h4>
                                        </div>
                                        <div class="m-diy-btn m-box-center-a"><i class="lite-iconf lite-iconf-like"></i>
                                                <h4>101</h4>
                                        </div>
                                        <aside><i class="m-font m-font-dot-more"></i></aside>
                                </footer>
                        </div>
                </div>
        </div>
        <div class="wb-item-wrap">
                <div class="wb-item">
                        <div class="card m-panel card9 f-weibo">
                                <div class="card-wrap">

                                        <header class="weibo-top m-box">
                                                <div class="m-avatar-box m-box-center"><a href="/profile/2022252207"
                                                                class="m-img-box"><img src="https://tvax4.sinaimg.cn/crop.0.0.1242.1242.180/78891eafly8fj8r9qeqnqj20yi0yjwfx.jpg">
                                                                <i class="m-icon m-icon-goldv-static"></i></a></div>
                                                <div class="m-box-dir m-box-col m-box-center">
                                                        <div class="m-text-box"><a href="/profile/2022252207" class="">
                                                                        <h3 class="m-text-cut">小白MTX
                                                                                <i class="m-icon m-icon-vipl6"></i></h3>
                                                                </a>
                                                                <h4 class="m-text-cut"><span class="time">10-30</span>
                                                                        <span class="from"> 来自 Mac客户端</span>

                                                                </h4>
                                                        </div>
                                                </div>
                                                <div callback="follow()" class="m-add-box m-followBtn"><span class="m-add-box"><i
                                                                        class="m-font m-font-plus"></i>
                                                                <h4>关注</h4>
                                                        </span></div>
                                        </header>
                                </div>
                                <article class="weibo-main">
                                        <div class="card-wrap">
                                                <div class="weibo-og">
                                                        <div class="weibo-text">关于小米MIX3的滑盖缝隙 来个清楚的。。。 <br>但是在实际上手滑动的时候
                                                                真的是一点旷量都感觉不到，很扎实 </div>
                                                        <div data-v-4ecfaa36="">
                                                                <div data-v-4ecfaa36="" class="weibo-media-wraps weibo-media f-media media-b">
                                                                        <ul data-v-4ecfaa36="" class="m-auto-list">
                                                                                <li data-v-4ecfaa36="" class="m-auto-box2">
                                                                                        <div data-v-4ecfaa36="" class="m-img-box m-imghold-4-3">
                                                                                                <img data-v-4ecfaa36=""
                                                                                                        src="https://wx2.sinaimg.cn/orj360/78891eafly1fwqeqspftnj20u0140akj.jpg"
                                                                                                        class="f-bg-img">

                                                                                        </div>
                                                                                </li>
                                                                                <li data-v-4ecfaa36="" class="m-auto-box2">
                                                                                        <div data-v-4ecfaa36="" class="m-img-box m-imghold-4-3">
                                                                                                <img data-v-4ecfaa36=""
                                                                                                        src="https://wx3.sinaimg.cn/orj360/78891eafly1fwqeqsox82j20u0140k2t.jpg"
                                                                                                        class="f-bg-img">

                                                                                        </div>
                                                                                </li>
                                                                        </ul>
                                                                </div>
                                                        </div>
                                                </div>
                                        </div>

                                </article>
                                <footer class="f-footer-ctrl">
                                        <div class="m-diy-btn m-box-center-a"><i class="lite-iconf lite-iconf-report"></i>
                                                <h4>6</h4>
                                        </div>
                                        <div class="m-diy-btn m-box-center-a"><i class="lite-iconf lite-iconf-comments"></i>
                                                <h4>182</h4>
                                        </div>
                                        <div class="m-diy-btn m-box-center-a"><i class="lite-iconf lite-iconf-like"></i>
                                                <h4>212</h4>
                                        </div>
                                        <aside><i class="m-font m-font-dot-more"></i></aside>
                                </footer>
                        </div>
                </div>
        </div> -->
</div>
    </div>
</template>
<script>
export default {
  data() {
    return {
      channel: 0
    };
  },
  // 计算属性
  computed:{
    // 把vuex的信息获取回来放到information里面
    information(){
      // 利用中介的getInformation把数据通过计算属性交给本组件的information里面存起来
      return this.$store.getters.getInformation
    }
  },
  // 换场判断
  watch: {
    $route() {
      console.log(this.$route.path);
      this.setChannel();
      console.log("路由改变了");
    }
  },
  methods: {
    setChannel() {
      var path = this.$route.path;
      switch (path) {
        case "/home/hot":
          this.channel = 0;
          break;
        case "/home/fresh":
          this.channel = 1;
          break;
        default:
          this.channel = 0;
      }
    }
  },
  // 进场判断
  mounted() {
    this.setChannel();
  }
};
</script>

