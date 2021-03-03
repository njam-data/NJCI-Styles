# Subscription Redirect 3/4/21
 - go to https://s3.console.aws.amazon.com/s3/buckets/njcannabisinsider.nj.com?region=us-east-2&prefix=checkout/&showversions=false
 - move exisiting files to /old-files/
 - create new index.html page with the following code

                <body onload="redirect()">
                    <script>
                        function redirect() {
                            location.replace("https://www.nj.com/cannabis-insider/subscribe/")
                            console.log("worked");
                            }
                    </script>
                </body>
- in an hour or two see if it's working at https://njcannabisinsider.nj.com/checkout/?s=at

## Step two
 - go to about page in aws: https://s3.console.aws.amazon.com/s3/object/njcannabisinsider.nj.com?prefix=about/index.html
 - download and rename for editing (don't screw up and have too many indexes open in VS code)
 - redirect the subscribe button to https://nj.com/cannabis-insider/subscribe . There should be four instances. 3 from the jumbotron and that sticky one at the bottom. 
