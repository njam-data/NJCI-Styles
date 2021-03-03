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