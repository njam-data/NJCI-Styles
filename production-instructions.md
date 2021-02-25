# How to create an NJCI post

In arc, choose create new story, then choose "longform"

## the other tabs

1\. The planning tab

-   headline: your headline

-   description: Start with "Issue #:" then add your subheadline

-   planned ready time: whenever you plan for it to be live

-   author: make it "Staff: NJ Cannabis Insider staff"

-   tag: add the @exfiba

2\. Circulate tab

-   choose NJ.com as the primary website 

-   choose /cannabis-insider as the primary section

3\. Featured Media

-   type: image

-   key: basic

-   choose an image that will be the giant first image

## Compose tab

-   add the headline and subheadline here again

-   delete the existing text and replace it with a long form story configuration. Do this by clicking the button that looks like a wrench. 

- ![photo of wrench](./images/article-config.png)

    - Within the long form article configuration, choose the following settings:
        -   style: light

        -   label text: put a single space, this will allow the NJCI logo to show up

        -   episode: put a single space, this will allow the NJCI logo to show up

        -   editors note: nothing

        -   show author image: leave unchecked

        -   newsletter sign up: you can add this if you want to promote an event. Add a title, content (which should be date and details. Keep it very short) and a link to the webpage.

        -   about the authors: leave disabled

        -   about the reporting: leave disabled

        -   related articles: choose three. Only the first two show up on mobile so choose accordingly.

        - Save the config box and scroll down for the main article space

-   Next add a custom HTML block by selecting the button that looks like a piece of paper. 

