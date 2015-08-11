---
---
<html>
<head>
  <title>CompSocs UK</title>
  <link href='http://fonts.googleapis.com/css?family=Gilda+Display|Vollkorn:700' rel='stylesheet' type='text/css'>
  <link rel="stylesheet" href="style.css" type="text/css" media="screen" />
</head>
<body>
  <h1>CompSocs UK</h1>

  <p>A number of computer science societies at UK universities who use
  IRC have resurrected the shared channel <tt>#compsoc-uk</tt> on
  freenode as a place for friendly discussion.</p>

  <p>The channel is <tt>#compsoc-uk</tt>
  on <tt>irc.freenode.net</tt>. This channel has slightly uncertain
  status, so the channel <tt>#compsoc<b>s</b>-uk</tt> (plural) on
  freenode has been registered as a backup.</p>

  <h3>Webchat</h3>

  <p>If you do not have a convenient IRC client, you can
  use <a href="http://webchat.freenode.net/?channels=compsoc-uk">freenode
  webchat</a> to connect to the channel.</p>

  <h3>Bot</h3>

  <p>There is (at least one) utility bot in the channel. One of the
    functions it provides is intended to make it easy to check which
    university and society someone is from (as this question comes up
    often).</p>

  <p>Type <tt>!whois &lt;nick&gt;</tt> to find the description a user
    has set for themselves.</p>

  <p>Type <tt>!whois.set &lt;description&gt;</tt> to set the
  description for yourself.</p>

  <h3>Grand Tech Meetup</h3>

  <p>There are currently plans underway to organise a meet up for the channel's community. This would involve a weekend of talks, roundtable discussions, maybe mini hacks and social events.</p>

  <p>Dates are not decided upon yet. Location is potentially going to be York, although depending on the amount of interest for the event that could also be subject to change.</p>

  <p><a href="https://goo.gl/k56ADB">Register your interest here</a></p>
  <p><a href="https://goo.gl/3tVqnF">Propose a talk here</a></p>
  <p><a href="https://goo.gl/fHTR09">Request a session here</a> <a href="https://goo.gl/RDGtBY">(results)</a></p>

  <h3>Known Societies</h3>

  <p>These societies have been seen in the channel:</p>
  <ul>
    {% assign socs = site.data.societies | sort: 'university' %}
    {% for society in socs %}
    <li><a href="{{ society.url }}">{{ society.title }}</a></li>
    {% endfor %}

  </ul>

  <h3>Future plans</h3>
  <p>Hopefully, various group activities will be organised among the
  people in <tt>#compsoc-uk</tt>. Perhaps when this becomes a proper
  website, those events will be listed here.</p>

  <h3>This Website</h3>

  <p>If you'd like to improve this website, it is hosted on GitHub pages, in the repository
  <a href="http://github.com/CompSocs/compsocs.github.io">Compsocs/compsocs.github.io</a>. Send
  a pull request, and ping <tt>qlkzy</tt> (among others) in the
  channel if it seems to be being ignored. Reputable individuals will
  probably be given commit access.</p>

</body>
</html>
