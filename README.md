Amazon style image and title scroller with jQuery
=======================

[![Amazon style image and title scroller with jQuery](http://www.htmldrive.net/media/2013/3/30/1364708830.png "Amazon style image and title scroller with jQuery")](http://www.htmldrive.net/items/show/244/Amazon-style-image-and-title-scroller-with-jQuery "Amazon style image and title scroller with jQuery")

[**Demo**](http://www.htmldrive.net/items/show/244/Amazon-style-image-and-title-scroller-with-jQuery "Amazon style image and title scroller with jQuery")
##Usage
**Include js and css files.**

    <link href="css/amazon_scroller.css" rel="stylesheet" type="text/css"></link>
    <script type="text/javascript" src="js/jquery-1.3.2.min.js"></script>
    <script type="text/javascript" src="js/amazon_scroller.js"></script>

  
**Add html.**

    <div id="amazon_scroller" class="amazon_scroller">
        <div class="amazon_scroller_mask">
            <ul>
                <li><a href="link1" title="title1"><img src="images/scroller_large_1.jpg" width="60" height="60" alt="title"/></a></li>
                <li><a href="link2" title="title2"><img src="images/scroller_large_2.jpg" width="60" height="60" alt="title"/></a></li>
                <li><a href="link3" title="title3"><img src="images/scroller_large_3.jpg" width="60" height="60" alt="title"/></a></li>
                <li><a href="link4" title="title4"><img src="images/scroller_large_4.jpg" width="60" height="60" alt="title"/></a></li>
                <li><a href="link1" title="title5"><img src="images/scroller_large_1.jpg" width="60" height="60" alt="title"/></a></li>
                <li><a href="link2" title="title6"><img src="images/scroller_large_2.jpg" width="60" height="60" alt="title"/></a></li>
                <li><a href="link3" title="title7"><img src="images/scroller_large_3.jpg" width="60" height="60" alt="title"/></a></li>
                <li><a href="link4" title="title8"><img src="images/scroller_large_4.jpg" width="60" height="60" alt="title"/></a></li>
            </ul>
        </div>
        <ul class="amazon_scroller_nav">
            <li></li>
            <li></li>
        </ul>
        <div style="clear: both"></div>
    </div>
        
**Add startup script.**

    $("#amazon_scroller3").amazon_scroller({
        scroller_title_show: 'enable',//enable  disable  
        scroller_time_interval: '3000',
        scroller_window_background_color: "#FFF",
        scroller_window_padding: '10',
        scroller_border_size: '2',
        scroller_border_color: '#CCC',
        scroller_images_width: '80',
        scroller_images_height: '60',
        scroller_title_size: '11',
        scroller_title_color: '#000',
        scroller_show_count: '3',
        directory: 'images'
    });