-   ![photo of piece of paper button](./images/html.png)

    -   In the HTML box, place the following HTML. Be sure to save the box after inserting it. 

                <head>
                    <link rel="stylesheet" href="https://use.typekit.net/fiw7olh.css">
                <style>
                body{
                    font-family: "hero-new", sans-serif!important;
                    font-weight: 400!important;
                    font-style: normal!important;
                }

                p{
                    font-family: "hero-new", sans-serif!important;
                    font-weight: 400!important;
                    font-style: normal!important;
                    letter-spacing: -.03rem!important;
                }


                h1 {
                    font-family: "hero-new", sans-serif;
                    font-weight: 900;
                    font-style: italic;
                    color: black;
                    border-bottom: solid 1px!important;
                }

                b, strong {
                    font-weight: 600;
                }

                .page-type__longform-article h1{
                    border-bottom: solid 2px #539643;
                    letter-spacing: -1px;
                }



                .page-type__longform-article .impact-article-header h1{
                    font-family: "hero-new", sans-serif;
                    font-weight: 900;
                    font-style: italic;
                    color: black;
                    border-bottom:none!important;
                    margin-top:1rem;
                    margin-bottom: 2rem;
                }

                .impact-header.h1{
                    font-family: "hero-new", sans-serif;
                    font-weight: 900;
                    font-style: italic;
                    color: black;
                    text-decoration:none!important;
                }

                .page-type__longform-article .deckhead, .page-type__longform-article .label, .page-type__longform-article .series-info, .page-type__longform-article a, .page-type__longform-article h1, .page-type__longform-article h2, .page-type__longform-article h3, .page-type__longform-article li, .page-type__longform-article, .editors-note p{
                    font-family: "hero-new", sans-serif;
                    font-weight: 400;
                    font-style: normal;
                    letter-spacing: -.03rem!important;
                }

                .page-type__longform-article .impact-article p.article__paragraph a {
                    font-weight: 400;
                    text-decoration: underline;
                    border: 0;
                    color: #538742;
                }

                .page-type__longform-article .impact-article-header .series-info .series{
                    border-top:none;
                }

                .page-type__longform-article .impact-article-header .series-info{
                    background-image: url(https://cloudfront-us-east-1.images.arcpublishing.com/advancelocal/DNN45QRHNJEHVE56WYGBGJOSSE.png);
                    height: 75px;
                    width: 200px!important;
                    width: auto;
                    background-position: center;
                    background-repeat: no-repeat;
                    background-size: cover;
                    z-index: 100;
                    margin: 1rem auto;
                }

                .page-type__longform-article .impact-article-header .deckhead{
                    letter-spacing: 0rem;
                    font-family: "hero-new", sans-serif;
                    font-weight: 200;
                    font-style: normal;
                }


                .series-info.h1{
                    font-family: "hero-new", sans-serif;
                    font-weight: 800;
                    font-style: italic;
                    color: #538742;
                }


                .page-type__longform-article .impact-dateline time {
                    font-size: 1.6rem;
                    letter-spacing: .02rem;
                    line-height: 2.2rem;
                    padding: .5rem;
                    color:#666;
                }

                .page-type__longform-article .impact-article .article-heading {
                    color:#538742!important;
                    font-size: 2.5rem;
                    letter-spacing: -1px!important
                    line-height: 3.1rem;
                    margin-bottom: 3rem;
                    font-weight: 200;
                    margin-bottom:1rem;
                    margin-top:0rem;
                }

                .page-type__longform-article .impact-article h2.article-heading {
                    letter-spacing: .03rem;
                    margin-bottom: 3rem;
                    font-size: 3rem;
                    line-height: 3.4rem;
                    color: black!important;
                    font-family: "hero-new", sans-serif;
                    font-weight: 600;
                    font-style: italic;
                    margin-top:0px!important;
                    line-height: 1.2em;
                }

                .page-type__longform-article .impact-article .article__unordered-list li {
                    font-size: 1.8rem;
                }

                .page-type__longform-article .impact-article .article__custom-image .caption {
                    font-size: 1.4rem;
                    line-height: 2rem;
                    letter-spacing: 0;
                    margin: 0rem auto;
                    color: darkgray;
                    font-style: italic;
                }

                .page-type__longform-article .impact-hero-image .caption{
                    font-size: 1.4rem;
                    line-height: 2rem;
                    letter-spacing: 0;
                    margin: 0rem auto;
                    color: darkgray;
                    font-style: italic;
                    font-family: "hero-new", sans-serif;
                }

                .page-type__longform-article .impact-article .article__custom-image .medium-image{
                    margin-top:10em;
                }

                .page-type__longform-article .impact-end-of-article .about-the-authors .author-card .author-card__bio{
                    font-family: "hero-new", sans-serif;
                    font-weight: 400;
                    font-style: normal;
                }

                .page-type__longform-article .impact-end-of-article .about-the-authors .author-card .author-card__name{
                    font-family: "hero-new", sans-serif;
                    font-weight: 700;
                    font-style: normal;
                }

                .page-type__longform-article .impact-end-of-article .headline{
                    display:none;
                }

                .page-type__longform-article .impact-end-of-article .label{
                    display:none;
                }

                .page-type__longform-article .impact-subscribe-cta .impact-subscribe-cta__border-container .impact-subscribe-cta__border{
                    border: .4rem solid #539443;
                }

                .page-type__longform-article .impact-subscribe-cta .impact-subscribe-cta__text-container .impact-subscribe-cta__button-cta{
                    background-color: #539443;
                }

                .page-type__longform-article .impact-related-articles .related-articles .related-article__articles .related-article__article-card .related-article__text .related-article__title{
                    font-family: "hero-new", sans-serif;
                    font-weight: 300;
                    font-style: normal;
                    letter-spacing:0rem;
                }

                .page-type__longform-article .impact-related-articles .related-articles .related-article__heading .related-article__series{
                    font-size: 3rem;
                    line-height: 2.4rem;
                    letter-spacing: 0rem;
                    font-family: "hero-new", sans-serif;
                    font-weight: 700;
                    font-style: normal;
                }

                .page-type__longform-article .impact-related-articles .related-articles .related-article__heading .related-article__label{
                    display:none;
                    
                }

                .page-type__longform-article .impact-related-articles .related-articles .related-article__articles{
                    margin-left: 15em;
                    margin-right: 10em;
                }

                .impact-byline{
                    display:none;
                }

                .sharebar{
                    display:none;
                }

                .page-type__longform-article .impact-article .impact-quote .quote-body{
                    margin-bottom: 0;
                    font-family: hero-new, sans-serif;
                    font-weight: 300;
                    font-style: normal;
                    letter-spacing:0rem;
                }
                .page-type__longform-article .impact-article .impact-quote .source-attribution{
                    margin-top: 2rem;
                    font-family: hero-new, sans-serif;
                    font-weight: 600;
                    font-style: normal;
                    font-size: 2em;
                }

                .page-type__longform-article .impact-article .impact-quote{
                    border-left: .7rem solid #538742;
                }

                .page-type__longform-article .impact-article-header .series-info{
                    margin-bottom:0rem!important;
                }

                .page-type__longform-article .impact-article-header .impact-header{
                    padding-top:2rem;
                }

                .page-type__longform-article .impact-dateline{
                    margin-bottom:3rem;
                }

                .page-type__longform-article .impact-article .article__unordered-list li a {
                    font-weight: 400;
                    text-decoration: underline;
                    border: 0;
                    color: #538742;
                    font-family:"hero-new", sans-serif!important;
                    font-weight:400!important;
                    font-style: normal!important;
                    letter-spacing: -.03rem!important;
                }

                @media screen and (min-width: 768px){
                    .page-type__longform-article .impact-article-header .series-info {
                    margin-bottom: 0rem;
                    }
                }

                @media only screen and (max-width: 700px) {
                    .page-type__longform-article .impact-article-header .series-info {
                        background-image: url(https://cloudfront-us-east-1.images.arcpublishing.com/advancelocal/O2JA7NVXR5CIVNZPHYORTKBDVM.png)!important;
                        height: 100px;
                        width: 100px!important;
                        width: auto;
                        background-position: center;
                        background-repeat: no-repeat;
                        background-size: cover;
                        z-index: 100;
                        margin: 1rem auto;
                    }

                    .page-type__longform-article .impact-article-header h1{
                        padding: 0 .5rem;
                        margin-bottom: 0px;
                        margin-top: 2rem;
                        font-size: 4.4em;
                        font-family: "hero-new", sans-serif;
                        font-weight: 900;
                        font-style: italic;
                        color: black;
                    }


                    .page-type__longform-article .impact-article h1.article-heading {
                        padding: 0;
                        font-size: 2.2rem;
                        letter-spacing: 0rem;
                        max-width:90%;
                        padding-right:0.5rem;
                        padding-left: 20px;
                    }

                    .page-type__longform-article .impact-article h2.article-heading {
                        font-size: 2.5rem;
                        letter-spacing: 0rem;
                    }
                    .page-type__longform-article .impact-article-header .series-info {
                        color: #444;
                        margin-bottom: -3rem;
                    }
                    .page-type__longform-article .impact-dateline {
                        margin-bottom: 4rem;
                    }
                    .page-type__longform-article .impact-article-header .impact-header {
                        padding-top: 0rem;
                    }
                    .page-type__longform-article .impact-article-header .deckhead {
                        letter-spacing: 0rem;
                        font-family: "hero-new", sans-serif;
                        font-weight: 200;
                        font-style: normal;
                        margin: 2rem auto 3rem;
                        padding: 0 1rem;
                        font-size: 1.5em;
                        line-height: 1.5em;
                    }
                    .page-type__longform-article .impact-article .article__unordered-list {
                        padding-left: 4rem;
                    }
                    
                    .page-type__longform-article .impact-dateline time{
                        font-size: 1rem;
                    }
                    
                    .page-type__longform-article .impact-related-articles .related-articles .related-article__articles{
                        margin-left: 3em;
                        margin-right: 3em;
                    }
                    
                    .related-article__article-card:nth-of-type(3) {
                        display:none;
                    }
                    
                    .page-type__longform-article .impact-related-articles .related-articles .related-article__articles .related-article__article-card{
                        width: 16rem;
                        height: 24rem;
                        margin-right: 2rem;
                        background-color: #f8f8f8;
                        display: inline-block;
                        white-space: normal;
                        vertical-align: top;
                    }
                    
                    .page-type__longform-article .impact-related-articles .related-articles .related-article__articles .related-article__article-card .related-article__image{
                        width: 100%;
                        height: 10rem;
                        background-position: 50%;
                        background-repeat: no-repeat;
                        background-size: cover;
                    }
                    
                    .page-type__longform-article .impact-related-articles .related-articles .related-article__articles .related-article__article-card .related-article__text{
                    padding: .5rem;
                    }
                    
                    .page-type__longform-article .impact-related-articles .related-articles .related-article__articles .related-article__article-card .related-article__text .related-article__title{
                        font-size: 1.5rem;
                        line-height: 1.7rem;
                    }
                    
                    .page-type__longform-article .impact-article .article__custom-image .medium-image{
                        margin-top:5em;
                    }
                }

                </style>
                <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>
                <script>
                    $( document ).ready(function() {
                        console.log( "document ready" );
                        $('.page-type__longform-article .impact-article-header .series-info').prepend($('<a target="_blank" style="border-bottom:none; display:block; width:100%; height: 10em;" href="https://www.nj.com/cannabis-insider/"></a>'));
                    });
                </script>
                </head>

-   Next, add the Welcome section. Make the welcome headline an H1.

-   ![H1 photo](./images/h1.png)

    -   add your welcome section text. 

    -   If you want to make an a line in the welcome section text, add a HTML block and type `<hr>`

-   The following articles are all laid out the same: **medium photo, H2, H1, then the text**. It is important you keep that exact order. We will go through each of these.

    -   For the medium photo, click the longform article photo button. It looks like a newspaper. 

    -   [photo of newspaper button]

        -   in the dialogue box, select medium image, paste in the URL and add a caption. You can leave the credit blank. 

        -   To find the URL you need to paste in, go to photo center, locate your photo, select the pencil or edit icon in the corner then copy the PATH TO RESIZER url. 

        -   hit submit and exit the dialouge box.

    -   Then type in your "bug", or the green words that announce each sub-article. These are "inside this issue", "the lead" etc. Make the text an h2. This will style it and make it green. 

    -   Then type the article headline. Make it an h1

    -   Then paste in your text. 

    -   Optional features:

        -   add a small photo within the article. Just following the same instructions with the medium photo but choose small instead. Make sure there are a few paragraphs above and below the small image to maintain the flow. 

        -   hr breaks. Add a custom HTML block then add `<hr>` inside it

        -   block quotes

        -  ![block quote photo](./images/quote.png)

-   At the very end of the issue, add in the contact and bio section. Add an HTML block, then paste the following code in. 

                <head>
                <style>
                .bw{
                    -webkit-filter: grayscale(100%); /* Safari 6.0 - 9.0 */
                    filter: grayscale(100%);
                    width: 100px;
                    height: 100px;
                    position: relative;
                    overflow: hidden;
                    border-radius: 50%;
                    float:left;
                    margin-right:10px;
                    max-width:35%;
                }
                    
                .bw.img{
                    border-radius: 50%;
                    display: inline;
                    margin: 0 auto;
                    height: 100%;
                    width: auto;
                }

                .bio-words{
                    float:right;
                    width: 60%;
                    text-align: left;
                }
                .cg-bio{
                    margin-bottom:7em;
                    min-height:7em;
                }
                .bio-words p{
                    margin-bottom:3px;
                }
                .social-items{
                    padding-top:3px;
                }
                .social-items a{
                    text-decoration:none;
                    border-bottom:none;
                    padding-left: .2em;
                }
                .tainer{
                    min-height:50em;
                    max-width: 500px;
                    margin: auto;
                }

                .contact-container{
                    text-align:left;
                }

                .contact-container h1{
                    color:#539643!important;
                    font-weight: 200;
                    margin-bottom: 1em;
                    margin-top: 2rem;
                }

                .contact-container a{
                    font-weight: 400;
                    text-decoration: underline;
                    border: 0;
                    color: #538742;
                }


                @media only screen and (max-width: 700px) {
                    .cg-bio{
                        margin-bottom:14em!important;
                        min-height:7em;
                    }
                    
                    .bio-words p{
                        line-height:1.5em;
                    }
                    
                    .bw{
                        width: 75px;
                        height: 75px;
                    }
                    
                    .tainer {
                        min-height:70em;
                    }
                }

                </style>
                </head>
                <div class="contact-container">
                    <h1>Contact us</h1>
                    <p class="contact">
                        <strong>Publisher & editor </strong>: Enrique Lavin, <a href="mailto:elavin@njcannabisinsider.biz">elavin@njcannabisinsder.biz</a>
                    </p>
                    <p class="contact">
                        <strong>Sales & events </strong>: Kristen Ligas, <a href="mailto:kligas@advancelocal.com">kligas@advancelocal.com</a>
                    </p>
                    <p class="contact">
                        <strong>Technical support</strong>: <a href="mailto:support@njcannabisinsider.biz">support@njcannabisinsider.biz </a>
                    </p>
                    <p class ="contact">
                        <strong>Subscriptions</strong>: <a href="mailto:subscriptions@njcannabisinsider.biz">subscriptions@njcannabisinsider.biz</a>
                    </p>
                    <h1>Reporters</h1>
                </div>
                <div class="tainer">
                    <div class="cg-bio">
                        <div class="bw">
                            <img src="https://cloudfront-us-east-1.images.arcpublishing.com/advancelocal/Y6AAKY3FIZBD5CTIFQJP2GZRHA.png" alt="Jenali Gibson">
                        </div>
                        <div class="bio-words">
                            <p><strong>Jenali Gibson </strong>is the lead reporter for Cannabis Insider. He previously covered gun violence for the Kansas City Star.</p>
                            <div class="social-items">
                                <a href="https://twitter.com/JelaniGibson1">
                                    <img src="/pf/resources/images/common/social/twitter.svg?d=446">
                                </a>
                                <a href="mailto:jgibson@njadvancemedia.com">
                                    <img src="/pf/resources/images/common/social/mail.svg?d=446">
                                </a>
                                <a href="https://www.linkedin.com/in/jelani-gibson-2297b03a/">
                                    <img src="https://cloudfront-us-east-1.images.arcpublishing.com/advancelocal/X77IVZSAGNEIFEGHP7LL5NT5BE.png" style="max-width:16px; max-height:16px;">
                                </a>
                            </div>
                        </div>
                    </div>
                    <br>
                    
                    <div class="cg-bio">
                        <div class="bw">
                            <img src="https://cloudfront-us-east-1.images.arcpublishing.com/advancelocal/QEJPMVI7EJB5TFYUPCI4CM44JY.png" alt="Amanda Hoover">
                        </div>
                        <div class="bio-words">
                            <p><strong>Amanda Hoover </strong>is a reporter covering the cannabis industry for NJ.com and The Star-Ledger. She previously covered crime and courts across New Jersey.</p> 
                            <div class="social-items">
                                <a href="https://twitter.com/amandahoovernj">
                                    <img src="/pf/resources/images/common/social/twitter.svg?d=446">
                                </a>
                                <a href="mailto:ahoover@njadvancemedia.com">
                                    <img src="/pf/resources/images/common/social/mail.svg?d=446">
                                </a>
                                <a href="https://www.linkedin.com/in/amanda-hoover-b3588583/">
                                    <img src="https://cloudfront-us-east-1.images.arcpublishing.com/advancelocal/X77IVZSAGNEIFEGHP7LL5NT5BE.png" style="max-width:16px; max-height:16px;">
                                </a>
                            </div>
                        </div>
                    </div>
                    <br>
                    <br>
                    <div class="cg-bio">
                        <div class="bw">
                            <img src="https://cloudfront-us-east-1.images.arcpublishing.com/advancelocal/DCJLOBTUZVANTCUMHUX2YSMHOU.png" alt="Susan Livio">
                        </div>
                        <div class="bio-words">
                        <p><strong>Susan Livio </strong> is a Statehouse reporter for The Star-Ledger and NJ.com who covers health, social policy and politics </p>  
                            <div class="social-items">
                                <a href="https://twitter.com/SusanKLivio">
                                    <img src="/pf/resources/images/common/social/twitter.svg?d=446">
                                </a>
                                <a href="mailto:slivio@njadvancemedia.com">
                                    <img src="/pf/resources/images/common/social/mail.svg?d=446">
                                </a>
                                <a href="https://www.linkedin.com/in/susan-k-livio-6365575/">
                                    <img src="https://cloudfront-us-east-1.images.arcpublishing.com/advancelocal/X77IVZSAGNEIFEGHP7LL5NT5BE.png" style="max-width:16px; max-height:16px;">
                                </a>
                            </div>
                        </div>
                    </div>
                    <br>
                    
                    <div class="cg-bio">
                        <div class="bw">
                            <img src="https://cloudfront-us-east-1.images.arcpublishing.com/advancelocal/5FCZEORPAFDM7BOTXUOOASAJCE.JPG" alt="Jonathan Salant">
                        </div>
                        <div class="bio-words">
                            <p><strong>Johnatan D. Salant </strong> is Washington correspondent for The Star-Ledger and NJ.com. </p>
                            <div class="social-items">
                                <a href="https://twitter.com/JDSalant">
                                    <img src="/pf/resources/images/common/social/twitter.svg?d=446">
                                </a> 
                                <a href="mailto:jsalant@njadvancemedia.com">
                                    <img src="/pf/resources/images/common/social/mail.svg?d=446">
                                </a>
                                <a href="https://www.linkedin.com/in/jdsalant/">
                                    <img src="https://cloudfront-us-east-1.images.arcpublishing.com/advancelocal/X77IVZSAGNEIFEGHP7LL5NT5BE.png" style="max-width:16px; max-height:16px;">
                                </a>
                            </div>
                        </div>
                    </div>
                    <br>
                </div>

-   Be sure to save and preview before publishing. You're done.