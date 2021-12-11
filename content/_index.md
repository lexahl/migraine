---
title: "my migraines"
subtitle: "a chatbot for the conversation that I am too tired to have"

description: "I designed this chatbot to assist me with talking about my migraines. I've had migraines for more than 9 years now. They started when I was 15. I usually get a couple of migraines each week. I know you can't see my migraines, so I guess that it is hard to understand what they are like and how having migraines affects me.<br><br>"

images:
  - img/head.gif
show_action_link: true
action_link: https://lexahl.github.io/migraine/chatbot/
action_label: "I don't need to explain this all to you, but I want to &rarr;"
action_type: text # text, button
type: home
---

  <script>
    $(function(){
        $('#blur').okshadow({
          color: 'black',
          xFactor: 5000,
          yFactor: 5000,
          textShadow: true,
          transparent: true
        });
    });
  </script>
  <style type="text/css">
    body {
    }


    .intro_text{
      padding-top: 25%;
      width: 50%;
      margin: auto;
      font-size: 12pt;
      line-height: 28pt;
      font-family: sans-serif;
    }

a:link {
  margin: 2%;
    font-variant: small-caps;  
    text-decoration: none;
    font-size: 12pt;
    font-family: sans-serif;
    color: black;
}
a:visited {
    font-variant: small-caps;  
    font-size: 12pt;
    font-family: sans-serif;
    color: black;
    text-decoration: none;
}

a:hover {
    color: white;
}    

a#blur:link{
    font-size: 22pt;
    font-family: sans-serif;
    margin-left: 35% !important;    
    white-space: nowrap;
    }

a#blur:visited{
    font-size: 20pt;
    font-family: sans-serif;     
    white-space: nowrap;
    }

a#blur:hover{
    }        

.menu{
      margin-top: 25%;
      padding-top: 25%;	      	
      width: 90%;
      font-size: 10pt;
      line-height: 16pt;
      font-family: sans-serif;
}

@media only screen and (max-width: 768px) {

	a#blur:link{
    font-size: 14pt;
    font-family: sans-serif;
    margin-left: 5% !important;    
    white-space: nowrap;
    }

}