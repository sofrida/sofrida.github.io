---
layout: page
---


soFrida is an automatic analysis tool, which breakdown vulnerabilities in the moblie cloud app.

We have analyzed 4 million Android apps and found 2,700+ vulnerable apps that can leak sensitive personal information data and manipulate back-end data.

Today(June 8, 2019 09:00 KST), we sent a notification to each developer of the vulnerable apps. We will release the list of vulnerable apps through the site after 2 weeks, and the detailed report will be available in another 30 days after the name of the app is relaesed.

We've demonstrated our tool soFrida at DEFCON 27 DEMO LABS and downloading tool is available now at our github page

Github : [LINK](https://github.com/june5079/soFrida)

Slide  : [LINK](https://www.slideshare.net/june5079/sofrida-dynamic-analysis-tool-for-mobile-apps-with-cloud-backend)


<!--<div id="gh-latest"></div>-->
<!-- <div class="posts">
  {% for post in site.posts %}
    <article class="post">

      <h1><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></h1>

      <div>
        <p class="post_date">{{ post.date | date: "%B %e, %Y" }}</p>
      </div>

      <div class="entry">
        {{ post.excerpt }}
      </div>

      <a href="{{ site.baseurl }}{{ post.url }}" class="read-more">Read More</a>
    </article>
  {% endfor %}
</div> -->

<!-- <script>
    /*var xmlhttp = new XMLHttpRequest();
    var userMetaURL = "https://api.github.com/users/yourusername/events";
    xmlhttp.onreadystatechange = function () {
      if (this.readyState == 4 && this.status == 200) {
        var userMeta = JSON.parse(this.responseText);

        for(let i = 0; i < userMeta.length; i++){
          if(userMeta[i].type == 'PushEvent'){
            var commitURL = userMeta[i].payload.commits[0].url.replace('api.', '').replace('repos/', '').replace('commits', 'commit');
            var projectURL = userMeta[i].repo.url.replace('api.', '').replace('repos/', '');
            var commitMessage = userMeta[i].payload.commits[0].message;
            var projectName = userMeta[i].repo.name;
            var commitDate = new Date(userMeta[i].created_at).toDateString();

            var ghLatestActivity = '<a class="chip yellow lighten-2">Latest commit</a>"' + '<a class="text-link" href="' + commitURL + '"' + '>' + commitMessage + '</a>' + '" at ' + '<a class="text-link" href="' + projectURL + '"' + '>' + projectName + '</a>' + ' on ' + commitDate + '.';

            document.getElementById("gh-latest").innerHTML = ghLatestActivity;
            break;
          }
        }
      }
    };
    xmlhttp.open("GET", userMetaURL, true);
    xmlhttp.send();*/
  </script> -->
