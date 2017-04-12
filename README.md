# StoryLab.Shorthand-LifeAndTheLunaticExpress

A Shorthand story about the residents of Mashimoni, Kibera: a community living right at the edge of the train tracks.


### Analytics

After updating, all shorthand stories should add the following analytics trackers in the `index.html` file.

```
  <!-- HuffPost.ZA Trackers -->

  <!-- Begin comScore Tag -->
  <script type="text/javascript">
    document.write(unescape("%3Cscript src='" + (document.location.protocol == "https:" ? "https://sb" : "http://b") + ".scorecardresearch.com/beacon.js' %3E%3C/script%3E"));
  </script>
  <script type="text/javascript">
      try {
          var comscore_data = {
                  c1:2,
                  c2:6723616,
                  c3:"",
                  c4:"",
                  c5:"south-africa",
                  c6:"",
                  c15:"",
                  options: {
                      url_append: "comscorekw=south-africa"
                  }
          }
          COMSCORE.beacon(comscore_data);
      } catch(e) {
      }
  </script>
  <noscript>
  <img src="http://b.scorecardresearch.com/p?c1=2&amp;c2=6723616&amp;c3=&amp;c4=&amp;c5=south-africa&amp;c6=&amp;c15=&amp;cj=1" />
  </noscript>
  <!-- End comScore Tag -->
  <!-- START Parse.ly -->
  <div id="parsely-root" style="display: none">
    <div id="parsely-cfg" data-parsely-site="huffingtonpost.co.za"></div>
  </div>
  <script>
  (function(s, p, d) {
    window.PARSELY = window.PARSELY || {};
    window.PARSELY.visitorCookieTimeoutSecs = (60 * 60 * 24 * 365); // 1 year
    var h=d.location.protocol, i=p+"-"+s,
        e=d.getElementById(i), r=d.getElementById(p+"-root"),
        u=h==="https:"?"d1z2jf7jlzjs58.cloudfront.net"
        :"static."+p+".com";
    if (e) return;
    e = d.createElement(s); e.id = i; e.async = true;
    e.src = h+"//"+u+"/p.js"; r.appendChild(e);
  })("script", "parsely", document);
  </script>
  <!-- END Parse.ly -->
  <!-- START Nielsen Online SiteCensus V6.0 -->
  <!-- COPYRIGHT 2012 Nielsen Online -->
  <script type="text/javascript" src="//secure.imrworldwide.com/v60.js"></script>
  <script type="text/javascript">
   var pvar = { cid: "f2", content: "0", server: "secure" };
   var trac = nol_t(pvar);
   trac.record().post();
  </script>
  <noscript>
   <img src="//secure.imrworldwide.com/cgi-bin/m?ci=f2&amp;cg=0&amp;cc=1&amp;ts=noscript"
   width="1" height="1" alt="" />
  </noscript>
  <!-- END Nielsen Online SiteCensus V6.0 -->
  <!-- BEGIN EFFECTIVE MEASURE CODE -->
  <!-- COPYRIGHT EFFECTIVE MEASURE -->
  <script type="text/javascript">
    (function() {
      var em = document.createElement('script'); em.type = 'text/javascript'; em.async = true;
      em.src = ('https:' == document.location.protocol ? 'https://za-ssl' : 'http://za-cdn') + '.effectivemeasure.net/em.js';
      var s = document.getElementsByTagName('script')[0]; s.parentNode.insertBefore(em, s);
    })();
  </script>
  <noscript>
    <img src="https://za.effectivemeasure.net/em_image" alt="" style="position:absolute; left:-5px;" />
  </noscript>
  <!--END EFFECTIVE MEASURE CODE -->
```
