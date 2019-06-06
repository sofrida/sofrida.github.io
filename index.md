---
layout: default
---

We've found thousands of vulnerabilities in mobile apps that can leak sensitive data and manipulate back-end data over several months of research.

More than 2,000 vulnerable apps have been identified, and we have sent detailed reports of vulnerabilities to each developer of the app and are waiting for a response.

We expect all vulnerabilities to be fixed, and we will release a list of all vulnerable apps within 30 days

Also, our research is now submitted to Defcon Talks and waiting for response.

If our research is adopted, you will find technical details at the Defcon Conference.


## Q&A

## What is soFrida?

ddddd

## How can Developers know if the app is vulnerable or not?

We've sent email with bug report details.

If they didn't get an email from us, the app is not vulnerable with bugs we've found.



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
