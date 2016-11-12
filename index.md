---
---

<html>
    <head>
        <title>Cognicast advice</title>
        <style>
            body
                {
                    margin:1em auto;
                    max-width:40em;
                    padding:0 .62em;
                    font:1.2em/1.62em sans-serif;
                }
            h1, h2, h3 { line-height:1.2em; }
            h1 { border-bottom: 1px solid #aaa; }
            @media print
                {
                    body
                        {
                            max-width:none
                        }
                }
        </style>    
    </head>
    <body>
        {% capture content %}{% include README.md %}{% endcapture %}{{ content | markdownify }}
        <div style="position: fixed; top: 1em; right: 1em">
            [ <a href="https://github.com/Biserkov/cognicast-advice/edit/master/README.md" title="Edit on GitHub">edit</a> ]
        </div>
    </body>
</html>